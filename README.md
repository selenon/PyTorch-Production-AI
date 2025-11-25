# PyTorch Production AI

A practical guide to building and deploying AI models with PyTorch in production environments.

## About This Project

This repository contains the companion code for building production-ready AI applications with PyTorch. Originally featured in a technical demo covering the complete pipeline from model training to mobile deployment.

## Quick Start

### Model Development
The core model training pipeline is available as a Jupyter notebook:
```python
# Train sentiment analysis model on movie reviews
Build_an_AI_Startup_with_PyTorch.ipynb
```

### Mobile Integration
The Android application demonstrates model deployment:
- Import project in Android Studio
- Dependencies auto-configured via Gradle
- TensorFlow Lite for mobile inference
- Place `.pb` models in `app/src/main/assets/`

## Tech Stack

**Core AI**
- PyTorch for model development
- ONNX for model interoperability
- TensorFlow Lite for mobile deployment

**Mobile & Backend**
- Android native development
- Firebase for cloud services
- PayPal for payment integration
- DialogFlow for conversational AI

## Development Notes

This project demonstrates a complete workflow:
1. Model training with PyTorch
2. Conversion to ONNX format
3. Export to TensorFlow protobuf
4. Mobile deployment with TensorFlow Lite
5. Full-stack integration with backend services

The current implementation focuses on sentiment analysis using movie reviews, but the architecture supports various AI applications.

## Dependencies

All major dependencies are managed through Gradle. Key requirements include:
- PyTorch 1.0+
- TensorFlow Lite
- Firebase SDK
- Android Studio 3.0+
