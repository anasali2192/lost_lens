# LostLens
AI-Powered Lost and Found Platform

## Project Overview
LostLens is a web-based platform designed to help users report, search for, and recover lost items on a university campus. Students and teachers currently rely on notice boards and WhatsApp groups, which are inefficient. LostLens uses AI to automatically match lost and found items, track claims, and even uses a smart camera to detect abandoned items.

## Project Purpose
The project aims to make the lost-and-found process easier, more organized, and accessible through a centralized platform. By using AI (CLIP for images and Sentence-BERT for text), we can automatically match items and notify owners instantly, reducing the number of permanently lost items.

## Project Team
- Member 1: Anas Ali Jafri
- Member 2: Sheeza Sajjad
- Member 3: Hira Nasir

## Key Features
- Web App: Role-based access (Student, Teacher, Admin), posting lost/found items with photos, and a claim status tracker.
- AI Matching: Automatic image and text matching with a confidence score to notify owners via email.
- Smart Camera: Uses YOLO and ByteTrack to detect abandoned items in a designated room and alerts the admin dashboard.
- Admin Dashboard: Manage users, posts, claims, and view camera alerts.

## Technologies Used
- Frontend: Next.js, Bootstrap CSS
- Backend: Next.js API routes, NextAuth.js
- Database: Supabase PostgreSQL
- Storage & Email: Cloudinary (photos), EmailJS or Resend
- AI & Camera: Python, FastAPI, Hugging Face Transformers, PyTorch, OpenCV, Ultralytics YOLO, ByteTrack

## Project Type
Final Year Project (FYP) - BS Computer Science
Product Owner / Supervisor: Sir Ahmad Arsalan
