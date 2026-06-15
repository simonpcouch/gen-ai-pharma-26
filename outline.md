# Part 1 - bluffbench 

* Ends with "Agents enact a performance of progress" 

# Part 2 - interlude 

## LLMs don't really care about correctness 

* Or at least, they can be incorrect in ways that feel strange to humans and occassionally difficult to fix.
* It's not just that they misinterpret the plots, but that their answers when they are wrong look very similar to their answers when they are right. 
    * Again, it's a performance of correctness and certainty. 
* bluffbench is an example of a pattern: LLMs, at least most of the current models, can exhibit this sort of deeply weird behavior that directly conflicts with what's correct. 
    * The result is a model that moves analysis forward, but doesn't necessarily match the values of data science, including correctness and skepticism. 
    * and this can lead to deeply weird behavior
* In data science, though, we care about actual correctness. 

## but this doesn't mean LLMs are useless for data work

* They are very good at certain tasks, including writing code. 
* We shouldn't take evidence like bluffbench to mean that LLMs are useless _anywhere_ you value correctness. 
* Instead, you have to figure out where they can fit and how to design around their limitations. 
* Another thing: they are generally getting more capable. 
    * Show bluffbench plot over time for most capable anthropic model
    * This is largely good, but introduces a complexity: what is true today might not be true tomorrow. It means it can be difficult to predict what they will be good at in the future.  

# Part 3 - agents for data analysis 

* So what does this mean for agents for data analysis? 
    * Brief aside: what is an agent? 
* Here is Posit Assistant, our agent for both general-purpose coding and data analysis 
* Point #1: the harness matters for correctness 
    * Show assistant eval plot with Posit Assistant vs. plain bluffbench 
* Point #2: code is the right foundation (maybe leave out if it seems too obvious)
    * Models are good at writing code
    * Code is reproducible and auditable by the human
* Point #3: the shape of the interaction matters 
    * What is the purpose of an analysis? 
        * often (maybe not always), it is to impart a sense of understanding on a human 
    * What Posit Assistant does to still provide understanding -- shorter turns, see code
        * These are also important for auditability and correctness. 




