# Train ChatGPT with custom data and create your own chatbot </br>

Building your own AI-powered chatbot has never been easier. With OpenAI’s ChatGPT, you can train a language model using custom data tailored to your specific needs.

#### Step 1: Install python </br>

#### Step 2: Upgrade Pip </br>
- python3 -m pip install -U pip

#### Step 3: Install libraries </br>
First command installs OpenAI library: </br>
- `pip3 install openai`
Next, install GPT index, which is also called LlamaIndex. It allows the LLM to connect to the external data that is our knowledge base.
- `pip3 install gpt_index`

Once done, install PyPDF2 Its python based PDF parsing library and needed if you are going to feed PDF files to model.
- `pip3 install PyPDF2`

and finally install gradio which creates simple UI to interact with AI chatgpt.
- `pip3 install gradio`

Finally we are done with installing libraries and we can move on to creating script for training and prepare data as well.
