---
title: Differenzierbarkeit
---
## Definition
Sei $D\subseteq \mathbb{R}$ und $c\in D$ ein [[Häufungspunkt]] von D.
Eine Funktion $f:D\to \mathbb{R}$ heißt ==differenzierbar im Punkt c==, wenn der Differentialquotient $\lim_{ x \to c } \frac{f(x)-f(c)}{x-c} \stackrel{h:=x-c}{=} \lim_{ h \to 0 } \frac{f(c+h)-f(c)}{h}$ existiert. Diesen nennen wir $f'(c)$.
Wenn $f$ an jeder Stelle im Definitionsbereich $D$ [[Differenzierbarkeit|differenzierbar]]  ist, dann nennen wir $f$ ==differenzierbar  in ganz D==.
Die Funktion $f'$ heißt ==1. Ableitung von f==. Die Notation $\frac{d}{dx}f(x)=f'(x)$ ist ebenfalls üblich.

---
## Propositionen
>[!info] Stetigkeit und Differenzierbarkeit
> Wenn eine Funktion an einem Punkt $c\in \mathbb{R}$ differenzierbar ist, ist sie auch am Punkt $c$ [[Stetigkeit|stetig]].
> Ebenso gilt die Kontraposition: Wenn eine Funktion nicht am Punkt $c$ [[Stetigkeit|stetig]] ist, dann ist sie auch am Punkt $c$ nicht [[Differenzierbarkeit|differenzierbar]].

>[!info] Links- und Rechtsseitige Differenzierbarkeit
>$f$ ist genau dann in $c$ [[Differenzierbarkeit|differenzierbar]] , wenn der linksseitige und der rechtsseitige Differentialquotient existieren und beide übereinstimmen, d.h.
>$\lim_{ x \nearrow c} \frac{f(x)-f(c)}{x-c} = \lim_{ x \searrow c } \frac{f(x)-f(c)}{x-c}$

---

## Beispiele
>[!example] $f(x)=\sin\left( \frac{1}{x} \right)$
>f(x) ist nicht differenzierbar.


>[!example] $f(x)=x\cdot \sin\left( \frac{1}{x} \right)$
>f(x) ist nicht differenzierbar.


>[!example] $f(x)=x^2 \cdot \sin\left( \frac{1}{x} \right)$
>f(x) ist differenzierbar.
