# Overview
Being on the job market I've sent in a lot of job applications and had numerous calls with recruiting agencies and company recruiters. One thing I've noticed is that it can be difficult to provide context on both sides of the conversation. For the recruiter, typically not in a technical role, it can be difficult convey the technical aspects of the role during the initial recruiter screen to assess fit and gauge applicant interest. Likewise, when an applicant submits a resume even if they tailor it to what the job description says it's hard to give more context as to what they worked on and how it can benefit this new team. 

# My Solution
The proof of concept solution is the feed an LLM all of the information on a company's website. To address the recruiter's side I would build out functionality to feed in a job description. The output would be a more detailed explanation on what the role is looking for relative to the context of the team and the broader company and provide more context on what the specific technologies being used are regardless of familiarity with the keywords. This can potentially be leveraged to created more tailored interview questions as well. On the applicant side, I would create an estimated translation layer that tries to put each line on a resume into the context of the hiring position and what value add may exist.

The end goal would be for this to be an internal company tool with a model trained on all of the company's documents (or those that are allowed to be fed in). However I dont have access to that so using the website to vet out the concept. 

# Key Features
- Web scraping to pull down information from each page in the website
- Text cleaning
- RAG Pipeline -> based on query, retrieve relevant company documents (prevents hallucination), provide context-driven answer based on those documents alone


# How does recruiting work today?






# Project Results






# Learning
