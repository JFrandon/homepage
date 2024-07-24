+++
title = 'Divisibility by 7'
date = 2024-07-03T23:37:31-04:00
draft = false
+++

Let's prove that a natural number \\(n = 10a + b\\), where \\(\\{a,b\\}\\subset\\mathbf{N} b \\lt 10\\) is divisible by 7 iff \\(5b + a\\)  is divisible by 7.
\\[
\begin{eqnarray}
7 | n &\iff& 7 | 10a+b \\\\  
& \iff&\exists q, 10a+b = 7q \\\\  
& \iff&10a+b \equiv 0 \pmod{7} \\\\  
& \iff&20a+2b \equiv 0 \pmod{7} \\\\  
& \iff&-a+2b \equiv 0 \pmod{7} \\\\  
& \iff&a-2b \equiv 0 \pmod{7} \\\\  
& \iff&a+5b \equiv 0 \pmod{7} \\\\  
7 | n &\iff&7 | a+5b \\\\  
\end{eqnarray}
\\]
QED.

Formulating the recursive algorithm to check the divisibiliy by 7 of any integer is left as an exercise for the reader.
