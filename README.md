# Deep Representation Class Augmentation

1. `/checkpoints`: ClassAug model checkpoints are stored in this folder during training
2. `/embeddings`: `.pkl` files for datasets with the naming convention of `<dataset_name>_embeddings.pkl`. As the `.pkl` files were too big to push on git, the embeddings maker notebooks are in the repo. Each `.pkl` file contains 1 JSON object with 2 keys: `embs` -> `(n, dimensions)` array and `labels` -> `(n, 1)` array.
3. `/models`: All the trained models for each of the 4 papers: DRCA, Outlier Exposure, Mixup, Maximum Softmax Probability.
4. `/`: Contains all the necessary notebooks to reproduce our results.

Authors:
[Mohammad Areeb Siddiqui](https://www.linkedin.com/in/mareebsiddiqui/), [Maham Shakir](https://www.linkedin.com/in/maham-shakir-326954189/), [Muhammad Usama Siddiqui](https://www.linkedin.com/in/muhammadusama100/)