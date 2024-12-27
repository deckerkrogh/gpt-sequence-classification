# Pretraining and Finetuning GPT for Sequence Classification

In this project, GPT-1 was pretrained on the wikitext dataset and finetuned on a sequence of user utterances.

### Pretrain and finetune
	python main.py --train --data "train.csv" --save_model "./trained_model.pt"

### Evaluating
	python main.py --test --data "test.csv" --model_path "./trained_model.pt"

