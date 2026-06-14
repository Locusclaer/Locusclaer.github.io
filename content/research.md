<div class="research-page">
  <section class="home-section">
    <h2 class="home-section__title">Timeline</h2>
    <div class="timeline-lanes">
      <div class="timeline-months">
        <span></span>
        <span>2024.02</span>
        <span>2024.10</span>
        <span>2025.10</span>
        <span>2025.11</span>
        <span>2026.01</span>
        <span>2026.03</span>
        <span>2026.04-05</span>
      </div>
      <div class="timeline-lane">
        <strong>OUC Computer Vision Lab</strong>
        <div class="lane-bar bar-ouc-cv">
          <span class="lane-date">2024.02 - 2024.10</span>
          <span>Self-Supervised Ultrasound Image Denoising Guided by CLIP Prior + Mamba</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>OUC 3D Vision Group</strong>
        <div class="lane-bar bar-ouc-3d">
          <span class="lane-date">2025.10 - 2026.03</span>
          <span>UNIFI-AR: Multimodal AI-Fused Augmented Reality Display System</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>OUC Computational Biology Lab</strong>
        <div class="lane-bar bar-ouc-cb">
          <span class="lane-date">2025.11 - Present</span>
          <span>Automatic Annotation and Intelligent Diagnosis of Echocardiography Images</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>OUC Computer Network Lab</strong>
        <div class="lane-bar bar-ouc-net">
          <span class="lane-date">2025.11 - 2026.01</span>
          <span>Underlying Development and Visual Analysis of TCP Protocol Stack</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>BUAA School of Cyberspace Security</strong>
        <div class="lane-bar bar-buaa">
          <span class="lane-date">2026.04 - 2026.05</span>
          <span>Multimodal LLM Fine-Tuning and Agent Memory Research & Reproduction</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>Independent Project</strong>
        <div class="lane-bar bar-independent">
          <span class="lane-date">Ongoing</span>
          <span>MiniMind Reproduction and LLM Engineering Practice</span>
        </div>
      </div>
    </div>
  </section>

  <section class="home-section">
    <h2 class="home-section__title">Detailed Research & Project Experience</h2>
    <div class="research-details">
      <details class="research-card" open>
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" loading="lazy" />
          <div>
            <span class="research-label">OUC · Computational Biology / Medical Image Segmentation</span>
            <h3>Prof. Shugang Zhang: Automatic Annotation and Intelligent Diagnosis of Echocardiography Images</h3>
          </div>
          <span class="research-period">2025.11 - Present</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2025.11 - Present</time>
              <div>
                <h4>Automated Segmentation Research for Complex Echocardiography Scenarios</h4>
                <p>Conducted research on automated segmentation of echocardiography images at the OUC Computational Biology Lab. Focused on addressing issues such as significant multi-view differences, strong speckle noise, difficulty in recognizing low-contrast regions, and blurred boundaries of anatomical structures like the myocardium, exploring precise annotation methods for key structures such as the atrium, ventricle, and myocardium.</p>
                <div class="gain-tags">
                  <span>Echocardiography✅️</span>
                  <span>Medical Image Segmentation✅️</span>
                  <span>Complex Anatomical Structures✅️</span>
                  <span>Blurred Boundary Modeling⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Engineering</time>
              <div>
                <h4>Building a Multi-GPU End-to-End Deep Learning Pipeline</h4>
                <p>Independently built an end-to-end training and evaluation pipeline in a multi-GPU RTX 4090 environment, covering standard ultrasound image preprocessing, data augmentation, model training, validation evaluation, and results visualization, forming a complete closed loop from data input to experimental conclusion output.</p>
                <div class="gain-tags">
                  <span>RTX 4090✅️</span>
                  <span>Multi-GPU Training✅️</span>
                  <span>Data Augmentation✅️</span>
                  <span>Result Visualization✅️</span>
                  <span>Experimental Closed-Loop✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Model Design</time>
              <div>
                <h4>Designing Boundary-Prediction Branch to Enhance Boundary Perception</h4>
                <p>Based on the Denoising Diffusion Probabilistic Model (DDPM) and Spatial Attention mechanisms, designed a Boundary-Prediction Branch. By explicitly predicting the boundary information of target regions, it guides the diffusion denoising branch to more accurately restore the segmentation results of complex anatomical structures, thereby improving segmentation quality in low-contrast and blurred boundary regions.</p>
                <div class="gain-tags">
                  <span>DDPM✅️</span>
                  <span>Spatial Attention✅️</span>
                  <span>Boundary Branch✅️</span>
                  <span>Structural Prior⬆️</span>
                  <span>Boundary-Aware Seg⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Outcomes</time>
              <div>
                <h4>Dual Validation on Public Datasets and Real Clinical Data</h4>
                <p>The model completed validation on the CAMUS public echocardiography dataset and further tested its generalization capability on real clinical ultrasound data from a partner hospital. Currently, the related research results are being organized, with plans to submit to MICCAI as the first author.</p>
                <div class="gain-tags">
                  <span>CAMUS✅️</span>
                  <span>Clinical Data Validation✅️</span>
                  <span>Generalization Ability⬆️</span>
                  <span>1st Author Paper in Prep⬆️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" loading="lazy" />
          <div>
            <span class="research-label">OUC · Computer Vision / Ultrasound Image Denoising</span>
            <h3>Computer Vision Lab: Self-Supervised Ultrasound Image Denoising Guided by Prior Information</h3>
          </div>
          <span class="research-period">2024.02 - 2024.10</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2024.02 - 2024.10</time>
              <div>
                <h4>Design of Self-Supervised Denoising Method for Medium-to-High Noise Ultrasound Images</h4>
                <p>Conducted research on self-supervised ultrasound image denoising tasks, focusing on solving problems like structural detail loss and poor tissue edge preservation under medium-to-high noise conditions. Proposed a denoising method integrating CLIP prior guidance and Mamba state space modeling.</p>
                <div class="gain-tags">
                  <span>Ultrasound Denoising✅️</span>
                  <span>Self-Supervised Learning✅️</span>
                  <span>Detail Preservation⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Prior Guidance</time>
              <div>
                <h4>Designing Prompt Text Learning Module Based on Image-Text Constraints</h4>
                <p>Leveraged the image-text alignment capabilities of pre-trained CLIP to construct positive and negative samples of ultrasound images according to their noise levels. Learned noise-related prompt representations through image-text similarity and cross-entropy constraints, enabling the model to obtain auxiliary information on noise levels and image quality from text priors.</p>
                <div class="gain-tags">
                  <span>CLIP✅️</span>
                  <span>Prompt Learning✅️</span>
                  <span>Image-Text Similarity✅️</span>
                  <span>Cross-Entropy Constraint✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Network Arch</time>
              <div>
                <h4>Constructing U-Net + Mamba Enhanced Denoising Network</h4>
                <p>Introduced the Mamba module based on a U-Net architecture to enhance the model's capacity for long-range dependency and local structure modeling. Jointly optimized using prompt text refinement, edge ranking loss, structural similarity loss, perceptual loss, and edge preservation loss.</p>
                <div class="gain-tags">
                  <span>U-Net✅️</span>
                  <span>Mamba✅️</span>
                  <span>Joint Loss✅️</span>
                  <span>Edge Preservation✅️</span>
                  <span>Long-Range Modeling⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Outcomes</time>
              <div>
                <h4>Public Dataset Validation and National Invention Patent Acceptance</h4>
                <p>Completed experimental validation under medium-to-high noise conditions on the CAMUS and BUSI datasets, achieving an average PSNR improvement of 1.8 dB and SSIM improvement of 2.7%. The core methodology has been submitted and accepted for a National Invention Patent application as the first inventor.</p>
                <div class="gain-tags">
                  <span>CAMUS✅️</span>
                  <span>BUSI✅️</span>
                  <span>PSNR +1.8 dB✅️</span>
                  <span>SSIM +2.7%✅️</span>
                  <span>Invention Patent Accepted✅️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" loading="lazy" />
          <div>
            <span class="research-label">OUC · 3D Vision / Multimodal AR System</span>
            <h3>Prof. Ziyue Zhang: UNIFI-AR Multimodal AI-Fused Augmented Reality Display System</h3>
          </div>
          <span class="research-period">2025.10 - 2026.03</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2025.10 - 2026.03</time>
              <div>
                <h4>Development of Immersive Guided Tour System for Apple Vision Pro</h4>
                <p>Participated as a core member in the R&D of the UNIFI-AR multimodal AI-fused augmented reality display system. Built an end-to-end immersive guided tour prototype based on Apple Vision Pro and Unity, focusing on multimodal content presentation and natural interaction experiences in spatial computing scenarios.</p>
                <div class="gain-tags">
                  <span>Apple Vision Pro✅️</span>
                  <span>Unity✅️</span>
                  <span>AR System Development✅️</span>
                  <span>Spatial Computing⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Architecture</time>
              <div>
                <h4>Designing "Timeline + FSM" Multimodal Synchronization Architecture</h4>
                <p>Integrated DeepSeek and TTS for automated generation of display content, and designed a "Timeline + Finite State Machine (FSM)" control architecture. Using voice as the main axis, it precisely aligned text, visual highlights, animation effects, and interaction feedback, enhancing the consistency and controllability of the multimodal display.</p>
                <div class="gain-tags">
                  <span>DeepSeek✅️</span>
                  <span>TTS✅️</span>
                  <span>FSM✅️</span>
                  <span>Multimodal Sync✅️</span>
                  <span>Automated Content Gen⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Interaction</time>
              <div>
                <h4>Implementing Dynamic Visual Effects and Eye/Gesture Interaction</h4>
                <p>Utilized Shader Graph, Procedural Mesh, and Unity XR Hands to implement dynamic highlighting, parametric wireframes, and collaborative "eye-tracking + gesture" holographic interaction logic, allowing users to browse, focus, and interact more naturally in spatial scenarios.</p>
                <div class="gain-tags">
                  <span>Shader Graph✅️</span>
                  <span>Procedural Mesh✅️</span>
                  <span>XR Hands✅️</span>
                  <span>Eye-Tracking Interaction✅️</span>
                  <span>Gesture Interaction✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Evaluation</time>
              <div>
                <h4>Delivering High-Fidelity Prototype and User Experience Evaluation</h4>
                <p>High-quality delivery of an immersive guided tour prototype, evaluating user experience, task load, and immersion via UEQ and NASA-TLX scales. The project accumulated a highly decoupled modular architecture, providing a reusable foundation for future adaptations to multiple artifacts and scenarios.</p>
                <div class="gain-tags">
                  <span>High-Fidelity Prototype✅️</span>
                  <span>UEQ✅️</span>
                  <span>NASA-TLX✅️</span>
                  <span>Modular Architecture✅️</span>
                  <span>Cross-Scenario Reuse⬆️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="Ocean University of China Logo" loading="lazy" />
          <div>
            <span class="research-label">OUC · Computer Network / System Engineering</span>
            <h3>Computer Network Lab: Underlying Development and Visual Analysis of TCP Protocol Stack Based on Simulation Platform</h3>
          </div>
          <span class="research-period">2025.11 - 2026.01</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2025.11 - 2026.01</time>
              <div>
                <h4>Independently Building Core Architecture of TCP Protocol Stack</h4>
                <p>Conducted project practice focusing on the underlying implementation of the TCP protocol stack and reliable communication mechanisms. Independently built a complete protocol stack using Java based on a network simulation platform, implementing connection management, sliding windows, congestion control, and complete state machine logic.</p>
                <div class="gain-tags">
                  <span>Java✅️</span>
                  <span>TCP✅️</span>
                  <span>Connection Management✅️</span>
                  <span>Sliding Window✅️</span>
                  <span>Congestion Control✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Debugging</time>
              <div>
                <h4>Locating Protocol State Issues via Visual Logs</h4>
                <p>Utilized visual log tools to track TCP state transitions and data packet flows, locating logical issues caused by data retransmission, window updates, and state machine boundary conditions, and debugging/fixing issues for complex anomaly scenarios.</p>
                <div class="gain-tags">
                  <span>Log Visualization✅️</span>
                  <span>State Machine Debug✅️</span>
                  <span>Retransmission Mechanism✅️</span>
                  <span>Anomaly Localization✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Validation</time>
              <div>
                <h4>Validating System Robustness in Complex Network Anomaly Scenarios</h4>
                <p>Tested the protocol stack's performance in complex anomalous network environments such as packet loss and out-of-order delivery. Validated the stability and reliable transmission capabilities of the communication architecture, ultimately yielding underlying protocol source code and an analysis report, which strengthened understanding of underlying computer network mechanisms.</p>
                <div class="gain-tags">
                  <span>Packet Loss Scenarios✅️</span>
                  <span>Out-of-Order Scenarios✅️</span>
                  <span>Reliable Transmission✅️</span>
                  <span>System Robustness✅️</span>
                  <span>Analysis Report✅️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/buaa-logo.png" alt="Beihang University Logo" loading="lazy" />
          <div>
            <span class="research-label">BUAA · Multimodal LLM / Agent Memory</span>
            <h3>Prof. Rong Yin: Multimodal LLM Fine-Tuning and Agent Memory Research & Reproduction</h3>
          </div>
          <span class="research-period">2026.04 - 2026.05</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2026.04 - 2026.05</time>
              <div>
                <h4>Entering the Direction of Multimodal LLMs and Agent Memory</h4>
                <p>Participated in a research internship at the Department of Security Engineering, School of Cyberspace Security, Beihang University. Conducted literature reviews, method reproductions, and experimental workflow organization surrounding Multimodal LLM fine-tuning and Agent Memory, supplementing experience in training and fine-tuning Large Language Models.</p>
                <div class="gain-tags">
                  <span>Multimodal LLM✅️</span>
                  <span>Agent Memory✅️</span>
                  <span>Paper Research✅️</span>
                  <span>Method Reproduction⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Research</time>
              <div>
                <h4>Reviewing Multimodal Model Fine-Tuning and Memory Mechanisms</h4>
                <p>Focused on researching multimodal model training, instruction fine-tuning, agent memory mechanisms, and context management methods in long-term interaction scenarios. Gained an understanding of the potential applications of multimodal models in security, agents, and complex task execution scenarios.</p>
                <div class="gain-tags">
                  <span>Model Fine-Tuning✅️</span>
                  <span>Instruction Learning⬆️</span>
                  <span>Long-Term Memory⬆️</span>
                  <span>Security Applications⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Skill Enhancement</time>
              <div>
                <h4>Supplementing Engineering Experience in LLM Post-Training and Agents</h4>
                <p>Further familiarized with the foundational processes of LLM training, fine-tuning, and agent systems through literature reading, code reproduction, and experimental workflow sorting. This laid the foundation for subsequent research related to LLM security, multimodal reasoning, and Agent systems.</p>
                <div class="gain-tags">
                  <span>LLM Post-Training⬆️</span>
                  <span>Workflow Organization✅️</span>
                  <span>Code Reproduction✅️</span>
                  <span>Agent System Understanding⬆️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="Personal Project Logo" loading="lazy" />
          <div>
            <span class="research-label">Independent Project · LLM Engineering</span>
            <h3>MiniMind Reproduction and LLM Engineering Practice</h3>
          </div>
          <span class="research-period">Ongoing</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>Reproduction</time>
              <div>
                <h4>Reproducing Lightweight LLM System from 0 to 1</h4>
                <p>Independently reproduced the MiniMind system. Understood the basic engineering pipeline of Large Language Models by going through components such as tokenizers, model architecture, training data organization, training workflows, inference calls, and evaluation analysis, bridging the gap from algorithmic principles to code implementation.</p>
                <div class="gain-tags">
                  <span>MiniMind✅️</span>
                  <span>LLM Architecture✅️</span>
                  <span>Training Process✅️</span>
                  <span>Inference Process✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Practice</time>
              <div>
                <h4>Combining AI Toolchains to Enhance Prototype Development</h4>
                <p>Combined AI programming tools during the reproduction process for code comprehension, module breakdown, bug localization, and experimental iterations. Gradually developed the ability to utilize toolchains to assist in model reproduction, system debugging, and engineering implementation.</p>
                <div class="gain-tags">
                  <span>AI Toolchains✅️</span>
                  <span>Code Debugging✅️</span>
                  <span>Engineering Iteration✅️</span>
                  <span>Prototype Development⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>Accumulation</time>
              <div>
                <h4>Establishing Understanding of LLM Mechanisms and Post-Training Paradigms</h4>
                <p>Through MiniMind reproduction and related literature study, grasped the foundational mechanisms of LLM training, fine-tuning, and alignment. Established a preliminary understanding of post-training paradigms such as SFT, RL, PPO, DPO, and GRPO, providing a basis for future research in Multimodal LLMs and Agent directions.</p>
                <div class="gain-tags">
                  <span>SFT✅️</span>
                  <span>RLHF⬆️</span>
                  <span>PPO / DPO / GRPO⬆️</span>
                  <span>Post-Training Paradigms⬆️</span>
                  <span>LLM Engineering Foundation✅️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
    </div>
  </section>
</div>