---
layout: default
---
<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/face.png" style="width:100%">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;">
             I am a Research Scientist at <a href="https://megagon.ai">Megagon Labs</a>. Prior to Megagon, I was a PhD student in Machine Learning at the University of California Irvine, advised by Prof.                       <a href="http://sameersingh.org">Sameer Singh</a>. My main area of interest includes Natural Language Understanding, Interpretability and Analysis of Models, and Knowledge Representation and Reasoning.
          </p>
        </td>
      </tr>
   </table>
</div>

# Research Internships

* * *
<ul>
  <li>Semantic Machines at Microsoft Research, summer 2021.</li>
  <li>Siri Knowledge group at Apple, summer 2020.</li>
  <li>Allen Institute for Artificial Intelligence, summer 2019.</li>
  <li>Fujitsu Laboratories of America, summer 2018. </li>
  <li>Chinese University of Hong Kong, summer 2014.  </li>
</ul>

# Professional Experience
* * *

<ul>
   <li>Co-organised Explainable Graph-Based Machine Learning workshop at AKBC <a href="https://xgml.github.io">2021</a>.</li>
  <li>Co-organised Knowledge Bases and Multiple Modalities workshop at AKBC <a href="https://kb-mm.github.io">2019</a> and <a href="https://kb-mm-2020.github.io">2020</a>.</li>
   <li>2021: Reviewer at NeurIPS, NAACL</li>
  <li>2020: Reviewer at NeurIPS, ICLR, AAAI, EMNLP</li>
  <li>2019: Reviewer at NeurIPS, ICLR, EMNLP</li>
  <li>2018: Reviewer at EMNLP</li>
  <li>Volunteer at NeurIPS 2018 and AKBC 2020.</li>
</ul>

# Preprints
* * *
<ul>
   <li><b>Pouya Pezeshkpour</b>, Moin Aminnaseri, Estevam Hruschka, "<a href="https://arxiv.org/pdf/2504.08974">Mixed Signals: Decoding VLMs' Reasoning and Underlying Bias in Vision-Language Conflict</a>".</li>
   <li><b>Pouya Pezeshkpour</b>, Estevam Hruschka, "<a href="https://arxiv.org/pdf/2504.00187">Insight-RAG: Enhancing LLMs with Insight-Driven Augmentation</a>".</li>
   <li><b>Pouya Pezeshkpour</b>, Estevam Hruschka, "<a href="https://arxiv.org/abs/2501.17840">Learning Beyond the Surface: How Far Can Continual Pre-Training with LoRA Enhance LLMs' Domain-Specific Insight Learning?</a>".</li>
  <li>Vishwas Mruthyunjaya, <b>Pouya Pezeshkpour</b>, et al, "<a href="https://arxiv.org/pdf/2308.13676">Rethinking Language Models as Symbolic Knowledge Graphs</a>".</li>
  <li><b>Pouya Pezeshkpour</b>, et al, "<a href="https://arxiv.org/pdf/2311.06383.pdf">Distilling Large Language Models using Skill-Occupation Graph Context for HR-Related Tasks</a>".</li>
</ul>


# Conference & Journal Publications
* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/mdc.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">From Single to Multi: How LLMs Hallucinate in Multi-Document Summarization</font><br>
              <font style="font-size:15px">Catarina G. Belem, <b>Pouya Pezeshkpour</b>, et al<br>
              NAACL (Findings) 2025</font><br> 
             </p><p align="justify"> <font style="font-size:13px">Although many studies have investigated and reduced hallucinations in large language models (LLMs) for single-document tasks, research on hallucination in multi-document summarization (MDS) tasks remains largely unexplored. In this work, we investigate how hallucinations manifest in LLMs when summarizing topic-specific information from multiple documents. Since no benchmarks exist for investigating hallucinations in MDS, we use existing news and conversation datasets, annotated with topic-specific insights, to create two novel multi-document benchmarks. When evaluating 5 LLMs on our benchmarks, we observe that on average, up to 75% of the content in LLM-generated summaries is hallucinated, with hallucinations more likely to occur towards the end of the summaries. Moreover, when summarizing non-existent topic-related information, gpt-3.5-turbo and GPT-4o still generate summaries about 79.35% and 44% of the time. To understand the characteristics of these hallucinations, we manually evaluate 700+ insights and find that most errors stem from either failing to follow instructions or producing overly generic insights. 
Motivated by these observations, we investigate the efficacy of simple post-hoc baselines in mitigating hallucinations but find them only moderately effective. 
 </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2410.13961">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>
* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/exsir.jpg" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Multi-Conditional Ranking with Large Language Models</font><br>
              <font style="font-size:15px"><b>Pouya Pezeshkpour</b>, Estevam Hruschka<br>
              NAACL 2025</font><br> 
             </p><p align="justify"> <font style="font-size:13px">Utilizing large language models (LLMs) to rank a set of items has become a common approach in recommendation and retrieval systems. Typically, these systems focus on ordering a substantial number of documents in a monotonic order based on a given query. However, real-world scenarios often present a different challenge: ranking a comparatively smaller set of items, but according to a variety of diverse and occasionally conflicting conditions. In this paper, we define and explore the task of multi-conditional ranking by introducing MCRank, a benchmark tailored for assessing multi-conditional ranking across various item types and conditions. Our analysis of LLMs using MCRank indicates a significant decrease in performance as the number and complexity of items and conditions grow. To overcome this limitation, we propose a novel decomposed reasoning method, consisting of EXtracting and Sorting the conditions, and then Iteratively Ranking the items (EXSIR). Our extensive experiments show that this decomposed reasoning method enhances LLMs' performance significantly, achieving up to a 14.4% improvement over existing LLMs.
 </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2404.00211.pdf">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>
* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/fair.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Evaluating Bias in LLMs for Job-Resume Matching: Gender, Race, and Education</font><br>
              <font style="font-size:15px">Hayate Iso, <b>Pouya Pezeshkpour</b>, et al.<br>
              NAACL 2025 (Industry Track)</font><br> 
             </p><p align="justify"> <font style="font-size:13px">LLMs can automate hiring by matching job descriptions with resumes and reducing costs, but they may also reinforce biases. This study evaluates the fairness of LLMs in U.S. English-language job-resume matching by examining gender, race, and educational background. Our findings indicate that recent models have reduced biases related to explicit attributes like gender and race, yet significant implicit biases concerning educational background persist, underscoring the need for better bias mitigation strategies.
 </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2503.19182">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>
* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/matt.jpg" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">LLMs Are Not Intelligent Thinkers: Introducing Mathematical Topic Tree Benchmark for Comprehensive Evaluation of LLMs</font><br>
              <font style="font-size:15px">Arash Gholami, Pouyan Mousavi, <b>Pouya Pezeshkpour</b> <br>
              NAACL 2025</font><br> 
             </p><p align="justify"> <font style="font-size:13px">Large language models (LLMs) demonstrate impressive capabilities in mathematical reasoning. However, despite these achievements, current evaluations are mostly limited to specific mathematical topics, and it remains unclear whether LLMs are genuinely engaging in reasoning. To address these gaps, we present the Mathematical Topics Tree (MaTT) benchmark, a challenging and structured benchmark that offers 1,958 questions across a wide array of mathematical subjects, each paired with a detailed hierarchical chain of topics. Upon assessing different LLMs using the MaTT benchmark, we find that GPT-4 achieved a mere 54% accuracy in a multiple-choice scenario. Moreover, LLMs accuracy dramatically reduced by up to 24.2 percentage point when the questions were presented without providing choices. In an effort to pinpoint the reasons behind LLMs performances, we conducted a manual evaluation of the completeness and correctness of the explanations generated by GPT-4 when choices were available. Surprisingly, we find that in only 53.3% of the instances where the model provided a correct answer, the accompanying explanations were deemed complete and accurate, i.e., the model engaged in genuine  reasoning.
 </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2406.05194.pdf">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>
* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/sensitive.jpg" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Large Language Models Sensitivity to The Order of Options in Multiple-Choice Questions</font><br>
              <font style="font-size:15px"><b>Pouya Pezeshkpour</b>, Estevam Hruschka<br>
              NAACL (Findings) 2024</font><br> 
             </p><p align="justify"> <font style="font-size:13px">Large Language Models (LLMs) have demonstrated remarkable capabilities in various NLP tasks. However, previous works have shown these models are sensitive towards prompt wording, and few-shot demonstrations and their order, posing challenges to fair assessment of these models. In this paper, we focus on LLMs robustness on the task of multiple-choice questions, commonly adopted task to study reasoning and fact-retrieving capability of LLMs. Investigating the sensitivity of LLMs towards the order of options in multiple-choice questions, we demonstrate a considerable performance gap of approximately 13% to 75% in LLMs on different benchmarks, when answer options are reordered, even when using demonstrations in
a few-shot setting. Through a detailed analysis, we conjecture that this sensitivity arises when LLMs are uncertain about the prediction between the top-2/3 choices and adopt two approaches to calibrate LLMs’ predictions, leading to up to 8 percentage points improvement across different models and benchmarks.
 </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2308.11483.pdf">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/nlg-eval.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Less is More for Long Document Summary Evaluation by LLMs</font><br>
              <font style="font-size:15px">Yunshu Wu, Hayate Iso, <b>Pouya Pezeshkpour</b>, et al<br>
              EACL 2024</font><br> 
             </p><p align="justify"> <font style="font-size:13px">Large Language Models (LLMs) have shown promising performance in summary evaluation tasks, yet they face challenges such as high computational costs and the Lost-in-the-Middle problem where important information in the middle of long documents is often overlooked. To address these issues, this paper introduces a novel approach, Extract-then-Evaluate, which involves extracting key sentences from a long source document and then evaluating the summary by prompting LLMs. The results reveal that the proposed method not only significantly reduces evaluation costs but also exhibits a higher correlation with human evaluations. Furthermore, we provide practical recommendations for optimal document length and sentence extraction methods, contributing to the development of cost-effective yet more accurate methods for LLM-based text generation evaluation.
 </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2309.07382">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/measure.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Measuring and Modifying Factual Knowledge in Large Language Models</font><br>
              <font style="font-size:15px"><b>Pouya Pezeshkpour</b><br>
              ICMLA 2023</font><br> 
             </p><p align="justify"> <font style="font-size:13px">In this work, we employ information theory-based measurements to provide a framework estimating the factual knowledge contained within large language models. More specifically, we measure knowledge by analyzing the LLM’s prediction probability distribution before and after instilling the target knowledge, employing metrics such as entropy and KL-divergence. Introducing our metrics, we first assess their accuracy in comparison to previous ranking-based methods, surpassing them by over 35% in a synthetic experiment. Then, we explore two prominent methods of knowledge instillation, discovering that LLMs exhibit limitations in capturing new knowledge under specific circumstances for one of these methods. Lastly, we demonstrate the applicability of our methods in extracting unlearned and mislearned facts in LLMs through their application to in-context learning.
 </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2306.06264.pdf">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/big.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Beyond the Imitation Game: Quantifying and extrapolating the capabilities of language models</font><br>
              <font style="font-size:15px">Aarohi Srivastava, et al.<br>
              TMLR 2023</font><br> 
             </p><p align="justify"> <font style="font-size:13px">In this paper we introduce the Beyond the Imitation Game benchmark (BIG-bench). BIG-bench currently consists of 204 tasks, with diverse topics about drawing problems from linguistics, childhood development, math, common-sense reasoning, biology, physics, social bias, software development, and beyond. BIG-bench focuses on tasks that are believed to be beyond the capabilities of current language models. We evaluate the behavior of OpenAI’s GPT models, Google-internal dense transformer architectures, and Switch-style sparse transformers on BIG-bench, across model sizes spanning millions to hundreds of billions of parameters. Findings include: model performance and calibration both improve with scale; tasks that improve gradually and predictably commonly involve a large knowledge or memorization component, whereas tasks that exhibit “breakthrough” behavior at a critical scale often involve multiple steps; social bias typically increases with scale in ambiguous settings, but this can be improved with prompting.
 </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2206.04615.pdf">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/gain.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">The Extremal GDoF Gain of Optimal versus Binary Power Control in 𝐾 User Interference Networks Is Θ(&radic;<span style="text-decoration: overline">k</span>)</font><br>
              <font style="font-size:15px">Yao-Chia Chan, <b>Pouya Pezeshkpour</b>, Chunhua Geng, Syed A. Jafar<br>
              IEEE Transactions on Wireless Communications 2022</font><br> 
             </p><p align="justify"> <font style="font-size:13px">In this paper we explicitly characterizes the extremal GDoF gain of optimal over binary power control as Θ(&radic;<span style="text-decoration: overline">k</span>) for all 𝐾. In particular, the extremal gain is bounded between
&radic;<span style="text-decoration: overline">k</span> and 2.5 &radic;<span style="text-decoration: overline">k</span> for every 𝐾. For 𝐾 = 2, 3, 4, 5, 6 users, the precise extremal gain is 1, 3/2, 2, 9/4 and 41/16, respectively. Networks shown to achieve the extremal gain may be interpreted as multi-tier heterogeneous networks. It is worthwhile to note that because of their focus on asymptotic analysis, the sharp characterizations of extremal gains are valuable primarily from a theoretical perspective, and not as contradictions to the conventional w. </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2205.02216.pdf">PDF</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *


<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/artifact.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Combining Feature and Instance Attribution to Detect Artifacts</font><br>
              <font style="font-size:15px"><b>Pouya Pezeshkpour</b>, Sarthak Jain, Byron Wallace, Sameer Singh<br>
              ACL 2022</font><br> 
             </p><p align="justify"> <font style="font-size:13px">In this paper we evaluate use of different attribution methods for aiding identification of training data artifacts. We propose new hybrid approaches that combine saliency maps (which highlight "important" input features) with instance attribution methods (which retrieve training samples "influential" to a given prediction). We show that this proposed training-feature attribution can be used to efficiently uncover artifacts in training data when a challenging validation set is available. We also carry out a small user study to evaluate whether these methods are useful to NLP researchers in practice, with promising results. </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2107.00323.pdf">PDF</a>&nbsp;&nbsp;&nbsp;<a href="https://www.youtube.com/watch?v=1xXnio8AdpY&t=141s">Video on Youtube</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/emp-inf.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">An Empirical Comparison of Instance Attribution Methods for NLP</font><br>
              <font style="font-size:15px"><b>Pouya Pezeshkpour</b>, Sarthak Jain, Byron Wallace, Sameer Singh<br>
              NAACL 2021</font><br> 
             </p><p align="justify"> <font style="font-size:13px">In this work we evaluate the degree to which different potential instance attribution agree with respect to the importance of training samples.
We find that simple retrieval methods yield training instances that differ from those identified via gradient-based methods (such as the IF), but that nonetheless exhibit desirable characteristics similar to more complex attribution methods. </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2104.04128.pdf">PDF</a>&nbsp;&nbsp;&nbsp;  <a href="https://github.com/successar/instance_attributions_NLP">Source Code</a> &nbsp;&nbsp;&nbsp;   <a href="https://www.youtube.com/watch?v=b9AbcEDmFyg&t=17s">Video on Youtube</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/parsinlu.png" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">PARSINLU: A Suite of Language Understanding Challenges for Persian</font><br>
              <font style="font-size:15px">Daniel Khashabi, Arman Cohan, Siamak Shakeri, Pedram Hosseini, <b>Pouya Pezeshkpour</b>, et al<br>
              TACL 2021</font><br> 
             </p><p align="justify"> <font style="font-size:13px">We introduce PARSINLU, the first benchmark in Persian language that includes a range of high-level tasks, Reading Comprehension, Textual Entailment, etc. These datasets are collected in a multitude of ways, often involving manual annotations by native speakers. This results in over 14.5k new instances across 6 distinct NLU tasks. Besides, we present the first results on state-of-the-art monolingual and multi- lingual pre-trained language models on this benchmark and compare them with human performance, which provides valuable in- sights into our ability to tackle natural language understanding challenges in Persian. </font><br></p>
                      <p align="center">
             <font style="font-size:15px"><a href="https://arxiv.org/pdf/2012.06154.pdf">PDF</a>&nbsp;&nbsp;&nbsp;  <a href="https://github.com/persiannlp/parsinlu">Source Code</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * * 




<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/crowd.jpg" width="1000">
        </td>
        <td>
          <p class="text cright-align text-large add-top-margin" style="width:100%;" align="center">
              <font style="font-size:20px">Revisiting Evaluation of Knowledge Base Completion Models </font><br>
              <font style="font-size:15px"><b>Pouya Pezeshkpour</b>, Yifan Tian, Sameer Singh<br>
              <font style="color:red;">(nominated for best paper award) </font>AKBC 2020 </font><br> 
             </p><p align="justify"> <font style="font-size:13px">In this paper, we first study the shortcomings of the evaluation metrics in knowldge graph Embeddings.  More specifically, we demonstrate that these metrics 1) are unreliable for estimating calibration, 2) make strong assumptions that    are often violated, and 3) do not sufficiently, and consistently, differentiate embedding methods from simple approaches and from each other. To address these issues, we provide a semi-complete KG using a randomly sampled subgraph from the test and validation data of YAGO3-10, allowing us to compute accurate triple classification accuracy on this data. </font><br></p>
           <p align="center">
             <font style="font-size:15px"><a href="https://pouyapez.github.io/yago3-tc/">Project Page</a>  &nbsp;&nbsp;&nbsp; <a href="https://openreview.net/pdf?id=1uufzxsxfL">PDF</a>&nbsp;&nbsp;&nbsp;  <a href="https://github.com/pouyapez/yago3-tc">Source Code</a>  &nbsp;&nbsp;&nbsp;  <a href="https://www.youtube.com/watch?v=y9BHvpqHo1g&t=9s">Video on Youtube</a></font>
             </p>
        </td>
      </tr>
   </table>
</div>

* * *

<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/criage.png" width="1000">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;" align="center">
            <font style="font-size:20px">Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications </font><br>
            <font style="font-size:15px"><b>Pouya Pezeshkpour</b>, Yifan Tian, Sameer Singh<br>
            NAACL 2019</font><br>
            </p><p align="justify"><font style="font-size:13px">In this paper, we propose adversarial modifications for link prediction models: identifying the fact to add into or remove from the knowledge graph that changes the prediction for a target fact after the model is retrained. We introduce an efficient approach to estimate the effect of such modifications by approximating the change in the embeddings when the knowledge graph changes. We use these techniques to evaluate the robustness of link prediction models (by measuring sensitivity to additional facts), study interpretability through the facts most responsible for predictions (by identifying the most influential neighbors), and detect incorrect facts in the knowledge base.</font><br></p>
           <p align="center">
<font style="font-size:15px"><a href="https://pouyapez.github.io/criage/">Project Page</a>  &nbsp;&nbsp;&nbsp;  <a href="https://arxiv.org/pdf/1905.00563.pdf">PDF</a>  &nbsp;&nbsp;&nbsp;  <a href="https://github.com/pouyapez/criage">Source Code</a>  &nbsp;&nbsp;&nbsp;  <a href="https://www.youtube.com/watch?v=irVqAjt664s">Video on Youtube</a></font>
          </p>
        </td>
      </tr>
   </table>
</div>

* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/graph.jpg" width="1000">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" align="center">
            <font style="font-size:20px">Embedding Multimodal Relational Data for Knowledge Base Completion</font><br>
            <font style="font-size:15px"><b>Pouya Pezeshkpour</b>, Liyan Chen, Sameer Singh<br>
            EMNLP 2018</font><br>
            </p><p align="justify"><font style="font-size:13px">In this work, we propose multimodal knowledge base embeddings (MKBE) that use different neural encoders for this variety of observed data, and combine them with existing relational models to learn embeddings of the entities and multimodal data. Further, using these learned embedings and different neural decoders, we introduce a novel multimodal imputation model to generate missing multimodal values, like text and images, from information in the knowledge base.</font><br></p>
           <p align="center">
<font style="font-size:15px"><a href="https://pouyapez.github.io/mkbe/">Project Page</a>  &nbsp;&nbsp;&nbsp;   <a href="https://arxiv.org/pdf/1809.01341.pdf">PDF</a>  &nbsp;&nbsp;&nbsp;   <a href="https://github.com/pouyapez/mkbe">Source Code</a>  &nbsp;&nbsp;&nbsp;   <a href="https://www.youtube.com/watch?v=Bt5CccdXHUM&t=2s">Video on Youtube</a></font>
          </p>
        </td>
      </tr>
   </table>
</div>

* * *
<div class="menu-container noselect">
   <table class="content-table">
    <col width="500px" />
    <col width="800px" />
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/2014.png"  width="1000">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" align="center">
            <font style="font-size:20px">Optimal tradeoff between source and state distortions over a Gaussian channel using single and hybrid digital analog codes</font><br>
            <font style="font-size:15px"><b>Pouya Pezeshkpour</b>, Hamid Behroozi<br>
            IST'2014</font><br>
            </p><p align="justify"><font style="font-size:13px">In this paper, the problem of transmitting an analog Gaussian source over an additive white Gaussian noise (AWGN) channel in the presence of a Gaussian interference known only at the transmitter is investigated. Our goal is to estimate both the analog source and the channel state at the receiver simultaneously. In this work, we present different transmission schemes based on joint source-channel coding. We study hybrid digital-analog (HDA) joint source-channel coding schemes and analyze the region of (mean-squared error) distortion pairs (in estimating the source and the state) that are simultaneously achievable.</font><br></p>
           <p align="center">
<font style="font-size:15px"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7000779">PDF</a></font>
          </p>
        </td>
      </tr>
   </table>
</div>

# Workshop & Symposia 

* * *

<ul>
   <li><b>Pouya Pezeshkpour</b>, et al,"<a href="https://arxiv.org/abs/2402.01108">Reasoning Capacity in Multi-Agent Systems: Limitations, Challenges and Human-Centered Solutions</a>". Compound AI Systems 2024.</li>
   <li>Eser Kandogan, et al,"<a href="https://arxiv.org/abs/2406.00584">A Blueprint Architecture of Compound AI Systems for Enterprise</a>". Compound AI Systems 2024.</li>
   <li>Preethi Seshadri, <b>Pouya Pezeshkpour</b>, Sameer Singh,"<a href="https://arxiv.org/abs/2210.04337">Quantifying Social Biases Using Templates is Unreliable</a>". The TSRML workshop at NeurIPS 2022.</li>
   <li><b>Pouya Pezeshkpour</b>, Zhengli Zhao, Sameer Singh,"<a href="https://openreview.net/pdf?id=p3m_WpN0rEX">On the Utility of Active Instance Selection for Few-Shot Learning</a>". The HAMLETS workshop at NeurIPS 2020.</li>
  <li><b>Pouya Pezeshkpour</b>, Zhengli Zhao, Sameer Singh,"<a href="https://github.com/EliSchwartz/VL3-Workshop/blob/master/pdfs/36.pdf">Using Data Importance for Effective Active Learning</a>". The CVPR workshop on Visual Learning with Limited Labels (VL3), 2020.</li>
  <li><b>Pouya Pezeshkpour</b>, Yifan Tian, Sameer Singh, "Integrating Local Structure into Knowledge Graph Embeddings". SoCal NLP Symposium 2019.</li>
  <li><b>Pouya Pezeshkpour</b>, Ramya Malursrinivasan, Ajey Chander, "<a href="https://pouyapez.github.io/Generating%20User-friendly%20Explanations%20for%20Loan%20Denials%20using%20GANs.pdf">Generating User-friendly Explanations for Loan Denials using GANs</a>". NIPS 2018 Workshop on Challenges and Opportunities for AI in Financial Services.</li>
  <li><b>Pouya Pezeshkpour</b>, Carlos Guestrin, Sameer Singh, "<a href="https://arxiv.org/pdf/1805.00184.pdf">Compact Factorization of Matrices Using Generalized Round-Rank</a>". Southern California Machine Learning Symposium 2017.</li>
</ul>

# Patents
* * *

<ul>
  <li><b>Pouya Pezeshkpour</b>, Ramya Malursrinivasan, Ajay Chander, "<a href="https://patents.justia.com/patent/20200125640">USER-FRIENDLY EXPLANATION PRODUCTION USING GENERATIVE ADVERSARIAL NETWORKS</a>". US Patent Number 20200125640, 2020.</li>
 <li><b>Pouya Pezeshkpour</b>, Ramya Malursrinivasan, Ajey Chander, "<a href="https://patents.justia.com/patent/20200125975">EXPLANATIONS GENERATION WITH DIFFERENT COGNITIVE VALUES USING GENERATIVE ADVERSARIAL NETWORKS</a>". US Patent Number 20200125975, 2020.</li>
</ul> 
* * *

<p align="center"><a href="https://medium.com/@pezeshkp">Medium</a>    &nbsp;&nbsp;&nbsp;   <a href="https://medium.com/series/my-writings-4de58ce3f034">My Writings</a>  &nbsp;&nbsp;&nbsp;   <a href="https://www.amazon.com/dp/B08DMK9PNM/ref=sr_1_1?dchild=1&keywords=a+bypass+to+nirvana&qid=1595806371&sr=8-1">My Book</a> </p>

