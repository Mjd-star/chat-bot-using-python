# chat-bot-using-python

## Steps
### 1. Installation
The full code is on the GitHub repository, but I’m going to walk through the details of the code for the sake of transparency and better understanding.
 Now let’s begin by importing the necessary libraries. (When you run the python files on your terminal, be sure to make sure they are installed properly. I use pip3 to install the packages.)

### 2. processing data

    # Counts how many words are present in each predefined message
    for word in user_message:
        if word in recognised_words:
            message_certainty += 1

    # Calculates the percent of recognised words in a user message
    percentage = float(message_certainty) / float(len(recognised_words))

    # Checks that the required words are in the string
    for word in required_words:
        if word not in user_message:
            has_required_words = False
            break

### 3. Finally it’s time to run our chatbot!

![image](https://user-images.githubusercontent.com/85651071/125214335-4a69a300-e2bf-11eb-8b2a-f2e8f6c3af6c.png)




