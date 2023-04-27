## Train ChatGPT with custom data and create your own chatbot </br>

Building your own AI-powered chatbot has never been easier. With OpenAI’s ChatGPT, you can train a language model using custom data tailored to your specific needs.

#### Step 1: Install python </br>

#### Step 2: Upgrade Pip </br>
- python3 -m pip install -U pip

#### Step 3: Install libraries </br>
First command installs OpenAI library: </br>
* ```
  pip3 install openai 
  ``` 
</br>
Next, install GPT index, which is also called LlamaIndex. It allows the LLM to connect to the external data that is our knowledge base. </br>
* ```
   pip3 install gpt_index
  ``` 

</br>

Once done, install PyPDF2 Its python based PDF parsing library and needed if you are going to feed PDF files to model.
* ```
    pip3 install PyPDF2
  ``` 
</br>

and finally install gradio which creates simple UI to interact with AI chatgpt.
* ```
   pip3 install gradio
  ``` 
</br>

Finally we are done with installing libraries and we can move on to creating script for training and prepare data as well.

#### Step 4: Get OpenAI key </br>
Before diving into script, lets get API key from Open AI You can then click on Create new secret key to generate a key for our script
Remember that once key is generated, you won’t be able to see it again. You must copy and save the key in some secure location to be able to access it later.

#### Step 5: Prepare data </br>
Create a new directory named ‘docs’ anywhere you like and put PDF, TXT or CSV files inside it. You can add multiple files if you like but remember that more data you add, more the tokens will be used. Free accounts are given 18$ worth of tokens to use.

#### Step 6: Create script </br>
Now that everything is in place, our next step is to create a python script to train chatbot with custom data. It will use files inside doc directory, that we created above, and generate a json file.
You can use any text editor if you are using Visual Studio Code then its even better.