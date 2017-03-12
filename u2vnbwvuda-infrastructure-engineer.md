## Infrastructure Engineer
#### San Francisco, CA

### Quick Summary
We believe companies should be able to send their data wherever they want, whenever they want, with no fuss. We make this easy with a single platform that collects, stores and sends data to hundreds of business tools with the flip of a switch. Our goal is to make using data easy, and we’re looking for people to join us on the journey. We are excited about building toward a world where engineers at other companies spend their time working on their core product, rather than spending nights and weekends tweaking their customer data into various formats for 3rd party tools.

Our infrastructure is mostly written in Go (we’re huge fans!), uses Docker containers for our 70 different microservices, and generally uses the latest and greatest from AWS.  Our small team is providing the data infrastructure for thousands of companies, and as a result we’re already processing terabytes of data each day.  We’re rapidly scaling our systems to keep up with our dramatic growth, and we’re looking for folks who love Kafka, NSQ, NoSQL databases, and distributed systems of every flavor.

Our customer data hub is helping companies achieve data nirvana, the blissful state you enter when all of your customer data is clean, complete, and accessible in your data warehouse and various analytics tools. Integrating with our platform enables our customers and partners to a new class of analytics models and marketing automation experiences.  Though we have already thousands of companies being built on top of our analytics platform, we’ve only penetrated less than 1% of the market.  

### Job Description
Acting as the middleman for billions of events isn’t easy. We essentially have to build the L4 networking layer, reliably delivering messages from clients in order, but at the L7 layer in the network stack. Where things get complicated is the fact that clients expect us to queue, instead of backing off. Messages get re-ordered, and we need to be prepared for the integrations we’re sending data to fail at any time.

We want to build a queueing topology to handle all of these cases gracefully, and scalably. If an integration’s endpoint goes down, it shouldn’t affect other destinations for that data. And if a customer suddenly batches a ton of data for an integration, they shouldn’t starve message delivery for their neighbors.

Most queueing systems don’t handle this case well. They’re severely limited in terms of partitions, topics, or whatever logical separation they use to provide isolation. We need a system that scales well, but also provides the same sorts of ordering and delivery guarantees that we’d get through a Kafka.

It’s a big, challenging piece of core infrastructure, but we’re feeling the pain more as customers exhaust the pipes for individual integrations.

+	Building infrastructure to process terabytes of data per day and thousands of API calls per second
+	Use cutting-edge technologies such as AWS, Go, Docker, and Terraform to continue to scale our infrastructure
+	Relentlessly measure and optimize as we build the highest-scale and most advanced analytics platform in the world

### Qualifications
+	CS Degree or equivalent knowledge of data structures and algorithms
+	2+ years of industry experience building and owning large-scale distributed infrastructure
+	Expert knowledge developing and debugging in C/C++, Java, or Go

### Company Info
You are currently viewing the public repo, which is limited in that company details have been ommitted from the job descriptions.  
    
We understand that this is a suboptimal user experience.  We are, for various reasons, unable to publicize the companies we work with, so we've
created a **private un-anonymized repository** which is much more informative on who these companies are and what they're hiring for.  
    
Please [authorize our Github OAuth2 application](https://letsrockit.co/users/auth/github?job_id=u2vnbwvuda-infrastructure-engineer) to be redirected to the private repo.
