<div class="research-page">
  <section class="home-section">
    <h2 class="home-section__title">交叉时间轴</h2>
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
        <strong>OUC 计算机视觉实验室</strong>
        <div class="lane-bar bar-ouc-cv">
          <span class="lane-date">2024.02 - 2024.10</span>
          <span>CLIP 先验引导 + Mamba 建模的自监督超声图像去噪</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>OUC 三维视觉课题组</strong>
        <div class="lane-bar bar-ouc-3d">
          <span class="lane-date">2025.10 - 2026.03</span>
          <span>UNIFI-AR：多模态 AI 融合增强现实展示系统</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>OUC 计算生物实验室</strong>
        <div class="lane-bar bar-ouc-cb">
          <span class="lane-date">2025.11 - 至今</span>
          <span>心脏超声影像自动标注与智能诊断</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>OUC 计算机网络实验室</strong>
        <div class="lane-bar bar-ouc-net">
          <span class="lane-date">2025.11 - 2026.01</span>
          <span>TCP 协议栈底层开发与可视化分析</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>BUAA 网络空间安全学院</strong>
        <div class="lane-bar bar-buaa">
          <span class="lane-date">2026.04 - 2026.05</span>
          <span>多模态 LLM 微调与 Agent Memory 调研复现</span>
        </div>
      </div>
      <div class="timeline-lane">
        <strong>Independent Project</strong>
        <div class="lane-bar bar-independent">
          <span class="lane-date">持续积累</span>
          <span>MiniMind 复现与大语言模型工程实践</span>
        </div>
      </div>
    </div>
  </section>

  <section class="home-section">
    <h2 class="home-section__title">详细科研与项目经历</h2>
    <div class="research-details">
      <details class="research-card" open>
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="中国海洋大学标识" loading="lazy" />
          <div>
            <span class="research-label">OUC · Computational Biology / Medical Image Segmentation</span>
            <h3>张树刚老师：心脏超声影像自动标注与智能诊断</h3>
          </div>
          <span class="research-period">2025.11 - 至今</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2025.11 - 至今</time>
              <div>
                <h4>面向复杂心脏超声场景的自动分割研究</h4>
                <p>在中国海洋大学计算生物实验室开展心脏超声图像自动化分割研究，重点面向多切面差异大、散斑噪声强、低对比度区域难以识别以及心肌等解剖结构边界模糊等问题，研究心房、心室及心肌等关键结构的精确标注方法。</p>
                <div class="gain-tags">
                  <span>心脏超声✅️</span>
                  <span>医学图像分割✅️</span>
                  <span>复杂解剖结构✅️</span>
                  <span>模糊边界建模⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>工程实现</time>
              <div>
                <h4>搭建多卡端到端深度学习流水线</h4>
                <p>独立搭建多卡 RTX 4090 环境下的端到端训练与评估流水线，覆盖超声图像标准化预处理、数据增强、模型训练、验证评估和结果可视化分析，形成从数据输入到实验结论输出的完整闭环。</p>
                <div class="gain-tags">
                  <span>RTX 4090✅️</span>
                  <span>多卡训练✅️</span>
                  <span>数据增强✅️</span>
                  <span>结果可视化✅️</span>
                  <span>实验闭环✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>模型设计</time>
              <div>
                <h4>设计 Boundary-Prediction Branch 强化边界感知</h4>
                <p>在 Denoising Diffusion Probabilistic Model 与空间注意力机制的基础上，设计 Boundary-Prediction Branch，通过显式预测目标区域边界信息，引导扩散去噪分支更准确地恢复复杂解剖结构的分割结果，从而提升低对比度区域和边界模糊区域的分割质量。</p>
                <div class="gain-tags">
                  <span>DDPM✅️</span>
                  <span>Spatial Attention✅️</span>
                  <span>Boundary Branch✅️</span>
                  <span>结构先验⬆️</span>
                  <span>边界感知分割⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>阶段成果</time>
              <div>
                <h4>公开数据集与真实临床数据双重验证</h4>
                <p>模型在 CAMUS 公开心脏超声数据集上完成验证，并在合作医院真实临床超声数据上进一步测试泛化能力。目前相关研究成果正在整理中，拟以第一作者身份投稿 MICCAI。</p>
                <div class="gain-tags">
                  <span>CAMUS✅️</span>
                  <span>临床数据验证✅️</span>
                  <span>泛化能力⬆️</span>
                  <span>一作论文整理中⬆️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="中国海洋大学标识" loading="lazy" />
          <div>
            <span class="research-label">OUC · Computer Vision / Ultrasound Image Denoising</span>
            <h3>计算机视觉实验室：基于先验信息引导的自监督超声图像去噪研究</h3>
          </div>
          <span class="research-period">2024.02 - 2024.10</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2024.02 - 2024.10</time>
              <div>
                <h4>面向中高噪声超声图像的自监督去噪方法设计</h4>
                <p>围绕自监督超声图像去噪任务开展研究，重点解决中高噪声条件下图像结构细节容易丢失、组织边缘不易保持等问题，提出融合 CLIP 先验引导与 Mamba 状态空间建模的去噪方法。</p>
                <div class="gain-tags">
                  <span>超声图像去噪✅️</span>
                  <span>自监督学习✅️</span>
                  <span>结构细节保持⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>先验引导</time>
              <div>
                <h4>设计基于图文约束的提示文本学习模块</h4>
                <p>利用预训练 CLIP 的图文对齐能力，将超声图像按照噪声程度构造正负样本，并通过图文相似度与交叉熵约束学习噪声相关提示表示，使模型能够从文本先验中获得噪声水平与图像质量的辅助信息。</p>
                <div class="gain-tags">
                  <span>CLIP✅️</span>
                  <span>Prompt Learning✅️</span>
                  <span>图文相似度✅️</span>
                  <span>交叉熵约束✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>网络结构</time>
              <div>
                <h4>构建 U-Net + Mamba 增强去噪网络</h4>
                <p>以 U-Net 为基础引入 Mamba 模块，增强模型对长程依赖和局部结构的建模能力，并结合提示文本细化、边缘排名损失、结构相似性损失、感知损失与边缘保持损失进行联合优化。</p>
                <div class="gain-tags">
                  <span>U-Net✅️</span>
                  <span>Mamba✅️</span>
                  <span>联合损失✅️</span>
                  <span>边缘保持✅️</span>
                  <span>长程建模⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>项目成果</time>
              <div>
                <h4>公开数据集验证与国家发明专利受理</h4>
                <p>在 CAMUS 与 BUSI 数据集的中高噪声条件下完成实验验证，实现平均 PSNR 提升 1.8 dB、SSIM 提升 2.7%。相关核心方案已作为第一发明人提交国家发明专利申请并获受理。</p>
                <div class="gain-tags">
                  <span>CAMUS✅️</span>
                  <span>BUSI✅️</span>
                  <span>PSNR +1.8 dB✅️</span>
                  <span>SSIM +2.7%✅️</span>
                  <span>发明专利受理✅️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="中国海洋大学标识" loading="lazy" />
          <div>
            <span class="research-label">OUC · 3D Vision / Multimodal AR System</span>
            <h3>张子悦老师：UNIFI-AR 多模态 AI 融合增强现实展示系统</h3>
          </div>
          <span class="research-period">2025.10 - 2026.03</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2025.10 - 2026.03</time>
              <div>
                <h4>面向 Apple Vision Pro 的沉浸式导览系统开发</h4>
                <p>作为核心成员参与 UNIFI-AR 多模态 AI 融合增强现实展示系统研发，基于 Apple Vision Pro 与 Unity 构建端到端沉浸式导览原型，重点关注空间计算场景下的多模态内容呈现与自然交互体验。</p>
                <div class="gain-tags">
                  <span>Apple Vision Pro✅️</span>
                  <span>Unity✅️</span>
                  <span>AR 系统开发✅️</span>
                  <span>空间计算⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>系统架构</time>
              <div>
                <h4>设计“时间线 + 状态机”多模态同步架构</h4>
                <p>集成 DeepSeek 与 TTS 实现展示内容自动化生成，并设计“时间线 + 有限状态机（FSM）”控制架构，以语音为主轴精准对齐文本、视觉高亮、动画效果和交互反馈，提升多模态展示的一致性与可控性。</p>
                <div class="gain-tags">
                  <span>DeepSeek✅️</span>
                  <span>TTS✅️</span>
                  <span>FSM✅️</span>
                  <span>多模态同步✅️</span>
                  <span>内容自动生成⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>交互实现</time>
              <div>
                <h4>实现动态视觉特效与眼动手势协同交互</h4>
                <p>使用 Shader Graph、程序化 Mesh 与 Unity XR Hands 实现动态高亮、参数化线框和“眼动 + 手势”协同的全息交互逻辑，使用户能够在空间场景中以更自然的方式完成浏览、聚焦与交互。</p>
                <div class="gain-tags">
                  <span>Shader Graph✅️</span>
                  <span>Procedural Mesh✅️</span>
                  <span>XR Hands✅️</span>
                  <span>眼动交互✅️</span>
                  <span>手势交互✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>系统评估</time>
              <div>
                <h4>交付高保真原型并完成用户体验评估</h4>
                <p>高质量交付沉浸式导览原型，并通过 UEQ 与 NASA-TLX 量表对用户体验、任务负荷与沉浸感进行评估。项目沉淀了高度解耦的模块化架构，为后续多文物、多场景适配提供了复用基础。</p>
                <div class="gain-tags">
                  <span>高保真原型✅️</span>
                  <span>UEQ✅️</span>
                  <span>NASA-TLX✅️</span>
                  <span>模块化架构✅️</span>
                  <span>跨场景复用⬆️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="中国海洋大学标识" loading="lazy" />
          <div>
            <span class="research-label">OUC · Computer Network / System Engineering</span>
            <h3>计算机网络实验室：基于仿真平台的 TCP 协议栈底层开发与可视化分析</h3>
          </div>
          <span class="research-period">2025.11 - 2026.01</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2025.11 - 2026.01</time>
              <div>
                <h4>独立构建 TCP 协议栈核心架构</h4>
                <p>围绕 TCP 协议栈底层实现与可靠通信机制开展项目实践，基于网络仿真平台使用 Java 独立构建完整协议栈，实现连接管理、滑动窗口、拥塞控制与完整状态机逻辑。</p>
                <div class="gain-tags">
                  <span>Java✅️</span>
                  <span>TCP✅️</span>
                  <span>连接管理✅️</span>
                  <span>滑动窗口✅️</span>
                  <span>拥塞控制✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>调试分析</time>
              <div>
                <h4>通过可视化日志定位协议状态问题</h4>
                <p>借助可视化日志工具追踪 TCP 状态转移与数据包流动过程，定位数据重传、窗口更新和状态机边界条件引发的逻辑问题，并针对复杂异常场景进行调试与修复。</p>
                <div class="gain-tags">
                  <span>日志可视化✅️</span>
                  <span>状态机 Debug✅️</span>
                  <span>重传机制✅️</span>
                  <span>异常定位✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>可靠性验证</time>
              <div>
                <h4>在复杂网络异常场景下验证系统鲁棒性</h4>
                <p>在丢包、乱序等复杂网络异常环境中测试协议栈表现，验证通信架构的稳定性和可靠传输能力，并最终产出底层协议源码与分析报告，强化了对计算机网络底层机制的理解。</p>
                <div class="gain-tags">
                  <span>丢包场景✅️</span>
                  <span>乱序场景✅️</span>
                  <span>可靠传输✅️</span>
                  <span>系统鲁棒性✅️</span>
                  <span>分析报告✅️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/buaa-logo.png" alt="北京航空航天大学标识" loading="lazy" />
          <div>
            <span class="research-label">BUAA · Multimodal LLM / Agent Memory</span>
            <h3>尹荣老师：多模态 LLM 微调与 Agent Memory 调研复现</h3>
          </div>
          <span class="research-period">2026.04 - 2026.05</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>2026.04 - 2026.05</time>
              <div>
                <h4>进入多模态大语言模型与智能体记忆方向</h4>
                <p>在北京航空航天大学网络空间安全学院安全工程系参与相关方向科研实习，围绕多模态 LLM 微调与 Agent Memory 展开论文调研、方法复现和实验流程梳理，补充大语言模型训练与微调经验。</p>
                <div class="gain-tags">
                  <span>Multimodal LLM✅️</span>
                  <span>Agent Memory✅️</span>
                  <span>论文调研✅️</span>
                  <span>方法复现⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>方向调研</time>
              <div>
                <h4>梳理多模态模型微调与记忆机制</h4>
                <p>重点调研多模态模型训练、指令微调、智能体记忆机制和长期交互场景中的上下文管理方法，理解多模态模型在安全、智能体和复杂任务执行场景中的潜在应用。</p>
                <div class="gain-tags">
                  <span>模型微调✅️</span>
                  <span>指令学习⬆️</span>
                  <span>长期记忆机制⬆️</span>
                  <span>安全应用场景⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>能力补充</time>
              <div>
                <h4>补充 LLM 后训练与智能体方向工程经验</h4>
                <p>通过文献阅读、代码复现与实验流程整理，进一步熟悉大语言模型训练、微调和智能体系统的基础流程，为后续开展大模型安全、多模态推理和 Agent 系统相关研究打下基础。</p>
                <div class="gain-tags">
                  <span>LLM 后训练⬆️</span>
                  <span>实验流程整理✅️</span>
                  <span>代码复现✅️</span>
                  <span>Agent 系统理解⬆️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
      <details class="research-card">
        <summary>
          <img class="research-logo" src="/images/homepage/ouc-logo.png" alt="个人项目标识" loading="lazy" />
          <div>
            <span class="research-label">Independent Project · LLM Engineering</span>
            <h3>MiniMind 复现与大语言模型工程实践</h3>
          </div>
          <span class="research-period">持续积累</span>
        </summary>
        <div class="research-body">
          <div class="detail-timeline">
            <article class="detail-step">
              <time>模型复现</time>
              <div>
                <h4>从 0 到 1 复现轻量级大语言模型系统</h4>
                <p>独立复现 MiniMind 系统，围绕 tokenizer、模型结构、训练数据组织、训练流程、推理调用和评测分析等环节理解大语言模型的基本工程链路，补充从算法原理到代码实现的完整认识。</p>
                <div class="gain-tags">
                  <span>MiniMind✅️</span>
                  <span>LLM 结构✅️</span>
                  <span>训练流程✅️</span>
                  <span>推理流程✅️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>工程实践</time>
              <div>
                <h4>结合 AI 工具链提升原型开发与代码落地能力</h4>
                <p>在复现过程中结合 AI 编程工具进行代码理解、模块拆解、Bug 定位和实验迭代，逐步形成利用工具链辅助完成模型复现、系统调试和工程实现的能力。</p>
                <div class="gain-tags">
                  <span>AI 工具链✅️</span>
                  <span>代码调试✅️</span>
                  <span>工程迭代✅️</span>
                  <span>原型开发⬆️</span>
                </div>
              </div>
            </article>
            <article class="detail-step">
              <time>能力沉淀</time>
              <div>
                <h4>建立大模型基础机制与后训练范式认知</h4>
                <p>通过 MiniMind 复现与相关文献学习，理解大语言模型训练、微调和对齐的基础机制，并对 SFT、RL、PPO、DPO、GRPO 等后训练范式建立初步认识，为后续多模态 LLM 与 Agent 方向研究提供基础。</p>
                <div class="gain-tags">
                  <span>SFT✅️</span>
                  <span>RLHF⬆️</span>
                  <span>PPO / DPO / GRPO⬆️</span>
                  <span>后训练范式⬆️</span>
                  <span>LLM 工程基础✅️</span>
                </div>
              </div>
            </article>
          </div>
        </div>
      </details>
    </div>
  </section>
</div>