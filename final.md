class: center, middle

# Therac 25

By David Bell, Chad Bowman, Matthew Gannon, Yue Hou, Michael Manning

---

# Outline

- What is Therac 25?
- Patient Case Studies
- Technical Failures
- Current Software Regulations
- Aftermath

---

# What is Therac 25?

- Medical Electron accelerator, used for electron therapy
- Two modes, direct and deep (5 Mev - 25 Mev, 25 Mev)
- Developed by Atomic Enegy of Canada Limited (AECL) in 1982
- 11 were installed in US, 6 in Canada
- Massive radiation overdoses
- 6 major accidents resulting in injury and death
- "Worst series of radiation accidents in 35-year history"

???

- Matt Speaks next
- Direct electron-beam
- Megavvolt X-ray
- Mev = Mega Electron Volts
- therac-6 &amp; therac-20 came before

---
## “You burned me!”

### 1st patient
- June 1985, Kennestone Regional Oncology Center, Marietta GA
- Patient's breast had to be removed, and she completely lost the use of her shoulder and arm.

### 2nd patient
- July 1985, Ontario Cancer Foundation clinic in Canada
- She died three months later of cancer, but a total hip-replacement would have been necessary if she had continued to live.

### 3rd patient
- Dec 1985, Yakima Valley Memorial Hospital, WA
- The patient received only minor disability and scarring from the accident.

---
## "Deaths"

### 4th patient
- March 1986, East Texas Cancer Center, TX
- Lost use of his left arm and both legs, was unable to speak, and died from complications.

### 5th patient
- April 1986, East Texas Cancer Center, TX
- Died three weeks after the accident after falling into a coma.

### 6th patient
- January 1987, Yakima Valley Memorial Hospital, WA
- The Patient died three months later from complications related to the overdose.

???

- Yue speaks next

---
class: center, middle

# Technical Failures

???

- Chad speaks next

---

# Current Software Regulations

.center[![FDA Image](https://raw.githubusercontent.com/djb388/therac-25/master/FDA.png)]

- Audits software in medical and non-medical devices
- Multiple regulatory requirements
- Design validation, Automated processes, Corrective and preventative action
- Basic Software Requirements
- Records, Integration and Unit testing, Design history file, Quality audits, and many, many more.
- "...software engineering needs an even greater level of managerial
scrutiny and control than does hardware engineering."

???

- David speaks next

---

# International Electrotechnical Commission

- International Electrotechnical Commission (IEC) 62304
- Medical device software life cycle processes
- Supersedes previous ISO standards
- 1996 amendment addressed failures
- SOUP: software of unknown pedigree

---

background-image: url(https://raw.githubusercontent.com/djb388/therac-25/master/Dave_slide_1_image.png)

# International Electrotechnical Commission

---

background-image: url(https://raw.githubusercontent.com/djb388/therac-25/master/Dave_slide_2_image.JPG)

---

# Sources

- [An investigation of the Therac-25 accidents](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=274940)
- [Death and Denial: The Failure of the THERAC-25, A Medical Linear Accelerator](http://users.csc.calpoly.edu/~jdalbey/SWE/Papers/THERAC25.html)
- [Medical Device Software - Software life cycle processes](https://webstore.iec.ch/preview/info_iec62304%7Bed1.1%7Den.pdf)
- [Medical Product Software Development](http://occs.ieee.org/presentations/2006/060327_Wyrwa_MedicalDevice.pdf)
- [Software Quote](http://www.fda.gov/cdrh/comp/guidance/938.pdf)
- [Therac-25](https://en.wikipedia.org/wiki/Therac-25)
- [Image - Therac 1](http://courses.cs.vt.edu/professionalism/Therac_25/Figure.1.GIF)
- [Image - Therac 2](http://2.bp.blogspot.com/_t2Wft402i8Y/S4iF6lfNgPI/AAAAAAAAANs/svqtGP3-ASE/s320/therac25.gif)
- [Image - World Map](https://upload.wikimedia.org/wikipedia/commons/d/dc/IEC_membership.png)
- [Image - Software Flow Chart](https://webstore.iec.ch/preview/info_iec62304%7Bed1.1%7Den.pdf)
- [Image - FDA](http://www.diamonddiagnostics.com/en/grfx/FDA.png)

