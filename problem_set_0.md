Question 1: In your opinion what are the 3 most important factors of a 12 factor app?
-Having one codebase tracked with revision control/versioning
-Keeping development, staging, and prod as similar as possible
-Separate config file!!!!



Question 2: Restate the Core Values of DevSecOps in your own words?
-Bringing people to the forefront; implementing automation wherever possible to speed up development and remove tedious/repetitive tasks; collaborating with team members that have different skillsets to enable everyone to work on any task.
-Learning from mistakes or issues via measurement so that the team can see how they are improving and use everything as a learning experience vs. a negative mark.




Question 3: Which of the 3 ways of DevSecOps do you think is the most difficult to implement? Explain why?
-Culture of continual experimentation and learning, because organizations that are not used to this type of culture can find it very difficult to shift mindsets from using mistakes as negative, punitive experiences to using them as learning experiences. The concept of experimenting to fail early and often is hard in practice but essential to adaptability. Getting companies to see the value in experimentation is key but it can be an uphill battle to do so. Anytime a shift in mindset is needed things become difficult just because of the human nature of being apprehensive about change.

-I am experiencing this now because our team is changing the way we are working and the people who are skeptical have given feedback that certain sessions have been wastes of time, when really we are in the experimentation phase and it is expected that not everything is going to work perfectly so we will change and adapt. The mindset is very hard to change.



Question 4: Why are we encouraged to treat our services as disposable?
-If there is an issue, we are not attached to the state that the app/services are in so we can quickly kill it.
-The app should not depend on the environment; reduces vendor lock in.
-Resources can be started and stopped at a moment's notice: you don't have to fear data loss and you can fix issues quickly in a stateless environment.





Question 5: Why is Dev Prod parity so important? What are some ways to acheive this?
-Being able to react nimbly if there are issues in production, if you roll forward you can be certain that the application is going to behave as expected.
-It increases confidence in testing - if testing is done in an environment that doesn't mimic production we have no way of certainly knowing that our code will work in a different environment. It reduces issues that could be encountered when moving from test to prod.
-To achieve this you can automate processes to ensure the configuration between environments stays the same. You can also implement disposability


