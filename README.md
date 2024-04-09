# sms_spam_detector
This repository contains an exercise using gradio to allow users to test text messages for spam.
# Code Source
Starter code for this exercise was provided by the instructor. I used Copilot to resolve an error with the defined function not running properly before initializing gradio.
# Conclusions
The model's training appears to have idenfified words requesting a recipient to reply to the message i.e., "text" as spam. While this is on the right track, it did not seem to associate words like "winner, lucky, or won" with spam. I think the model could be improved greatly by tuning the training to recognize those words when combined with suspicious punctuation such as "$" or "!". 