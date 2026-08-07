# DeepLearning.AI_Short_Courses
![DeepLearning.AI_Short_Courses Logo](https://wordpress.deeplearning.ai/wp-content/uploads/2023/08/Updated-web-preview.png)

DeepLearning.AI Short Courses Repository: A centralized hub for all materials, assignments, and resources from the popular short courses offered by DeepLearning.AI 

## Remote environment setup (Ollama + Gemma 4:31b)

Run the following on the remote Linux environment:

```bash
curl -fsSL https://ollama.com/install.sh | sh
ollama serve >/tmp/ollama.log 2>&1 &
ollama pull gemma4:31b
```
