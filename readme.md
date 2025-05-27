# Reproducible Materials – JAIR 2025 Paper

This repository includes the notebooks, datasets, and experimental artefacts used in our paper *Using Large Language Models to Improve Query‑based Constraint Acquisition* submitted to **JAIR** (2025).

---

## Repository Layout

```
SourceCodeForJAIR/
├── Experiment with real human users_Sudoku/
│   ├── Sudoku_current_MistralLargeFORLLMAcq.ipynb
│   └── sudoku/
│       ├── reps/
│       │   ├── 1/  IMG_3891.jpg … IMG_3902.jpg
│       │   ├── 2/  IMG_3903.jpg … IMG_3914.jpg
│       │   ├── 3/  IMG_3915.jpg … IMG_3926.jpg
│       │   └── 4/  IMG_3927.jpg … IMG_3938.jpg
│       └── questionnaire_sudoku_v4.pdf
├── LLMAcq_decoder_version/
│   └── LLMAcq_decoder_version.ipynb
└── LLmAcq_encoder_version/
    ├── Final_version_Fine_Tune_BERT_for_Acq_04_04_24.ipynb
    ├── LLMAcqFinalVersion.ipynb
    ├── model_dict_27_12_23.pth
    ├── synthetic_data_27_12_23.txt
    └── README.md
```

---

## Detailed Contents

### 1. *Experiment with real human users\_Sudoku*

* **Sudoku\_current\_MistralLargeFORLLMAcq.ipynb** – Jupyter notebook running the Sudoku experiment with Mistral‑Large.
* **sudoku/questionnaire\_sudoku\_v4.pdf** – Questionnaire given to participants.
* **sudoku/reps/** – Scanned photos of handwritten answers (4 pages × 12 participants).

### 2. *LLMAcq\_decoder\_version*

* **LLMAcq\_decoder\_version.ipynb** – Full implementation of the *decoder* variant of **LlmAcq**.

### 3. *LLmAcq\_encoder\_version*

* **Final\_version\_Fine\_Tune\_BERT\_for\_Acq\_04\_04\_24.ipynb** – Fine‑tuning BERT for constraint learning.
* **LLMAcqFinalVersion.ipynb** – Consolidated pipeline for the *encoder* variant.
* **model\_dict\_27\_12\_23.pth** – Pre‑trained PyTorch weights 
* **synthetic\_data\_27\_12\_23.txt** – Synthetic dataset.


---

## Quick Start

1. **Clone the repo**:

   ```bash
   git clone https://github.com/<user>/SourceCodeForJAIR.git
   ```
2. **Install dependencies**: each main notebook contains its own installation cells; no external setup is needed.
3. **Open the notebooks** in google Colab and run the cells in order.
NB: Please use your own API keys

---

## Contact

For questions about this code:

* **Younes Mechqrane** – younes.mechqrane@um6p.ma

