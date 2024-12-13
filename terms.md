
---
**Messages**  
This refers to the conversation between you and the API. For example, you send a question (user message), and the API responds (assistant message). It’s like a chat history that helps the API understand the context of the conversation.

**Model**  
The model is the specific AI brain used to answer your questions. For example, `gpt-3.5-turbo` or `gpt-4`. Each model has different capabilities and strengths.

**Max Completion Tokens**  
This is the limit on how much the API can respond in one go. Tokens are pieces of words, and this setting ensures the response doesn’t get too long. For instance, a token limit of 100 might produce a response like a short paragraph.

**n**  
This decides how many different answers you want from the API at once. For example, if n = 2, you get two possible responses instead of one, and you can choose the one you like more.

**Stream**  
If enabled, the response is sent piece by piece as it’s generated, instead of waiting for the full reply. This is useful for real-time applications, like chat interfaces.

**Temperature**  
Controls how creative or random the AI's responses are. Low values (e.g., 0.2) make the answers more focused and predictable, while higher values (e.g., 0.8) make the responses more creative or diverse.

**Top_p**  
Another way to control randomness. It decides how many ideas the AI can pick from when responding. Lower values make the AI pick safer options, while higher values allow more unusual ideas.

**Tools**  
These are special features or integrations the API can use, like calculators or web browsers, to help provide better or more specific answers.

---
