<div class="homepage-sections acad-homepage">
  <section class="home-section" id="welcome">
    <h2 class="home-section__title">👋 Welcome!</h2>
    <div class="home-section__body">
      <p>Hello, and welcome to my personal homepage! I am Yihang Zhai, an undergraduate student with a strong interest in medical image analysis, computer vision, and deep learning. My current research interests focus on medical image segmentation, diffusion models, and attention mechanisms, especially their applications in real-world medical imaging tasks. This website records my academic journey, research exploration, project experience, and some moments from my daily life. I hope it can serve not only as a place to present my work, but also as a space for continuous learning, reflection, and growth.</p>
    </div>
    <div class="about-actions">
      <a href="/files/resume.pdf" class="about-btn" target="_blank" rel="noopener">Resume</a>
      <div class="about-contact">
        <button type="button" class="about-btn about-btn--secondary">Contact Me</button>
        <div class="about-contact-card">
          <div class="about-contact-card__row">
            <span class="about-contact-card__label">Email</span>
            <span class="about-contact-card__value"><a href="mailto:zyh9097@stu.ouc.edu.cn">zyh9097@stu.ouc.edu.cn</a></span>
          </div>
          <div class="about-contact-card__row">
            <span class="about-contact-card__label">Phone</span>
            <span class="about-contact-card__value">13083671489</span>
          </div>
          <div class="about-contact-card__row">
            <span class="about-contact-card__label">WeChat</span>
            <span class="about-contact-card__value">13083671489</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="home-section" id="education">
    <h2 class="home-section__title">📖 Education</h2>
    <div class="edu-list">
      <article class="edu-item">
        <div class="edu-item__logo"><img src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" /></div>
        <div class="edu-item__main">
          <div class="edu-item__title">Ocean University of China (Project 985) · College of Computer Science and Technology</div>
          <div class="edu-item__sub">Software Engineering (WuBa Excellence Class), Undergraduate Student (2023 Cohort)</div>
        </div>
        <div class="edu-item__date">2023 - Present</div>
      </article>
    </div>
  </section>

  <section class="home-section" id="scores">
    <h2 class="home-section__title">📝 Academic Performance</h2>
    <div class="kv-list score-list">
      <div class="kv-item"><div class="kv-item__main"><strong>GPA: </strong><span class="top-rank">3.45/4.0</span></div></div>
      <div class="kv-item"><div class="kv-item__main"><strong>Academic Ranking: </strong><span class="top-rank">7/21</span></div></div>
      <div class="kv-item"><div class="kv-item__main"><strong>Comprehensive Ranking: </strong><span class="top-rank">2/21</span></div></div>
      <div class="kv-item"><div class="kv-item__main"><strong>CET-6: </strong>533</div></div>
      <div class="kv-item"><div class="kv-item__main course-row"><strong>Core Courses: </strong><span class="course-tags"><span class="course-tag">Operating Systems <em>98</em></span><span class="course-tag">Computer Networks <em>97</em></span><span class="course-tag">Linear Algebra <em>94</em></span><span class="course-tag">Database Systems <em>93</em></span></span></div></div>
    </div>
  </section>

  <section class="home-section publication-section" id="publications">
    <h2 class="home-section__title">Selected Publications & Research</h2>
    <div class="pub-list">
      <article class="pub-card">
        <div class="pub-card__thumb"><img src="/images/homepage/Network_frame.png" alt="Network Framework of Self-Supervised Ultrasound Image Denoising Method Guided by Prior Information" /></div>
        <div class="pub-card__body">
          <div class="pub-card__meta">
            <span class="pub-card__authors">Core Contributor</span>
          </div>
          <p class="pub-card__abstract">A self-supervised medical image enhancement scheme integrating pre-trained CLIP text prompt learning and Mamba state space modeling. Constrained by a multi-dimensional joint loss, it is specifically designed to overcome the challenge of detail loss in ultrasound images under medium-to-high noise conditions.</p>
        </div>
      </article>
    </div>
  </section>

<section class="home-section" id="research">
  <h2 class="home-section__title">🔬 Research Experience</h2>

  <div class="intern-list">
    <article class="intern-entry">
      <div class="intern-entry__logo">
        <img src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" />
      </div>
      <div class="intern-entry__content">
        <div class="intern-entry__title">Ocean University of China · Computational Biology Lab</div>
        <div class="intern-entry__meta">Research Intern · Supervised by Prof. Shugang Zhang</div>
        <p class="intern-entry__desc">
          Conducted independent research on automated cardiac ultrasound image segmentation, focusing on challenges such as speckle noise interference and ambiguous anatomical boundaries.
          Built a multi-GPU end-to-end deep learning pipeline and designed a boundary prediction branch based on DDPM and spatial attention mechanisms, using explicit boundary guidance to improve segmentation accuracy in low-contrast regions.
          Took full responsibility for algorithm design, core experiments, and model evaluation. The proposed method demonstrated strong generalization performance on both the CAMUS public dataset and real clinical data, and the work is currently planned for submission to MICCAI as a first-author paper.
        </p>
      </div>
      <div class="intern-entry__date">Nov. 2025 - Present</div>
    </article>
    <article class="intern-entry">
      <div class="intern-entry__logo">
        <img src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" />
      </div>
      <div class="intern-entry__content">
        <div class="intern-entry__title">Ocean University of China · Computer Vision Lab</div>
        <div class="intern-entry__meta">Research Intern · Computer Vision Lab</div>
        <p class="intern-entry__desc">
          Conducted research on self-supervised ultrasound image denoising, with a focus on preserving fine structural details under medium-to-high noise conditions.
          Proposed a denoising framework that integrates CLIP prior guidance and Mamba-based state space modeling. Led the design of a prompt learning module based on image-text constraints, and implemented the core enhancement network with U-Net and Mamba.
          Optimized a multi-dimensional joint loss function, achieving an average improvement of 1.8 dB in PSNR and 2.7% in SSIM on the CAMUS and BUSI datasets. The core method has been filed as a national invention patent, with myself as the first inventor.
        </p>
      </div>
      <div class="intern-entry__date">Feb. 2025 - Oct. 2025</div>
    </article>
    <article class="intern-entry">
      <div class="intern-entry__logo">
        <img src="/images/homepage/buaa-logo.png" alt="Beihang University Logo" />
      </div>
      <div class="intern-entry__content">
        <div class="intern-entry__title">Beihang University · Department of Security Engineering, School of Cyber Science and Technology</div>
        <div class="intern-entry__meta">Research Intern · Supervised by Prof. Rong Yin</div>
        <p class="intern-entry__desc">
          Participated in literature review and reproduction work related to multimodal LLM fine-tuning and Agent Memory, gaining hands-on experience in large language model training, fine-tuning, and memory mechanisms for intelligent agents.
        </p>
      </div>
      <div class="intern-entry__date">Apr. 2026 - May 2026</div>
    </article>
  </div>
</section>


<section class="home-section" id="projects">
  <h2 class="home-section__title">💻 Project Experience</h2>

  <div class="intern-list">
    <article class="intern-entry">
      <div class="intern-entry__logo">
        <img src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" />
      </div>
      <div class="intern-entry__content">
        <div class="intern-entry__title">Ocean University of China · 3D Vision Research Group</div>
        <div class="intern-entry__meta">Project Developer · Supervised by Prof. Ziyue Zhang</div>
        <p class="intern-entry__desc">
          Developed an end-to-end immersive guided tour system, focusing on multimodal content presentation and spatial computing interaction on Apple Vision Pro.
          Designed a “timeline + finite state machine” architecture to achieve precise multimodal synchronization, integrated DeepSeek for automated content generation, and implemented collaborative interaction logic based on eye tracking and hand gestures.
          Delivered a high-fidelity prototype that significantly improved immersion and user cognitive efficiency through questionnaire-based cross-validation. The resulting highly decoupled and modular architecture also shows strong potential for commercial reuse.
        </p>
      </div>
      <div class="intern-entry__date">Oct. 2025 - Apr. 2026</div>
    </article>
    <article class="intern-entry">
      <div class="intern-entry__logo">
        <img src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" />
      </div>
      <div class="intern-entry__content">
        <div class="intern-entry__title">Ocean University of China · Computer Networks Lab</div>
        <div class="intern-entry__meta">Course Project · Supervised by Prof. Feng Hong</div>
        <p class="intern-entry__desc">
          Independently developed a low-level TCP protocol stack, focusing on reliable communication under complex network anomaly scenarios.
          Built a complete protocol stack in Java on a simulation platform, implementing core state-machine logic such as connection management, sliding window control, retransmission, and congestion control.
          Used visualized log tracing to identify and resolve logical deadlocks caused by retransmission and window update issues. The system demonstrated strong robustness under packet loss and out-of-order delivery, resulting in reliable source code and an in-depth technical report.
        </p>
      </div>
      <div class="intern-entry__date">Oct. 2025 - Jan. 2026</div>
    </article>
  </div>
</section>

  <section class="home-section competition-section" id="competitions">
    <h2 class="home-section__title">💬 Competition Experience</h2>
    <div class="competition-list">
      <div class="competition-item">
        <div class="competition-item__main">Meritorious Winner, Mathematical Contest in Modeling (MCM/ICM)</div>
        <div class="competition-item__date">2026.05</div>
      </div>
      <div class="competition-item">
        <div class="competition-item__main">National 2nd Prize, "Lanqiao Cup" Digital Technology Application Innovation Competition</div>
        <div class="competition-item__date">2026.05</div>
      </div>
      <div class="competition-item">
        <div class="competition-item__main">Rank 3, China Collegiate Programming Contest (CCPC) Campus Team Qualifier</div>
        <div class="competition-item__date">2025.04</div>
      </div>
      <details class="competition-more">
        <summary><span class="competition-more__open">View More Competitions</span><span class="competition-more__close">Collapse</span></summary>
        <div class="competition-more__content">
          <div class="competition-item">
            <div class="competition-item__main"><strong>Provincial 3rd Prize</strong>, Lanqiao Cup National Software and Information Technology Professionals Competition</div>
            <div class="competition-item__date">2024.05</div>
          </div>
          <div class="competition-item">
            <div class="competition-item__main"><strong>Provincial 3rd Prize</strong>, Computer Innovation Challenge</div>
            <div class="competition-item__date">2025.06</div>
          </div>
        </div>
      </details>
    </div>
  </section>

  <section class="home-section home-section--closing" id="thanks">
    <h2 class="closing-card__greeting">Thanks for Visiting!</h2>
    <p class="closing-card__text">I am actively seeking Master's study and research opportunities for the 2026 postgraduate recommendation (Baoyan) / 2027 enrollment.</p>
    <p class="closing-card__sub">If you would like to communicate, collaborate, or offer advice, please feel free to contact me via the methods below.</p>
    <div class="about-actions">
      <div class="about-contact">
        <button type="button" class="about-btn about-btn--secondary">Contact Me</button>
        <div class="about-contact-card">
          <div class="about-contact-card__row">
            <span class="about-contact-card__label">Email</span>
            <span class="about-contact-card__value">zyh9097@stu.ouc.edu.cn</span>
          </div>
          <div class="about-contact-card__row">
            <span class="about-contact-card__label">Phone</span>
            <span class="about-contact-card__value">13083671489</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</div>