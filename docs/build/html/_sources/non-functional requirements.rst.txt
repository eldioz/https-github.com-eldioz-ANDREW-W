Non-functional requirements
===========================
A non-behavioral requirement describes a technical feature of a system, features typically pertaining to availability, security, performance, interoperability, dependability, and reliability. Non-behavioral requirements are often referred to as ¡°non-functional¡± requirements due to a bad naming decision made by the IEEE (as far as I¡¯m concerned non-functional implies that it doesn¡¯t work).

Response time
-------------
On the one hand, because the web application faces scientists all over the world, the number of users is more, and the requests for simultaneous processing are much more, so the response time must be reduced as much as possible. On the other hand, because a lot of data is huge, it needs to be analyzed for a long time, which will bring a poor user experience to the user, so our reaction time must be less than 5 seconds, which is an optimal reaction time.

Aesthetic aspects
-----------------
Because this web application faces scientists all over the world, the interface must be internationalized, and it can support various languages such as English, Chinese, Korean and so on. Because this web application is the data analysis, so the interface as simple as possible, give scientists a rigorous style, so that the product is trustworthy. Since this web application is mainly fed by tables and scatter plots, the tables and scatter plots must be as clear as possible to make the data more explicit.

Confidentiality policy
----------------------
Ensuring the safety of the gene library is an integral part of our web application, and we must unconditionally guarantee the security of the user¡¯s data, as well as the results of each experiment. Most importantly, our web application serves scientists all over the world, so it requires more security and no data is leaked.

Availability
------------
We must always consider the fault, consider how to expand, mitigate risk, monitor availability, Respond to usability problems in a predictive and determined way.

Always consider the fault
#########################
The web application will always consider the response to the fault. For example, capturing the underlying exception, retrying logic, and circuit breakers, the circuit breaker mode is very useful in handling dependent failures, because they can reduce the impact of dependent failures on the system.

Always consider how to expand
#############################
The web application will always consider how to expand. The system can now function properly, which does not mean that it will continue to operate properly tomorrow.The flow of most Web applications is increasing. A website that generates a certain amount of traffic today may produce much larger traffic than we think tomorrow.When we build the system, we will take into account future traffic. When most of the contents in the navigation bar are static content, we can dynamically add the change content to the page in the user¡¯s browser. By grouping these dynamic data and differentiating with static content, the performance of Web pages can be improved and the dynamic data amount needed to be processed by the application is reduced. This improves scalability and ultimately improves availability.

Mitigate risk
#############
The web application will always mitigate risk. When the system fails, we have identified the cause of the failure for risk before that. When the system becomes more and more complex, eliminating all risks is becoming more and more impossible. More of what we do is to manage the risks of the system, know what these risks are, which risks are acceptable, and what we can do to mitigate the risks.

Monitoring availability
#######################
1. Monitor the health of the server and ensure that they are always running effectively.
2. Monitor the configuration changes of the system to determine their impact on the application.
3. In depth understanding of applications and services to ensure that they are running as expected.
4. From the perspective of users, we can detect the running of applications in real time so as to find them before users really find problems.

Respond to usability problems in a predictive and determined way.
################################################################
When our web applications are faced with more and more users¡¯ needs and become more and more complex. Preparing for dealing with usability problems ahead of time is the best way to reduce the probability and severity of problems.
