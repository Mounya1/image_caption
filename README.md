# Image Captioning with Attention-based Encoder-Decoder

## Required Libraries

- `numpy`
- `pandas`
- `matplotlib`
- `PIL` (Pillow)
- `pickle`
- `random`
- `re`
- `collections.Counter`
- `tqdm`
- `torch`
- `torchvision`
- `nltk`

Optional for evaluation:

- `nltk.translate.bleu_score`

---

## Directory Structure
project/
│
├── input/
│ └── flickr8k/
│ ├── Images/ # All image files (.jpg)
│ └── captions.txt # Captions file
│
├── working/
│ └── outputs/ # Directory for saving models, results, vocab, plots
│ ├── best_model.pth
│ ├── results.png
│ └── vocab.pkl
│
├── image_caption.ipynb# Training and evaluation script
│
└── README.md # This file


"- input/flickr8k/Images` – contains the dataset images.
- input/flickr8k/captions.txt` – CSV-like file with image IDs and captions.
- working/outputs` – saves trained models, BLEU scores, and generated caption visualizations.
- src/main.py` – contains the full training, evaluation, and caption generation code."