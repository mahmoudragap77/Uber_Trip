# Uber Trip 🚗

An Android application built with **Kotlin and Jetpack Compose** to estimate trip fares based on distance, travel time, and traffic conditions.

## ✨ Features
- Animated start screen with car horn sound.
- Enter trip distance and travel time.
- Choose traffic conditions (0%, 5%, or 10%).
- Calculate and animate the estimated fare in EGP.
- Navigation using Navigation 3.
- Automated UI journey testing.

## 🛠️ Tech Stack
- Kotlin
- Jetpack Compose & Material 3
- Navigation 3
- Kotlin Serialization
- Compose Animation APIs

🧪 Automated Testing with Journey Test

The project includes an Android journey test that verifies the main user flow:

Start the application.

1-Enter a trip distance of 50 km.

2-Enter a travel time of 10 minutes.

3-Select a traffic condition.

4-Calculate and verify the estimated fare.

The expected fare for a 50 km trip taking 10 minutes with no traffic surcharge is 393 EGP.
<img width="1615" height="558" alt="Screenshot 2026-10-19 093400" src="https://github.com/user-attachments/assets/3d381d3b-aab5-40c2-afba-3130cdfe2b98" />

