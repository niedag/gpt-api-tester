# gpt-api-tester
testing chat gpt api calling and DALL-E image generation


For the Exception Catching for Talk To GPT Model
completion["choices"]: the choices field contains an array of potential completions ranked by the model.

    return completion["choices"][0]["message"]["content"] 
means returning the choice 1 model

Message: information related to a specific choice made by the model (the container for metadata and content)
Content: the actual text or information generated by the model for that specific message

Model Selection

For chat completion responses, only **gpt-4-1106-preview** and **gpt-3.5-turbo-1106** will return.
