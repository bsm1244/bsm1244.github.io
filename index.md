---
layout: default
title: Seungmin Baek
---

<style>
  /* 1. Global & Text Style */
  :root {
    --snu-blue: #003087;
    --accent-orange: #e67e22;
    --text-main: #333;
    --text-light: #666;
  }

  .intro-container {
    display: flex;
    justify-content: space-between;
    align-items: flex-end; /* 텍스트 하단과 버튼 정렬 */
    gap: 20px;
    margin-bottom: 1.5rem; /* 아래 섹션과의 간격 */
  }

  .intro-text {
    line-height: 1.6; /* 줄 간격을 조금 더 타이트하게 */
    font-size: 1.05rem;
    color: #333;
    margin-bottom: 0; /* 하단 마진 제거 */
    flex: 1;
  }

  .cv-wrapper {
    margin-top: 20px; /* 위쪽 여백 제거 */
  }

  /* 2. Link & Button Style */
  .custom-link {
    text-decoration: none;
    color: var(--snu-blue);
    font-weight: 600;
    border-bottom: 1px solid rgba(0, 48, 135, 0.2);
    padding-bottom: 1px;
    transition: all 0.2s ease;
  }
  .custom-link:hover {
    background-color: rgba(0, 48, 135, 0.05);
    border-bottom: 2px solid var(--snu-blue);
  }

  .btn-cv {
    display: inline-flex;
    align-items: center;
    padding: 8px 16px; /* 패딩을 줄여 더 콤팩트하게 */
    background-color: #1a1a1a;
    color: #fff !important;
    text-decoration: none !important;
    border-radius: 6px;
    font-size: 0.9rem;
    transition: 0.2s;
    white-space: nowrap; /* 버튼 글자 줄바꿈 방지 */
  }
  .btn-cv:hover {
    background-color: #444;
    transform: translateY(-2px);
  }
  .btn-cv svg { margin-right: 8px; }

  /* 3. Section Headers */
  h2 {
    border-bottom: 2px solid #eee;
    padding-bottom: 8px;
    margin-top: 3.5rem !important;
    font-weight: 700;
    font-size: 1.6rem;
    color: #111;
  }
  h3 {
    margin: 1.2rem 0 0.2rem 0 !important; /* 위 간격은 유지, 아래 간격은 대폭 축소 */
    font-size: 1.2rem;
  }

  /* 4. Content Items (Experience, Publication, etc.) */
  .item-row {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 0px; /* 대학 이름과 아래 학위 설명 사이 간격 제거 */
  }

  .item-date {
    font-size: 0.95rem;
    color: #666;
    font-style: italic;
  }

  /* 대학 이름 바로 아래 오는 학위 정보 텍스트 간격 */
  .item-row + p, 
  .item-row + div {
    margin-top: 2px; /* 이름과 학위 정보 사이를 아주 가깝게 설정 */
    margin-bottom: 0.5rem; /* 다음 항목과의 최소 간격 */
  }
  .pub-item:hover { border-left-color: var(--snu-blue); }
  
  .pub-title {
    font-weight: 600;
    display: block;
    margin-bottom: 4px;
    line-height: 1.4;
  }
  .pub-venue {
    color: var(--accent-orange);
    /* color: #003087; */
    font-weight: 700;
    text-transform: uppercase;
    font-size: 0.85rem;
    letter-spacing: 0.5px;
  }
  .pub-authors {
    font-size: 0.9rem;
    color: var(--text-light);
  }
  .me {
    color: #000;
    font-weight: 700;
    text-decoration: underline;
    text-underline-offset: 2px;
  }
  .award-tag {
    background: #fff5eb;
    color: #d35400;
    font-size: 0.75rem;
    font-weight: 700;
    padding: 2px 8px;
    border-radius: 4px;
    margin-left: 8px;
    vertical-align: middle;
  }

  /* 5. Lists */
  ul { padding-left: 1.2rem; }
  li { margin-bottom: 0.4rem; color: var(--text-main); }

  @media (max-width: 600px) {
    .intro-container {
      flex-direction: column;
      align-items: flex-start;
    }
  }
</style>

<div class="intro-text">
  Hi! I am a Ph.D. candidate at <strong>Seoul National University</strong> since 2023. 
  I am currently advised by <strong>Prof. Jung Ho Ahn</strong> and a member of 
  <a href="https://scale.snu.ac.kr/" class="custom-link">SCALE Lab</a> ↗. Before pursuing Ph.D., I received a B.S. in Electrical and Electronic Engineering from Korea University in 2023. 
  <br><br>
  My research primarily focuses on <strong>high performance memory system for LLMs</strong> and <strong>DRAM reliability & security</strong>. For further information, please refer to my CV.
</div>

<div class="cv-wrapper">
  <a href="https://drive.google.com/file/d/17ULd6EiKvWhN5cQ84h6UMRpN_1RkR_Ux/view?usp=drive_link" class="btn-cv">
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16"><path d="M14 14V4.5L9.5 0H4a2 2 0 0 0-2 2v12 a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2zM9.5 3A1.5 1.5 0 0 0 11 4.5h2V14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h5.5v2z"/></svg>
    View Full CV
  </a>
</div>

<!-- ## Research Experience

<div class="item-row">
  <strong>Graduate Research Assistant</strong>
  <span class="item-date">Mar. 2023 – Present</span>
</div>
*SCALE Lab, Seoul National University*

<div class="item-row">
  <strong>Undergraduate Research Assistant</strong>
  <span class="item-date">Jun. 2022 – Aug. 2022</span>
</div>
*SCALE Lab, Seoul National University*
* Designing RowHammer generator Verilog module in DDR3 SoftMC
* RowHammer error characteristics analysis on HBM2

<div class="item-row">
  <strong>Undergraduate Research Assistant</strong>
  <span class="item-date">Sep. 2021 – Jun. 2022</span>
</div>
*Compiler & Microarchitecture Lab, Korea University*
* PointPillars model performance analysis on TI-SOC and CPU-GPU platforms (Korean) 
<a href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11132910" class="pub-link">📄 DBpia Link</a> -->

## Publication

<div class="pub-item">
  <span class="pub-venue">IEEE Access '26</span>
  <span class="pub-title">"Sudoku: Refining DRAM Address Mapping through Advanced Timing and Configuration Analysis"</span>
  <div class="pub-authors">Minbok Wi*, Wanju Doh*, <span class="me">Seungmin Baek</span>, Seonyong Park, Mattan Erez, Jung Ho Ahn. (*Co-first)</div>
</div>

<div class="pub-item">
  <span class="pub-venue">HPCA '26</span>
  <span class="pub-title">"RoMe: Row Granularity Access Memory System for Large Language Models"</span>
  <div class="pub-authors">Hwayong Nam*, <span class="me">Seungmin Baek</span>*, Jumin Kim, Michael Jaemin Kim, Jung Ho Ahn. (*Co-first)</div>
</div>

<div class="pub-item">
  <span class="pub-venue">IEEE S&P '26</span>
  <span class="pub-title">"SoK: Systematizing a Decade of Architectural RowHammer Defenses Through the Lens of Streaming Algorithms"</span>
  <div class="pub-authors">Michael Jaemin Kim, <span class="me">Seungmin Baek</span>, Jumin Kim, Hwayong Nam, Nam Sung Kim, Jung Ho Ahn.</div>
</div>

<div class="pub-item">
  <span class="pub-venue">arXiv '25</span>
  <span class="pub-title">"The New LLM Bottleneck: A Systems Perspective on Latent Attention and Mixture-of-Experts"</span>
  <div class="pub-authors">Sungmin Yun, Seonyong Park, Hwayong Nam, Younjoo Lee, Gunjun Lee, Kwanhee Kyung, Sangpyo Kim, Nam Sung Kim, Jongmin Kim, Hyungyo Kim, Juhwan Cho, <span class="me">Seungmin Baek</span>, Jung Ho Ahn.</div>
</div>

<div class="pub-item">
  <span class="pub-venue">IEEE CAL '25</span><span class="award-tag">Best of CAL</span>
  <span class="pub-title">"Per-Row Activation Counting on Real Hardware: Demystifying Performance Overheads"</span>
  <div class="pub-authors">Jumin Kim, <span class="me">Seungmin Baek</span>, Minbok Wi, Hwayong Nam, Michael Jaemin Kim, Sukhan Lee, Kyomin Sohn, Jung Ho Ahn.</div>
</div>

<div class="pub-item">
  <span class="pub-venue">ASPLOS '25</span>
  <span class="pub-title">"Marionette: A RowHammer Attack via Row Coupling"</span>
  <div class="pub-authors"><span class="me">Seungmin Baek</span>, Minbok Wi, Seonyong Park, Hwayong Nam, Michael Jaemin Kim, Nam Sung Kim, Jung Ho Ahn.</div>
</div>

<div class="pub-item">
  <span class="pub-venue">ISCA '24</span>
  <span class="pub-title">"DRAMScope: Uncovering DRAM Microarchitecture and Characteristics by Issuing Memory Commands"</span>
  <div class="pub-authors">Hwayong Nam, <span class="me">Seungmin Baek</span>, Minbok Wi, Michael Jaemin Kim, Jaehyun Park, Chihun Song, Nam Sung Kim, Jung Ho Ahn.</div>
</div>

<div style="margin-top: -10px; margin-bottom: 20px;">
  <small style="color: #666; font-style: italic;">
    * denotes equal contribution / Co-first authorship
  </small>
</div>


## Education

<div class="item-item">
  <div class="item-row">
    <h3>Seoul National University</h3>
    <span class="item-date">Mar. 2023 – Present</span>
  </div>
  <div class="item-desc-compact">Ph.D. in Intelligence & Information Convergence | <em>Advisor: Prof. Jung Ho Ahn</em></div>
</div>

<div class="item-item">
  <div class="item-row">
    <h3>Korea University</h3>
    <span class="item-date">Mar. 2017 – Feb. 2023</span>
  </div>
  <div class="item-desc-compact">B.S. in Electrical & Electronic Engineering</div>
</div>


## Academic Service

<div class="item-item">
  <div class="item-row">
    <strong>Artifact Evaluation Committee</strong>
    <span class="item-date">2026</span>
  </div>
  <span class="item-desc">IEEE International Symposium on High-Performance Computer Architecture (HPCA)</span>
</div>

<!-- <div class="item-item">
  <div class="item-row">
    <strong>Technical Program Committee</strong>
    <span class="item-date">2026</span>
  </div>
  <span class="item-desc">IEEE/ACM International Symposium on Microarchitecture (MICRO)</span>
</div> -->

## Honors & Awards

<div class="item-item">
  <div class="item-row">
    <strong>Best of CAL Award</strong>
    <span class="item-date">Feb. 2026</span>
  </div>
  <span class="item-desc">HPCA 2026, Australia</span>
</div>

<div class="item-item">
  <div class="item-row">
    <strong>Excellent Research Talent Fellowship</strong>
    <span class="item-date">Sep. 2023 – Feb. 2024</span>
  </div>
  <span class="item-desc">Brain Korea (BK) 21</span>
</div>

<div class="item-item">
  <div class="item-row">
    <strong>LG Electronics Paper Award</strong>
    <span class="item-date">Jun. 2022</span>
  </div>
  <span class="item-desc">Summer Annual Conference of IEIE</span>
</div>


## Skills

* **Programming**: Python, C/C++, Verilog
* **Tools**: Intel VTune, Xilinx Vivado, Cadence Xcelium, Synopsys Design Compiler