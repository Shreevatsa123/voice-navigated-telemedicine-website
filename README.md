# Enhancing Telemedicine Website Accessibility with Voice Navigation

## **Disclaimer: Lost Source Code**

Unfortunately, the source code for this project has been **permanently lost** due to an accidental deletion during a system cleanup. At the time, my proficiency with version control systems like Git and GitHub was limited, and backups were not adequately maintained. Recovery efforts were unsuccessful.

I am **deeply saddened** by this loss, as this project represented a significant effort and achievement in accessible web design. The primary proof of the project's existence and functionality are the associated research paper and the video demonstration linked below.

## Overview

This project focused on improving the accessibility and user experience of telemedicine websites, specifically for users with visual impairments. I developed and integrated a voice navigation system that allows users to interact with the website using spoken commands and receive audio feedback, eliminating the need for traditional input devices like keyboards and mice.

My goal was to create a more inclusive digital healthcare experience, aligning with universal design principles and addressing the challenges faced by visually impaired individuals when navigating complex web interfaces.

## Problem Statement

Visually impaired users often encounter significant barriers when accessing web-based services, including telemedicine platforms. Standard navigation methods relying on visual cues, mouse interactions, and keyboard inputs can be difficult or impossible to use. This limits their ability to independently access essential healthcare services like scheduling appointments, consulting doctors, or retrieving medical information online.

## My Solution: Voice Navigation System

To address these challenges, I implemented a voice navigation system directly integrated into the web browser. This system enables users to:

1.  **Control the website using voice commands:** Users can speak predefined commands to perform actions.
2.  **Receive audio feedback:** The system provides spoken responses and reads out content, confirming actions and providing necessary information.

The system was built using web technologies, leveraging the WebSpeech API for speech recognition and synthesis.

![System Architecture/Concept Diagram](https://placehold.co/600x300/cccccc/ffffff?text=Placeholder:+System+Concept+Diagram)
*(Optional: Add a diagram illustrating the voice navigation concept or architecture)*

### Core Components:

* **Speech Recognition Engine:** Interprets user voice commands using deep learning models and acoustic modeling (mapping sounds to phonetic units).
* **Speech Grammar:** Defines the specific set of English commands the system understands (e.g., "Scroll Up", "Zoom In", "Go to Sign Up page").
* **Language Model:** Predicts word sequences and understands context to improve recognition accuracy, especially for homophones.
* **Decoding:** Uses algorithms like the Viterbi algorithm to determine the most likely sequence of words spoken by the user.
* **Speech Synthesis Engine:** Generates computerised voice output to read website content or provide feedback to the user.

## Key Features Implemented

The voice navigation system allowed users to perform various actions, including:

* **Scrolling:** "Scroll Up", "Scroll Down"
* **Zooming & Font Size:** "Zoom In", "Zoom Out", "Increase Font Size", "Decrease Font Size", "Default Window Size"
* **Page Navigation:** "Go to [page name]" (e.g., "Go to the Video Consult page", "Go to homepage")
* **Content Interaction:** "Read Content", "Find [text]"
* **General Navigation:** "Go Up", "Go Down", "Go Left", "Go Right", "Select"
* **Form Filling:** Voice-based input for forms (demonstrated on Sign Up page).
* **Searching:** "Search [item/doctor]"

![Screenshot of a Key Feature](https://placehold.co/600x400/cccccc/ffffff?text=Placeholder:+Screenshot+of+Feature+in+Action)
*(Optional: Add a screenshot from the video demo showing a feature like voice scrolling or form filling)*

## Technology Stack

* **Frontend:** JavaScript
* **Web APIs:** WebSpeech API (SpeechGrammar, SpeechRecognition, SpeechSynthesis)
* **Speech Recognition Core:** Deep Learning Models (e.g., DNNs, HMMs, RNNs), Acoustic Modeling, Language Modeling (N-grams, RNNs), Viterbi Algorithm for decoding.

## Evaluation and Results

Usability testing was conducted with 15 visually impaired participants to evaluate the system's effectiveness across different browsers (Chrome, Edge, Firefox, etc.). Key metrics included:

* **Task Completion Rate / Accuracy:** Measured how often commands were correctly executed. Accuracy varied by command length (e.g., 2-word commands ~82%, 3-word ~73%, 4/5-word ~61%).
* **Error Rate:** Measured incorrect command executions.
* **Time to Complete Task:** Average time taken for each command.
* **User Satisfaction:** Assessed via questionnaires (rated on a 1-10 scale).

**Key Findings:**

* The voice navigation system significantly improved users' ability to access information and navigate the telemedicine website independently.
* Users reported high levels of satisfaction (average ratings mostly between 7.5 and 8.5 out of 10).
* Accuracy was generally good, though longer commands had slightly lower success rates.
* Performance showed some variation depending on the browser used, likely due to differences in their underlying speech recognition engines/APIs.
* Areas for improvement identified during testing included response time and initial ease of use, which improved as users became more familiar with the commands.

![Chart Showing Accuracy Results](https://placehold.co/600x300/cccccc/ffffff?text=Placeholder:+Accuracy+Results+Chart)
*(Optional: Add a chart visualizing the accuracy results, similar to Fig 2 or 3 in the paper)*

## Available Assets

While the code is gone, the following assets provide evidence and insight into the project:

1.  **Research Paper:** The detailed research paper, "[Enhancing the Experience and Accessibility of Users with Disability by Integrating Voice Navigation into a Telemedicine Website](link_to_your_paper.pdf)", which describes the concepts and findings in detail. This paper was a collaborative effort.
2.  **Video Demonstration:** Click the image below to view a video showcasing the working system I built.

[![Watch the video](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://github.com/user-attachments/assets/8451c58d-498e-445e-bf8e-1ba8b09fd944)

I hope these resources provide valuable insights into the project's methodology, implementation details, and its positive impact on accessibility for visually impaired users exploring telemedicine platforms.

*(Project based on the research paper: Kolekar, S. V., Agnihotri, S., & Rao, D. (2024). Enhancing the Experience and Accessibility of Users with Disability by Integrating Voice Navigation into a Telemedicine Website. International Journal of Mathematical, Engineering and Management Sciences, 9(4), 801-820.)*
