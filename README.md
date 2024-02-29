# Local-Coding-Assistant
Building a Local Coding Assistant with Code Llama and Cody
# Other options
Continue
## Getting up to speed
* If you are just starting out with local LLMs, refer to my guide on setting up your own local LLM using Ollama here: https://github.com/Akshay-Dongare/Ollama-Local-LLM
## Pulling CodeLlama
* Open cmd and run: `ollama pull codellama:7b-code`
* Note: codellama is a LLM finetuned for coding domain
## Integration with Visual Studio Code
* To get your own personal, free, local and accurate coding assistant going, follow these steps
  1. Open Visual Studio Code
  2. Go to extensions tab: `ctrl+shift+x`
  3. Install Cody AI by Sourcegraph extension and enable it globally
  4. Navigate to the Cody extension settings by pressing `ctrl+shift+p` and typing "Cody:Extension Settings"
  5. Navigate to `Cody › Autocomplete › Advanced: Provider` and select `experimental-ollama`
  6. Navigate to `Cody › Autocomplete › Advanced: Server Endpoint` and type `http://localhost:11434`
  7. Your local coding assistant is up and running!

## Demo
* To check it's performance, make a new python file and type `#fibonacci method` and codellama:7b-code will start auto-completing the code for you!
* Example: 
* ![alt text](image-1.png) 
* ![alt text](image-2.png)
* To check logs, go to `Console>Output` and select `Cody by Sourcegraph`
* You should see something similar to: 
* ![alt text](image.png)

## Sources
* https://sourcegraph.com/blog/local-code-completion-with-ollama-and-cody
* [text](https://www.youtube.com/watch?v=gY_E3QBZ-NE&t=1s&ab_channel=MatthewBerman)
