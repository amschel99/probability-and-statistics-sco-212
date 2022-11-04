# probability-and-statistics-sco-212
Notes on probability theory: https://www.youtube.com/watch?v=KbB0FjPg0mw&list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo
 A probablistic model is a mathematical construction which is comprised of:
 
 1. An experiment- something with a well defined outcome.
 2. A sample space - which is a set of all the possible outcomes of an experiment.
 
 ### An event is a subset of the sample space. 
 
 ## The Naive definition of probability
 ```
 p(A)= Favorable outcomes/ possible outcomes.
 
In an experiment, a coin is tossed twice, what is the probability of getting all tails?

Possible_outcomes= ["HH","HT","TH","TT"]

numberOfOutcomes= sizeof(Possible_outcomes)/sizeof(string);
 numberOfOutcomes ===4;
 int all_tails=0;
 for(int i=0; i<=numberOfOutcomes; i++){
 if(possible_outcomes[i]=="TT"){
 all_tails++;
 }
 }
 
 ofcourse all_tails===1;
 Favorable outcomes=all_tails;
 possible outcomes=numberOfOutcomes;
 
 probability of getting all tails is 1/4...
 
 sorry for the codinng jargon
 ```
 This definition of probability makes 2 faulty assumptions.
 1. all outcomes are equally likely
 2. there is a finite sample space.
 
 ## Multiplication rule
 For independent  events, p(A and B)= P(A) * P(B)

For dependent events p(A and B)=P(A) * p(B |A)

e.g drawing out A and King from 52 cards where 4 are As and 4 are kings

4/52 *4/51= 1/167.
We have to minus 1 from 52

 

 


 
 
 
