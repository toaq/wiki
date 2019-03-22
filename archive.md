@@toc@@

## On the format of the archive

    ## On *Title*
    
    ### date, #channel
    **mi Hoenmair**
    > I'm **Hoenmai** and this is what I say␣␣
    > This is another line of my speech␣␣
    > **Linmel** said once:
    > > **Min Linmel jip ka.**
    >
    > I find that very deep.

Mind the two spaces.

This will display as:
> ## On *Title*
> 
> ### date, #channel
> **mi Hoenmair**
> > I'm **Hoenmai** and this is what I say  
> > This is another line of my speech  
> > **Linmel** said once:
> > > **Min Linmel jip ka.**
> >
> > I find that very deep.

## On names with falling tone

### 2018-07-10, #chiejio
**mi Lim**:
> > In (NAM.1) and (NAM.2), the name after mi carries a falling tone. It can also carry any other tone. The name ends automatically when the phrase started by the name's tone ends.  
>
> I'm actually a little confused about this phrasing  
> oh, phrase means something very specific, right

**mi Hoenmair**
> `%miu` **min buf**

**mi Nuongair**
> **(mỉ bũ)**
> {λ𝑋 chua(‹bũ›, 𝑋)}().

**mi Hoenmair**
> `%miu` **min neok nip**

**mi Nuongair**
> **(mỉ {nèo ní})**
> {λ𝑋 chua(‹nèo ní›, 𝑋)}().

**mi Hoenmair**
> So here the names are **bũ** and **nèo ní**  
> An adverbial phrase and a prepositional phrase  
> the prepositional phrase ends with its noun complement (which itself ends once
> its serial verb is over and once there aren't any attached relative clauses
> anymore)  
> And then the name is automatically over

**mi Linmel**
> `%miu` **mỉ mỏq**

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
> roughly  
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
> As for frames-list.txt…  
> Since there are only a few common types in the type system (c, 0, 1, and 2), and since each word has usually only one or two slots, it happens that a lot of words have the same signature as each other.  
> (This is bolstered by the fact that Toaq tries to build patterns into the vocabulary, so many words that deal with similar concepts are given them same signature on purpose – see the triplet (**dua**, **chi**, **miu**) or (**jui**, **jao**, **leaq**, **poe**, **cuao**))   
> A frame is just a common signature that lots of words fit into. For example, the LEO frame is the signature [(c) (c 1)] – predicates whose 1-ary meaning takes just a concrete object and whose 2-ary meaning takes a concrete object and a property (a proposition with one open slot).  
> Math stuff here, don't look if you're already feeling overwhelmed 😃 : There's also the special case of the JEO frame, which has the signature [(0) (c 1)] and the special requirement that, for a predicate *P* to be in the JEO frame, it must satisfy the equivalence *P*(*x*, *y*) = *P*(**jeo**(*x*, *y*)).  We also have the MAO frame, which is defined as predicates which have a signature of [(0) (c 1)] but which don't satisfy that equality, which is named the "JEO-frame Equivalence"

## On ternary predicates

### 2019-03-13, #general

**mi Hoamgior**
> `%` **cutaq**

**mi Nuongair**
> 1–1/1 — **cutaq** + — <▯1, ▯2> are such that <x1, x2, x1> satisfy ternary relation ▯/3; ▯ does/is ▯/3 to themselves.

**mi Hoamgior**
> Here's one that was added recently  
> It's the first one I know of though  
> 2-ary properties are useful for words like **mia** (▯ satisfies property ▯ with many things) and **jeq** (▯ and ▯ satisfy property ▯ with the same thing)
> 3-ary properties aren't useful for much, as far as we've discovered


## On the low tone

### 2019-03-13, #general
**mi Hoamgior**
> Here's how ◌̀ works:
> Both ◌̀ and ◌̃ serve to create adverbials. An adverbial is a part of a sentence that makes a claim about the sentence itself (not its text, but its content).  
> Everything in Toaq is done with predicates, and adverbials are no different. Ultimately an adverbial always does its thing by taking the entire Toaq sentence, pretending is has a ◌̂ tone (that generates propositions) and sticking it into the first place of a predicate.  
> For example:  
> "**Shie jí rào kôi hó**"  
> Here, the **rao** with the ◌̀ grabs the entire rest of the sentence, throws it into a ◌̂ clause, then passes it as the x1 place to the predicate rao.  ◌̀ also has the effect of taking the following noun and passing it to the predicate as the x2 place.  
> Thus the sentence is equivalent to:  
> "**Rao (shîe jí na) kôi hó**"  
> With the originally top-level claim in parentheses  
> It means "I am awake while he/she is walking"

### 2019-03-21, #general

**mi Heukueqche**
> This would mean "it seems funny that you think so"?  
> Dủ lûaı hóq jìe súq da  

**mi Sheireq**
> %miu Dủ lûaı hóq jìe súq da  

**mi Nuogai**
> **({Dủ [lûaı <hóq (jìe súq)>]} da)**  
> [℩𝐻 : hoq(𝐻)] [℩𝑆 : suq(𝑆)] du({jie({luai(𝐻)}, 𝑆)}).  

**mi Sheireq**
> "It seems that you judge it (**hoq**) to be funny"  
> **jìe** gets the **lûai** phrase as its first argument; you could also write the sentence as **"Dủ jîe lûai hóq na súq da"**  
> %miu **Dủ jîe lûai hóq na súq da**  

**mi Nuogai**
> **({Dủ [jîe <(lûaı hóq na) súq>]} da)**  
> [℩𝐻 : hoq(𝐻)] [℩𝑆 : suq(𝑆)] du({jie({luai(𝐻)}, 𝑆)}).  

**mi Heukueqche**
> oooh yeah, because of the low tone  
> wouldn't the first argument to **jie** be **Du luai hoq**  
> how do you distinguish what part of the sentence becomes the first argument?  
**mi Sheireq**
> Take a look at example CCL.3 on toaq.org; basically, adverbs and prepositions take as their argument the content/relative clause (or entire sentence) that in which they're directly contained  
> So in this case, if you wanted **jìe** to get **dû lûai hóq** as its argument, you would say **Dủ lûai hóq na jìe súq da**  
> %miu **Dủ lûai hóq na jìe súq da**  

**mi Nuogai**
> **({Dủ [<lûaı hóq na> <jìe súq>]} da)**  
> [℩𝐻 : hoq(𝐻)] [℩𝑆 : suq(𝑆)] jie({du({luai(𝐻)})}, 𝑆).  

**mi Sheireq**
> (I love miu so much)  

**mi Heukueqche**
> I'm starting to like it too, since I'm slowly learning to interpret its output XD  
> so, the **na** finishes clauses. and the :t6: takes as argument the phrase that contains it. So, since **jie** is contained in the **luai hoq jie** clause, it takes the head of that clause. If I wanted it to take the whole sentence, I would have to end the clause earlier with a **na**, and put the **jie** after it  

**mi Sheireq**
> exactly

**mi Heukueqche**
> Thanks!!


## On the necessity of the tones

### 2019-03-13, #general
**mi Hoamgior**
> ◌̀ and ◌̃ can be excluded without too much difficulty  
> ◌̌ might be possible to get rid of, but it would take some work to prove that. It doesn't just expand to something else like those other two tones do  
> ◌̄, ◌́, ◌̉, ◌̂, and ◌ are all 100% necessary

## On implications

### 2019-03-14, #general

**mi Seamtal**
> Those are lojban words  
> * rinka = **ca**
> * nibli = **lucar**
> * krinu ≈ **mu kui**

## On ordinal compounds

### 2019-03-14, #general

**mi Hoenmair**
> I have written a possible lesson 2.  
> Also I need to add the ordinal compounds to the official dictionary.

You make ordinal compounds by concatenating the number name with the (**ko**) predicate: **shikor**, **gukor**, **saqkor**…

## On laughter and the lambda quantifier (ja)

### 2019-03-16, #general

**mi Heunkueltuar**
> jajajaja

**mi Chain**
> hahahaha\*  
> we’re in Toaqistan, sir

**mi Heunkueltuar**
> sorry, my spanish showed XD

**mi Chain**
> you don’t necessarily want to laugh with the lambda variable quantifier  
> unless it’s **ja dó ja dó ja dó ja dó**

**mi Heunkueltuar**
> would that mean XXXX?

**mi Chain**
> it would  
> kind of  

**mi Chain**
> although each of the X’s would be distinct  
> and the whole wouldn’t really mean anything without context  

[…]

**mi Heunkueltuar**
> O.O, I didn't realize that each **ja dop** would represent a different variable

**mi Chain**
> it always does  
> so, how do you differentiate between their values? by position?

**mi Chain**
> **chẻo súqjī lî sẻaq ja póq ja póq**  
> = we are reciprocal in relation λxy. x has sex with y  
> = we have sex with each other  
> = **chẻo sẻaq súqjī**

**mi Chain**
> **ja** binds variables

**mi Heunkueltuar**
> oooh, I see! and the variables are predicates?  
> like **poq** and **do**?  

**mi Chain**
> no  
> I mean, yes  
> but **poq** isn’t a variable predicate  
> if you say **ja póq**, then **poq** won’t refer to [the bound variable]  
> but **ja dó** will[, because **do** is a variable predicate]  

**mi Heunkueltuar**
> oh, its the lambda calculus  
> ok, the first **ja** means the x, the second **ja** means the y  
> I don't understand what **ja dop** refers to

**mi Chain**
> **do** doesn’t mean anything until it’s bound by a quantifier

**mi Hoenmair**
> `%miu` **lẻo jí lî nủo ja dó**

**mi Nuongair**
> **(lẻo {jí [lî <nủo (ja dó)>]})**  
> [℩𝐽 : ji(𝐽)] leo(𝐽, {λ𝑋 nuo(𝑋)}).  

**mi Chain**
> `%miu` **lẻo jí lî nủo ja póq**

**mi Nuongair**
> **(lẻo {jí [lî <nủo (ja póq)>]})**  
> [℩𝐽 : ji(𝐽)] leo(𝐽, {[λ𝑃 : poq(𝑃)] nuo(𝑃)}).  

## On Transitive and intransitive verbs
### 2019-03-16, #general

**mi Heunkueltuar**
> why are there two different words for "gather", one transitive (**tua tijeq**) and the other intransitive?  
> wait, I think I misunderstood the idea. is it the **tua** that makes **tijeq** transitive?  
**mi Hoamgior**
> Intransitive is used like "The marbles all gathered together at the bottom of the bucket"  
> Transitive is used as "I gathered together some firewood"  
> The second kind has a place for a person making the things gather  
> And yes, it's **tua** that makes it so  

**mi Heunkueltuar**
> I see, thanks!  
> could you use the intransitive **tijeq** in a toaq sentence?  

**mi Hoamgior**
> Sure!  
> "**Tinjel sa róai deon ní da**"  
> Would you like me to give the translation or do you want to work it out?  

[…]

**mi Seamtal**
> It would be better with **sho tinjel**  

**mi Hoenmair**
> **tıjēq** only means "to be in the same place", not "to gather" (which would be **sho tỉjēq**). But also, note that there is a root for "gather" (**kueq**)  

**mi Hoamgior**
> Oh  
> Then let me try again  
> "**Kuem sa róai deon ní da.**"  
> The translation is: "Eight children gather here."  

## On inflecting serials
### 2019-03-16, #general

**mi Heunkueltuar**
> I'm having trouble parsing this sentence  
> > **Chỏ jí báq nảo da.**

[…]

**mi Hoenmair**
> Probably the báq nảo part  

**mi Heunkueltuar**
> exactly  

**mi Hoenmair**
> So the trick here is  
> you can turn serial predicates into nouns, just like you can turn single predicates into nouns, using ◌́  
> But when you do this with serial predicates, only the first predicate gets that tone  
> the rest keep their falling tone  
> **bảq nảo** → **báq nảo**  
> This works with every tone  

**mi Heunkueltuar**
> so **bảq nảo** is a serial predicate, and a serial predicate can be ?conjugated? to any of the tones, and the first verb of the serial predicate gets the target tone, but the others keep the falling tone.  

**mi Hoenmair**
> Exactly.  

[…]

**mi Hoenmair**
> Inflection in Toaq happens by way of suprafixation.  

## On inflection
### 2019-03-16, #general

**mi Heunkueltuar**
> what's the name of applying a tone to a word?  

**mi Seamtal**
> suprafixation  
> i love them, and have used tones to mark the scope of affixes in one of my conlangs  

**mi Hoenmair**
> I think you can say "inflect"  

**mi Seamtal**
> Suprafixation is also broader than just tones tho  

**mi Seamtal**
> > In linguistics, a suprafix is a type of affix that gives a suprasegmental pattern (such as tone, stress, or nasalization) to either a neutral base or a base with a preexisting suprasegmental pattern. This affix will, then, convey a derivational or inflectional meaning.

**mi Hoenmair**
> I would say inflect or decline  
> But conjugate would also be understood  

**mi Seamtal**
> Suprafixation would just be applying a suprafix, so just use the above definition when archiving and uh for the others

**mi Hoenmair**
> Inflection in Toaq happens by way of suprafixation.  

### Summary
So, there are 4 words to say that a tone was applied to a predicate:  
Inflect, Decline, Conjugate, Suprafixate.


### 2019-02-24, #general

**mi Moinlul**
> suprafix — (linguistic morphology) A type of affix where a suprasegmental change (such as tone or stress) modifies an existing morpheme's meaning.  
> Ah, that's relevant to Toaq.  

## On naming time

### 2019-02-24, #luaq

A nice game of Translation of the Day :)

**mi Lim**
> I elect @Hỏemāı as the winner \^\_\^  
> (thank you for the new roots)  

**mi Chain**
> …and the new dealer  

**mi Hoenmair**
> TotD #3  
> "The train will arrive at ten o'clock, which is when I'm usually still asleep."  

**mi Lim**
> (TotD.LIQ.3)  (that's how I intended the numbering to go, for what it's worth.)  
> **Tỉshā chúe(chāo) rào héıhōrāsīao, lǔ dủq nủo jí rào hóa da.**  
> * **heıhōrā** = hour 10 of the day (the 10:00–11:00 hour), just like **shıchāq** = day 1 of the month (I already defined this in Toadua).  
> → **heıhōrāsīao** = the start of hour 10 of the day.  

**mi Seamtal**
> *n* + **horar** gives that part of the day, but *n* + **chaq** gives that part of the month? Why not that part of the week since that is the next unit up?  
> Also we have been adding numbers to subscript kinda e.g. **doshir**, **hoagur** so why not continue that and have **horarheir** and **chaqshir**?  
> **semcur shuaif keo jam chon jip lut moin sa raip pop bab damchiur**  
> Ah  
> I reread your explanation with more attention and i see why you skipped weeks, but my ordering beef still stands

**mi Lim**
>** niaqgu** is a twosome of something, a kind of **gu**, namely of consecutive years.  
> whereas **guniaq** is a kind of **niaq**, namely the second one.  

**mi Chain**
> clever, **Lim hu mi**  
> I do understand why you’d choose days-\>months instead of weeks-\>months  
> because the latter would be ill-defined  

**mi Lim**
> it also mimics Chinese/Japanese 2019年, 3月, that kinda stuff  

**mi Niuncul**
> (TotD.3.NCQ) **Jỉa tỉshā chúe lũ chảqpāqchīu kó hẻı hóa, ju dủq rảo hóa hôaı nủo jí da.**  

**mi Niuncul**
> **(soan pó mí nimdaor roi mí Lim jí bâi ru je taonroar jí tîe kúo kúqtoair nò mí Dinkor da.) (kuam hain tuan shain tien ka.)**  

**mi Hoamgior**
> (TodD.3.HGO) **Tỉshā chúe rào hórāchīu hẻı, ju dủq jí lî hỏaı nủo rào hóa da.**  

**mi Niuncul**
> **(pójībi dun huam gin mó Tỉshā jĩa teo mǔa ru je len gin tûa beon keo taonroar shoen bun hoin lun tuan beon da)**  

**mi Hoenmair**
> So should we vote or should I just declare a winner?  

**mi Niuncul**
> setting up an emoji poll by the dealer in the case of indecision sounds sufficient  

**mi Hoenmair**
> Okay, so I'll just make a decision.   
> First, some comments: I like both of the suggested systems. A downside with **Lỉq**'s system is that because it's all in the form a single compound, it is less flexible w.r.t. other complements, like questions ("at what time") and if you want to fill in things like "(at the time we agreed to meet"). I think this is easier to do with Hoaqgīo's proposal. Also conceptually, the **-sīao** in Lỉq's system bugs me a little. I'm sure the system itself is still very useful outside of specifying X o'clock, so it's still good to have no matter what.   
> Second comment: Everyone used **hoa** in the **ju** phrase, but this is illegal. It should be **maq** or **hoq**. Also, **ju** is better than **lǔ** here.   
> All things considered, I'll go with **Hoaqgīo**.  
> @Hỏaqgīo congratulations  

**mi Lim**
> oh, because it's a {noi}, not a {poi}  

**mi Hoamgior**
> Woot woot  

### 2019-02-24, #general

**mi Lim**
> To elaborate on my #luaq submission:  
>
> I've envisioned a convention where  (number)+(time unit)  is a compound for   “the *n*-th time unit within the one-level-up unit, going  second → minute → hour → day → month → year → calendar era.”  
> (skipping weeks seems okay; we have separate color-words for the weekdays, and usually weeks are not used as a date unit)  
> and  (time unit)+(number)  is a new time unit that's *n* times longer,  like  **nıaqhēı** decade, **joagū** fortnight.  
> and probably concatenating  (*m* + unit₁ + *n* + unit₂) means:   the *n*-th unit₂ of the *m*-th unit₁ (of the salient unit-above-unit₁).  
> **saqjūe pāchāq** = the 1st of March (of the year).  
> **heıcīhōrā jōhēımīnū** = 16:40 o'clock (of the day).   (would probably be written **16hōrā40mīnū** or **16h̄40m̄**)  
> now, people talk about “10 a.m.” more than they talk about the 10 a.m. – 11 a.m. hour range.  so maybe heıhōrāsīao deserves some sort of abbreviation  

**mi Lim**
> (but then again **heıshīhōrāsīao** is as many syllables as  e-le-ven o'clock !  maybe it's fine)  

**mi Niuncul**
> **m̂**, *lertcitydetrysmi* **nò** *a compound* **jufhorshurhir**  

**mi Lim**
> ja'a  

**mi Moinlul**
> With the number serial rule, **nıaqnē gủ** = the duration of two years, i.e. 2 × 365¼ days  

## On indirect questions

### 2019-03-17, #general

**mi Shủao**
> The concept of 'indirect questions' has always confused me.  
> What is this black magic?  

**mi Chain**
> what exactly about indirect questions do you find to be like black magic?  
> there is a significant difference about a question mentioned (not asked – thus ‘indirect’) in the sentence and its answer  
> ’I don't know what friends he has’ means that you don't know what would answer the question: ’What friends does he have?’  
> in English, though, you can have a (tenuously) polysemous question like ’I don't know what you're pointing at’  
> on the one hand, it can mean: ‘I don't know the thing that you're pointing at,’ so if you were pointing at Bob, I'd be saying: ’I don't know Bob’  
> on the other hand, it can mean, ‘I don't know what the answer to the question: What you're pointing at? is’  

**mi Shủao**
> But… how?!  

**mi Chain**
> thow  
> indirect questions are a concept that can't be analysed into smaller parts, and it's so by definition  
> an indirect question is a subordinate clause that pertains to an unasked question  
> and it is different from a relative clause that points to the answer of such a question  
> the Biblish ‘he who…’ might be easier to understand, I guess  
> ’I don't know him who did that’ – I don't know the person  
> ’I don't know who did that’ – I don't know the answer to the question: ‘Who did that?’  
> <https://en.wikipedia.org/wiki/Content_clause#Interrogative_content_clauses>  

**mi Shủao**
> Are there not less nonsensical methods with the same effect?  

**mi Chain**
> > [T]hey are often direct objects of verbs of cognition, reporting, and perception, but here they emphasize knowledge or lack of knowledge of one element of a fact[.]  
>
> no  
> if you have content clauses, you have to have indirect questions too  
> in case of Toaq, you have:  
> **Bủ dủa jí tâo hı ráı máq da.** – I don't know who did that.  
> **Bủ rảqdūa jí lú tảo hóa máq da.** – I don't know the one who did that.  
> **dua** can be applied to context clauses only; I used **raqdūa** here for the meaning: ‘I know of him.’  
> @**Shủao** of course, you might try making a language where, instead of indirect questions, you have predicates like ‘X doesn't know what has property Y,’ but indirect questions are handier in that they don't require you to know that you're going to use one before the moment they're stated  
> in general, every sentence with an interrogative content clause can be transformed into one with declarative content clauses only:  
> **Bủ dủa jí tâo hı ráı máq da.** (I don't know who did that.) → **Sa dó tǔq lủ tảo hóa máq bı, bủ dủa jí tâo dó máq da.** (There's somebody who did that for which I don't know to have done that.)  
> but, as you can see, the above is messy  
> and, to nitpick even further, the above transformation relies on the assumption that there is somebody who did that  
> in the end, you'd need to construct a sentence like: ‘If there isn't anybody who *X*-es, then I don't know that there is nobody who *X*-es; and if there is somebody who *X*-es, then for all people *p* such that *p* *X*-es, I don't know that *p* *X*-es’  
> or, even better: ‘For all plural constants *pp*, I know that *pp* has p-ty *X* if *pp* has p-ty *X*, and I know that *pp* doesn't have p-ty *X* if *pp* doesn't have p-ty *X*.‘  

**mi Chain**
> the need for indirect questions could also be avoided with a predicate with a definition like: ‘*X* knows what *n*-tuple of arguments satisfies *n*-ary relation *Y*’ (for any *n*, including 0)

[…]

**mi Hỏaqgīo**
> uakci, your expansion of the indirect question was wrong […]  

**mi Chain**
> @**Hỏaqgīo** therefore, I am asking to nitpick and correct  
> I should emphasise that it’s my understanding of indirect questions that I was dwelling  
> it isn’t necessarily the most elegant definition  
> I, too, would like indirect questions gone  

**mi Hỏaqgīo**
> First problem:  
> > **Bủ dủa jí tâo hı ráı máq da.** – I don't know who did that.  
> > **Bủ rảqdūa jí lú tảo hóa máq da.** – I don't know the one who did that.  
>
> These sentences aren't alike  

**mi Chain**
> I’m aware  
> what point are you trying to make here?  

**mi Hỏaqgīo**
> I'm not really making a point, unless you consider "that's wrong" to be a point  
> (Which I do – retracting incorrect information is important even if you don't have correct information to replace it with)  
> But that there wasn't my main correction  

**mi Chain**
> I was showing an example of the almost same sentence and its not so same translation  
> they were somewhat supposed to turn out as different from each other  
> but, to the main tea, please  

**mi Hỏaqgīo**
> Ah wait, I just found:  
> or, even better: ‘For all plural constants *pp*, I know that *pp* has p-ty *X* if *pp* has p-ty *X*, and I know that *pp* doesn't have p-ty *X* if *pp* doesn't have p-ty *X*.‘  
> I was going to correct you on:  
> in the end, you'd need to construct a sentence like: ‘If there isn't anybody who *X*-es, then I don't know that there is nobody who *X*-es; and if there is somebody who *X*-es, then for all people *p* such that *p* *X*-es, I don't know that *p* *X*-es’  
> But the "even better" one isn't wrong  

**mi Chain**
> are you saying that the one above is correct and the one below is wrong?  
> because if so, I agree  

**mi Hỏaqgīo**
> Yes  
> (Or slightly more accurately: that the one above is a plausible rendition. We might not go with that)  

**mi Chain**
> I didn’t say we should go with any of that – again, it’s my interpretation specifically  
> although indeed it would be beneficial to keep this definition at the back of your head and see if it works in different, more convoluted sentences  
> note, however, how such an îndirect quẻstion is dependent in meaning on the containing predication  
> which means that ◌̂ + hi dó attains special semantic powers, just like ◌̀ in Toaq and macros in Scheme  
> (not Scheme macros, because they can only operate on their own arguments and not on their surroundings, and I’m trying to make the point that ◌̂ + hi dó does transform the outer clause)  

**mi Hỏaqgīo**
> How do they transform the outer clause?  

**mi Chain**
> ‘I don’t know what caused this’ → ‘for all pp, I don’t know that pp caused this if pp caused this, and I don’t know that pp didn’t cause this if pp didn’t cause this.’  
> the italic parts are attachments onto the outer clause; moreover, this clause, with the modification (did → didn’t), is copied to make a second claim (underlined)  

**mi Hỏaqgīo**
> Hmm, I think I understand  
> Are you saying that Bủ dủa jí câ hi ráı ní should be the same as Bủ dûa jí câ hi ráı ní, since there is no change in scope, but it requires special semantics to do so?  

**mi Chain**
> this is not what I’m scared about – serial predicates and scoping in sentences where they’re present don’t bother me because they’re lightweight and predictable  
> (lightweight = requiring little thinking power to crack, allowing one to gain an intuitive, no-brainer understanding over time)  
> what I’m scared about is this:  
> you can’t consider **râi hi rái** in isolation, but only **rai râi hi rái** – one level up from the clause  
> furthermore, if you answer a question with a fragment that is a case of ◌̂ + **hi dop**, you’re actively transforming the asker’s sentence  
> and the change is not lightweight  
> this means that the answer doesn’t really answer the original question, but a transformed version of it  
> this is different from, for example, ‘**ma shie súq moq**’ — ‘**[jeo hóq] rào dío**’  
> because the answerer gives an explicit condition of the sentence being true, using an afterthought sentence transformer that ◌̀ is one of  
> with ◌̂ + **hi dop**, it’s nothing like that  

**mi Hỏaqgīo**
> So would **Dủa súq hi ráı** → **câ hi dó be** an example of this?  

**mi Chain**
> yes, I was going to type this exact example in right now  
> the question is transformed opaquely  
> and it’s done with what’s supposed to be the most transparent and well-behaved construct in the grammar, namely ◌̂  

**mi Hỏaqgīo**
> But isn't your interpretation -- that an indirect Q is just a statment in disguise -- the antidote for this problem?  
> In that interpretation, the sentence isn't transformed  

**mi Chain**
> I’ve come to realise that indirect questions can’t be statements in disguise  
> they do complex stuff  
> all their heavy work is abstracted out into a mere collocation of a tone and a question word  
> so I can no longer accept an interpretation where the outer claim isn’t transformed  

**mi Hỏaqgīo**
> I still don't understand what transformation is necessary  

**mi Chain**
> I, on the other hand, don’t understand how it can be not essential  
> of course, we can keep indirect q’s as an inanalysable construct that you’re just supposed to understand  
> if you find a satisfactory transformation that is bounded by the ◌̂, let me know  

**mi Hỏaqgīo**
> What's wrong with "what caused this" → "that whatever caused this caused this and whatever didn't didn't"?  

**mi Chain**
> »[…] the philosophy that indirect questions are their own type of semantic object and cannot be reduced to statements to be fed into "**dua**".«  
> (this is what I’m trying to put into doubt and see if there are alternatives)  

**mi Hỏaqgīo**
> What's wrong with "what caused this" → "that whatever caused this caused this and whatever didn't didn't"?

**mi Chain**
> there are two issues here

**mi Hỏaqgīo**
> Oh wait a second wait a second  
> The quantification leaks out into the outer claim, right?  

**mi Chain**
> 1) **bu dua jí câ hi rái** → either **bu dua jí câ cá**, which is a tautology, or **sa dó ca3 bi bu dua jí câ dó** (same problem)  
> yes ^^  
> smart one  

**mi Hỏaqgīo**
> Now I see  
> Okay, that sucks  

**mi Chain**
> 2) even if there’s a way to keep the quantification inside, there’s still relativism that ought to be remembered. I might know what caused this, but it might not be the actual things that caused this  
> …and implementing this behaviour would require to… know the outer predication  

**mi Hỏaqgīo**
> Hmm, what now?  
> I don't know what you mean by that  
> I might know what caused this, but it might not be the actual things that caused this
> this  

**mi Chain**
> okay, let’s switch around the outer predicate:  
> **dua jí chîaidua jí câ hi rái**  
> we would somehow need to transform this into dua jí chîaidua jí câ + an argument phrase that would signify some referent for which the chîaidua clause holds  
> because we can’t substitute it with the real cá, because we know we’re supposed to be wrong about what we know  

**mi Hỏaqgīo**
> Aha  
> So even if "I know [what caused this]" goes magically to "I know [that the candle caused this]", that breaks on "I am wrong about [what cause this]" because that will go to "I am wrong about [that the candle caused this]"  

**mi Chain**
> yes  

**mi Hỏaqgīo**
> Looks like a big oof for "questions are statements in disguise" theory  

**mi Chain**
> and the ‘questions are black boxes’ theory too, unless we allow ◌̂ to transform their containing clauses  

**mi Hỏaqgīo**
> Is that so?  
> "I am wrong about [what caused this]" seems fine as a black box  

**mi Chain**
> the indirect questions are black boxes theory would stand solid if either ◌̂ could transform the outer clauses or predicates that expect indirect q’s had rules on handling them  
> the latter is easier to prove the existence of a feasible implementation of, of course  

**mi Hỏaqgīo**
> Oh, well yes  

**mi Chain**
> let’s call it a small oof  

**mi Hỏaqgīo**
> I was counting "rules for indirect q's built into the predicate" as part of black box thoery  

**mi Chain**
> okay  
> then give it a better name, if you may  
> »indirect questions are black boxes with special handling from their receiving predicates«  

**mi Hỏaqgīo**
> black box theory is the perfect name already  

**mi Chain**
> alright  

**mi Hỏaqgīo**
> Just remember that "black box" is stronger than "opaque in-place transformation"  

**mi Chain**
> or maybe ‘primitive indirect question(s) theory’  
> which makes a looser claim  

**mi Hỏaqgīo**
> Or "the amiguity approach" (predicates which can take IQs are ambiguos)  
> This one is stolen from a paper than was linked here  

**mi Chain**
> kay  
> the amiguilty approach  
> and its friend, the yesyouare implementation  

**mi Hỏaqgīo**
> I'm wooshing  
> Anyhow **Dủa súq hi ráı** → **Bỏao jí câ hi ráı** becomes sensible because now the latter is an explicit transformation of the former  

**mi Chain**
> just playing around with words  
> wait  
> how is that a transformation?

**mi Hỏaqgīo**
> Well  
> The latter stands in for a transformation of the former  
> "**boaon jí…**" expands to "**tu … bi duan jí …**]"  
> Thus you get the satisfying "What do you know?" → "I know …" without forcing quantifiers into somebody else's sentence  

**mi Hỏaqgīo**
> I mean, I propose a texture pack where dua splits into dua and boao but yes  

**mi Chain**
> make an edit for the future generations  
> and smile!  
> 📸

**mi Hỏaqgīo**
> 😬  

**mi Chain**
> I’m okay with **dua** being polymorphic like it seems to be now  

**mi Hỏaqgīo**
> Oops, I was making a face  

**mi Chain**
> too late  

**mi Hỏaqgīo**
> But the polymorphis lets you be lazy and say **câ hi ráı** alone as a response  
> Hoemai, thoughts on this conversation?  

**mi Shủao**
> 😬  

**mi Chain**
> @Hỏaqgīo
> > I’m okay with **dua** being polymorphic like it seems to be now  
>
> exactly what I was saying.  

## the N-Word Stone

### 2019-03-17, #off-topic

**mi Seamtal**
> **tảoshāo nảıjīa kủq jí tóa pỏ nílāı da…NỦTĪRĪSHŌQHĒQCĀI GỦIBĒAQHĀQ MỦOQ GO KỦORĪBĀ (kıo hỏkēı la tủa fỏaq so dảıchī na, kùı lû nảqpīa go pó gójī rỏaqpīafū ga pảı sa ráı rǒaqpīafū sa méahēo mu pǎı sa lú gảq hóa hóı nỉq rỏaqpīafū bòı dêo na ceı jǔlū gủaıgāq hóa sa póq bǒ hóa sa kúnē pảınīaı, ju cěorīaq pỏ máq pó sa méahēo củe nǎqpāo go hóa sa lú pủ lủeq go sỏıfūaı hóa ju pủ bủagāq hó sa chíegāq rào chîetāo na ju jẽo bı chủrīe pỉafū go hó sa lú tủaobū mu pỉa hóa sa ráı mǎıpāı go hóa sa lú rào kôaqshō tì sa núı bı rảqdūa hó sa jáq pảırūo lẻaqbūe, ju lỉqfū go hó sa lú geonē sa níaqnē rỏaı hó ju chỉetūa go hó sa ráı hǎo hóı chẻ hóa mu lǐqpīa sa géonēhūaq ju pảı go hó sa lú gảq hóa bòı pó céochīejīo ga hóı lỉqpīa  lǐqpāo sa lú mu rỏaqpīafū hóa sa lú kỉqrūotāo hóa sa núı kỉq pỏ sa púı gủa ga ju fảq lû mu lỉqpīa sa náq sa lú mu lỉqpīafū hóa sa ráı mǎıpāı sa póq pǎosū sa lú pủ sẻoshō hóa sa náq gǔaı go pó sa dúaogūıjēarīaq ru těqdōa hóa sa rótī sa lú dủq tẻq hóa sa kíaqchē chǐe chẻ tẻ go bảq kỉaq hóa mu sòa sa póq mu lǐqpīa hóa sa lú to ru lủı bủadūo pèa sa dáqjāq to jãq jẻo bı rảqdūa hóa sa téqjūqchē mu pǎı hóa sa ráı mu nǎqfū hóa hóa sa lú mu lủeq hóa sa róalūeqdōa kỏqpānī cǔe go hóa sa ráı rǒaqpīafū hóa sa níq lǐe jảq bỏmīa hóa bòı jîu na kùı pó lúo ju bỏ  pó hóa sa lúeqchē mu nǎqpīa hóa sa ráı gěonē go hóa sa níaqnē shỉcēı ru chǐe hóa pó téıdīu mu gàq sa líq chǒ jãq hó hóa ju mu pảosū hó sa lú pủ chẻ gỏlūfū ju rảo kỏ gủ sa ráı hó sa súaıkōı měa go hóa sa lú mảıgēq hóa sa líq lǔı jẻa bỏ hóa sa cháo hảı mu chỏq sa póq lủ mu pỉa hóa sa lú rỉochē hóa  ju rỉoqhēaqfā pòı lủeq sa ríokōqpānī lủ põı dảı tủa pỉaq bı sẻcāq hóa gûaqtīshō**

### 2019-03-17, #general

**mi seaqtaq**
> It is a copypasta  
> namely this:  
> I’m gonna say the n word… NUTRI-GRAIN BLUEBERRY BREAKFAST GRANOLA BARS (it’s okay, my cousin’s friend has a brother who’s girlfriend has another cousin that has a childhood friend who grew up to work with a guy that has a dog who was originally from an owner that has a husband who’s father met a guy in the military that had a college roommate who actually has a half nephew who has a step brother who has a girlfriend that growing up in a small town had a friendly neighbor who had a 8 year old daughter who had a 4th grade teacher that had a student that actually had an older sister that had an old friend from preschool who’s mom had a 2nd cousin who was in a short international film that starred a guy who’s sister has a niece that has a boyfriend who had a grandmother who has an ex husband that worked in a bakery and sold bread to this guy that had a barber who learned to cut hair from this guy who has a sister that moved to Madagascar and actually knows a local cashier that had a best friend who has a son that has a health insurance provider who’s ran by a guy that’s cousins with a girl that was born into a rich family with a butler who has a 16 year old son that has a trigonometry class with this girl he likes that has a grandfather who was a professional golfer that once got second place behind a guy that was dating this girl that bought a used car from a guy that has a brother who is a pilot and flys for an airline which is surprisingly responsible for the death of some guy who got in a plane crash that before he died had a girlfriend who was an aspiring musician that made a song that this one guy tweeted about that also has a cousin who has a best friend who’s very religious and has a pastor that actually eats nutri-grain breakfast bars. Oh and who’s black)  
> Now yall other humans can practice your vietoaq more [note: the original was in Vietoaq]  
> There are a few errors in my translation I have noticed, but i sped through this one (≈45mins) so i am not too worried  
> I also had to coin some stuff on the fly and quite hastily, like **temjulcher** for cashier  

## On water, waters, and the idea of water

### 2019-03-18, #general

**mi Heunkueltuar**
> in the meantime, I have another question about this sentence **Chỏ jí báq nảo da.**  
> I don't understand why the bab is necesary to say "I like water"  
> wouldn't **Chon jip naop da** be enough?  

**mi Hỏaqgīo**
> No  
> The reason is that **náo** means "the water"  
> So if you live by a lake, that would be appropriate to say you like the water in the lake  
> Or if somebody serves you water and asks how it is  

**mi Heunkueltuar**
> ah, its THE water (only the one referred to at the moment. This water), not water in general  

**mi Hỏaqgīo**
> Yes  
> (Though not necessarily "this" water. It could be in a cup on the table or it could be on Mars; **náo** just means "the water (the water we're currently talking about, not some random water)")  

**mi Heunkueltuar**
> like, the UofD?  
> well, A specific water  
> and is that different from the waters?  

**mi Hỏaqgīo**
> No  
> In fact you've hit on an important point  
> If there are multiple waters in the UoD, then náo is all of them  
> If we are talking about three lakes then **chỏ jí náo da** means I like the three lakes  

**mi Heunkueltuar**
> so the distinction is between the abstract idea of water, and any concrete instance of water  

**mi Hỏaqgīo**
> Yes, that's between **báq nảo** and **náo**  

**mi Heunkueltuar**
> is this like Plato's Forms?  

**mi Hỏaqgīo**
> I am not familiar with those 😛
> Oh wait! Yes I am  
> Yes, I think that's a good way to think about it  

[…]


**mi Heunkueltuar**
> but one last thing, with the water question. If I wanted to talk about some concrete waterS (plural), would it be like this?  
> **Chom jip naop sa da**  

**mi Hỏaqgīo**
> In any case, the answer is no 😛
> sa may be glossed as "some", but it's not a willy-nilly word like English has, it's the E quantifier  
> It's used like this:  
> **Chỏ jí sa náo da**  

**mi Heunkueltuar**
> ah, right associating?  

**mi Hỏaqgīo**
> No associating  
> This is equivalent to the logical proposition:  
> ∃*x*. *x* is-water: I like *x*  
> "There exists some *X* which is water such that: I like *X*"  
> (This *X* still could be singular or plural, it isn't specified)  

**mi Heunkueltuar**
> hm, I kinda see. So I'm just saying that there is some thing, which is water, and that I like?  
> not how many of that thing there is  

**mi Hỏaqgīo**
> Yes  
> To specify that there are multiple things, you can use the predicate puq  
> **Chỏ jí sa púq nảo da** = "I like some multiple waters"  
> Or: **Chỏq jí púq nảo da** = "I like the multiple waters"  


## On having sex with bees

### 2019-18-03, #totd

**mi Shủao**
> TotD 15: **Sẻaq sa hápī ba**.

**mi Heukueqche**
> XDDD well done! I'm proud of you (and so is that sexy, sexy bee)

**mi Chain**
> @Heukueqche @Shủao  
> it’s not ‘sexy bee,’ but ‘The bee has (is having) sex.’  
> those are two fundamentally different concepts; you can have sex despite not being sexy and you can have no sex despite being sexy  
> for ‘sexy,’ consider something like **seaqdē** (‘sexually beautiful’)  

**mi Shủao**
> @🍵 Fuck bees.

[...]

**mi Shủao**
> "Fuck bees."  
> The (meme) phrase I tried to translate; directed at no specific person, yet imperative.  
> ... perhaps there should be a specific quantifier on **hápī**, and I'm not sure about nothing filling the second spot, but it's nice to have it concise too.  

**mi Chain**
> @Shủao and you’re right. the correct v. would be **Sẻaq súq sa hápī ba**.

**mi Shủao**
> Why **súq**?

**mi Chain**
> without **súq**, it could be **go**.  
> ‘May (indetermined) have sex with one or more bees.’

**mi Shủao**
> The places of **seaq** don't seem that specific.

**mi Chain**
> wdym

**mi Shủao**
> In the definition I saw, they seemed interchangable.

**mi Chain**
> **seaq**, I believe, is symmetric.

**mi Shủao**
> Then the **go** would be redundant, would it not?

**mi Chain**
> well then, **seaq go hápi** would suffer from the same issue as **seaq hápi**  
> I guess it’s only fair to assume that the **go** omits an implied **suq**, or whoever the command is actually directed towards.

**mi Shủao**
> It's not directed towards anyone, as I said.

**mi Chain**
> **seaq sa póq sa hápi ba** = may somebody fuck a bee  

**mi Shủao**
> I'm not telling people to go out and fuck bees, I'm just telling bees to get fucked.

**mi Chain**
> okay then, **seaq hápi ba**, then
>

**mi Shủao**
> No more **sa**?  

**mi Chain**
> oh yes, **sa**

**mi Shủao**
> Would **tu** be bad in place of **sa**?

**mi Chain**
> **tu** would be bad
> as it would imply all sets of bees

**mi Shủao**
> Fuck 'em all.  
> Pokémon style.

**mi Chain**
> catch ‘em all first.

## On beer and expanding serial predicates

## 2019-03-18, #general

**mi Heukueqche**
> On the serial expansion of **Bủ chỏ jí báq bỉrā da.**
> would it be:  
> **Bun chot jip bad ja dop biprar da** 

**mi Hỏemāı**
> **bâq** is not correct  
> If you want to expand the argument phrase (**báq bỉrā**) as well, then:  
> **Bủ chô jí lú bảq bỉrā hóa da**

**mi Chain**
> you didn’t expand it  

**mi Hỏemāı**
> There is also another solution using binary **bủ**, but I see no point  
> Yes true  

**mi Chain**
> **lú baq hóa lî bira ja dó**

**mi Hỏemāı**
> Yes, that.  
> **Bủ chô jí lú bảq hóa bîrā ja dó**
> or **Bủ chô jí lú bảq hóa lî bỉrā ja dó**

**mi Chain**
> `%nui` **bu pai go baq rai**

**nuogai**
> (`(#f)` . **lî ja dóshī bı bủ dóshī lî ja dógū bı pảı dógū sa lí ja dósāq bı bảq dósāq lî ja dójō bı rảı dójō**)  

[…]

**mi Chain**
> (by the way, they are the same)  

**mi Heukueqche**
> might you tell us the binary solution, @**Hỏemāı** ? different versions of the same thing help a lot to learn  

**mi Hỏemāı**
> It's what **miu** would give if it knew **cho**

**mi Chain**
> see what it does with **bu pai**
> `%nui` **bu pai**

**nuogai**
> (`(#f #f)` . **lî ja dóshī ja dógū bı bủ dóshī lî ja dósāq bı pảı dósāq dógū)**

**mi Chain**
> **bu *x₁* lî pai ja dó *x₂* **, essentially  

**mi Hỏaqgīo**
> `%serial` **bu pai**

**nuogai**
> <`[c c]` (**bủ A pâi ja dó B**)>  

**mi Chain**
> @**Heukueqche**
> in general, **bu** is binary in serial predicates, so it would work as ‘x1 doesn’t satisfy property of being a friend to x2,’ instead of ‘it isn’t the case that x1 is a friend of x2’  
> however these are equal by virtue of the ‘JEO-frame equivalence’ we all know and love  
> `%serial` **bu mai**

**nuogai**
> <`[c c]` (**bủ A mâi ja dó B**)>  

**mi Chain**
> `%nui` **bu mai**

**nuogai**
> (`(#f #f)` . **lî ja dóshī ja dógū bı bủ dóshī lî ja dósāq bı mảı dósāq dógū**)

**mi Chain**
> @**Heukueqche** if you examine this definition closely, you should get this:  
> λ*a b*. **bu**(*a*, λ*x*. **pai**(*x*, *b*))  

## On a Complete Grammar

### 2019-03-19, #general


**mi Z Mo**
> Hey, I was wondering, how do you ensure that the grammar is actually flexible enough / covers all possibilities etc  

**mi Chain**
> what do you mean?  

**mi Z Mo**
> How do you know you've finished the grammar?  

**seaqtaq**
> We don't, I mean can you ever know? We don't even think that is the case as we have lists of things we cannot do  
> like measuring and telling time, the big ones  
> Normally and seemingly someone has been doing irl things until their brain is like "Hey, somethings wrong with toaq, alert the others ASAP," or something similar. Another way of finding out that we just can't say something (the way we would like) is by doing translations  
> But that includes grammar and vocab ofc  

**mi Hỏemāı**
> The grammar is complete in that you can already say everything using the current available syntax.  
> Making words for measurements is not a matter of grammar.  
 
 **seaqtaq**
> > But that includes grammar and vocab ofc  
> Ah nope, that doesnt work  

**mi Hỏemāı**
> Serial predicates alone have unlimited expressive power.  
> The only way in which the grammar could be incomplete at this point would be a missing terminator (if we find an ambiguity in the syntax).  
> So, how do I know the grammar is finished? I know, because I know what my vision for the grammar was and I made the grammar exactly as I wanted.  
> Writing the PEG grammar was one of the necessary steps from vision to reality.  
> Since we have a working parser which can parse any sentence I would deem correct and rejects ones I would reject (with only very minor exceptions which are due to oversights or due to minor syntax/morphology changes between beta and now), we can use that as another measurement for completeness.  

**mi Z Mo**
Thanks, that's actually pretty insightful


## On Corrections and Connections (huq)

### 2019-03-20, #chiejio

**mi Xylochoron**
> Is there a word for making corrections  
> Like “si” in Lojban,  

**mi Shủao**
> **huq**?  

**mi Xylochoron**
> Oh ok! Cool  
> So that’s where you replace one word with another  
> That seems very useful and works for what I’m trying to do, but  
> Now I’m wonder if you really wanted to erase something but not replace it with a new thing how that would work shrugs  
> Also I’m imagining some confusion in the details of how it works  
> If you want to replace one whole phrase with another whole phrase,  
> Like I mean what if you said an argument word but you meant to say a predicate word, could you do a replacement? How in the structure of **huq** would you say you want to replace an argument with a predicate, it seems the grammar might get tricky, I dunno  
> Maybe anything in **huq** has to go in quotes? And the quotes are removed before replacement?  

**mi Hỏaqgīo**
> I've just coined **è**, an interjection whose purpose is to erase "some" words  
> It doesn't always erase the same number of words or even the same kind of phrase; it cues the listener to figure it out based on context  
> Thus **Hảı dủa jí, è súq** would likely replace **jí** with **súq**, whereas **Mỉu súq jâq dẻ, è, hi ráı pa mỉu súq jâq dẻ ráı moq?** starts the sentence over.  

[...]

### Summary

**mi Heukueqche**
> ok, I'm feeling like summarizing. On Xylochoron's idea, of correcting mistakes in speech. They wanted to correct arbitrary arguments and phrases, and **huq** does that job (by replacing the left hand argument with the right hand argument). But it is ambiguous with phrases and single arguments. So Hoamgior coined **ek** to erase words. **Ek** is not precise, it just cues the listener to replace based on context.  


## On Single Words and Interjections

### 2019-03-20, #chiejio

**mi Hỏaqgīo**
> I've just coined **è**, an interjection whose purpose is to erase "some" words  
> It doesn't always erase the same number of words or even the same kind of phrase; it cues the listener to figure it out based on context  
> Thus **Hảı dủa jí, è súq** would likely replace **jí** with **súq**, whereas **Mỉu súq jâq dẻ, è, hi ráı pa mỉu súq jâq dẻ ráı moq?** starts the sentence over.  

**mi Xylochoron**
> But every word in Toaq starts with a non-“q” consonant so that one can tell where a root starts and ends without listening for pauses, or...?  

**mi Hỏaqgīo**
> Yes, there is that  
> E.g. **dẽ** sounds exactly like **dè   é** if you don't pause  
> But Hoemai has declared that the lone vowels, paired with tones, will be interjections, so I think they want us to just pause before them  
> To make it unambiguous  

**mi Xylochoron**
> Oh, ok!  
> Gotta be careful picking them I guess, since there’s only 5 total :stuck_out_tongue:  

**mi Shủao**
> I think that does work, given the tones, unambiguously.  

[...]


**mi Xylochoron**
> Can you have dipthong words, like “iao” by itself  
> Or “iaq”  

[...]


**mi Heukueqche**
> from what I remember, Hoemai doesn't want tones to carry semantic meaning, only grammatical meaning.  
> So, no matter what tone you use, **hapi** always means bee. But it can be a verb, a noun, a dependent clause, and any other kind of grammatical role  

**seaqtaq**
> He does seem to want this with interjections  
> Just look at the m-interjections  

[...]

**mi Heukueqche**
> [so, for (a u i o e, m l r) there are]  
> (5+3)\*7=56 interjections  

## On Pain

## 2019-03-20, #general

**seaqtaq**
> **mm**
> Well on to the next thing while I have your heliosic attention, the **kieq vs **kieqge** and **noi vs **noilie** thing brings me terrible memories of esperanto  
> Ah yes, reversability!  
> That thing where you had to remember the inherent part of speech of every root in order to properly apply derivational affixes  
> That sucked  

**mi Hỏemāı**
> I see  
> I  t h i n k  the reason for **noi** being defined as it is had to do with pain being in a specific place (?)  
> like, **noi** is not just **lû noilie**  
> or **noilietue**  
> but the locus etc  

**seaqtaq**
> Like the lojban word...  

**mi Hỏemāı**
> The Lojban word has the experiencer in x1, which is what you want  
> **noi**1 is the pain  
> (as defined)  
> With **noi** you can say "a pain"  

**seaqtaq**
> But if **noi** were **noilie**, could you not just say **noige**?  
> Or if you find **ge** you be ugly, the "base" of this and related words would be **ge** and we would from there apply **lie**  

**mi Hỏemāı**
> I think **noıgē** would be like the impact of a hammer hitting your thumb  

**seaqtaq**
> **m̄**  
> m̌akes sense  
> Well, I do not rest my case as a solution hasn't been found if it is even possible, but I rest my case.  
> for now ofc  

**mi Hỏemāı**
> The case of "my leg hurts" remains problematic.  

**seaqtaq**
> Oh you are still here, and I agree. Maybe something like **huatī**?  
> Just made that up on the spot so it may not exactly be the best, but I am now trying to think of a definition for that.  
> My leg is the source of my pain? Using **ceoriaq** or something less physical?  
> **nỏı tì gójī shỉaq**  

**mi Hỏemāı**
> Indeed, **tì** alone doesn't work.  

## On Starting words with Vowels or glottal stops

### 2019-03-21, #chiejio

**mi Xylochoron**
> I’m still curious if words like “iaq” will be an option at some point......  

**mi Hỏemāı**
> Words cannot begin with a vowel or glottal stop, because it would be ambiguous with the :t7: tone in environments such as **dẽ** vs **dè é**  
> That's why the currently-proposed interjections have to be considered extra-linguistic or at least grammar-adjacent, the way that laughter or inflating your cheeks with air and the expelling it (to show relief) are meaningful signals, but not grammatical signals, but rather socio-cultural signals.  


## On Voldemort, Zombies, and Cereal Killers.
## Or, Running from the dead, and inflecting serial predicates.

### 2019-03-21, #general



**mi Heukueqche**
> flee from death: **bủıfā go cúaq mủaq**  

**mi Sheireq**
> I would go with just **"rỉeq mủaq"**  
> possibly prefixed with **"dảqmīq"**  

**mi Heukueqche**
> **dảqmíq Rỉeq mủaq**  

**mi Sheireq**
> Yeah; **lẻo rỉeq mủaq báq pỏq**  
> **Keo bủ lẻo dảqmīq rỉeq mủaq báq pỏq**  

**mi Heukueqche**
> **lẻo rỉeq mủaq báq pỏq**  
> woud that mean "tries to avoid the many dead"  
> or: avoids zombies?  
> and how does the keo bun changes the phrase? "but doesnt' try to avoid the many dead"?  

**mi Sheireq**
> **"Keo bủ lẻo dảqmīq rỉeq mủaq"** = "But does-not try-to eternally avoid-satisfying-the-property-of being-dead"  

**mi Sheireq**
> For "avoid" in the sense of "avoid the zombies" you'd want **"rỉeq tỉjūi"** = "☆ avoids being near / in the vicinity of ☆"  

**mi Heukueqche**
> ah, I see. You extend the meaning with a serial predicate  
> **Rỉeq tỉjūı mủaq pỏq nı**  

**mi Heukueqche**
> would that mean "avoids being near to the dead person over there"?  

**mi Sheireq**
> I think it means "☆ avoids being near ☆ and being a dead person"  
> **Rỉeq tỉjūi ☆ ní mủaq pỏq** = ☆ avoids being near that dead person  

**mi Heukueqche**
> **Rỉeq tỉjūı jí ní mủaq pỏq**  

**mi Heukueqche**
> "I avoid being near that dead person"?  

**mi Sheireq**
> Jẻo da!  

**mi Heukueqche**
> : D thanks!  
> oh, yeah, **ní** is a predıcate, and its argument is the serial predıcate **mủaq pỏq**  

**mi Hỏemāı**
> More like, **ní mủaq pỏq** is what you get when you apply the :t2: tone to the serial predicate **nỉ mủaq pỏq**  

**mi Heukueqche**
> oh! I see!!! thanks. You first make the serial predicate, and then you transform it into a noun XD thanks!!!!  

