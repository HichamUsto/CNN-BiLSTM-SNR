# CNN-BiLSTM-SNR

This repository is the official implementation of the paper: 

**'Hybrid CNN-BiLSTM Network with SNR-Aware Fusion for Automatic Modulation Classification'**

**DOI: XXXXXXXX**

Thank you for your interest in our work.

## Authors

* **Sihem SOUIKI** - *University of Ain-Temouchent, Ain-Temouchent, Algeria*
* **Mohammed Hicham HACHEMI** - *University of Science and Technology of Oran-Mohamed Boudiaf (USTO-MB), Oran, Algeria* 
* **Mohammed MERZOUG** - *University Abou-bakr Belkaid, Tlemcen, Algeria* 
* **Mourad HADJILA** - *University Abou-bakr Belkaid, Tlemcen, Algeria*  
* **Mohammed M’HAMEDI** - *Ecole Supérieure en Sciences Appliquées de Tlemcen (ESSAT), Tlemcen, Algeria* 
* **Lamia BENLALDJ** - *University Abou-bakr Belkaid, Tlemcen, Algeria* 


# Proposed model (CNN-BiLSTM-SNR) — Architecture 
<img width="1474" height="704" alt="CNNBiLSTMwithSNR" src="https://github.com/user-attachments/assets/01b88a96-a105-4de6-a48f-8d8145cb8619" />


# Project Structure for "Modulation_signals_SNR_6dB.ipynb" 
```text
│
├── Modulation_signals_SNR_6dB.ipynb   # Main notebook 
│
└── outputs/
    └── Figure_2.png                   # Generated accuracy curves chart (Train/Val Accuracy)
```

# Project Structure for "CNN_+_BiLSTM_+_separate_SNR_PyTorch_OHE_pkl.ipynb"
```text
│
├── Go to "2. Load RadioML2016.10a pickle dataset" to select your dataset path  
│   └── PKL_PATH = ./XXX/XXX/RML2016.10a_dict.pkl       # RadioML2016.10a dataset file 
│
├── CNN_+_BiLSTM_+_separate_SNR_PyTorch_OHE_pkl.ipynb   # Main notebook (data preparation, model, training, evaluation)
│
└── outputs/
    ├── best_model.pth                                  # Saved PyTorch model weights (best validation accuracy)
    ├── Figure_3.png                                    # Generated accuracy curves chart (Train/Val Accuracy)
    ├── Figure_4.png                                    # Generated loss curves chart (Train/Val Loss)
    ├── Figure_5.png                                    # Generated Confusion Matrices at Selected SNRs
    ├── Figure_6.png                                    # Generated Global Confusion Matrice
    └── Figure_7.png                                    # Generated model’s performance metrics (acc., prec., recall, and F1-score) across a range of SNR
```

# Project Structure for "CNN_+_BiLSTM_+_separate_SNR_PyTorch_OHE_dat_10b.ipynb"
```text
│
├── Same thing. Go to "2. Load RadioML2016.10b dataset" to select your dataset path  
│   └── PKL_PATH = ./XXX/XXX/RML2016-10b.dat                # RadioML2016.10b dataset file 
│
├── CNN_+_BiLSTM_+_separate_SNR_PyTorch_OHE_dat_10b.ipynb   # Main notebook (data preparation, model, training, evaluation)
│
└── outputs/
   ├── best_model.pth                                       # Saved PyTorch model weights (best validation accuracy)
   ├── Figure_8.png                                         # Generated accuracy curves chart (Train/Val Accuracy)
   ├── Figure_9.png                                         # Generated loss curves chart (Train/Val Loss)
   ├── Figure_10.png                                        # Generated Confusion Matrices at Selected SNRs
   ├── Figure_11.png                                        # Generated Global Confusion Matrice
   └── Figure_12.png                                        # Generated model’s performance metrics (acc., prec., recall, and F1-score) across a range of SNR
```

# License
MIT License — free to use, modify, and distribute.
