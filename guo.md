<title>The Guo semantics</title>
# The *Guo* semantics

by uakci, 2018-02-XX

## 0. Introduction
In Toaq, as in every other language, the veracity of some predications heavily depends on the context – in particular, the spatial and the temporal. The goal of this write-up is to solidify the semantics hidden in the background of all Toaq utterances by means of the **guo** operator predicate and *Guo* theory.

## 1. What does it mean to be **guo**?

Let's read the definition of **guo**:

> \_\_\_ is a repetition/instance of \_\_\_ [gloss word: ‘instance’].

What does this definition entail? What goes into the two slots? The **go** slot is definitely a **lufē** (‘subordinate proposition created using the fifth tone’). But should the **fi** slot be **lufē** too? What about a sentence like:

> **Gủo hôa na hôa da.**
> ‘**Hoa**-ing is an instance of **hoa**-ing.’

This doesn't look good – should a proposition be one instance of itself? We can, of course, reinterpret the sentence above in at least two ways. Firstly, we can try to understand **guo** as a kind of **mea** for propositions, i.e., ‘\_\_\_ is a specific instance of a more general case \_\_\_,’ which would make way for statements like these:

> **Gủo rûqshūa rúq gúaq séoq na rûqshūa [sa ráı sa ráı sa ráı] da.**
> ‘That the rain falls/fell onto the land from the sky is/was an instance of raining.’

> **Mảı jí hó gùo mâı jí sa réq da.**
> ‘I love(d) them, which is/was an instance of me loving somebody.’

The **mu gủo** in the sentences above are more general in that they exemplify more general cases (like ‘raining of something onto somewhere from somewhere’). The latter sentence could be rephrased as:

> **Mẻa mâı jí hó na sa túq lủ sa dó bı jẻı mâı jí dó na hóa da.**
> `[ιJ0 : ji(J0)] [ιH : ho(H)] [ιJ1 : ji(J1)] [∃T : tuq∘{λX ∃Y X={mai(J1, Y)}}(T)] {mai(J0, H)}≺T.`
> ‘That I love them is among the set of all my lovings of somebody.’

Oof. Such an interpetation of **guo** would be unwieldy because of how it would need to tear **mu gủo**'s internal quantification out of the fifth tone's containment, and, although **guo** could be assumed to work in this way because of how natural it is to use, I'll leave this issue for later. [FIX – reference]

A better interpretation, perhaps, is to assume that the resulting type of **guo**, i.e., a **gúo**, is not a **lufē**, but a special atomic type – *Guo*. I state that **guo** is an *operator* from the *Lufe* type to the *Guo* type, and that *Lufe* and *Guo* are disjoint.

## 2. *Guo* and context
<b>Definition.</b> We define a *context* to be any binary predicate *φ* such that:
1. The domain of *φ* is (*Lufe*, *T*), where *T* is any topology. (We assume predicates to be identically false outside their domain.)
2. For every **dó**, if **jẻo dó**, then there exists at least one **dóhēo** such that **φ̉ dó dóhēo**.

Any set of contexts *φ*<sub>1</sub>, *φ*<sub>2</sub> may be 
