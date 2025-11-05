------------------------------------------1-----------------------------------------------
-> Learning what is LLM -> Large language models.(A neural netwrok desinged to understand and generate human like text).
-> Large -> (Deep) Neural Networks ans billions and trillions of parameters. 
![Alt text](/images/model_parameters.png)
-> LLM vs NLPs
NLP is task specific, but a LLm can perform wide range of NLP tasks.
-> What is making LLM special.
Transformer architecture is the main import part of LLm which makes LLM work.
->LLM vs GenAI vs DL vs AI vs ML
![Alt text](/images/Ai_hirearchy.png)
------------------------------------------1-----------------------------------------------

------------------------------------------2-----------------------------------------------
-> Pre training LLM vs Fine tuning of LLM

Creating LLm = pre training + fine tuning

-> Pre training: Training on a large and diverse dataset. (Also called fundamental model)
Here is the volumne f dataset used to train gpt3 
![Alt text](/images/gpt3_trained_dataset.png) ->  trained with near to 300 bilion tokens 
-> Fine tuning: Refining (response specific to your requirement, i.e for company specific requiremnets we need to ifine tune the fundamental model).

pre-training method are trained with unsupervised dataset(not labled).
fine-tuning method is trained with supervised dataset(labled).

Steps: 
Data(raw text eg:)(text, books, media, articeles,...)->pre trained model(foundational model)->finetuned LLM(requirment specific response generating llm).
There are 2 types of fineTunings,
1) Instruction fine tuning (provide the instructions)(eg: text transaltion)
2) Classification tasks(eg: Email spam or non spam identification)
------------------------------------------2-----------------------------------------------
------------------------------------------3-----------------------------------------------
-> Transformer Architecture
Transformer is the main part of the LLM architecture. (Refer to attention is all you need research papaer.)
Initially the architecture built was to serve the language translation (eng-french, eng-german), but later it came to know that using this architecture there can be many things done.
-> Gpts base architecure is simlar to this architecture, refer to all the 8 steps.
![Alt text](/images/Basic_transformer_architecture.png) -> simplified transformer architecure
Self Attention.
BERT and GPT models.
BERT -> Predicts the missing or masked words.(So it pays attention to all words, so good for sentiment analysis.)
GPT -> Generates the new words.(attention of previous words.)
-> Transformer vs LLM
Transformers are also used for vision tasks(computer vision), but LLm its not the case.
Similarly LLm also can be built from CNN and RNN architecture, no transformer needed in previous cases.
------------------------------------------3-----------------------------------------------
------------------------------------------4-----------------------------------------------
GPT-2,3. Overiew of dataset and Zero and Few shot learning, Auto regresive, Emergent Behavor of LLM.
------------------------------------------4-----------------------------------------------

------------------------------------------Sources-----------------------------------------------
Credits : Youtube Playlist Named - Building LLMs from scratch
Research Papers: Attention is all you need. 
Reference Book followed ->Build a Large Language Model (From Scratch) Book by Sebastian Raschka
