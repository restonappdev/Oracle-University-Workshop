# Lab 100: Getting Started with DA One Skill
## Introduction
This lab walks you through the steps to explore ODA Skill UI, import a skill called University Workshop Bot, and lastly interact with the skill. This skill is for our fictional generic university. It will be used for customers to ask worker questions (via automated FAQ) and update basic information, through this user-friendly and interactive skill, finally they can get proper answers and update.

## Objectives
- Understand ODA Skill UI
- Import the skeleton of university workshop bot from workshop artifacts
- Interact with the skill

## Required Artifacts
- The following lab requires an Oracle Public Cloud account. You may use your own cloud account, a cloud account that you obtained through a trial, or a training account whose details were given to you by an Oracle instructor.

---
### Step 0: Clone Artifacts
- Clone artifacts required for this lab to a local directory. We will be using them throughout all labs.   
  `git clone https://github.com/restonappdev/Oracle-University-Workshop-Artifacts`

### Step 1: Sign In to Oracle Cloud
-   a). Go to <a target="_blank" href="https://myservices.us.oraclecloud.com/mycloud/signup?language=en&sourceType=:se:eo:ie:2t:RC_NAMK180429P00004:OCSH_Reston&evite=:se:eo:ie:2t:RC_NAMK180429P00004:OCSH_Reston">free trial registration page</a>, sign up a free trial account;
    (Note: When you are doing the sign up, for adding credit card section, please make sure address is same to your billing address.)

-   b). Then go to <a target="_blank" href="https://cloud.oracle.com/getting-started">cloud.oracle.com</a>, click **Sign In** to sign in with your free Oracle Cloud account.

![](./images/100/2.png)

-   Enter your **Cloud Account Name** and click **My Services**.

![](./images/100/3.png)

-   Enter your Cloud **username** and **password**, and click **Sign In**.

![](./images/100/4.png)

### Step 2: Access Autonomous Mobile Cloud Enterprise

- Now, you are in the Oracle Cloud dashboard. Click on the hamburger menu button on the upper left of the screen and expand **Services**.
- Note: 
	- At first time, if you cannot find this cloud service, click 'Compute Classic', then you will find it.
    - Make sure your 'Identity Domain' which is on the right-top side is correct.

![](./images/100/15.png)

- Scroll down and find **Autonomous Mobile Cloud Enterprise** and Provision one instance.

![](./images/100/14.png)

- Provisioning an AMCE instance

:: Click **Create Instance** 
![](./images/100/14_1.png)

:: Fill fields' data, then Click **Next** 
![](./images/100/14_2.png)

:: Click **Confirm**, after you review the information
![](./images/100/14_3.png)

- Once your instance is ready, click on the hamburger button next to the instance and then click on **Go to Instance Home**. 

![](./images/100/16.png)

- Now, you should be in AMCe's dashboard page. Click on the hamburger menu icon on the upper left of the screen, and then expand **Development** dropdown

![](./images/100/6.png)

- As you can see, there are a lot of features included with AMCe. Today, we will just focus on Bots, Backends & APIs. Click on **Bots** to navigate to the Intelligent Bot UI.

![](./images/100/7.png)

- If you see a tour page, go ahead and click on **Got It!** since we are going to take you through a personal tour.

![](./images/100/8.png)

### Step 3: Import University Workshop Bot

- Now, you are in the bot dashboard. Close the side bar menu by clicking on the hamburger menu icon on the upper left of the screen again. 

![](./images/100/9.png)

- Here we have the dashboard for all of your chatbots. We are going to import a basic gen univeristy chatbot. We will improve this chatbot's workflow in later labs. Click on **Import Bot** on the top right of the screen and select the **UniversityWorkshopBot.zip** from the files you cloned from git. 

![](./images/100/10.png)

- This will import a bot called "UniversityWorkshop". Go ahead and click on it to see the details.

![](./images/100/11.png)

- On this page is where you will develop the rest workflow with the integration of backend & API services (e.g. HCM backend service), configuration of Q&A, and channels for the bot. We will dive into each section on the next lab. 

![](./images/100/11.png)

- In order to test the functionality and the flow of the current bot: 
   - You should train the bot firstly. 
   - Clicking on the Play button on the top right of the screen which will open up a testing place to test the functionality of your chatbot before you fully commit to it. 
   - Go ahead and chat with the bot. You can say "hello". 

**:: Before Training:**
![](./images/100/12_1_before.png)

**:: After Training:**
![](./images/100/12_1_after.png)

**:: Testing Bot:**
![](./images/100/12.png)

- As you can see, it will reply with welcome message and service you might like to chose. Select one service you would like to use. Student service will allow you to get or update students basic information (such as: phone, email, address etc.); Visitor service will provide you FAQ answers on the basic of your asked questions.

- Now, you have familiarized with the dashboard, imported a chatbot, and interacted with a chatbot. The bot is interactive but we would like to add more functionalities to it. Let's do that in the next lab!

**[Navigate to Lab 200](Lab200.md)**