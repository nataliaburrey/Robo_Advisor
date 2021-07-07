# Robo Advisor

📌 Challenge 14

<img width="723" alt="Screen Shot 2021-07-06 at 5 25 47 PM" src="https://user-images.githubusercontent.com/80833988/124682261-36691000-de7f-11eb-8055-1892958230e6.png">



> "In this Challenge, I combine my new AWS skills with existing Python superpowers to create a bot that will recommend an investment portfolio for a retirement plan
"








## Table of content
- [Overview of the project and project goals](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#overview-of-the-project-and-project-goals) 
- [Software version control](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#software-version-control)
    - [Libraries](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#libraries)
    - [Work with GitHub](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#work-with-github)
    - [How to install](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#how-to-install)
- [Project findings](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#project-findings)
- [Helps recruiters](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#helps-recruiters)
- [License](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#license)



## Overview of the project and project goals

Using the power of machine learning and NLP to disrupt finance and improve the customer experience, we are creating a robo advisor. Both existing and potentially new customers will be able to use this robo advisor to get investment portfolio recommendations for retirement.

Following main tasks were accomplished:

  1. Configure the initial robo advisor: Define an Amazon Lex bot with a single intent that establishes a conversation about requirements to suggest an investment portfolio for retirement.

  2. Build and test the robo advisor: Make sure that your bot works and accurately responds during the conversation with the user.

  3. Enhance the robo advisor with an Amazon Lambda function: Create an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This includes testing the Amazon Lambda function and integrating it with the bot.



 



## Software version control

Amazon Lex is used to create the bot

### Step 1: Initiate the bot

<img width="742" alt="Screen Shot 2021-07-05 at 12 25 15 PM" src="https://user-images.githubusercontent.com/80833988/124686468-0e31df00-de88-11eb-86b6-8694b0b56d53.png">

### Step 2: Create the intent

<img width="844" alt="Screen Shot 2021-07-05 at 12 36 39 PM" src="https://user-images.githubusercontent.com/80833988/124686569-391c3300-de88-11eb-8b29-2896ae16589b.png">

### Step 3: Create Lambda

Amazon Lambda is used to enhance original bot

<img width="864" alt="Screen Shot 2021-07-06 at 6 32 21 PM" src="https://user-images.githubusercontent.com/80833988/124686760-83051900-de88-11eb-98c2-3b314725d635.png">

### Step 4: Deploy Lambda

<img width="691" alt="Screen Shot 2021-07-06 at 6 31 25 PM" src="https://user-images.githubusercontent.com/80833988/124686672-623cc380-de88-11eb-905f-3616e0e6a1fc.png">

### Libraries 

* Following libraries were imported

```
# Import the required libraries and dependencies

from datetime import datetime
from dateutil.relativedelta import relativedelta
```


 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* File with code for Lambda function included lambda_function.py


### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/Robo_Advisor.git
```

now you can find repo on your desktop


* Choose [ lambda_function.py ] file to see the code for Enhanced Robo Advisor.


## Working Bot Demonstration

### Initial robo advisor

>" Define an Amazon Lex bot with a single intent that establishes a conversation about requirements to suggest an investment portfolio for retirement.
"



https://user-images.githubusercontent.com/80833988/124681906-6bc12e00-de7e-11eb-98b9-d48959155925.mov



### Enhanced Robo Advisor 

>"  Create an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This includes testing the Amazon Lambda function and integrating it with the bot.
"


https://user-images.githubusercontent.com/80833988/124681923-77acf000-de7e-11eb-8e8a-9eaf4253ffd6.mov






## Helps recruiters

The project was created in collaboration with Berkeley Fintech Bootcamp team


## License

MIT


📔 Contact me: 
📩 nataliaburrey@gmail.com
