Colab link: https://colab.research.google.com/drive/1bJHed6DACYrg-1-ugzP0eLwROp3DiMqo#scrollTo=r39mCjN2NFtC
# Topsis_text_summarization
![image](https://github.com/user-attachments/assets/78bacbf7-2c9c-412e-ab2a-4feb8a28d69a)
# Model Evaluation Results

## TOPSIS Scores

Below are the final rankings of the models based on the TOPSIS score:

| **Model**                               | **TOPSIS Score** |
|-----------------------------------------|------------------|
| facebook/bart-large-cnn                | 0.799226         |
| sshleifer/distilbart-cnn-12-6           | 0.766142         |
| facebook/bart-large-xsum               | 0.409801         |
| t5-base                                 | 0.341695         |
| google/pegasus-cnn_dailymail           | 0.225625         |

## Detailed Model Metrics

Here are the detailed evaluation metrics (ROUGE scores, inference time, and model size) for each model:

| **Model**                               | **ROUGE-1 F1** | **ROUGE-2 F1** | **ROUGE-L F1** | **Inference Time (s)** | **Model Size (MB)** |
|-----------------------------------------|----------------|----------------|----------------|------------------------|---------------------|
| facebook/bart-large-cnn                | 0.402          | 0.204          | 0.312          | 0.683                  | 1549.875            |
| sshleifer/distilbart-cnn-12-6           | 0.363          | 0.170          | 0.300          | 0.430                  | 1165.430            |
| facebook/bart-large-xsum               | 0.301          | 0.107          | 0.227          | 0.565                  | 1549.875            |
| t5-base                                 | 0.316          | 0.135          | 0.232          | 1.198                  | 850.310             |
| google/pegasus-cnn_dailymail           | 0.332          | 0.143          | 0.244          | 1.403                  | 2177.418            |

---

### Key Insights:
- **facebook/bart-large-cnn** achieved the highest **TOPSIS Score** (0.799226), making it the most well-rounded model in terms of ROUGE scores, inference time, and model size.
- **sshleifer/distilbart-cnn-12-6** came in second with a **TOPSIS Score** of 0.766142, also performing well across the metrics.
- **google/pegasus-cnn_dailymail**, despite having a higher inference time and model size, scored the lowest with a **TOPSIS Score** of 0.225625.

These evaluations provide a clear comparison of model performance in terms of both their summarization quality and efficiency. 

---

> **Note**: The evaluations were conducted using the CNN/DailyMail test set, focusing on summarization quality as measured by the **ROUGE** metrics.

