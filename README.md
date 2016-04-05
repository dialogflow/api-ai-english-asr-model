# Api.ai kaldi Speech Recognition Model

Model is released under Creative Commons Attribution-ShareAlike 4.0 International Public License and available here for download here https://api.ai/downloads/api.ai-kaldi-asr-model.zip

## How to use
There are example scripts on how to use model with model in kaldi repo
https://github.com/kaldi-asr/kaldi/blob/master/egs/apiai_decode/s5/README

## Training
Model is trained using kaldi "Chain models", read more about them here http://kaldi-asr.org/doc2/chain.html

Acustic data for training is Api.ai data mixed with Librispeech corpus (http://www.openslr.org/12/)

Language model is based on Assistant.ai logs, so it good for short commands, like "Wake me up at 7 am".

## Results
Api.ai test corpus WER: 13.5%
