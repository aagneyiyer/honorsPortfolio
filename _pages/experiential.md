---
layout: page
permalink: experiential
title: experiential '23
description: Recapping my Summer '23 research at the Applied Hearing Science Lab.
nav: true
nav_order: 5
---

## Context

I discovered the Applied Hearing Science Lab (AHSLAB) when I stumbled upon a posting for an independent study on the undergraduate research opportunities database. It was titled "Modeling Speech Perception through Cochlear Implants" and involved an intriguing blend of biology, computer science, and bioengineering. I worked on this project with a bioengineering student throughout Spring 2023 under Dr. Yi Shen, the head of the AHSLAB. Though intriguing, much of the project was explorative and self-directed, leaving myself and my lab mate scratching our inexperienced heads. Furthermore, the project demanded the use of proprietary, often esoteric hardware and software with little documentation to guide us. The independent study was certainly a rich and eye-opening experience, but I wanted to pivot. 

As Spring quarter drew to an end, I received the opportunity to work on a mobile app built with modern technologies (TypeScript and React) that I've covered in my degree coursework. Here, I would be working in an interdisciplinary team alongside students in Human Centered Design & Engineering, Speech & Hearing Sciences, and Computer Science. The project is led by a Speech & Hearing Sciences PhD candidate, Bertan Kursun. I accepted the position and thus began my summer research.

***

## Objective

Traditionally, fitting hearing aids requires audiometric tests using specialized equipment, as well as fine tuning that may be conducted across several weeks. We aim to make this process more streamlined and accessible to the 85% of hearing-impaired Americans with unmet hearing healthcare needs.

How will we accomplish this? Our lab has developed a mobile-based web app that allows patients to adjust settings on their own hearing aids, and fit their exact audiometric profile. This process is called "self-fitting". We aimed to make the app as accessible and easy to use as possible for elderly patients with less familiarity with modern apps.

When I joined the project, our application had one main fitting interface: a 5x5 grid across which users drag a cursor that adjusts the frequencies of their hearing aids. The user is taken through 20-some trials of this process, continuously dragging the cursor until the sound feels the best for them, which iteratively perfects their hearing aid settings.
<div style="text-align:center">
    <figure>
        <img src="assets\img\grid.gif" alt="Grid Interface" width="350" height="350"/>
        <figcaption>The app's 5x5 grid interface for self-tuning.</figcaption>
    </figure>
</div>

My goal throughout this summer was to implement a new fitting interface: a set of tappable buttons that each apply some adjustment to different frequencies on users' hearing aids. Similarly to the grid interface, the user is taken through several trials, which iteratively improve their hearing aid experience. Aside from this new button interface, we wanted to give the app a total aesthetic redesign to make it both user-friendly for older patients and more presentable to potential funders of our lab. We aimed to schedule clinical trials for patients at the end of August, so our timeline was clearly defined.

<div style="text-align:center">
    <figure>
        <img src="assets\img\lab2.jpg" alt="AHSLAB" width="350" height="350"/>
        <figcaption>Behind the computer is a booth in which our clinical tests will be run.</figcaption>
    </figure>
</div>

<div style="text-align:center">
    <figure>
        <img src="assets\img\lab3.jpg" alt="AHSLAB" width="350" height="350"/>
        <figcaption>Inside one of our audio booths, where we test the app for accuracy.</figcaption>
    </figure>
</div>
***

## Process & Outcome

I'm really grateful to have been able to contribute to a project like this. It's not the first codebase I've worked on collaboratively, but I do feel that it's the first one that offers such a clear, tangible benefit to future users. All aspects of the project were clearly defined - the who, the what, the when, the why, and the how - which allowed me to focus in on the actual software development without worrying about logistics. As I mentioned earlier, this is part of the reason I chose to join this project; it was so concretely defined by the time I joined, and it had an existing codebase for me to contribute to. I could start immediately; I made my first pull request (code contribution) within my first week of joining, and I knew those changes would be included in the final version of the app, which was satisfying and rewarding. After Spring quarter's project filled with question marks and uncertainty, it was incredibly refreshing to work on something so concrete.

Prior to this project, I had the misconception that the process of building software was far removed from the actual end users of that software. That is, I never believed that I'd be thinking about the *why* or the *who* when cranking out lines of code; I instead believed that writing code is purely analytical and mathematical. However, the reality was different. With each annoying bug I had to fix, every new feature I had to implement, and all the seemingly tedious aesthetic adjustments our team made, I envisioned elderly patients using our app and appreciating every last detail. Somehow, writing code began to have a degree of humanness and emotion involved, as I associated each code snippet with a purpose in the larger goal of improving an older person's life. This notion is what made this project much more enjoyable to work on than the class projects in CSE 331 in my opinion. Though our self-fitting app involved virtually the same technology stack as CSE 331 projects, knowing that my hard work will be put towards more than just a GPA is such a significant motivator. From this, I've learned that I truly do care about what I build, and if I'm working in industry moving forward, I will need to be aligned with my company's mission if I want to feel fulfilled in my work.

<div style="text-align:center">
    <figure>
        <img src="assets\img\lab1.gif" alt="AHSLAB" width="350" height="350"/>
        <figcaption>Testing algorithm accuracy with an Audioscan Verifit device.</figcaption>
    </figure>
</div>

While the scope of our app's target audience is limited to local patients of the UW Speech and Hearing Clinic, the work I did this summer felt very rewarding. The strengths of mine that contributed the most to my success were my patience and willingness to learn. In engineering settings and, more broadly, research settings, the demands are constantly changing. I worked on entire features that we ended up having to scrap and completely redo simply because we decided another solution would be optimal. Keeping up with these changing minds and wanting to improve relentlessly required patience, which I've learned I have a lot of.

Another aspect of this project that I'm incredibly thankful for was the team's interdisciplinarity. I learned a ton from Bertan, the PhD student leading the project, about audiology and acoustics. He answered all my questions - even the shockingly obvious ones. Though he doesn't come directly from a computing background, I was surprised by his grasp on programming and how he was able to switch seamlessly from thinking about the app's algorithm to its aesthetic design. We're also blessed to have Jason in our lab; he's a third-year computer science major and hands down the most talented, experienced developer I've directly worked with. He implemented basically the entirety of what was there when I joined this project. I learned a lot from him about using Git for version control, including merging changes and working across multiple branches.

<div style="text-align:center">
    <figure>
        <img src="assets\img\buttons.jpg" alt="Button Interface" width="300" height="300"/>
        <figcaption>The app's new button interface, implemented by yours truly (I promise it's cooler than it looks).</figcaption>
    </figure>
</div>

***

## Conclusion

As of August 21st, 2023, and we're done with all main functional and aesthetic changes to the app. Last week, we did a rehearsal of a clinical trial, and made some last adjustments to the instructional pages. All that I worked on this summer can be seen at https://github.com/AHSLab-UW/self-fitting-gui. We have patients coming in in the coming weeks to tune their hearing aids with our app, and I'm satisfied by the experience. I hope to continue contributing to lab in the upcoming school year, whether it's on the same project or a new one.
