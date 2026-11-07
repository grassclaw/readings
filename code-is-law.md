# Code is law

[← Back](README.md)

The architecture of a system regulates the people inside it. Lessig said it first in these
words; others said it before him in other words, and the people after him turned it into
a practice. The order below is the order to read them in.

## Before Lessig

1. [Lex Informatica: The Formulation of Information Policy Rules through Technology](https://ir.lawnet.fordham.edu/faculty_scholarship/42/) (Reidenberg, 1998)
   - *Why*: The year before *Code*, Reidenberg argued that technical standards and system
     design are a source of policy rules in their own right, with their own jurisdiction.
     Read it to see the idea arrive without the slogan.

## Lessig

2. [Code: And Other Laws of Cyberspace](https://codev2.cc/) (Lessig, 1999; *Code v2*, 2006, free online)
   - *Why*: The origin. Four things regulate behaviour: law, norms, markets, and
     architecture. Architecture in software is code, and whoever writes the code sets rules
     nobody voted on. Everything I build that enforces a policy in software owes this book
     the question "who wrote this rule, and can it be seen?"

3. [Open Code and Open Societies: Values of Internet Governance](https://scholarship.kentlaw.iit.edu/cklawreview/vol74/iss3/8/) (Lessig, 1999)
   - *Why*: The companion essay. If code regulates, then closed code is regulation you
     cannot read. Open code is not a licensing preference here; it is a condition for
     governance you can inspect.

## After Lessig

4. [Open Code Governance](https://chicagounbound.uchicago.edu/uclf/vol2008/iss1/9/) (Citron, 2008)
   - *Why*: Takes Lessig's open-code argument into public administration: when agencies
     automate decisions, closed systems defeat the procedural protections the law assumes.
     The case for auditable systems, made before anyone said "algorithmic accountability".

5. [Regulating Code: Good Governance and Better Regulation in the Information Age](https://mitpress.mit.edu/9780262018821/regulating-code/) (Brown and Marsden, 2013)
   - *Why*: The regulator's side. Case studies of how states and standards bodies shape
     code, and what "better regulation" means when the thing regulated is software.

6. [The Expansion of Algorithmic Governance: From Code is Law to Law is Code](https://journals.openedition.org/factsreports/4518) (Hassan and De Filippi, 2017)
   - *Why*: The inversion. Smart contracts and automated enforcement turn law into code
     that executes. Short, clear, and the best single statement of the step from "code
     regulates" to "regulation is code".

## The counterweight

7. [To Save Everything, Click Here: The Folly of Technological Solutionism](https://www.publicaffairsbooks.com/titles/evgeny-morozov/to-save-everything-click-here/9781610391397/) (Morozov, 2013)
   - *Why*: If code is law, then "fix it with code" is legislation without a legislature.
     Morozov is the reminder that encoding a rule is a political act with costs, and that
     the fix often defines the problem to suit itself.

## Where the idea is practised now

8. [Open Policy Agent and the Rego policy language](https://www.openpolicyagent.org/docs/latest/policy-language/) (Cloud Native Computing Foundation)
   - *Why*: Policy as code, as it is actually written today. Read the language docs once to
     see what "law is code" looks like when it has a type system and a test suite.

9. [Open Security Controls Assessment Language (OSCAL)](https://pages.nist.gov/OSCAL/) (NIST)
   - *Why*: Security controls as machine-readable data: catalogues, profiles, system
     plans, assessment results. The format a compliance rule has to be in before any
     automation can act on it.

10. [Normative requirements for regulatory compliance: An abstract formal framework](https://doi.org/10.1007/s10796-015-9558-1) (Hashmi, Governatori and Wynn, 2016)
    - *Why*: The formal version. What has to be true of a "rule" before compliance with it
      can be checked by a machine; obligations, permissions, violations and their
      lifecycles, stated precisely.
