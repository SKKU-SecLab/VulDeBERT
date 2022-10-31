# VulDeBERT: A Vulnerability Detection System Using BERT

#### Soolin Kim*+, Jusop Choi*, Ejaz Ahmed+, Surya Nepal+, and Hyoungshick Kim*+.
##### Sungkyunkwan University*, CSIRO Data61+

---



Deep learning technologies recently received much attention to detect vulnerable code patterns accurately. This paper proposes a new deep learning-based vulnerability detection tool dubbed VulDeBERT by fine-tuning a pre-trained language model, Bidirectional Encoder Representations from Transformers (BERT), on the vulnerable code dataset. To support VulDeBERT, we develop a new code analysis tool to extract well-represented abstract code fragments from C and C++ source code. The experimental results show that VulDeBERT outperforms the state-of-the-art tool, [VulDeePecker](https://arxiv.org/abs/1801.01681) for two security vulnerability types (CWE-119 and CWE-399). For the CWE-119 dataset, VulDeBERT achieved an F1 score of 92.6\%, which is significantly better than VulDeePecker, achieving an F1 score of 86.6\% in the same settings. Again, for the CWE-399 dataset, VulDeBERT achieved an F1 score of 97.9\%, which is also better than VulDeePecker, achieving an F1 score of 95\% in the same settings.




* VulDeBERT dataset focuses on two types of vulnerabilities in C and C++ programs (i.e., buffer error vulnerability (CWE-119) and resource management error vulnerability (CWE-399)).

