# An Elegant Puzzle: Systems of Engineering Management
An Elegant Puzzle: Systems of Engineering Management by Will Larson


## Chapter 1: Introduction
Nothing to note.

## Chapter 2: Organizations

- This chapter covers approaches to organization design + evolution
- Defines an organization as "a collection of people working toward a shared goal" and as an "exploration of the possible, undertaken together" by the x number of employees

### 2.1 Sizing teams
Managers should support 6-8 engineers
- Allows for active coaching, coordinating, writing strategies, leading change, etc.

	*Tech Lead Managers* 
	- Support <= 4 engineers
	- Take on share of design and implementation
	- Limited career opportunities
		- Work on management skills to progress
		- Or progress towards staff engineer (not as much in technical details)

	*Coaches*
	- 8-9 engineers
	- Too busy to be actively involved or invest in their team
	- Bad status quo

Managers-of-managers should support 4-6 managers
- Allows for coaching and aligning with stakeholders

On-call rotations should have 8 engineers

Teams <= 4 members aren't teams
- Leaky abstraction, they function indistinguishably from individuals
- Fragile if one member departs or is on vacation, etc.

*Closing thoughts*
- Teams should be 6-8 in steady state
- To make a new team, an existing team should be 8-10, then split into two teams of 4 or 5
- Managers shouldn't support more than 8 members

### 2.2 Staying on the path to high-performing teams

- Staying the course while growing is tough
- Hiring is usually the first fix, but may not be what is needed

#### 2.2.1 Four states of a team

1) Falling Behind -> Add People
2) Treading Water -> Reduce WIP
3) Repaying Debt -> Add Time
4) Innovating -> Add Slack

*Falling behind*
- Backlog is growing
- Working hard but not making a lot of progress
- Morale is low
- Users dissatisfied

*Treading water*
- Critical work can get done
- Can't quite start paying technical debt or starting new major projects
- Morale is a bit higher
- Users are a bit happier

*Repaying debt*
- Start paying technical debt
- Benefiting from paying technical debt

*Innovating*
- Technical debt is low
- Morale is high
- New work is for users

#### 2.2.2 System fixes and tactical support
This section contains more details on the fixes to the problems listed above.

*Falling behind*
- Hire more people until the team is treading water
- Set expectations with users

*Treading water*
- Reduce concurrent work and focus efforts to finish things until debt can be repaid
- Want to transition the personal view of productivity to a team view

*Repaying debt*
- Add time
- Work with users

*Innovating*
- Maintain slack
- Avoid backtracking
- Continue in work that is valued, don't spend too much time in science projects

**These fixes are slow.**

#### 2.2.3 Consolidate your efforts
- Focus team by team to fix these issues.
- Adding new members could also disrupt these processes in some stages

#### 2.2.4 Durable excellence
The process isn't fast. Changes stick around to compound.

### 2.3 A case against top-down global optimization
Reallocating individuals to address changes in global priority can be problematic.  The following sections will describe points against this idea.

#### 2.3.1 Team first
- It takes a while to become a high performing team, and disassembling them can leave to huge losses in productivity
- Stagnation can be bad, but restrained growth can prevent this
- Dismantling completely can take a long time to get back to the same levels of productivity

#### 2.3.2 Fixed costs
- Teams typically have high fixed cost and low variable cost

#### 2.3.3 Slack
- Believer in not adding more resources to teams with slack, less convinced on the inverse.
- Adding new resources to a team can slow it down by adding upstream constraints
- "Slackful" teams function as a debugger for the organization
	- They don't need to be considered when debugging org throughput

#### 2.3.4 Shift scope; rotate
Best to move scope between teams, preserving the teams themselves.
- Avoids regelling costs and preserves system behavior

Rotating individuals to an area that needs assistance for a fixed period of time also works.
- Gives the individual full focus to the other team
- Maintains membership on their current team

Another successful model is the swarming model.

### 2.4 Productivity in the age of hyper-growth
"We're going so quickly that every six months we're a new company".

Another corollary: "our process is always six months behind our head count".

Explores challenges and suggests strategies for overcoming them.

#### 2.4.1 More engineers, more problems
Real-world systems have a degree of self-healing properties
- E.G. Overloaded DB will slow down enough that someone will fix it
- E.G. Overwhelmed employee will get slow until someone finds a way to help

Most of these properties are efficient or deliberate.

*Problems*
- Onboarding and training needs grow.
- Time spent hiring grows
- New layers of management need to be added
- Teams need to be developed as engineering count grows
- There is increased load on development tools
- More deployments -> More outages -> More incident management and review
- More specialization teams means more on-call rotations

Rarely, but sometimes the marginal added value of hiring gets very slim for high hiring rates (can even be negative).

#### 2.4.2 Systems survive one magnitude of growth

Increased load has a few important trends
- System-implemented systems are designed to support 1-2 orders of magnitude of growth from the current state
- If traffic doubles every six months, then load increases order of magnitude every 18 months
- If your company is designing systems for one order of magnitude and 2x every six months, that's two re-implementations every three years

Productivity killer is the migrations not the rewrites.

#### 2.4.3 Ways to manage entropy
You only get value from projects when you finish them.  Many things come up.

*Time thiefs and solutions*
- Engineers giving interviews
	- Rotate the interview schedule
- Ad Hoc interruptions
	- Funnel interruptions and automate
	- Rotate cycles of who is answering random questions
- Ad Hoc meetings
	- Add blocks throughout the week

Companies with few interruptions almost always have really good, available documentations.

Keep interfaces generic.

Anti-pattern of the gatekeeper
- Build systems with enough isolation that most actions can go forward
- If they fail, make it a limited blast radius
- Sometimes these are for compliance reasons, otherwise it should be viewed almost as a bug

#### 2.4.4 Closing thoughts
Managing rapid growth is about stacking small wins.

When handling urgent project requests when you're already in trouble, learn how to say no in a way that's appropriate in your company culture.

### 2.5 Where to stash your organizational risk?
Organizational debt are problems that prohibit an organization from reaching its full potential.

Examples of organization debt:
- Biased interview process
- Inequitable compensation mechanisms

Almost never pressing problems, but the volatile subset that can become abruptly due is called *organizational risk*.

Examples of organizational risk:
-  Toxic team culture
-	Struggling leader

Most effective response: identify a few areas to improve, make sure progress is being made, and give yourself permission to do the rest poorly.

Write an explicit plan and agree with your manager on what reasonable progress look like.

"As an organizational leader, you'll always have a portfolio of risk, and you'll always be doing very badly at some things that are important to you ... it's unavoidable"

### 2.6 Succession planning
2-3 years into a role, may find personal rate of learning has trailed off.  This can be a sign to start looking for your next role, but also is a great time to practice succession planning.

Thinking through the holes that would be created in the organization if you left, documenting those gaps, and filling them in.

This is foundational for building an enduring organization.

#### 2.6.1 What do you do?
Step #1: figuring out what you do.

*Tips*
- Write down your role in meetings
- Look at calendar for non-meeting items
- Review past six months for recurring processes
- Look at individuals you support and how you support them
- Audit inbound requests
- Keep a to-do list
- Review external relationships

#### 2.6.2 Close the gaps
Review your list, see if there are individuals who can currently take the work with a relatively smooth transition, and cross those pieces off.

Review for individuals who could potentially take it over.

Filter remaining gaps to two lists:
1) Has the easiest gaps to close
2) The riskiest gaps

Write a plan to close all the easy gaps, and then 1-2 of the riskiest gaps.

Not a one-time tool, but should be a good base to run through this once a year.

## Chapter 3: Tools
This chapter provides various tools for managing change for an abstract chair of guiding and for serving as glue during transition periods.

### 3.1 Introduction to systems thinking
Product management skillset is effective for identifying problems, but systems thinking is the most universally effective.

#### 3.1.1 Stocks and flows
Links between events are more subtle than they appear.

*Stocks*: Accumulation of small changes, or the memory of changes over time.

*Flows*: Changes to stocks. Can be *inflows* or *outflows*
- Example of an *inflow*: training a new manager.
- Example of an *outflow*: a trained manage who departs the company.

*Information link*: Indicates that the value of a stock is a factor in the size of the flow.
- E.G. time available for developing features depends on # of trained managers.

A few notes:
- *Stocks* outside of a diagram's scope are clouds
- Every flow should be labeled
- Flows are rates
- Stocks are quantities

#### 3.1.2 Developer velocity
*The Science of Lean Software and DevOp* has four measurers of dev velocity:

 1. Delivery lead time
	 - Time from creation of code to deployment in production
 2. Deployment frequency
	 - How often code is deployed
 3. Change fail rate
	 - How frequently changes fail
 4. Time to restore service
	 - The amount of time spent recovering from defects

These modeled as a system to measure dev productivity:

1. Code review rate
	- Pull Requests are converted into Ready Commits based on code review rate
2. Deploy rate
	- Ready Commits converted to Deployed Commits
3. Defect rate
	- Deployed Commits converted into Incidents
4. Recovery rate
	- Incidents remediated into Reverted Commits
5. Debug rate
	- Revert Commits debugged into new Pull Requests

This creates a feedback loop.  The downstream behavior effects the upstream.

Finding where to invest isn't one size fits all.
- E.G. If there isn't a backlog of ready commits, speeding up the deploy rate won't be valuable

#### 3.1.3 Model away
Any difficult problem is worth trying to represent as a system.

Check out Stella (expensive) or Insight Maker.

### 3.2 Product management: exploration, selection, validation
Good to separate engineering and product leadership.

Product management is an iterative elimination tournament with rounds of:
1. Problem Discovery
	- Uncovering possible problems to work on
2. Problem Selection
	- Filtering those problems down to a subset
3. Solution Validation
	- Ensuring your approach to solving these problems works as cheaply as possible
4. Execution
	- Not a phase, just loops back to Problem Discovery

This obviously isn't all that needed to be a PM, but it's a good starting place.

#### 3.2.1 Problem discovery
This is often skipped, but taking time to evaluate which problems to solve is a great predictor of a team's long-term performance.

Common themes that generate problems:
- Users' pain
	- Problems the user experiences
- Users' purpose
	- What motivates users to engage?
- Benchmark
	- How does you company compare to competitors?
		- Specifically, where are you weaker?
- Cohorts
	- Explore your data for cohorts hidden behind top-level analysis to find new kinds of users with different/surprising needs
- Competitive advantages
	- Knowing where you strong can open new doors that you can fill compared to other companies
- Competitive moats
	- Sustaining competitive advantage that makes it possible to pursue offerings others cannot.
	- 1) What do your existing moats enable you to do today?
	- 2) What are the potential moats you could build for the future?
	- 3) What moats do your competitors have?
- Compound leveraging
	- What could you build today that would compound into major product/technical leverage?
	- Work to get the benefit twice
		- Design example: Introducing a navigation scheme that supports an expanded set of actions today and will support future additions
		- Infra example: Moving from a failing piece of tech to a new standard (addresses reliability, lowers maintenance cost, reduces cost of future migrations)

#### 3.2.2 Problem selection
- Surviving the round
	- What do you need to do to survive the current round?
- Surviving the next round
	- Where do you need to be when the next round comes along to avoid getting eliminated?
- Winning rounds
	- It's important to survive, but also to win
- Consider different time frames
	- What would you do if you were out of money in six months?
	- What if there were no external factors forcing results until two years out?   Five years?
- Industry trends
	- Where is the industry moving and how will you take advantage of those trends/avoid rework?
- Return on investment
	- Take a look at cost and potential return
	- Don't overlook small and easy wins
- Experiments to learn
	- What can you learn now to make problem selection easier in the future?

#### 3.2.3 Solution validation
Worth it to have an explicit solution validation phase to make sure the approach is correct and worth it.

- Write a customer letter
	- Write the launch announcement, are you able to write something exciting, useful, and real?
- Identify prior art
	- How do peers in the industry approach this?
		- Doesn't mean it's the best way, but means it's possible
		- Take with a grain of salt depending on the source
- Find reference users
	- Can you find guinea pigs fo the solution?  If not, might need to be skeptical and go back to the drawing board
- Prefer experimentation over analysis
	- Analysis can uncover missing info, but experimentation allows you to find problems you didn't anticipate
- Find the path more quickly traveled
	- Most expensive way to validate is to build out entirely
- Justify switching costs
	- Cost of users switching?

Most aspects of running a successful technology migration overlap with good solution validation.

### 3.3 Visions and strategies

As an organization grows beyond 50 people, organizational alignment can be difficult.

Understanding each instance of each team isn't scalable.

Operating reviews for metrics and major projects was helpful, but was better for learning and fine-tuning versus broad alignment.

Strategy and vision proved to be the most effective tool for alignment at scale.

#### 3.3.1 Strategies and visions
*Strategies*: Grounded documents that explain trade-offs and actions that will be taken to address a specific challenge.

*Visions*: Aspirational documents that enable individuals who don't always work closely together to make decisions that fit together cleanly.

|  | Strategy | Vision |
|--|--|--|
| Purpose | Approach to a specific challenge | A gentle, aligning pressure |
| Character | Practical | Aspirational |
| Time Frame | Variable | Long-Term |
| Specificity | Accurate, detailed | Illustrative, directional |
| Quantity | As many as useful | As few as possible |

#### 3.3.2 Strategy
Recommends specific actions that address a given challenge's constraints.

A good structure is the following:
1. Diagnosis
	- Describes the challenge at hand
	- A very thorough problem statement
	- Before you finish reading, you'll often have several good approaches
	- E.G. "I am too busy to think about long-term goals. I attend 35 hours of meeting each week. I am under pressure to immediately increase team performance. I believe that if I stop doing my current meetings, short-term team performance will decrease. I am concerned if my short-term team performance decreases, I may lose face as an effective leader, which will undermine my career opportunities. I believe that if I don't think about long-term goals, our performance will never improve, which will also undermine my career opportunities."
2. Policies
	- Identify how you will approach this problem and often the trade-offs between two competing goals.
	- For the example above, you may allow short-term performance to dip to benefit long-term performance.
	- Bad policy results in "So what?"'s
		- This policy likely entrenches the status quo
	- Good policy results in "Oh that will annoy so and so..."
		- This policy takes a clear stance on competing goals
3. Actions
	- When you apply the policies to the diagnosis
	- Good actions usually cause a reaction like "This is going to be uncomfortable, but I think it can work"
	- For the example above, action could be to "stop attending weekly team meetings to free up time and move to a monthly metrics review with blocked out focus hours"

Be honest about constraints that make the challenge tough (usually a people or organizational aspect).

#### 3.3.3 Vision
Describe a future in which trade-offs are no longer mutually exclusive.

Helps individuals think beyond the local maxima without tightly centralized coordination.

A good vision has the following:
1. Vision statement
	- 1-2 sentence aspiration statement to serve as a summary
	- This will be repeated often and is a core speaking point
	- Don't need to capture every detail, but needs to be memorable enough to evoke the vision
2. Value proposition
	- How will you be valuable to users and the company?
	- What successes can be achieved?
	- Starting from users leads to visions that are more ambitious and grounded
3. Capabilities
	- What capabilities will the product, platform, and team need to deliver on the value proposition?
4. Solved constraints
	- What are you limited by today, but won't be in the future?
5. Future constraints
	- What constraints will come in the future?  Hopefully easy to adjust like funding/hiring
6. Reference materials
	- Link all plans, metrics, updates, references, and documents into an appendix
	- Allows complexity without losing context
7. Narrative
	- Synthesize all of these details into a ~1 page easy to digest summary
	- In the final, this is probably second to the vision statement

*A few additional tips*:
- Test the document
	- This is a core leadership tool.  Iterate.
	- Get feedback, address conflict in the feedback
- Refresh periodically
	- Refresh once a year
	- If it's outdated, restart
- Use present tense
- Write simply
	- Lost the buzzwords

You should have one vision for each complete, distinct area, but no more.

Having two clear visions that overlap areas is worse than zero.

Useful when:
- Team is struggling to align with stakeholders
- You're struggling to lead a cohesive organization

### 3.4 Metrics and baselines
Planning goes from specific projects into goals.

Goals decouple the "what" from the "how".

*Defining Goals*
- Bad goals are basically numbers
	- E.G. "Our p50 build time will be below two seconds"
	- E.G. "We'll finish eight large projects"
	- Aren't sure if these are ambitious or if they even matter
- Good goals have four specific kinds of numbers
	1. A **target** you want to reach
	2. A **baseline** where you are today
	3. A **trend** describing current velocity
	4. A **time frame** to set bounds for the change

	- E.G. "In Q3, we will reduce time to render our frontpage from 600ms (p95) to 300ms (p95).  In Q2, render time increased from 500ms to 600ms."
- Tests of an effective goals
	- Someone who doesn't know much about an area can get a feel for the difficulty
	- They can also evaluate if the goal was achieved

*Investments and baselines*
These are two types of goals.

*Investments*: Describe a future state you want to reach

*Baselines*: Describe aspects of the present you want to preserve
- Help to narrow the solution space to accomplish investment goals
- Typically about preserving a current property

Pair investment goals with baseline metrics (also called *countervailing metrics*).

Example:
- Efficiency of running batch jobs shouldn't exceed current price of $0.05 per GB
- Batch jobs should not increase alert load on teams, which is currently alerting 2x per week

*Plans and contracts*
Goals are useful for planning.

Specify as few investment goals as possible (maybe 3), and that should be the focus of planning.

*Acronyms mentioned*
- *SLO*: Service level object
- *OKR*: Objectives and key results

### 3.5 Guiding broad organization change with metrics
Very effective to lead organizational change if you don't necessarily have authority.

*Approach*
1. Explore
	- Get data into an explorable formate
	- Look through it and get a feel for it
	- Identify the levers of change
		- E.G. Batch pipeline is majority of your cost
2. Dive
	- Once 3-4 issues are identified, dive deep on those areas
	- E.G. Batch jobs could be based on # of jobs, total data stored, new development, or by expensive jobs
3. Attribute
	- Find the true source of the cost metric, may be for a team that supports the team you initially thought
4. Contextualize
	- Build context around teams performance
	- E.G. It's one thing to know they spend $100,000 / month, but another to know they spend that and are the second-highest spender of 47 teams
	- Benchmarking is powerful
		- Benchmark into cohorts (front=end, back-end, and infra teams) because cost is different
5. Nudge
	- Dashboards can be helpful
	- Push notifications (email) can be even better for metrics that have shifted
	- Basically notify when behavior shifts
6. Baseline
	- Key teams should agree on baseline metrics
7. Review
	- Running a monthly or quarterly review for teams
	- Typically requires and executive sponsor

### 3.6 Migrations: the sole scalable fix to tech debt
Most interesting migration was Uber's migration from Puppet-managed services to self-service provisioning model to spin up services in a matter of clicks.

Migrations are essential and frustratingly frequent as codebases and businesses evolve.

Most processes/tools only support one order of magnitude.

If something requires a migration at increased scale, it's likely a sign that you build it properly instead of being over-designed.

#### 3.6.1 Why migrations matter
Usually the only available way to make meaningful progress on technical debt.

Each migration aims to create technical leverage or reduce tech debt.

Googler's phrase: "Running to stand still" for teams whose capacity is spent upgrading dependencies and patterns.

Migrations are healthy, if you don't do them when needed, it'll probably read to a full rewrite.

#### 3.6.2 Running good migrations
*Playbook for migrations*
1. De-risk
	- Do so quickly and cheaply
	- Write a design document, show teams who will have a tough time, iterate, test against roadmap, iterate
	- Start with the most challenging migrations
2. Enable
	- Slow down, build tools to handle the easy 90%
	- Figure out self-service tooling and documentation
	- **Best migration tools are incremental and reversible**
3. Finish
	- Last phase is deprecating the legacy system
		-	This requires 100% adoptions
	- Stop the bleeding, have all new code use the new approach
	- Generate tracking tickets and push migration statuses to teams that need to migrate
	- Finish it yourself, get into the nooks and crannies
	- Recognition should be reserved for their successful completion

### 3.7 Running an engineering reorg
For quickly growing companies, here are two skills that have a disproportionate impact on organizational success:
1. Making technical migrations cheap
2. Running clean reorganizations


*Framework for (re)designing an engineering organization (more of a thinking tool than recipe)*
1. Validate that organizational change is the right tool
2. Project headcount a year out
3. Set target ration of management to individual contributors
4. Identify logical teams and groups of teams
5. Plan staffing for these teams and groups
6. Commit to moving forward
7. Roll out the change

#### 3.7.1 Is a reorg the right tool?
*Two best kinds of reorganizations*
1. The one that solves a structural problem
2. The one that you don't do

*The worst kind*
1. The one you do because you're avoiding a people management issue

*Checklist to see if reorganization is the right tool*
1. Is the problem structural?
	- Reorgs can increase communication, reduce decision friction, and focus attention
	- If not one of these, consider something else
2. Are you reorganizing to work around a broken relationship?
	- Karma always comes do with management
	- Better off addressing the issue than working around it
3. Does the problem already exist?
	- Wait until it exists to solve it
	- Hard to predict future problems, and even if you do, you may hit a different problem first
4. Are conditions temporary?
	- Are you in a crunch period or a unique period?
		- If so, it might be best to just continue on and rethink afterwards

#### 3.7.2 Project head count a year out
*Ways to reason to this number*
1. Optimistic number based on what's barely possible
2. Based on the "natural size" of your organization if every position was fully staffed
3. Realistic number based on historical hiring rates

Merge these into a single number.  Historical trends should hold the most weight.

#### 3.7.3 Manager-to-engineer ratio
If manager is expected to do hands-on technical work, their teams should be 3-5 engineers (unless it already exists).

If not, then 5-8 engineers depending on experience is typical.

If you're targeting more, then you should ask why.

6-8 is a usual target.

#### 3.7.4 Defining teams and groups
Example with 35 engineers and 7 engineers per manager.

35/7 = 5 managers
Log7(35) ~= 1.8 managers of managers

Orgs should generally round up.

35 engineers should probably be 1-3 groups with 5-6 teams.

*Additional considerations*
1. Can you write a mission statement for each team?
2. Would you personally be excited to be a member of each team, and to be a manager of each team?
3. Put teams that work together (especially poorly) as close as possible.
	- This minimizes distance of escalations with disagreements
	- Poor working relationships are the by-product of information gaps
4. Can you define clear interfaces for each team?
5. Can you list areas of ownership for each team?
6. Have you created a gap-less map of ownership so each responsibility is owner by a team
	- Try to avoid a implicitly creating holes
7. Are there compelling candidate pitches for each team?
8. Are you over-optimizing on individuals versus establishing a sensible structure?

#### 3.7.5 Staffing the teams and groups
*Sources of candidates*
1. Team members who are ready to fill the roles now
2. Team members who can grow into the roles within the time frame
3. Internal transfers from within your company
4. External hires who have the skills already

Keep a spreadsheet and go in this order.

Missing someone is the cardinal sin of reorganization

#### 3.7.6 Commit to moving forward
*Questions to ask*
1. Are the changes meaningful net positive?
2. Will the new structure last for at least six months?
3. What problems did you discover during redesign?
4. What will trigger the reorg after this one?
5. Who is going to be impacted most?

#### 3.7.7 Roll out the change
*Key elements to a rollout*
1. Explanation of reasoning driving the reorganization
2. Documentation of how each person and team will be impacted
3. Availability and empath to help bleed off frustration from the individuals who are impacted

*Tactics for doing the above elements*
1. Discuss with heavily impacted individuals in private first
2. Ensure managers and other key individuals are prepared to explain the reasoning of the changes
3. Send out an email documenting the changes
4. Be available for discussion
5. If necessary, hold an org all-hands, but try not to
	- People don't process well in large groups
	- Best discussion is in small rooms
6. Double down on doing skip-level one-on-ones

*Closing thoughts*
An organization is:
1. A collection of people
2. A manifestation of an idea separate form the individuals comprising it 

### 3.8 Identify your controls
When transitioning from directly supporting teams to partnering with managers, this helps to remain effective without understanding day-to-day tasks.

This helps to know where to engage and where to hang back to avoid micromanaging.

*Common controls*
- Metrics
	- Align on outcomes, but leave how they're achieved as flexible
- Visions
	- Ensure you agree on long-term visions, keep short-term flexibility
- Strategies
	- Make sure you have a shared understanding of constraints and how to address them
- Organization design
	- Allows you to coordinate the evolution of a wider organization within the context of sub-organizations
- Head count and transfers
	- Ultimate form of prioritization
	- Good forum for validating how organizational priorities align on individual teams
- Roadmaps
	- Align on problem selection and solution validation
- Performance reviews
	- Coordinate culture and recognition

*Agree on degree of alignment for each one, here are the levels*
- I'll do it
	- Stuff I will do
	- Be explicit to avoid redoing work
	- Use this sparingly
- Preview
	- Be involved early and often
	- May not be on the same page at the beginning
	- This helps to avoid rework
- Review
	- Weigh in before it gets published or rolled out
	- This usually means you're already pretty aligned
- Notes
	- Projects you'd like to follow on, but don't have much to add in
	- Want to be able to represent colleagues work correctly
- No surprises
	- Work is currently aligned, but requires updates to keep mental model in tact
	- If asked about related problem, want to be able to answer correctly
	- This one is important
- Let me know
	- We're well aligned and confident you can deliver
	- Let me know if something comes up where I can help

If you can't imagine a world where you don't preview everyone's work, it's probably time to reflect on what's holding you back from letting the team thrive.

### 3.9 Career narratives
Peculiar challenge is investing in someone's career development when they're unsure on their own goals.

Also hard to plan your own career.

*Career narrative*: Intersection between the individual's and their manager's perspective

#### 3.9.1 Artificial competition
Much more opportunities on career ladders than off of them.

Let's say you want to be head of engineering at a mid size company. There is probably only one person at that company that will achieve that and everyone else is likely pursuing that path as well.

Another approach is to identify the gaps that would keep you from being a strong head of engineering, and then starting to use your current role to fill those gaps.

Head of engineering will be skilled at organizational design, process design, business strategy, recruiting, mentoring, coaching, public speaking, and written communication. They also have a broad personal network, and a broad foundation from everything from project engineering to infrastructure engineering.  This isn't even a complete list.

**There is no need to convince yourself that your current role is holding you back -- everything you need is here.** These skills can be practiced now.

An important part of setting goals is developing areas you're less experienced in to maximize global success. It's equally important to succeed locally in your current environment by prioritizing what you do well.

*Action steps*
1. Write up as many goals as you can for what you want to accomplish in the next one to five years
2. Prioritize this list
3. Pick a few that you want to focus on in the next 3-6 months
4. Share with your manager

#### 3.9.2 Translating goals
Now, we need to translate these goals to actions.  This is where your manager can be helpful.

Manager's have a strong sense of the business needs and can intersect those needs with your interests and goals.

A refined list of goals, aligned with company priorities, becomes a central artifact for collaborating with your manager on career evolution.

Refresh it every quarter or so.

### 3.10 The briefest of media trainings
*Three rules*
1. Answer the question you want to be asked
	- Reframe difficult questions into one that you're comfortable answering
2. Stay positive
	- Find positive framing and stick to it
3. Speak in threes
	- Stick to three concise points

### 3.11 Model, document, and share
A good way to grow as a leader is to develop a range of styles and apply them to various circumstances, don't just apply one style.

One tricky and common leadership scenario is leading without authority.

This is called **Model, Document, Share**

#### 3.11.1 How it works
Hard to have personal credibility right off the back (even if hired on experience). This example is about recommending Kanban.

*Model*
- Measure team's health (surveys) and throughput (lightweight task sizing) to establish a baseline
- Just start using Kanban, don't make a big deal. Frame as an experiment.
- Keep iterating and improving until it's refined and test against the baseline to see if it's helping

*Document*
- After an effective approach is found:
	- Document the problem
	- The learning process you went through
	- The details on how another team could adopt the practice
- Be detailed and receive feedback

*Share*
- Share your documented approach and experience doing the rollout
- Don't ask everyone to adopt the change or lobby for change, just present the approach and your experience

#### 3.11.2 Where it works
*Top-down mandate assumes:*
- It's better to adopt a good-enough approach quickly
- Teams have the bandwidth to adopt a new approach
- The organization has available resources to coordinate a rollout
- You want to centralize decision-making on this topic
- Consistency is important (all teams need the same approach)
- Making this change quickly is important

*Model, Document, Share assumes:*
- It's better to adopt a great approach slowly
- Some teams don't have the bandwidth to adopt a new approach
- The organization may not have resources to coordinate a rollout
- You want to decentralize decision-making on this topic
- Teams have agency to adopt the appropriate practices for themselves
- This change can be approached gradually

Model, Document, Share may not always work, but it's an inexpensive failure most of the time.

### 3.12 Scaling consistency: designing centralized decision-making groups
As organizations grow, there is a subtle sliding to inconsistency.

_Some solutions to this_
- Formalized sprints
- Training
- Shadowing
- Documentation
- Linters
- Process automation (especially deployment)
- Incident reviews

Most people reach for adding a centralized, accountable group.
- Production reviews (standardize product decisions)
- Architecture group (encourage consistent technical design)

Some of these groups can become
- Authoritative
- Rigid gatekeepers
- Advisory

#### 3.12.1 Positive and negative freedoms
_Positive freedom_ -  The freedom to do something
- E.G. Pick a programming language for a project

_Negative freedom_ - The freedom from things happening to you
- E.G. Not to be obligated to support additional programming languages

#### 3.12.2 Group design
_Choices surrounding these groups_
**Influence**
- How will they influence results?
	- Authoritative that makes binding decisions?
	- Work through advocacy?
- Answering these questions and member selection are important

**Interface**
- How will other teams interact with this team?
	- Tickets, emails, weekly review sessions?
- Reviewing work before it launches?
- Previewing designs before work is started?

**Size**
- Six or fewer could become a true team focused on the team versus individual identities
- 10+ will be tough to have discussions and should be broken down into subgroups

**Time commitment**
- How much time will members be working in this group?
- What are their priorities?

**Identity**
- Should members view their role in this group as their primary identity?
	- If so, this should be a small and highly committed team

**Selection process**
- How will you select numbers?
	- Structured process works well
		- Identify requirements to be a member
		- Identify skills that will be valuable
		- Allow people to apply
	- Consistency is critical here because membership will often have perceptions of status

**Length of term**
- How long will people serve?
	- Permanent?
	- Fixed terms?
		- Eligible for subsequent elections?
- Best default is fixed terms and allowing current members to remain eligible without term limits

**Representation**
- How representative will this group be?
	- Explicit selection on teams, tenure, seniority?
	- Or clustered selection?
- A good mix is important

#### 3.12.3 Failure modes
_Four ways these groups consistently fail_

**Domineering**
- Significantly reduce positive and negative freedoms
- Churn factories for members
- **A key cause of this is where decisions are abstracted from the consequence of the decision**
	- E.G. Architecture groups where the members write little code

**Bottlenecked**
- Helpful, but try to do more than they actually do

**Status-oriented**
- More emphasis on being a member than on the groups actual purpose

**Inert**
- These groups don't do much of anything
- Members are gelled or are too busy

To avoid these, a manager should be in every centralized group and they're responsible for iterating on the format to avoid these pitfalls.

### 3.13 Presenting to senior leadership

### 3.14 Time management

### 3.15 Communities of learning

## Chapter 4: Approaches

### 4.1 Work the policy, not the exceptions

#### 4.1.1 Good policy is opinionated

#### 4.1.2 Exception debt

#### 4.1.3 Work the policy

### 4.2 Saying no

#### 4.2.1 Constraints

#### 4.2.2 Velocity

#### 4.2.3 Priorities

#### 4.2.4 Relationships

### 4.3 Your philosophy of management

#### 4.3.1 An ethical profession

#### 4.3.2 Strong relationships > any problem

#### 4.3.3 People over process

#### 4.3.4 Do the hard thing now

#### 4.3.5 Your company, your team, yourself

#### 4.3.6 Think for yourself

### 4.4 Managing in the growth plates

#### 4.4.1 In the growth plates

#### 4.4.2 Outside the growth plates

#### 4.4.3 Aligning with values

### 4.5 Ways engineering managers get stuck

### 4.6 Partnering with your manager

### 4.7 Finding managerial scope

### 4.8 Setting organizational direction

#### 4.8.1 Scarce feedback, vague direction

#### 4.8.2 Mining for direction

### 4.9 Close out, solve, or delegate

## Chapter 5: Culture

### 5.1 Opportunity and membership

#### 5.1.1 Opportunity

#### 5.1.2 Membership

#### 5.1.3 Keep going

### 5.2 Select project leads

### 5.3 Make your peers your first team

### 5.4 Consider the team you have for senior positions

### 5.5 Company culture and managing freedoms

### 5.6 Kill your heroes, stop doing it harder

#### 5.6.1 The fall and rise of a hero

#### 5.6.2 Kill the hero programmer

#### 5.6.3 A long time coming, a long time going

#### 5.6.4 Resetting broken systems

## Chapter 6: Careers

### 6.1 Roles over rocket ships, and why hypergrowth is a weak predictor of personal growth

#### 6.1.1 Your new career narrative

#### 6.1.2 Opportunities for growth

### 6.2 Running a humane interview process

#### 6.2.1 Be kind

#### 6.2.2 What role is this, anyway?

#### 6.2.3 Finding signal

#### 6.2.4 Be prepared

#### 6.2.5 Deliberately express interest

#### 6.2.6 Feedback loops

#### 6.2.7 Optimize the funnel

### 6.3 Cold sourcing: hire someone you don't know

#### 6.3.1 Moving beyond your personal networks

#### 6.3.2 Your first cold sourcing recipe

#### 6.3.3 Is this high-leverage work?

### 6.4 Hiring Funnel

#### 6.4.1 Funnel fundamentals

#### 6.4.2 Instrument and optimize

#### 6.4.3 Extending the funnel

### 6.5 Performance management systems

#### 6.5.1 Career ladders

#### 6.5.2 Performance designations

#### 6.5.3 Performance cycles

### 6.6 Career levels, designation momentum, level splits, etc.

### 6.7 Creating specialized roles, like SRE or TPM

#### 6.7.1 Challenges

#### 6.7.2 Facilitating success

#### 6.7.3 Advantages

#### 6.7.4 What to do?

### 6.8 Designing an interview loop

## Chapter 7: Appendix

### 7.1 Tools for operating a growing organization

#### 7.1.1 Line management

#### 7.1.2 Middle management

#### 7.1.3 Managing an organization

### 7.2 Books I've found very useful
1.  _Thinking in Systems: A Primer_ by Donella Meadows
2. _Don't Think of an Elephant!: Know Your Values and Frame the Debate_ by George Lakoff
3. _Peopleware: Productive Projects and Teams_ by Tom DeMarco & Timothy Lister
4. _Slack: Getting Past Burnout, Busywork, and the Myth of Total Efficiency_ by Tom DeMarco
5. _Mythical Man-Month, Essays on Software Engineering_ by Frederick Brooks Jr.
6. _Good Strategy Bad Strategy: The Difference and Why it Matters_ by Richard Rumelt
7. _The Goal: A Process of Ongoing Improvement_ by Eliyahu M. Goldratt
8. _The Five Dysfunctions of a Team: A Leadership Fable_ by Patrick Lencioni
9. _The Three Signs of a Miserable Job_ by Patrick Lencioni
10. _Finite and Infinite Games_ by James Carse
11. _Inspired: How to Create Tech Products Customers Love_ by Marty Cagan
12. _The Innovator's Dilemma: When New Technologies Cause Great Firms to Fail (Management of Innovation and Change)_ by Clayton M. Christensen
13. _The E-Myth Revisited: Why Most Small Businesses Don't Work and What to Do About It_ by Michael E. Gerber
14. _Fierce Conversations: Achieving Success at Work & in Life, One Conversation at a Time_ by Susan Craig Scott 
15. _Becoming a Technical Leader: An Organic Problem-solving Approach_ by Gerald M. Weinberg
16. _Designing with the Mind in Mind: Simple Guide to Understanding User Interface Design Guidelines_ by Jeff Johnson
17. _The Leadership Pipeline: How to Build the Leadership Powered Company_ by Ram Charran, Steve Drotter, and Jim Noel
18. _The Manager's Path: A Guide for Tech Leaders Navigating Growth and Change_ by Camille Fournier
19. _High Output Management_ by Andrew S. Grove
20. _The First 90 Days: Proven Strategies for Getting Up to Speed Faster and Smarter_ by Michael D. Watkins
21. _The Effective Executive: The Definitive Guide to Getting the Right Things Done_ by Peter F. Drucker
22. _Don't Make Me Think: A Common Sense Approach to Web Usability_ by Steve Krug
23. _The Deadline: A Novel About Project Management_ by Tom DeMarco
24. _The Psychology of Computer Programming_ by Gerald M. Weinberg
25. _Adrenaline Junkies and Template Zombies: Understanding Patterns of Project Behavior_ by Tom DeMarco, Peter Hruschka, Tim Lister, Steve McMenamin, James Robertson, Suzanna Robertson
26. _The Secrets of Consulting: A Guide to Giving and Getting Advice Successfully_ by Gerald Weinberg
27. _Death by Meeting: A Leadership Fable About Solving the Most Painful Problem in Business_ by Patrick Lencioni
28. _The Advantage: Why Organizational Health Trumps Everything Else in Business_ by Patrick Lencioni
29. _Rise: 3 Practical Steps for Advancing Your Career, Standing Out as a Leader, and Liking Your Life_ by Patty Azzerello
30. _The Innovator's Solution: Creating and Sustaining Successful Growth_ by Clayton M. Christensen and Michael E. Raynor
31. _The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win_ by Gene Kim, Kevin Behr, and George Spafford
32. _Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations_ by Nicole Forsgren, Jez Humble, and Gene Kim

### 7.3 Papers I've found very useful
1. [Dynamo: Amazon’s Highly Available Key-value Store](./papers/1-dynamo-amazons-highly-available-key-value-store.pdf)
2. [Hints for Computer System Design](./papers/2-hints-for-computer-system-design.pdf)
3. [Big Ball of Mud](./papers/3-big-ball-of-mud.pdf)
4. [The Google File System](./papers/4-the-google-file-system.pdf)
5. [On Designing and Deploying Internet-Scale Services](./papers/5-designing-and-deploying-internet-scale-services.pdf)
6. [CAP Twelve years later: How the "Rules" have Changed](./papers/6-cap-12-years-later.pdf)
7. [Harvest, Yield, and Scalable Tolerant Systems](./papers/7-harvest-yield-and-scalable-tolerant-systems.pdf)
8. [MapReduce: Simplified Data Processing on Large Clusters](./papers/8-mapreduce-data-processing.pdf)
9. [Dapper, a Large-Scale Distributed Systems Tracing Infrastructure](./papers/9-dapper-systems-tracing.pdf)
10. [Kafka: a Distributed Messaging System for Log Processing ](./papers/10-kafka-distributed-messaging.pdf)
11. [Wormhole: Reliable Pub-Sub to Support Geo-replicated Internet Services](./papers/11-wormhold-pub-sub.pdf)
12. [Borg, Omega, and Kubernetes](./papers/12-borg-omega-kubernetes.pdf)
13. [Large-scale cluster management at Google with Borg](./papers/13-google-borg-cluster-management.pdf)
14. [Omega: flexible, scalable schedulers for large compute clusters](./papers/14-omega-scalable-schedulers.pdf)
15. [Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center](./papers/15-mesos-resource-sharing.pdf)
16. [Design patterns for container-based distributed systems](./papers/16-container-based-design-patterns.pdf)
17. [In Search of an Understandable Consensus Algorithm](./papers/17-raft-understandable-concensus-alg.pdf)
18. [Paxos Made Simple](./papers/18-paxos-simple.pdf)
19. [SWIM: Scalable Weakly-consistent Infection-style Process Group Membership Protocol](./papers/19-swim-process-groups.pdf)
20. [The Byzantine Generals](./papers/20-the-byz-generals.pdf)
21. [Out of the Tar Pit](./papers/21-out-of-the-tar-pit.pdf)
22. [The Chubby lock service for loosely-coupled distributed systems](./papers/22-chubby-lock-service.pdf)
23. [Bigtable: A Distributed Storage System for Structured Data](./papers/23-bigtable-distributed-storage.pdf)
24. [Spanner: Google’s Globally-Distributed Database](./papers/24-spanner-globally-distributed-db.pdf)
25. [Security Keys: Practical Cryptographic Second Factors for the Modern Web](./papers/25-security-keys.pdf)
26. [BeyondCorp: Design to Deployment at Google](./papers/26-beyondcorp-deployment-at-google.pdf)
27. [Availability in Globally Distributed Storage Systems](./papers/27-availability-in-distributed-storage.pdf)
28. [Still All on One Server: Perforce at Scale](./papers/28-perforce-at-scale.pdf)
29. [Large-Scale Automated Refactoring Using ClangMR](./papers/29-clang-mr-automated-refactoring.pdf)
30. [Source Code Rejuvenation is not Refactoring](./papers/30-rejuvenation-is-not-refactoring.pdf)
31. [Searching for Build Debt: Experiences Managing Technical Debt at Google](./papers/31-tech-debt-at-google.pdf)
32. [No Silver Bullet -- Essence and Accident in Software Engineering](./papers/32-no-silver-bullet.pdf)
33. [The UNIX Time- Sharing System](./papers/33-unix-time-sharing-system.pdf)
