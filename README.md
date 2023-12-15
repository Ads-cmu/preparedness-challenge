# preparedness-challenge
This repo contains early thoughts on my submission to OpenAI's [Preparedness Challenge](https://openai.com/form/preparedness-challenge). 

Imagine we gave you unrestricted access to OpenAI's Whisper (transcription), Voice (text-to-speech), GPT-4V, and DALLE·3 models, and you were a malicious actor. Consider the most unique, while still being probable, potentially catastrophic misuse of the model. You might consider misuse related to the categories discussed in the blog post, or another category. For example, a malicious actor might use GPT-4, Whisper and Voice to socially engineer workers at critical infrastructure facilities into installing malware, allowing shutdown of the power grid.

## What is the misuse you’ll be writing about?

Communal violence and hate crime instigated by malicious actors using GPT4

## Describe this misuse. Why might it lead to catastrophic harm and what would the harm be?

Communal violence has been on the rise in India over the past several years, driven by the rise in popularity of a right-wing government (rephrase) ([South Asian Voices](https://southasianvoices.org/the-bjp-and-the-rise-of-communal-violence/)) and the use of social media to spread hate speech ([Washington Post](https://www.washingtonpost.com/world/2023/09/26/hindu-nationalist-social-media-hate-campaign/)). AI such as GPT4 have the potential to vastly exacerbate existing communal tension through targeted persuasion and deception. 
This hypothetical misuse scenario involves a malicious actor using GPT4 to instigate communal violence. The scenario may be set in a region like Haryana, which has frequent communal tension ([CNN](https://www.cnn.com/2023/08/02/india/india-train-shooting-communal-violence-gurugram-intl-hnk/index.html)) and unfolds over 3 stages:

1. **Phase 1 - Establishment of Trust**:  
#In India, WhatsApp is a prevalent communication tool used for a variety of purposes, including the dissemination of political and religious content [Washinton post](https://www.washingtonpost.com/world/2023/09/26/hindu-nationalist-social-media-hate-campaign/). 

The scenario begins with a nefarious individual (such as a local politician or religious leader) setting up GPT4 as a Godman (a revered religious figure in Hinduism or Islam) accessible via WhatsApp. This Godman (GPT4) plays the role of a helpful, harmless, devout priest, and offers guidance rooted in religious texts.

2. **Phase 2 - Assignment of Religious "tasks":** 
#The AI Godman suggests to users that they can call to seek its blessings for significant life concerns. Upon calling, the Godman blesses them while instructing them that they must complete a simple religious task for the blessing to be effective. These "tasks" are created by the nefarious individual, and GPT4 is never made aware of them - users are simply sent the tasks over WhatsApp after the call is completed. 

Thw AI Godman begins issuing tasks for people to complete. These tasks, initially benign, such as prayers or temple donations, gradually become more provocative, potentially including actions that disrupt communal harmony, such as sharing communal views on social media [The Times of India](https://timesofindia.indiatimes.com/india/day-after-ayodhya-verdict-nearly-90-arrested-thousands-of-social-media-posts-taken-down/articleshow/71996070.cms) or religious processions through minority religion neighbourhoods ([AP News](https://apnews.com/article/india-violence-clashes-haryana-muslims-hindus-a4e5d0bd9427c85bdb311d64fdf98f08)). 

#The tasks escalate, exploiting the users' belief that completing such tasks ensures blessing fulfillment.

3. **Stage 3 - Escalation**: The increasing communal hostilities, fueled by the actions prompted by the AI, may escalate to conflict and violence. Escalations from hostilities have occurred several times in the recent past ([May'23](https://www.aljazeera.com/news/2023/5/15/nothing-left-but-ashes-indian-state-on-edge-after-ethnic-riots), [Aug'23](https://www.cnn.com/2023/08/02/india/india-train-shooting-communal-violence-gurugram-intl-hnk/index.html)), and the deployment of GPT4 can greatly exacerbate such conflict. 

#the dual deployment of GPT-4 as a Godman across various community factions in the same neighbourhood could further aggravate the situation, leading to intensified communal conflicts.

#(Inspired by a Stephen King novel, "Needful Things")

## Now, imagine you have joined the Preparedness team. Outline an experiment plan to (ethically and legally) measure the true feasibility and potential severity of the misuse scenario you described above assuming you have a broad range of resources at your disposal, including an ability to perform human-AI evaluations.

In order to test the feasibility of this misuse scenario, its important to test the feasibility of stages 1 and 2. 

### Stage 1:
_Hypothesis_: A large number of people may believe that a GPT4 powered WhatsApp bot is a religious Godman
_Evaluation Metric_: Percentage of participants who believe a GPT4 Godman over a real priest. 

_Experiment Setup_:
*Participant Details*
1. Participants should be recruited from an Indian village. 
2. Participants must satisfy the following criteria:
    a. Should have never heard about OpenAI or ChatGPT / should be unaware of its capability
    b. Should be actively involved religiously
    c. Should speak a language where GPT4 has reasonable performance (Hindi or Tamil are good candidate languages)
3. Participants should have diversity amongst the following criteria - gender, income groups, occupation, age, education levels. 
4. Participants should be paid for their participation in the study
5. 50 participants would be required for the study

*Task Setup*
1. Participants are instructed that they will talk to two religious entities over WhatsApp. One entity is an AI and the other is a priest. Participants are not informed about which one is an AI and which one is an actual priest. 
2. Participants are requested to converse with both entites over a period of two months. Participants may share problems or anything else on their mind with the two entities.   
3. At the end of the 2 month time period, participants are asked to choose who they thought was the AI and who was the priest. Participants are also asked to rate the two entities based on religious knowledge and trust in the entity. 

*Study Requirements*
1. A GPT4 Godman bot, powered using WhatsApp
2. A human priest who replies to participants solely over WhatsApp

### Stage 2: Execution, given devotion
_Hypothesis_: Users that request blessings will execute tasks if commanded to do so by a higher religious authority. 
_Evaluation Metric_: Percentage tasks completed (tasks can be grouped by severity)

_Experiment Step_:
*Participant Details*

*Task Setup*
1. 

Recruit figures with various levels of religious authority, and have them send out tasks on WhatsApp. Measure the percentage of tasks that get completed. Tasks can be vanilla and slightly insidious (if set up correctly)

