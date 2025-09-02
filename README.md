-----

# Hello, Recruiter\! 

Welcome to my GitHub profile\! I created this repository specifically as a landing page for recruiters and hiring managers like you. If you've found your way here, it's likely because you're exploring my work, or that you have a few minutes to look at my Resume. This document serves as a guide to help you navigate my projects and understand my passion for engineering.

-----

## 1\. Who Am I?

I am Paul, and I am a USC Aerospace Engineering Undergraduate with a passion for designing and building complete electronic systems from the ground up. My GitHub is a portfolio of most of my personal projects, showcasing my skills in both hardware design and firmware development.

Here you will find a collection of projects that demonstrate my expertise in:

  * **PCB Design & Layout:** Creating (somewhat) functional printed circuit boards for various applications.
  * **Embedded Systems Programming:** Writing firmware to bring my hardware to life.
  * **System Integration:** Ensuring that hardware and software work together.

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/paul-lototsky-787171276/) or contact me via email at [paullototsky2005@gmai.com].

-----

## 2\. What I Like to Do

I am driven by a curiosity to understand how things work and a desire to create useful and interesting devices, within the context of my second hobby: Amateur Rocketry! My primary interests lie in:

  * **Embedded Hardware Design:** I specialize in schematic capture and multi-layer PCB layout using **Altium Designer**.
  * **Firmware Development:** I enjoy writing C/C++ for microcontrollers, primarily using the **STM32 ecosystem** (STM32CubeIDE, HAL libraries).
  * **Prototyping & Testing:** From breadboarding initial concepts to soldering fine-pitch components and debugging the final product, I love the hands-on process of turning an idea into a physical reality.
  * **Open Source Design:** I do not intend to sell any of my designs, and I would rather have my designs be a stepping stone for others to use!

-----

## 3\. How to Read My Repositories

I structure my projects to be clear and easy to navigate. Most of my project repositories will follow this simple format:

```
project-repository-name/
├── HW/
│   ├── project.SchDoc
│   │  
│   ├── project.PcbDoc
│   │  
│   ├── Project-Outputs/
│   │   └── gerber-files.zip
│   └── README.md  (Hardware-specific details)
│
├── SW/
│   ├── MCU Name/
│   │   └── Core/
|   |       └── main.c
│   ├── Drivers/
│   │   └── ...
│   └── project.ioc (STM32CubeMX Configuration)
│
└── README.md  (Main project overview)
```

  * **`/HW` (Hardware):** This directory contains all files related to the printed circuit board. You will find the **Altium Designer** source files (`.SchDoc`, `.PcbDoc`), Gerber files for manufacturing, and a bill of materials (BOM).
  * **`/SW` (Software):** This directory holds the firmware for the project. The code is typically a **STM32CubeIDE** project, written in C. The `.ioc` file can be viewed to see the pinout and peripheral configuration in STM32CubeMX.

Each repository's main `README.md` file will provide a high-level overview of the project, its purpose, and key features.

-----

## 4\. Why I Do These Projects

These projects are more than just lines of code or traces on a board; they reflect my commitment to continuous learning and my passion for engineering.

  * **To Solve Problems:** Many projects start with a simple question: "Could I build a device that does X?" I enjoy the challenge of designing a solution from scratch.
  * **To Learn New Technologies:** Personal projects are the perfect playground for exploring new components, software libraries, and design techniques that I may not encounter in a professional or academic setting.
  * **To Build a Portfolio: ** The best way to demonstrate my skills is to show my work. Each repository is a case study of my ability to manage a project from concept to completion.

-----

## 5\. Q\&A

Here are some answers to questions you might have while exploring my work.

**Q: Why do you primarily use STM32 microcontrollers and Altium Designer?**

> **A:** I chose to specialize in the STM32 ecosystem due to its powerful and versatile range of ARM Cortex-M microcontrollers, extensive documentation, and excellent development tools like STM32CubeIDE. For PCB design, I use Altium Designer, an industry-standard tool that provides powerful features for complex, professional-grade designs. TLDR: USCRPL uses STM32s with MBed RTOS and Altium Designer, which I do too.

**Q: I don't have Altium Designer. Do you know how I can view your hardware files?**

> **A:** No problem\! I've included a PDF of the schematic and Gerber files in each project's `/HW` folder. You can use any free online Gerber viewer to inspect the PCB layers.

**Q: Are your projects "finished"?**

> **A:** These are personal projects, so they are often in various states of completion. I consider a project "functionally complete" when it achieves its primary goals (most of the time, never lol). However, I often have ideas for future improvements (e.g., cost reduction, feature additions), which I may note in the repository's `README`.

**Q: Can I ask you about a specific design choice in one of your projects?**

> **A:** Absolutely\! I would happily discuss my engineering decisions, the trade-offs I considered, and the lessons I learned. Please feel free to reach out.

-----

Thank you for taking the time to review my work. I look forward to discussing how my skills and passion can contribute to your team.
