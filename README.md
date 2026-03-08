# AI Hiring Checklist ✅

> Stop the 87% failure rate. A practical checklist for hiring AI/ML developers who actually ship.

Most AI projects fail — not because of the technology, but because of hiring mistakes. This checklist helps you find, vet, and onboard AI talent the right way.

---

## 🔴 Before You Post a Job

- [ ] Can you describe the problem in one sentence? (Not the AI solution — the *problem*)
- [ ] Do you have a measurable success metric? ("improve accuracy" ≠ success metric)
- [ ] Is your data clean, labeled, and accessible?
- [ ] Have you done a simple baseline (rules-based, SQL query, manual process)?
- [ ] Do you know if you need ML, fine-tuning, RAG, or just prompting?

> **If you can't answer all 5, you're not ready to hire yet. Define these first.**

---

## 🟡 Evaluating AI Developer Candidates

### Technical Screen (30 min)
- [ ] Can they explain their last project's data pipeline end-to-end?
- [ ] Have they deployed a model to production (not just trained one)?
- [ ] Ask: "How would you handle data drift after deployment?" — vague answers = red flag
- [ ] Ask: "What would make you recommend NOT using AI for this problem?" — good devs know the limits
- [ ] Can they write a basic data cleaning script on the spot?

### Portfolio Review
- [ ] Look for GitHub repos with actual commit history (not just imported projects)
- [ ] Ask for a live demo, not just screenshots
- [ ] Check if they can explain tradeoffs (why this model vs. alternatives?)
- [ ] Look for evidence of handling production issues, not just happy-path demos

### Red Flags 🚩
- Claims expertise in every ML domain
- Portfolio is all Jupyter notebooks with no deployment
- Can't explain why accuracy/F1/AUC matters differently in different contexts
- "We just need more data" is their answer to everything
- No experience with data versioning or experiment tracking

---

## 🟢 Structuring the Engagement

### Project Setup
- [ ] Start with a **2-4 week paid POC** — not a 6-month contract
- [ ] Define what "done" looks like *before* day 1
- [ ] Agree on how model performance will be measured
- [ ] Set up a shared experiment tracking tool (MLflow, Weights & Biases, etc.)
- [ ] Establish data access and security protocols in writing

### Week-by-Week Milestones (POC)
- **Week 1:** Data exploration + baseline model
- **Week 2:** Improved model + performance benchmarks
- **Week 3:** Basic deployment (API or batch job)
- **Week 4:** Documentation + handoff

### Go/No-Go Decision
- [ ] Does the POC beat your baseline by a meaningful margin?
- [ ] Can the dev explain *why* it works (not just that it does)?
- [ ] Is the code readable and maintainable without them?
- [ ] Are you confident scaling this to production?

---

## 💰 Rates (2025 Market Data)

| Role | Hourly Range | When to Hire |
|------|-------------|--------------|
| AI Generalist | $80-120/hr | POC phase, greenfield |
| ML Engineer | $100-150/hr | Production deployment |
| Data Engineer | $80-130/hr | Pipeline/infrastructure |
| LLM Specialist | $120-180/hr | Fine-tuning, RAG, agents |
| AI Architect | $150-250/hr | System design, scale |

> **Rule of thumb:** Start junior-to-mid for POCs. Bring in seniors when you're ready to scale.

---

## 📋 Contract Template (Key Clauses)

- [ ] IP ownership: specify who owns the model weights, training data, code
- [ ] Data security: NDA + data handling protocols
- [ ] Milestone payments: tie payment to deliverables, not time
- [ ] Non-compete: standard 6-month in your core domain
- [ ] Knowledge transfer: require documentation and handoff sessions

---

## 🔍 Where to Find AI Talent

| Platform | Best For | Quality Signal |
|----------|----------|---------------|
| [RevolutionAI](https://www.revolutionai.io) | AI/ML-specific hiring | All freelancers pre-vetted for AI expertise |
| Toptal | Senior generalists | Rigorous screening |
| Upwork | Wide range | High variance — screen carefully |
| LinkedIn | Direct outreach | Best for full-time or long-term |
| GitHub | Open source contributors | Find people who build in public |

---

## 🧠 Interview Questions That Actually Work

**For ML Engineers:**
1. "Walk me through how you'd debug a model that performed well in training but poorly in production."
2. "What's your process when you receive a new dataset you've never seen before?"
3. "Describe a time you recommended NOT using ML for a problem. What did you suggest instead?"

**For LLM/GenAI Specialists:**
1. "How would you evaluate whether a RAG system is hallucinating vs. not finding the answer?"
2. "Walk me through prompt caching and when you'd use it."
3. "What's your approach to reducing LLM costs in production?"

**For Data Engineers:**
1. "How do you handle schema changes in production data pipelines?"
2. "What's your approach to data quality monitoring?"
3. "Describe your ideal orchestration setup for a batch ML pipeline."

---

## 📖 Resources

- [ML Project Failure Patterns](https://www.revolutionai.io/blog/why-ai-projects-fail-2026) — deep dive on the 87% stat
- [Find vetted AI talent → RevolutionAI](https://www.revolutionai.io)

---

## Contributing

Found a question that separates great AI devs from pretenders? Open a PR. 

This checklist is maintained by [RevolutionAI](https://www.revolutionai.io) — the marketplace for AI/ML freelancers.

---

⭐ Star this if it saved you from a bad hire. Share it with a founder who's about to post "AI developer needed" on Fiverr.
