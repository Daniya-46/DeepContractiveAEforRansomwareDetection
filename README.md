# DeepContractiveAEforRansomwareDetection
Deep Contractive Autoencoder–based ransomware detection using static features. The model learns robust latent representations and identifies malware through reconstruction error, offering resilience against noise and zero-day ransomware variants. Built with TensorFlow and Scikit-learn.

## Tech Stack

* **Python**
* **TensorFlow / Keras**
* **NumPy & Pandas**
* **Scikit-learn**
* **Matplotlib & Seaborn**

## Project Structure

```
├── deepcontractiveaeforransomwaredetection.ipynb
├── README.md
```

* The notebook contains:

  * Data loading and preprocessing
  * Feature scaling
  * Model architecture definition
  * Training with contractive loss
  * Evaluation and visualization

## Methodology

1. **Data Preprocessing**

   * Feature normalization using standard scaling
   * Balanced dataset of benign and ransomware samples

2. **Model Architecture**

   * Deep encoder-decoder network
   * Contractive loss added to reconstruction loss
   * Latent space learning for robust representations

3. **Detection Strategy**

   * Reconstruction error used as a decision metric
   * Higher reconstruction error indicates malicious behavior

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

Performance is evaluated on both benign and ransomware samples to assess detection capability.

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. Install dependencies:

   ```bash
   pip install numpy pandas tensorflow scikit-learn matplotlib seaborn
   ```

3. Run the notebook:

   ```bash
   jupyter notebook deepcontractiveaeforransomwaredetection.ipynb
   ```

## Key Highlights

* Signature-free ransomware detection
* Robust feature learning using contractive regularization
* Suitable for research and academic experimentation

## Limitations

* Uses static features only
* Threshold-based classification may require tuning
* Real-world deployment would require dynamic analysis integration

**Author:** Daniya Aamir
