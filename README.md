# ChatGPT_and_gradio_localy
Here is a simple example to start using your own personalized openai chat gtp

This repos was created and aspired by article [How to Build Your Own AI Chatbot With ChatGPT API: A Step-by-Step Tutorial](https://beebom.com/how-build-own-ai-chatbot-with-chatgpt-api/).

To cut it short just follow the below commands:

```
# Create new conda environment
conda create --name new_env_name
conda activate new_env_name

# install packages
conda install pip
python -m pip install -U pip
pip intall openai
pip intall gradio

# clone this repositiry
git clone repo_name

# copy API key from openai website
export OPENAI_API_KEY="your value...."
echo $OPENAI_API_KEY

# run this script
python app.py
```
