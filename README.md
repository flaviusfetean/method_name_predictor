# method_name_predictor

This repository was created with the purpose of studying LLM's in the context of Method Name Prediction Task. <br />
As LLM's are notorious for being computationally intensive, I have created Google Colab notebooks in order to train and evaluate the models.<br />
Unfortunatelly, I cannot save directly in Colab the fine-tuned variant of the models, so only my outputs may be visible. <br />
For both experiments I have used as dataset methods extracted from the java files contained in the open-source code of Intellij-Community
<br />
## CodeT5-small
_CodeT5 is a transformer model specifically fine-tuned for code-related tasks, excelling in natural language understanding and generation within the programming domain._<br />
In my experiments I have used the small variant for faster training and inference. <br />
You can check out my results in the __nlp_codet5_method_predict.iypnb__, where I have fine-tuned, made some inferences and evaluated the model against the original, non-finetuned version of CodeT5 small.
<br />
## Llama-2-7b
_Llama-2-7b is the smallest model of the llama-2 family (7 billion parameters) and is generic, as opposed to CodeT5. It was also made publicly available so that experiments could be done on it_ <br />
Being bigger makes it harder to train and experiment on, thus, despite its size, __my__ results using it were poorer than using the previous one.<br />
You can check out my results in the __nlp_llama_method_predict_with_sample_outputs.iypnb__, where I have fine-tuned, made and analysed some inferences and evaluated the model.
<br />
