# Security principles

[← Back](README.md)

The small set of ideas that security design keeps returning to, and two papers on why the
numbers we put on vulnerabilities are less solid than they look.

## Design

1. [The Protection of Information in Computer Systems](https://web.mit.edu/Saltzer/www/publications/protection/) (Saltzer and Schroeder, 1975)
   - *Why*: Economy of mechanism, fail-safe defaults, complete mediation, open design,
     separation of privilege, least privilege, least common mechanism, psychological
     acceptability. Fifty years on, a system that violates one of these is usually the
     system that got breached. The author's own copy is free.

2. [Measuring Relative Attack Surfaces](https://www.cs.cmu.edu/~wing/publications/Howard-Wing05.pdf) (Howard, Pincus and Wing, 2005)
   - *Why*: "Attack surface" as something you can count rather than a feeling. Entry
     points, channels, untrusted data; compare two versions of a system and say which
     exposes less.

3. [Secure by Design](https://www.cisa.gov/securebydesign) (CISA, 2023 onward)
   - *Why*: The current public statement of what a vendor owes its users: defaults that
     are safe, ownership of security outcomes, and transparency. Read with Saltzer and
     Schroeder to see how little the principles moved and how much the audience did.

## Privacy

4. [A Taxonomy of Privacy](https://scholarship.law.upenn.edu/penn_law_review/vol154/iss3/1/) (Solove, 2006)
   - *Why*: "Privacy" is sixteen distinct harms grouped under information collection,
     processing, dissemination, and invasion. The vocabulary for saying which one a system
     actually threatens, instead of waving at the word.

## Scoring vulnerabilities

5. [An expert-based investigation of the Common Vulnerability Scoring System](https://doi.org/10.1016/j.cose.2015.04.012) (Holm and Afridi, 2015)
   - *Why*: Experts given the same vulnerability do not produce the same CVSS vector. The
     first careful look at how much of a score is the vulnerability and how much is the
     scorer.

6. [Shedding Light on CVSS Scoring Inconsistencies: A User-Centric Study on Evaluating Widespread Security Vulnerabilities](https://doi.org/10.1109/SP54263.2024.00058) (Wunder, Kurtz, Eichenmüller, Gassmann and Benenson, 2024)
   - *Why*: The same finding at scale, a decade later, with the metrics that disagree most
     named. Required before building anything that ranks by CVSS, or that replaces it.
