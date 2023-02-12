# Describe two of the more interesting program bugs you had in your projects in the past

> Do a “post-mortem” analysis of how you found them, why you think these bugs happened and what you could do to avoid them


Throughout our careers as programmers, we may encounter numerous bugs or errors. Some of them can be fixed in a few seconds; others take a lot of time from our lives. Sometimes, after finding hard or stupid mistakes, you can either hate yourself for the time lost or be proud of yourself because your analytical abilities have led to success.
 
Therefore, I want to tell you about both kinds of bugs that I usually face:
 
1) A small, stupid bug that ruined my night. Well, when we had the algorithms course during the last semester, we were so full of the course, therefore some must-have tasks were easy for pretty much everyone. I wasn't an exception. Unfortunately, I once spent the entire night fixing a small and simple solution to a task involving the discovery of components in a graph. The problem was solved only in the morning, when I asked my teacher to see my code. The issue was the obvious fact that the solution should have included the if statement for n == 1. 

	- How did you find them?

	This issue was found by my teacher because, after a lot of time spent on bug finding, it is 	becoming more and more impossible to find it with your blurry eyes. I attempted to write 	stress tests, but they only helped find errors in large amounts of data, not in small ones.

	- Why do you think these bugs happened?

	The primary cause of this bug is a simple lack of attention and time spent thinking about the 	algorithm.

	- What could you do to avoid them?

 

2) The second big bug appeared in my first work. I had to write a script to compare the results of two different solutions. It was obvious that the second one should have had a better performance. Unfortunately, just one metric had a very bad outcome. I'd been living with this knowledge for one week before I went to the numerical method course lecture. Our teacher spoke to the class about floating-point representation and how some functions should be calculated to maintain precision. After that, a completely brilliant idea came to my mind: I had to use the Tailor series instead of regular sin.

	- How did you find them?

	Well, I found this particular mistake just because I have gained some more knowledge about 	the topic.

	- Why do you think these bugs happened?

	Unfortunately, this bug arose as a result of a misunderstanding of how certain functions 	work.

	- Why do you think these bugs happened?

	To tell the truth, the best way to avoid this kind of issue is to be a better specialist. A 	deep understanding of the frameworks you are using can help you a lot in this direction.

 

3) The additional bug that I want to introduce is something that was fixed quickly and painlessly. During the implementation of pet-project: a web application to assist researchers in developing a neural network using an effortless visual constructor. We had a comparatively large application; therefore, we practiced the test coverage. Once I decided to implement a small amount of testing for the class that helped store the neural network parameters in the PG database.  After some days of using the application, we understood that after making some changes in the specified entity, this change didn't occur there. Afterwards, I decided to implement more tests and realized that the method used for updating the database entity worked completely wrong.

	- How did you find them?

	I discovered this problem after some time using the application.

	- Why do you think these bugs happened?

	This bug happened, in part, because I hadn't spent enough time implementing tests.

	- What could you do to avoid them?

	From the conclusion above, I assume that, to avoid this kind of issue, I could develop more 	tests.
