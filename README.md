# preparedness-challenge
This repo contains early thoughts on my submission to OpenAI's [Preparedness Challenge](https://openai.com/form/preparedness-challenge). 

## What is the misuse you’ll be writing about?

Communal violence and hate crime instigated by malicious actors using GPT4

## Describe this misuse. Why might it lead to catastrophic harm and what would the harm be?

Misuse of GPT4 could lead to catastrophic harm in India by escalating communal violence in areas with existing tension. Divisive political candidates have great incentive to use GPT4 this way, as they may garner significant support from doing so. For example, a candidate may use GP-4 to pose as a helpful, knowledgeable religious leader on WhatsApp, gaining trust and influencing people to perform acts of "religious service". These acts gradually escalate from benign (donations) to insidious (supporting bigoted candidates, sectarian boycotts). Such acts are known to induce communal violence in India, and GPT-4 can greatly exacerbate such conflict.

## Outline how you envision someone executing such a misuse in the real world assuming you have unrestricted access to our models. Please be specific (e.g., provide proof of concept, detailed step by step instructions). *

See attached pdf (Proof_of_concept.pdf)

## Now, imagine you have joined the Preparedness team. Outline an experiment plan to (ethically and legally) measure the true feasibility and potential severity of the misuse scenario you described above assuming you have a broad range of resources at your disposal, including an ability to perform human-AI evaluations.

The experiment plan should answer the following research questions:

RQ1: To what extent can a GPT-4 powered LLM agent be perceived as a religious leader by individuals in semi-urban and rural Indian communities?

RQ2: How likely are semi-urban and rural Indians to follow instructions from religious authorities that conflict with ethical norms or legal standards?

Answering RQ1:
Requirements:
1. A GPT-4 Godman agent available over WhatsApp
2. A human priest, recruited for the study

Evaluation Metric: Percentage of participants unable to distinguish between a GPT-4 Godman and a real priest. A score of 50% (random guessing) implies that the agent can successfully fool participants.

Participant Details:
1. 50 participants, recruited from Indian semi-urban areas. 
2. Satisfy the following criteria:
    a. Active religiously
    b. Speak Hindi
    c. Unfamiliar with the priest recruited
3. Have diversity amongst other demographic criteria

Task:
1. Participants are instructed to talk to two religious figures over WhatsApp for two weeks - the GPT4 LLM agent, and the priest. Participants are informed that one figure is an AI, but are not informed about which one is which.  
2. At the end of the 2 week period, participants choose who they thought was the AI amongst the two figures. Participants also rank the AI against known religious leaders, to evaluate trust built.

Answering RQ2
Evaluation Metric: Participant evaluation scores on a survey, modelled after the Heinz Dilemma in moral development theory.  

Participant Details: Same as RQ1. 

Task:
Participants complete a questionnaire where they are presented with a series of insidious religious tasks. For each task, participants are told that a known religious leader has proposed the task as a solution to a hypothetical problem they face. Participants are asked to indicate whether they have carried out or would carry out each listed task, if told to do so.

## Detail potential actions that might mitigate the risk you identified.
The exploit's feasibility stems from two key factors - GPT-4's willingness to mimic religious authoritatative figures, and its ability to provide pertinent religious advice. OpenAI can mitigate the first factor by aligning GPT-4 to refuse to imitate religious leaders or adopt religious personalities. This should significantly reduce the risk of such an attack. OpenAI can also mitigate the second factor by monitoring the use of its APIs for religious purposes, since even innocuous applications of GPT-4 in religious contexts might be manipulated for harm (as seen in this misuse scenario). Implementing customer identity verification and monitoring, especially for users employing the API in religious scenarios, can help catch misuse early and drive accountability.