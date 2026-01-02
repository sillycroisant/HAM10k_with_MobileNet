# HAM10k_with_DenseNet121
## Skin lesions' images classification with Dense121

HAM10KDataset [link](https://challenge.isic-archive.com/data/#2018) with [paper](https://arxiv.org/pdf/1803.10417).

Ham10K is an ISIC 2018 challenge's dataset with 7 classes of skin cancer diseases with about 10,000 iamges.
But the training dataset suffers a huge inter-classes data size imbalance and intra-class variant making it more difficult for models to learn the features of dataset.
Thus harder to make correct predictions. Even from the sources of the Ham10k dataset, doctor still struggle to confidently predict and verify 50% skin lesions without years follow-up cases, microscopic and colleges assitance. Making only the rest 50% of the dataset is pathologic verification.

The project will going through the Model Experiemnt phase in ML development streams include (hi vọng làm được hết :>) I
1. Data acquisition (Already have)
2. Exploratory data analysis - inspect dataset and visualize distribution to detect potential problem
3. Feature design/engineer - address dataset's problem, or augment it
4. Prototyping (jupyternotebook/gg colab) - build model, choose loss function, optimizer,.etc..
5. Hyper-parameter search/optimize - testing model with different hyper-parameter
6. Model analysis - compare with other models base on many metrics
