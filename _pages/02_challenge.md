---
layout: page
permalink: /challenge/
title: Challenge
---

We have seen an increase in Sign Language Production (SLP) approaches over the last few years. However, the lack of standardized evaluation metrics for SLP approaches hampers meaningful comparisons across different systems. Therefore, we are organizing an SLP challenge on the RWTH-PHOENIX-Weather-2014T dataset, which has become the standard benchmark for SLP research. We will release a standardized evaluation network, establishing a consistent baseline for the SLP field and enabling future researchers to compare their work against a broader range of methods.  We are inviting existing and new authors to submit their model’s predictions for evaluation. 

**Important Dates:**
- Start of the Challenge (development phase): January 13, 2025 
- Start of test phase: February 24, 2025 
- End of the Challenge: March 3, 2025 
- Code and Fact sheets submission: March 7, 2025 
- Release of results: March 13, 2025

All deadlines begin at 00:00 GMT (London) and end 23:59 GMT.

**Rewards:**

The winning team will be invited to present their work at the SLRTP workshop at CVPR 2025. We will publish a collaborative paper summarizing the key findings, methodologies, and insights from the challenge. Top teams will be added to this paper that will be included in the CVPR Workshop proceedings.

For more details, please visit the challenge website: [https://www.codabench.org/competitions/4854/](https://www.codabench.org/competitions/4854/) 

**Official Results:**

We are delighted to announce the winners of the SLRTP 2025 Sign Language Production Challenge. This year, more than 30 teams competed, and we thank all participants for their efforts. Below are the top three teams:

**1st Place: USTC-MoE**
- Team Leader: Kepeng Wu (University of Science and Technology of China)

- Members: Zecheng Li, Weichao Zhao, Haodong Wang, Wengang Zhou, Houqiang Li

- Method: A retrieval-based approach using generated gloss segmentation and pose dictionary lookups for high-fidelity sign generation.

**2nd Place: hfut-lmc**
- Team Leader: Shengeng Tang (Hefei University of Technology)

- Members: Jiayi He, Xu Wang, Ruobei Zhang, Yaxiong Wang, Lechao Cheng

- Method: A text-driven conditional diffusion model, learning a direct mapping from text to continuous poses without gloss annotations.

**3rd Place: Hacettepe**
- Team Leader: Meryem Tasyurek (Hacettepe University)

- Members: Tugce Kiziltepe, Hacer Yalim Keles

- Method: A gloss-free transformer encoder-decoder where poses are generated from latent embeddings.


**SLP Challenge Results on the Hidden Test Set**
<table>
  <thead>
    <tr>
      <th>Team</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>CHRF</th>
      <th>ROUGE</th>
      <th>WER</th>
      <th>DTW MJE</th>
      <th>Total Dist.</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>USTC-MoE (1st)</td>
      <td>21.35</td>
      <td>13.47</td>
      <td>7.83</td>
      <td>4.93</td>
      <td>31.71</td>
      <td>23.26</td>
      <td>109.38</td>
      <td>0.057</td>
      <td>1.185</td>
    </tr>
    <tr>
      <td>hfut-lmc (2nd)</td>
      <td>20.17</td>
      <td>11.97</td>
      <td>7.16</td>
      <td>4.44</td>
      <td>29.93</td>
      <td>22.20</td>
      <td>107.93</td>
      <td>0.049</td>
      <td>0.972</td>
    </tr>
    <tr>
      <td>Hacettepe (3rd)</td>
      <td>15.88</td>
      <td>8.05</td>
      <td>4.17</td>
      <td>2.41</td>
      <td>23.23</td>
      <td>15.40</td>
      <td>105.49</td>
      <td>0.053</td>
      <td>0.761</td>
    </tr>
  </tbody>
</table>
