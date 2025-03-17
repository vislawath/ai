# LOCAL LLM TUTORIAL
## OLLAMA 
### Installation
Simply visit [ollama.com](https://ollama.com) and install!

Once complete, the ollama server should be running locally.  
- Visit [http://localhost:11434/](http://localhost:11434/) to confirm. You should see the message `Ollama is running`.
- Try using `llama3.2` if latest Ollama is slow on your machine. To change, run `ollama pull llama3.2` from a Terminal.


# FRONTIER MODELS

| COMPANY    | MODELS               | CHAT (UI)      | NOTES                                                                                                |
|------------|----------------------|----------------|------------------------------------------------------------------------------------------------------|
| OPEN AI    | GPT, o1              | ChatGPT        | - o1 uses chain of reasoning. <br/> - 4o with canvas can be used to work collaboratively with openAI |
| ANTHROPIC  | Claude (hi2, sonnet) | CLAUDE         |                                                                                                      |
| GOOGLE     | Gemini               | Gemini Advance |                                                                                                      |   
| COHERE     | Command R+           | Command R+     |                                                                                                      |  
| META       | Llama                | meta.ai        |                                                                                                      |  
| Perplexity | Perplexity           | Perplexity     | Search Engine                                                                                        |  

These LLMs are really good at:
- Synthesizing information
- Fleshing out a skeleton
- Coding

Limitations:
- Specialized domains. Most are not at PhD level but fast approaching.
- Limited Knowledge beyond training cut-off date.
- Hallucination, some responses are not correct and models have not learned.