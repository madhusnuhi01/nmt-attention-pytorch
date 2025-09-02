# Neural Machine Translation with Attention (PyTorch)

An implementation of a **seq2seq NMT** system with a **bidirectional GRU encoder** and an **attention-based decoder** in PyTorch. Includes training loop, teacher forcing, and evaluation with translation quality metrics.

## Highlights
- Encoder–decoder with additive attention (Bahdanau-style) in **PyTorch**.
- Tokenization, vocabulary creation, batching, and masking utilities.
- Evaluation with BLEU or compatible metrics (configure as needed).

## Getting Started
```bash
# (optional) create a virtual env
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate

pip install -r requirements.txt
python -m ipykernel install --user --name nmt-attention-pytorch
```

Open the notebook in Jupyter and run:

```bash
jupyter notebook Neural_Machine_Translation_using_Attention_Mechanism.ipynb
```

## Repository Structure
```
.
├── Neural_Machine_Translation_using_Attention_Mechanism.ipynb
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

## Notes
- Adjust dataset paths and preprocessing configs to your corpus (e.g., WMT/Tatoeba).
- For reproducibility, seed everything and log key hyperparameters.

## Citation
If you use or extend this code, please cite:
> Panda, M. (2025). Neural Machine Translation with Attention (PyTorch).

## License
MIT
