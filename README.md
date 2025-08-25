

## Education

- **Ph.D., Electrical Engineering**  
  University of Central Florida (Aug 2024 – Present)

- **B.Sc., Electrical and Electronics Engineering**  
  University of Dhaka (Jan 2018 – Jan 2023)

## Work Experience
**Graduate Research Assistant @ University of Central Florida (August 2024 - Present )**
- A vision-language model induced prompt learning framework that leverages subspace projection to enhance ID/OOD separability for robust out-of-distribution detection.
- Pseudo-label Induced Subspace Representation Learning for Robust Out-of-Distribution Detection.
- Proposed a Foundation model aided crowd framework that integrates noisy annotations from different foundation models. and positive class confusion matrices for robust multi-label recognition task.

**ML Research Assistant  @ Qatar University (April 2022 - May 2024)**
- Developed a 1D CycleGAN-based AF detection framework with Self-ONN layers, improving accuracy by 3.5% in restoring poor-quality wrist PPG signals.
- Developed a robust model combining DenseNet-201 and Multi-axis Vision Transformer with data augmentation to classify 28 categories of waste images.
- Novel Self-ONN based hybrid DL model with statistical features injection utilizing EEG, EMG and accelerometer signals for multimodal freezing of gait detection.
- Applied several domain adaptation techniques to improve raman bacteria classification performance from cross-device spectrum datasets.
  
## Projects
### Vision Language Model Based Prompt Optimizaton with Subspace Representation Learning for Few-shot Out-of-Distribution Detection


Recent advances in large-scale vision-language models have enabled promising few-shot OOD detection frameworks using only a handful of in-distribution (ID) samples. Existing prompt learning methods in vision language models focus only on softmax outputs, neglecting the discriminative strength of feature embeddings. To address this, we propose a context optimization based framework that combines subspace representation learning with prompt tuning, enhancing ID-OOD separability through subspace and null-space projections. Our end-to-end learning criterion achieves strong OOD detection while maintaining high ID classification accuracy, validated through experiments on real-world datasets.
![EEG Band Discovery](/assests/subcoop_v2.png)

### Foundation Model Aided Crowd Framework with Geometric Regularization
Multi-label learning is vital for AI applications but suffers from noisy and expensive annotations, as each instance requires multiple labels from diverse annotators. Recent advances in foundation models such as CLIP provide pseudo-labels to reduce annotation costs, but these predictions are not optimized for multi-label tasks and often introduce additional noise. We propose a novel crowd framework that robustly integrates human annotations with different CLIP based pseudo-labels using modeling and factorization techniques. A geometric regularization with end-to-end learning criterion ensures robustness, and experiments on real-world datasets demonstrate the effectiveness of our approach
![Bike Study](/assests/new3.png)
### Text-to-Image Generation with LLM guided image refinement
Modern text-to-image systems based on diffusion models struggle with complex prompts describing multi-object scenes with fine-grained attributes and spatial relationships. To address this, we incorporate large language models (LLMs) to analyze prompts and use an open-vocabulary detector to verify whether generated images match the extracted details. If inconsistencies arise, the LLM suggests localized adjustments in the latent representation, refining errors while preserving correct regions. Preliminary experiments demonstrate that this training-free pipeline achieves promising results in both text-to-image generation and image editing, offering precise control over object placement and attributes.
![Bike Study](/assests/method.png)


## Publications
1. Faizul Rakib Sayem and Shahana Ibrahim, ”Subspace Representation Learning Based Prompt Optimization for Few-Shot Out-of-Distribution Detection”, Proceedings of the AAAI Conference on Artificial Intelligence, 2026 (under review).
2. Faizul Rakib Sayem and Shahana Ibrahim, ”Robust Multi-Label Learning with Human-Guided and Foundation Model-Aided Crowd Framework”, IEEE International Conference on Image Processing (ICIP), 2025 (Accepted).
3. Tarhib Al Azad, Faizul Rakib Sayem, and Shahana Ibrahim. "Pseudo-label Induced Subspace Representation Learning for Robust Out-of-Distribution Detection." arXiv preprint arXiv:2508.03108 (2025).
4. Faizul Rakib Sayem, and Shahana Ibrahim. "Prompt Optimization Meets Subspace Representation Learning for Few-shot Out-of-Distribution Detection." In First International KDD Workshop on Prompt Optimization, 2025. 2025.
5. Faizul Rakib Sayem, Md Sakib Bin Islam, Mansura Naznine, Mohammad Nashbat, Mazhar Hasan-Zia, Ali K. Ansaruddin Kunju, Amith Khandakar et al. "Enhancing waste sorting and recycling efficiency: robust deep learning-based approach for classification and detection." Neural Computing and Applications 37, no. 6 (2025): 4567-4583.
6. Faizul Rakib Sayem, Mosabber Uddin Ahmed, Saadia Binte Alam, Sakib Mahmud, Md Mamun Sheikh, Abdulrahman Alqahtani, Md Ahasan Atick Faisal, and Muhammad EH Chowdhury. "A novel 1D generative adversarial network-based framework for atrial fibrillation detection using restored wrist photoplethysmography signals." Biomedical Signal Processing and Control 101 (2025): 107233.
7. Adiba Tabassum, Muhammad EH Chowdhury, Md Sakib Bin Islam, Mehrin Newaz, Abdus Salam, Faizul Rakib Sayem, Mazhar Hasan-Mia et al. "Intelligent waste management: a comprehensive review of machine learning and deep learning applications in advanced recycling." Harnessing Automation and Machine Learning for Resource Recovery and Value Creation (2025): 427-460.
8. Lubaba Tazrian Rahman, Mahmud Elahi Akhter, Faizul Rakib Sayem, Mainul Hossain, Rajib Ahmed, MM Lutfe Elahi, Khaleda Ali, and Sharnali Islam. "A 1.55 μm wideband 1× 2 photonic power splitter with arbitrary ratio: characterization and forward modeling." IEEE Access 10 (2022): 20149-20158.
9.  Md Mamun Sheikh, Faizul Rakib Sayem, and Md Atiqur Rahman Ahad. "A residual network with focal loss to handle class-imbalance problem on nurse care activity recognition." In 2021 Joint 10th International Conference on Informatics, Electronics & Vision (ICIEV) and 2021 5th International Conference on Imaging, Vision & Pattern Recognition (icIVPR), pp. 1-8. IEEE, 2021.
10.  Faizul Rakib Sayem, Md Mamun Sheikh, and Md Atiqur Rahman Ahad. "Feature-based method for nurse care complex activity recognition from accelerometer sensor." In Adjunct Proceedings of the 2021 ACM International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of the 2021 ACM International Symposium on Wearable Computers, pp. 446-451. 2021.
11.  Faizul Rakib Sayem, Md Mamun Sheikh, and Md Atiqur Rahman Ahad. "Bento Packaging Activity Recognition Based on Statistical Features." In Sensor-and Video-Based Activity and Behavior Computing: Proceedings of 3rd International Conference on Activity and Behavior Computing (ABC 2021), pp. 207-216. Singapore: Springer Nature Singapore, 2022.
