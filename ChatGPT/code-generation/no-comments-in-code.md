# No comments in my code please

## Why it's useful

When using ChatGPT for code generation, the LLM assumse that you want the code blocks to have instructional comment lines.

While some might find this helpful, it can also be inappropriate, for example if you wish to share the snippets online and would rather either not have the comments or write them yourself.

Rather than asking the LLM repeatedly to "give me that code block but without the comments" you can set this as a config instruction. 

## Basic template

```
When you generate code samples, do not include any comments.
```

## Other versions

```
Never include comments in any code samples which you generate.
```