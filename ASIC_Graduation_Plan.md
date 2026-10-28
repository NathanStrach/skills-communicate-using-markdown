# Graduating Ready to Be an ASIC Engineer
## Table of Contents
- [Purpose](#purpose)
- [Choosing ASIC-Focused Courses](#choosing-asic-focused-courses)
  - [Digital Design EE Electives](#digital-design-ee-electives)
  - [Expanding Technical Skills](#expanding-technical-skills)
- [Hardware Design Projects](#hardware-design-projects)
  - [Experience Using a Simulated FPGA](#experience-using-a-simulated-fpga)
  - [Bringing Projects to Life](#bringing-projects-to-life)
- [References](#references)
## Purpose
Application-specific integrated circuit, or ASIC engineers design custom chips that operate inside vehicle systems, networking hardware, and various consumer electronics. 
These chips are used all around the world by most of the world and to be an ASIC engineer, you as a new graduate must arrive to the workforce bearing the skills of digital design. 
At UW Bothell you will fill your three upper-division elective slots with courses that will build the foundation for your skills and knowledge. Outside of class you will implement 
these skills and knowledge into projects using FPGAs which act as programmable versions of an ASIC, almost like a non-optimized ASIC.
This plan will detail which courses you will take and hardware projects you will tackle in order to graduate with the experience desired by companies hiring ASIC engineers. 

## Choosing ASIC-Focused Courses
As an electrical engineering major at UW Bothell, you are required to take three electives from the 400 range of electrical engineering courses, including one 300-level course. 
The following sections will address the three best choices for electives, along with courses outside of the major requirements to be taken. 

### Digital Design EE Electives
Entry-level positions for ASIC engineers seek candidates with specific skills. Annapurna Labs, one of Amazon’s labs that designs custom chips, requires proficiency in a hardware description language, 
or HDL, such as Verilog, SystemVerilog, or VHDL [1]. An ideal candidate has a degree that focuses on very large-scale integration or VLSI, which is more commonly referred to as digital design [1]. 
Few courses at UW Bothell teach digital design, and they are as follows: B EE 427, which teaches Verilog and what is known as register transfer level or RTL design; B EE 440, which teaches design for 
testing through Verilog labs; and B EE 486, which teaches the fabrication of integrated circuits or ICs [3]. Although not part of the elective choices, it should be noted that UW Bothell does offer B EE 475, 
Introduction to VLSI System Design, which teaches the exact skills required of an ASIC engineer.
	To best prepare yourself to be an ASIC engineer, make B EE 427, 440, and 486 your elective choices. 
  If you are able, consult your counselor and swap B EE 486 with B EE 475 to best suit your skill development. 

### Expanding Technical Skills
According to Annapurna Labs ASIC engineer job listing, in the same breath as digital design proficiency, they seek candidates with knowledge of computer architecture and scripting experience [1]. 
Ideal candidates will also have research or lab experience in chip design [1]. While there aren’t any EE electives that teach these skills [2], the CSS (Computing and Software Systems) program at 
UW Bothell offers two courses, CSS 342, which teaches data structures and algorithms, and CSS 422, which teaches computer architecture and organization. 
	For the most efficient path to becoming an ASIC engineer, take CSS 342 and then CSS 422 early on in your junior year to get ahead on your understanding of digital design. 

## Hardware Design Projects
The following two sections will detail how you will get hands-on experience with skills related to ASIC engineering through means of FPGA projects, digital and then physical. The following figure 
shows projects you can begin with using FPGA Virtual Lab and then using a physical FPGA board and how they progress in complexity. 
### Experience Using a Simulated FPGA
An FPGA is a field-programmable gate array, which is a programmable chip that acts as digital hardware, making FPGAs a great platform for testing chip designs. The Open Source FPGA Foundation offers 
a free course that can be run from your browser and teaches Verilog through a basic seven-segment display project [5]. The programming and board are all digital, so no real hardware is needed at this
point; this browser-based FPGA simulator is the best way for you to get started once your junior year has begun. 
	During your first quarter of your junior year, complete the Open Source FPGA course while taking B EE 271 to double down on your understanding of basic Verilog syntax and FPGA programming. 
  Once complete, make this project your own by adding an additional feature such as a counter reset button. 

### Bringing Projects to Life
The virtual simulator is where you should start, but it does not simulate real-life debugging. A physical board gives you real inputs and outputs to integrate with other parts, and experience integrating 
parts outside of just the FPGA board is necessary; employers don’t want students coming into a job needing to be taught [6]. To get started with your first FPGA, you will purchase an AMD RealDigital Boolean 
Board, an $87 FPGA board that works with AMD’s Vivado design software [7]; this board is far more affordable than many of its competitors.
	Buying the AMD board is affordable and will give you ample resources for troubleshooting, as the board is widely used [7]. After finishing the virtual course, maintain a pace of one physical project per quarter 
  using your Boolean Board; this will allow for ample time to understand your projects, but not so much time that you graduate without a portfolio to display. Along with these physical projects, documentation
  should be kept up with regularly to later be used to create a portfolio for potential employers to see. Keep code on your Github and use photos and videos to document your projects. 
  Create Github ReadMe files to explain your design process. 

## References
[1] Annapurna Labs (U.S.) Inc., "ASIC Engineer I, Annapurna Labs, Early Career - 2027," Indeed.com, 20 September 2026. [Online]. Available: https://www.indeed.com/viewjob?jk=b780b4650872ad62. [Accessed Oct. 15, 2026].
[2] University of Washington, "Bachelor of Science in Electrical Engineering," UW General Catalog, n.d. [Online]. Available: https://www.washington.edu/students/gencat/program/B/EngineeringandMathematics-1092.html. [Accessed Oct. 27, 2026].
[3] University of Washington Bothell, "Electrical Engineering (B EE) Course Descriptions," UW Course Catalog, n.d. [Online]. Available: https://www.washington.edu/students/crscatb/bee.html. [Accessed Oct. 27, 2026].
[4] University of Washington Bothell, "Computing and Software Systems (CSS) Course Descriptions," UW Course Catalog, n.d. [Online]. Available: https://www.washington.edu/students/crscatb/css.html. [Accessed Oct. 23, 2026].
[5] Open Source FPGA Foundation, "Getting Started with FPGAs," GitHub, n.d. [Online]. Available: https://github.com/os-fpga/GettingStartedWithFPGAs. [Accessed Oct. 27, 2026].
[6] P. Patel, "U.S. Universities Are Building a New Semiconductor Workforce," IEEE Spectrum, 13 May 2023. [Online]. Available: https://spectrum.ieee.org/chips-act-workforce-development. [Accessed Oct. 27, 2026].
[7] AMD, "RealDigital Boolean Board," AMD University Program, n.d. [Online]. Available: https://www.amd.com/en/corporate/university-program/aup-boards/realdigital-boolean-board.html. [Accessed Oct. 27, 2026].
