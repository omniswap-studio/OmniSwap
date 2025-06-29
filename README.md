![omniswap-banner](https://github.com/user-attachments/assets/772094bd-4e15-4a9a-885c-f108d46cc042)
# What is OmniSwap?

The purpose of this project is to build something new out of what [VisoMaster](https://github.com/visomaster/VisoMaster) and [FaceFusion](https://github.com/facefusion/facefusion) offer. That includes a new name and full rebrand, separating OmniSwap from the two programs. We take the best of both worlds, combine their concepts, and rework it all from the ground-up. This project will not be monetized or earn revenue in any way.

# VisoMaster ➡️ OmniSwap: An Overview
- New CLI-based core systems that allow for both a new and improved local GUI *and/or* a Gradio interface
- Utilize VisoMaster's efficient multi-target face processing methods as the backbone for OmniSwap
- Completely rework and rewrite the thread handling system to ensure the local UI *never* hangs or freezes
- Improve-on and enhance the Webcam input system
- Continue the development of a brand new, easier-to-use local GUI.
- Incorporate several features and quality of life improvements from base VisoMaster

# FaceFusion ➡️ OmniSwap: An Overview
- Incorporate Gradio's API functionality into the current WebGUI for controling OmniSwap remotely or with full automation.
- Replace FaceFusion's default Gradio playback module with a new custom component that utilizes Gradio's [backend](https://www.gradio.app/guides/backend) and [frontend](https://www.gradio.app/guides/frontend) capabilities. Provides real-time playback of processed frames, or as close as possible given the user's hardware constraints. Also adds the option to enable audio during processed playback.
- Integrate free alternatives for FaceFusion's features currently locked behind its "Buy Me A Coffee" paywall. Including video downloading functionality, hair modification, and face mask exporting. Essentially, a free option for the same features that would typically cost $50 to unlock.
- In addition to the above, create and maintain an open source all-in-one .EXE installer for Windows included as <ins>a new standard with every update for free.</ins>
- Finalize the addition of several new Gradio themes that match the new local UI's selection of choices. 
- Fully upgrade and resolve all possible dependencies, providing a modern framework for future community-driven development.
- Properly license the distribution under MIT, as FaceFusion is currently ambiguously and improperly licensed. This is corrected by the original author's numerous public statements over the years regarding FaceFusion's *"free"* and *"open source"* nature. Additionally, an implied intention can clearly be established considering the use of MIT or OpenRAIL-AS labels across FaceFusion's repositories. Regardless, the author's original copyright notice will stay intact and clearly displayed, with or without any additional declarations. 

# Current FaceFusion Backend Visualized

![callgraph_conditional_process](https://github.com/user-attachments/assets/ca428fb3-101c-4a1f-9f2f-0c80066addf3)
![callgraph_process_video](https://github.com/user-attachments/assets/6fa1cded-d675-46ef-ad93-0e542fd2a567)
![callgraph_render](https://github.com/user-attachments/assets/b6282044-8dda-4534-aebb-8155b7847579)
![callgraph_route](https://github.com/user-attachments/assets/0788bfc4-4f4b-45f2-8c71-42ac806d0be9)
![callgraph_run](https://github.com/user-attachments/assets/a455572b-89b4-4a4f-a1c2-823dad1c7f30)
![callgraph_ui_core_launch](https://github.com/user-attachments/assets/0ad70ae1-bdf2-4e21-91e7-f73dc960426a)
