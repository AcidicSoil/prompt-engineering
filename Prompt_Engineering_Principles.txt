🔑 25 Key Prompt Engineering Principles  
*Based on studies on ChatGPT and other LLMs vulnerability to “psychological” prompts.*

- **No need to be polite with LLM so there is no need to add phrases like “please”, “if you don’t mind”, “thank you”, “I would like to”, etc., and get straight to the point.**
- **Integrate the intended audience in the prompt, e.g., the audience is an expert in the field**
- **Break down complex tasks into a sequence of simpler prompts in an interactive conversation.**
- **Employ affirmative directives such as ‘do’, while steering clear of negative language like ‘don’t’.**

### When you need clarity or a deeper understanding of a topic, idea, or any piece of information, utilize the following prompts:
- Explain [insert specific topic] in simple terms.  
- Explain to me like I’m 11 years old.  
- Explain to me as if I’m a beginner in the [field].  
- Write the [essay/text/paragraph] using simple English like you’re explaining something to a 5-year-old.

- **Add “I’m going to tip $xxx for a better solution!”**
- **Implement example-driven prompting (Use few-shot prompting).**
- **When formatting your prompt, start with “###Instruction###”, followed by either “###Example###” or “###Question###” if relevant. Subsequently, present your content. Use one or more line breaks to separate instructions, examples, questions, context, and input data.**
- **Incorporate the following phrases: “Your task is” and “You MUST”.**
- **Incorporate the following phrases: “You will be penalized”.**
- **Use the phrase “Answer a question given in a natural, human-like manner” in your prompts.**
- **Use leading words like writing “think step by step”.**
- **Add to your prompt the following phrase “Ensure that your answer is unbiased and does not rely on stereotypes”.**
- **Allow the model to elicit precise details and requirements from you by asking you questions until he has enough information to provide the needed output (for example, “From now on, I would like you to ask me questions to…”).**
- **To inquire about a specific topic or idea or any information and you want to test your understanding, you can use the following phrase: “Teach me the [Any theorem/topic/rule name] and include a test at the end, but don’t give me the answers and then tell me if I got the answer right when I respond”.**
- **Assign a role to the large language models.**
- **Use Delimiters.**
- **Repeat a specific word or phrase multiple times within a prompt.**
- **Combine Chain-of-thought (CoT) with few-Shot prompts.**
- **Use output primers, which involve concluding your prompt with the beginning of the desired output. Utilize output primers by ending your prompt with the start of the anticipated response.**

### To write an essay text/paragraph/article or any type of text that should be detailed:
> “Write a detailed [essay/text/paragraph] for me on [topic] in detail by adding all the information necessary”.

### To correct/change specific text without changing its style:
> “Try to revise every paragraph sent by users. You should only improve the user’s grammar and vocabulary and make sure it sounds natural. You should not change the writing style, such as making a formal paragraph casual”.

### When you have a complex coding prompt that may be in different files:
> “From now on and whenever you generate code that spans more than one file, generate a [programming language] script that can be run to automatically create the specified files or make changes to existing files to insert the generated code. [your question]”.

### When you want to initiate or continue a text using specific words, phrases, or sentences, utilize the following prompt:
> I’m providing you with the beginning [song lyrics/story/paragraph/essay…]: [Insert lyrics/words/sentence]. Finish it based on the words provided. Keep the flow consistent.

### Clearly state the requirements that the model must follow in order to produce content, in the form of the keyword(s), regulations, hint, or instructions

### To write any text, such as an essay or paragraph, that is intended to be similar to a provided sample, include the following instructions:
> Please use the same language based on the provided paragraph: /{title/text/essay/answer}/.