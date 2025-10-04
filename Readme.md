# Echo Vision - AI Companion for the Visually Impaired

Echo Vision is a voice-only AI companion app designed to empower visually impaired users by providing real-time object identification, interactive queries, and emergency assistance—all while protecting user privacy.

## Problem Statement
Track 2: The Accessibility Technology Gap. Over 285 million people worldwide live with visual impairments. Existing assistive technologies are often expensive, impractical, or lack the intelligence to provide a truly empowering experience. Our project directly tackles this by offering a free, software-based solution.

## Features
-   **Real-Time Object Naming:** Uses an on-device ML model to identify objects through the phone's camera and announces them via audio.
-   **"Smart Memory" & Interactive Search:** The app remembers recently seen objects and their general location, allowing the user to ask "Where is my cup?"
-   **Emergency "Help Me" Command:** A voice-activated command that sends an SMS with the user's GPS location to a pre-configured emergency contact.
-   **Privacy-First by Design:** All visual processing happens 100% on-device. No images or videos are ever stored or sent to a cloud server.

## Tech Stack
-   **Framework:** Flutter (for rapid, cross-platform development)
-   **Object Detection:** Google ML Kit (for fast, on-device inference)
-   **Voice Input/Output:** Flutter TTS & Speech-to-Text libraries
-   **Permissions:** Permission Handler for managing camera/microphone access securely.

## Setup Instructions
1.  Clone the repository:
    ```
    git clone https://github.com/DIVYA-27J/Echo-Vision.git
    ```
2.  Navigate to the project directory:
    ```
    cd Echo-Vision
    ```
3.  Install dependencies:
    ```
    flutter pub get
    ```
4.  Connect a device and run the app:
    ```
    flutter run
    ```

## Team
-   [Your Name] - Team Leader & Developer
-   [Teammate Name 2] - [Role]
-   [Teammate Name 3] - [Role]

## License
This project is licensed under the MIT License.
