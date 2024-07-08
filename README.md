# Parkia_app
# Early Detection of Parkinson's Disease - Flutter Application
This Flutter application aims to aid in the early detection of Parkinson's disease through two primary features: hand drawing and speech analysis.

# Features
## Hand Drawing
The user is prompted to draw three specific shapes: a spiral, a meander, and a circle. These shapes are displayed on the screen one at a time, and the user must draw each shape within the app. The accuracy and characteristics of these drawings are analyzed as part of the detection process.

## Speech Analysis
After completing the drawing tasks, the user is asked to record their voice while reading a text displayed on the screen. The speech recording is analyzed for signs indicative of Parkinson's disease.

# Widgets and Libraries Used
CustomPaint: Utilized for rendering custom shapes and capturing user drawings.
RepaintBoundary: Ensures efficient redrawing of only the necessary parts of the screen.
SnackBar: Provides user feedback and notifications.
Audio Recorder: Powered by the Record library, this class handles the recording of user speech.
