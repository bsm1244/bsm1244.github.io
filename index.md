---
layout: default
title: Seungmin Baek
---

<style>
  /* 텍스트 내 연구실 링크 스타일 */
  .custom-link {
    text-decoration: none;
    color: #003087; /* SNU Blue */
    font-weight: 600;
    border-bottom: 1px solid rgba(0, 48, 135, 0.3);
    padding-bottom: 1px;
    transition: all 0.2s ease-in-out;
  }
  .custom-link:hover {
    color: #0056b3;
    border-bottom: 2px solid #0056b3;
    background-color: rgba(0, 86, 179, 0.05);
  }

  /* CV 버튼 스타일 */
  .cv-wrapper {
    margin-top: 25px;
  }
  .btn-cv {
    display: inline-flex;
    align-items: center;
    padding: 10px 22px;
    background-color: #1a1a1a;
    color: #ffffff !important;
    text-decoration: none !important;
    border-radius: 8px;
    font-size: 0.95rem;
    font-weight: 500;
    transition: all 0.3s ease;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  .btn-cv:hover {
    background-color: #404040;
    transform: translateY(-2px);
    box-shadow: 0 6px 12px rgba(0,0,0,0.15);
  }
  .btn-cv svg {
    margin-right: 8px;
  }

  /* 본문 줄간격 및 폰트 최적화 */
  .intro-text {
    line-height: 1.75;
    font-size: 1.1rem;
    color: #333;
  }
</style>

<div class="intro-text">
  Hi! I am a Ph.D. candidate at <strong>Seoul National University</strong> since 2023. 
  I am currently advised by <strong>Prof. Jung Ho Ahn</strong> and a proud member of 
  <a href="https://scale.snu.ac.kr/" class="custom-link">SCALE Lab</a> ↗. 
  <br><br>
  Overall, my research primarily focuses on <strong>memory system performance, reliability, and security</strong>.
</div>

<div class="cv-wrapper">
  <a href="/CV.pdf" class="btn-cv">
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
      <path d="M14 14V4.5L9.5 0H4a2 2 0 0 0-2 2v12 a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2zM9.5 3A1.5 1.5 0 0 0 11 4.5h2V14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h5.5v2z"/>
    </svg>
    View Full CV
  </a>
</div>

---

## Education
### <u>Seoul National University</u>

Ph.D. in Intelligence & Information Convergence, March 2023 - Present

**Advisor: Prof. Jung Ho Ahn**

### <u>Korea University</u>

B.S. in Electrical & Electronic Engineering, March 2017 - February 2023

---

## Research Experience

**Graduate research assistant @** Scalable Computer Architecture Laboratory, Seoul National University

Mar. 2023 - Present

**Undergraduate research assistant @** Scalable Computer Architecture Laboratory, Seoul National University

Jun. 2022 - Aug. 2022

- Designing RowHammer generator verilog module in DDR3 SoftMC
- RowHammer error characteristics analysis on HBM2

**Undergraduate research assistant @** Compiler & Microarchitecture Laboratory, Korea University

Sep. 2021 - Jun. 2022

- PointPillars model performance analysis on TI-SOC and CPU-GPU platforms (Korean) [Link]

  [Link]: https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11132910&googleIPSandBox=false&mark=0&minRead=5&ipRange=false&b2cLoginYN=false&icstClss=010000&isPDFSizeAllowed=true&accessgl=Y&language=ko_KR&hasTopBanner=true

---

## Publication

### IEEE Access '26
- \"Sudoku: Refining DRAM Address Mapping through Advanced Timing and Configuration Analysis\"

    Minbok Wi<sup>*</sup>, Wanju Doh<sup>*</sup>, **Seungmin Baek**, Seonyong Park, Mattan Erez, Jung Ho Ahn.
    - Minbok Wi and Wanju Doh are co-first authors of this work<sup>*</sup>.

### HPCA '26
- \"RoMe: Row Granularity Access Memory System for Large Language Models\"

    Hwayong Nam<sup>*</sup>, **Seungmin Baek**<sup>*</sup>, Jumin Kim, Michael Jaemin Kim, Jung Ho Ahn.
    - Hwayong Nam and Seungmin Baek are co-first authors of this work<sup>*</sup>.

### IEEE S&P '26
- \"SoK: Systematizing a Decade of Architectural RowHammer Defenses Through the Lens of Streaming Algorithms\"

    Michael Jaemin Kim, **Seungmin Baek**, Jumin Kim, Hwayong Nam, Nam Sung Kim, Jung Ho Ahn.

### arXiv '25
- \"The New LLM Bottleneck: A Systems Perspective on Latent Attention and Mixture-of-Experts\"

  Sungmin Yun, Seonyong Park, Hwayong Nam, Younjoo Lee, Gunjun Lee, Kwanhee Kyung, Sangpyo Kim, Nam Sung Kim, Jongmin Kim, Hyungyo Kim, Juhwan Cho, **Seungmin Baek**, Jung Ho Ahn.

### IEEE CAL '25 [Best of CAL]
- \"Per-Row Activation Counting on Real Hardware: Demystifying Performance Overheads\"

  Jumin Kim, **Seungmin Baek**, Minbok Wi, Hwayong Nam, Michael Jaemin Kim, Sukhan Lee, Kyomin Sohn, Jung Ho Ahn

### DRAMSec '25
- \"Sudoku: Decomposing DRAM Address Mapping into Component Functions\"
  
  Minbok Wi, **Seungmin Baek**, Seonyong Park, Mattan Erez, and Jung Ho Ahn

### ASPLOS '25
- \"Marionette: A RowHammer Attack via Row Coupling\"
  
  **Seungmin Baek**, Minbok Wi, Seonyong Park, Hwayong Nam, Michael Jaemin Kim, Nam Sung Kim, and Jung Ho Ahn

### ISCA '24
- \"DRAMScope: Uncovering DRAM Microarchitecture and Characteristics by Issuing Memory Commands\"
  
  Hwayong Nam, **Seungmin Baek**, Minbok Wi, Michael Jaemin Kim, Jaehyun Park, Chihun Song, Nam Sung Kim, and Jung Ho Ahn

### IEEE CAL '23
- \"X-ray: Discovering DRAM Internal Structure and Error Characteristics by Issuing Memory Commands\"
  
  Hwayong Nam, **Seungmin Baek**, Minbok Wi, Michael Jaemin Kim, Jaehyun Park, Chihun Song, Nam Sung Kim, and Jung Ho Ahn

---

## Award
- Jun. 2022: **LG Electronics Paper Award, Summer Annual Conference of IEIE 2022**, Korea.
- Feb. 2026: **Best of CAL Award, HPCA 2026**, Australia.

---

## Recognition
- Sep. 2023 - Feb. 2024: **\[BK21\] Exellent Research Talent Fellowship**

---

## Academic Service
 - Artifact Evaluation Committee: HPCA'26

---

## Skill
- Programming: Python, C/C++, Verilog
- Tools: VTune (Intel), Vivado (Xilinx), Xcelium (Cadence), Design Compiler (Synopsys)

___
