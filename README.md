### Welcome! The area you are about to enter is under construction:
### discordLLM is a program designed to make interacting with an LLM easier and more intuitive. Through the use of customizable "personas," users can talk to LLMs with multiple personalities.

# Usage
## Requirements
- A copy of the source code (how you obtain it doesn't matter!)
- A modern version of python
- Poetry
- An OpenAI-compatible API or Ollama  
  - OpenRouter, at the time of writing, has select [models](https://openrouter.ai/docs/models) that can be used for free  
- A Discord bot token and guild ID
## Usage
1. Navigate to the cloned repository
2. Run `poetry install`
3. Run `poetry -m discordllm` to start! Your first time running will walk you through creating a config file. From there, the config file will automatically be detected if it is found in the working directory. Alternatively, you can run use the ``-config-path` argument to direct the program to a config file elsewhere on your system.
4. The bot should now be online! By default, the config file created by the program only has one 'persona,' called `default`. To interact with the bot, simply ping it in any Discord server! To switch the bot's persona, run `/changepersona` in the server.

MORE INFORMATION COMING SOON :)
