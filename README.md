<div align="center">
  <img src="demo-img.jpg">
</div>

<h1 align="center">
  Run large language models (LLMs) natively & privately in your own browser. No need for any server-side processing.
</h1>

<div align="center">
  
![GitHub Repo stars](https://img.shields.io/github/stars/addyosmani/chatty)
  
</div>

**Chatty** is your private AI that leverages WebGPU to run large language models (LLMs) natively in your browser, bringing you the most feature rich in-browser AI experience.

# Features ✨

- **In-browser privacy:** All AI models run locally on your hardware, ensuring that your data is processed only on your pc.
- **Offline:** Once the initial download of a model is processed, you'll be able to use it without an active internet connection.
- **Chat history:** Access and manage your conversation history.
- **Supports new open-source models:** Chat with popular open-source models such as Gemma, Llama2 & 3 and Mistral!
- **Responsive design:** If your phone supports WebGl, you'll be able to use Chatty just as you would on desktop.
- **Intuitive UI:** Inspired by popular AI interfaces such as Gemini and ChatGPT to enhance similarity in the user experience.
- **Markdown & code highlight:** Messages returned as markdown will be displayed as such & messages that include code, will be highlighted for easy access.
- **Chat with files:** Load files (.pdf, .txt or .csv) into the browser and ask the models questions about them - fully local! Your documents never gets processed outside of your local environment, thanks to [XenovaTransformerEmbeddings](https://huggingface.co/Xenova/all-MiniLM-L6-v2) & [MemoryVectorStore](https://js.langchain.com/v0.1/docs/integrations/vectorstores/memory/)
- **Custom memory support:** Add custom instructions/memory to allow the AI to provide better and more personalized responses.
- **Export chat messages:** Seamlessly generate and save your chat messages in either JSON or Markdown format.
- **Voice input support:** Use voice interactions to interact with the models.
- **Light & Dark mode:** Switch between light & dark mode.

# Preview

https://github.com/addyosmani/chatty/assets/114422072/04f0651d-530f-491b-8e24-5a58d6df9a25

# Browser support

By default, WebGPU is enabled and supported in both Chrome and Edge. However, it is possible to enable it in Firefox and Firefox Nightly aswell as Safari.
Check the [browser compatibility](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API#browser_compatibility) for more information.

# Acknowledgements & credits

Chatty is built with help from the [WebLLM](https://github.com/mlc-ai/web-llm) project, utilizing [HuggingFace](https://huggingface.co/) and open source LLMs. We want to acknowledge their great work and thank the open source community.
