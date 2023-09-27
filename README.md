# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very* easy for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows other to copy and paste their code to replicate or research issues.

In order to create codeblocks in markdown you need to use three backticks (`) 
Not to be confused with quotation (')

```
def fibonacci_of(n):
     if n in {0, 1}:  # Base case
         return n
     return fibonacci_of(n - 1) + fibonacci_of(n - 2)  # Recursive case

 [fibonacci_of(n) for n in range(15)]

```
When you can you should attempt to apply syntax highlighting to your codeblocks

```python

def fibonacci_of(n):
     if n in {0, 1}:  # Base case
         return n
     return fibonacci_of(n - 1) + fibonacci_of(n - 2)  # Recursive case

 [fibonacci_of(n) for n in range(15)]

```

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

Use backticks bash to indicate the code is copied from the console (showing the error thrown)

## Step 4 - Use Emojis (Optional)

GitHub Flavoured Markdown (GFM) supports emoji shortcodes. Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with Lightning | `:cloud_with_Lightning` | 🌩️ | 


## References

- [Basic Writing and Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

