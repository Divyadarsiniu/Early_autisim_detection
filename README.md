# Early_autisim_detection
 Autism Spectrum Disorder (ASD) is a developmental condition that affects how people communicate, interact, and behave. It's characterized by persistent challenges in social interaction and communication, as well as restricted and repetitive patterns of behavior, interests, or activities. The "spectrum" in ASD refers to the wide range of ways autism can manifest, with varying degrees of severity.
 # Technologies used 
 This project is built with:
>Vite

>>TypeScript
>>>React
>>>>shadcn-ui
>>>>>Tailwind CSS

# Dependency installation
npm install

# to run the program
npm run dev

you will get a local host like this
 > http://localhost:8080/

 # The Welcome page 
 Include The get started button that navigates to the name place The Audisense uses machine learning Front Page Description – Early Eye Detection for Autism
The front page of the Early Eye Detection for Autism system is a graphical user interface (GUI) designed using Tkinter in Python. It serves as the main entry point for users to interact with the system, allowing easy access to real-time behavioral analysis tools.

The interface presents a clean, user-friendly layout with the project title prominently displayed, and provides buttons to begin the detection process or exit the application. When users click “Start Detection”, the system activates the webcam and begins real-time analysis using machine learning models from MediaPipe, which perform:

Facial landmark tracking for expression and eye movement

Eye gaze estimation to monitor attention and social engagement

Pose detection to observe physical posture and movement

Hand gesture recognition for non-verbal behavior analysis

This front page is designed to be intuitive for researchers, clinicians, or guardians who may want to observe behavioral cues in children, serving as a foundational interface for early screening support in autism diagnosis.
![Screenshot 2025-05-11 212732](https://github.com/user-attachments/assets/41b7febe-4127-4b40-8e5c-7d15f6745f96)
# the name page
Name Page – Early Eye Detection for Autism
The name page is the initial interface screen that welcomes users to the application. It typically appears before the main functionality begins and is designed to introduce the project's identity and purpose in a visually appealing way.

🔹 Key Features:
Project Title Displayed Prominently:

"Early Eye Detection for Autism"

Often styled with large fonts and centered alignment to capture attention.

Subheading or Tagline (Optional):

A short phrase such as "An AI-based tool for early behavioral screening"

Simple Background and Layout:

Clean design using Tkinter with optional color themes or logos.

Proceed Button:

A “Start” or “Next” button that transitions the user from the name page to the main front page or detection interface.


![Screenshot 2025-05-11 212747](https://github.com/user-attachments/assets/94fa56fc-17be-436a-ad5c-beaaccb614de)
 # the age page
 Age Page – Early Eye Detection for Autism
The age page is a key interface that prompts the user to input the age of the child before beginning behavioral analysis. Age is an important contextual factor when analyzing signs of autism, as expected behaviors vary significantly across developmental stages.

🔹 Key Features:
Age Input Field:

A simple textbox or dropdown where the user enters the child’s age (in years or months).

Validation Logic:

Ensures that the input is a valid number and within a realistic range (e.g., 1 to 12 years).

"Continue" Button:

Proceeds to the detection module after age is entered.

The age input can optionally be used to customize model sensitivity or reporting.
![Screenshot 2025-05-11 212816](https://github.com/user-attachments/assets/8f60e50d-4ec3-4dec-91f4-8d3af289e5d5)


# the Video upload page
Video Upload Page – Early Eye Detection for Autism
The video upload page allows users to upload pre-recorded videos of children for offline behavioral analysis. This feature is especially useful when live camera access is not possible or when reviewing past behavioral sessions.

🔹 Key Features:
Upload Button:

Opens a file dialog to select a video file (e.g., .mp4, .avi, .mov).

File Type Validation:

Ensures only supported video formats are uploaded.

Preview Section (Optional):

Shows a thumbnail or first frame of the uploaded video for confirmation.

“Start Analysis” Button:

Triggers the backend pipeline to analyze the uploaded video using machine learning models for:

Eye gaze tracking

Facial expressions

Gesture recognition

Pose estimation

Progress Indicator or Loading Animation:

Informs the user that the analysis is running.
![Screenshot 2025-05-11 212835](https://github.com/user-attachments/assets/92e0d986-ec49-4cdc-8faf-e16ea3b9a8ef)

# Analysis page 
Analysis Page – Early Eye Detection for Autism
The Analysis Page is the core results interface where behavioral data extracted from live or uploaded video is presented to the user. It acts as a feedback screen, summarizing the key findings from the AI-powered analysis pipeline.

🔹 Key Features:
Visual Overlays:

Displays the processed video with overlays for:

Facial landmarks

Eye gaze direction

Body pose

Hand gestures

Behavioral Metrics Panel:

Summarized data such as:

Average eye contact duration

Gaze fixation ratio

Expression variability

Gesture frequency

Posture alignment or abnormalities

Age Context Integration:

Adjusts interpretation or highlights based on the child’s age entered previously.

![Screenshot 2025-05-11 212927](https://github.com/user-attachments/assets/07ac4663-292b-4ec8-97d4-f8137e979d2a)




![Screenshot 2025-05-11 212940](https://github.com/user-attachments/assets/5119a219-c044-42f1-b79d-6079a27c3a52)


