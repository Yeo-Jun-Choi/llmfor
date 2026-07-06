# [IEEE Access] Enhancing LLMs for Sequential Recommendation with Reversed User History and User Embeddings

[![View Paper](https://img.shields.io/badge/View%20Paper-PDF-E24D35)](https://doi.org/10.1109/ACCESS.2025.3583094) [![DOI](https://img.shields.io/badge/DOI-10.1109/ACCESS.2025.3583094-blue)](https://doi.org/10.1109/ACCESS.2025.3583094)

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
sh test_lastfm.sh
```

For other shell files, you can train other datasets.

## Dataset
The data folder contains three datasets that can be easily utilized for training and evaluation.

## Acknowledgements
This work was partly supported by the National Research Foundation of Korea (NRF) grant funded by the Korea government (MSIT) (RS-2025-00553785) and the Institute of Information & Communications Technology Planning & Evaluation (IITP) grant funded by the Korean government (MSIT) (RS-2021-II211341, Artificial Intelligence Graduate School Program of Chung-Ang University).

## Citation
If you find this work useful, please cite our paper:
```bibtex
@article{choi2025enhancing,
  title={Enhancing LLMs for Sequential Recommendation with Reversed User History and User Embeddings},
  author={Choi, Yeo Jun and Yun, Woo-Seong and Cho, Yoon-Sik},
  journal={IEEE Access},
  volume={13},
  pages={121641--121651},
  year={2025},
  publisher={IEEE}
}
```
