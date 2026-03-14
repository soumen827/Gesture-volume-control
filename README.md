# Gesture-volume-control
🚀 About The Project
Gesture Control transforms your ordinary webcam into a touchless, hands-free input device. Powered by Google's MediaPipe neural network — running entirely on your local CPU — it detects 21 hand landmarks in real time and maps natural hand shapes and motions to system-level actions: moving the mouse, clicking, adjusting volume, switching windows, and more.

The problem it solves:

Traditional input devices create friction. Gesture Control removes the physical barrier between you and your computer. Whether you're presenting, cooking, exercising, or simply exploring the frontier of Human-Computer Interaction, you can control your PC without touching anything.

Who is it for?


🧑‍💻 Developers and makers exploring computer vision and HCI

♿ Users who benefit from accessibility-friendly, touch-free PC control

🎓 Students learning real-time AI/CV application development

🖥️ Presenters who want hands-free slide and window management

Features
Feature	Description
🖱️ Smooth Mouse Control	Move the cursor naturally using only your index finger — exponential smoothing eliminates jitter
🤏 Left Click	Pinch your thumb and index finger together to click
✌️ Right Click	Peace-sign (index + middle) triggers a right-click
🔊 Real-Time Volume Control	Raise or lower your open hand to set system volume — hand height maps directly to volume level
🔄 Window Switching	Swipe your open hand left or right to cycle through windows with Alt+Tab / Alt+Shift+Tab
🖥️ Show Desktop	Three-finger gesture instantly triggers Win+D
📋 Task View	Index + Pinky (rock sign) opens Win+Tab Task View
⏸️ Pause / Resume	Hold a fist for 1.5 seconds to freeze all gesture controls — hold again to resume
🎨 Live HUD Overlay	Semi-transparent heads-up display with active gesture badge, FPS counter, volume bar, and fading action log
⚡ Zero-Latency Design	pyautogui.PAUSE = 0 + frame-level gesture dispatch — actions fire within the same frame cycle
📴 Fully Offline	No API keys, no cloud endpoints, no telemetry — all inference runs locally on CPU
🚀 One-Click Launcher	START.bat installs all dependencies and launches the app automatically
