# Teach-yourself-coding
Teach yourself coding! _Remember These Things_ Before you get started. 

_**What I wish I'd been taught**_
  • Programming isn't about languages 
  • The language ultimately doesn't matter much 
  • There's not a lot of memorizing 
  • Most programming isn't about math 
  • Programming languages are simpler than human ones 
  • Programming is really about solving problems 
  • It's about explaining things to the idiot computer
  
_**Code isn't about language**_
   • Coding has only about eight main concepts 
   • They work in almost the same way in every language 
   • Learn how to use these concepts in English 
   • Write out the concepts first , then convert to code later 
   • Most beginners think they don't understand what code to write 
   • The real problem is they don't really understand the problem they're trying to solve 
   • Experts do that too ...
   
_**Comments are Code**_
    • Comments explain code to other programmers 
    • NO ! 
    • Code explains the comments to the computer
    
_**new variable**_
  • Name : what do we call this thing ? 
  • Type : what type of data does it contain ? 
  • InitVal : what is it's starting value ?
  
_**new variable algorithm**_
Create a variable called name of type type that starts with the value initVal

_**new variable code**_
Create a variable called name of type type that starts with the value initVal name initial

_**input**_
• variable : where answer from user will be stored • message : question being asked of the user

_**input algorithm**_
ask the user message and store the answer in variable

_**output**_
• message : text to write to user

_**Failure is WONDERFUL !**_
  • This is a normal part of programming 
  • Begin debugging now • Did you tell it what to do incorrectly ? 
  • or did you tell it to do the wrong thing ? 
  • Most beginners assume it's an implementation problem 
  • Usually it's really an algorithm problem
  
_**How to debug**_
  • the best way to debug is to not have bugs 
  • bad implementation can be googled 
  • bad algorithms usually cannot 
  • what are you not understanding ? 
  • what tools can you use ? 
  • DON'T start with a solution . 
  • start by truly understanding the problem
  
_**what happened here ?**_
• Easy to assume + sign is broken 
• That's not really the problem 
• try print ( " python " + " meetup " ) 
• hmmm . We can add text 
• I wonder if it thinks " 2 " and " 3 " are text ? 
• look up a tool to find out 
• type function does this !

_**while loop**_
• sentry : variable that will control loop 
• initialization code : code that initializes sentry 
• condition : loop repeats if condition is true 
• change code : code to change sentry so condition can be triggered

_**for loop**_
 • sentry : integer variable that will control loop 
 • start : integer value of sentry at beginning 
 • finish : integer value of sentry at end 
 • change : integer to add to sentry at each pass
 
_**for algorithm**_ 
 begin with sentry at start and add change to sentry on each pass until sentry is larger than or equal to finish


_**while loop**_
  • sentry : variable that will control loop 
  • initialization code : code that initializes sentry 
  • condition : loop repeats if condition is true 
  • change code : code to change sentry so condition can be triggered

_**while loop algorithm**_
Initialize sentry with initialization code then continue loop as long as condition is true . Inside loop , change sentry with change code

_**while loop notes**_
Note the syntax only requires a condition . Good logic requires much more . This is why while loops can be such notorious problems for beginners .

_**Multiple exits**_
  • consider a basic password loop 
  • It exits with a positive result if the user chooses the right password 
  • It exits with a negative result if the user is wrong three times . 
  • How will you code this loop ?
  • Use a compound condition 
  • ( tries > = 3 and guess ! = correct ) 
  • wait .. 
  • if it's a not , should it be ... 
  • ( tries > = 3 or guess ! = correct ) 
  • Screw it . make it a for loop 
  • If they guess correctly just promote the counter to exit 
  • No , make it an endless loop and throw in some break statements

**NOTE:** Coding Is Game Of Practice.
