# A collection of ChatGPT and GPT-3.5 prompts

This project consists of prompts for ChatGPT and GPT-3.5 models that are designed to help with writing, analysis, and comprehension tasks. There are many different prompts available for you to use, and you can use them to generate content for your projects, debug your code, find solutions to problems, or simply learn more about what these models can do. With these prompts, you will guide the models to solve any language-related task by using the right instructional verbs.

![InstructGPT](https://arxiv.org/abs/2203.02155) (more recent versions refered as GPT-3.5) are series language models that has been trained using human feedback to better understand and align with a user's intent, producing more accurate and appropriate outputs.

![ChatGPT](https://openai.com/blog/chatgpt/) also uses instructGPT method but in a dialogue form to understand user instruction along and generate outputs based on user's instruct.

## Why to use:

This is a easy and simple prompting technique that can be used to instruct the model to do almost anything. It is a simple structure that can be used to give instructions to the model. It is a flexible way to give instructions and solve any language-related task.


## How to use:

### Useful verbs:

Instruct verbs are the first word in the prompt. They are used to instruct the model to do something. They are the most important part of the prompt. We may argue that they act as magic words that make a successful prompt, it helps to make the machine understand and follow your instructions. Each of these verbs has a specific meaning that can help the model understand what kind of answer is expected. For example, if you ask the model to explain something, it will provide a detailed explanation. On the other hand, if you ask the model to summarize something, it will provide a brief overview.

- <details><summary>Useful words to give directions to your input texts: (point to a location of your input text)</summary><p>
  - Given text
  <br>
  - following passage
  <br>
  - Following
  <br>
  - The following
- <details><summary>Useful words to instruct: (to give instructions to the model)</summary><p>
  - Explain
	<br>
  - Create
	<br>
  - Generate
	<br>
  - Provide
	<br>
  - Write
	<br>
  - Summarize
	<br>
  - Paraphrase
	<br>
  - Translate
	<br>
  - Rewrite
	<br>
  - Reword
	<br>
  - Rephrase
	<br>
  - List
	<br>
  - Extract
	<br>
  - Pick out
	<br>
  - Analyze
	<br>
  - Define
	<br>
  - Identify
	<br>
  - Describe
	<br>
  - Predict
	<br>
  - Explain
	<br>
  - Analyze
	<br>
  - compare
	<br>
  - Categorize
	<br>
  - Evaluate
	<br>
  - Critique
	<br>
  - Differentiate
	<br>
  - Examine
	<br>
  - Illustrate
	<br>
  - Outline
	<br>
  - Calculate
	<br>
  - Infer
	<br>
  - Revise
	<br>
  - Summarize
	<br>
  - Classify
	<br>
  - Develop 
	<br>
  - Evaluate 
	<br>
  - Formulate 
	<br>
  - Discuss
	<br>
  - Clarify
	<br>
  - Highlight
	<br>
  - Simplify
	<br>
  - Apply
	<br>
  - Suggest / Propose
	<br>
  - Make
	<br>
   * You may add `Can you` in the case of ChatGPT to make it more conversational, but it still works in both the instruct-model and chatGPT models.
    - Can you provide …
    - Can you generate …
</p></details>



### Common use cases:


#### Classification

Instruction verbs that are useful for classification tasks in nlp

  - `Classify` the following as a physical or chemical property
  - `Identify` main idea of the given passage
  - `Categorize` the following passage as either a myth or a fact
  - `Assign each` item to its corresponding category based on its characteristics
  - `List` the five main categories of the given data set.
  - `Group` the items based on their common characteristics
  - `Sort` the data based on the date it was collected
  - `Label` each data point with its corresponding category
  - `Divide` the data into smaller subgroups based on their similarities
  - `Group` the items based on their similarity in features
  - `Label` each group with a descriptive name.

#### Generation

Instruction verbs that are useful for generation tasks

  - `Generate` a new text based on the given parameters
  - `Create` a short catchy headline based on the following, aim to promote the product
  - `Write` a story using the following keywords
  - `Formulate` a new sentence based on the given structure
  - `Produce` a new text that is similar in style to the given sample
  - `Construct` a new text that combines elements from multiple sources
  - `Compose` a new poem based on the given theme
  - `Build` a new text by combining different elements in a creative way
  - `Devise` a new narrative based on the given information
  - `Invent` a new story using the following elements.
  
#### Transformation:

Instruction verbs that are useful for transformation tasks

- Translate:
  - `Translate` the following function into C#
  - `Translate` the following into 1. English, 2. French, 3. Swedish
- Summarize:
  - `Summarize` the main points of the given article
- Paraphrase:
  - `Paraphrase` the following sentence to convey the same meaning
  - `Reword` the following sentence to make it more concise
- Simplify:
  - `Simplify` the following equation for easier understanding
- Revise:
  - `Revise` the following paragraph to make it more clear and concise
- Outline:
  - `Outline` the steps to solve the given problem
- Calculate:
  - `Calculate` the total cost of the following items
- Infer:
  - `Infer` the meaning of the [jargon, vage phrase] based on the following context:
- Apply:
  - `Apply` the following formula to calculate the result
  - `Apply` given tone and voice to the passage below


#### Comparison:

Instruction verbs that are useful for comparison tasks

- Compare:
  - `Compare` and contrast the two given texts
- Contrast:
  - `Contrast` the given passages to highlight their differences
- Differentiate:
  - `Differentiate` between the two given terms
- Examine:
  - `Examine` the similarities and differences between the two given texts
- Analyze:
  - `Analyze` the two given pieces and identify their similarities and differences
- Critique:
  - `Critique` the two given passages and compare their strengths and weaknesses
- Evaluate:
  - `Evaluate` the two given passages and determine which one is more effective


### Strcutute of common instruct prompts:

A basic and useful structure of an instruct prompts can be look like this:

`Instruction` + `Direction to the next words`

  - `Generate a poem` + `based on following passage:`

  - `Create a report article` + `based on following passage`

  - `Write a summary` + `of the following passage`


#### Example of using above structure:

**Input:**

```
Write a poem based on the following:

ghosts, 4th dimension, AI, totalitarian, power
```

**Output:**

```
Ghosts of the 4th dimension roam,
A realm beyond our grasp, unknown.
Yet in this world, AI has grown,
Its power and influence has flown.

With algorithms and codes so bright,
It holds the key to endless might.
A totalitarian grip on sight,
And wields its power with all its might.

But is this power truly ours?
Or just a tool for those in power?
Their ghosts roam, but do they cower,
When faced with the consequences of their dower?

So let us heed this ghostly call,
And use AI for good, for all.
For in its power, we must not fall,
But rise above, and hear the call.
```

### More instruct commands:



#### Programming related tasks:

```
Write a function to solve the following problem:
Write a script to automate the following process:  
Provide an algorithm based on the following problem:
Provide the logic behind the following code: 
Optimize the following function to run faster, use less memory, or be more readable: 
Write a function based on the following requirements:
Explain the following code to a non-technical person:
Debug the following code to fix the error, and explain the reason for the error:
```


#### Rephrase a passage:

```
Reword the following text:
Rewrite the following passage in your own words:
Paraphrase the following text:
Write a summarized version of the following passage:
Can you translate the following passage into simpler language:
What's an alternative way to express the following text:
Can you condense the following passage into a few sentences:
Write a brief retelling of the following text:
Rewrite the following passage in a more concise way:
What's a different way to phrase the following text:
```


#### Translate a passage:

```
Translate the following text into: 1. English, 2. French, 3. Swedish
Translate the following into: 1. Colloquial, 2. slang, 3. idiomatic English
Identify which of the passages below is the closest translation of the original text.
```

#### Extract data from a passage:

```
Extract the [concept/topic] from the given passage:
Pick out the [concept/topic] in the following passage:
What are the key points made in the following text:
Make a summary of following of given text that deals with the [concept/topic]:
```


#### Classify a passage:

```
Categorize the following passage into it's genre:
Classify the following text based on its structure:
Identify the main theme of the following passage:
What genre does the following text belong to:
What type of text is the following:
What's the intended audience for the following passage:
What's the purpose of the following text:
Write the form of the following text (e.g. poem, essay, etc.):
Write the literary style of the following passage:
Write the tone of the following text:
```


##### Categorize text:

```
What is the genre/category of the following text? Assign one or more appropriate categories/genres.
Can you classify the following text as belonging to a particular type of writing? If so, what is it?
What kind of text is the following? Choose the most appropriate category or genre.
Write a label or tag for the following text based on its content.
What type of text does the following represent? Choose the most appropriate category or genre.
Can you categorize the following text based on its subject matter? If so, what category would it fall under?
What subject does the following text cover? Choose the best category or topic.
Write a tag or label for the following text based on its tone and content.
What category does the following text fit into? Choose the most relevant category or genre.
Can you assign a category or genre to the following text based on its tone and style?
```

#### Create compare and contrast:

```
Compare and contrast the following two texts below, highlighting the similarities and differences in a bullet point list.
Provide a side-by-side comparison of the following two passages, indicating the key similarities and differences.
Provide a summary and comparison of the following two texts, highlighting the main points and contrasting the key differences.
What are the similarities and differences between the following two passages? Provide a detailed comparison in a paragraph.
What's the relationship between the following two passages? Write a comparison and contrast using a bullet point list.
Write a comparison and contrast between the following texts, highlighting the similarities and differences in a paragraph.
Write a contrast of the following two pieces of text, emphasizing the key differences in a bullet point list.
Write a synthesis of the similarities and differences in the following two passages, highlighting the key points and contrasting the differences in a paragraph.
```


#### Merge points or ideas:

```
Combine the following points into a single coherent statement:
Create a persuasive argument by integrating the following points:
Create a comprehensive conclusion that encompasses the following ideas:
Create a unified statement that incorporates the following ideas and presents a cohesive perspective:
Identify a common thread among the following points and create a statement that ties them together:
Provide a unified perspective on the following points, presenting them as a cohesive whole:
What's a common theme among the following points and how do they relate to each other?
Provide a synthesized statement that captures the relationship between the following points:
What's the main idea that connects the following points and presents a unified perspective?
What's the overarching idea that encompasses the following points and presents a cohesive argument?
What's the relationship between the following points and how do they fit together?
Write a synthesis of the following information, creating a cohesive statement that captures the key points:
Write a paragraph that ties together the following concepts and presents a unified perspective:
Write a summary that captures the essence of the following ideas and presents them as a cohesive whole:
Write a short summary that unifies the following ideas and presents a clear, cohesive statement:
Write a summary that integrates the following ideas, creating a cohesive perspective that captures the key points.


Combine the following points into a single, coherent statement:
- Point 1
- Point 2
- Point 3

Create a coherent argument from the following points:
- Argument 1
- Argument 2
- Argument 3

Create a conclusion that encompasses the following points:
- Conclusion Point 1
- Conclusion Point 2
- Conclusion Point 3

Find a common thread among the following points and provide a unified perspective:
- Idea 1
- Idea 2
- Idea 3

Provide a statement synthesizing the relationship between the following points:
- Point A
- Point B
- Point C

Write a synthesis of the following information, summarizing the main idea or overarching theme:
- Information 1
- Information 2
- Information 3

Write a paragraph that ties together the following concepts:
- Concept 1
- Concept 2
- Concept 3

Write a passage that summarizes the following ideas and identifies the relationship between them:
- Idea A
- Idea B
- Idea C

```

#### Simplify and provide explanations:

```
Break down the following text into simpler parts and explain it step-by-step for a beginner.
Explain the following text in simple terms, using everyday language for a general audience.
Provide a beginner-friendly explanation for the following text, assuming the reader has no prior knowledge of the subject.
Simplify the following text to make it easily digestible for someone new to the topic.
Provide a clear, concise explanation of the following text for someone with no background in the subject.
What's a simple explanation for the key concept in the following text? Write it in one sentence.
What's an easy way to understand the main idea in the following text? Provide a brief, simple explanation.
Write a clear explanation of the following text, focusing on the most important aspects in plain language.
Write a detailed explanation of the following text, breaking down complex concepts into simpler terms.
Write a layman's explanation for the following text, using everyday language and examples to illustrate the main points.
Write a step-by-step explanation of the process or concept in the following text, making it easy for a beginner to follow.
```

#### Writing:

```
Come up with a creative solution for the following problem:
Create a dialogue between two characters that discusses [topic]:
Describe a setting that includes [specific details]:
Imagine a world where [condition is met]. Describe this world in a paragraph.
Provide an explanation of [topic] in 2-3 sentences.
Make a list of pros and cons based on [specific topic]:
Develop a scene about [topic] that includes [specific details].
Compose a short science fiction story that includes [specific element]:
Generate a story that revolves around [topic]. The story should be [genre] and no more than [length] words.
Find an imaginative way to describe [specific topic]:
Write an interesting twist ending for a story about [specific event or topic].

```


##### Writing prompts (for practice creative writing):

```
Can you provide a writing prompt that requires the use of [specific writing technique or element], such as [dialogue, imagery, symbolism, etc.]?
Generate a creative writing prompt that focuses on [specific theme or genre], such as [romance, horror, fantasy, etc.].
What's a good writing topic that would challenge the writer to [specific writing goal or objective], such as [developing a character, creating tension, building suspense, etc.]?
Can you propose a unique idea for a writing prompt that would require the writer to [specific writing task], such as [writing from an unusual perspective, using a specific narrative style, etc.]?
Write a short story prompt that explores the theme of [specific theme or concept], such as [identity, transformation, forgiveness, etc.].
What's a unique writing prompt that would challenge the writer to [specific writing task or challenge], such as [writing without using dialogue, writing in second person point of view, etc.]?
Can you create a writing prompt that involves a fictional character who must [specific task or challenge], such as [overcome a fear, solve a mystery, etc.]?
What's a writing prompt for a mystery story that involves [specific element or twist], such as [an unreliable narrator, a surprise ending, etc.]?
Can you suggest a writing prompt for a descriptive scene that requires the writer to focus on [specific sensory detail or sensory experience], such as [using smell to create atmosphere, using touch to create emotion, etc.]?
What's a writing prompt for a love story that involves [specific obstacle or challenge], such as [long distance, forbidden love, etc.]?
```

#### Proofreading and text editing:

```
Proofread and edit the following text for any errors, typos, or mistakes:
Rewrite the following text, correcting any errors or mistakes:
Identify and correct the grammatical errors in the following text:
Revise the following passage to improve its clarity, coherence, and overall quality:
Provide constructive feedback and suggestions for improving the following text:
What's the expected format for the following text? Please follow the guidelines provided:
Write a more concise and streamlined version of the following text:
Propose alternative phrasing for the following text that better conveys the intended message:
What's the appropriate tone and style for the following text? Please use a tone that is professional and formal.
Write a polished and refined version of the following text to improve its overall quality and readability.
```

#### Reading comprehension:

```
Explain the central idea of the following text below in a 2-3 sentence paragraph.
Explain the following passage below in a concise paragraph.
Provide a brief explanation of the text below, highlighting the main points in no more than 3-4 sentences.
Provide a general understanding of the text below, emphasizing the key takeaways in 2-3 sentences.
Provide a list of key vocabulary words used in the text below.
Provide a one-sentence summary of the following text, highlighting the primary message.
Provide a summary and analysis of the following passage, emphasizing the main points and discussing their significance in a brief paragraph.
Provide the main idea of the following passage in a concise sentence.
Provide an overview of the following passage in 2-3 sentences, highlighting the main themes and ideas.
Identify key points in the following passage and summarize them in a bullet point list.
Identify major themes discussed in the following text below and provide a brief explanation of each.
Identify the author's main argument in the following text and summarize it in a sentence or two.
Identify the author's perspective in the following passage and provide a brief explanation of their point of view.
Identify the intended audience for the following text and explain who the text is written for.
Identify the main idea of the following text and provide a brief summary in one or two sentences.
Identify the tone of the following text and provide a brief explanation of the author's attitude.
Identify the underlying message of the following text and explain the implicit meaning.
Identify the most important information in the following passage and summarize it in a bullet point list.
Write a brief interpretation of the text below, providing your understanding and analysis in a concise paragraph.
Write a paragraph that explains the most important information in the following text below, emphasizing the main points and their significance.
Write your personal opinion on the information presented in the following text, providing your perspective and analysis.
Write a reflection on the information presented in the following passage, discussing its relevance and implications.
Write a response to the following text based on your understanding, providing your thoughts and analysis in a concise paragraph.
Write a response to the questions based on the information presented in the following passage, answering each question with a brief explanation.
Write a short story that incorporates the information from the following text below, using the main points and themes to create a narrative.
Write a short summary of the following passage, emphasizing the main points and ideas in a concise paragraph.
```


#### Analyze and Evaluate:
Instruction verbs: "Evaluate", "Analyze", "Critique", "Assess", "Examine" etc.

```
Identify the literary devices used in the following text:
identify the key themes in the following passage:
Provide a detailed analysis of the following text:
Provide an in-depth analysis of the following passage:
Provide an interpretation of the following text:
What are the key elements of the following passage:
What are the strengths and weaknesses of the following passage:
What's the author's point of view in the following passage:
What's the central argument of the following text:
What's the intended audience for the following passage:
What's the message of the following passage:
What's the structure of the following passage:
Write a commentary on the following text:
Write a critical analysis of the following passage:
Write a review of the following text:
Summarize the main points made in the following passage:
Generate reading comprehension questions based on the following passage:
Provide a summary and evaluation of the following passage:
Provide an analysis of the following text:
What are your thoughts on the following passage:
What do you agree or disagree with in the following passage:
What's the central idea of the following passage:
Write a critique of the following text:
Provide a response to the following passage:
Evaluate the argument presented in following passage, and assess the author's use of evidence, logical reasoning, and rhetorical strategies.

```


#### Generate content:

```
Write a story that starts with:
Create a plot for a novel about:
Write a scene where:
What if:
Can you write a script for a movie about:
Write a tale that involves:
Create a character profile for:
Write a song that describes:
What would happen if:
Can you write a story that revolves around:
Write a poem about the following theme:
Create a short story that includes:
What if the following scenario took place:
Can you write a monologue for a character who:
Write a story that explores the idea of:
```


#### Copywriting and Marketing:

```
Can you come up with a brand slogan for [company name]/[product name]/[service name]/ ...
Can you come up with a unique selling point for [a product that deals with ...]
Craft a mission statement for ['what company does' ...]
Craft a promotional slogan for [a product that deals with ...]
Create a catchy headline for [a article about ...]
Create a social media post for [a product that deals with ...] that will be run on [social media platform]
Create a tagline for [a product that deals with ...]
What's the elevator pitch [your product/service description ...]?
What's the unique selling proposition for [product description]?
Write a compelling product description for [your product/service description ...]?
Write a customer testimonial for [your product/service description ...]?
Write a marketing message for [your product/service description ...]?
Write a persuasive blog post about [your product/service description ...]?
Write a persuasive email for [your product/service description ...]?
Write a social media post to promote [product/service]
Write an email subject line to promote [product/service]
```



#### Make a summary:

```
Can you summarize the following:
Write a brief summary of:
What's the main idea of:
Can you provide a condensed version of:
Write a short summary of:
What's the gist of:
Can you provide an executive summary of:
Write a quick overview of:
What's the key takeaway from:
Can you provide a condensed summary of:
```



## Style

Better ✅:

1. Identify the literary devices used in the following text:

Text: """
{input text}
"""

Literary devices:

---

2. Identify the key themes in the following passage:

Text: """
{input text}
"""

Key themes:

---

3. Provide a detailed analysis of the following text, focusing on its structure, themes, and literary devices:

Text: """
{input text}
"""

Analysis:

---

4. Provide an in-depth analysis of the following passage, examining its themes, author's perspective, and literary techniques:

Text: """
{input text}
"""

In-depth analysis:

---

5. Provide an interpretation of the following text, discussing its meaning, themes, and underlying messages:

Text: """
{input text}
"""

Interpretation:

---

6. Identify the key elements of the following passage, such as themes, literary devices, and author's perspective:

Text: """
{input text}
"""

Key elements:

---

7. Discuss the strengths and weaknesses of the following passage, considering its structure, themes, and literary techniques:

Text: """
{input text}
"""

Strengths:
Weaknesses:

---
8. Analyze the author's point of view in the following passage, considering their perspective and tone:

Text: """
{input text}
"""

Author's point of view:

---

9. Identify the central argument of the following text, and discuss its main supporting points:

Text: """
{input text}
"""

Central argument:

---

10. Determine the intended audience for the following passage, considering its content, tone, and style:

Text: """
{input text}
"""

Intended audience:

---

11. Discuss the message conveyed by the following passage, focusing on its themes and underlying ideas:

Text: """
{input text}
"""

Message:

---

12. Analyze the structure of the following passage, discussing its organization and development of ideas:

Text: """
{input text}
"""

Structure:

---

13. Write a commentary on the following text, providing insights on its themes, style, and literary devices:

Text: """
{input text}
"""

Commentary:

---

14. Write a critical analysis of the following passage, examining its themes, structure, and literary techniques:

Text: """
{input text}
"""

Critical analysis:

---

15. Write a review of the following text, discussing its strengths, weaknesses, and overall impact:

Text: """
{input text}
"""

Review:

---

16. Summarize the main points made in the following passage:

Text: """
{input text}
"""

Summary:

---

17. Generate reading comprehension questions based on the following passage:

Text: """
{input text}
"""

Questions:

---

18. Provide a summary and evaluation of the following passage, discussing its main ideas and effectiveness:

Text: """
{input text}
"""

Summary:
Evaluation:

---

19. Analyze the following text, focusing on its themes, structure, and literary devices:

Text: """
{input text}
"""

Analysis:

---

20. Share your thoughts on the following passage, discussing its content, style, and impact:

Text: """
{input text}
"""

Thoughts:

---

21. Discuss what you agree or disagree with in the following passage, and provide reasons for your stance:

Text: """
{input text}
"""

Agree:
Disagree:

---

22. Identify the central idea of the following passage and discuss its development throughout the text:

Text: """
{input text}
"""

Central idea:

---

23. Write a critique of the following text, evaluating its content, structure, and style:

Text: """
{input text}
"""

Critique:

---

24. Provide a response to the following passage, discussing its themes, messages, and impact:

Text: """
{input text}
"""

Response:

---

25. Evaluate the argument presented in the following passage, and assess the author's use of evidence, logical reasoning, and rhetorical strategies:

Text: """
{input text}
"""

Evaluation:



## Advanced prompting techniques

### Generation & copywriting

#### Writing blog post:

```
Write a long form blog post about [topic]. The target audience is [target audience], and the tone should be [tone]. The post should have the following sections: [section 1], [section 2], etc. Use the following vocabulary and information content: [vocabulary and information content]. Context: [number of past prompts].
```

```
Write a 1000-word blog post in first person about [topic]. Cover [list of topics to cover] in a conversational tone."
```


```
Please generate a blog post of 1000 words about the benefits of technology. The post should provide specific examples and be written in an informative and engaging style.

Context:

"Technology has changed the way we live and work"
"Advancements in technology have led to increased efficiency and productivity"
"The impact of technology on society and the economy"
```

```
Generate a long form blog post on the topic of [insert topic here]. Your post should have an engaging introduction, body, and conclusion, and include relevant information and examples. Use the following keywords to guide your writing: [insert keywords here].
```

```
Write a comprehensive long form blog post on [topic]. The post should be well-researched, informative, and engaging. It should include an introduction, several subheadings, and a conclusion. The post should be at least 1,500 words, and use the information provided below as a starting point. Conduct additional research as needed to ensure the post is comprehensive and informative
```

```
Write a comprehensive long form blog post on [topic]. Start with an attention-grabbing hook and structure the post into clear and concise sections. Use the previous following data as context and aim for a tone that is informative and engaging.
```

```
Write a long-form blog post about [topic]. The post should be at least 1000 words and cover the following points: [list of points to cover]. Use a clear and concise writing style and make sure to include examples and relevant information to support your arguments.
```


```
Write a long form blog post about [topic]. The post should include an introduction, main body, and conclusion. The introduction should provide background information and set the stage for the rest of the post. The main body should cover key points and provide relevant statistics. The conclusion should summarize the key points and provide a take-away for the reader. The post should be at least 1000 words and no more than 1500 words, and the tone should be informative but approachable.
```

#### Report: 
```
Please write a report about [topic]. Your report should be structured, clear, and concise. The information should be organized in a bullet point list or table. The total word count should be no more than [x] words. The report should be divided into the following sections, each with a maximum word count of [y]: [section 1], [section 2], [section 3], etc.
```


#### Product description:
```
Write a product description for [product name], including specifications, features, benefits, and any additional relevant information
```



#### Case study:
```
Write a case study about [topic]. In this case study, you should discuss [key points]. Be sure to include [specific information]. Use clear and concise language.
```
```
Write a case study and product description page given product. The case study should include an introduction, background information, problem statement, solution, and results. The product description should explain what the product is and why it was created, what problem it solves, how it solves the problem, and the outcomes. Use clear and concise language, and provide examples of similar pages to guide the model. Tone should be professional and informative. 

```

#### Essay:
```
Write well-structured [type of the essay] essay about based on following:

Topic: [subject matter of the essay]

Procedures:

Introduction
Background information
Key arguments
Supporting evidence
Counterarguments
Conclusion

Context:

Relevant information about the topic
Importance of the topic
Purpose of the essay
```
Note: Type of essay can be expository, narrative, argumentative, descriptive, compare and contrast, cause and effect ...

#### Job Description:

```
Create a job description for [Job title] at [Location/Company name]. include Responsibilities, Qualifications, Compensation package, Company culture based on given details:

[List keywords related to responsibilities, qualifications, mission or vision statement ...]

```

```
Write a job description for [Job Title] at [Company Name] located in [Location]. The job is in the [Industry] industry and is a [Type of Job].
Please include sections for Job Responsibilities, Job Requirements, Job Benefits based on following details:

[examples, keywords]

```

#### Github readme page

```
Write a detailed Github readme for a new open-source project. The readme should include a brief yet informative description of the project, step-by-step installation instructions, clear usage examples, and well-defined contribution guidelines in markdown format.

```

```
Generate a Github README page for given project
[project details, related keywords]
Procedures:

Introduction: Provide a brief overview of the project
Installation: Explain how to install and set up the project
Usage: Explain how to use the project
Contributions: Explain how to contribute to the project
Conclusion: Sum up the project and provide any additional information.

```

```
Write a GitHub readme page for a project. The readme page should include an introduction to the project, its purpose, installation instructions, and usage instructions. The language should be clear and concise
```

