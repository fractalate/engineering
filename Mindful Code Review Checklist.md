# Mindful Code Review Checklist

*Tuesday, March 26, 2024 - Revision 1*

This questionnaire is designed to be used when you are reviewing code. You might use this when reviewing an entire project you're not familiar with or while evaluating a pull request for your own project on GitHub.

## Gather Context

Before considering the code deeply, gain an understanding of the context in which the software is used and developed.

* What kind of computer systems run the software?
* What languages and tools are used to build the software?
* What libraries does the software use?
* What ecosystems does this software exist within?
* What relevant direction is outlined for the software?
* Who are the intended users of the software?
* What other systems does the software integrate with and how?

## Evaluate Intent

* Identify the system integrations affected by the change.
* Identify the intended outcomes of the change.
* Does the change make a sound attempt to produce the intended outcomes?
* Does the change produce any unintended outcomes?

## Evaluate Code Structure

* Is the code clear?
* Does the code follow industry conventions/best-practices and/or is it consistent with project conventions?

## Evaluate Operational Fitness

* Does the changed software produce error reports suitable for the user/operator of the software to research and identify the cause?

## Evaluate Maintainability

* Is the relevant documentation updated?
* Are relevant tests added or updated?
* Are there others who can readily work on the areas changed?

## Evaluate Deployability

* If there is a standard deployment/upgrade process, does that process work for these changes?
* If there is a custom deployment/upgrade process, does the change include a deployment/upgrade plan?
