---
layout: default
---
<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/face.png" style="width:00%">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;">
              I am a fourth-year PhD student in Machine Learning at the University of California Irvine, advised by Prof.                       Sameer Singh. My main area of interest are Knowldge Graphs, Intrepretability, Active Learning and NLP.
          </p>
        </td>
      </tr>
   </table>
</div>

# Internships

* * *
<ul>
  <li>Siri Knowledge Graph group at Apple, summer 2020.</li>
  <li>Allen Institute for Artificial Intelligence, summer 2019.</li>
  <li>Fujitsu Laboratories of America, summer 2018. </li>
  <li>Chinese University of Honk Kong, summer 2014.  </li>
</ul>

# Professional Experience
* * *

<ul>
  <li>Co-organised Knowledge Bases and Multiple Modalities workshop at AKBC 2019 and 2020.</li>
  <li>2020: Reviewer at NeurIPS, ICLR, AAAI, EMNLP</li>
  <li>2019: Reviewer at NeurIPS, ICLR, EMNLP</li>
  <li>2018: Reviewer at EMNLP</li>
  <li>Volunteer at NeurIPS 2018.</li>
</ul>


# Conference Publications
* * *

<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/crowd.jpg" style="width:150%">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;">
              Revisiting Evaluation of Knowledge Base Completion Models
Pouya Pezeshkpour, Yifan Tian, Sameer Singh
AKBC 2020
In this paper, we first study the shortcomings of the evaluation metrics in knowldge graph Embeddings.  More specifically, we demonstrate that these metrics 1) are unreliable for estimating calibration, 2) make strong assumptions that are often violated, and 3) do not sufficiently, and consistently, differentiate embedding methods from simple approaches and from each other. To address these issues, we provide a semi-complete KG using a randomly sampled subgraph from the test and validation data of YAGO3-10, allowing us to compute accurate triple classification accuracy on this data. 
          </p>
        </td>
      </tr>
   </table>
</div>


<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/criage.png" style="width:150%">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;">
Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications
Pouya Pezeshkpour, Yifan Tian, Sameer Singh
NAACL 2019
Representing entities and relations in an embedding space is a well-studied approach for machine learning on relational data. Existing approaches, however, primarily focus on improving accuracy and overlook other aspects such as robustness and interpretability. In this paper, we propose adversarial modifications for link prediction models: identifying the fact to add into or remove from the knowledge graph that changes the prediction for a target fact after the model is retrained. We introduce an efficient approach to estimate the effect of such modifications by approximating the change in the embeddings when the knowledge graph changes. We use these techniques to evaluate the robustness of link prediction models (by measuring sensitivity to additional facts), study interpretability through the facts most responsible for predictions (by identifying the most influential neighbors), and detect incorrect facts in the knowledge base.
Project Page     PDF     Source Code     Video on Youtube
          </p>
        </td>
      </tr>
   </table>
</div>

<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/graph.jpg" style="width:100%">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;">
Embedding Multimodal Relational Data for Knowledge Base Completion
Pouya Pezeshkpour, Liyan Chen, Sameer Singh
EMNLP 2018
Knowledge bases (KB) are an essential part of many computational systems with applications in search, structured data management, recommendations, question answering, and information retrieval. However, KBs often suffer from incompleteness, noise in their entries, and inefficient inference under uncertainty. To address these issues learning relational KBs by representing entities and relations in an embedding space has been a focus of active research. Nevertheless, Knowledge bases in the real-world, contain a wide variety of data types such as text, images, and numerical values which are being ignored by current methodology. We propose multimodal knowledge base embeddings (MKBE) that use different neural encoders for this variety of observed data, and combine them with existing relational models to learn embeddings of the entities and multimodal data. Further, using these learned embedings and different neural decoders, we introduce a novel multimodal imputation model to generate missing multimodal values, like text and images, from information in the knowledge base.
Project Page     PDF     Source Code     Video on Youtube
          </p>
        </td>
      </tr>
   </table>
</div>


<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td>
          <img class="left-align image noselect" src="/images/2014.png" style="width:100%">
        </td>
        <td>
          <p class="text right-align text-large add-top-margin" style="width:100%;">
Optimal tradeoff between source and state distortions over a Gaussian channel using single and hybrid digital analog codes
Pouya Pezeshkpour, Hamid Behroozi
IST'2014
In this paper, the problem of transmitting an analog Gaussian source over an additive white Gaussian noise (AWGN) channel in the presence of a Gaussian interference known only at the transmitter is investigated. Our goal is to estimate both the analog source and the channel state at the receiver simultaneously. In this work, we present different transmission schemes based on joint source-channel coding. We study hybrid digital-analog (HDA) joint source-channel coding schemes and analyze the region of (mean-squared error) distortion pairs (in estimating the source and the state) that are simultaneously achievable.
PDF
          </p>
        </td>
      </tr>
   </table>
</div>

# Efficiently Identifying the Modification

* * *

In this section, we propose algorithms to address mentioned challenges by (1) approximating the effect of changing the graph on a target prediction,and (2) using continuous optimization for the discrete search over potential modifications.

### First-order Approximation of Influence

<p align="justify">
To capture the effect of an adversarial modification on the score of a target triple, we need to study the effect of the change on the vector representations of the target triple. As a result, using the Taylor expansion on the changes of the loss after conducting the attack, we approximate ψ(s,r,o)−ψ'(s,r,o) as:
 </p>

![equation](https://latex.codecogs.com/gif.latex?%5Cbegin%7Balign%7D%20%5Coverline%7B%5Cpsi%7D%7B%28s%2Cr%2Co%29%7D-%5Cpsi%28s%2C%20r%2C%20o%29%3D%20%5Cmathbf%7Bz%7D_%7Bs%2Cr%7D%20%28%5Coverline%7B%5Cmathbf%7Be%7D_o%7D-%5Cmathbf%7Be%7D_o%29%20%3D%20%5Cmathbf%7Bz%7D_%7Bs%2Cr%7D%20%28%281-%5Cvarphi%29%20%28H_o%20&plus;%20%5Cvarphi%20%281-%5Cvarphi%29%20%5Cmathbf%7Bz%7D_%7Bs%27%2Cr%27%7D%5E%5Cintercal%20%5Cmathbf%7Bz%7D_%7Bs%27%2Cr%27%7D%29%5E%7B-1%7D%20%5Cmathbf%7Bz%7D_%7Bs%27%2Cr%27%7D%5E%5Cintercal%20%29.%5Cnonumber%20%5Cend%7Balign%7D)

### Continuous Optimization for Search

![Branching](/images/autoencoder.png)

<p align="justify">
Using the approximations provided in the previous section, we can use brute force enumeration to find the adversary〈s′,r′,o〉. This approach is feasible when removing an observed triple since the search space of such modifications is usually small. On the other hand, finding the most influential unobserved facts to add requires search over a much larger space of all possible unobserved facts (that share the object). Instead, we identify the most influential unobserved fact〈s′,r′,o〉by using a gradient-based algorithm on vector Z(s',r') in the embedding space. After identifying the optimal Z(s′,r′), we map the vector Z(s′,r′) to the entity-relation space, i.e., translating it into (s′,r′) using above inverter network.
</p>

# Experiments

* * *

<p align="justify">
We evaluate CRIAGE by, 1) comparing CRIAGE estimate with the actual effect of the attacks, 2) studying the effect of adversarial attacks on evaluation metrics, 3) exploring its application to the interpretability of KG representations, and 4) detecting incorrect triples.
</p>

### Influence Function vs CRIAGE

![Branching](/images/IF.png)

<p align="justify">
We show the time to compute a single adversary by IF (influence function) compared to CRIAGE, as we steadily grow the number of entities (randomly chosen subgraphs), averaged over 10 random triples. As it shows, CRIAGE is mostly unaffected by the number of entities while IF increases quadratically. Considering that real-world KGs have tens of thousands of times more entities, making IF unfeasible for them.
</p>

### Robustness of Link Prediction Models

![Branching](/images/robustness.png)

<p align="justify">
Now we evaluate the effectiveness of CRIAGE to successfully attack link prediction by adding false facts. Since this is the first work on adversarial attacks for link prediction, we introduce we consider two baselines to compare against our method: 1) choosing a random fake fact〈s′,r′,o〉(Random Attack); 2) finding (s′,r′) by first calculating f(e_s,e_r) and then feeding −f(e_s,e_r) to the decoder of the inverter function (Opposite Attack).  In addition to CRIAGE-Add, we introduce two other alternatives of our method:  (1) CRIAGE-FT, that uses CRIAGE to increase the score of a fake fact over, and (2) CRIAGE-Best that selects between CRIAGE-Add and CRIAGE-FT attacks. 
</p>
<p align="justify">
All-Test: The result of the attack on all test facts as targets is provided in the Table 4. CRIAGE-Add outperforms the baselines, demonstrating its ability to effectively attack the KG representations. It seems DistMult is more robust against random attacks, while ConvE is more robust against designed attacks.
</p>
<p align="justify">
Uncertain-Test: we consider a subset of test triples that 1) the model predicts correctly, 2) difference between their scores and the negative sample with the highest score is minimum. The attacks are much more effective in this scenario, causing a considerable drop in the metrics. Further, in addition to CRIAGE significantly outperforming other baselines, they indicate that ConvE’s confidence is much more robust.
</p>

###  Interpretability of Models

![Octocat](/images/int.png)

<p align="justify">
To be able to understand and interpret why a link is predicted, we need to find out which part of the graph was most influential on the prediction. To provide such explanations, we identify the most influential fact using CRIAGE-Remove. Instead of focusing on individual predictions, we aggregate the explanations over the whole dataset for each relation using a simple rule extraction technique: we find simple patterns on subgraphs that surround the target triple and the removed fact from CRIAGE-Remove, and appear more than 90% of the time. The rules show several interesting inferences, such that "hasChildis" often inferred via married parents, and "isLocatedIn" via transitivity. Furthermore, DistMult often uses the "hasCapitalas" an intermediate step for "isLocatedIn", while ConvE incorrectly uses "isNeighbor".  We also compare against rules extracted in DistMult paper. Interestingly, the extracted rules contain all the rules provided by CRIAGE, demonstrating that CRIAGE can be used to accurately interpret models.
</p>
