# GaitVision

_2-D Gait Analysis for clinical use._

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [PC Development Environment Setup](#pc-development-environment-setup)
- [Deployment Artifacts](#deployment-artifacts)
- [Usage](#usage)
- [Dataset & Validation](#dataset--validation)
- [References](#references)
- [Acknowledgments](#acknowledgments)
---

## Overview

GaitVision is an Android application focused on solving the problem of lower technology access for gait analysis in developing parts of the world. It requires minimal hardware:
1. Android phone
2. GaitVision Software
3. Camera access OR stored videos

---

## Features

- Record videos in app
- Annotate input video with joint angles at each timepoint
- Generate gait score estimate using autoencoder
- Display graphs of joint angles for analysis
- Store CSV data locally for later use

---

## Technology Stack

- **Language:** Kotlin / Java
- **UI Framework:** Android XML
- **Pose Detection:** MLKit
- **Gait Score:** Autoencoder

---

## Installation

### Steps

1. Transfer the .apk file to Android compatible device
2. Open .apk file in filemanager
3. Click install and allow all

---

## PC Development Environment Setup

### Requirements

- Git
- Android Studio
- JDK 17 or compatible version

### Setup Steps

1. Clone the repository
2. Open the project in Android Studio
3. Allow Gradle to sync and install dependencies
4. Install any required SDK components if prompted
5. Select the Android app configuration
6. Run the app on an emulator or connected Android device

---

## Deployment Artifacts

The following artifacts should be included for deployment:

- Android APK file  
- Autoencoder (AE) model files  
- PCA model files  
- Linear regression scoring model  
- Sample test videos  

---

## Usage

1. Launch the app  
2. Enter a unique participant ID  
3. Enter participant height (feet and inches)  
4. Record a video or select an existing video  
5. Have the participant walk normally for at least 2 gait cycles (~5 seconds)  
6. Click "Perform Analysis"  
7. View the processed video and analysis results  
8. Select graphs as needed  
9. Export CSV data or return to the main menu  

---

## Contact

contact for clarification at nathaniel.schimpf@gmail.com

---

## References
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) by Phil Jay (Apache 2.0 License)

## Acknowledgments

- Guna Sindhuja Siripurapu
- Dr. Rita Patterson
- Dr. Mark Albert
- University of North Texas