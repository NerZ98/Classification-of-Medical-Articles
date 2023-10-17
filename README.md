# MultiLabel Classification of PubMed Articles 
 
1. The traditional machine learning models give a lot of pain when we do not have sufficient labeled data for the specific task or domain we care about to train a reliable model.

2. Transfer learning allows us to deal with these scenarios by leveraging the already existing labeled data of some related task or domain. We try to store this knowledge gained in solving the source task in the source domain and apply it to our problem of interest.

3. In this work, I have utilized Transfer Learning utilizing BIO BERT model and Default BERT-BASE Uncased.

4. Also Applied Roberta For Sequence Classification and XLNet For Sequence Classification models class for Fine-Tuning the Model.

5. All the model performance for comparision has been logged to Weight and Biases. Check them out here?workspace=)

6. Model upload to Hugging Face Hub

This dataset consists of an approx 50k collection of research articles from PubMed repository. Originally these documents are manually annotated by Biomedical Experts with their MeSH labels and each article are described in terms of 10-15 MeSH labels. In this Dataset we have huge numbers of labels present as a MeSH major, raising the issue of extremely large output space and severe label sparsity issues. To solve this issue, the Dataset has been Processed and mapped to its root as described below.

![image](https://github.com/NerZ98/MultiLabel-Classification-of-PubMed-Articles-/assets/24356496/4db411bf-816e-4d48-87ef-31e8637278bf)

![image](https://github.com/NerZ98/MultiLabel-Classification-of-PubMed-Articles-/assets/24356496/2dc97499-5ee3-4852-b6b3-8ae53cb5ea78)
