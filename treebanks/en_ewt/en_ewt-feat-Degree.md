---
layout: base
title:  'Statistics of Degree in UD_English-EWT'
udver: '2'
---

## Treebank Statistics: UD_English-EWT: Features: `Degree`

This feature is universal.
It occurs with 3 different values: `Cmp`, `Pos`, `Sup`.

17768 tokens (7%) have a non-empty value of `Degree`.
2997 types (15%) occur at least once with a non-empty value of `Degree`.
2436 lemmas (16%) occur at least once with a non-empty value of `Degree`.
The feature is used with 3 part-of-speech tags: <tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (16771; 7% instances), <tt><a href="en_ewt-pos-ADV.html">ADV</a></tt> (996; 0% instances), <tt><a href="en_ewt-pos-INTJ.html">INTJ</a></tt> (1; 0% instances).

### `ADJ`

16771 <tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> tokens (100% of all `ADJ` tokens) have a non-empty value of `Degree`.

`ADJ` tokens may have the following values of `Degree`:

* `Cmp` (614; 4% of non-empty `Degree`): <em>more, better, less, larger, bigger, earlier, smaller, higher, older, greater</em>
* `Pos` (15538; 93% of non-empty `Degree`): <em>good, great, new, other, many, last, same, few, little, sure</em>
* `Sup` (619; 4% of non-empty `Degree`): <em>best, most, least, worst, cheapest, largest, latest, easiest, highest, oldest</em>
* `EMPTY` (37): <em>s, First, second, i.e., 10th, 14th, 17th, 21st, 55th, Central</em>

<table>
  <tr><th>Paradigm <i>good</i></th><th><tt>Pos</tt></th><th><tt>Cmp</tt></th><th><tt>Sup</tt></th></tr>
  <tr><td><tt>_</tt></td><td><em>good</em></td><td><em>better</em></td><td><em>best</em></td></tr>
  <tr><td><tt><tt><a href="en_ewt-feat-Abbr.html">Abbr</a></tt><tt>=Yes</tt></tt></td><td><em>gud</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="en_ewt-feat-Typo.html">Typo</a></tt><tt>=Yes</tt></tt></td><td></td><td></td><td><em>bast</em></td></tr>
</table>

`Degree` seems to be **lexical feature** of `ADJ`. 97% lemmas (2358) occur only with one value of `Degree`.

### `ADV`

996 <tt><a href="en_ewt-pos-ADV.html">ADV</a></tt> tokens (8% of all `ADV` tokens) have a non-empty value of `Degree`.

The most frequent other feature values with which `ADV` and `Degree` co-occurred: <tt><a href="en_ewt-feat-PronType.html">PronType</a></tt><tt>=EMPTY</tt> (996; 100%).

`ADV` tokens may have the following values of `Degree`:

* `Cmp` (378; 38% of non-empty `Degree`): <em>more, later, better, earlier, longer, less, further, sooner, closer, higher</em>
* `Pos` (483; 48% of non-empty `Degree`): <em>well, far, soon, long, hard, early, late, close, little, high</em>
* `Sup` (135; 14% of non-empty `Degree`): <em>most, best, least, worst, highest, longest</em>
* `EMPTY` (11539): <em>so, just, when, very, also, how, now, even, then, there</em>

<table>
  <tr><th>Paradigm <i>well</i></th><th><tt>Pos</tt></th><th><tt>Cmp</tt></th><th><tt>Sup</tt></th></tr>
  <tr><td><tt>_</tt></td><td><em>well</em></td><td><em>better</em></td><td><em>best</em></td></tr>
  <tr><td><tt><tt><a href="en_ewt-feat-Typo.html">Typo</a></tt><tt>=Yes</tt></tt></td><td></td><td><em>etter</em></td><td></td></tr>
</table>

### `INTJ`

1 <tt><a href="en_ewt-pos-INTJ.html">INTJ</a></tt> tokens (0% of all `INTJ` tokens) have a non-empty value of `Degree`.

`INTJ` tokens may have the following values of `Degree`:

* `Pos` (1; 100% of non-empty `Degree`): <em>Bon</em>
* `EMPTY` (927): <em>please, yes, well, no, hi, ok, like, lol, hey, oh</em>

## Relations with Agreement in `Degree`

The 10 most frequent relations where parent and child node agree in `Degree`:
<tt>ADJ --[<tt><a href="en_ewt-dep-conj.html">conj</a></tt>]--> ADJ</tt> (621; 97%),
<tt>ADJ --[<tt><a href="en_ewt-dep-amod.html">amod</a></tt>]--> ADJ</tt> (98; 96%),
<tt>ADJ --[<tt><a href="en_ewt-dep-advcl.html">advcl</a></tt>]--> ADJ</tt> (47; 87%),
<tt>ADJ --[<tt><a href="en_ewt-dep-parataxis.html">parataxis</a></tt>]--> ADJ</tt> (38; 86%),
<tt>ADJ --[<tt><a href="en_ewt-dep-ccomp.html">ccomp</a></tt>]--> ADJ</tt> (20; 100%),
<tt>ADJ --[<tt><a href="en_ewt-dep-obl-npmod.html">obl:npmod</a></tt>]--> ADJ</tt> (18; 64%),
<tt>ADJ --[<tt><a href="en_ewt-dep-nsubj.html">nsubj</a></tt>]--> ADJ</tt> (14; 93%),
<tt>ADV --[<tt><a href="en_ewt-dep-advcl.html">advcl</a></tt>]--> ADJ</tt> (12; 55%),
<tt>ADJ --[<tt><a href="en_ewt-dep-appos.html">appos</a></tt>]--> ADJ</tt> (9; 100%),
<tt>ADJ --[<tt><a href="en_ewt-dep-list.html">list</a></tt>]--> ADJ</tt> (9; 90%).

