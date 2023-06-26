# There are no "Technical stories"!

A prevailing anti-pattern in the industry is the use of "Technical stories" or work that cannot be defined as "functional". Such work typically revolve around security, infrastructure, technical debt, migration activities, and anything that the team considers more technical than what the business can comprehend.

So, why is this a problem? One common complaint is that technical stories often don't receive the same priority as business stories, resulting in delays that eventually reach a critical stage. And when that happens, it risks halting progress on all value-driven work for the business.
 
## It's not about technical work

If something is not understandable to the business, it cannot be prioritized fairly. It is unfair to expect Product owners to prioritize something they cannot see the value in or understand its benefits.

Its important to understand and illustrate the value of work in a common language that can help drive decisions.

Any unit of work improves the product for its consumers, either directly or indirectly, is valuable and can be quantified.
 
I find <a href="https://en.wikipedia.org/wiki/FURPS">FURPS+</a> as a useful reference to categorise the work.
	
- Enhances the product capability i.e. functionality (F)
- Improves the product usability i.e. User experience (U)
- Robustness of the system against failures i.e. Reliability against bugs, Availability against time to recovery (R)
- Address the performance i.e. scalability, memory management (P)
- And the internal quality of the product i.e. Supportability (S)
- Other considerations: Security, Observability and Tracebility, Ability to continuously integrate and deploy
	

Here are a few examples of why your current technical stories are actually business stories with value
 
| ***Technical work*** | ***Business story*** |
|:----------------------|:---------------------|
| Add SSL certificate to web application  |  We want to ensure user information is secure in transition through SSL security |
| Onboard application on continuous delivery pipeline | Ability to quickly deliver quality product while minimizing manual errors  |
| Migrate app to cloud |  There could be multiple reasons to move to cloud. Which one is yours?  ( Scale product to support 1 mil concurrent users, Reduce product cost through a flexible costing model, Improve availability of the product through on cloud backup and disaster recovery mechanisms ) |
| | |












