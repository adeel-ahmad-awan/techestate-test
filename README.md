# Read me

### questions

**Your thoughts about the code. What makes it amazing code. Or what makes it ok code. Or what makes it terrible code. How would you have done it. Thoughts on formatting. Logic..**

In my opinion, several improvements can make this code easy to maintained and enhance

1. I didn't find any use of service. for instance, all the emails were sent from the repository class, which is not right. As per my understanding "Repositories are classes or components that encapsulate the logic required to access data sources". 
2. the functions are too thick, and in my experience the thicker the function is, the harder it is to understand and enhance
3. there is no use of translator interface. This could provide us ease by converting any string to the required language. 
4. hardcoded strings are used in much of the code, which again could lead to a code difficult to maintain. 
5. there are no use of constants and hardcoded strings are used for string comparison, which could lead to code harder to expand from a feature point of view
6. there should be one coding standard used, eg some variables are declared as camelcase others were in some other standard
7. there is very little exception handling seen in the code. This may lead to 500 error on the server
8. at one instance I have seen returning the exception message as a response rather than returning a proper response. There should be a proper response
9. much of the time doc-block for the function are not there and if there are, then they are not properly communicating the proper return type or arguments.
10. in some functions there are dozen 'IF' statements, which I think is not good programming practice. 

**Refactor it if you feel it needs formatting. The more love you put into it. The easier for us to asses.** 
I have done much refactoring. but I was allowed a limited time. So I have done as much as possible in that time. Secondly, the pattern of the code was repeating itself, therefore I felt that in a limited amount of time if I cover some cycles of the pattern, then my point has been communicated. One last thing, I have placed as many points on the table I could, tough for some of the points, the refactored code may not be there. Sorry for that, but the time was an asset to play here.

sorry for third commit, i have mistakenly put readme file in wrng folder