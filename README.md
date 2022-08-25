This is a project that aims to train an ML algorithm to converse as a Seinfeld character. Starting code was borrowed from https://towardsdatascience.com/make-your-own-rick-sanchez-bot-with-transformers-and-dialogpt-fine-tuning-f85e6d1f4e30. 
The first model released here was trained on George, and can be found [here](output/GPTGeorge_DiabloMedium/GPTGeorge_DiabloMedium.pdf)

After training, I conversed with GPTGeorge in 5 lines using a few different parameter options. Since the model was originally trained on Reddit data, there were some odd responses sometimes (such as remindme! or a string of exclamation marks and commas). There were a couple of decent ones, shown in the pdf and here is one example:  
>> User:What is your name?  
SeinBot: ..Alaines Costanza.  
>> User:What do you do for a living?  
SeinBot: I'm an architect.  
>> User:What buildings have you designed?  
SeinBot: Uh, the library, uh.  
>> User:Oh wow, that's so cool. Which library was it?  
SeinBot: !!! remindme 3 days. 
>> User:Tell me a joke. 
SeinBot: ! remind me 3 days!  

At least we know that GPTGeorge loves to tell people he's an architect as much as the real George Costanza. We also know that the GPTGeorge still appreciates his internet days.
