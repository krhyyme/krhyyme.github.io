# Reflections on being a data scientist

I was recently asked about my experiences working as a data scientist by a close friend looking to transition out of 
academia once he completed his PhD. Considering a data science role, he asked _"What are five things you wish you knew, or someone told you,
at the start of your career?"_

### The title Data Scientist can describe many different roles.

Data science is often used as a catch-all term by business leaders to describe  heavily quantitative work their team
or company does. The potential applications cover a diverse set of domains. A non-exhaustive list would include pricing, 
personalization, operations research, demand forecasting, and survey analysis work. In addition, this doesn't capture the range of machine learning / data science engineering roles
that focus on deploying and maintaining models in production.

Each domain can require a unique mix of technical and soft skill sets. This is why it's hard to take the what is a  "real data scientist"
articles seriously. There is a diversity of skill sets that match the diversity of application domains. And often, successful analysts/software engineers who
have worked in these domains since before popularization of data science don't fit the conventional image of a data scientist that you see described
in the blogosphere or on Twitter. 

My recommendation to my friend was to identify what domains excite you and fill any identified skill gaps. Then chase interesting work
wherever it leads regardless of job title or whether someone online thinks its "real data science."

### Good code is organized code

Software engineering is almost entirely about managing complexity. Especially, when it comes to managing machine learning
or statistical modeling pipelines. When I hear the term "good code" used in my professional life it often means the code
base is:

* Readable: someone reading the code can _easily_ identify the moving parts and how they interact.
* Parsimonious: Doesn't engage in unnecessary complexity. No feature is more complex than the problem it is trying to 
solve.
* Documented: There is ample documentation that discusses how to use the codebase, what the codebase does, and how it works.

As data scientist we are professional programmers. And we need to care deeply about the craftsmanship of the tools we 
build. 

### Understand what motivates you

It's really important to know yourself and understand why your favorite projects leave you with a sense of satisfaction. Getting a job is
a culture match as well as a skill match. Having a confident sense of self enables you to ask the right questions about team culture, better 
navigate what particular employers may mean when they speak of "cultural fit", and construct a personal brand to attract employers that have
the flavor work culture that most appeals to you.

During my own career, I've found that I'm motivated by a sense of curiosity and discovery. This often translates to working with a team
that encourages self-directed work and tackling open-ended projects pushing the envelope of a company's data science capabilities.

### Data is collected because it's necessary to run the business. 

For the most part,in industry, data isn't collected for the purpose of analysis. It's collected for other business related reasons and rarely 
be in the form you want. More often than not, it will be unclear how events in the data are recorded and no one will know the data in sufficient detail to answer all your questions.

I've witnessed data scientists of all levels take a cynical and arrogant attitude when confronted with this reality. They would often 
remark "If those who collect data don't know anything then how am I expected to do this analysis!" or even threaten to leave
their roles whilst making the accusation that their employer is not "data mature" or "prepared for data science." The most frustrating
comments are when folks start throwing around the term "garbage in, garbage out" when data is not in the form they want. Claiming that the 
data is useless because its not 100% in the form they want.

This behavior is unfitting of a professional and is an attempt to take the easy way out. Its our professional responsibility to understand the 
best way to wield the data for data science purposes. If you are lucky - there will be a data engineering team that works with you to accomplish 
this. Or you will have to read the source code gathering the data, define many data hypotheses to test, continue to ask around for 
information, and/or suggest changes to the data collection process if the data doesn't have the information needed for the task.
This is hard work and is totally part of the job. 

### Integrity matters. Do the right thing.

Data scientists are often under a lot of pressure to generate novel insights that have big impacts to the bottom line. Sometimes,
in high pressure environments, data scientists take shortcuts or embellish results. This sometimes can put customers, employees, or/and the 
business at risk. 

It should go without saying but be honest about ideas and models that don't work. Be transparent about methods and ensure that
your work can be reproduced by your peers. Work with your manager to minimize tense situations that encourage rushed work. 
Don't be afraid to challenge decisions that you believe create unnecessary risk.

Integrity also means being informed on the ethical concerns related to data analysis, artificial intelligence, and machine learning. Here is 
a list of reading materials that I found particularly informative:

* [Big Data is People!](https://medium.com/@torgo/big-data-is-people-47158068201a)
* [Weapons of Math Destruction](https://weaponsofmathdestructionbook.com)
* [Archaeology for cyborgs](https://medium.com/@janeruffino/archaeology-for-cyborgs-a4c7c5594c2c)
* [A Code of Ethics for Data Science](https://medium.com/@dpatil/a-code-of-ethics-for-data-science-cda27d1fac1)