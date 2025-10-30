## Kotlin Client Example for OpenAI Chat Completions API

Start your [AI Chat .NET App](https://docs.servicestack.net/ai-chat-api)

Run the example:

```bash
./gradlew run
```

Add just the `ChatCompletion` and its dependent DTOs:

```bash
npx get-dtos kotlin http://localhost:5000 --include "ChatCompletion.*" -qs "Package=org.example"
```

Alternatively, add all DTOs:

```bash
npx get-dtos kotlin http://localhost:5000 -qs "Package=org.example"
```

Update DTOs:

```bash
npx get-dtos kotlin
```
