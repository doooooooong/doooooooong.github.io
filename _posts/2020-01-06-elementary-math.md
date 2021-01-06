---
layout: post
title: "기초수학"
date: 2020-01-06 23:59:29 +0900
categories: sample
---

기초수학

1. logarithms

$$
X = a^b, \ \  b = log_aX
$$

- $$
  log \ ab = log \ a + log \ b
  $$

- $$
  log \ \frac a b = log \ a - log \ b
  $$

- $$
  log \ a^b = b \ log \ a
  $$

- $$
  log_an = \frac {log_bn} {log_ba} = \frac {log \ n} {log \ a}
  $$

- $$
  log_aa = 1, for \ all \ a > 0 \\
  log_a1 = 0, for \ all \ a > 0
  $$

2.  Summation

    - Arithmetic Sum

      $$
      \sum_{i=1}^n i = 1 + 2 + 3 ... + i
      $$

      - $$
        \sum_{i=1}^n i = \frac {n(n+1)} 2
        $$

      - $$
        \sum_{i=1}^n i^2 = \frac {2n^3 + 3n^2 + n} 6
        $$

    - Geometric Sum
      $$
     \sum_{i=0}^n a^i = 1 + a^1 + a^2 + ... a^{n-1} + a^n
     $$

           - $$
             S = \sum_{i=1}^n i = \frac {a^{n+1} - 1} {a-1}
             $$

             $$
             S = 1 + a^1 + a^2 + ... + a^{n-1} + a^n \\
             aS = a^1 + a^2 + a^3 + ... + a^n + a^{n+1} \\
             ----------------- \\
             (1-a)*S \ =\  1 - a^{n+1} \\
             S = \ \frac {a^{n+1} - 1} {a-1} \\
             lim_{x \to \infin}\ S =\sum_{i=0}^\infin\ a^i = \frac {1} {1-a} \ (when, a < 1 )

      $$


      $$

3.  Mathematical Proofs

- 직접 증명
- 간접 증명 or 귀류법
- 귀납법
