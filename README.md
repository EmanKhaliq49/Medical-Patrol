# Medical Patrol – AI-Powered Counterfeit Medicine Detection & Voice Assistant

## Table of Contents
- [Project Title](#project-title)
- [Short Description](#short-description)
- [Long Description](#long-description)
- [The Problem](#the-problem)
- [Our Solution](#our-solution)
- [Key Features](#key-features)
- [Technology & Category Tags](#technology--category-tags)
- [Getting Started](#getting-started)
- [Contribution](#contribution)
- [License](#license)
- [Contact](#contact)

## Project Title
Medical Patrol – AI-Powered Counterfeit Medicine Detection & Voice Assistant

## Short Description
Medical Patrol is an AI-powered web app that detects fake medicines using OCR and LLaMA-3, with a voice-enabled chatbot that remembers conversations using MCP.

## Long Description

### The Problem
In Africa, counterfeit medicines are a critical health crisis. Many patients unknowingly consume fake drugs, leading to failed treatments, worsening conditions, and even death. There is an urgent need for accessible, low-cost tools to verify medicine authenticity.

### Our Solution
Medical Patrol is an AI-powered web application designed to help communities quickly detect counterfeit drugs and receive medical guidance. Users simply upload a photo of a medicine's label. The app uses OCR (Optical Character Recognition) to extract text, which is then analyzed by LLaMA-3 (via Groq) to determine if the medicine may be counterfeit. If detected, the app sends email alerts to concerned authorities and automatically generates a case report using an autonomous agent.

A unique feature of Medical Patrol is its voice-enabled AI chatbot. Users can speak directly to the assistant to get answers to medicine-related queries. Speech is transcribed using Groq’s Whisper (speech-to-text) model and processed by LLaMA-3 for intelligent replies. Most importantly, the chatbot uses MCP (Model Context Protocol) to remember previous messages, making conversations feel consistent and personalized—crucial for users needing ongoing support or clarifications.

Medical Patrol is built for impact, especially in regions with limited healthcare access, low literacy rates, and high medicine fraud cases.

## Key Features
- 📷 Medicine text analysis using OCR
- 🤖 LLaMA-3 AI for authenticity checks
- 🧠 Voice chatbot with MCP context memory
- 🎤 Whisper (Groq) for speech input
- 📧 Email alerts and case logging for authorities
- 🌍 Designed for use in Africa and other underserved regions

## Technology & Category Tags
- AI/ML
- Healthcare
- Social Impact
- Computer Vision
- Speech Recognition
- Conversational AI
- MCP (Model Context Protocol)
- Groq LLaMA-3
- Whisper (Groq)
- Flask
- OCR.space API
- Email Automation
- Voice AI
- Hack for Africa

## Getting Started
To get a local copy up and running follow these simple steps.

### Prerequisites
- Python 3.x
- pip
- Virtual environment (recommended)

### Installation
1. Clone the repo
   ```bash
   git clone [https://github.com/yourusername/medical-patrol.git](https://github.com/yourusername/medical-patrol.git)
