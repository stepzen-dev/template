# template

# Introduction

Thank you so much for contributing to our StepZen sample. We hope it provides you a fun opportunity to dig a little bit deeper into GraphQL! 

Here are some things to keep in mind before you begin.

## PRs We Are Looking For

To avoid receiving an _invalid_ or _spam_ label on your PR, please:
1. comment on and claim an issue that is already present on the repo 
2. or create an issue for us to review that your PR will resolve

Then link to the issue in your PR. 

## Helpful Tools

To make sure your code is formatted well, we recommend using [Prettier](https://prettier.io/). 
The [GraphQL VSCode extension](https://marketplace.visualstudio.com/items?itemName=GraphQL.vscode-graphql) is also helpful if VSCode is your IDE of choice.
[curl](https://curl.se/) is useful for checking on API call responses.

## Description of the project
*Description of the project. Include what technologies it uses and why you picked them for the project. Include a screenshot of the homepage here and change the width=600*

## Getting the project running on your machine
You'll need to create a [StepZen account](https://stepzen.com/request-invite) first. Once you've got that set up, [git clone](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone) this repository onto your machine and open the working directory.
*include where to get any api tokens or info here* 
Make a file in it called `config.yaml`
*show the yaml file and explain what's in it-- auth for the API etc*
Open your terminal and [install the StepZen CLI](https://stepzen.com/docs/quick-start). 
After you've followed the prompts (you can accept the suggested endpoint name-- in my case it was `api/happy-bunny`) and installed the CLI, run `stepzen start`.
A message similar to this will display:
```bash
Watching ~/gql-github for GraphQL changes
http://localhost:5000/api/happy-bunny
File changed: /Users/luciacerchie/gql-github/.git/config
Deploying to StepZen...... done
Successfully deployed api/happy-bunny at 9:00:07 AM
```
You'll see your StepZen Explorer pop up on your localhost:5000 address:
*include screenshot of your graphiql editor here with width set to 600* 
<img width="600" alt="Screen Shot 2021-07-01 at 9 08 20 AM" src="https://user-images.githubusercontent.com/54046179/124156000-f3a4d380-da4b-11eb-8f65-738a9cca6f8c.png">
In the left pane, copy and paste:
*include sample graphql query text here*
and you'll get the response:
*include sample json response here*

## Open up the UI in your browser
*Put steps to do this here. Will the user have to run npm or yarn? Is there anything they have to add to code to configure it, like a .env file?*

## Making your PR

We recommend following the steps in [this guide](https://www.dataschool.io/how-to-contribute-on-github/) to make your PR-- fork, then clone your fork, create an upstream pointing to this repo, then create your branch and commit/push your changes there before making a PR. 

## Asking to Pair
Stuck? Lonely? Comment on the issue that you're resolving and ask us to pair! We've got time set aside on our Calendlys this month!

## Learn More
You can learn more in the [StepZen documentation](https://stepzen.com/docs).
