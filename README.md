# Dev Cards

## Problem
How can you easily spot a developers expertise? What programming languagues is she most proficient in? 

While questioning developers about how to use design patterns—and other coding practices— is a way to understand if they have used a language,
it doesn't provide the full picture. When dealing with coding expertise, its safe to say that consistency and effort makes a great part. 
The more time a developer puts on a language, the better the results. However, there is no clear way to measure that, at least not yet.

## Appetite
I want to invest two weeks to design the first draft of what I want to call the Dev Cards. I would like to make use of the concept of 
trading cards, like the ones we see in Baseball or Fifa.

## Solution
As a way to easily give it a try, I want to create Dev Cards that can describe a developers main experience on programming languages.
This profile will include picture, total score, role (Frontend, Backend, Full Stack, etc), country, company, and the six main languages
the user has been using in the past. 

An Android App will be used as the Frontend to test this idea. Kotlin being the language to be used. 

The language information will come from GitHub API, when the profile has been made public. 

## Rabbit Holes

This project has a strong dependency on a third-party API, in this case GitHub or any other code repository management system that can 
provide the users code repositories languages.

## No-Gos

This first iteration will not have a connection to a database layer. Also, the mobile app will not have any sort of authenticaion initially.
