---
layout: post
mathjax: false
date: 2021-03-24
title: "In what way are math olympiads useful?"
categories: math olympiad
---

Last year, around July 2020, I chatted with the Indonesian IMO 2020 team after
they are done with the IMO. It is nice to stay in touch with the teams, as I get
to know these talented people (much more talented than my batch -- they got 2
gold medals, in comparison to the IMO 2014 and 2015 teams which have 0 gold and
2 silver medals each!)

I get to share my experiences on how life is like after the IMO. In particular,
I talked about my observations on how math olympiads can be useful in life.
This post is a recap of the discussion. It is arranged from the most related to
math olympiads, to the least.

## 1. Directly related: combinatorics research
Generally, math olympiad problems consist of 4 categories: algebra,
combinatorics, geometry, and number theory.

Research in algebra, geometry, and number theory at the highest level can be
very, very far from how the subjects are treated in the math olympiad level.
For example, there is the subject of algebraic geometry, which needs at the
very least knowledge about basic algebraic structures (groups, rings, fields),
and point set topology. The algebraic structures are already quite some
knowledge above olympiad algebra, and point set topology is only remotely
related to olympiad geometry.

However, research in combinatorics are actually very related to olympiad
combinatorics. For example, the probabilistic method, which can be used to
solve some of the hardest problems in olympiad combinatorics, has its
applications in research topics like random matrices.

## 2. Somewhat related: fields like cryptography
Even though research in algebra, geometry, and number theory can be very far
from the olympiad level, knowledge of certain mathematical properties taught in
the olympiad can be very useful for many fields.

For example, cryptography requires quite some knowledge in modulus arithmetic,
such as Fermat's Little Theorem. One might think that the knowledge of number
theory is only to understand how the RSA cryptographic system works. However,
there are many cases in open source libraries where the security of the RSA
implementation is severly weakened due to not understanding the mathematical
principles behind it. As an example, some libraries have set the exponent of
RSA to be 1, making encryption a noop. Others have set the modulus to be a
prime or a prime power, making decryption easy to do as the totient of the
modulus is trivially computable. Attacks such as
[Hastad's broadcast attack](https://en.wikipedia.org/wiki/Coppersmith%27s_attack#H%C3%A5stad's_broadcast_attack)
rely on the knowledge of the Chinese Remainder Theorem.

There are also other fields in which I find my math olympiad knowledge to be
useful in understanding some things better. For example, in theoretical machine
learning,
[Sauer's lemma](https://en.wikipedia.org/wiki/Sauer%E2%80%93Shelah_lemma)
which has a purely combinatorial proof is used to prove one of the fundamental
results in theoretical machine learning: that finite VC dimension implies
uniform convergence.

## 3. Mathematical maturity
Still related to math, beyond these fields mentioned above, regular practice
in math olympiad problems and understanding the concepts helps a lot in
mathematical maturity.

During my time in university, I took a course on distributed systems, and the
professor spent a lot of time talking about basic mathematical techniques: for
example, if you want to establish a property that applies to objects, you need
proof, whereas if you want to show that this is false, it is enough to show a
counterexample. I remember being rather frustrated by this, as I find this a
rather basic technique in mathematics. I do realise that many computer science
students are not exposed to a lot of these fundamentals (they code much better
than me though) and my journey in math olympiad definitely gives me a much
bigger head start in mathematical concepts like this.

## 4. Concrete benefits, such as university entrance scholarships
Going out of math, there is also visible benefits in getting a medal in these
science olympiads. NUS and NTU both offer scholarships for admission with no
entrance exams necessary (at least in my year). This is especially fortunate for
me, since back then I had no plans to apply to any other university other than
NUS and NTU.

Top universities such as MIT and Stanford also, as far as I know, factor in
somewhat significantly the fact that you won these medals.

## 5. Knowing the community
I feel blessed that my journey in the math olympiad has also introduced me to
very talented people in the space. It allowed me to form bonds with Indonesian
people who has now gone to do great things, such as: head of data in Traveloka;
head of business intelligence in Shopee Indonesia; quantitative trader in DRW;
founder of a data engineering consultancy startup in Indonesia; operations
research PhD candidate in MIT; and so on. The common trait of dabbling in math
olympiads has made me much easier to connect with them and enrich myself with
more perspectives of the world.

Common experience in math olympiads also serves as a good ice breaker when
talking to IMO participants that I might have not previously known. No matter
which country the participants come from, we always like to reminisce about
our math olympiad times.

## 6. Values like grit
Finally, my journey in math olympiad has taught me a lot about grit. About how
you can achieve a lot of things in life if you put in enough dedication (luck
too, I suppose, but I do hope my luck carries over from the math olympiad times).

I don't think my character would be the same without devoting many, many hours
every day into training for the IMO. I don't think I would, for example, survive
applying to hundreds of companies and getting many rejection letters for
internships without the grit I carried from my math olympiad times.

## Afterthoughts
Back when I was doing math olympiad, many people (including, sometimes, me
myself) always ask to me: why do you want to do math olympiads? How are they
useful? Back then, lacking knowledge of what the real world is like, I usually
can only answer: well, why not?

I am hoping that my retrospective can answer this question to current math
olympiad students (mathletes, as some people like to call it) and provide them
with some actual answers about why math olympiad can be really worth pursuing.

I would also like to emphasise that doing math olympiads are not the only way
to acquire the benefits above! If math olympiads are not your cup of tea,
that's fine too :) If it is, though, you're in for a treat!
