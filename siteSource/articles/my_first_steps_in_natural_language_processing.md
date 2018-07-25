# My first steps in natural language processing: converting a sentence to a conceptual graph

## Abstract
The article describes my small experiment: extracting information as a conceptual graph from a phrase in natural language. 

This will allow me to manage the game character by voice or text messages. 

The obtained results are a good basis for me for achieving some practical results in the future. 
But they are not yet suitable for practical using right now.

## Background
During the increased interest to AI in the society, I also wanted to try to do something in this direction. 
Using it in games seemed as evident to me. 
I have gotten an idea: to make a simple scene in Unity 3d by standard assets and try to write a simple AI for the scene. 
The examples of game logic (which i saw) were pretty much spaghetti code in C#. 
These rules in that code was a very simple and far from intelligence. 

On the one hand, it is understandable: players want a lot of stupid "meat" for destroying it. 
And in this case a game does not require an expensive and high-performance device.

At the same time, it disappointed me: where are the achievements in the area of AI. 
In addition, in real games, the dullness of the characters is compensated by an excellent art. 
I am only able to program. 
And I do not have many opportunities for getting a such art. 
I have an interest in voice control of the character. 
Also it seemed to me as interesting to use documents in the natural language at economic and political simulators.

I quickly made a choice for a symbolic approach and for a system which is based on explicit rules. 
It allows to clearly define a behavior of a character and to explain why this or that action was performed.

The feature that seemed me as very difficult and as very interesting: to convert a text in natural language to a machine-readable format. 
It is still difficult for me, because. But now I have an expandable basis.

I was looking for a ready solution, because writing such solution is complex and also it takes a lot of time.
I did not find a solution which suited for me. 
But controlling by natural language is a cool feature. 
I also have bought a book which briefly describes main stages of natural language processing. 
So I decided to try to convert at least one phrase by myself. 
My way for it and the result are described here.

## Formulation of my task
I want to convert the sentence "I know the dog" to a conceptual graph. 
This task seems to me as small and it may be solved in a short time. 
This is only one phrase which contains only four words.

## Making a phrase tree of target sentence
Firstly, I must make a phrase tree of target sentence. 
The sentence "I know the dog" should be transformed to a tree as in figure 1.

![Figure 1. Phrase tree for sentence &quot;I know the dog&quot;](https://metatypeman.github.io/articles/37814308_2068182069919818_6317889088460423168_n.jpg "Figure 1. Phrase tree for sentence &quot;I know the dog&quot;")