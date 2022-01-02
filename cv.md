# Valentine Garbuzenko (@NickFallman)

![My CV image](./cv-pics/ProfilePhotoCZ.jpg)

***

## Contents

* [Contacts](https://nickfallman.github.io/rsschool-cv/cv#contacts) <!-- https://nickfallman.github.io/rsschool-cv/cv#contacts -->
* [My credo](https://nickfallman.github.io/rsschool-cv/cv#my-credo)
* [Job status](https://nickfallman.github.io/rsschool-cv/cv#job-status)
* [Milestones](https://nickfallman.github.io/rsschool-cv/cv#milestones)
* [Skills and devtools](https://nickfallman.github.io/rsschool-cv/cv#skills-and-devtools)
* [Code examples](https://nickfallman.github.io/rsschool-cv/cv#code-examples)
* [Projects](https://nickfallman.github.io/rsschool-cv/cv#projects)
* [Graduation](https://nickfallman.github.io/rsschool-cv/cv#graduation)
* [Languages](https://nickfallman.github.io/rsschool-cv/cv#languages)

***

## Contacts

* Mobile: +375 29 7682306
* E-mail: [nickf@tut.by](mailto:nickf@tut.by)
* Viber: +375297682306
* WhatsApp: +375297682306
* LinkedIn: [My Linkedin Page](https://www.linkedin.com/in/valentine-garbuzenko-46134341/)

## My credo

>*"If something can be automated, it must be automated".*
>*"No limits for excellence".*

### Favorite movie

## Job status

Looking for a new, productive, stable and interesting job.

## Milestones

**1991** Electronics engineer, system programmer. Programming languages: ASM i51, ASM i86, Borland Pascal, Delphi (Pascal), C. *Employer* – Scientific Reserch Institute of Applied Physical Problems (Belarus).

**1993** Programmer, Graphics design, Image processing, Computer nesting for publishing. *Employer* – Belprint Ltd. (Belarus).

**1996** Operator of digital printing machine. Image processing on Mac computer. *Employer* – Belaya Vezha Ltd. (Kodak, Belarus).

**1996** Head of IT department, System administrator. Industrial Automation. Industrial communications. Programming languages: Delphi (Pascal), C, Asm. *Employer* – Aquar Ltd. (Belarus).

**1998** Deputy Director, System administrator. Industrial Automation. Industrial communications. Programming languages: Delphi (Pascal), C, C++, Asm.
*Employer* – Aquar Ltd. (Belarus).

**2001** Head of IT department, System administrator, DevOps operations. Industrial Automation. Industrial communications. Embedded microprocessor equipment. Brend developing, graphics design, prepress nesting, polygraphy for exibitions. Programming languages: Delphi (Pascal), C, C++, Asm. *Employer* – Aquar-System Ltd. (Belarus).

**2006** Leading System Engineer, System administrator, DevOps operations. Industrial Automation. Industrial communications. Brend developing, graphics design, prepress nesting, polygraphy for exibitions. Programming languages: Delphi (Pascal), C, Asm. *Employer* – Aquar-System Ltd. (Belarus).

**2009** Self-employed entrepreneur, Cisco Account Manager, Cisco Presales Engineer, Sales Manager. Trade in computer equipment. Website developing, brend developing, graphics design. *In cooperation with* – LD Systems company (Belarus).

**2014** Senior Software Programmer, System administrator, DevOps operations. Special purpose software development. Cryptographic protection of software. IT infrastructure аdministration. Programming languages: C#. *Employer* – Belfortex Ltd. (Belarus).

**2015** Senior Software Programmer, System administrator, DevOps operations. Special purpose software development. Cryptographic protection of software. IT infrastructure аdministration. AWS cloud operations. Programming languages: C#. *Employer* – BFL Ltd. (Belarus).

↓ ¯\\\_(ツ)\_/¯ *I'm sorry. The sections below under construction.* ¯\\\_(ツ)\_/¯ ↓

## Skills and devtools

### Code develope tools

### Graphics Design and Publishing

## Code examples

### Asm i51 example

```assembler
; ╔═════════════════════════════════════════════════════════════╗
; ║ Init ADC.                                                   ║
; ╚═════════════════════════════════════════════════════════════╝
ADC_Init:
    clr   ADCCLK             ; Set external synchronization
    setb  ADCDRDY            ; Enable analog input
    mov   R6,#00100000b      ; Set background calibration mode
    mov   R5,#10010000b      ; Set input data size (16)24 bit
    mov   R4,#11000011b
    acall S_Ctrl_write
    acall S_Data24_read
    ret
```

### C# example

```C#
public static void LoadCamerasDb(List<CameraInfo> cameras)
{
    var NumberFormat = BelfortexFormats.GetNumberFormat();
    var rows = BelfortexSql.SqlSelect("SELECT id FROM cameras");
    foreach (var camera in (from DataRowView row in rows select new CameraInfo((int)row["id"], NumberFormat)))
    {
        cameras.Add(camera);
    }
}
```

## Projects

todo: Andritz Belgosles RFID driveBOSS COSS (with links)

↑ ¯\\\_(ツ)\_/¯ *I'm sorry. The sections above under construction.* ¯\\\_(ツ)\_/¯ ↑

## Graduation

* **1984-1991** [Belarusian State University](https://bsu.by/), [Radiophysics and Electronics Department](https://rfe.bsu.by/) . <br>Specialization - _radiophysics_
* **2009** [Cisco Network Academy](https://www.netacad.com/). <br>Course alumni - _CCNA Exploration 4.0_
* **2010** [Cisco Partner Education Connection](https://www.cisco.com/c/en/us/training-events.html). <br>Qualification ([Pearson VUE](https://home.pearsonvue.com/) exam) - _Cisco SMBAM 650-177, SMBENG 650-195_

↓ ¯\\\_(ツ)\_/¯ *I'm sorry. The sections below under construction.* ¯\\\_(ツ)\_/¯ ↓

## Languages

todo: add info according to the online test at Epam/BBC and practice

↑ ¯\\\_(ツ)\_/¯ *I'm sorry. The sections above under construction.* ¯\\\_(ツ)\_/¯ ↑
