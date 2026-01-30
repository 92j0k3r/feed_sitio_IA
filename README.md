### Fuente de referencia

- Ruta estándar de extensiones por usuario en Windows: `%USERPROFILE%\.vscode\extensions` (equivalente a `C:\Users\<usuario>\.vscode\extensions`).
- Método de enriquecimiento de extensiones relacionadas con IA usando la API pública de Visual Studio Marketplace
	- https://marketplace.visualstudio.com/_apis/public/gallery/extensionquery?api-version=3.0-preview.1
	- A partir de esa salida se deriva una lista de ExtensionId (y/o nombres) a usar como matching en hunting
		- Búsqueda por TAG: 
			- anthropic, openai, chatgpt, ai, claude, deepseek, gemini, huggingface, llm, grok, qwen, copilot, codewhisperer, azure-openai, ollama, llama, mistral, langchain, rag
		- Búsqueda por categoría IA
