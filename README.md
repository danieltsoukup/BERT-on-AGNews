# BERT-on-AGNews
A detailed walk-through of using pytorch-transformers and BERT for text classification.

These notes will show you how to use BERT for text-classification. Some highlights:
* dataloaders in pytorch,
* BERT from pytorch-transformers,
* freezing layers,
* learning rate schedulers, optimizers and gradient clipping,
* mixed precision training,
* logging your training.

Resources:
* [a good tutorial from C. McCormick](https://mccormickml.com/2019/07/22/BERT-fine-tuning/)
* [the original BERT paper](https://arxiv.org/abs/1810.04805)
* [the main library we use is pytorch-tranformers from huggingface](https://github.com/huggingface/pytorch-transformers)
* ['Fine-tuning BERT for text classification' by Sun et. al](https://arxiv.org/abs/1905.05583)
* [a post on compressing and speeding-up large models](https://blog.rasa.com/compressing-bert-for-faster-prediction-2/)
