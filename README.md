# 🏋️ MotionIQ AI

### Real-Time Human Pose Analytics and Intelligent Fitness Coaching Platform

🚀 Live Demo: https://motioniq-ai-coach.streamlit.app/

---

## Problem Statement

Millions of people perform workouts without professional supervision. Incorrect exercise form can reduce workout effectiveness and increase the risk of injuries.

Most fitness applications can track workouts but cannot provide real-time posture correction, exercise analysis, or intelligent coaching during a workout session.

---

## Solution

MotionIQ AI is an AI-powered fitness coaching platform that combines Computer Vision, Human Pose Estimation, Large Language Models (LLMs), and Voice Feedback to provide real-time workout assistance.

Using a webcam, the system:

- Detects human body posture in real time
- Recognizes exercises automatically
- Counts repetitions and sets
- Evaluates exercise form
- Tracks workout progress
- Generates AI-powered coaching feedback
- Provides voice-guided workout assistance

The goal is to deliver a virtual personal trainer experience using AI.

---

## Key Features

### Real-Time Pose Detection
- MediaPipe Pose Landmark Detection
- Live body tracking
- Real-time skeletal analysis

### Exercise Recognition
Supported exercises:
- Squats
- Push-Ups
- Biceps Curls
- Shoulder Press
- Lunges

### Intelligent Workout Tracking
- Automatic repetition counting
- Set completion tracking
- Workout analytics
- Exercise-specific metrics

### AI Coaching System
- Groq LLM integration
- Context-aware feedback generation
- Form correction suggestions
- Motivational coaching responses

### Voice Guidance
- AI-generated coaching messages
- Text-to-Speech integration
- Hands-free workout assistance

### Data Persistence
- SQLite database
- User workout history
- Session tracking

---

## Technical Highlights

- Built a complete end-to-end AI application
- Implemented real-time human pose estimation
- Developed custom exercise-specific detection logic
- Integrated LLM-powered coaching feedback
- Designed a workout analytics pipeline
- Deployed a production-ready cloud application

---

## Tech Stack

| Category | Technologies |
|-----------|-------------|
| Language | Python |
| Frontend | Streamlit |
| Real-Time Video | Streamlit WebRTC |
| Computer Vision | OpenCV |
| Pose Estimation | MediaPipe |
| AI Coaching | Groq LLM |
| Voice Generation | gTTS |
| Database | SQLite |
| Deployment | Streamlit Cloud |

---

## Architecture

User Webcam
↓
MediaPipe Pose Detection
↓
Exercise Detection Engine
↓
Rep Counting & Form Analysis
↓
Workout Analytics
↓
Groq AI Coach
↓
Voice Feedback System
↓
Streamlit Dashboard

---

## Impact

MotionIQ AI demonstrates practical application of:

- Artificial Intelligence
- Computer Vision
- Human Pose Estimation
- Large Language Models
- Real-Time Analytics
- Voice AI
- Full-Stack Application Development
- Cloud Deployment

This project showcases the ability to design, build, and deploy a production-ready AI system that solves a real-world problem.

---

## Live Application

https://motioniq-ai-coach.streamlit.app/

---

## Author

**Gaurav Raipurkar**
