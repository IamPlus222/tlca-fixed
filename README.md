# transfer-learning-conv-ai fixed
-------------------------------------------------------------------------------------------------------------------------------------------------------
I did some stuff to huggingface's transfer-learning-conv-ai. Idk if it works but there arent errors now.
[Modified version of finetuned_chatbot_gpt.tar.gz](https://www.dropbox.com/s/2bxlot6ghc498y8/finetuned_chatbot_gpt.tar.gz?dl=1). Download and extract the file. Put the 'finetuned_chatbot_gpt' folder in the 'transfer-learning-conv-ai' folder.
Commands:
cd (location of the project folder)
Install command:
py -m pip install -r ./transfer-learning-conv-ai/requirements.txt
If it fails, install them with pip manually
Run command:
py ./transfer-learning-conv-ai/interact.py --model_checkpoint ./transfer-learning-conv-ai/finetuned_chatbot_gpt
