![omniswap-banner](https://github.com/user-attachments/assets/bf7be986-1c6d-48e9-97d6-691ac59475c5)
# What is OmniSwap?

Great question! But to fully understand, you need some backstory. I previously had friendly and productive relations with the author and maintainer of FaceFusion; the software OmniSwap is based on. I also spent several months in the private channel for internal devlopment discussion. While I never officially contributed code, I spent a significant amount of time working directly with both developers and community members to brainstorm, collaborate, and improve FaceFusion.

However, after feeling discouraged by the author's poor communication skills and disregard for others' opinions, I began tinkering with the new alternative, [VisoMaster](https://github.com/visomaster/VisoMaster). I eventually released the [VisoMaster: Job Manager](https://github.com/PronPan/VisoMaster-Job-Manager) mod after seeing it lacked such basic functionality. As admitted by FaceFusion's author, he took personal offense to this. In the end, he messaged me calling me incompetent, said I "*sided with a competitor"*, and accused me of *"copying"* from FaceFusion.

So the purpose of this project is to build something new out of what FaceFusion offers. That includes a new name and full rebrand. The main goal being to strip FaceFusion of unneccessary and bloated code while adding a significant amount of new features, functionality, and optimizations outside the scope of FaceFusion's current leadership. This project will not be monetized or earn revenue in any way.

# FaceFusion ➡️ OmniSwap: An Overview

- Fully strip and remove the NSFW detection pipeline. Current implementation adds significant time to processing, suffers false positives, and can be circumvented by editing a single line of code (it's 100% just for show). Add new, non-instrusive realistic deterrents and disclaimers that fully comply with GitHub's [Synthetic & Manipulated Media Tools](https://github.com/github/site-policy/blob/main/Policies/acceptable-use-policies/github-misinformation-and-disinformation.md#synthetic--manipulated-media-tools) policy. Contrary to proper belief, NSFW detection is **not** required by GitHub's polices or the OpenRAIL-AS license. 
- Continue the development of a fully custom, local GUI independent from a network or browser. 
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


# A Letter to FaceFusion's Creator

Henry,

You banned me from the Discord and accused me of *"siding with the competition"* just because I began tinkering with VisoMaster. When you asked why I would put time into VisoMaster and not FaceFusion, I explained I saw some of its advantages and it helped me understand how things could be improved for FaceFusion. Crucially, I also explained that I was hesitant to contribute to FaceFusion given some of our differences, your attitude, and the reputation you've established online.

You tried to treat me like a subordinate, and guilt trip me for not spending my free time working on FaceFusion. Even though I constantly assured you I was "loyal" to FaceFusion, and *did* in fact dedicate a lot of my time trying to help. Then I got busy with my disability, school/work, and understandably found myself doing other things. Just to have you crawl back to my DMs, call me incompetent, and effectively block me each time so I couldn't respond... And you wonder why you felt "disappointed" after I repeatedly ghosted you during the period I tried to be helpful. Truthfully, Henry, 9 times of 10 you're an insufferable a**hole unless the other person is actively worshipping you. You legitimately have the communication skills of a toddler.

It's obvious you felt threatened because you saw the genuine work I put into VisoMaster's Job Manager mod. Is this the "copying" you're talking about? It's insane to think a fully custom job manager, which I spent time and effort uniqely developing for VisoMaster, could be seen as "copying". I had no idea helping them with such simple, standard functionality, would get you so worked up and aggressive. It's incredibly petty and a bit delusional. 

Your adamant use of the word "competition" is ironic, considering both VisoMaster and FaceFusion are open source and encourage community development. I can assure you no other *truly* open source, community-made project sees this as a competition. But that's apparent from your need to profit off FaceFusion, restricting fundamental resources like a .EXE installer behind a paywall. That's not community-minded, it's not open source thinking, nor is it understandable from a "compensate the developer" viewpoint. It's just flexing your ignorance and true intentions for everyone to see. Which, based off the first few public threads that appear when Googling "FaceFusion", they certainly have.

You say this is your full time job, but the dev branch sits untouched for days or multiple weeks at a time. Then you go around treating everyone like they owe you something and should be grateful you'd even speak to them. I suggest you either earn that attitude by close-sourcing the project and taking complete control, or lowering your expectations for people who are willing to deal with that sh*t for free and under scrutiny.

You developed some great software, but unfortunately FaceFusion's growth is limited by your ego's control over how you handle the project and present yourself. I'll be using this experience as newfound motivation to fully develop a new "competitor" *(as you prefer to call free, open-source projects)* with some much needed improvements. All credit/copyright attributed, of course.

Congrats on the new model announcement. Can't wait to show you what I've been working on.

-Axel