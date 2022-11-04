# probability-and-statistics-sco-212
Notes on probability theory: https://www.youtube.com/watch?v=KbB0FjPg0mw&list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo
 A probablistic model is a mathematicle construction which is comprised of:
 
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
 

 


 
 
 
