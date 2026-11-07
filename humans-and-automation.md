# Humans and automation

[← Back](README.md)

A model in a workflow is automation, and the human-factors field studied what automation
does to the person next to it for forty years before anyone called that person a
"human in the loop". Read the classics first; the recent work mostly rediscovers them.

## The classics

1. [Ironies of Automation](https://doi.org/10.1016/0005-1098(83)90046-8) (Bainbridge, 1983)
   - *Why*: Automating the easy parts leaves the human with the hard parts, less practised
     and with less context. Four pages. The single most useful thing to read before
     designing an analyst's console that "lets the AI handle the routine cases".

2. [Toward a Theory of Situation Awareness in Dynamic Systems](https://doi.org/10.1518/001872095779049543) (Endsley, 1995)
   - *Why*: Perception, comprehension, projection. The three levels are the checklist for
     whether an interface tells the operator what is going on, or only what happened.

3. [A Model for Types and Levels of Human Interaction with Automation](https://doi.org/10.1109/3468.844354) (Parasuraman, Sheridan and Wickens, 2000)
   - *Why*: Automation is not one dial. Information acquisition, analysis, decision
     selection and action implementation can each be automated to a different level, and
     the right level differs per stage. The framework for saying exactly what a model is
     allowed to do.

4. [Trust in Automation: Designing for Appropriate Reliance](https://doi.org/10.1518/hfes.46.1.50_30392) (Lee and See, 2004)
   - *Why*: The goal is not trust; it is trust calibrated to actual reliability. Overtrust
     and distrust are both failures, and the design decides which one you get.

## When the automation is a model

5. [The Principles and Limits of Algorithm-in-the-Loop Decision Making](https://doi.org/10.1145/3359152) (Green and Chen, 2019)
   - *Why*: People given a risk score did not become better judges of risk; they became
     worse in predictable ways. The experiment that should temper every "the human
     reviews the model's output" design.

6. [To Trust or to Think: Cognitive Forcing Functions Can Reduce Overreliance on AI in AI-assisted Decision-making](https://doi.org/10.1145/3449287) (Buçinca, Malaya and Gajos, 2021)
   - *Why*: Explanations alone did not stop people from accepting wrong answers. Making
     them think first did, and they liked it less. Design for the behaviour, not the
     preference.

7. [Does the Whole Exceed its Parts? The Effect of AI Explanations on Complementary Team Performance](https://doi.org/10.1145/3411764.3445717) (Bansal et al., 2021)
   - *Why*: The human-plus-model team rarely beat the model alone, and explanations made
     people agree with the model whether it was right or wrong. If the claim is
     "complementary", this is the bar.

## Why people adopt a tool at all

8. [Perceived Usefulness, Perceived Ease of Use, and User Acceptance of Information Technology](https://doi.org/10.2307/249008) (Davis, 1989)
   - *Why*: Two variables explain most of whether people use a system. Every internal tool
     that was correct and unused failed on the second one.

9. [User Acceptance of Information Technology: Toward a Unified View](https://doi.org/10.2307/30036540) (Venkatesh, Morris, Davis and Davis, 2003)
   - *Why*: The consolidation of eight acceptance models into one. Useful as a checklist
     when asking why a team will not pick up the thing you built for them.
