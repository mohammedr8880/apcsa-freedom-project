# Entry 3
##### 3/09/23

Alright, so for Blog 3, I will be talking about how I have been learning my tool and what I plan on learning next about my tool.

So I have been learning my tool by looking through documentation like [datacamp](https://www.datacamp.com/tutorial/case-conversion-python) in order to find methods that I would need to use in order to get what I want the bot to do. So I wanted my bot to count text that only has capital letter differences to get the same responses. For example, if I ask my bot “How are you doing”, I would expect the bot to reply with the same answer when I ask “HOW ARE you DOING”. So I would want the bot to read all the replies in lowercase. 

Looking through [datacamp](https://www.datacamp.com/tutorial/case-conversion-python) I found out that java and python have a similar way of using the lowercase method. 

Java - `.toLowerCase();`
Python - `.lower();`

Before I implement the lowercase method, I need to get the bot to scan the messages, so I have to use `def get_response(message: str) -> str:`.

After that, I wrote `p_message = message.lower()`. `p_message` is the message the bot is seeing after `message.lower()` turns my reply into all lowercase.

So I continue and write my responses:

`if p_message == 'who are you':
	return 'I am a bot named CactusJack, created by Mo'`

 `if p_message == ‘yo’:
	Return ‘Yo!’`

I was looking through [w3schools](https://www.w3schools.com/python/python_conditions.asp) and found out that python uses the same if statement format as java but without the curly brackets. And the code basically looks for “yo” or “who are you” and returns the responses. It doesn’t matter if you have any capital letters; it will still give you the same response.

What I plan to learn with my tool next is making my bot take I said, and it keeps my message and spits it out whenever I tell it to stop copying me.

For the engineering design process, I am on stage 2 because I am still researching how to write the code in python like how to use booleans and how to make my bot copy my text. And for the next stage in the engineering design process, I will brainstorm ideas about how I can make the bot copy the text without copying every single text I send.

Alright, to end this blog, I will be talking about the  [Skills](https://hstatsep.github.io/students/#skills) I had to use. I had to use, “how to read” because w3schools and data camp had me reading the code on how to make something lowercase and use if statements. Another skill that I used was attention to detail because I was carefully examining the if statements because I am so used to writing curly brackets which would mess up my code in python.


[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
