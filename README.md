# roberta-pos-finetuning
This repo contains a nootebok which shows in details how to finetune roberta (as the example I used the polish version: [sdadas/polish-roberta-base-v2](https://huggingface.co/sdadas/polish-roberta-base-v2)) model for part-of-speech tagging task. It uses modern API from Huggingface ecosystem and is heavily based on https://huggingface.co/docs/transformers/tasks/token_classification. 

I used this template to train two taggers for polish language: [wkaminski/polish-roberta-base-v2-pos-tagging](https://huggingface.co/wkaminski/polish-roberta-base-v2-pos-tagging) and [wkaminski/polish-roberta-base-v2-cposes-tagging](https://huggingface.co/wkaminski/polish-roberta-base-v2-cposes-tagging). 

Dataset used in training: [ipipan/nkjp1m](https://huggingface.co/datasets/ipipan/nkjp1m)
