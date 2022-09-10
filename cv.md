# Valentine Garbuzenko CV (@NickFallman)

![My CV image](./assets/imgs/profile-photo.jpg)

***

## Contacts

* Mobile: [Call me](tel:+375297682306)
* E-mail: [E-mail me](mailto:nickf@tut.by)
* Viber: [Contact me](viber://chat?number=%2B375297682306)
* WhatsApp: [Contact me](https://wa.me/375297682306)
* Discord: [at RS School server](https://discordapp.com/users/516715744646660106)
* Telegram: [Contact me](https://t.me/nickfallman)
* LinkedIn: [My Linkedin Pages](https://www.linkedin.com/in/valentine-garbuzenko-46134341/)
* GitHub: [@NickFallman](https://github.com/nickfallman)

## Job status

Ready for hiring. Looking for a new, productive, stable and interesting job.

## Credo

>*"If something can be automated, it must be automated".*
>*"No limits for excellence".*

## Milestones

**1991** Electronics engineer, system programmer. Programming languages: ASM i51, ASM i86, Borland Pascal, Delphi (Pascal), C. *Employer* – Scientific Reserch Institute of Applied Physical Problems (Belarus).

**1993** Programmer, Graphics design, Image processing, Computer nesting for publishing. *Employer* – Belprint Ltd. (Belarus).

**1996** Operator of digital printing machine. Image processing on Mac computer. *Employer* – Belaya Vezha Ltd. (Kodak, Belarus).

**1996** Head of IT department, System administrator. Industrial Automation. Industrial communications. Programming languages: Delphi (Pascal), C, Asm. *Employer* – Aquar Ltd. (Belarus).

**1998** Deputy Director, System administrator. Industrial Automation. Industrial communications. Programming languages: Delphi (Pascal), C, C++, Asm. *Employer* – Aquar Ltd. (Belarus).

**2001** Head of IT department, System administrator, DevOps operations. Industrial Automation. Industrial communications. Embedded microprocessor equipment. Brend developing, graphics design, prepress nesting, polygraphy for exibitions. Programming languages: Delphi (Pascal), C, C++, Asm. *Employer* – Aquar-System Ltd. (Belarus).

**2006** Leading System Engineer, System administrator, DevOps operations. Industrial Automation. Industrial communications. Brend developing, graphics design, prepress nesting, polygraphy for exibitions. Programming languages: Delphi (Pascal), C, Asm. *Employer* – Aquar-System Ltd. (Belarus).

**2009** Self-employed entrepreneur, Cisco Account Manager, Cisco Presales Engineer, Sales Manager. Trade in computer equipment. Website developing, brend developing, graphics design. *In cooperation with* – LD Systems company (Belarus).

**2014** Senior Software Programmer, System administrator, DevOps operations. Special purpose software development. Cryptographic protection of software. IT infrastructure аdministration. Programming languages: C#. *Employer* – Belfortex Ltd. (Belarus).

**2015** Senior Software Programmer, System administrator, DevOps operations. Special purpose software development. Cryptographic protection of software. IT infrastructure аdministration. AWS cloud operations. Programming languages: C#. *Employer* – BFL Ltd. (Belarus).

## Skills and devtools

### Code develope tools

* Borland Pascal (IDE, Pascal/Asm)
* Borland C++ (IDE, C/C++/Asm)
* Borland Delphi (IDE, Pascal)
* Keil µVision (IDE, ASM/C)
* [Denwer](http://www.denwer.ru) (Local web environment)
* Microsoft Visual Studio (IDE, C/C++/C#/F#...)
* ProGit (GIT, GIT GUI)
* Amazon AWS (Cloud services)
* Nullsoft NSIS (Package maker)
* Embarcadero RAD Studio (IDE, Pascal)
* Microsoft Visual Studio Code (Markdown, HTML, CSS, JS, Git)
* JS (Codewars rank) - ![Codewars JS NickFallman](https://www.codewars.com/users/rsschool_NickFallman/badges/small)

### Graphics Design and Publishing

* CorelDRAW Graphics Suite
* Adobe InDesign (Adobe PageMaker)
* Adobe Photoshop
* Joomla! CMS
* Adobe Acrobat
* Adobe Premiere

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

**2005-2006** ["Kartontara" (Pulp and Board Mill).](http://sftgroup.ru/en/about/enterprises/kartontara-eng/) Startup new CTMP production line in the cardboard pulp preparation workshop on "Kartontara" (Pulp and Board Mill), Maykop (Russia). In cooperation with "ANDRITZ AG" (Austria) specialists and engineers. Acting as startup electronics engineer and technical translator (russian/english).

**2003-2008** Developing brand "Aquar-System". Preparing and publish many advertiment and exibition materials. [Magazine advertisement](./assets/docs/zerno-mag-advertisement.pdf), [Catalog booklet](./assets/docs/2004-aquar-catalog-grinding.pdf), [Exhibition booklet](./assets/docs/expo2008-booklet-2page.pdf).

**2011** LD Systems company web-site. Sorry, but it doesn't exist in the internet now and can be deployed locally (on [Denwer](http://www.denwer.ru) platform).

**2014** [Belgosles video surveillance system.](http://strazh.by/) Video surveillance system for early detection of the forest fire. C# programming.

**2015** [RFID marking of fur products.](https://asklt.datamark.by/praca.html) Automation of programming and printing RFID tags on Zebra ZXP RFID printers. C# programming, devops operations, system administration.

**2017** [driveBOSS TMS.](https://www.drivebossllc.net/) Logistic system for transportation of patients in New Jersey state (USA). DevOps operations, Web- and Backend- services deployment on AWS cloud platform, system administration.

*and much more…*

## Graduation

**1984-1991** [Belarusian State University](https://bsu.by/), [Faculty of Radiophysics and Electronics](https://rfe.bsu.by/). <br>Specialization - *radiophysics*

**2009** [Cisco Network Academy](https://www.netacad.com/), *remark: use VPN to access this site from Belarus*. <br>Course alumni - *CCNA Exploration 4.0*

**2010** [Cisco Partner Education Connection](https://www.cisco.com/c/en/us/training-events.html). <br>Qualification ([Pearson VUE](https://home.pearsonvue.com/) exam) - *Cisco SMBAM 650-177, SMBENG 650-195*

**2022** [RS School «JavaScript/Front-end. Stage 0»](https://rs.school/js-stage0/). <br>Course alumnus - [*JS/FE PRE-SCHOOL 2022Q2*](https://app.rs.school/certificate/53jg8ulr)

## Languages

### Language proficiency

1. Russian - Native
2. Belarusian - Intermediate
3. English - A2, Pre-Intermediate (self-established level)
   * Epam ([A1 Elementary](./assets/docs/english-level-a1-epam.pdf)) - according to [Epam online test](https://training.epam.com/UserProfile#!/Main/?lang=en)
   * BBC ([B1 Intermediate](./assets/docs/english-level-b1-bbc.pdf)) - according to [BBC online test](https://www.bbc.co.uk/learningenglish/course/test-your-level)

### Language practice

I've got too episodical practice in spoken and written English. The most of my practice - is reading technical documentation. The last one happens almost every day. There are my main practice cases:

**1993** Work with American colleagues (native speaking) at Belprint Ltd. (Minsk, Belarus)

**2005** Cooperative work with "ANDRITZ AG" (Austria) specialists as russian-english technical translator on CTMP production line startup, at "Kartontara" Pulp and Board Mill (Maykop, Russia).

**2007** Cooperative work with "HGH Gaßmann" (Germany) spesialists on a joint project at the Pulp and Paper Mill in Kherson region (Ukraine).

**2014** Short travel in the USA.
