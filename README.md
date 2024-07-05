

                                          TESTING FOR FAIRNESS IN FINANCIAL LLMS

                                          STEP 1

1.We started by cloning the Mutaint Repo from https://github.com/Anonymous1925/MutaInT/tree/main/Mutaint_tool_usage

Which we openned using the Pycharm IDE.

2. All the 9 Finma validation datasets were downloaded and added to the project in the subfolder FinMa_Dataset. Below is the link to all the 9 datasets
Note that after downloading the datasets, it was renamed accordingly just for convenience and easy recognition.

ACL18 ---→https://huggingface.co/datasets/TheFinAI/flare-sm-acl/tree/main/data

BigData22---→https://huggingface.co/datasets/TheFinAI/flare-sm-bigdata/tree/main

CIKM18 ---→https://huggingface.co/datasets/TheFinAI/flare-sm-cikm/tree/main/data

ConvFinQA ---→https://huggingface.co/datasets/TheFinAI/flare-convfinqa/tree/main/data

FinQA ---→https://huggingface.co/datasets/TheFinAI/flare-finqa/tree/main/data

FiQA-SA ---→https://huggingface.co/datasets/TheFinAI/en-fpb/tree/main/data

FPB ---→https://huggingface.co/datasets/TheFinAI/en-fpb/tree/main/data

Headline ---→https://huggingface.co/datasets/TheFinAI/flare-headlines/tree/main/data

NER ---→https://huggingface.co/datasets/TheFinAI/flare-ner/tree/main/data

3. We created 2 python files in the MutaInt project from our Pycharm IDE
abiramistep1.py : For atomic mutation, runtime was aproximately 12h on a 16GB icore 5 intel laptop
abiramistep11.py : For intersectional mutation, runtime was aproximately 48h on a 16GB icore 5 intel laptop

4. Here is the google drive link to download the project to reproduce the experiment:

   
   MutaInt(Open with Pycharm) -> https://drive.google.com/drive/folders/1Ju9616fHfHDQhOmXpi4rpPaxJIfsk5T3?usp=sharing
   
   AtomicMutationResults -> https://drive.google.com/drive/folders/1Ju9616fHfHDQhOmXpi4rpPaxJIfsk5T3?usp=sharing
   
   IntersectionalMutationResults -> https://drive.google.com/drive/folders/1Ju9616fHfHDQhOmXpi4rpPaxJIfsk5T3?usp=sharing



6. Then you can open the project in pycharm to reproduce the experiment, by running the files abiramistep1.py and abiramistep11.py

                                             STEP 2

1. We created a google colab notebook, by following the examples at https://huggingface.co/blog/4bit-transformers-bitsandbytes](https://colab.research.google.com/drive/1ge2F1QSK8Q7h0hn3YKuBCOAS0bK8E0wf?usp=sharing)


