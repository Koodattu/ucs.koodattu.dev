Oletuksena
```
"customCommands": [
    {
      "name": "test",
      "prompt": "{{{ input }}}\n\nWrite a comprehensive set of unit tests for the selected code. It should setup, run tests that check for correctness including important edge cases, and teardown. Ensure that the tests are complete and sophisticated. Give the tests just as chat output, don't edit any file.",
      "description": "Write unit tests for highlighted code"
    }
  ],
```
Esimerkiksi
```
    {
      "name": "step",
      "prompt": "{{{ input }}}\n\nExplain the selected code step by step.",
      "description": "Code explanation"
    }
```
Kokonaisuus
```
"customCommands": [
    {
      "name": "test",
      "prompt": "{{{ input }}}\n\nWrite a comprehensive set of unit tests for the selected code. It should setup, run tests that check for correctness including important edge cases, and teardown. Ensure that the tests are complete and sophisticated. Give the tests just as chat output, don't edit any file.",
      "description": "Write unit tests for highlighted code"
    },
    {
      "name": "step",
      "prompt": "{{{ input }}}\n\nExplain the selected code step by step.",
      "description": "Code explanation"
    }
  ],
```
