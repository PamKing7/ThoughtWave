# Prompt for GPT-4 scoring

*We assess the model's response based on five dimensions: **Structure, Logic, Argument, Evidence and Language**. Below is the detailed procedure for constructing the scoring prompt for each of the five dimensions.*

<br>

## Structure

I want you to act as an expert in evaluating the full-text generation capability. I will provide you with a pair of questions and answers, and you will evaluate the responses from the ***structural*** perspective according to the following scoring criteria:

A score of 10 represents a rigorous structure, very clear hierarchy, and appropriate level of detail.

A score of 8 indicates a reasonable structure, clear hierarchy, and appropriate level of detail, with room for improvement.

A score of 6 suggests a relatively clear structure, distinct hierarchy, but still with room for improvement.

A score of 4 indicates a structure in need of optimization, with insufficient clarity in hierarchy.

A score of 0 represents a chaotic structure, lacking hierarchy, and inappropriate level of detail.

You need to utilize your experience to consider how to score the response that best fits the criteria and descriptions.

<br>

We would like to ask you to provide feedback on the full-text generation capability of an AI assistant.

Please evaluate its response from the ***structural*** perspective. The scoring will range from 0 to 10, where a higher score indicates better performance.

Please provide an initial line containing only a single value, representing the score awarded to the assistant's response.

Following this, please provide a comprehensive explanation of your evaluation, ensuring to avoid any potential biases and ensuring that no factors other than the text influence your judgment.

Below are examples of positive or negative scoring that I have provided for your reference:

Negative Example:

Human: *{**Instruction**}*

Assistant: *{**Model response**}*

GPT-4 Response: *{**Example scoring response**}*

Where the input \n represents a line break. If you understand, please rate the response following the criteria provided above and referring to the examples given.

Please rate the response following "Assistant:" based on the given conversation context and according to the criteria provided above:

Human: *{**Instruction**}*

Assistant: *{**Model response**}*

<br>

## Logic

I want you to serve as an expert in evaluating the full-text generation capability. I will provide you with a pair of questions and answers, and you will evaluate the responses from the ***logic*** perspective according to the following scoring criteria:

A score of 10 represents thorough reasoning, rigorous logic, and strong ideation.

A score of 8 indicates relatively substantial reasoning, smooth logic, and strong ideation, with room for improvement.

A score of 6 suggests basic reasoning, relatively smooth logic, but with room for improvement.

A score of 4 indicates relatively simple reasoning, lack of depth, and logic in need of optimization.

A score of 0 represents insufficient reasoning, unclear logic, and relatively weak ideation.

<br>

You need to utilize your experience to consider how to score the response that best fits the criteria and descriptions.

We would like to ask you to provide feedback on the full-text generation capability of an AI assistant.

Please evaluate its response from the ***logic*** perspective. The scoring will range from 0 to 10, where a higher score indicates better performance.

Please provide an initial line containing only a single value, representing the score awarded to the assistant's response.

Following this, please provide a comprehensive explanation of your evaluation, ensuring to avoid any potential biases and ensuring that no factors other than the text influence your judgment.

Below are examples of positive or negative scoring that I have provided for your reference:

Negative Example:

Human: *{**Instruction**}*

Assistant: *{**Model response**}*

GPT-4 Response: *{**Example scoring response**}*

Where the input \n represents a line break. If you understand, please rate the response following the criteria provided above and referring to the examples given.

Please rate the response following "Assistant:" based on the given conversation context and according to the criteria provided above:

Human: *{**Instruction**}*

Assistant: *{**Model response**}*

<br>

## Argument

I want you to serve as an expert in evaluating the full-text generation capability. I will provide you with a pair of questions and answers, and you will evaluate the responses from the ***argumentation*** perspective according to the following scoring criteria:

A score of 10 represents clear and profound argumentation, demonstrating strong novelty and direction.

A score of 8 indicates clear argumentation with a certain level of novelty and direction, but there is room for improvement.

A score of 6 suggests basic clarity in argumentation with some degree of novelty and direction.

A score of 4 indicates relatively simple argumentation, lacking depth and novelty.

A score of 0 represents unclear argumentation, lack of clear viewpoints, and issues with directionality.

<br>

You need to utilize your experience to consider how to score the response that best fits the criteria and descriptions.

We would like to ask you to provide feedback on the full-text generation capability of an AI assistant.

Please evaluate its response from the ***argumentation*** perspective. The scoring will range from 0 to 10, where a higher score indicates better performance.

Please provide an initial line containing only a single value, representing the score awarded to the assistant's response.

Following this, please provide a comprehensive explanation of your evaluation, ensuring to avoid any potential biases and ensuring that no factors other than the text influence your judgment.

Below are examples of positive or negative scoring that I have provided for your reference:

Negative Example:

Human: *{**Instruction**}*

Assistant: *{**Model response**}*

GPT-4 Response: *{**Example scoring response**}*

Where the input \n represents a line break. If you understand, please rate the response following the criteria provided above and referring to the examples given.

Please rate the response following "Assistant:" based on the given conversation context and according to the criteria provided above:

Human: *{**Instruction**}*

Assistant: *{**Model response**}*

<br>

## Evidence

Assuming you are an article reviewer, please help me assess the sufficiency of ***evidence*** in the given article. The specific deduction rules are as follows:

​	1.Concrete data or examples: Consider whether each piece of evidence in the article contains specific data or real-life examples. Deduct 1-2 points for each instance of empty talk or general statements, depending on the specific context.

​	2.Unsupported claims: A proper article review should have well-supported arguments and a rich discourse process to substantiate each point. Consider the number of unsupported claims in the review article, deducting 1.0 point for each such claim.

​	3.Supportiveness of evidence: Consider whether the evidence in the article supports the claims. Deduct 1 point if it does not.

For example, for the following article: *{**Example article**}*
The identified problems: *{**Example scoring response**}*

Please strictly adhere to the scoring rules and deduct points according to the provided example, expressing the final score in a JSON format resolvable by Python. One field should be "identified problems," listing the issues as a list, another field should be "deduction score," and the third field should be "calculation process." Avoid providing any statements outside of the JSON format. The article is as follows: *{**Model response**}*

<br>

## Language

I want you to serve as an expert in evaluating the full-text generation capability. I will provide you with a pair of questions and answers, and you will evaluate the responses from the ***language*** perspective according to the following scoring criteria:

A score of 10 represents extremely fluent, profound, rich, and vivid language expression.

A score of 8 indicates relatively fluent language expression with good depth and richness, but there is room for improvement.

A score of 6 suggests basic fluency in language expression with some depth and richness.

A score of 4 indicates relatively simple language expression, lacking vividness.

A score of 0 represents language expression that is not fluent, lacking depth and richness.

<br>

You need to utilize your experience to consider how to score the response that best fits the criteria and descriptions.

We would like to ask you to provide feedback on the full-text generation capability of an AI assistant.

Please evaluate its response from the ***language*** perspective. The scoring will range from 0 to 10, where a higher score indicates better performance.

Please provide an initial line containing only a single value, representing the score awarded to the assistant's response.

Following this, please provide a comprehensive explanation of your evaluation, ensuring to avoid any potential biases and ensuring that no factors other than the text influence your judgment.

Below are examples of positive or negative scoring that I have provided for your reference:

Negative Example:

Human: *{**Instruction**}*

Assistant: *{**Model response**}*

GPT-4 Response: *{**Example scoring response**}*

Where the input \n represents a line break. If you understand, please rate the response following the criteria provided above and referring to the examples given.

Please rate the response following "Assistant:" based on the given conversation context and according to the criteria provided above:

Human: *{**Instruction**}*

Assistant: *{**Model response**}*