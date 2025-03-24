GPT-2 Text Generation Web App:
This is a Flask-based web application that generates text using a fine-tuned GPT-2 model. The app takes a user-provided prompt, processes it using a fine-tuned GPT-2 model, and generates a coherent continuation of the text.

Features:
1. Accepts user input as a text prompt
2. Uses a fine-tuned GPT-2 model for text generation
3. Implements temperature, top-p, and beam search for better text diversity
4. Simple and interactive web interface using Flask

Tech Stack:
1. Python
2. Flask
3. Hugging Face Transformers (GPT2LMHeadModel, GPT2Tokenizer)
4. PyTorch

How It Works:
1. The user enters a text prompt in the web interface.
2. The input is tokenized using the GPT-2 tokenizer.
3. The fine-tuned GPT-2 model processes the input and generates text.
4. The generated text is displayed on the web page
