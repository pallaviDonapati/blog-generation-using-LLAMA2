# blog-generation-using-LLAMA2

![blog](https://github.com/pallaviDonapati/blog-generation-using-LLAMA2/assets/144420250/0d312d7a-8882-4a53-b0bb-3cfa5514706c)

Overview

This project allows users to generate blogs automatically based on a given topic, style, and word count. It utilizes the Llama 2 model through the CTransformers API for generating blog content. The user inputs a topic, selects the style of the blog (e.g., for researchers, data scientists, or common people), and specifies the desired word count. The model then generates a blog in response to the user's inputs.

Project Overview

The repository contains code for generating blog posts based on user input using the Llama 2 model. The app allows users to customize the content generation by specifying the blog's style and word count. The project uses LangChain's PromptTemplate to structure prompts dynamically and CTransformers to interface with the Llama 2 model for text generation.

Repository Contents

app.py: Main code for the Streamlit app, which takes user inputs, formats the prompt, and generates the blog using Llama 2.
requirements.txt: Contains all the necessary Python dependencies for running the app.

Key Features

Text Input: Users input a blog topic for which they want a blog to be generated.
Word Count: Users specify the desired word count for the blog post.
Blog Style Selection: Users can choose from different writing styles, including styles tailored for researchers, data scientists, or the general public.
Blog Generation: Based on the inputs, the Llama 2 model generates a blog that fits the user's specifications.
