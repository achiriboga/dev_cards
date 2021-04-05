# Dev Cards

## Problem
How can you easily spot a developers expertise? What programming languagues is someone most proficient in? How is the most suited person based on our development needs?

Questioning developers about how to use design patterns and other coding practices—via examples- is a way to understand if they have used a language, but it doesn't provide the full picture. When dealing with coding expertise, its safe to say that consistency and effort in coding with a particular language or framwork makes a huge different. 

The more practice a developer puts on a language, the better the results. However, there is no clear way to measure that, at least not yet.

## Appetite
I want to invest two weeks to design the first draft of what I want to call the Dev Cards. I would like to make use of the concept of 
trading cards, like the ones we see in Baseball or Fifa.

## Solution
As a way to easily give it a try, I want to create Dev Cards that can describe a developers main experience on programming languages.
This profile will include picture, total score, role (Frontend, Backend, Full Stack, etc), country, company, and the six main languages
the user has been using in the past. 

![Dev_card_example](https://github.com/achiriboga/dev_cards/blob/master/app/src/main/res/drawable/example.png height="500)

An Android App will be used as the Frontend to test this idea. Kotlin being the language to be used for development so the app will be aviable for Android. 

The developers languagues' information will come from GitHub API, when the profile has been made public. 

## Rabbit Holes

This project has a strong dependency on a third-party APIs, in this case GitHub or any other code repository management system that can 
provide the users code repositories languages.

## No-Gos

This first iteration will not have a connection to a database layer. Also, the mobile app will not have any sort of authenticaion to begin with. All data used will be data provided by the developer in his profile, like picture and name, and the data provided by GitHub publicly.
