<title>Archive</title>

# Archive

## On names with falling tone

### 2018-07-10, #chiejio
**mi Lim**:
> > In (NAM.1) and (NAM.2), the name after mi carries a falling tone. It can also
carry any other tone. The name ends automatically when the phrase started by
the name's tone ends.
>
> I'm actually a little confused about this phrasing
>
> oh, phrase means something very specific, right

**mi Hoenmair**
> %miu **min buf**

**mi Nuongair**
> **(mỉ bũ)**
> {λ𝑋 chua(‹bũ›, 𝑋)}().

**mi Hoenmair**
> %miu **min neok nip**

**mi Nuongair**
> **(mỉ {nèo ní})**
> {λ𝑋 chua(‹nèo ní›, 𝑋)}().

**mi Hoenmair**
> So here the names are **bũ** and **nèo ní**
>
> An adverbial phrase and a prepositional phrase
>
> the prepositional phrase ends with its noun complement (which itself ends once
> its serial verb is over and once there aren't any attached relative clauses
> anymore)
>
> And then the name is automatically over

**mi Linmel**
> %miu **mỉ mỏq**

**mi Nuongair**
> syntax error :1.7: want [bB], [cC], [dD], [fF], [gG], [hH], [jJ], [kK], [lL], [mM], [nN], [pP], [rR], [sS], or [tT]; got EOF

**mi Lim**
> so, if my name is **Lı̉q**, that tone is part of the name? as in, **mi Líq** and **mi Lĩq** are different persons

**mi Hoenmair**
> Unless you also go by those names

**mi Lim**
> right

**mi Huamchir**
> That’s the difference between Ms. Being a female, Ms. A Female and Ms. Femininely
> 
> roughly
>
> zo’orei

### 2019-03-07, #general
**mi Seamtal**
> Anyhow normally you will find a name in the fourth tone

### 2019-03-08, #general
**mi Niuncul**
> **m̂**, fragments of terms and serial predicates also can be taken as a name/phrase by **mi**/**shu**

### Summary
Names can have any tone, but the most common one is the fourth tone.
Two names with the same word, but different tones are technically different names (**mi Lim** ≶ **mi Lib** ≶ **mi Liv**).

## On frames and signatures 

This file contains most of the common frames.    
[frames-list.txt](https://github.com/acotis/serial-predicate-engine/blob/master/code/dict/frame-list.txt)

### 2019-03-08, #general
**mi Hoamgior**
> As for frames-list.txt...
> Since there are only a few common types in the type system  
>     (c, 0, 1, and 2),  
> and since each word has usually only one or two slots, it happens that a lot of
> words have the same signature as each other.
> 
> (This is bolstered by the fact that Toaq tries to build patterns into the
> vocabulary, so many words that deal with similar concepts are given them same
> signature on purpose.
> -- see the triplet 
>     (**dua**, **chi**, **miu**)  
> or  
>     (**jui**, **jao**, **leaq**, **poe**, **cuao**) )
> 
> A frame is just a common signature that lots of words fit into.
> For example, the LEO frame is the signature
>     [(c) (c 1)] -- 
> predicates whose 1-ary meaning takes just a concrete object and whose 2-ary
> meaning takes a concrete object and a property (a proposition with one open
> slot)
> 
> Math stuff here, don't look if you're already feeling overwhelmed :smiley: : There's also the special case of the JEO frame, which has the signature [(0) (c 1)] and the special requirement that, for a predicate P to be in the JEO frame, it must satisfy the equivalence P(x, y) = P(**jeo**(x, y)).  We also have the MAO frame, which is defined as predicates which have a signature of [(0) (c 1)] but which don't satisfy that equality, which is named the "JEO-frame Equivalence"

## On ternary predicates

### 2019-03-13, #general

**mi Hoamgior**
> % **cutaq**

**mi Nuongair**
> 1–1/1 — **cutaq** + — <▯1, ▯2> are such that <x1, x2, x1> satisfy ternary relation ▯/3; ▯ does/is ▯/3 to themselves.

**mi Hoamgior**
> Here's one that was added recently
>
> It's the first one I know of though
>
> 2-ary properties are useful for words like **mia** (▯ satisfies property ▯ with many things) and **jeq** (▯ and ▯ satisfy property ▯ with the same thing)
> 3-ary properties aren't useful for much, as far as we've discovered


## On the low tone

### 2019-03-13, #general
**mi Hoamgior**
> Here's how :t6: works:
> Both :t6: and :t7: serve to create adverbials. An adverbial is a part of a sentence that makes a claim about the sentence itself (not its text, but its content).
>
> Everything in Toaq is done with predicates, and adverbials are no different. Ultimately an adverbial always does its thing by taking the entire Toaq sentence, pretending is has a :t5: tone (that generates propositions) and sticking it into the first place of a predicate.
>
> For example:
>
> "**Shie jí rào kôi hó**"
>
> Here, the **rao** with the :t6: grabs the entire rest of the sentence, throws it into a :t5: clause, then passes it as the x1 place to the predicate rao.  :t6: also has the effect of taking the following noun and passing it to the predicate as the x2 place.
>
> Thus the sentence is equivalent to:
>
> "**Rao (shîe jí na) kôi hó**"
>
> With the originally top-level claim in parentheses
>
> It means "I am awake while he/she is walking"

## On the necessity of the tones

### 2019-03-13, #general
**mi Hoamgior**
> :t6: and :t7: can be excluded without too much difficulty
>
> :t3: might be possible to get rid of, but it would take some work to prove that. It doesn't just expand to something else like those other two tones do
>
> :t1:, :t2:, :t4:, :t5:, and :t8: are all 100% necessary

## On implications

### 2019-03-14, #general

**mi Seamtal**
> Those are lojban words
>
> * rinka = **ca**
> * nibli = **lucar**
> * krinu ≈ **mu kui**

## On ordinal compounds

### 2019-03-14, #general

**mi Hoenmair**
> I have written a possible lesson 2.
>
> Also I need to add the ordinal compounds to the official dictionary.

You make ordinal compounds by concatenating the number name with the (**ko**) predicate: **shikor**, **gukor**, **saqkor**…

## On laughter and the lambda quantifier (ja)

### 2019-03-16, #general

**mi Bunrurnor**
> jajajaja

**mi Chain**
> hahahaha\*
>
> we’re in Toaqistan, sir

**mi Bunrurnor**
> sorry, my spanish showed XD

**mi Chain**
> you don’t necessarily want to laugh with the lambda variable quantifier
>
> unless it’s **ja dó ja dó ja dó ja dó**

**mi Bunrurnor**
> would that mean XXXX?

**mi Chain**
> it would
>
> kind of
>

**mi Chain**
> although each of the X’s would be distinct
>
> and the whole wouldn’t really mean anything without context
>

[...]

**mi Bunrurnor**
> O.O, I didn't realize that each **ja dop** would represent a different variable

**mi Chain**
> it always does
>
> so, how do you differentiate between their values? by position?

**mi Chain**
> **chẻo súqjī lî sẻaq ja póq ja póq**
>
> = we are reciprocal in relation λxy. x has sex with y
>
> = we have sex with each other
>
> = **chẻo sẻaq súqjī**

**mi Chain**
> **ja** binds variables

**mi Bunrurnor**
> oooh, I see! and the variables are predicates?
>
> like **poq** and **do**?
>

**mi Chain**
> no
>
> I mean, yes
>
> but **poq** isn’t a variable predicate
>
> if you say **ja póq**, then **poq** won’t refer to [the bound variable]
>
> but **ja dó** will[, because **do** is a variable predicate]
>

**mi Bunrurnor**
> oh, its the lambda calculus
>
> ok, the first **ja** means the x, the second **ja** means the y
>
> I don't understand what **ja dop** refers to

**mi Chain**
> **do** doesn’t mean anything until it’s bound by a quantifier

**mi Hoenmair**
> %miu **lẻo jí lî nủo ja dó**

**mi Nuongair**
> **(lẻo {jí [lî <nủo (ja dó)>]})**
>
> [℩𝐽 : ji(𝐽)] leo(𝐽, {λ𝑋 nuo(𝑋)}).
>

**mi Chain**
> %miu **lẻo jí lî nủo ja póq**

**mi Nuongair**
> **(lẻo {jí [lî <nủo (ja póq)>]})**
>
> [℩𝐽 : ji(𝐽)] leo(𝐽, {[λ𝑃 : poq(𝑃)] nuo(𝑃)}).
>

## On Transitive and intransitive verbs
### 2019-03-16, #general

**mi Bunrurnor**
> why are there two different words for "gather", one transitive (**tua tijeq**) and the other intransitive?
>
> wait, I think I misunderstood the idea. is it the **tua** that makes **tijeq** transitive?
>
**mi Hoamgior**
> Intransitive is used like "The marbles all gathered together at the bottom of the bucket"
>
> Transitive is used as "I gathered together some firewood"
>
> The second kind has a place for a person making the things gather
>
> And yes, it's **tua** that makes it so
>

**mi Bunrurnor**
> I see, thanks!
>
> could you use the intransitive **tijeq** in a toaq sentence?
>

**mi Hoamgior**
> Sure!
>
> "**Tinjel sa róai deon ní da**"
>
> Would you like me to give the translation or do you want to work it out?
>

[...]

**mi Seamtal**
> It would be better with **sho tinjel**
>

**mi Hoenmair**
> **tıjēq** only means "to be in the same place", not "to gather" (which would be **sho tỉjēq**). But also, note that there is a root for "gather" (**kueq**)
>

**mi Hoamgior**
> Oh
>
> Then let me try again
>
> "**Kuem sa róai deon ní da.**"
>
> The translation is: "Eight children gather here."
>

## On inflecting serials
### 2019-03-16, #general

**mi Bunrurnor**
> I'm having trouble parsing this sentence
>
> > **Chỏ jí báq nảo da.**

[...]

**mi Hoenmair**
> Probably the báq nảo part
>

**mi Bunrurnor**
> exactly
>

**mi Hoenmair**
> So the trick here is
>
> you can turn serial predicates into nouns, just like you can turn single predicates into nouns, using :t2:
>
> But when you do this with serial predicates, only the first predicate gets that tone
>
> the rest keep their falling tone
>
> **bảq nảo** -> **báq nảo**
>
> This works with every tone
>

**mi Bunrurnor**
> so **bảq nảo** is a serial predicate, and a serial predicate can be ?conjugated? to any of the tones, and the first verb of the serial predicate gets the target tone, but the others keep the falling tone.
>

**mi Hoenmair**
> Exactly.
>

[...]

**mi Hoenmair**
> Inflection in Toaq happens by way of suprafixation.
>

## On inflection
### 2019-03-16, #general

**mi Bunrurnor**
> what's the name of applying a tone to a word?
>

**mi Seamtal**
> suprafixation
>
> i love them, and have used tones to mark the scope of affixes in one of my conlangs
>

**mi Hoenmair**
> I think you can say "inflect"
>

**mi Seamtal**
> Suprafixation is also broader than just tones tho
>

**mi Seamtal**
> > In linguistics, a suprafix is a type of affix that gives a suprasegmental pattern (such as tone, stress, or nasalization) to either a neutral base or a base with a preexisting suprasegmental pattern. This affix will, then, convey a derivational or inflectional meaning.

**mi Hoenmair**
> I would say inflect or decline
>
> But conjugate would also be understood
>

**mi Seamtal**
> Suprafixation would just be applying a suprafix, so just use the above definition when archiving and uh for the others

**mi Hoenmair**
> Inflection in Toaq happens by way of suprafixation.
>

### Summary
So, there are 4 words to say that a tone was applied to a predicate:  
Inflect, Decline, Conjugate, Suprafixate.


### 2019-02-24, #general

**mi Moinlul**
> suprafix — (linguistic morphology) A type of affix where a suprasegmental change (such as tone or stress) modifies an existing morpheme's meaning.
>
> Ah, that's relevant to Toaq.
>

## On naming time

### 2019-02-24, #luaq

A nice game of Toaq of the Day :)

**mi Lim**
> I elect @Hỏemāı as the winner \^\_\^
>
> (thank you for the new roots)
>

**mi Chain**
> …and the new dealer
>

**mi Hoenmair**
> TotD #3
>
> "The train will arrive at ten o'clock, which is when I'm usually still asleep."
>

**mi Lim**
> (TotD.LIQ.3)  (that's how I intended the numbering to go, for what it's worth.)
>
> **Tỉshā chúe(chāo) rào héıhōrāsīao, lǔ dủq nủo jí rào hóa da.**
>
> * **heıhōrā** = hour 10 of the day (the 10:00–11:00 hour), just like **shıchāq** = day 1 of the month (I already defined this in Toadua).
>
> → **heıhōrāsīao** = the start of hour 10 of the day.
>

**mi Seamtal**
> *n* + **horar** gives that part of the day, but *n* + **chaq** gives that part of the month? Why not that part of the week since that is the next unit up?
>
> Also we have been adding numbers to subscript kinda e.g. **doshir**, **hoagur** so why not continue that and have **horarheir** and **chaqshir**?
>
> **semcur shuaif keo jam chon jip lut moin sa raip pop bab damchiur**
>
> Ah
>
> I reread your explanation with more attention and i see why you skipped weeks, but my ordering beef still stands

**mi Lim**
>** niaqgu** is a twosome of something, a kind of **gu**, namely of consecutive years.
>
> whereas **guniaq** is a kind of **niaq**, namely the second one.
>

**mi Chain**
> clever, **Lim hu mi**
>
> I do understand why you’d choose days-\>months instead of weeks-\>months
>
> because the latter would be ill-defined
>

**mi Lim**
> it also mimics Chinese/Japanese 2019年, 3月, that kinda stuff
>

**mi Niuncul**
> (TotD.3.NCQ) **Jỉa tỉshā chúe lũ chảqpāqchīu kó hẻı hóa, ju dủq rảo hóa hôaı nủo jí da.**
>

**mi Niuncul**
> **(soan pó mí nimdaor roi mí Lim jí bâi ru je taonroar jí tîe kúo kúqtoair nò mí Dinkor da.) (kuam hain tuan shain tien ka.)**
>

**mi Hoamgior**
> (TodD.3.HGO) **Tỉshā chúe rào hórāchīu hẻı, ju dủq jí lî hỏaı nủo rào hóa da.**
>

**mi Niuncul**
> **(pójībi dun huam gin mó Tỉshā jĩa teo mǔa ru je len gin tûa beon keo taonroar shoen bun hoin lun tuan beon da)**
>

**mi Hoenmair**
> So should we vote or should I just declare a winner?
>

**mi Niuncul**
> setting up an emoji poll by the dealer in the case of indecision sounds sufficient
>

**mi Hoenmair**
> Okay, so I'll just make a decision. 
>
> First, some comments: I like both of the suggested systems. A downside with **Lỉq**'s system is that because it's all in the form a single compound, it is less flexible w.r.t. other complements, like questions ("at what time") and if you want to fill in things like "(at the time we agreed to meet"). I think this is easier to do with Hoaqgīo's proposal. Also conceptually, the **-sīao** in Lỉq's system bugs me a little. I'm sure the system itself is still very useful outside of specifying X o'clock, so it's still good to have no matter what. 
>
> Second comment: Everyone used **hoa** in the **ju** phrase, but this is illegal. It should be **maq** or **hoq**. Also, **ju** is better than **lǔ** here. 
>
> All things considered, I'll go with **Hoaqgīo**.
>
> @Hỏaqgīo congratulations
>

**mi Lim**
> oh, because it's a {noi}, not a {poi}
>

**mi Hoamgior**
> Woot woot
>

### 2019-02-24, #general

**mi Lim**
> To elaborate on my #luaq submission:
>
>
> I've envisioned a convention where  (number)+(time unit)  is a compound for   “the *n*-th time unit within the one-level-up unit, going  second → minute → hour → day → month → year → calendar era.”
>
> (skipping weeks seems okay; we have separate color-words for the weekdays, and usually weeks are not used as a date unit)
>
> and  (time unit)+(number)  is a new time unit that's *n* times longer,  like  **nıaqhēı** decade, **joagū** fortnight.
>
> and probably concatenating  (*m* + unit₁ + *n* + unit₂) means:   the *n*-th unit₂ of the *m*-th unit₁ (of the salient unit-above-unit₁).
>
> **saqjūe pāchāq** = the 1st of March (of the year).
>
> **heıcīhōrā jōhēımīnū** = 16:40 o'clock (of the day).   (would probably be written **16hōrā40mīnū** or **16h̄40m̄**)
>
> now, people talk about “10 a.m.” more than they talk about the 10 a.m. – 11 a.m. hour range.  so maybe heıhōrāsīao deserves some sort of abbreviation
>

**mi Lim**
> (but then again **heıshīhōrāsīao** is as many syllables as  e-le-ven o'clock !  maybe it's fine)
>

**mi Niuncul**
> **m̂**, *lertcitydetrysmi* **nò** *a compound* **jufhorshurhir**
>

**mi Lim**
> ja'a
>

**mi Moinlul**
> With the number serial rule, **nıaqnē gủ** = the duration of two years, i.e. 2 × 365¼ days
>

## On indirect questions

### 2019-03-17, #general


ShủaoToday at 8:01 AM
The concept of 'indirect questions' has always confused me.
What is this black magic?
🍵Today at 8:05 AM
what exactly about indirect questions do you find to be like black magic?
there is a significant difference about a question mentioned (not asked – thus ‘indirect’) in the sentence and its answer
’I don't know what friends he has’ means that you don't know what would answer the question: ’What friends does he have?’
in English, though, you can have a (tenuously) polysemous question like ’I don't know what you're pointing at’
on the one hand, it can mean: ‘I don't know the thing that you're pointing at,’ so if you were pointing at Bob, I'd be saying: ’I don't know Bob’
on the other hand, it can mean, ‘I don't know what the answer to the question: What you're pointing at? is’
ShủaoToday at 8:14 AM
But... how?!
🍵Today at 8:15 AM
thow
indirect questions are a concept that can't be analysed into smaller parts, and it's so by definition
an indirect question is a subordinate clause that pertains to an unasked question
and it is different from a relative clause that points to the answer of such a question
the Biblish ‘he who…’ might be easier to understand, I guess
’I don't know him who did that’ – I don't know the person
’I don't know who did that’ – I don't know the answer to the question: ‘Who did that?’
https://en.wikipedia.org/wiki/Content_clause#Interrogative_content_clauses
ShủaoToday at 8:18 AM
Are there not less nonsensical methods with the same effect?
🍵Today at 8:18 AM
[T]hey are often direct objects of verbs of cognition, reporting, and perception, but here they emphasize knowledge or lack of knowledge of one element of a fact[.]
no
if you have content clauses, you have to have indirect questions too
in case of Toaq, you have:
Bủ dủa jí tâo hı ráı máq da. – I don't know who did that.
Bủ rảqdūa jí lú tảo hóa máq da. – I don't know the one who did that.
HỏemāıToday at 8:21 AM
(but the second sense of "know" is different, and not dua)
🍵Today at 8:21 AM
yes, I corrected for that
dua can be applied to context clauses only; I used raqdūa here for the meaning: ‘I know of him.’
@Shủao of course, you might try making a language where, instead of indirect questions, you have predicates like ‘X doesn't know what has property Y,’ but indirect questions are handier in that they don't require you to know that you're going to use one before the moment they're stated
in general, every sentence with an interrogative content clause can be transformed into one with declarative content clauses only:
Bủ dủa jí tâo hı ráı máq da. (I don't know who did that.) → Sa dó tǔq lủ tảo hóa máq bı, bủ dủa jí tâo dó máq da. (There's somebody who did that for which I don't know to have done that.)
but, as you can see, the above is messy
and, to nitpick even further, the above transformation relies on the assumption that there is somebody who did that
in the end, you'd need to construct a sentence like: ‘If there isn't anybody who X-es, then I don't know that there is nobody who X-es; and if there is somebody who X-es, then for all people p such that p X-es, I don't know that p X-es’
@Hỏemāı @Mỏılūq if I made a mistake anywhere above here, please let me know
or, even better: ‘For all plural constants pp, I know that pp has p-ty X if pp has p-ty X, and I know that pp doesn't have p-ty X if pp doesn't have p-ty X.‘
ShủaoToday at 8:37 AM
I've found a bug in toadua.
🍵Today at 8:37 AM
the need for indirect questions could also be avoided with a predicate with a definition like: ‘X knows what n-tuple of arguments satisfies n-ary relation Y’ (for any n, including 0)
what is it, @Shủao?
the fix will most probably come with toadua2, because toadua1's code is fundamentally flawed
ShủaoToday at 8:38 AM
Spaces in a search -> (load URL again in whatever manner) -> %20 in the search
🍵Today at 8:39 AM
you're not supposed to use spaces in a search, by the way
if you want to search for the word tue joemieq, then input:
% tuejoemieq
nuogaiBOTToday at 8:39 AM
1–1/1 — tue jỏemīeq ∿ — examination (knowledge test)
ShủaoToday at 8:40 AM
They should be handled properly either way, though, right?
🍵Today at 8:41 AM
you're right, of course
@Shủao wait… are your doubts about indirect questions gone, or have you decided not to dwell further on them?
ShủaoToday at 8:46 AM
I found the bug when I was going to figure out what tao meant so I could try to figure out what you said.
🍵Today at 8:46 AM
alright
I've got about 40 minutes before I leave home, so make sure your contemplating's done by then
ShủaoToday at 9:27 AM
I suppose I've decided not to dwell further on them.
I should just accept it as black magic and move on.
🍵Today at 9:46 AM
perhaps not
they aren’t black magic
ShủaoToday at 9:52 AM
The concept doesn't seem to fit with everything else; therefore, it is black magic.
HeukueqcheToday at 10:01 AM
"Any sufficiently advanced technology is indistinguishable from magic"
so, it will be magic until we explain it thoroughly XD
🍵Today at 10:02 AM
it isn’t black magic because it does fit with everything else
HeukueqcheToday at 10:02 AM
Thanks for asking @Shủao ! I don't understand indirect questions either  XD
🍵Today at 10:02 AM
as they say, you ‘understand’ them, but you don’t understand them
ShủaoToday at 10:02 AM
What something actually is is irrelevant; only what it seems to be matters.
🍵Today at 10:03 AM
pffff
ShủaoToday at 10:03 AM
seem is a weird word.
🍵Today at 10:03 AM
you seem to be naïve
by the same measure
ShủaoToday at 10:03 AM
I may as well be naïve, then.
🍵Today at 10:03 AM
>:)
HeukueqcheToday at 10:03 AM
oh, I agree it fits into everything else. Just like airplanes fit into all of aerodynamics and physics. But to me, mere mortal in my dirt hut, it stays in the air because of magic XD
you'll have to teach me physics to see it as science
ShủaoToday at 10:04 AM
Indeed.
🍵Today at 10:04 AM
it’s enough to be told by a doctor of aerodynamics that it’s not magic that holds the airplanes up
HeukueqcheToday at 10:04 AM
but man, I'M STUDYING MEDICINE!
🍵Today at 10:04 AM
so, listen to your bachelor of indirect questions
ShủaoToday at 10:04 AM
The doctor of aerodynamics is a magician.
HeukueqcheToday at 10:04 AM
I need the explanation
anyways, I appreciate the explanation : ) I'll archive it and peruse it in my spare time
🍵Today at 10:05 AM
I could try taking another go at explaining at some other point
oh yes, please do archive it
also, please comply with the format
it took me half an hour to properly stylise the archive
https://uakci.pl/wiki/ and see the new style and form
form(at)
HeukueqcheToday at 10:07 AM
oh, thanks! I didn't know there was a document explaining the format. I was just trying to follow what you had done the first time XD
I'll read it
🍵Today at 10:07 AM
no, there isn’t any
just follow the format of the archive
when adding new entries
you should be able to grok it just by looking
HeukueqcheToday at 10:08 AM
#blackmagic XD
sorry, sorry
🍵Today at 10:09 AM
no, #grokking
I’ll go now
remember to merge from the parent repository often
i.e., before you introduce a change
HeukueqcheToday at 10:10 AM
as fagri said. You think too fast and too clearly. It would take me an hour to deduce the formatting from the document alone. I'm learning markdown on the fly XD! if you could whip out something quick, I would appreciate it a lot
all right, will do. Thanks mi Chai : )
ShủaoToday at 10:24 AM
Mankind is not meant to understand the languages they speak.
🍵Today at 11:49 AM
it is
that you haven’t yet got the necessary preliminary knowledge doesn’t mean it can’t be understood by those who have it
in such a case, though, you can catch up by reading such preliminary material
ShủaoToday at 11:53 AM
... we can always go against what we're "meant to" do, though, with enough work.
🍵Today at 11:53 AM
alright then
but then don’t complain about me being unintelligible
HỏaqgīoToday at 12:18 PM
uakci, your expansion of the indirect question was wrong
I'm on mobile and in bed right now, I'll be more specific later
nuogaiBOTToday at 1:00 PM
hỉo jí tỉrēa kǎqgāı hóa kenēıdē shq̂hūalāpīsīu da. mảq báq dẻo da. kỉhā.
MỏılūqToday at 1:01 PM
shq̂hūalāpīsīu
lol
🍵Today at 1:46 PM
@Hỏaqgīo therefore, I am asking to nitpick and correct
nuogāi seems to be entering some kind of lethargic state, judging by their recent babbling in computerese
🍵Today at 1:56 PM
I should emphasise that it’s my understanding of indirect questions that I was dwelling
it isn’t necessarily the most elegant definition
I, too, would like indirect questions gone
je m’aussi voudrais
@Mỏılūq is this the correct ante-predicat-ive order?
MỏılūqToday at 2:05 PM
#off-topic
HỏaqgīoToday at 2:45 PM
First problem:
> Bủ dủa jí tâo hı ráı máq da. – I don't know who did that.
> Bủ rảqdūa jí lú tảo hóa máq da. – I don't know the one who did that.
These sentences aren't alike
🍵Today at 2:46 PM
I’m aware
what point are you trying to make here?
HỏaqgīoToday at 2:46 PM
Nice picture
🍵Today at 2:46 PM
kủaq kỉe ka
HỏaqgīoToday at 2:47 PM
I'm not really making a point, unless you consider "that's wrong" to be a point
(Which I do -- retracting incorrect information is important even if you don't have correct information to replace it with)
But that there wasn't my main correction
🍵Today at 2:48 PM
I was showing an example of the almost same sentence and its not so same translation
they were somewhat supposed to turn out as different from each other
but, to the main tea, please
HỏaqgīoToday at 2:49 PM
Ah wait, I just found:
or, even better: ‘For all plural constants pp, I know that pp has p-ty X if pp has p-ty X, and I know that pp doesn't have p-ty X if pp doesn't have p-ty X.‘
I was going to correct you on:
in the end, you'd need to construct a sentence like: ‘If there isn't anybody who X-es, then I don't know that there is nobody who X-es; and if there is somebody who X-es, then for all people p such that p X-es, I don't know that p X-es’
But the "even better" one isn't wrong
🍵Today at 2:50 PM
are you saying that the one above is correct and the one below is wrong?
because if so, I agree
HỏaqgīoToday at 2:50 PM
Yes
(Or slightly more accurately: that the one above is a plausible rendition. We might not go with that)
🍵Today at 2:51 PM
I didn’t say we should go with any of that – again, it’s my interpretation specifically
although indeed it would be beneficial to keep this definition at the back of your head and see if it works in different, more convoluted sentences
note, however, how such an îndirect quẻstion is dependent in meaning on the containing predication
which means that :t5: + hi dó attains special semantic powers, just like :t6: in Toaq and macros in Scheme
(not Scheme macros, because they can only operate on their own arguments and not on their surroundings, and I’m trying to make the point that :t5: + hi dó does transform the outer clause)
HỏaqgīoToday at 2:55 PM
How do they transform the outer clause?
🍵Today at 2:57 PM
‘I don’t know what caused this’ -> ‘for all pp, I don’t know that pp caused this if pp caused this, and I don’t know that pp didn’t cause this if pp didn’t cause this.’
the italic parts are attachments onto the outer clause; moreover, this clause, with the modification (did -> didn’t), is copied to make a second claim (underlined)
HỏaqgīoToday at 2:58 PM
Hmm, I think I understand
Are you saying that Bủ dủa jí câ hi ráı ní should be the same as Bủ dûa jí câ hi ráı ní, since there is no change in scope, but it requires special semantics to do so?
🍵Today at 3:00 PM
this is not what I’m scared about – serial predicates and scoping in sentences where they’re present don’t bother me because they’re lightweight and predictable
(lightweight = requiring little thinking power to crack, allowing one to gain an intuitive, no-brainer understanding over time)
what I’m scared about is this:
you can’t consider râi hi rái in isolation, but only rai râi hi rái – one level up from the clause
furthermore, if you answer a question with a fragment that is a case of t5 + hi do, you’re actively transforming the asker’s sentence
and the change is not lightweight
this means that the answer doesn’t really answer the original question, but a transformed version of it
this is different from, for example, ‘ma shie súq moq’ — ‘[jeo hóq] rào dío’
because the answerer gives an explicit condition of the sentence being true, using an afterthought sentence transformer that :t6: is one of
with t5+hido, it’s nothing like that
HỏaqgīoToday at 3:06 PM
So would Dủa súq hi ráı -> câ hi dó be an example of this?
🍵Today at 3:06 PM
yes, I was going to type this exact example in right now
the question is transformed opaquely
and it’s done with what’s supposed to be the most transparent and well-behaved construct in the grammar, namely :t5:
HỏaqgīoToday at 3:08 PM
But isn't your interpretation -- that an indirect Q is just a statment in disguise -- the antedote for this problem?
In that interpretation, the sentence isn't transformed
🍵Today at 3:08 PM
antidote*?
HỏaqgīoToday at 3:08 PM
Yes
🍵Today at 3:09 PM
I’ve come to realise that indirect questions can’t be statements in disguise
they do complex stuff
all their heavy work is abstracted out into a mere collocation of a tone and a question word
so I can no longer accept an interpretation where the outer claim isn’t transformed
HỏaqgīoToday at 3:11 PM
I still don't understand what transformation is necessary
🍵Today at 3:11 PM
I, on the other hand, don’t understand how it can be not essential
of course, we can keep indirect q’s as an inanalysable construct that you’re just supposed to understand
if you find a satisfactory transformation that is bounded by the :t5:, let me know
HỏaqgīoToday at 3:13 PM
What's wrong with "what caused this" -> "that whatever caused this caused this and whatever didn't didn't"?
🍵Today at 3:13 PM
»[…] the philosophy that indirect questions are their own type of semantic object and cannot be reduced to statements to be fed into "dua".«
(this is what I’m trying to put into doubt and see if there are alternatives)
> What's wrong with "what caused this" -> "that whatever caused this caused this and whatever didn't didn't"?
there are two issues here
HỏaqgīoToday at 3:15 PM
Oh wait a second wait a second
The quantification leaks out into the outer claim, right?
🍵Today at 3:16 PM
1) bu dua jí câ hi rái -> either bu dua jí câ cá, which is a tautology, or sa dó ca3 bi bu dua jí câ dó (same problem)
yes ^^
smart one
HỏaqgīoToday at 3:16 PM
Now I see
Okay, that sucks
🍵Today at 3:17 PM
2) even if there’s a way to keep the quantification inside, there’s still relativism that ought to be remembered. I might know what caused this, but it might not be the actual things that caused this
…and implementing this behaviour would require to… know the outer predication
HỏaqgīoToday at 3:18 PM
Hmm, what now?
I don't know what you mean by that
> I might know what caused this, but it might not be the actual things that caused this
this
🍵Today at 3:20 PM
okay, let’s switch around the outer predicate:
dua jí chîaidua jí câ hi rái
we would somehow need to transform this into dua jí chîaidua jí câ + an argument phrase that would signify some referent for which the chîaidua clause holds
because we can’t substitute it with the real cá, because we know we’re supposed to be wrong about what we know
HỏaqgīoToday at 3:23 PM
Aha
So even if "I know [what caused this]" goes magically to "I know [that the candle caused this]", that breaks on "I am wrong about [what cause this]" because that will go to "I am wrong about [that the candle caused this]"
🍵Today at 3:24 PM
yes
HỏaqgīoToday at 3:25 PM
Looks like a big oof for "questions are statements in disguise" theory
🍵Today at 3:25 PM
and the ‘questions are black boxes’ theory too, unless we allow :t5: to transform their containing clauses
HỏaqgīoToday at 3:26 PM
Is that so?
"I am wrong about [what caused this]" seems fine as a black box
🍵Today at 3:27 PM
the indirect questions are black boxes theory would stand solid if either :t5: could transform the outer clauses or predicates that expect indirect q’s had rules on handling them
the latter is easier to prove the existence of a feasible implementation of, of course
HỏaqgīoToday at 3:28 PM
Oh, well yes
🍵Today at 3:28 PM
let’s call it a small oof
HỏaqgīoToday at 3:28 PM
I was counting "rules for indirect q's built into the predicate" as part of black box thoery
🍵Today at 3:28 PM
okay
then give it a better name, if you may
»indirect questions are black boxes with special handling from their receiving predicates«
HỏaqgīoToday at 3:29 PM
black box theory is the perfect name already
🍵Today at 3:29 PM
alright
HỏaqgīoToday at 3:29 PM
Just remember that "black box" is stronger than "opaque in-place transformation"
🍵Today at 3:30 PM
or maybe ‘primitive indirect question(s) theory’
which makes a looser claim
HỏaqgīoToday at 3:30 PM
Or "the amiguity approach" (predicates which can take IQs are ambiguos)
This one is stolen from a paper than was linked here
🍵Today at 3:30 PM
kay
the amiguilty approach
and its friend, the yesyouare implementation
HỏaqgīoToday at 3:31 PM
I'm wooshing
Anyhow Dủa súq hi ráı -> Bỏao jí câ hi ráı becomes sensible because now the latter is an explicit transformation of the former
🍵Today at 3:34 PM
just playing around with words
wait
how is that a transformation?
what from and what to?
HỏaqgīoToday at 3:34 PM
Well
The latter stands in for a transformation of the former
"boao jí ..." expands to "tu ... bi dua jí ..."
Thus you get the satisfying "What do you know?" -> "I know ..." without forcing quantifiers into somebody else's sentence
🍵Today at 3:36 PM
dua jí câ hi rái, then?
HỏaqgīoToday at 3:36 PM
Sure
🍵Today at 3:36 PM
alright
I was confused
HỏaqgīoToday at 3:36 PM
I mean, I propose a texture pack where dua splits into dua and boao but yes
🍵Today at 3:36 PM
make an edit for the future generations
and smile!
:camera_with_flash:
HỏaqgīoToday at 3:37 PM
:grimacing:
🍵Today at 3:37 PM
I’m okay with dua being polymorphic like it seems to be now
HỏaqgīoToday at 3:37 PM
Oops, I was making a face
🍵Today at 3:37 PM
too late
HỏaqgīoToday at 3:38 PM
But the polymorphis lets you be lazy and say câ hi ráı alone as a response
Hoemai, thoughts on this conversation?
ShủaoToday at 3:56 PM
:grimacing:
🍵Today at 4:27 PM
@Hỏaqgīo > I’m okay with dua being polymorphic like it seems to be now

exactly what I was saying.

