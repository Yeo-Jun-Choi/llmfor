# Enhancing LLMs for Sequential Recommendation with Reversed User History and Efficient User Embeddings

## Environment Setup

To replicate our environment, please use the provided `requirements.txt` file.

To set up the environment, run the following command:

```sh
pip install -r requirements.txt
```

## Training & Evaluation
1. First, update the paths in the training scripts **(llm_path, data_dir, ckpt_dir, and log_dir)** with your own folder paths.
2. To train the model using a single A100 GPU, run the following command:
```sh
sh train_lastfm.sh
```
3. Once the model is trained, you can test it by updating the necessary paths in the test scripts and running:
```sh
sh train_lastfm.sh
```

For other shell files, you can train other datasets.

## Dataset
The data folder contains three datasets that can be easily utilized for training and evaluation.