🖐️ GestureForge
AI-Powered Gesture-Based 3D Interaction Interface
A futuristic web application that lets you draw in the air and interact with virtual 3D objects using only hand gestures and your webcam. Think Tony Stark's hologram interface meets modern web technology.
🚀 Quick Start
Option 1: Local Development (Recommended)
Clone or download these files
Use a local web server (Python 3):
Bash
Open http://localhost:8000 in your browser
Allow webcam access when prompted
Start gesturing!
Option 2: Direct File Access
Simply open index.html in a modern browser
Note: Some browsers may block webcam access when opening local files
Requirements
Modern web browser (Chrome, Edge, Firefox, Safari)
Webcam access
Desktop/laptop with sufficient GPU (for smooth 3D rendering)
🎮 How to Use
Hand Gestures
Gesture
Action
🖐️ Raise index finger
Draw - Leave glowing trails in 3D space
✊ Closed fist
Pause - Stop drawing temporarily
🤏 Pinch (thumb + index)
Erase - Clear drawing strokes
✋ Open hand
Interact - Grab and manipulate 3D objects
Drawing Tools (Left Panel)
Brush Color
Click any of 6 neon colors to change your drawing color
Colors: Green, Blue, Magenta, Pink, Cyan, Yellow
Brush Size
Adjust brush thickness (1-8px)
Larger sizes create bolder strokes
Glow Intensity
Control the neon glow effect (0-200%)
Higher values make drawings more luminous
Clear Canvas
Remove all drawing strokes instantly
Save Artwork
Download your creation as PNG
3D Object Spawning (Right Panel)
Spawn Objects
Cube - Classic geometric shape
Sphere - Smooth rounded object
Cylinder - Tall geometric form
Burst - Spawn 5 random objects at once
Interactions
Objects fall with gravity
Throw gestures apply physics
Two-hand gestures for scaling/rotation
Collision detection between objects
Clear Objects
Remove all 3D objects from scene
🎨 Design Features
Visual Style
Dark Futuristic HUD - Inspired by Tony Stark's lab interface
Neon Colors - Blue, purple, cyan accents on black background
Glassmorphism - Transparent panels with blur effects
Holographic Effects - Glowing text and UI elements
Performance
Real-time hand tracking (60 FPS)
GPU-accelerated 3D rendering
Smooth gesture recognition
Low-latency drawing system
UI Panels
Top Bar - Status info, FPS counter, hand detection indicators
Left Panel - Drawing controls and tools
Right Panel - 3D object spawning
Bottom Info - Gesture hints and instructions
🛠️ Tech Stack
Core Libraries
React 18 - UI framework
Three.js - 3D rendering engine
MediaPipe Hands - Hand gesture tracking and detection
Tailwind CSS - Styling and layout
Key Features
Hand Tracking: Real-time detection of hand landmarks and movements
3D Rendering: WebGL-based 3D object creation and manipulation
Air Drawing: Canvas-based stroke recording in 3D space
Physics Simulation: Gravity, velocity, and collision detection
Gesture Recognition: Index finger tracking, pinch detection, fist recognition
📊 Performance Metrics
Frame Rate: Displays real-time FPS (target: 60 FPS)
Hand Detection: Shows which hands are visible (L/R indicators)
Drawing Points: Trails fade naturally over time
Object Limit: Supports multiple concurrent 3D objects
🎯 Tips & Tricks
Smooth Drawing
Keep your hand steady for clean strokes
Move hand slowly for precise lines
Quick movements create longer trails
Object Manipulation
Use both hands for complex interactions
Gravity pulls objects downward (physics-based)
Objects rotate as they move
Creating Artwork
Combine drawing with 3D objects for mixed media
Use different colors for layered effects
High glow intensity creates neon aesthetic
Performance
Close other tabs for better FPS
Ensure good lighting for hand detection
Use desktop for best performance
🔧 Customization
Change Colors
Edit the colors array in GestureForge.jsx:
Javascript
Adjust Hand Tracking
Modify confidence thresholds:
Javascript
Change 3D Physics
Edit gravity and velocity values:
Javascript
⚠️ Browser Compatibility
Browser
Support
Notes
Chrome
✅ Full
Best performance
Edge
✅ Full
Excellent support
Firefox
✅ Full
Good support
Safari
⚠️ Partial
May require webcam permissions
Requirements:
WebGL support
Webcam access
JavaScript ES6+
🐛 Troubleshooting
Webcam Not Working
Check browser permissions (Settings → Privacy → Camera)
Ensure no other apps are using the camera
Try a different browser
Restart browser and try again
Hand Detection Issues
Ensure good lighting (natural light works best)
Keep hands in view and not blurred
Move hands slower for tracking stability
Check distance from camera (30-100cm optimal)
Low FPS
Close other browser tabs
Reduce brush size or glow intensity
Lower object count
Restart browser
Drawing Not Appearing
Raise index finger more distinctly
Check if hand is detected (look for hand indicators)
Verify brush color is visible
Try clearing canvas and restarting
🎓 Educational Use
This project demonstrates:
Computer Vision - Hand landmark detection
3D Graphics - WebGL and Three.js rendering
Gesture Recognition - Real-time hand pose analysis
Physics Simulation - Gravity and collision detection
Performance Optimization - Real-time constraint solving
📝 Features Implemented
✅ Real-time hand tracking with MediaPipe
✅ Air drawing with glowing trails
✅ 3D object spawning and interaction
✅ Gesture-based controls (raise, pinch, close)
✅ Physics simulation with gravity
✅ Neon futuristic UI design
✅ Multiple brush colors
✅ Adjustable glow and brush size
✅ Save artwork functionality
✅ FPS monitoring
✅ Responsive design
✅ Holographic visual effects
🎬 Future Enhancements
Potential additions:
Hand gesture library (thumbs up, peace sign, etc.)
Sound effects and ambient music
Multiplayer collaboration
AR overlay on real world
More complex 3D models
Animation presets
Color picker
Texture mapping
Export to 3D formats
📄 License
This project is provided as-is for educational and personal use.
🙏 Credits
MediaPipe - Hand tracking and gesture recognition
Three.js - 3D graphics rendering
React - UI framework
Tailwind CSS - Styling
💡 Questions?
Refer to the in-app instructions (bottom of screen) or review the gesture guide above. Start with simple hand movements and gradually explore more complex interactions!
Enjoy creating with GestureForge! 🚀✨