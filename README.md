# Virtual Teacher: Multi-Implementation AI Educational Assistant

## Project Overview

Virtual Teacher is an AI-powered educational assistant designed to provide personalized Computer Science instruction. The project features three distinct implementations:

1. **Web Implementation** - A fully functional web application with RAG-powered question answering
2. **Unreal Engine with Convai** - A digital human representation using Metahuman and Convai plugin
3. **Integration Attempt** - Experimental WebSocket bridge connecting the RAG backend with Unreal Engine

This project demonstrates advanced AI integration techniques, 3D character creation, and multiple approaches to educational technology implementation.

## Key Features

### Web Implementation
- **Voice and Text Interaction**: Support for both text input and voice recording
- **RAG System**: Retrieval-Augmented Generation for accurate, context-aware responses
- **Professor's Voice**: Text-to-speech using ElevenLabs voice cloning technology
- **Educational Focus**: Specialized for Computer Science education with code formatting
- **Responsive Design**: Works across desktop and mobile devices

### Unreal Engine with Convai
- **Digital Professor**: Photorealistic Metahuman representation of Professor Soule
- **Facial Capture**: Created using Poly Cam and refined in Blender
- **Animation System**: Realistic facial expressions and animations
- **Conversational AI**: Basic question answering via Convai plugin
- **Visual Presence**: Immersive visual representation for enhanced engagement

### Integration Attempt
- **WebSocket Communication**: Real-time messaging between systems
- **Audio Processing Bridge**: Bidirectional audio transmission
- **Custom Message Protocol**: Structured data exchange format
- **Animation Control**: Attempted synchronization with facial expressions
- **State Management**: System status coordination between platforms

## Technology Stack

### Web Implementation
- **Frontend**: React, Vite, Tailwind CSS
- **Backend**: FastAPI, SQLAlchemy, PostgreSQL
- **AI Integration**: OpenAI (GPT, Embeddings, Whisper), ElevenLabs
- **Vector Database**: ChromaDB for embedding storage and retrieval
- **Deployment**: Docker, Docker Compose

### Unreal Engine
- **Character Creation**: Metahuman Creator, Poly Cam, Blender
- **Game Engine**: Unreal Engine 5
- **AI Plugin**: Convai for conversational capabilities
- **Animation**: Live Link Face, Animation Blueprints
- **Audio**: Unreal Engine audio components

### Integration Attempt
- **Communication**: WebSockets, JSON messaging
- **Bridge Scripts**: Python scripts for communication management
- **Audio Processing**: Whisper for transcription, ElevenLabs for synthesis
- **Message Handling**: Conversation manager for coordinating systems

