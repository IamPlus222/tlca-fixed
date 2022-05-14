# tlca-fixed
I did some stuff to huggingface's transfer-learning-conv-ai. Idk if it works but there arent errors now\nModified version of finetuned_chatbot_gpt.tar.gz: https://www.dropbox.com/s/2bxlot6ghc498y8/finetuned_chatbot_gpt.tar.gz?dl=1
It should work without you needing to download the file
Commands:
cd (location of the project folder)
Install command:
py -m pip install -r ./transfer-learning-conv-ai/requirements.txt
If it fails, install them with pip manually
Run command:
py ./transfer-learning-conv-ai/interact.py --model_checkpoint ./transfer-learning-conv-ai/finetuned_chatbot_gpt
