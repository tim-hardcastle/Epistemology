## An isomorphism between deontology and epistemology

If we use the standard symbols of modal logic, `□` and `◊`, together with the standard rules and symbols of logic, we find that we can do very much the same sorts of things with them that are still capable of diverse interpretations.

* The alethic interpretation. `□` means "is necessarily true"; `◊` means "is possibly true". So now `¬□p → ◊¬p` means: "If p is not necessarily true then it is possible for p not to be true."

* The temporal interpretation. `□` means "is always true" and `◊` means is "may sometimes be true". So now `¬□p → ◊¬p` means: "If p is not always true then sometimes p may not be true."

* The deontic interpretation. `□` means "is obligatory"; `◊` means "is permissible". So now `¬□p → ◊¬p` means: "If p is not obligatory, then it is permissible to not do p."

* The egocentric interpretation: `□` means "I insist on getting ...", and `◊` means "I am willing to accept ...". So now `¬□p → ◊¬p` means: "If I don't insist on p, then I will accept the absence of p."

Now let's try an epistemological interpretation: `□` means "The evidence shows" and `◊` means "The evidence allows". So now `¬□p → ◊¬p` means : "If the evidence doesn't show p, then the evidence allows p to be false."

Up until now I've emphasized the similarity between these logics. But we want there to be differences. For example, in the alethic version we very much want the rule `□p → p` to hold, and so introduce it as axiom (M) of the alethic interpretation because then it means "if p is necessarily true, then p is true"; and likewise we add axiom (M) to the temporal interpretation, because then it means "if p is always true, p is true".

But unless we are Dr Pangloss, we don't want it to hold in a deontic system, because then it means: "If p ought to be the case, it is", and so gives us a deontology that denies the actual existence of evil. Nor does my demanding something imply that I have it: that disposes of the egocentric system.

Now, in the epistemological interpretation, we must also go without (M), because we face the usual cases where e.g. all the ravens we've seen so far have been black, and yet can't conclude that all ravens are black.

Can we at least say that if something is true, then the evidence must permit it? (Surely, after all, if we think otherwise the fault is with us and not the evidence?) No, that would be `q → ◊q`, or by the contrapostive `¬◊q → ¬q`, so we have `□¬q → ¬q`. So by choice of `q` to be `¬p`, we've proved (M).

What, then, *can* we reasonably say? Well let's start with the axioms of Standard Deontic Logic. We want all tautologies as usual, and modus ponens of course. Then we have the modal axioms and derivation schemes. We will translate them into English and see if they still work when we're talking about epistemology.

(K) : `□(p → q) → (□p → □q)`

"If the evidence shows that p implies q, then if the evidence shows p, then the evidence shows q."

This is true because if `p` logically implies `q`, then the evidence for `p` *is* evidence for `q`, and so the `□q` term doesn't necessarily imply the existence of any *further* evidence.

(NC) : `□p → ¬□¬p`

"If the evidence shows that p, then the evidence does not show that not p."

This makes perfect sense.

(NEC) : if `⊢p` then `⊢□p` 

"What we can derive as a theorem is shown by the evidence."

This is necessary because we need e.g. `p ∨ ¬p` to have *at least* as much evidential status as any merely synthetic proposition!

All the basic axioms seems to stand up. We can also see that the most obvious consequences of SDL also work when translated, eg:

(OD): `¬□⊥` 

"The evidence does not show a contradiction in terms."

(OB-M) `□(p ∧ q) → (□p ∧ □q)`

"If the evidence shows that p and q, then the evidence shows that p, and the evidence shows that q."

(N) : `□⊤` :

"The evidence shows the truth of a tautology."

(RM) : if `⊢p → q` then `⊢□p → □q`

"If we can derive as a theorem that p implies q, then we may also say that if the evidence shows p, then the evidence shows q."

This all seems acceptable. We might say that the two systems are *isomorphic up to interpretation*: where the isomorphism is simply reinterpreting a deontological formula as epistemological and the quality being preserved by the isomorphism is *making sense*. Things that we want to be results because they make perfect sense, like `□(p ∧ q) → (□p ∧ □q)`, are results. Things that don't make sense and we don't want to be results, like `◊p → □p` are gibberish in both systems ("Everything permitted is compulsory; everything possible is true.") Axiom (M) denies in one system that we can do evil and in the other that we can be misled by the evidence.

And plausible extensions to the system which cannot be proved in it continue to be plausible extensions. For example the deontologists suggest that we should add as an axiom (U) `□(□p → p)`. To a deontologist it says that it is obligatory that if it is obligatory that `p` should happen then `p` should happen; to an epistemologist it means that the evidence shows that if the evidence shows that `p` is true, then `p` is true.

Or to take a non-random example, it makes equal sense in both cases to take our logic and apply the Andersonian-Kangerian reduction, discovered by deontologists, which *means* something completely different if you're an epistemologist, but which again turns out to mean something that *makes perfect sense*.

Consider the Andersonian-Kangerian reduction from the deontological point of view. We take a normal alethic logic. We introduce a constant, `d`, with the interpretation: "all (relevant) normative demands are met". We add an axiom `◊d`: "all (relevant) normative demands are capable of being met". And then we point out that saying that `p` is obligatory in deontic logic can be translated into saying `□(d → p)` in this new system.

But to reduce epistemological modal logic, we do the same thing but take `d` to mean "the evidence is not misleading" and `◊d` to mean "it is possible that the evidence is not misleading". And then we point out that saying that the evidence shows `p` can be translated into saying `□(d → p)` in this new system.

And this explains why this rather surprising isomorphism between deontology and epistemology goes on working. Because people trying to find out the facts also want normative conditions to be met — by nature, who they wish would "play fair" with them. What is it to say that "the evidence shows" such-and-such, but to say that in a world which rewarded virtue with happiness, the hard work and honesty of researchers would have been rewarded with truth, as they wished?

It therefore seems likely that continuing this line of investigation (i.e. following the deontologists around and converting their math into the equivalent epistemology) would continue to be interesting.
