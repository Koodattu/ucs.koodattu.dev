Esimerkki
```
  "tabAutocompleteModel": {
    "title": "codeqwen",
    "provider": "ollama",
    "model": "codeqwen"
  },
```
Kokonaisuus
```
{
  "models": [
    {
      "title": "Llama 3",
      "provider": "ollama",
      "model": "llama3"
    },
    {
      "title": "Ollama",
      "provider": "ollama",
      "model": "AUTODETECT"
    }
  ],
  "customCommands": [
    {
      "name": "test",
      "prompt": "{{{ input }}}\n\nWrite a comprehensive set of unit tests for the selected code. It should setup, run tests that check for correctness including important edge cases, and teardown. Ensure that the tests are complete and sophisticated. Give the tests just as chat output, don't edit any file.",
      "description": "Write unit tests for highlighted code"
    }
  ],
  "tabAutocompleteModel": {
    "title": "codeqwen",
    "provider": "ollama",
    "model": "codeqwen"
  },
  "allowAnonymousTelemetry": true,
  "embeddingsProvider": {
    "provider": "ollama",
    "model": "nomic-embed-text"
  }
}
```
