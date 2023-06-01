# There are no "Technical stories"!

A prevailing anti-pattern in the industry is the use of "Technical stories" or work that cannot be defined as "functional". Such work typically revolve around security, infrastructure, technical debt, migration activities, and anything that the team considers more technical than what the business can comprehend.

So, why is this a problem? One common complaint is that technical stories often don't receive the same priority as business stories, resulting in delays that eventually reach a critical stage. And when that happens, it risks halting progress on all value-driven work for the business.
 
## It's not about technical work

If something is not understandable to the business, it cannot be prioritized fairly. It is unfair to expect them to prioritize something they cannot see the value in or understand its benefits.

When a unit of work improves the product for its consumers, it means that the changes or enhancements being made have a positive impact on the users who interact with the system. This goes beyond just technical improvements and focuses on delivering value to both external users and internal users (such as the development team).

 
Any work that we do has an impact on product lifecycle
	
- Enhances the product capability i.e. functionality (F)
- Improves the product usability i.e. User experience (U)
- Robustness of the system against failures i.e. Reliability against bugs, Availability against time to recovery (R)
- Address the performance i.e. scalability, memory management (P)
- And the internal quality of the product i.e. Supportability (S)
	
That's FURPS (https://en.wikipedia.org/wiki/FURPS)

 
Here are a few examples of why your current technical stories are actually business stories with value
 
| ***Technical story*** | ***Business story*** |
|:---------|:---------|
| Add SSL certificate to web application  |  Ensure user information is secure in transition through SSL security |
| Migrate app to cloud |  There could be multiple reasons to move to cloud. Which one is yours?
- Scale product to support 1 mil concurrent users
- Reduce product cost through a flexible costing model
- Improve availability of the product through on cloud backup and disaster recovery mechanisms |
| Add unit/regression tests | Not applicable and huge anti-pattern. Just do it as you go. The PO is not supposed to prioritise such activities as they are meant to be integral part of development. Estimate your work inclusive of quality concerns. Quality should not
 be an after-thought and bulk activity. |









