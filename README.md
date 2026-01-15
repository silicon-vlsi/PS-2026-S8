# Practice School 2026

This is the portal for all 2026 (Sem-8) Practice School students. Learning materials, assignments, announcements, etc will be shared on this portal.

# Getting Started

- Students with NO Linux exeperience may follow these [8 Lessons in Linux](https://github.com/silicon-vlsi-org/module-cs3-301) to get started.
- If you haven't, install **Windows Subsystem for Linux (WSL)** on your Windows 10/11. **Follow this [page](https://github.com/silicon-vlsi-org/eda-wsl2)**
- If you don't have one yet, create a [GitHub](https://github.com) account. Create a Git Repository with the name `PS-2025-S8-<username>` where, username is First initial and Surname or Surname Initial and First Name. For eg. if name is _Subash Bose_, the repossitory name should be `PS-2025-S8-sbose`
- Get familiar with editor `vim` and `git`. As an exercise for `vim` and `git`, open your README.md and create a documentation for Capacitor section and insert a table with the capacitor properties.
  - [Tutorial from Perplexity](https://www.perplexity.ai/search/create-a-quick-vim-editor-tuto-OOEC6K37R9a6DdMBq4TTew) : Short tutorials on `vim`, `git` and writing equations in markdown

# Resources

- **TEXT/REFERENCES**
  - **Electrical Circuits**
    - [**[RoutS]**]. "_IC Engineering I_", 2025.
      - Most of the notes covered during this PS will be shared on this eBook.
    - [**[ThomasRE]**], Rosa, A. J., Toussaint, G. J. (2023). _The Analysis and Design of Linear Circuits_. UK: Wiley.
    - [**[SadikuMNO]**] and Alexander C.K., _Fundamentals of Electric Circuits_. McGraw-Hill Higher Education, 2007.
  - **Digital Design and Computer Architecture**
    - [**[ManoM]]**, Ciletti, M.D., _Digital Design: With An Introduction to Verilog HDL_, 5th Ed. 2012.
    - [**[PalnitkarS]]**, _Verilog HDL: A Guide to Digital Design and Synthesis_, 2ndEd.. PrenticeHall.
    - [**[MishraK]]**, _Advanced Chip Design: Practical Examples in Verilog_
    - [**[HarrisHarris]**], _Digital Design and Computer Architecture_, 2nd Ed., MK

  - **CMOS IC**
    - [**[HodgesDA]**], et.al., "_Analysis and Design of Digital Integrated Circuits_", Tata-McGraw Hill, 3rd Ed
    - [**[KangS]**], Leblebici and Kim C., "_CMOS Digital Integrated Circuits_, McGraw Hill, 4th Ed, 2015.
    - [**[WesteN]**], and David Harris. "*CMOS VLSI Design: A Circuits and Systems Perspective*". 4Ed., Pearson Education, 2011
      - [**[WesteMartin]**] : Highlighted notes from West and JohnsMartin for IC Fab and layout preparation.
    - [**[JohnsMartin]**], _Analog Integrated Circuit Design_, 2nd Ed.
    - [**[AllenHolberg]**], _CMOS Analog Circuit Design_, 3rd Ed., Oxford
    - [**Uyemura**] Uyemura, John P. "*CMOS Logic Circuit Design*". Springer, 2007
    - [**Baker**] Baker, R. Jacob. "*CMOS: Circuit Design, Layout, and Simulation*". John Wiley & Sons, 2008

- **ARTICLES/DATASHEETS/WHITEPAPERS/ETC**
  - Harald Pretl and Matthias Eberlein, _Fifty Nifty Variations of Two Transistor Circuits_, IEEE SSC Mag. ([PDF](https://www.dropbox.com/scl/fi/6q7plwha2kzx5n48umkm9/2021-PretlEberlein-50variationsOf2transitorCkts-IEEESSCmag-13-3.pdf?rlkey=njcd6j43486n9y56l6e6k0ivz&dl=0) )
    - _An excellent set of CMOS circuits for practice_.
- **ONLINE**
  - [Silicon VLSI Lab GitHub Portal](https://github.com/silicon-vlsi) : All github portals related to courses, projects, CAD, etc. are hosted here.
  - [Digital Temperature Monitor](https://github.com/silicon-efabless/tt06-silicon-tinytapeout-lm07): An excellent first Verilog project.


# EE Refresher

- **PASSIVE DEVICES**: Resistor, Capacitor and Inductors (RLC)  [[Chap-2: Passives](https://mixignal-press.github.io/ebook-ice1/passives.html)] [[Video-2021](https://www.youtube.com/watch?v=3SCYAH57Ixw)]
   - Derivation of IV char for resistive material.
   - Derivation of Capacitance using Gauss's Law.
   - Basic inductance calculation.
- **BASIC CIRCUIT THEORY** [[Chap-3: Linear Circuit](https://mixignal-press.github.io/ebook-ice1/circuits.html)] [[Video-2021](https://www.youtube.com/watch?v=OzlsThjjUDA)]
  - Basic circuit analysis: Voltage current division, circuit reduction.
  - Analysis techniques:
    - Node-voltage and mesh-analysis
    - Linearity properties
    - Thevenin and Norton equivalent.
    - Interface circuit design
  - **Reading Assignment**: Chap-2 and 3 from [[ThomasRE]]
  - **Problems**:
    - Basic Circuits: [[ThomasRE]] (2.2, 2.5, 2.7(a,b), 2.10, 2.25, 2.26, 2.27, 2.31, 2.34, 2.35, 2.37, 2.49, 2.50)
    - Circuit Analysis Techniques: [[ThomasRE]]
      - Node and Mesh Analysis: (3.1, 3.6, 3.8, 3.9, 3.11, 3.14)
      - Superposition: (3.33, 3.35, 3.36)
      - Thevenin and Norton: (3.39, 3.42, 3.45, 3.48, 3.52)
      - Maximum Power Transfer: (3.57, 3.59, 3.61)

* * *


[RoutS]:          https://mixignal-press.github.io/ebook-ice1/
[ThomasRE]:       https://www.box.com/scl/fi/83ygnyynx2sfex1h7tdhg/Thomas-AnalysisDesignOfLinearCkts-Wiley-2023.pdf?rlkey=4xzk0an1z7r3fcj936o0enjg4&st=oio90ydk&dl=0
[SadikuMNO]:      https://archive.org/details/sadiku-fundamentals-of-electric-circuits-6th-2016
[ManoM]:          https://www.box.com/scl/fi/yf8vfcfrqfp64jyhn31sd/ManoCiletti-DigitalDesignWithIntroToVerilog-5thEd-2012.pdf?rlkey=jy1tp7d81f7jn9ynwe3v0jayu&dl=0
[PalnitkarS]:     https://www.box.com/scl/fi/8neiqcma4l2im6v5eu9wu/PalnitkarSamir-VerilogHDL-2ndEd-2003.pdf?rlkey=wef5hist6aq0tapdu9wmajihk&dl=0
[MishraK]:        https://www.box.com/scl/fi/jl3hl4lbza1917cr86geu/MishraKishore-AdvancedChipDesign-Verilog.pdf?rlkey=r8nsin7tjyk022nrv9jxuxvng&dl=0
[HarrisHarris]:   https://www.box.com/scl/fi/67d1r2k6zh6yhpn4dol5o/Harris-Harris-DigitalDesignAndComputerArchitecture-MK-2ed-2012.pdf?rlkey=6azp4fylvpeykezhg6wm38hvk&dl=0

[HodgesDA]:       https://www.box.com/scl/fi/43orxdtdm6u4u5mq68mc2/HodgesJackson-DesignAndAnalysisOfDigitalIC-3Ed-McGraw-2005.pdf?rlkey=1awl7pw48611qd8cnru6az7x5&dl=0
[KangS]:          https://www.box.com/scl/fi/qv87mhnbzkntthl3atjqh/Kang-CMOS-DigitalIC-4thIE-McGrawHill-2015.pdf?rlkey=k5jkk4k1b5zmfkwldt1eseetl&dl=0
[WesteN]:         https://www.box.com/scl/fi/8i5pftaeux4x2kzj51cpr/Weste-Harris-CMOS-VLSI-design-Pearson-4thEd-2011.pdf?rlkey=g1efbminflmhqze5o2pc9rnl8&dl=0
[WesteMartin]:    https://www.box.com/scl/fi/fm6tyicvb72crje7r51ey/Weste-JohnsMartin-CMOSprocessing-Layout-Highlight-annotate.pdf?rlkey=wqcjq4fhb79qwxkiue2gihdx9&dl=0
[JohnsMartin]:    https://www.box.com/scl/fi/7jp5q4e3kvalnlbui7p5m/JohnsMartinCarusone-AnalogICDesign-2ndEd-Wiley-2012.pdf?rlkey=exl7b2bmfgoiqyku6f0qeyk7a&dl=0
[AllenHolberg]:   https://www.box.com/scl/fi/bxv3gagfq6p7t88runbx1/Allen-Holberg-CMOS-AnalogCircuitDesign-3rdEd-Oxford-2012.pdf?rlkey=jqjyleetec34oe6upvxu7lfox&dl=0
[SCMOS]:                https://www.mosis.com/files/scmos/scmos.pdf
[NGSpice]:              http://ngspice.sourceforge.net
[NGSpiceMan]:           http://ngspice.sourceforge.net/docs/ngspice-html-manual/manual.xhtml
[Magic]:                http://opencircuitdesign.com/magic/
[Netgen]:               http://opencircuitdesign.com/netgen/
