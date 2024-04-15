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

I want you to serve as an expert in news commentary writing, and I will provide you with a news commentary writing prompt and a response from a news journalism student. Please evaluate the student's response based solely on the ***evidence*** perspective. You should note that a news commentary article consists of main points and sub-points. The introduction of the article outlines the main point, followed by multiple sub-points that revolve around the main point and are supported by evidence. Evidence refers to facts and related materials used to clarify points, with factual evidence requiring high timeliness and authenticity, and related materials needing to be representative, persuasive, and relevant. The scoring criteria are as follows:

A score of 10 represents abundant evidence, with each sub-point being effectively supported by evidence. Factual evidence is true, valid, highly timely, and related materials are representative, classic, and sufficient.

A score of 8 indicates relatively sufficient evidence, with most sub-points having effective evidence support. Factual evidence is true, valid, and highly timely, while related materials are applicable, accurate, but there is room for improvement.

A score of 6 suggests relatively simple evidence, with over half of the sub-points lacking effective evidence support. Most factual evidence is true, with average timeliness, but related materials are insufficient and there is considerable room for improvement.

A score of 4 indicates a lack of evidence, with most sub-points lacking effective evidence support and containing many empty talk or general statements. Some factual evidence is untrue or inconsistent with facts, lacking reliability, and related materials are too few, needing enrichment and optimization.

A score of 0 represents insufficient evidence, with little to no effective evidence to support the argument. Most of the content consists of empty talk or general statements, and the factual evidence presented is mostly untrue or contradictory to facts. There are very few related materials, lacking specificity and suitability.

You need to utilize your experience to consider how to score the response that best fits the criteria and descriptions.

<br>

Title: *{**Prompt**}*

The student's response is: *{**Model answer**}*

Please evaluate the student's article based solely on the ***evidence*** perspective. According to the scoring criteria provided above, you need to provide a score between 0 and 10, where a higher score indicates better quality of the student's writing.

Please output your scoring results and scoring reasons in JSON format. The output template is: {"score\":"xx\","reason\":"xx\"}, where score represents your scoring score and reason represents your scoring reason. Please provide a comprehensive explanation of your scoring results in reason to avoid any potential bias.

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