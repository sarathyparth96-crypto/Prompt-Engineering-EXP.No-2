# Ex - 2 Evaluation of Prompting Techniques Across AI Platforms for Text Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

_______________________________________________________________________________________________________________________________________________________________________________________________

# Prompting Techniques

## 1. Zero-Shot Prompting
In zero-shot prompting, the AI model is given a task directly without examples. The model relies entirely on its prior training knowledge to generate the summary.


### Zero-Shot Prompting Comparison

| Platform | Accuracy | Coherence | Simplicity | Speed | User Experience | Observation |
|----------|----------|-----------|------------|-------|-----------------|-------------|
| ChatGPT  | High     | High      | High       | Medium| Excellent       | Produces clear summaries with good structure |
| Gemini   | Medium-High | High   | High       | Very Fast | Very Good  | Very quick responses but may shorten details |
| Claude   | High     | Very High | High       | Medium | Very Good     | Produces natural and readable summaries |

## 2. Few-Shot Prompting

Few-shot prompting provides a small number of examples before asking the AI to perform the task. These examples guide the model toward the expected output style.

### Few-Shot Prompting Comparison

| Platform | Accuracy | Coherence | Simplicity | Speed | User Experience | Observation |
|----------|----------|-----------|------------|-------|-----------------|-------------|
| ChatGPT  | Very High | Very High | High | Medium | Excellent | Learns patterns from examples effectively |
| Gemini   | High | High | High | Fast | Very Good | Works well with examples |
| Claude   | High | Very High | High | Medium | Very Good | Clear and natural summaries |


## 3. Chain-of-Thought Prompting

This method encourages the AI to reason step-by-step before producing the final answer. It is useful for complex reasoning tasks and structured summarization.

### Role-Based Prompting Comparison

| Platform | Accuracy | Coherence | Simplicity | Speed | User Experience | Observation |
|----------|----------|-----------|------------|-------|-----------------|-------------|
| ChatGPT  | Very High | Very High | High | Medium | Excellent | Structured and professional summaries |
| Gemini   | High | High | High | Very Fast | Very Good | Simple summaries quickly |
| Claude   | High | Very High | High | Medium | Excellent | Very natural and human-like summaries |

## ChatGPT

ChatGPT performs very effectively with chain-of-thought prompting. It follows the reasoning steps carefully, identifies key information, and generates well-structured summaries. The summaries are typically accurate and logically organized.

**Strengths:**

Strong reasoning ability

Clear step-by-step processing

High summary accuracy

**Limitation:**

Slightly slower compared to Gemini when prompts are long.

## Gemini

Gemini responds quickly to chain-of-thought prompts and produces summaries efficiently. However, it may compress reasoning steps internally, resulting in slightly shorter explanations.

**Strengths:**

Very fast response time

Clear summaries

Good readability

**Limitation:**

Sometimes reduces the detailed reasoning process.

## Claude

Claude performs well with chain-of-thought prompting because it focuses on natural language understanding and coherent responses. Its summaries tend to be very smooth and easy to read.

**Strengths:**

Very coherent writing

Good logical structure

Balanced reasoning

**Limitation:**

Slightly slower than Gemini.

Comparison of Platforms
Platform	Accuracy	Coherence	Simplicity	Speed	User Experience	Observation
ChatGPT	High	High	High	Medium	Excellent	Produces clear summaries with good structure
Gemini	Medium–High	High	High	Very Fast	Very Good	Very quick responses but may shorten important details
Claude	High	Very High	High	Medium	Very Good	Produces very natural and readable summaries


# Comparative Analysis
Based on experimentation with different prompting techniques across multiple AI platforms, the following general observations were made:
• ChatGPT performs very well with Chain-of-Thought and Role-based prompting, producing highly coherent and accurate summaries.
• Gemini performs strongly with Zero-shot and Few-shot prompts and produces clear summaries quickly.
• Claude is known for generating very natural and coherent summaries, especially when using Role-based prompts.
• Copilot works efficiently for shorter summaries and performs best with structured prompts such as Few-shot examples.

#  Evaluation Metrics
## .1 Accuracy

Accuracy measures how well the summary represents the original text without losing important information.

Factors affecting accuracy:

## Quality of prompt :

AI model capability

Length of source text

## 5.2 Coherence

Coherence refers to the logical flow of ideas in the summary. A coherent summary connects sentences smoothly and maintains a clear structure.

## 5.3 Simplicity

Simplicity measures how easy the summary is to understand. A good summary should avoid unnecessary complexity and present ideas clearly.

## 5.4 Speed

Speed refers to how quickly the AI platform generates the summary after receiving the prompt.

### Factors influencing speed:

Model size

Prompt length

System performance

##  5.5 User Experience

User experience includes:

Interface usability

Response clarity

Ease of prompt interaction

Good user experience improves productivity when using AI tools.

# Result

From the evaluation, it was observed that:

Chain-of-thought prompting with ChatGPT produced the most accurate summaries.

Role-based prompting with Claude generated very natural and coherent summaries.

Few-shot prompting with Gemini delivered fast and simple summaries.

Copilot performed best for short and structured summaries.

Overall, ChatGPT with chain-of-thought prompting provided the best balance of accuracy, coherence, and quality.
