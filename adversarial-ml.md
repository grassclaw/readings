# Adversarial machine learning

[← Back](README.md)

Four papers that established that a learned model can be steered by its input, and two
living catalogues that name the attacks in practice. The full research curriculum lives in
[kitsumiko/papers](https://github.com/kitsumiko/papers), in the Safety and Security area.

## The papers

1. [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) (Goodfellow, Shlens and Szegedy, 2015)
   - *Why*: Adversarial examples are not a curiosity of one architecture; they follow from
     linear behaviour in high dimensions. The fast gradient sign method is still the first
     attack anyone tries.

2. [The Limitations of Deep Learning in Adversarial Settings](https://arxiv.org/abs/1511.07528) (Papernot, McDaniel, Jha, Fredrikson, Celik and Swami, 2016)
   - *Why*: The attacker's view: which features to change and by how much to reach a chosen
     wrong answer. The paper that made "adversarial" a threat model instead of a property.

3. [Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644) (Carlini and Wagner, 2017)
   - *Why*: Defensive distillation, the defence of the day, broken; and a set of attacks
     strong enough that "robust" has meant "robust to Carlini-Wagner" ever since. Also the
     template for how to evaluate a defence honestly.

4. [Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning](https://arxiv.org/abs/1712.03141) (Biggio and Roli, 2018)
   - *Why*: The field's own history, including the decade of security work on evasion and
     poisoning that predated deep learning and gets forgotten. Read it to stop
     rediscovering 2006.

## The catalogues

5. [MITRE ATLAS](https://atlas.mitre.org/) (MITRE)
   - *Why*: The ATT&CK-shaped matrix for attacks on machine-learning systems, with case
     studies. The shared vocabulary when a security team and a model team have to talk.

6. [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/) (OWASP, 2025 edition)
   - *Why*: Prompt injection, data poisoning, excessive agency and the rest, as a list a
     reviewer can actually walk. Where a language-model deployment review starts.
