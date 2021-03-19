# ArCovBERT
Arabic natural language understanding model based on BERT architecture, and trained on a large Arabic Twitter dataset related to the COVID-19 topic.
## Pre-trained model:
  - The trained model is available at this link [ArCovBER](https://drive.google.com/drive/folders/1flbJe0D96Lx47e5_1FA0rqExuwyJnElf?usp=sharing) (tensorflow-based  version).
## Uses
  - Fine-tuning : To use this model for downstream NLP tasks, we recommend the steps and scripts described in [Bert repository from google-research](https://github.com/google-research/bert#fine-tuning-with-bert).
  
  - Further pre-training : For additional pre-training on your text corpus, follow the steps shown here [Pre-training with bert](https://github.com/google-research/bert#pre-training-with-bert) using our model as checkpoint ("init_checkpoint" parmeter of "run_pretraining.py" script).

## Acknowledgments
We would like to express our thanks and gratitude to the TensorFlow Research Cloud (TFRC) team for their help which allows us to freely benefit from Cloud TPU instances for research purposes.
