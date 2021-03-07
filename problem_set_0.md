Question 1: In your opinion what are the 3 most important factors of a 12 factor app?
1. Dev/Prod parity is important because the fewer differences between the dev and prod environments that you have, you (theoretically) reduce the amount of prod-specific issues.
2. Concurrency is important so that the app is able to scale, as well as so that nothing blocks any other apps.
3. Configuration is important to be used as an independent way so that it can be updated without touching the code base, which streamlines the process so that a config change doesn't need another deployment.


Question 2: Restate the Core Values of DevSecOps in your own words?
The core values of DevSecOps are culture, automation, measurement, and sharing.
Culture is related to people, process, and tools.
Automation is best when you have infrastructure as code.
Measurement is about how important it is to measure as much as you can.
Sharing has the intention of being forthcoming about the work with collaboration and feedback.


Question 3: Which of the 3 ways of DevSecOps do you think is the most difficult to implement? Explain why?
I would imagine the third way of DevSecOps is the most difficult to implement because it would be quite costly to build a culture of continuous experimentation and learning.  It would be a lot more work to get feedback and information from the customers, and would be also more work to spend the time figuring out what areas to improve with ourselves and the system.  Having said all of this, I absolutely see the value in doing so.


Question 4: Why are we encouraged to treat our services as disposable?
If you are able to spin something up quickly and tear it down equally quickly, it helps to reduce the amount of time that is needed if something goes wrong.


Question 5: Why is Dev Prod parity so important? What are some ways to achieve this?
Dev/Prod parity is important because having the development environment being as close to the production environment should reduce the impact of issues that are environment-specific.  I would think this could be achieved by cloning production environments (while being aware that there may be data that shouldn't be cloned exactly) and modifying the configs as needed.
