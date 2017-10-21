# Summary: Extreme Programming Explained

## Stay aware. Adapt. Change.

## Resources

- https://www.goodreads.com/book/show/67833.Extreme_Programming_Explained

## Values

Values are the roots of the things we like and don't like in a situation. Values are the large-scale criteria we use to judge what we see, think, and do. Making values explicit is important because without values, practices quickly become rote, activities performed for their own sake but lacking any purpose or direction.

If everyone on the team chooses to focus on what's important to the team, what is it they should focus on?

- **Communication:** 

  Communication is important for creating a sense of team and effective cooperation.

- **Simplicity:**
  
  What is the simplest thing that could possibly work?

- **Feedback:**

  Strive to generate as much feedback as we can handle as quickly as possible. The sooner you know, the sooner you can adapt.

- **Courage:**

  Courage is effective action in the face of fear. The courage to speak truths, pleasant or unpleasant, fosters communication and trust. The courage to discard failing solutions and seek new ones encourages simplicity. The courage to seek real, concrete answers creates feedback.

- **Respect:**

  No one is intrinsically worth more than anyone else. The contributions of each person on the team need to be respected. I am important and so are you.

## Principles

Bridging the gap between values and practices are principles. Principles are a set of domain-specific guidelines for finding practices in harmony with our values. Principles give us a better idea of what a practice is intended to accomplish. Understanding the principles gives you the opportunity to create practices that work with your existing practices and your overall goals.

- **Humanity:**

  - Basic safety
  - Accomplishment: the opportunity and ability to contribute to our society.
  - Belonging: the ability to identify with a group from which they receive validation and accountability and contribute to its shared goals.
  - Growth: the opportunity to expand their skills and perspective.
  - Intimacy: the ability to understand and be understood deeply by others.

- **Economics:**

  Make sure what you are doing has business value, meets business goals, and serves business needs.

- **Mutual Benefit:**

  There are always solutions to any problem that cost one person while benefitting another. When the situation is desperate, these solutions seem attractive. Mutual benefit is searching for practices that benefit me now, me later, and my customer as well. 

- **Improvement:**

  There is no perfect process. There is no perfect design. There are no perfect stories. We can, however, perfect our process, our design, and our stories. The cycle is to do the best you can today, striving for the awareness and understanding necessary to do better tomorrow. It doesn't mean waiting for perfection in order to begin.

- **Diversity:**

  Teams need to bring together a variety of skills, attitudes, and perspectives to see problems and pitfalls, to think of multiple ways to solve problems, and to implement the solutions. Respecting others and maintaining myself smooths communication in times of stress.

- **Reflection:**

  Good teams don't just do their work, they think about how they are working and why they are working. They analyze why they succeeded or failed. They don't try to hide their mistakes, but expose them and learn from them. No one stumbles into excellence. Reflection should not be limited to "official" opportunities. Reflection comes after action. Learning is action reflected. To maximize feedback, reflection is mixed with doing.

- **Flow:**

  Delivering a steady flow of valuable software by engaging in all the activities of development simultaneously. A continuous flow of activities rather than discrete phases. Any time you move away from flow, resolve to return. Resolve the problems that disrupted your flow and get back to improving flow as soon as you can.

- **Opportunity:**

  Learn to see problems as opportunities for change. The attitude of "survival" leads to just enough problem solving to get by. To reach excellence, problems need to turn into opportunities for learning and improvement, not just survival. Consciously choose to transform each problem into an opportunity: an opportunity for personal growth, deepening relationships, and improved software.

- **Failure:**

  If you're having trouble succeeding, fail. If you knew the best way to implement the story you'd just implement it that way. Given that you don't already know the best way, what's the cheapest way to find out? When you don't know what to do, risking failure can be the shortest, surest road to success.

- **Quality:**

  Projects don't go faster by accepting lower quality. They don't go slower by demanding higher quality. Pushing quality higher often results in faster delivery; while lowering quality standards often results in later, less predictable delivery. A concern for quality is no excuse for inaction.

- **Baby Steps:**

  What's the least you could do that is recognizably in the right direction? Under the right conditions, people and teams can take many small steps so rapidly that they appear to be leaping. Baby steps acknowledge that the overhead of small steps is much less than when a team wastefully recoils from aborted big changes.

- **Accepted Responsability:**

  Responsibility cannot be assigned; it can only be accepted. Whoever signs up to do work also estimates it. Similarly, the person responsible for implementing a story is ultimately responsible for the design, implementation, and testing of the story

## Practices 

Practices are the kind of things you'll see teams doing day-to-day. Practices by themselves are barren. Unless given purpose by values, they become rote.

- **Sit together**

Develop in an open space big enough for the whole team. Meet the need for privacy and "owned" space by having small private spaces nearby or by limiting work hours so team members can get their privacy needs met elsewhere.

- **Whole team**

  Include on the team people with all the skills and perspectives necessary for the project to succeed. People need a sense of "team":
  - We belong.
  - We are in this together.
  - We support each others' work, growth, and learning.

- **Informative Workspace**
  
  Make your workspace about your work. An interested observer should be able to walk into the team space and get a general idea of how the project is going in fifteen seconds. He should be able to get more information about real or potential problems by looking more closely. Use your space for important, active information.

- **Energized work**

  Work only as many hours as you can be productive and only as many hours as you can sustain. Burning yourself out unproductively today and spoiling the next two days' work isn't good for you or the team.

- **Pair programming**

  Write all production programs with two people sitting at one machine. Pair programming is a dialog between two people simultaneously programming (and analyzing and designing and testing) and trying to program better. Pair programmers:
  
  - Keep each other on task.
  - Brainstorm refinements to the system.
  - Clarify ideas.
  - Take initiative when their partner is stuck, thus lowering frustration.
  - Hold each other accountable to the team's practices.

  Pairing doesn't mean that you can't think alone. People need both companionship and privacy.

- **Stories**

  Plan using units of customer-visible functionality. As soon as a story is written, try to estimate the development effort necessary to implement it. Estimation gives the business and technical perspectives a chance to interact, which creates value early, when an idea has the most potential. When the team knows the cost of features it can split, combine, or extend scope based on what it knows about the features' value.

- **Sprints**

  Plan work 1 sprint at a time. Have a meeting at the beginning of every sprint. During this meeting:

  - Review progress to date, including how actual progress for the previous sprint matched expected progress.
  - Have the customers pick a sprint's worth of stories to implement this sprint.
  - Break the stories into tasks. Team members sign up for tasks and estimate them.
  
  Start the sprint by writing automated tests that will run when the stories are completed. Then spend the rest of the sprint completing the stories and getting the tests to pass. A team proud of its work will fully implement the stories, not just do enough work to get the tests to pass. The goal is to have deployable software at the end of the sprint which everyone can celebrate as progress. The sprint heartbeat also gives you a convenient, frequent, and predictable platform for team and individual experiments.
  
- **Slack**

  In any plan, include some minor tasks that can be dropped if you get behind. You can always add more stories later and deliver more than you promised. It is important in an atmosphere of distrust and broken promises to meet your commitments. A few met commitments go a long way toward rebuilding relationships.

- **Ten-Minute Build**

  Automatically build the whole system and run all of the tests in ten minutes. Never let the process take longer than ten minutes. If it does, someone has to optimize it but only until it takes ten minutes again.

- **Continuous Integration**

 Integrate and test changes after each check-in. The longer you wait to integrate, the more it costs and the more unpredictable the cost becomes. Integrate and build a complete product. Continuous integration should be complete enough that the eventual first deployment of the system is no big deal.

- **TDD**

  Write a failing automated test before changing any code. Test-first programming addresses many problems at once:

  - Scope creep
  - Coupling and cohesion
  - Trust
  - Rhythm

- **Incremental Design**

  Invest in the design of the system every day. Strive to make the design of the system an excellent fit for the needs of the system that day. When your understanding of the best possible design leaps forward, work gradually but persistently to bring the design back into alignment with your understanding.

- **Customer Involvement**

  Make people whose lives and business are affected by your system part of the team. The point of customer involvement is to reduce wasted effort by putting the people with the needs in direct contact with the people who can fill those needs.

- **Team Continuity**

  Keep effective teams together.

- **Root-Cause Analysis**

  Every time a defect is found after development, eliminate the defect and its cause. The goal is not just that this one defect won't ever recur, but that the team will never make the same kind of mistake again.

- **Shared Code**

  Anyone on the team can improve any part of the system at any time. If something is wrong with the system and fixing it is not out of scope for what I'm doing right now, I should go ahead and fix it.

- **Code and Tests**

  Maintain only the code and the tests as permanent artifacts. Generate other documents from the code and tests. Rely on social mechanisms to keep alive important history of the project.

- **Single Code Base**

  There is only one code stream.

- **Continuous Deployment**

  Put new software into production as soon as possible.

## The Theory of Constraints

The Theory of Constraints says that in any system there is one constraint at a time (occasionally two). To improve overall system throughput you have to first find the constraint; make sure it is working full speed; then find ways of either increasing the capacity of the constraint, offloading some of the work onto non-constraints, or eliminating the constraint entirely.

## License

Summary-Extreme-Programming-Explained is licensed under the [MIT License](LICENSE).
