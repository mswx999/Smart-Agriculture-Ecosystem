# Smart-Agriculture-Ecosystem

Smart AgriTech Platform
Introduction

Smart AgriTech Platform is a unified digital ecosystem designed to modernize agriculture using technology. It integrates IoT-based monitoring, AI-driven crop advisory, weather analytics, and a farmer-centric marketplace into a single platform.

The platform addresses major agricultural challenges such as climate uncertainty, lack of real-time data, dependency on middlemen, and limited access to modern tools. By providing data-driven insights and direct market access, it empowers farmers to make smarter decisions, improve productivity, and increase profitability while promoting sustainable farming practices .

Key Features
IoT-Based Crop Monitoring
Real-time tracking of soil conditions, temperature, and crop health
AI Crop Advisory System
Smart recommendations for irrigation, fertilization, and pest control
Weather Analytics
Accurate forecasts and alerts to reduce climate-related risks
Advisory & Assistance Module
Regional language articles, government scheme connectivity, and expert guidance
Pesticides & Seeds Support
Recommendations and access to quality agricultural inputs
Marketplace Integration
Direct farmer-to-buyer connection ensuring fair pricing
Equipment Acquisition Module
Renting or purchasing farming equipment easily
Logistics & Supply Chain
Efficient transportation and delivery support
Government MSP & Policy Connect
Awareness and integration with government pricing and schemes
Crop Insurance Support
Assistance with insurance policies and claims
User-Friendly Dashboard
Centralized control panel with insights, reports, and alerts

Smart Agriculture Technology Platform providing IoT monitoring AI crop advisory weather analytics and marketplace support for modern farming

 Tech Stack
Frontend HTML CSS JavaScript
Authentication Firebase Authentication Email and Google
Database Cloud Firestore
Deployment Vercel

 Setup

1 Install dependencies
npm install

2 Configure Firebase
cp .env .env.local

Edit .env.local with your Firebase credentials from console.firebase.google.com

3 Local development
npm run dev

4 Deploy to Vercel
npx vercel

Add Firebase environment variables in Vercel Dashboard Settings Environment Variables
Project Structure

├── index.html Single page application including landing authentication and dashboard
├── style.css Professional light theme styling
├── app.js Firebase Authentication Firestore and dashboard logic
├── build.js Build script for environment variable injection
├── package.json Project configuration
├── vercel.json Deployment configuration
├── .env Environment variable template
├── .env.local Actual environment variables not committed
└── .gitignore Git ignore rules

Features

Landing page with hero section features workflow solutions technology stack and testimonials
Authentication using email password and Google sign in
Three step onboarding including account setup personal details and farm configuration
Dashboard with crop monitoring weather updates marketplace disease detection reports and settingsase detection reports and settings
