# Unity Version
Unity 6.3 LTS (6000.3.8f1)

# Project template
3D (URP)

# Required Unity Hub Modules
Android Build Support
 Android SDK & NDK Tools<br>
 OpenJDK<br>
<br>
No other build modules are required.

# Meta XR SDK
(Have to be opened via the Unity Asset Store then the link opened and downloaded in Unity)
Meta XR all in one SDK
Meta XR Simulator

# Version Control Settings (Important for Git)
Project Settings → Version Control<br>
Mode: Visible Meta Files<br>
Project Settings → Editor<br>
Asset Serialization Mode: Force Text<br>

# XR / VR Configuration (Meta Quest 3)
Project Settings → XR Plug-in Management<br>
Enable OpenXR (Android)<br>

OpenXR settings =>
Enable Meta Quest support<br>
Enable Quest controller profile<br>
Enable hand tracking<br>
Android Player Settings (Quest 3)<br>

Project Settings → Player → Android<br>
Minimum API Level: Android 10 (API 29) or higher<br>
Target API Level: Automatic (Highest Installed)<br>
Scripting Backend: IL2CPP<br>
Target Architectures: ARM64 (required)<br>
Graphics API: Vulkan (recommended) or OpenGLES3<br>
Multithreaded Rendering: Enabled<br>
Rendering Settings (Performance)<br>
Render Pipeline: Universal Render Pipeline (URP)<br>
Rendering Path: Forward<br>
HDR: Disabled<br>
Anti-Aliasing: 2x or 4x MSAA<br>
XR Rendering Mode: Single Pass Instanced<br>
