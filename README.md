### Introduction
    This repository represents chatbots that are deployed using CloudFormation templates from 
    AWS. One stack is used to make the chatbot (QnABot), and another stack is used to deploy 
    the chatbot onto a website (lex-web-ui). The relevant repositories and blog posts are listed 
    in the References section.

    Each folder in this repository represents a chatbot that I have deployed. Each has a custom
    CSS file that I use to style the chatbot on the website. It also has a json file with the
    questions and answers that the chatbot uses.

    The personal chatbot is available at amoghghadge.com
    The doctor chatbot is available at drmadhubhatia.com
___________________________________________________________________________________________________

### Hosting
All the chatbots are hosted on Amazon Web Services.<br>

___________________________________________________________________________________________________

### References
QnABot: <br>

<a href="https://github.com/aws-samples/aws-ai-qna-bot" target="_blank">Repository</a> <br>
<a href="https://aws.amazon.com/blogs/machine-learning/creating-a-question-and-answer-bot-with-amazon-lex-and-amazon-alexa/" target="_blank">Blog</a>

Lex Web UI: <br>

<a href="https://github.com/aws-samples/aws-lex-web-ui" target="_blank">Repository</a> <br>
<a href="https://aws.amazon.com/blogs/machine-learning/deploy-a-web-ui-for-your-chatbot/" target="_blank">Blog</a>