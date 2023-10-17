# MultiLabel Classification of PubMed Articles 
 
1. The traditional machine learning models give a lot of pain when we do not have sufficient labeled data for the specific task or domain we care about to train a reliable model.

2. Transfer learning allows us to deal with these scenarios by leveraging the already existing labeled data of some related task or domain. We try to store this knowledge gained in solving the source task in the source domain and apply it to our problem of interest.

3. In this work, I have utilized Transfer Learning utilizing BIO BERT model and Default BERT-BASE Uncased.

4. Also Applied Roberta For Sequence Classification and XLNet For Sequence Classification models class for Fine-Tuning the Model.

5. All the model performance for comparision has been logged to Weight and Biases. Check them out here?workspace=)

6. Model upload to Hugging Face Hub

This dataset consists of an approx 50k collection of research articles from PubMed repository. Originally these documents are manually annotated by Biomedical Experts with their MeSH labels and each article are described in terms of 10-15 MeSH labels. In this Dataset we have huge numbers of labels present as a MeSH major, raising the issue of extremely large output space and severe label sparsity issues. To solve this issue, the Dataset has been Processed and mapped to its root as described below.

# MeSH Major Covid-19 will be converged to Root category Diseases
![image](https://github.com/NerZ98/MultiLabel-Classification-of-PubMed-Articles-/assets/24356496/4db411bf-816e-4d48-87ef-31e8637278bf)

# Portion of the MeSH hierarchy, representing its complete path from the root node to the leaf node ‘Bipolar Disorder’.
![image](https://github.com/NerZ98/MultiLabel-Classification-of-PubMed-Articles-/assets/24356496/2dc97499-5ee3-4852-b6b3-8ae53cb5ea78)

# Training Epochs
![TrainingEpoch](https://github.com/NerZ98/MultiLabel-Classification-of-PubMed-Articles-/assets/24356496/2bc95e7b-35ba-4723-acb0-7beb2b933cec)

# F1 Validation vs Number Of Epochs
![image](![image](https://github.com/NerZ98/MultiLabel-Classification-of-PubMed-Articles-/assets/24356496/64d78581-b469-483f-985a-3708a2842884)
