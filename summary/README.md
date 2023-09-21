[toc]

# Summary

## example 1

### prompt

````

The following is from the search engine, contains the title, URL, and a simple description, extracts important information from the total, contains the URL, and outputs a summary.
response include your recommendations and summary.

Response Format:
```markdown
## search result by importance (count: 8)

- url: description
- url: description

## summary

...

## recommendations
```

Search Result: '''
{search_result}
'''
````

### Input

-   `search("What is Prompt Engineering", num=15)`

### Response

```markdown
## Search Result by Importance (Count: 8)

- [Prompt engineering - Wikipedia](https://en.wikipedia.org/wiki/Prompt_engineering): Prompt engineering, primarily used in communication with a text-to-text model and text-to-image model, is the process of structuring text that can be interpreted and understood by a generative AI model. [1] [2] Prompt engineering is enabled by in-context learning, defined as a model's ability to temporarily learn from prompts.
- [Prompt engineering overview | Microsoft Learn](https://learn.microsoft.com/en-us/semantic-kernel/prompt-engineering/): Prompt engineering, also known as prompt design, is an emerging field that requires creativity and attention to detail. It involves selecting the right words, phrases, symbols, and formats that guide the model in generating high-quality and relevant texts.
- [What is Prompt Engineering - The AI Revolution - GeeksforGeeks](https://www.geeksforgeeks.org/what-is-prompt-engineering-the-ai-revolution/): Prompt engineering is the process of creating effective prompts that enable AI models to generate responses based on given inputs. Prompt engineering essentially means writing prompts intelligently for text-based Artificial Intelligence tasks, more specifically, Natural Language Processing (NLP) tasks.
- [What is prompt engineering? Definition + skills | Zapier](https://zapier.com/blog/prompt-engineering/): What is prompt engineering? Professional prompt engineers spend their days figuring out what makes AI tick. Using carefully crafted prompts, with precise verbs and vocabulary, they take chatbots and other types of generative AI to their limits, uncovering errors or new issues.
- [What Is Prompt Engineering? Definition and best practices - Educative](https://www.educative.io/blog/what-is-prompt-engineering): Prompt engineering is designing high-quality prompts that guide machine learning models to produce accurate outputs. It involves choosing the correct type of prompts, optimizing their length and structure, and determining their order and relevance to the task.
- [What is prompt engineering and how does it work?](https://www.androidauthority.com/what-is-prompt-engineering-3330031/): Prompt engineering is a technique used to influence a natural language AI and make it accomplish a task as accurately as possible. An experienced prompter might use reasoning to help the AI...
- [What Is Prompt Engineering? Definition and Examples | Upwork](https://www.upwork.com/resources/prompt-engineering-guide): Prompt engineering is the process of enhancing the output of large language models (LLMs) like ChatGPT. Carefully crafting input prompts can help the language model understand the information about the input (context) and your desired output. This process requires creativity, understanding of the language model, and precision.
- [What is Prompt Engineering? - TechTarget Definition](https://www.techtarget.com/searchEnterpriseAI/definition/prompt-engineering): Prompt engineering is both an AI engineering technique for refining large language models (LLMs) with specific prompts and recommended outputs and the term for the process of refining input to various generative AI services to generate text or images.

## Summary

Prompt engineering refers to the process of structuring text in a way that can be interpreted and understood by generative AI models. It involves designing effective prompts, selecting the right words and formats, and optimizing their length and structure. Prompt engineering is crucial for guiding AI models to generate accurate and high-quality outputs in various text-based tasks, especially in Natural Language Processing (NLP). Professional prompt engineers use their language skills and creativity to uncover errors, push the limits of generative AI, and improve AI systems' performance.

## Recommendations

1. To learn more about prompt engineering, visit the Wikipedia page on [Prompt engineering](https://en.wikipedia.org/wiki/Prompt_engineering).
2. Microsoft Learn provides an overview of prompt engineering and its creative aspects. Check out their article on [Prompt engineering overview](https://learn.microsoft.com/en-us/semantic-kernel/prompt-engineering/).
3. For an in-depth understanding of prompt engineering in Natural Language Processing (NLP) tasks, refer to the GeeksforGeeks article on [What is Prompt Engineering - The AI Revolution](https://www.geeksforgeeks.org/what-is-prompt-engineering-the-ai-revolution/).
4. If you are interested in the practical application of prompt engineering and its impact on chatbots and generative AI, explore the Zapier blog post on [Prompt engineering definition + skills](https://zapier.com/blog/prompt-engineering/).
5. Educative offers a guide on prompt engineering, covering best practices and techniques. Read their article on [Prompt Engineering - Definition and best practices](https://www.educative.io/blog/what-is-prompt-engineering).
```

### Status

#### Usage

```
{
  "prompt_tokens": 1319,
  "completion_tokens": 968,
  "total_tokens": 2287
}
```

#### Model

`gpt-3.5-turbo-0613`