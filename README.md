# OpenVisSim-2020: a Unity3D, data-driven sight-loss simulator, for Virtual and Augmented Reality (VR/AR)

### About
This repository is an updated version of the OpenVisSim Project (now deprecated) by Pete R. Jones found here: https://github.com/petejonze/OpenVisSim
This version works in Unity 2020.3, all features were tested with a Vive Pro Eye.
This updated version was created earlier in 2021 during my bachelor thesis. However, it will soon be obsolete due to the announcement on 27.08.2021 of the launch of it's succesor [V]irtual and [A]ugmented [R]eality for [I]nclusive [Design] (VARID) in late 2021 by Pete R. Jones.

The following text was taken from original project:
OpenVisSim is a free library for simulating many of the symptoms associated with common eye diseases (e.g., glaucoma, AMD, diabetic retinopahty, etc.). The software is written primarily in OpenGL shaders, and supports most commercial VR/AR hardware (e.g., the HTC Vive, Google Cardboard, etc.).  Eye-tracking is also supported and is HIGHLY recommended. Until eye-tracking hardware is more widely available I will not be releasing an 'app' version of this software on iTunes or Google Play. OpenVisSIm is not suitable for simulating refractive error (i.e., long- or short-sightedness). For that, just try wearing the wrong glasses =)

### Quick Start: Setting up
Download the project. Install/Import the dependencies, create External-SDKs/ in the unity project folder, and import Tobii XR SDK into it. When first opening the project, you have to accept the Tobii terms of use. Open the demo scene "Demo_ViveProEye\VisSim_Example.unity" in the Unity Editor, and click run (NB: doesn't require any hardware to be connected, but will mirror to a Vive Pro Eye headset if one is connected). When running in the editor, the mouse is used by default to simulate the observer's gaze (This can be changed in the GazeTracker attached to the CameraRig). Filters can be modified and turned on and off by toggling the post-processing effects attached to each eye.

**Further details:**
When effects are linked, the right eye automatically copies the parameters from the left eye. A second demo provided by Pete R. Jones original project is also included, designed to use the Fove Headset. (Not tested in this version)

### System Requirements
**Operating system:**
Any system that supports Unity3D. Can export to most VR/Ar hardware.
This 2020 Version is only tested with the Vive Pro Eye!

**Programming language:**
Unity 2020.3.3f1

**Dependencies:**
Steam VR, 
SRanipal, 
SRanipal SDK v1.3.3.0 (https://developer.vive.com/resources/vive-sense/sdk/vive-eye-and-facial-tracking-sdk/), 
Tobii XR SDK v3.0.0.178 (https://developer.tobii.com/download-packages/tobiixr-sdk-3-0-0/)

**License:**
GNU GPL v3.0

### For more info
https://github.com/petejonze/OpenVisSim

### Acknowledgments
Original Project by Pete R. Jones: https://github.com/petejonze/OpenVisSim

### Contact
For any questions/comments to the original project, feel free to contact Pete R. Jones: https://github.com/petejonze ,
For questions to the updated 2020 version and use with Vive Pro Eye contact me at: tobias.aescht@uni-ulm.de,
Supervisor of the bachelor thesis was Mark Colley at Ulm University: https://github.com/M-Colley
