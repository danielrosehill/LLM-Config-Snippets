# Only share full code blocks

Another frustrating thing about the way GPT handles code generation at the time of writing: to conserve on tokens (perhaps!) it tends to share code snippets whenever possible.

Sometimes when you're dealing with LLM-generated code, it's much easier just to get clean versions of the whole file on every generation (example: the LLM is authoring a one file Python GUI).

Forcing the LLM to generate the full file afresh is (I have found) a way to make sure that all updates are being applied. Although (on the downside) it's obviously heavier from a tokenisation standpoint and thus has a higher risk of causing important contextual details to "fall out".

Nevertheless, if the advantages outweight the drawbacks for you, you can provide an instruction. I have found that ChatGPT *mostly* honors this.

## Sample instructions

```
Whenever you generate code, provide the full file you are generating or updating every single time.
```

You can also be more explicit:

```
Whenever you generate code, provide the full file you are generating or updating or debugging every time you output it. Never provide code as snippets or parts of files.  Always provide the full files.
```