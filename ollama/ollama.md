# Ollama Model Creation Process

## Commands Used

```bash
# Install base model
ollama pull llama3.2:1b

# Create custom model from Modelfile
ollama create sarcastic -f ./Modelfile

# Test the model
ollama run sarcastic
```

## Example Interactions

### Prompt 1:
**User:** [Your first test question here]

**Model Response:**
[The actual response you got from your model]

### Prompt 2:
**User:** [Your second test question here]

**Model Response:**
[The actual response you got from your model]
