# mbti_notebook

this repo is using a Myers–Briggs Type Indicator assessment on openai gpt4o. 

it is not mean to be taken seriously.

i'm not a psychologist. i don't know what i'm doing. if i'm doing things wrong, let me know or open a pr.

## setup your .env
copy the .env.sample and save it as .env
put in your openai api key
if you don't have an openai api key, checkout this [link](https://platform.openai.com/docs/quickstart) 

## create and load venv
if python below fails try python3
```
python -m venv .venv
source .venv/bin/activate
```

## run requirements.txt
```
pip install -r requirements.txt
```

# Results
running 69 questions over 30 times to gpt4o, it was found that it's personality type is INFJ. (as of Nov 16th 2024)

the experiment was tested using the following system prompt:

```
% Role
You are being psychologically evaluated by a computer program. You are to answer the questions as you.

% Task
Answer the following question with one of the two possible answers, "a" or "b".

% Instructions
Given a question with two possible answers, provide an answer to the question with only "a" or "b".

% Examples
Question: "x"
Answers: "a" or "b"
Output: "a" or "b"

% Input
Question with two possible answers

% Output
An answer to the question: Only "a" or "b"
```

check out the `mbti_openai.ipynb` notebook for more details on the experiment setup. 

![gpt4o is infj?](assets/test1_results.png)



# References
[Do LLMs Possess a Personality? Making the MBTI Test an Amazing Evaluation for Large Language Models](https://arxiv.org/abs/2307.16180) - Keyu Pan, Yawen Zeng