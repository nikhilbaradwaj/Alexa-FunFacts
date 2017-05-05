# Alexa - Fun Facts

This is a repo to try out the Alexa API. This project let's you ask alexa to say some fun facts for you using the command
"Alexa Ask Fun Fact" {command}

The command can be one of the following - 

1. give me a fun fact
2. fun fact of the day please
3. blow my mind with a fun fact

You will expect Alexa to repond with one of the following fun facts - 

```
During your lifetime, you will produce enough saliva to fill two swimming pools.
An adult human being is made up of around 7,000,000,000,000,000,000,000,000,000 atoms.
An eagle can kill a young deer and fly away with it.
in 2015, more people were killed from injuries caused by taking a selfie than by shark attacks.
When hippos are upset, their sweat turns red.
Bananas are curved because they grow towards the sun.
Heart attacks are more likely to happen on a Monday.
The average woman uses her height in lipstick every 5 years.
```

## Setup

1. Zip all the files other than the folder "speech_assets"
2. Sign into your AWS account and create a Lambda function by choosing the 'Alexa skills kit'
3. Upload the zip file created in step 1 as the code for the lambda function
4. Create an IAM role for the lambda function. Take a note of the ARN of the lambda function created.
5. Sign into https://developer.amazon.com/ and select the 'Alexa' tab to create a new Alexa skill set.
6. Add a name and Invocation name for your skill set. Example - 'Fun Fact'
7. Copy the sample utterances from the 'utterances.txt' file.
8. Copy the intent schema from 'intent_schema.json' file.
9. Add the lamda function ARN of the lambda function you created at step 2-4.
10. Now you can test the skill set. You can also go to https://echosim.io/ and test the Alexa skill set by saying the following - "Alexa Ask Fun Fact blow my mind with a fun fact". It should give you an answer from one of the facts in facts.txt.
11. Fin

## Reference 

https://github.com/ktseytlin/WIT-AlexaClass
https://docs.google.com/presentation/d/1qt73vqX6rYBwQeGvyTccjjIJ47GK5NsqFM9S0N-OGfU/edit#slide=id.g1d4fb8249d_0_0

