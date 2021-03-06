%Conditionals book, Introduction
%Cian Dorr; John Hawthorne 
%December 2014

There is a long tradition of treating ‘if’ (or perhaps ‘if…then…’) as a
binary connective, expressing a function from ordered pairs of
propositions to propositions. The proposition expressed by a particular
‘if’ sentence on a given occasion is the result of applying the function
contributed by ‘if’ to two other propositions, the antecedent and the
consequent, which are expressed on that occasion by the subordinate
clause and the main clause respectively. For example, the proposition
expressed by

(@indicative) If Jack is in the park now, Jill is in the park now

on an occasion of utterance is the result of applying the function
contributed on that occasion by ‘if’ to the propositions contributed on
that occasion by ‘Jack is in the park now’ and ‘Jill is in the park
now’. The antecedent and consequent needn’t be sentences that would
serve as standalone declarative utterances. For example, in

(@counterfactual) If I resigned tomorrow, I would be hired by Google the day after 
	tomorrow

the antecedent, ‘I resigned tomorrow’ would not make sense to assert on
its own: nevertheless, it is natural to think of it as contributing a
proposition, namely the same one that would be expressed by a standalone
utterance of ‘I will resign tomorrow’.[^1]

This model is prima facie plausible for many ‘if’-sentences. But there
are some ‘if’ sentences for which it is completely hopeless. Consider

(@llamas) If a farmer owns llamas, the farmer is rich

What two propositions would be the inputs to the function putatively
contributed by ‘if’ on this occasion? Certainly ‘the farmer is rich’
does not contribute the proposition that the one and only farmer is
rich, or the proposition that the one and only farmer with such-and-such
feature is rich, or a proposition concerning the richness of any
particular farmer. If we were determined to force this sentence into the
two-proposition model, the best option would be to take the consequent
to be the proposition that all the llama-owning farmers are rich, and
the antecedent the proposition that there is a llama-owning farmer. But
this seems a bit of a stretch; and it is far from obvious what
linguistic mechanisms would be responsible for associating those two
propositions with the subordinate and main clauses of (@llamas).

The dominant strand in the philosophical literature deals with sentences
like (@llamas) by silently ignoring them. But there are other cases which are
arguably like (@llamas) but which sometimes have been shoehorned into the
two-proposition model, such as (@doeswill):

(@doeswill) If Jack sees Jill next week, he will wave

Here there is a natural candidate to be the antecedent, namely the
proposition that Jack will see Jill next week. But what would be the
consequent? The proposition that Jack will wave sometime in the future?
The proposition that Jack will wave sometime next week? More plausible
candidates are the proposition that every time Jack sees Jill next week
he will wave at Jill, or the proposition that on at least one occasion
next week Jack will see and wave at Jill. But these *ad hoc*
reconstructions are not much use to systematic theorising; and it would
be a mistake to take it for granted that a systematic theory will
conform to the two-proposition model at all.

Another kind of case where the application of the two-proposition model
is questionable is where certain kinds of modals occur in the consequent
of an ‘if’ sentence.

(@) If you steal from your employer, you should only steal a little

(@cant) If he is in the pub, he can’t be at home

(@) If he is in the pub, he might be at home

These sentences could perhaps be assimilated within the two-proposition
model, although there is pressure to think that the
consequent-proposition is something quite different from the proposition
that would be naturally be taken to be expressed by a standalone
occurrence of the consequent. There is also a tradition in which certain
sentences like these are reconstructed in such a way that there is a
mismatch between the real and apparent scopes of the modals which on the
surface occur in the consequent, so that the content of (@cant), for
example, would be more perspicuously represented by ‘It can’t be that
(if he is in the pub, he is at home)’. And some (e.g. Kratzer \*\*\*)
reject the application of the two-proposition model to these sentences
in more radical ways.[^2]

One other kind of problem case for the two-proposition model is
exemplified by

(@any) If Fred had eaten any kind of shellfish, he would have been sick

Some will be comfortable assimilating (@any) within the two-proposition
model, claiming that its antecedent is the existential proposition that
Fred eats some kind of shellfish. But we are not sure this is right:
thinking about the difference between the natural reading of (@any) and the
natural reading of (@shellfish),

(@any2) If Fred had eaten any kind of shellfish, he would have eaten lobster

one feels that the subordinate clause in (@any2) is much more apt than the
one in (@any) for a mundane existential treatment. (The ‘any’ in (@any)
strikes us as somewhat reminiscent of the indefinite article in (@llamas), ‘If
a farmer owns llamas, he is rich’.) Moreover, the reasons for being
cautious in the case of (@any) arguably carry over to (@or), whose contrast
with (@or2) is similar to that between (@any) and (@any2):

(@or) If Fred had eaten either lobster, crab, or prawns, he would have been sick.

(@or2) If Fred had eaten either lobster, crab, or prawns, he would have eaten lobster.

We think it is important for an adequate theory of conditionals to
account for all these sentences. Nevertheless, in the first three
chapters of this book, we will focus entirely on ‘if’ sentences like (@indicative)
and (@counterfactual), where it is especially plausible that the meaning somehow
involves two propositions and where there is likely to be little dispute
about which propositions they are. We will defend a view on which these
sentences express propositions that are evaluable for truth and falsity,
and we will attempt to say something systematic about the kind of
relation that needs to hold between the antecedent and the consequent
for the proposition expressed by the whole conditional to be true. Note
that in developing a theory of this sort, we will not need to make any
particular assumptions about the syntactic structure of the relevant
‘if’ sentences, or about the semantic contribution of the word ‘if’. It
is compatible with our view, for example, that ‘if’ doesn’t have a
semantic value at all, so that the semantic value of ‘if Jack is in the
park now’ is the same as the semantic value of ‘Jack is in the park now’
(just as, e.g., ‘snow is white’ and ‘that snow is white’ arguably have
the same semantic value in ‘I believe that snow is white’), so that the
determination of the semantic value of the whole sentence is governed
entirely by compositional rules and/or the semantic values of
unpronounced constituents.[^3] Still less are we making any assumption
about the semantic value of ‘then’ in ‘If p, then q’, or committing
ourselves to the unlikely hypothesis that ‘if’ and ‘then’ comprise a
single scattered semantic unit. All that matters for our positive view
is that the contributions of the subordinate and main clauses in (1) and
(2) are propositions (or things that in some natural way determine
propositions), and the very propositions that the philosophical
tradition takes them to be.[^4]

Having narrowed our field in this way, we are in a position to state the
theory we will be defending in a schematic way, as follows:

>	A conditional with antecedent p and consequent q is true iff either
>  there is no accessible world at which p is true, or the closest
>  accessible world at which p is true is a world at which q is true.

The schema is not original to us: it has been around since the classic
works of Stalnaker and Lewis. Our contribution will be in what we have
to say by way of fleshing out the key technical terms of art:
‘accessible’, ‘closest’, and ‘world’. Quite obviously, different ways of
cashing out this ideology will yield wildly different theories. Suppose
for example that we interpret ‘accessible’ in such a way that at any
given possible world, that world is the only accessible world. Then the
schema will yield the same truth conditions as the material conditional:
when the antecedent is false, it is false in all accessible worlds, and
so the conditional is vacuously true; when the antecedent is true, the
actualised world must be the closest accessible world where the
antecedent is true (since it is the only accessible world), and so in
that case the conditional is true if and only if the consequent is true.
Our preferred take on the relevant ideology, which works very
differently from this, will emerge over the course of the next three
chapters, which consider ‘accessible’, ‘closest’, and ‘world’
respectively.

- Be clearer here about: (a) the way in which we are treating words like 'accessible' in the light of our contextualism, and (b) the idea that we are identifying (at least up to necessary equivalence) the propositions expressed by conditional utterances / sentences in contexts.  

- See if we are being consistent in using "conditional" to mean a kind of sentence not a kind of proposition.  If necessary say that we are going to leave it up to context to decide.  

- Add: a big table of logical principles validated by the view, plus another table listing some that aren't validated by the view.  Report completeness results due to Stalnaker or whoever.  

- Be more wry about the oldie-but-goodie character of the project. 


[^1]: We use ‘antecedent’ and ‘consequent’ for propositions. Others use these words for linguistic items, either what we call the ‘subordinate clause’ and ‘main clause’ of the ‘if’-sentence (e.g. ‘I  resigned tomorrow’ and ‘I would be hired by Google the day after tomorrow’ in the case of (@counterfactual)), or certain standalone declarative sentences derived by applying certain transformations to these clauses (e.g. ‘I will resign tomorrow’ and ‘I will be hired by Google the day after tomorrow’ in the case of (@counterfactual)).

[^2]: Note that linguistically ‘will’ and ‘would’ are also modals…

[^3]: Examples like ‘If he came to the party and if he behaved himself,
    he was invited back’ are especially problematic for the idea that
    the semantic value of ‘if’ is a relation between propositions.

[^4]: Examples of what we mean by ‘things that naturally determine
    propositions’: sets of possible worlds, properties of possible
    worlds, context-change potentials that map each set of worlds to the
    result of intersecting it with some given set, … For now we will not
    need to make any assumptions about how fine-grained propositions
    are, although we will have more to say about this in chapter 3.
