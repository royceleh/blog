---
layout: post
title: Lessons from Gojek's Podcasts
---

Gojek is one of Southeast Asia’s superapp offering an on-demand multi-service tech platform. Last valued at US$10 billion, the decacorn launched a 14-episode podcast called GO FIGURE last year, hosted by then-CEO Nadiem Makarim, to discuss authentically the inner workings of a high-growth tech company. 
I went through the podcast and compiled some personal takeaways below (You can find the podcast on Youtube, Spotify and other popular podcast platforms).

#### Episode 1: Gojek’s Growing Pains of Becoming a Decocorn

* The leadership team underinvested in communicating the company’s vision and strategy effectively once Gojek started growing beyond a small group of employees. There were no company-wide OKRs and planning tools, resulting in alignment issues between teams due to the lack of a reference point on the company’s priority. Resolutions were made on a point-by-point basis from management, which gave the impression of a top-down leadership approach.
* There were instances where the team prioritised what the company was gunning for based on observations of other successful companies who were able to monetise (ie taking a business perspective), instead of focusing on taking a product/problem-centric approach. Ultimately, if you are able to help people solve a key problem, monetisation and revenue will follow.
* The choice of business model should be based on the company’s key strengths and values. For instance, in the case of GO-MART, Gojek’s value proposition was using its marketplace of drivers to create the fastest O2O market, so it decided not to follow traditional O2O business models like B2C or advertising.
* When hiring, project what the role will look like in 12-18 months, and assess whether the candidate has the ability/potential to meet those requirements.

#### Episode 2: Unlocking GOJEK's 2 Million Drivers

* There needs to be constant communication and interaction between Ops and Product to learn about each side’s perspectives, instead of making assumptions. Both teams have their own characteristics: Ops tends to be more anecdotal, while product and other digital teams are likely more data-driven. 
* There’s often the tempting short-term solution of employing human resources rather than technical resources (the former is often cheaper in countries like Indonesia) to solve Ops’ problems. That’s fast, but it doesn’t help you go far. Nonetheless, below a certain scale, it's fine to use such processes (especially when you are in the testing phase) instead of trying to build and automate everything.
* It’s important to bridge the gap and build the same level of empathy that Ops has in non-user-facing teams. Having more empathy improves intellectual curiosity and opens up an individual’s point of view when addressing issues.

#### Episode 3: The Gender Gap in Tech and How Gojek is Bridging it

* While the gender ratio at entry level roles may be balanced, it progressively becomes more skewed towards males at higher levels of the organisation. This can be generalised to most industries, not just in tech.
* It’s not just about gender, the point is diversity - Females bring in a different perspective. Gender just happens to be the most visible branch of diversity. Diversity should be enforced on a project basis, instead of just a general ratio at the organisational level.
* The solution shouldn’t be to intentionally hire more females, because that is preferential treatment towards women. It’s about looking for the best performer, regardless of gender.

#### Episode 4: Realistic Approaches To Machine Learning At Gojek

* To be considered successful, machine learning initiatives should either improve efficiency through automation, or push business metrics and customer experiences forward. The struggle comes from integrating data science with business problems.
* After formulating the problem, the first step is usually to start with a simple model first and get a baseline, before exploring more complex models. Lots of exploring and experimentations are involved in machine learning, you likely won’t get it right on your first try.
* Data science is less relevant in situations where the business cannot change anything to improve the outcome. For instance, you may be able to build a highly accurate churn prediction model, but churn will always happen and the company’s ability to move that metric is limited.
* The model needs to be able to capture a sense of the causality relationship involved in order for the business to take actionable steps to improve the outcome. This means that black-box models or complex features that don’t make business sense are often less relevant.

#### Episode 5: Gojek's Organisational Principles

* Long-term principles compound like savings accounts, there is no instant gratification and things may slow down in the short-run but they will have a long-term impact in the grand scheme of things. 
* You can be a people or thought leader, irrespective of your role. As the company grows to become complex, it needs masses of people who are adept at problem-solving and collaborating at all levels.
* It’s easy to recognise the importance of fostering an environment of collaboration and breaking down silos, but most companies don’t create the goal-setting incentives to achieve that. Quantifying collaboration and infusing it into processes helps to facilitate instituting such principles.

#### Episode 6: Gojek's 10x Engineer - Truth or Myth?

* When > 1 person works on a software, it becomes a communication problem and productivity dips beyond a certain headcount (~5). At Gojek, the system architecture gets mapped out based on what a 5-person team can do, instead of the reverse.
* Systems should be refactored as the startup grows and scales to better serve the multi-users. Until that refactoring is done, adding more engineers/teams will just add on to the bottleneck. Every startup likely goes through this process, as it’s inefficient to plan things out right from the start. You want to start monolithic since communication overhead is initially low. 
* You need to be proud of your work in order to produce high quality output, but at the same time be comfortable with the fact that the things you create have to evolve eventually. If you are attached to them, you will stand in their way of evolution. Take pride in the journey instead.

#### Episode 7: Is Bottom Up Innovation Really Possible at Gojek?

* Culture is everything that is not stated in processes/policies but defines the decisions that employees make everyday. It is an outward manifestation of a consistent shared set of values, identified by the actions that people take. It is also an efficient and scalable way of creating shared behaviours that no amount of policies can match.
* Walk the talk: At Gojek, leaders in technical teams have the necessary background. They are expected to be very involved in building things and serve as role models for their departments. 
* A sense of belonging and psychological safety encourages employees to behave autonomously (feel safe making decisions in this environment even though these decisions aren’t codified and protected by policies).
* Fear works and scales in systems/organisations where you are dealing with a completely solved problem that will not evolve, where everything is clear, and there’s little/no need for creativity. To be creative, you need to be open to failing and iterating. Creativity is not just about ideation, it’s about flexibly solving complex unexpected problems. When there’s a price to pay for failing, creativity is stifled.

#### Episode 8: How Does Gojek Design A Product That Actually “Fits”

* The biggest mistake is to jump straight into the solution, without first identifying the problem to address.
* Finding product market fit involves optimising as early as you can (time), as economically as you can (cost) and with a high degree of confidence. 
* Quantitative data tells you what’s happening (signal) and the magnitude of it, while qualitative data gives you opinions of why (possible insights into causality). One cannot do the other, and both are equally important.
* Aggressive incentives such as discounts create noise in the data because it’s the money that is causing the data to grow, not product market fit. Money can be used to overcome some shortcomings/pain-points of your product, but not for determining product market fit (people will use it because you are paying them to do so).
* However, if you are launching a product that the world has never seen before, then that’s where promotional incentives become more important. The amount of incentives that you give is proportional to the magnitude of behaviour that you want to change in your customers. Incentives can be more than just money, money is just the fastest and most explicit form.
* When you have strong product market fit, there’s high NPS (referrals), as well as some form of price insensitivity.
* When you hit the ceiling of a customer segment and are not expanding beyond it, the data will show. Your cost per incremental transaction increases, ROI goes down etc. That is when you know you need to get to a new segment for the business to grow. 

#### Episode 9: Gojek’s Growth Dilemma

* Incentives can get you the jumpstart you need to understand users’ product behaviour, however these tactics should be applied as part of a longer-term strategy. For instance, promotions could be used as a top-of-mind nudge to test whether the behaviour of getting a user to complete his/her Xth transaction is important.
* Marketing as a function is decreasing in effectiveness, because companies are assessing it in the short-term (eg month-to-month) and there is the pressure to deliver immediate results when in fact, there is a massive delay in the actual impact of brand-building campaigns (average 6 months). Marketing’s role is to be the first to mind in purchase occasions, to occupy that mental share.
* The user base of any company consists of users of different frequencies, with the far majority being infrequent users. It’s more effective to spread wide (reach) than to keep hitting on the same user repeatedly (frequency), when you’re targeting growth. 
* You want to focus your efforts on increasing the top of the funnel and conversion of low-frequency users. They are the ones who return the most value for every dollar that you spend, as they have yet to max out their ceiling of usage and hence there’s more to gain out of shaping their behaviour. In contrast, it’s harder to get power users to make that extra transaction.
* Treat power users as role models to understand the maximum utility that a user can gain from the platform. They symbolise a set of a-ha moments that they have achieved to get to where they are today, and these lessons can translate to actions that remove the friction for low-frequency users to similarly adopt such behaviours. 
* You can only improve word-of-mouth in the long term through product excellence. You can also design features/loops to match these organic conversations by natural extensions of the product (Example: Dropbox’s file-sharing feature encourages the recipients to use the product). Promotions can also be designed to loop your friends in (Example: Buy 3 get 4)

#### Episode 10: Fantastic Product Managers and Where to Find Them in Gojek

* At the end of the day, it’s all about solving the customer’s problem and that is how you should be evaluated (not strictly by the number of features you shipped etc). PMs should own the autonomy and accountability (vs being instructed on what to ship).
* Product management is massively unpredictable and PMs need the mental resilience to be comfortable with this. They should also have the ability to think a few steps ahead and contingency plan, creating a sense of calmness within the team. 
* PMs should genuinely love products that solve the customer’s problems (not limited to tech products). They do not necessarily need to have built one before, but they need to demonstrate that they have thought deeply about the products they use and understand why they love them. 
* It’s not just about coming up with solutions, but also defining what the problem is in the first place, and prioritising a list of problems to solve

#### Episode 11: How 3 Founders Met In Business School And Joined Forces

* The most useful part of attending business school was meeting and watching other students in action with their startups.
* The most effective way to learn how to start a company is by jumping in or to gain experience at another high-growth company.



