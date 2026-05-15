# Free References for Sampling and Synthesis

Use these references for the sentence about the sampling rate needing to be at least twice the highest frequency component.

## 1. Shannon (recommended main citation)

Claude E. Shannon, *Communication in the Presence of Noise*, Proceedings of the IRE, 37(1), 10-21, 1949.

Link: https://www.math.unl.edu/~bdeng1/Teaching/math943/Topics/Genetics/Shannon1949.pdf

Why it fits:
- This is the canonical primary source that explicitly includes the sampling theorem.
- It is the best academic reference for the “twice the highest frequency” statement.

Suggested LaTeX:
```latex
According to the sampling theorem, a bandlimited signal can be perfectly reconstructed if it is sampled at a rate greater than twice its highest frequency component~\cite{shannon1949communication}.
```

## 2. Additive synthesis

Sean Luke, *Computational Music Synthesis*, first edition, 2021.

Free text: https://people.cs.gmu.edu/~sean/book/synthesis/

Why it fits:
- This is a free academic text hosted by the author.
- It has a dedicated additive synthesis chapter and is easy to access without a paywall.
- It is a safer choice than a paywalled book if you want the reference to be readable by anyone.

Suggested LaTeX:
```latex
Additive synthesis consists of generating a sound as the sum of sinusoidal components with individually controlled amplitudes and frequencies~\cite{luke2021computermusicsynthesis}.
```

## 3. Subtractive synthesis

Sean Luke, *Computational Music Synthesis*, first edition, 2021.

Free text: https://people.cs.gmu.edu/~sean/book/synthesis/

Why it fits:
- This is a free academic text hosted by the author.
- It has a dedicated subtractive synthesis chapter and directly describes filtering a harmonically rich waveform.
- It is openly accessible, which matches your requirement.

Suggested LaTeX:
```latex
Subtractive synthesis starts from a harmonically rich waveform and shapes it by filtering and modulation~\cite{luke2021computermusicsynthesis}.
```

## 4. ADSR envelope

Sean Luke, *Computational Music Synthesis*, first edition, 2021.

Free text: https://people.cs.gmu.edu/~sean/book/synthesis/

Why it fits:
- This free text has a specific ADSR section in the modulation chapter.
- It explains the attack, decay, sustain, and release stages in a way that matches your paragraph.
- It is openly accessible and consistent with the other synthesis references in this project.

Suggested LaTeX:
```latex
An ADSR envelope is a multiplicative amplitude function commonly used to shape the temporal evolution of a synthesized sound~\cite{luke2021synthesis}.
```
