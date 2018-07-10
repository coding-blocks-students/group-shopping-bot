# Group Shopping Bot


#### The Group Shopping Bot is an AI based conversational dialog engine build in Python which makes it possible to generate responses based on collections of known conversations. Generally it will deal with the inputs regarding consumers looking for any kind of products to shop online from various E-commerce websites. What makes it more feasable is that this bot can be added with a group of people who can specify their requirements and the bot will provide them links for the best deals avaliable.


### *An example of basic converastion*:
> **gpMember1:** Hey there...
> **bot:** hello..! What can i do for you..?   
> **gpMember1:** I am looking for some sneakers   
> **gpMember2:** and that to be in blue or black colors  
> **bot:** ...displays the links...


## How it works

An untrained instance of Bot starts off with no knowledge of how to communicate. Each time a user enters a statement, the library saves the text that they entered and the text that the statement was in response to. As Bot receives more input the number of responses that it can reply and the accuracy of each response in relation to the input statement increase. The program selects the closest matching response by searching for the closest matching known statement that matches the input, it then returns the most likely response to that statement based on how frequently each response is issued by the people the bot communicates with.