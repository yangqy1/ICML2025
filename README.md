# ICML2025

**Table 1**: Compare with more baselines on LongBench. 'Previous layer' uses the attention of the previous layer as prediction and selects top-k positions as critical tokens. Similarly, 'Previous token' uses the attention of the previous token attention in each layer as attention prediction. For baseline [1], [4], we report the results reported in their papers because their codes are not available. For baseline [2], [5], we use their official codes and reproduce the results.

![tab1](https://github.com/user-attachments/assets/682f04cc-266b-4860-8e51-d1f7ee51dd69)



**Table 2**: Evaluation on InfiniBench with up to 200K context length. Results of InfLLM is the results reported in their papers.

<img src="https://github.com/user-attachments/assets/6207482e-ca31-4a9a-a68f-e1500bc52daa" alt="" width="380" height="120" />


**Table 3**: Evaluation on long-CoT dataset with average decode length 1716.

<img src="https://github.com/user-attachments/assets/c2c0fdcc-144b-4d50-a699-8732cdd93566" alt="" width="290" height="100" />

**Table 4**: Per token decoding latency. The LLM is Llama-3.1-8B-Instruct. The cache budget is set to 1/16. All experiments are conducted on one NVIDIA-A800-80GB. 

<img src="https://github.com/user-attachments/assets/eda42bac-99d5-4e14-9f9f-55b2c783edb7" alt="" width="400" height="130" />


**Figure 1**: Revision of Algorithm 1 with clarification of the behavior of the $A_H$ Update (line 3) and position Expand functions (line 6).

<img src="https://github.com/user-attachments/assets/38d9ab3f-cf81-48b2-bb64-c998f6d454b7" alt="" width="380" height="230" />



**Figure 2**: Accuracy of the predictor with different ratios of training data. 

<img src="https://github.com/user-attachments/assets/e27bd7b2-13b9-480b-956b-5be344d23c40" alt="" width="380" height="280" />
