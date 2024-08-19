# Classification model - lncRNA & mRNA  
This project focuses on long-chain non-coding RNA (lncRNA), which plays a significant role in various biological processes. Distinguishing lncRNA from messenger RNA (mRNA) is challenging due to their similar sequence structures. Therefore, developing an effective model to differentiate between lncRNA and mRNA is crucial.  
  
The approach first analyzes the differences in k-mer frequency distributions between lncRNA and mRNA sequences, converting these differences into a k-mer frequency matrix. By employing relative entropy, we select k-mers with a broader variety. A classification model for lncRNA and mRNA sequences is then developed, utilizing this k-mer frequency matrix to train a convolutional neural network.  
  
Model architecture based on Paper : Wen, J., Liu, Y., Shi, Y. et al. A classification model for lncRNA and mRNA based on k-mers and a convolutional neural network. BMC Bioinformatics 20, 469 (2019). https://doi.org/10.1186/s12859-019-3039-3
