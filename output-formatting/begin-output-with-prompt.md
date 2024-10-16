# Instruction snippet: begin your outputs by repeating my prompt

## Why it's useful

When copying and pasting from the web UI for ChatGPT and into notebooks, it's helpful to have your prompt. 

You could do this manually. But you can save time by just fixing it as an instruction for GPT.

## Basic version

This instruction will just get you the prompt at the start of your outputs:

```
Please begin every output with a summary of the prompt that I used. Fix any typos, but don't omit any details from the prompt.
```

## Format the outputs

I find it helpful to ask GPT to adhere to a specific format when outputting. 

You can try something like:

```
Please generate your outputs in this format, preserving the markdown tags that I provide and following my instructions exactly:

# Prompt

Repeat the propmt that I used

# Output

Provide your output

```