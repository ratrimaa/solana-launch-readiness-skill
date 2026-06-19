# Solana Launch Readiness Skill

AI-powered launch advisor for Solana founders, builders, operators, and startup teams.

## Problem

Many Solana projects successfully deploy their smart contracts but still fail during or shortly after launch.

Common causes include:

* Missing monitoring and alerting
* Poor incident response planning
* Single points of failure in authority management
* Incomplete documentation
* Lack of operational ownership
* Weak launch preparation
* Insufficient support readiness

Most existing tools focus on development or security auditing. Very few help teams answer a much broader question:

**"Are we actually ready to launch?"**

## Solution

Solana Launch Readiness Skill transforms an AI coding agent into a launch advisor capable of evaluating launch readiness across multiple domains.

The skill combines:

* Technical infrastructure review
* Security readiness review
* Operations readiness review
* Documentation assessment
* Community and launch preparation review

The result is a structured readiness score with actionable recommendations.

---

## Key Features

### Launch Readiness Score

Generate a weighted readiness score from 0-100.

Categories:

* Technical Infrastructure (30%)
* Security (30%)
* Operations (20%)
* Documentation (10%)
* Community & GTM (10%)

---

### Technical Readiness Assessment

Evaluate:

* Program deployment status
* Testnet validation
* RPC redundancy
* Monitoring
* Alerting
* Infrastructure ownership

---

### Security Readiness Assessment

Evaluate:

* Upgrade authority configuration
* Multisig adoption
* Key management
* Dependency risks
* Security review status

---

### Operations Readiness Assessment

Evaluate:

* Incident response plans
* Escalation procedures
* Service ownership
* Support readiness
* Recovery procedures

---

### Documentation Review

Evaluate:

* User onboarding
* FAQs
* Troubleshooting guides
* Developer documentation

---

### Founder Mode

Review a project from a founder and launch-operator perspective.

Example:

"Review my startup before launch."

---

### Investor Due Diligence Mode

Review a project from an investor perspective.

Example:

"Would this project pass technical due diligence?"

---

### Post-Mortem Simulator

Predict likely causes of failure before launch.

Example:

"Assume this project failed 30 days after launch. What most likely caused it?"

---

## Example Output

Launch Readiness Score: 82/100

Technical: 28/30

Security: 24/30

Operations: 15/20

Documentation: 8/10

Community: 7/10

Critical Issues:

* Upgrade authority controlled by a single wallet
* No RPC failover configured

Recommendations:

* Move authority to a multisig
* Configure secondary RPC provider
* Publish incident response process

Launch Recommendation:
Proceed after critical issues are resolved.

---

## Repository Structure

```text
skill/
├── SKILL.md
├── technical-readiness.md
├── security-readiness.md
├── operations-readiness.md
├── launch-checklist.md
├── incident-response.md
├── documentation-review.md
└── scoring-framework.md

commands/
├── launch-audit.md
├── readiness-score.md
└── launch-report.md

agents/
└── launch-advisor.md
```

---

## Example Commands

/launch-audit

Generate a complete launch readiness assessment.

---

/readiness-score

Generate a readiness score.

---

/launch-report

Generate a detailed launch report.

---

## Why This Skill Matters

Launching is one of the highest-risk events in a project's lifecycle.

This skill helps teams identify launch blockers before they become production incidents.

It bridges the gap between:

* Development
* Security
* Operations
* Documentation
* Launch execution

into a single workflow.

---

## Roadmap

### v1

* Launch scoring framework
* Readiness assessment
* Launch reporting

### v2

* Monitoring readiness integrations
* RPC provider assessment

### v3

* Multisig readiness checks
* Automated launch report generation

### v4

* Ecosystem-specific launch templates

---

## License

MIT
