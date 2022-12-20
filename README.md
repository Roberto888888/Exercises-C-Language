# Exercises-C-Language

Very old exercises I had to come up with for an exam during my bachelor degree. It's mostly about working with text files.

Nothing super advanced and given the long time, the quality of the code is not the best.

For that exam I was required to compile from command prompt using gcc and then run the programs from the command promp. I'm not going to go into the details of how to install gcc, set it up, and how to compile code. The good thing is that the number of files is very minimal.

I've also included the executables and some sample input files to test these programs directly together with some results.

## Possible improvements:
Upon reading at the code again when I was translating the comments in English I noticed that the following things should be improved:
- Control that files are correctly open. I didn't bother doing it back then because the complexity wasn't too high.
- It'd be nice if memory was allocated dynamically to get what is needed at runtime rather than allocating a fixed abundant memory (through MAX) and work within it.
- It'd be nice to have more consistend text processing. Back then, some times I treated some characters in a way, some other times I didn't. Also, I haven't played too much with the code so some processing might not be too robust or general.
- Alternatives to scanf and fscanf can be used because those functions can create bugs.
- Improve search algorithms. In one case I used a binary search (but I had to assume data was already ordered) but in other cases I did a lot of linear searching and scanning so I have doubts about the efficiency of this code in general.
- In the case of dbOps, it might be a good idea to work with pointers if sorted is included, to avoid moving a lot of data around.


### PS 
Should anybody ever use this repository for learning or fun, you're welcome to try and improve the code and contact me :) 
