# NLP-Assignment-8---Instruction-Tuning-with-hf-AlpacaEval

## Student Info

Ashmita Phuyal(124454)

### Task 1. Alpaca Dataset <br>

We first integrate the Alpaca Dataset and downloaded the dataset from the designated GitHub repository by mapping its JSON format with the appropriate dataset package. Once the JSON format is successfully mapped, we proceed to set up the instruction format, defining the features and structuring the data as per the requirements of our code framework. 

### Task 2. Model Training <br>

Then, we incorporated the Alpaca Dataset into our existing code framework to train a language model capable of understanding text context and style. For model training, we have used the distilgpt2 architecture. The training process is facilitated by the SFTTrainer. We used Trainer and the Self-Training Framework (SFT) to facilitate the training process. With the dataset integrated, we configure the training parameters, initialize the model architecture, and iterations performed to optimize the model's performance.

### Task 3. Model Evaluation <br>

We trained a language model using the Alpaca evaluation dataset obtained from the specified Hugging Face repository link. We then compare the generated text produced by our model with the gold label provided in the evaluation dataset.  During the initialization of the SFTTrainer, the eval_dataset is provided as input. The evaluation process is initiated by invoking the trainer.evaluate() function. 

### Task 4. Text Generation - Web Application Development <br>

At last, we developed web application using FLASK framework and necesaary html codes that showcases the capabilities of our trained language model in text generation. The web application takes the input from user and loads the model. Then, the input text is encoded using the provided tokenizer and then forwarded to the model with specified necessary parameters.

Once the model generates the text based on the input, the generated output is decoded and presented back to the user for viewing on the interface.

<img width="1056" alt="Screenshot 2024-03-29 at 02 50 02" src="https://github.com/ashmita-5/NLP-Assignment-8---Instruction-Tuning-with-hf-AlpacaEval/assets/32629216/1ba49c64-b806-451f-b793-12ee37fc56da">
