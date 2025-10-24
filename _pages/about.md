---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently a second-year M.S. student (with thesis) in Computer Science at University of Illinois Urbana-Champaign (UIUC). I am a member of [iDEA-iSAIL Lab](https://www.idea-isail.com/index.html), advised by [Prof. Jingrui He](https://www.hejingrui.org/). Prior to this, I earned my B.S. with highest honors in Computer Engineering at UIUC. I have been fortunate to work with [Prof. Mengdi Wang](https://mwang.princeton.edu/) at Princeton University, and [Prof. James Zou](https://www.james-zou.com/) at Stanford University. Currently, I am a student researcher at [Google DeepMind](https://deepmind.google/). I also held research internships at [Amazon](https://www.amazon.science/) and [Microsoft Research](https://www.microsoft.com/en-us/research/) before.  

My research lies in the intersection of **machine learning** and **natural language processing**, with a specific focus on **LLMs Reasoning**. My research interests include but not limit to:
- **Agentic AI:** single/multi-agent systems, tool integrated LLMs.
- **LLM Post-Training:** RLHF, reward modeling.
- **Data-Centric Learning:** structure/multimodal data representation learning, effecient data selection and pruning.
- **Scientific Foundation Models:** AI for X (social science, weather forecasting, agriculture, clinic discovery, etc.).

I’m always happy to connect! Feel free to email me if you’d like to discuss my research interests or potential collaborations. Let’s cook up something cool together! 👨🏻‍🍳

<!-- 📌 <span style="color:red">I am actively seeking Ph.D. opportunities starting in Fall 2026. If there is a good fit, please feel free to reach out to me through email at jiaruz2 [at] illinois [dot] edu.</span> -->


# 📢 News

{: .news-scroll}
**[10/2025]** Receive the <span style="color:red;">**Best Paper Award**</span> in ICCV 2025 Workshop on MMRAgI!
**[10/2025]** Check [**TaTToo**](https://arxiv.org/abs/2510.06217), a special tool-grounded thinking PRM for test time scaling in tabular reasoning.\
**[10/2025]** Small model, Big mind 🧠. Check our [**new analytic study**](https://arxiv.org/pdf/2510.11701) on Agentic RL.\
**[10/2025]** Check [**RAG Over Tables**](https://arxiv.org/abs/2504.01346v4), a coarse-to-fine hierarchical Graph-Table-RAG framework with a new [**benchmark**](https://huggingface.co/collections/jiaruz2/multitableqa-68dc8d850ea7e168f47cecd8).\
**[09/2025]** Two papers accepted at NeurIPS 2025, including [**Transformer Copilot**](https://arxiv.org/abs/2505.16270) (<span style="color:red">**spotlight paper, top 3%**</span>) and [**ReasonFlux-PRM**](https://arxiv.org/abs/2506.18896).\
**[08/2025]** Start my internship as a student researcher at Google DeepMind GenAI team.\
**[05/2025]** Start my internship as an applied scientist at Amazon.\
**[05/2025]** One paper accepted at ACL 2025: [**STEM-PoM**](https://arxiv.org/abs/2411.00387), a benchmark on math-symbol reasoning.

<style>
.news-scroll {
  max-height: 220px; /* adjust for how much you want visible */
  overflow-y: auto;
  scroll-behavior: smooth;
}
.news-scroll::-webkit-scrollbar {
  width: 6px;
}
.news-scroll::-webkit-scrollbar-thumb {
  background: #ccc;
  border-radius: 3px;
}
.news-scroll::-webkit-scrollbar-thumb:hover {
  background: #999;
}
</style>



# 📄 Selected Publications ([Full List](https://scholar.google.com/citations?user=GzLTey4AAAAJ&hl=en))
(* denotes Equal Contribution)


<table style="border-collapse:collapse; border:none; margin:0; padding:0;">
<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/openRL.png" width="150" 
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      Preprint
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://arxiv.org/abs/2510.11701" 
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      Demystifying Reinforcement Learning in Agentic Reasoning
    </a><br/>
    <span style="font-size:16px;">
      Zhaochen Yu, Ling Yang, <strong>Jiaru Zou</strong>, Shuicheng Yan, Mengdi Wang
    </span><br/>
    <span style="font-size:16px; font-weight:bold;">
      Preprint
    </span>
  </p>
  <p>
    <a href="https://arxiv.org/pdf/2510.11701" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://github.com/Gen-Verse/Open-AgentRL" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Code</a>
    <a href="https://huggingface.co/Gen-Verse/DemyAgent-4B" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Model</a>
    <a href="https://huggingface.co/datasets/Gen-Verse/Open-AgentRL-30K" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Data</a>
    <a href="https://x.com/LingYang_PU/status/1977931241916862779" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Twitter</a>
  </p>
</td>
</tr>
</table>


<table style="border-collapse:collapse; border:none; margin:0; padding:0;">
<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/tattoo.png" width="150" 
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      FoRLM@NeurIPS 2025
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://arxiv.org/abs/2510.06217" 
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      TaTToo: Tool-Grounded Thinking PRM for Test-Time Scaling in Tabular Reasoning
    </a><br/>
    <span style="font-size:16px;">
      <strong>Jiaru Zou</strong>, Soumya Roy, Vinay Kumar Verma, Ziyi Wang, David Wipf, Pan Lu, 
      Sumit Negi, James Zou, Jingrui He
    </span><br/>
    <span style="font-size:16px; font-weight:bold;">
      FoRLM, NeurIPS 2025
    </span>
  </p>
  <p>
    <a href="https://arxiv.org/pdf/2510.06217" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://huggingface.co/papers/2510.06217" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">HuggingFace</a>
    <a href="https://x.com/Jiaru_Zou/status/1976122872671207676" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Twitter</a>
  </p>
</td>
</tr>
</table>

<table style="border-collapse:collapse; border:none; margin:0; padding:0;">
<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/rag_over_table.png" width="150" 
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      Preprint
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://arxiv.org/abs/2510.06217" 
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      RAG over Tables: Hierarchical Memory Index, Multi-Stage Retrieval, and Benchmarking
    </a><br/>
    <span style="font-size:16px;">
      <strong>Jiaru Zou*</strong>, Dongqi Fu*, Sirui Chen, Xinrui He, Zihao Li, Yada Zhu, Jiawei Han, Jingrui He
    </span><br/>
    <span style="font-size:16px;"><strong>Preprint</strong></span>
  </p>
  <p>
    <a href="https://arxiv.org/abs/2504.01346v4" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://huggingface.co/collections/jiaruz2/multitableqa-68dc8d850ea7e168f47cecd8" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Data</a>
    <a href="https://github.com/jiaruzouu/T-RAG" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Code</a>
    <a href="https://www.linkedin.com/posts/jiaruzou_graphrag-rag-tablereasoning-activity-7383267082693533696-KlrJ?utm_source=share&utm_medium=member_desktop&rcm=ACoAADc5TzgBN_tNOuzpi7kE7n6dZ0y13EkxZOs" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Post</a>
    <a href="https://x.com/Jiaru_Zou/status/1977869000274055170" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Twitter</a>
    <a href="https://medium.com/@namanlazarus/gtr-graph-table-rag-for-cross-table-question-answering-f8ed7cdc44cf" 
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Medium</a>
  </p>
</td>
</tr>
</table>

<table style="border-collapse:collapse; border:none; margin:0; padding:0;">
<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/copilot.png" width="150"
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      NeurIPS 2025 (Spotlight)
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://arxiv.org/abs/2505.16270"
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      Transformer Copilot: Learning from The Mistake Log in LLM Fine-tuning
    </a><br/>
    <span style="font-size:16px;">
      <strong>Jiaru Zou</strong>, Yikun Ban, Zihao Li, Yunzhe Qi, Ruizhong Qiu, Ling Yang, Jingrui He
    </span><br/>
    <span style="font-size:16px;">
      <strong>NeurIPS 2025 <span style="color:#FF4C4C;">(spotlight, top 3%)</span></strong>
    </span>
  </p>
  <p>
    <a href="https://arxiv.org/pdf/2505.16270"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://github.com/jiaruzouu/TransformerCopilot"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Code</a>
  </p>
</td>
</tr>



<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/reasonflux-prm.png" width="150"
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      NeurIPS 2025
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://arxiv.org/abs/2506.18896"
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      ReasonFlux-PRM: Trajectory-Aware PRMs for Long Chain-of-Thought Reasoning in LLMs
    </a><br/>
    <span style="font-size:16px;">
      <strong>Jiaru Zou*</strong>, Ling Yang*, Jingwen Gu*, Jiahao Qiu, Ke Shen, Jingrui He, Mengdi Wang
    </span><br/>
    <span style="font-size:16px;">
      <strong>NeurIPS 2025 <span style="color:#FF4C4C;">(500+ stars on GitHub)</span></strong>
    </span>
  </p>
  <p>
    <a href="https://arxiv.org/pdf/2506.18896"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://github.com/Gen-Verse/ReasonFlux"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Code</a>
    <a href="https://huggingface.co/collections/Gen-Verse/reasonflux-prm-68463c73cf1c6a0ec6fafeb5"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Models</a>
    <a href="https://x.com/_akhaliq/status/1937345023005048925"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Twitter</a>
  </p>
</td>
</tr>



<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/stem-pom.png" width="150"
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      ACL 2025
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://arxiv.org/abs/2411.00387"
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      STEM-PoM: Evaluating Language Models Math-Symbol Reasoning in Document Parsing
    </a><br/>
    <span style="font-size:16px;">
      <strong>Jiaru Zou</strong>, Qing Wang, Pratyush Thakur, Nickvash Kani
    </span><br/>
    <span style="font-size:16px;">
      <strong>ACL 2025; Math-AI, NeurIPS 2024</strong>
    </span>
  </p>
  <p>
    <a href="https://arxiv.org/pdf/2411.00387"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://github.com/jiaruzouu/STEM-PoM"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Code</a>
    <a href="https://github.com/jiaruzouu/STEM-PoM"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Data</a>
  </p>
</td>
</tr>

<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/prb.png" width="150"
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      NeurIPS 2024
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://openreview.net/forum?id=VSz9na5Jtl&noteId=haaAwoAULA"
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      PageRank Bandits for Link Prediction
    </a><br/>
    <span style="font-size:16px;">
      Yikun Ban*, <strong>Jiaru Zou*</strong>, Zihao Li, Yunzhe Qi, Dongqi Fu, Jian Kang, Hanghang Tong, Jingrui He
    </span><br/>
    <span style="font-size:16px;"><strong>NeurIPS 2024</strong></span>
  </p>
  <p>
    <a href="https://openreview.net/pdf?id=VSz9na5Jtl"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://github.com/jiaruzouu/PRB"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Code</a>
  </p>
</td>
</tr>



<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/promptintern.png" width="150"
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      EMNLP 2024
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://arxiv.org/abs/2407.02211"
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      PromptIntern: Saving Inference Costs by Internalizing Recurrent Prompt during LLM Fine-tuning
    </a><br/>
    <span style="font-size:16px;">
      <strong>Jiaru Zou</strong>, Mengyu Zhou, Tao Li, Shi Han, Dongmei Zhang
    </span><br/>
    <span style="font-size:16px;"><strong>EMNLP 2024</strong></span>
  </p>
  <p>
    <a href="https://arxiv.org/pdf/2407.02211"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://github.com/microsoft/PromptIntern"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Code</a>
  </p>
</td>
</tr>



<tr>
<td width="160" style="border:none; vertical-align:top;">
  <img src="images/papers/tap4llm.png" width="136"
       style="border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.15);"/>
  <div style="margin-top:8px;">
    <span style="background:#003366; color:white; padding:3px 6px; border-radius:4px; font-size:12px;">
      EMNLP 2024
    </span>
  </div>
</td>
<td style="border:none; padding-left:20px; vertical-align:top;">
  <p>
    <a href="https://arxiv.org/abs/2312.09039"
       style="font-size:18px; font-weight:bold; color:inherit; text-decoration:none;">
      TAP4LLM: Table Provider on Sampling, Augmenting, and Packing Semi-structured Data for Large Language Model Reasoning
    </a><br/>
    <span style="font-size:16px;">
      Yuan Sui*, <strong>Jiaru Zou*</strong>, Mengyu Zhou, Xinyi He, Lun Du, Shi Han, Dongmei Zhang
    </span><br/>
    <span style="font-size:16px;">
      <strong>
        EMNLP 2024
        <span style="color:#FF4C4C;">
          (Featured in 
          <a href="https://www.microsoft.com/en-us/microsoft-365/copilot/try-copilot-chat?ccac=copilotchat&ef_id=_k_Cj0KCQjwgKjHBhChARIsAPJR3xdO56awHpRnTMoSDnW0sCOeTawVcY3uODYt7rpsdyYCq5mjAFOurWEaAoJ-EALw_wcB_k_&OCID=AIDcmmhexn0fwe_SEM__k_Cj0KCQjwgKjHBhChARIsAPJR3xdO56awHpRnTMoSDnW0sCOeTawVcY3uODYt7rpsdyYCq5mjAFOurWEaAoJ-EALw_wcB_k_&gad_source=1&gad_campaignid=22353285968&gbraid=0AAAAADcJh_v7YsYOXtUgWuGXSxB6hjMC6&gclid=Cj0KCQjwgKjHBhChARIsAPJR3xdO56awHpRnTMoSDnW0sCOeTawVcY3uODYt7rpsdyYCq5mjAFOurWEaAoJ-EALw_wcB"
            style="color:#FF4C4C; text-decoration:none; font-weight:bold;">
            Microsoft Excel Copilot)
          </a>
        </span>
      </strong>
    </span>
  </p>
  <p>
    <a href="https://arxiv.org/pdf/2312.09039"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">PDF</a>
    <a href="https://github.com/microsoft/TableProvider/tree/main"
       style="border:1px solid black; padding:3px 6px; text-decoration:none;">Code</a>
  </p>
</td>
</tr>
</table>

<br>

# 💼 Selected Experience

<table style="width:100%; border:none !important; border-collapse:collapse !important; margin:0 !important; padding:0 !important; background:transparent !important;">
  <tr style="border:none !important;">
    <td style="vertical-align:top; text-align:left; padding:0 !important; border:none !important;">
      <p style="margin:0; font-size:20px; font-weight:600; color:inherit;">
        Princeton AI Lab
      </p>
      <p style="margin:4px 0 0 0; font-size:18px; color:inherit;">
        Research Assistant, 2025
      </p>
      <p style="margin:4px 0 0 0; font-size:18px; color:inherit;">
        Research Topic: <strong>Process Reward Model, LLM Agents</strong>
      </p>
    </td>

    <td style="text-align:right; vertical-align:middle; padding:0 !important; border:none !important;">
      <img src="images/company/princeton.png" alt="Princeton Logo"
           style="width:250px; max-width:100%; border-radius:8px; box-shadow:0 4px 12px rgba(0,0,0,0.08);"/>
    </td>
  </tr>
</table>


<br>

<table style="width:100%; border:none !important; border-collapse:collapse !important; margin:0 !important; padding:0 !important; background:transparent !important;">
  <tr style="border:none !important;">
    <!-- Left column -->
    <td style="vertical-align:top; text-align:left; padding:0 !important; border:none !important;">
      <p style="margin:0; font-size:20px; font-weight:600; color:var(--text-primary);">
        Google DeepMind
      </p>
      <p style="margin:4px 0 0 0; font-size:18px; color:var(--text-secondary);">
        Student Researcher (part-time), 2025
      </p>
      <p style="margin:4px 0 0 0; font-size:18px; color:var(--text-secondary);">
        Research Topic: <strong>Agentic RL, GUI Agent, AI for Science</strong>
      </p>
    </td>

    <!-- Right column -->
    <td style="text-align:right; vertical-align:middle; padding:0 !important; border:none !important;">
      <img src="images/company/gdm.png" alt="Google DeepMind Logo"
           style="width:240px; max-width:100%; border-radius:8px; box-shadow:0 4px 12px rgba(0,0,0,0.08);"/>
    </td>
  </tr>
</table>

<br>

<table style="width:100%; border:none !important; border-collapse:collapse !important; margin:0 !important; padding:0 !important; background:transparent !important;">
  <tr style="border:none !important;">
    <!-- Left column -->
    <td style="vertical-align:top; text-align:left; padding:0 !important; border:none !important;">
      <p style="margin:0; font-size:20px; font-weight:600; color:var(--text-primary);">
        Amazon
      </p>
      <p style="margin:4px 0 0 0; font-size:18px; color:var(--text-secondary);">
        Applied Scientist Intern, 2025
      </p>
      <p style="margin:4px 0 0 0; font-size:18px; color:var(--text-secondary);">
        Research Topic: <strong>Reward Modeling, Speculative Decoding</strong>
      </p>
    </td>

    <!-- Right column -->
    <td style="text-align:right; vertical-align:middle; padding:0 !important; border:none !important;">
      <img src="images/company/amazon.png" alt="Amazon Logo"
           style="width:210px; max-width:100%; border-radius:8px; box-shadow:0 4px 12px rgba(0,0,0,0.08);"/>
    </td>
  </tr>
</table>

<br>

<table style="width:100%; border:none !important; border-collapse:collapse !important; margin:0 !important; padding:0 !important; background:transparent !important;">
  <tr style="border:none !important;">
    <!-- Left column -->
    <td style="vertical-align:top; text-align:left; padding:0 !important; border:none !important;">
      <p style="margin:0; font-size:20px; font-weight:600; color:var(--text-primary);">
        Microsoft Research
      </p>
      <p style="margin:4px 0 0 0; font-size:18px; color:var(--text-secondary);">
        Research Intern, 2023-2024
      </p>
      <p style="margin:4px 0 0 0; font-size:18px; color:var(--text-secondary);">
        Research Topic: <strong>Stucture data representation learning, Code generation, Prompt Compression, Data Pruning</strong>
      </p>
    </td>

    <!-- Right column -->
    <td style="text-align:right; vertical-align:middle; padding:0 !important; border:none !important;">
      <img src="images/company/msr.png" alt="MicrosoftLogo"
           style="width:340px; max-width:100%; border-radius:8px; box-shadow:0 4px 12px rgba(0,0,0,0.08);"/>
    </td>
  </tr>
</table>

<br>


# ✨ Honors & Awards

- ICCV 2025 Workshop Best Paper Award, 2025
- NeurIPS 2025 Scholar Award, 2025
- Highest Honor Graduation at UIUC, 2024
- Microsoft Stars of Tomorrow Award, 2023
- O. Thomas and Martha S. Purl Scholarship, 2023
- Daniel W. and Carol A. Dobberpuhl Student Award, 2023
- Illinois Engineering Outstanding & Achievement Scholarship, 2023
- Professor N. Narayana Rao Scholarship, 2022
- Edmund J. James Scholarship, 2021

# 🌍 Academic Services

- **Conference Program Committee/Reviewer:** ICLR 2026, AAAI 2026, NeurIPS 2025, ICML 2025, ARR Rolling Review (Oct 2024, Dec 2024, May 2025, July 2025, Oct 2025)

- **Journal Reviewer:** IEEE Transactions on Knowledge and Data Engineering (TKDE), ACM Transactions on Knowledge Discovery from Data (TKDD), ACM Computing Surveys

- **Conference Student Volunteer:** EMNLP’24, NeurIPS’24

- **Teaching Experience:**
  - **Graduate Teaching Assistant:** UIUC CS307 (Fall 2024), UIUC CS128 (Spring 2025)
  - **Course Assistant/Grader:** UIUC CS/ECE374 (Head CA), ECE210, ECE310, ECE313


# 🧩 Miscellaneous

<p style="font-size:18px; line-height:1.6; color:inherit;">
  I’m a <strong>boarder</strong> through and through — 🏂 snowboarding is my favorite ride 
  (my setup: <strong>Burton Custom X Flying V</strong> for all-mountain ride, and 
  <strong>YES BASIC</strong> for freestyle and park ride). 
  You’ll also find me carving pavement on a skateboard or chasing waves on a surfboard. 
  Maybe one day I’ll earn my spot as an 
  <a href="https://www.xgames.com/" target="_blank" style="color:#003366; font-weight:bold; text-decoration:none;">
    X-Gamer
  </a>. Some of my riding pictures below:
</p>


<div class="snowboard-gallery">
  <img src="images/misc/snowboard1.png" alt="Snowboard 1">
  <img src="images/misc/snowboard2.png" alt="Snowboard 2">
  <img src="images/misc/snowboard3.png" alt="Snowboard 3">
</div>

<br>
<p style="font-size:18px; line-height:1.6; color:inherit;">
  I am also a fan of <strong>📸 Conceptual Photography</strong> and <strong>🎨 Visual Aesthetics</strong>.
</p>
<div style="border-left:4px solid #003366; padding-left:14px; margin:12px 0; color:#444; font-size:16px; font-style:italic; background:#f9f9f9; border-radius:6px; box-shadow:0 2px 6px rgba(0,0,0,0.05);">
  A glimpse of my visual world — abstract forms, motion, and color captured through my lens.
</div>


<div class="image-grid">
  <img src="images/misc/art1.png" alt="Color abstraction" />
  <img src="images/misc/art2.png" alt="Abstract installation" />
  <img src="images/misc/art3.png" alt="Portrait fusion" />
  <img src="images/misc/art4.png" alt="Ruined structure" />
  <img src="images/misc/art5.png" alt="Horse close-up" />
</div>

<div class="lightbox-overlay" id="lightbox">
  <span class="close-btn">&times;</span>
  <img src="" alt="Expanded image" id="lightbox-img" />
</div>

<script>
// --- Unified lightbox for both galleries ---
document.querySelectorAll('.image-grid img, .snowboard-gallery img').forEach(img => {
  img.addEventListener('click', () => {
    const lightbox = document.getElementById('lightbox');
    const lightboxImg = document.getElementById('lightbox-img');
    lightboxImg.src = img.src;
    lightbox.classList.add('active');
    document.body.style.overflow = 'hidden'; // prevent scroll behind overlay
  });
});

document.querySelector('.lightbox-overlay .close-btn').addEventListener('click', () => {
  const lightbox = document.getElementById('lightbox');
  lightbox.classList.remove('active');
  document.body.style.overflow = ''; // restore scroll
});

// Allow click outside image to close
document.getElementById('lightbox').addEventListener('click', e => {
  if (e.target === e.currentTarget) {
    e.currentTarget.classList.remove('active');
    document.body.style.overflow = '';
  }
});
</script>



<br><br>
<div style="
  text-align:center;
  margin: 40px auto;
">
  <a href='https://clustrmaps.com/site/1c87x' title='Visit tracker' target="_blank">
    <img 
      src='https://clustrmaps.com/map_v2.png?cl=7f9de8&w=500&t=n&d=Y1dpqO88hB2DPdczZSnpMGGzp2rovUGVhiqwICY6ChI&co=ffffff&ct=ffffff'
      alt='Visitor Map'
      style="
        width:400px;
        max-width:80%;
        border-radius:12px;
        box-shadow:0 4px 20px rgba(0,0,0,0.15);
        transition: all 0.3s ease;
      "
      onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 8px 28px rgba(0,0,0,0.25)'"
      onmouseout="this.style.transform='scale(1.0)'; this.style.boxShadow='0 4px 20px rgba(0,0,0,0.15)'"
    />
  </a>
  <p style="color:#666; font-size:14px; margin-top:6px;">🌍 Visitors around the world</p>
</div>
