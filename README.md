# Finetuning a LLM using QLora technique

## Used Open Assistant dataset
- Dataset: OpenAssistant
- Model: Phi-3.5-mini-instruct and phi-2
- 
## Learnings
- One of the major tasks is to convert the data in the right format as required by the fine tuning model
- Identification of the parameters that need to be used in PEFT
- BitandBytes does not work on CPU though there are other quantization libraries that work with CPU
- Time is significantly reduced in both training and inference of model using quantization
- 
