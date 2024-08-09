# DialogueSystemFinal

Ok so the plan is for me to summarize how the system works, then I will link a doc below which will have screenshots and the details of the system. I wish I could just send the code but it is in C# and moreover, is in unity so even if you have the code, you would need to install unity and download my unity project which is quite a few extera steps that I am cutting as you will get the basic idea.

I am in the lengthy process of designing a game right now and my dialogue system needed to be completed and so did my final for this class. So they both got done. 

The way it works is there is a superclass called "CharacterLogic" which each character is derived from. This class contains the "GetDialogue" function and its helper functions. This functions takes in three booleans to check for special dialogue conditions, then based on the booleans, will output a line of dialogue from the character's "dialogue library" (which is a dictionary). 

I will try to make the code as clear as possible as some aspects of it relate to other parts of the game and not only the dialogye system.

The doc:
https://docs.google.com/document/d/1Wn2szNNltvV-4Sf_sIJi2Ux2rTvgvrz-ZDEL0do8nz0/edit?usp=sharing

If the doc link is invalid, please email coba8730@colorado.edu or cooper.baugh@gmail.com so I can resend it or just email a pdf.
