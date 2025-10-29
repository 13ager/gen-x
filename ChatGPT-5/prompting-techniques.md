# GPT-5 Prompting Playbook for Senior Leaders v3

> **How to think *with*, not just *through*, AI**  
> A tactical guide for Gen X executives who remember when "CC" meant carbon copy  
> *Now with Tree-of-Thought, Chain-of-Thought, Reflexion, and other computational patterns that matter*

---

## Why This Matters Now

You've survived the shift from memos to email, desktop to cloud, and waterfall to agile. This isn't another tech transition—it's a cognitive multiplier. GPT-5 isn't your intern; it's your sparring partner. Master these patterns, and you'll operate like you have a strategy team on demand, 24/7.

**Core principle**: Precision in, precision out. Vague asks get fortune-cookie wisdom.

---

## The Essential Ten

### 1. Structured Reasoning for Complex Problems (Chain-of-Thought)

**Pattern:**
```
You are a [specific role with expertise].
Break this problem into logical steps before giving your final recommendation.
Think deliberately and show your work.
```

**Live Example:**
```
You are a Chief Revenue Officer with 20 years in enterprise SaaS.
Break down how to pivot our outbound sales motion to product-led growth 
without tanking Q3 pipeline. Consider: comp plans, team structure, and 
customer success handoffs. Show your reasoning, then give me the 90-day plan.
```

**Why it works:** Forces systematic thinking vs. GPT's tendency to leap to conclusions. You get the logic chain, not just the answer. This is "Chain-of-Thought" prompting—making AI think like you do in strategic planning sessions.

---

### 2. Draft → Debrief → Deliver (Reflexion)

**Pattern:**
```
First, produce your best answer.
Then critique it like a [skeptical stakeholder].
Finally, rewrite addressing every weakness you found.
```

**Live Example:**
```
Draft a board memo explaining why we're killing our most profitable product line.
Then critique it as our most skeptical board member would.
Finally, rewrite it to pre-empt those concerns.
```

**Why it works:** Mimics the review cycles you already do, but in seconds. No more "I should have anticipated that question." This is "Reflexion" in action—AI improving its own output through self-critique.

---

### 3. Role + Objective + Constraints (The Trinity)

**Pattern:**
```
You are [expert role].
Your goal: [specific measurable objective].
Constraints: [list hard boundaries].
```

**Live Example:**
```
You are our General Counsel.
Your goal: Draft an AI usage policy that protects IP without stifling innovation.
Constraints: 500 words max, plain English (8th-grade level), implementable tomorrow.
```

**Why it works:** Constraints breed creativity. Also prevents GPT from writing a doctoral thesis when you need a decision doc.

---

### 4. Progressive Deepening

**Pattern:**
```
Level 1: Give me the executive summary of [topic].
Level 2: Now drill into the most critical component with data.
Level 3: Give me three non-obvious implications.
```

**Live Example:**
```
Level 1: Executive summary of how GenAI impacts our consulting business model.
Level 2: Deep dive on the pricing/margin implications with benchmarks.
Level 3: Three second-order effects our competitors haven't considered yet.
```

**Why it works:** Matches how senior leaders actually consume information—headline, then selective deep dives.

---

### 5. The Synthesis Engine

**Pattern:**
```
Input 1: [paste document/data]
Input 2: [different source]
Task: Synthesize into [specific format] highlighting [what matters].
```

**Live Example:**
```
Input 1: Last quarter's customer churn data
Input 2: Product roadmap for next 6 months
Task: Create a one-page retention strategy linking specific features to churn drivers. 
Use a simple table showing Feature → Churn Factor → Expected Impact.
```

**Why it works:** GPT-5 excels at pattern-matching across disparate inputs—like having McKinsey's research team on tap.

---

### 6. Scenario Branching

**Pattern:**
```
Here's our situation: [context].
Map out three scenarios: pessimistic, realistic, optimistic.
For each, give me key indicators to watch and trigger points for action.
```

**Live Example:**
```
Situation: We're considering a $50M Series B in this market.
Map three funding scenarios with different valuations and dilution.
Include warning signals for each path and decision triggers for pivoting.
```

**Why it works:** Builds your peripheral vision for strategic optionality—crucial when markets shift fast.

---

### 7. The Bezos Method (Work Backwards)

**Pattern:**
```
End state: [desired outcome with specifics].
Work backwards to create the plan.
Include dependencies and risk points.
```

**Live Example:**
```
End state: By Dec 2025, we're the recognized thought leader in AI governance,
measured by 3 tier-1 speaking invitations and 2 board advisor roles.
Work backwards to build the 18-month authority-building campaign.
```

**Why it works:** Starts with clarity on success, then reverse-engineers the path—avoiding activity without progress.

---

### 8. Cognitive Diversity Simulator

**Pattern:**
```
Analyze this [decision/strategy] from three perspectives:
1. [Stakeholder 1]: Their priorities and concerns
2. [Stakeholder 2]: Their priorities and concerns  
3. [Stakeholder 3]: Their priorities and concerns
Then integrate into a balanced recommendation.
```

**Live Example:**
```
Analyze our remote-first policy from:
1. CFO: Cost and productivity metrics
2. CHRO: Talent retention and culture
3. Individual contributors: Career development and work-life balance
Integrate into a policy that addresses all three.
```

**Why it works:** Prevents blind spots from single-lens thinking. Like having your entire C-suite in one prompt.

---

### 9. The Stress Test

**Pattern:**
```
Here's my [strategy/plan/argument].
Play devil's advocate aggressively.
Find three ways it could catastrophically fail.
Then tell me how to hedge against each.
```

**Live Example:**
```
Strategy: We're moving all customer data to a single cloud provider for efficiency.
Attack this plan like you're our Chief Risk Officer after three espressos.
Give me the disaster scenarios and mitigation tactics.
```

**Why it works:** Better to find holes in private with GPT than public with your board.

---

### 10. The Clarity Refinery

**Pattern:**
```
Here's my rough thinking: [brain dump].
Transform this into:
1. Core message (one sentence)
2. Three supporting points
3. One compelling metaphor
4. Call to action
```

**Live Example:**
```
Rough thinking: We need to somehow get sales and product to stop fighting 
about roadmap priorities while also making customers happy but not 
over-promising and maybe we need better processes or different meetings...

Transform into a crisp all-hands message.
```

**Why it works:** Turns executive stream-of-consciousness into communication that lands.

---

## Technical Foundations

*The computational patterns that power executive thinking—now yours to command*

### Tree-of-Thought (Parallel Strategic Exploration)

**Pattern:**
```
I need to make a decision about [strategic choice].
Explore these paths simultaneously:
- Path A: [approach with assumptions]
- Path B: [different approach]
- Path C: [third approach]

For each path:
1. Map outcomes at 3, 6, 12 months
2. List dependencies and failure points
3. Calculate resources (time, money, people)
4. Score on: ROI, risk, strategic alignment

Compare all three, then recommend with rationale for why you rejected the others.
```

**Live Example:**
```
Decision: How to enter the enterprise market with our SMB product.
Path A: Enterprise-specific product fork
Path B: Premium tier with enterprise features
Path C: Acquisition of enterprise competitor

[Full analysis per above]
Recommend with explicit rejection reasoning.
```

**Why it works:** Unlike human thinking that follows one thread, GPT can hold multiple strategic branches in parallel—like running three board meetings simultaneously.

---

### Prompt Chaining (Multi-Stage Workflows)

**Pattern:**
```
Chain of 4 prompts where each output feeds the next:
Prompt 1: [First task] → Output A
Prompt 2: Using Output A, [Second task] → Output B
Prompt 3: Using Output B, [Third task] → Output C
Prompt 4: Using Output C, [Final deliverable]
```

**Live Example:**
```
Prompt 1: List our top 5 competitive vulnerabilities
Prompt 2: Using that list, design defensive strategies for each
Prompt 3: Using those strategies, create resource allocation plan
Prompt 4: Using that plan, draft board presentation with trade-offs
```

**Why it works:** Mimics how senior teams actually work—each meeting builds on the last, but compressed into minutes.

---

### ReAct (Reason → Act → Observe)

**Pattern:**
```
Task: [What you need to accomplish]
Step 1 - Reasoning: Think through how to approach this
Step 2 - Action Plan: List specific steps you'll take
Step 3 - Execute: Perform each step, showing work
Step 4 - Observe: Assess results and adjust if needed
Step 5 - Deliver: Final output with confidence level
```

**Live Example:**
```
Task: Determine if we should sunset our legacy product

Step 1 - Reasoning: Need to analyze revenue, costs, strategic fit, and migration path
Step 2 - Action Plan: 
  a) Calculate revenue contribution and trajectory
  b) Assess technical debt and maintenance burden
  c) Map customer dependencies
  d) Design migration strategy
Step 3 - Execute: [Shows each analysis]
Step 4 - Observe: Migration risk higher than expected, need phased approach
Step 5 - Deliver: Recommend 18-month sunset with three phases
```

**Why it works:** Makes reasoning transparent and adjustable—like having your strategy team show their homework.

---

### Generate Knowledge (Domain Expertise On-Demand)

**Pattern:**
```
Explain [concept/framework/technique] with:
1. Core definition (one paragraph)
2. Key components (numbered list)
3. Real-world application example
4. Common mistakes to avoid
5. How to measure success
```

**Live Example:**
```
Explain "Jobs-to-be-Done" framework with:
1. Core definition
2. Key components
3. Real example from B2B SaaS
4. Common mistakes product teams make
5. KPIs to track progress
```

**Why it works:** Instant expertise transfer—like having Clayton Christensen on speed dial.

---

### RAG Pattern (Real-Time Intelligence)

**Pattern:**
```
Research current information on [topic].
Sources: Look for data from last [timeframe]
Synthesis: Combine findings to answer [specific question]
Perspective: Analyze through lens of [your context]
Recommendation: Action items based on current landscape
```

**Live Example:**
```
Research current state of AI regulation in financial services.
Sources: Last 90 days of regulatory announcements
Synthesis: What compliance requirements are emerging?
Perspective: We're a fintech with AI-driven underwriting
Recommendation: Compliance roadmap for next 6 months
```

**Why it works:** Bridges the gap between GPT's training data and today's reality—essential for time-sensitive decisions.

---

## Advanced Patterns

### The Canonical Reference

Build a "source of truth" context that persists across prompts:

```
For all responses in this chat, assume:
- Company: B2B SaaS, $50M ARR, 200 employees
- Market: Competitive, 15% annual growth
- Challenge: Scaling without losing agility
- North Star: IPO-ready in 24 months
```

### The Expertise Ladder

When you need deep technical insight:

```
Explain [complex topic] at three levels:
1. Board level (strategic implications)
2. VP level (operational requirements)
3. Engineer level (implementation details)
Flag the transitions between levels.
```

### The What-If Machine

For strategic planning:

```
Starting position: [current state]
Variable to change: [specific factor]
Map out implications if this variable moves to:
- 50% of current
- 200% of current
- Goes to zero
Include second-order effects.
```

---

## Common Pitfalls & Fixes

| Pitfall | Fix |
|---------|-----|
| Getting generic MBA-speak | Add "Be specific with examples from [industry]" |
| Too much hedging ("it depends") | Add "Take a position and defend it" |
| Overwhelming detail | Add "Executive summary first, then support" |
| Missing nuance | Add "Consider edge cases and exceptions" |
| Dated references | Add "Use examples from 2024-2025" |
| Single-path thinking | Use Tree-of-Thought: "Explore multiple approaches simultaneously" |
| Losing context in chains | Add "Carry forward key context: [essentials]" between prompts |
| Shallow knowledge transfer | Use Generate Knowledge: "Include implementation details and metrics" |
| Stale data assumptions | Use RAG: "Search for current data on this topic first" |

---

## The Meta-Prompt

When stuck, use this:

```
I have a fuzzy goal around [topic].
Help me convert this into a precise prompt that will get me 
a useful answer. Ask me clarifying questions if needed.
```

---

## Quick Reference Card

### By Situation
**For Strategy**: Tree-of-Thought, Progressive Deepening, or Scenario Branching  
**For Communication**: Draft → Debrief → Deliver or Clarity Refinery  
**For Decision-Making**: Tree-of-Thought, Stress Test, or Cognitive Diversity Simulator  
**For Planning**: Bezos Method, ReAct, or What-If Machine  
**For Problem-Solving**: Structured Reasoning (Chain-of-Thought) or Synthesis Engine  
**For Workflows**: Prompt Chaining or ReAct  
**For Learning**: Generate Knowledge or Progressive Deepening  
**For Current Events**: RAG Pattern or Synthesis Engine with recent data

### By Thinking Style
**Linear thinkers**: Chain-of-Thought, ReAct, Prompt Chaining  
**Parallel processors**: Tree-of-Thought, Scenario Branching  
**Critics**: Stress Test, Reflexion (Draft → Debrief → Deliver)  
**Synthesizers**: RAG Pattern, Synthesis Engine  
**Explorers**: Generate Knowledge, What-If Machine  

---

## Remember

You learned to code in BASIC, built companies through the dot-com bust, and figured out social media when it was still called "Web 2.0." This is just another tool in your arsenal—but one that amplifies judgment rather than replacing it.

The executives who master these patterns won't just survive the AI transition; they'll lead it.

---

*Want to contribute improvements? PRs welcome. Written by humans who remember dial-up, refined by AI that doesn't.*

---

### License

MIT License - Use freely, attribution appreciated.

### Author

Originally created for saren.ai senior leader workshops. 
Refined through real-world application with Fortune 500 executives.

### Version

v03 10/29/2025
v3.0 - Comprehensive edition with technical patterns integrated (January 2025)  
v2.0 - Updated for GPT-5 capabilities  
v1.0 - Original GPT-4 version
