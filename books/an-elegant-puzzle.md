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

### 3.1 Introduction to systems thinking

#### 3.1.1 Stocks and flows

#### 3.1.2 Developer velocity

#### 3.1.3 Model away

### 3.2 Product management: exploration, selection, validation

#### 3.2.1 Problem discovery

#### 3.2.2 Problem selection

#### 3.2.3 Solution validation

### 3.3 Visions and strategies

#### 3.3.1 Strategies and visions

#### 3.3.2 Strategy

#### 3.3.3 Vision

### 3.4 Metrics and baselines

### 3.5 Guiding broad organization change with metrics

### 3.6 Migrations: the sole scalable fix to tech debt

#### 3.6.1 Why migrations matter

#### 3.6.2 Running good migrations

### 3.7 Running an engineering reorg

#### 3.7.1 Is a reorg the right tool?

#### 3.7.2 Project head count a year out

#### 3.7.3 Manager-to-engineer ratio

#### 3.7.4 Defining teams and groups

#### 3.7.5 Staffing the teams and groups

#### 3.7.6 Commit to moving forward

#### 3.7.7 Roll out the change

### 3.8 Identify your controls

### 3.9 Career narratives

#### 3.9.1 Artificial competition

#### 3.9.2 Translating goals

### 3.10 The briefest of media trainings

### 3.11 Model, document, and share

#### 3.11.1 How it works

#### 3.11.2 Where it works

### 3.12 Scaling consistency: designing centralized decision-making groups

#### 3.12.1 Positive and negative freedoms

#### 3.12.2 Group design

#### 3.12.3 Failure modes

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

### 7.3 Papers I've found very useful
