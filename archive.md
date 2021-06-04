@@toc@@

## On the format of the archive

    ## On *Title*
    
    ### date, #channel
    **mı hỏemāı**
    > I'm **hỏemāı** and this is what I say␣␣
    > This is another line of my speech␣␣
    > **lỉmēq** said once:
    > > **mỉ lỉmēq jí ka.**
    >
    > I find that very deep.

Mind the two spaces.

This will display as:
> ## On *Title*
> 
> ### date, #channel
> **mı hỏemāı**
> > I'm **hỏemāı** and this is what I say  
> > This is another line of my speech  
> > **lỉmēq** said once:
> > > **mỉ lỉmēq jí ka.**
> >
> > I find that very deep.

## On names with falling tone

### 2018-07-10, #chiejio
**mı lỉq**:
> > In (NAM.1) and (NAM.2), the name after mi carries a falling tone. It can also carry any other tone. The name ends automatically when the phrase started by the name's tone ends.  
>
> I'm actually a little confused about this phrasing  
> oh, phrase means something very specific, right

**mı hỏemāı**
> `%miu` **mỉ bũ**

**mı nủogāı**
> **(mı̉ bũ)**
> {λ*X* **chua**(‹**bũ**›, *X*)}().

**mı hỏemāı**
> `%miu` **mỉ nèo ní**

**mı nủogāı**
> **(mı̉ {nèo nı́})**
> {λ*X* **chua**(‹**nèo nı́**›, *X*)}().

**mı hỏemāı**
> So here the names are **bũ** and **nèo nı́**  
> An adverbial phrase and a prepositional phrase  
> the prepositional phrase ends with its noun complement (which itself ends once
> its serial verb is over and once there aren't any attached relative clauses
> anymore)  
> And then the name is automatically over

**mı lỉmēq**
> `%miu` **mı̉ mỏq**

**mı nủogāı**
> syntax error :1.7: want [bB], [cC], [dD], [fF], [gG], [hH], [jJ], [kK], [lL], [mM], [nN], [pP], [rR], [sS], or [tT]; got EOF

**mı lỉq**
> so, if my name is **lỉq**, that tone is part of the name? as in, **mı líq** and **mı lĩq** are different persons

**mı hỏemāı**
> Unless you also go by those names

**mı lỉq**
> right

**mı hủaqchī**
> That’s the difference between Ms. Being a female, Ms. A Female and Ms. Femininely  
> roughly  
> zo’orei

### 2019-03-07, #general
**mı sẻaqtāq**
> Anyhow normally you will find a name in the fourth tone

### 2019-03-08, #general
**mı nỉucūq**
> **m̂**, fragments of terms and serial predicates also can be taken as a name/phrase by **mı**/**shu**

### Summary
Names can have any tone, but the most common one is the fourth tone.
Two names with the same word, but different tones are technically different names (**mı lỉq** ≶ **mı líq** ≶ **mı lĩq**).

## On frames and signatures 

This file contains most of the common frames.    
[frames-list.txt](https://github.com/acotis/serial-predicate-engine/blob/master/code/dict/frame-list.txt)

### 2019-03-08, #general
**mı hỏaqgīo**
> As for frames-list.txt…  
> Since there are only a few common types in the type system (c, 0, 1, and 2), and since each word has usually only one or two slots, it happens that a lot of words have the same signature as each other.  
> (This is bolstered by the fact that Toaq tries to build patterns into the vocabulary, so many words that deal with similar concepts are given them same signature on purpose – see the triplet (**dua**, **chı**, **mıu**) or (**juı**, **jao**, **leaq**, **poe**, **cuao**))   
> A frame is just a common signature that lots of words fit into. For example, the LEO frame is the signature [(c) (c 1)] – predicates whose 1-ary meaning takes just a concrete object and whose 2-ary meaning takes a concrete object and a property (a proposition with one open slot).  
> Math stuff here, don't look if you're already feeling overwhelmed 😃 : There's also the special case of the JEO frame, which has the signature [(0) (c 1)] and the special requirement that, for a predicate *P* to be in the JEO frame, it must satisfy the equivalence *P*(*x*, *y*) = *P*(**jeo**(*x*, *y*)).  We also have the MAO frame, which is defined as predicates which have a signature of [(0) (c 1)] but which don't satisfy that equality, which is named the "JEO-frame Equivalence"

### 2019-03-21, #general


**mı hẻukūeqchē**
> also, what does it mean for a slot to be concrete?  

**mı hỏaqgı̄o**
> In general, slot types do define what type of argument goes into a slot  
> So, a 1 slot always takes a property with one hole, like **lı̂ mảı ja dó súq**  
> And a 2 slot always takes a property with two holes, like **lı̂ paı ja dó ja dó**  
> And a 0 slot takes a proposition, like **lû koaq hó**  
> But a c slot can take anything -- properties, propositions, persons, potatoes  
> The defining characteristic of a c slot is that, during the formation of serial predicates, it's treated as though it isn't an abstraction of any kind  
> In **dua maı**, you end up with **mâi** (a proposition) being inserted into the second slot of **dua**, because that slot is a 0 slot  
> In **de maı**, nothing is inserted into anything, because **de**'s slot is a c slot  
> `%serial` **dua maı**  

**mı nủogāı**
> <`[c c c]` (**dủa a mâi b c**)>  

**mı hỏaqgı̄o**
> `%serial` **de maı**  

**mı nủogāı**
> <`[c c]` (**lủ to ru dẻ a na to mải a b**)>  

**mı hẻukūeqchē**
> ok… I'll tell you what I got:  
> Slot types restrict what kind of argument goes into it (whether property, proposition, relation, etc…)  
> and the c type is the most permissive of them all, it can take any type?  

**mı hỏaqgı̄o**
> Those sentences are true  
> But the real essence of slot types is that they define what happens during serialization  
> The 0 type sucks up a proposition, while the c type doesn't  

**mı hẻukūeqchē**
> so its a dynamic thing. WHEN you're making serial predicates, all this slot type comes into play  
> so, frames are a way to define the characteristics of serial predicates?  

**mı hỏaqgı̄o**
> Yes  

### 2019-03-21, #general

**mı hẻukūeqchē**
> **mı̉o lı̉ bỏkē nı́ da**  
> would that mean "that is a blue cow"?  

**mı hỏaqgı̄o**
> **"mıorēo bokē nı́ da"**  
> **mıo** is the color blue, **mıorēo** is something that's blue  
> No need for **lı**  
> (Words with just one slot of the c type combine with a simple AND: blue-and-a-cow = "blue cow")  

## On ternary predicates

### 2019-03-13, #general

**mı hỏaqgīo**
> `%` **cutaq**

**mı nủogāı**
> 1–1/1 — **cutaq** + — <▯1, ▯2> are such that <x₁, x₂, x₁> satisfy ternary relation ▯/3; ▯ does/is ▯/3 to themselves.

**mı hỏaqgīo**
> Here's one that was added recently  
> It's the first one I know of though  
> 2-ary properties are useful for words like **mıa** (▯ satisfies property ▯ with many things) and **jeq** (▯ and ▯ satisfy property ▯ with the same thing)
> 3-ary properties aren't useful for much, as far as we've discovered


## On the low tone

### 2019-03-13, #general
**mı hỏaqgīo**
> Here's how ◌̀ works:
> Both ◌̀ and ◌̃ serve to create adverbials. An adverbial is a part of a sentence that makes a claim about the sentence itself (not its text, but its content).  
> Everything in Toaq is done with predicates, and adverbials are no different. Ultimately an adverbial always does its thing by taking the entire Toaq sentence, pretending is has a ◌̂ tone (that generates propositions) and sticking it into the first place of a predicate.  
> For example:  
> "**shıe jı́ rào kôi hó**"  
> Here, the **rao** with the ◌̀ grabs the entire rest of the sentence, throws it into a ◌̂ clause, then passes it as the x₁ place to the predicate rao.  ◌̀ also has the effect of taking the following noun and passing it to the predicate as the x₂ place.  
> Thus the sentence is equivalent to:  
> "**rao (shı̂e jı́ na) kôi hó**"  
> With the originally top-level claim in parentheses  
> It means "I am awake while he/she is walking"

### 2019-03-21, #general

**mı hẻukūeqchē**
> This would mean "it seems funny that you think so"?  
> **dủ lûaı hóq jı̀e súq da**

**mı shẻırēq**
> `%miu` **dủ lûaı hóq jı̀e súq da**  

**mı nủogāı**
> **({dủ [lûaı <hóq (jı̀e súq)>]} da)**  
> \[℩*H* : **hoq**(*H*)\] \[℩*S* : **suq**(*S*)\] **du**({**jıe**({**luaı**(*H*)}, *S*)}).  

**mı shẻırēq**
> "It seems that you judge it (**hoq**) to be funny"  
> **jı̀e** gets the **lûai** phrase as its first argument; you could also write the sentence as **"dủ jı̂e lûai hóq na súq da"**  
> `%miu` **dủ jı̂e lûai hóq na súq da**  

**mı nủogāı**
> **({dủ [jı̂e <(lûaı hóq na) súq>]} da)**  
> \[℩*H* : **hoq**(*H*)\] \[℩*S* : **suq**(*S*)\] **du**({**jıe**({**luaı**(*H*)}, *S*)}).  

**mı hẻukūeqchē**
> oooh yeah, because of the low tone  
> wouldn't the first argument to **jıe** be **du luaı hoq**  
> how do you distinguish what part of the sentence becomes the first argument?  
**mı shẻırēq**
> Take a look at example CCL.3 on toaq.org; basically, adverbs and prepositions take as their argument the content/relative clause (or entire sentence) that in which they're directly contained  
> So in this case, if you wanted **jı̀e** to get **dû lûai hóq** as its argument, you would say **dủ lûai hóq na jı̀e súq da**  
> `%miu` **dủ lûai hóq na jı̀e súq da**  

**mı nủogāı**
> **({dủ [<lûaı hóq na> <jı̀e súq>]} da)**  
> \[℩*H* : **hoq**(*H*)\] \[℩*S* : **suq**(*S*)\] **jıe**({**du**({**luaı**(*H*)})}, *S*).  

**mı shẻırēq**
> (I love miu so much)  

**mı hẻukūeqchē**
> I'm starting to like it too, since I'm slowly learning to interpret its output XD  
> so, the **na** finishes clauses. and the ◌̀ takes as argument the phrase that contains it. So, since **jıe** is contained in the **luaı hoq jıe** clause, it takes the head of that clause. If I wanted it to take the whole sentence, I would have to end the clause earlier with a **na**, and put the **jıe** after it  

**mı shẻırēq**
> exactly

**mı hẻukūeqchē**
> Thanks!!


## On the necessity of the tones

### 2019-03-13, #general
**mı hỏaqgīo**
> ◌̀ and ◌̃ can be excluded without too much difficulty  
> ◌̌ might be possible to get rid of, but it would take some work to prove that. It doesn't just expand to something else like those other two tones do  
> ◌̄, ◌́, ◌̉, ◌̂, and ◌ are all 100% necessary

## On implications

### 2019-03-14, #general

**mı sẻaqtāq**
> Those are lojban words  
> * rinka = **ca**
> * nibli = **lucā**
> * krinu ≈ **mu kuı**

## On ordinal compounds

### 2019-03-14, #general

**mı hỏemāı**
> I have written a possible lesson 2.  
> Also I need to add the ordinal compounds to the official dictionary.

You make ordinal compounds by concatenating the number name with the (**ko**) predicate: **shıkō**, **gukō**, **saqkō**…

## On laughter and the lambda quantifier (ja)

### 2019-03-16, #general

**mı hẻukūeqchē**
> jajajaja

**mı chảı**
> hahahaha\*  
> we’re in Toaqistan, sir

**mı hẻukūeqchē**
> sorry, my spanish showed XD

**mı chảı**
> you don’t necessarily want to laugh with the lambda variable quantifier  
> unless it’s **ja dó ja dó ja dó ja dó**

**mı hẻukūeqchē**
> would that mean XXXX?

**mı chảı**
> it would  
> kind of  

**mı chảı**
> although each of the X’s would be distinct  
> and the whole wouldn’t really mean anything without context  

[…]

**mı hẻukūeqchē**
> O.O, I didn't realize that each **ja dó** would represent a different variable

**mı chảı**
> it always does  
> so, how do you differentiate between their values? by position?

**mı chảı**
> **chẻo súqjı̄ lı̂ sẻaq ja póq ja póq**  
> = we are reciprocal in relation λxy. x has sex with y  
> = we have sex with each other  
> = **chẻo sẻaq súqjı̄**

**mı chảı**
> **ja** binds variables

**mı hẻukūeqchē**
> oooh, I see! and the variables are predicates?  
> like **poq** and **do**?  

**mı chảı**
> no  
> I mean, yes  
> but **poq** isn’t a variable predicate  
> if you say **ja póq**, then **poq** won’t refer to [the bound variable]  
> but **ja dó** will[, because **do** is a variable predicate]  

**mı hẻukūeqchē**
> oh, its the lambda calculus  
> ok, the first **ja** means the x, the second **ja** means the y  
> I don't understand what **ja dó** refers to

**mı chảı**
> **do** doesn’t mean anything until it’s bound by a quantifier

**mı hỏemāı**
> `%miu` **lẻo jı́ lı̂ nủo ja dó**

**mı nủogāı**
> **(lẻo {jı́ [lı̂ <nủo (ja dó)>]})**  
> \[℩*J* : ji(*J*)\] **leo**(*J*, {λ*X* **nuo**(*X*)}).  

**mı chảı**
> `%miu` **lẻo jı́ lı̂ nủo ja póq**

**mı nủogāı**
> **(lẻo {jı́ [lı̂ <nủo (ja póq)>]})**  
> \[℩*J* : **jı**(*J*)\] **leo**(*J*, {\[λ*P* : **poq**(*P*)\] **nuo**(*P*)}).  

## On Transitive and intransitive verbs
### 2019-03-16, #general

**mı hẻukūeqchē**
> why are there two different words for "gather", one transitive (**tua tıjeq**) and the other intransitive?  
> wait, I think I misunderstood the idea. is it the **tua** that makes **tıjeq** transitive?  
**mı hỏaqgīo**
> Intransitive is used like "The marbles all gathered together at the bottom of the bucket"  
> Transitive is used as "I gathered together some firewood"  
> The second kind has a place for a person making the things gather  
> And yes, it's **tua** that makes it so  

**mı hẻukūeqchē**
> I see, thanks!  
> could you use the intransitive **tıjeq** in a toaq sentence?  

**mı hỏaqgīo**
> Sure!  
> "**tỉjēq sa róai dẻo nı́ da**"  
> Would you like me to give the translation or do you want to work it out?  

[…]

**mı sẻaqtāq**
> It would be better with **sho tỉjēq**  

**mı hỏemāı**
> **tıjēq** only means "to be in the same place", not "to gather" (which would be **sho tı̉jēq**). But also, note that there is a root for "gather" (**kueq**)  

**mı hỏaqgīo**
> Oh  
> Then let me try again  
> "**kủeq sa róai dẻo nı́ da.**"  
> The translation is: "Eight children gather here."  

## On inflecting serials
### 2019-03-16, #general

**mı hẻukūeqchē**
> I'm having trouble parsing this sentence  
> > **chỏ jı́ báq nảo da.**

[…]

**mı hỏemāı**
> Probably the báq nảo part  

**mı hẻukūeqchē**
> exactly  

**mı hỏemāı**
> So the trick here is  
> you can turn serial predicates into nouns, just like you can turn single predicates into nouns, using ◌́  
> But when you do this with serial predicates, only the first predicate gets that tone  
> the rest keep their falling tone  
> **bảq nảo** → **báq nảo**  
> This works with every tone  

**mı hẻukūeqchē**
> so **bảq nảo** is a serial predicate, and a serial predicate can be ?conjugated? to any of the tones, and the first verb of the serial predicate gets the target tone, but the others keep the falling tone.  

**mı hỏemāı**
> Exactly.  

[…]

**mı hỏemāı**
> Inflection in Toaq happens by way of suprafixation.  

### 2019-04-13, #general

**mı mỏılūq**
> **kảqgāı jı́ chı́e** = I see the learner(s)  
> **kảqgāı jı́ chı̉e** = I, who learn, see  
> notice the tone change on **chıe**  
> A falling ʔ tone elsewhere than at the beginning of a sentence indicates an addition to a serial predicate  
> so in the second sentence, there's a serial **jı chỉe** converted into a noun with the raising / tone on the first word  
> in a serial, the tone on the first word indicates the role of the whole serial in the sentence  


## On inflection
### 2019-03-16, #general

**mı hẻukūeqchē**
> what's the name of applying a tone to a word?  

**mı sẻaqtāq**
> suprafixation  
> i love them, and have used tones to mark the scope of affixes in one of my conlangs  

**mı hỏemāı**
> I think you can say "inflect"  

**mı sẻaqtāq**
> Suprafixation is also broader than just tones tho  

**mı sẻaqtāq**
> > In linguistics, a suprafix is a type of affix that gives a suprasegmental pattern (such as tone, stress, or nasalization) to either a neutral base or a base with a preexisting suprasegmental pattern. This affix will, then, convey a derivational or inflectional meaning.

**mı hỏemāı**
> I would say inflect or decline  
> But conjugate would also be understood  

**mı sẻaqtāq**
> Suprafixation would just be applying a suprafix, so just use the above definition when archiving and uh for the others

**mı hỏemāı**
> Inflection in Toaq happens by way of suprafixation.  

### Summary
So, there are 4 words to say that a tone was applied to a predicate:  
Inflect, Decline, Conjugate, Suprafixate.


### 2019-02-24, #general

**mı mỏılūq**
> suprafix — (linguistic morphology) A type of affix where a suprasegmental change (such as tone or stress) modifies an existing morpheme's meaning.  
> Ah, that's relevant to Toaq.  

## On naming time

### 2019-02-24, #luaq

A nice game of Translation of the Day :)

**mı lỉq**
> I elect @Hỏemāı as the winner \^\_\^  
> (thank you for the new roots)  

**mı chảı**
> …and the new dealer  

**mı hỏemāı**
> TotD #3  
> "The train will arrive at ten o'clock, which is when I'm usually still asleep."  

**mı lỉq**
> (TotD.LIQ.3)  (that's how I intended the numbering to go, for what it's worth.)  
> **tı̉shā chúe(chāo) rào héıhōrāsı̄ao, lǔ dủq nủo jı́ rào hóa da.**  
> * **heıhōrā** = hour 10 of the day (the 10:00–11:00 hour), just like **shıchāq** = day 1 of the month (I already defined this in Toadua).  
> → **heıhōrāsı̄ao** = the start of hour 10 of the day.  

**mı sẻaqtāq**
> *n* + **horā** gives that part of the day, but *n* + **chaq** gives that part of the month? Why not that part of the week since that is the next unit up?  
> Also we have been adding numbers to subscript kinda e.g. **doshī**, **hoagū** so why not continue that and have **horāhēı** and **chaqshī**?  
> **sẻqcū shũaı keo jảq chỏ jí lû mỏı sa ráı pó báq dảqchīu**  
> Ah  
> I reread your explanation with more attention and i see why you skipped weeks, but my ordering beef still stands

**mı lỉq**
> **nıaqgu** is a twosome of something, a kind of **gu**, namely of consecutive years.  
> whereas **gunıaq** is a kind of **nıaq**, namely the second one.  

**mı chảı**
> clever, **lỉq hu mı**  
> I do understand why you’d choose days→months instead of weeks→months  
> because the latter would be ill-defined  

**mı lỉq**
> it also mimics Chinese/Japanese 2019年, 3月, that kinda stuff  

**mı nỉucūq**
> (TotD.3.NCQ) **jı̉a tı̉shā chúe lũ chảqpāqchı̄u kó hẻı hóa, ju dủq rảo hóa hôaı nủo jı́ da.**  

**mı nỉucūq**
> **(sỏa pó mı́ nỉqdāo roı mı́ lỉq jı́ bâi ru je tảorōa jı́ tı̂e kúo kúqtōaı nò mı́ dỉkō da.) (kủaq hảı tủa shảı tỉe ka.)**  

**mı hỏaqgīo**
> (TodD.3.HGO) **tı̉shā chúe rào hórāchı̄u hẻı, ju dủq jı́ lı̂ hỏaı nủo rào hóa da.**  

**mı nỉucūq**
> **(pójı̄bı dủ hủaq gỉ mó tı̉shā jı̃a teo mǔa ru je lẻ gỉ tûa bẻo keo tảorōa shỏe bủ hỏı lủ tủa bẻo da)**  

**mı hỏemāı**
> So should we vote or should I just declare a winner?  

**mı nỉucūq**
> setting up an emoji poll by the dealer in the case of indecision sounds sufficient  

**mı hỏemāı**
> Okay, so I'll just make a decision.   
> First, some comments: I like both of the suggested systems. A downside with **lı̉q**'s system is that because it's all in the form a single compound, it is less flexible w.r.t. other complements, like questions ("at what time") and if you want to fill in things like "(at the time we agreed to meet"). I think this is easier to do with Hoaqgīo's proposal. Also conceptually, the **-sı̄ao** in Lỉq's system bugs me a little. I'm sure the system itself is still very useful outside of specifying X o'clock, so it's still good to have no matter what.   
> Second comment: Everyone used **hoa** in the **ju** phrase, but this is illegal. It should be **maq** or **hoq**. Also, **ju** is better than **lǔ** here.   
> All things considered, I'll go with **hoaqgı̄o**.  
> @Hỏaqgīo congratulations  

**mı lỉq**
> oh, because it's a {noi}, not a {poi}  

**mı hỏaqgīo**
> Woot woot  

### 2019-02-24, #general

**mı lỉq**
> To elaborate on my #luaq submission:  
>
> I've envisioned a convention where  (number)+(time unit)  is a compound for   “the *n*-th time unit within the one-level-up unit, going  second → minute → hour → day → month → year → calendar era.”  
> (skipping weeks seems okay; we have separate color-words for the weekdays, and usually weeks are not used as a date unit)  
> and  (time unit)+(number)  is a new time unit that's *n* times longer,  like  **nıaqhēı** decade, **joagū** fortnight.  
> and probably concatenating  (*m* + unit₁ + *n* + unit₂) means:   the *n*-th unit₂ of the *m*-th unit₁ (of the salient unit-above-unit₁).  
> **saqjūe pāchāq** = the 1st of March (of the year).  
> **heıcı̄hōrā jōhēımı̄nū** = 16:40 o'clock (of the day).   (would probably be written **16hōrā40mı̄nū** or **16h̄40m̄**)  
> now, people talk about “10 a.m.” more than they talk about the 10 a.m. – 11 a.m. hour range.  so maybe heıhōrāsīao deserves some sort of abbreviation  

**mı lỉq**
> (but then again **heıshı̄hōrāsı̄ao** is as many syllables as  e-le-ven o'clock !  maybe it's fine)  

**mı nỉucūq**
> **m̂**, *lertcitydetrysmi* **nò** *a compound* **jũhōshūhī**  

**mı lỉq**
> ja'a  

**mı mỏılūq**
> With the number serial rule, **nıaqnē gủ** = the duration of two years, i.e. 2 × 365¼ days  

## On indirect questions

### 2019-03-17, #general

**mı shủao**
> The concept of 'indirect questions' has always confused me.  
> What is this black magic?  

**mı chảı**
> what exactly about indirect questions do you find to be like black magic?  
> there is a significant difference about a question mentioned (not asked – thus ‘indirect’) in the sentence and its answer  
> ’I don't know what friends he has’ means that you don't know what would answer the question: ’What friends does he have?’  
> in English, though, you can have a (tenuously) polysemous question like ’I don't know what you're pointing at’  
> on the one hand, it can mean: ‘I don't know the thing that you're pointing at,’ so if you were pointing at Bob, I'd be saying: ’I don't know Bob’  
> on the other hand, it can mean, ‘I don't know what the answer to the question: What you're pointing at? is’  

**mı shủao**
> But… how?!  

**mı chảı**
> thow  
> indirect questions are a concept that can't be analysed into smaller parts, and it's so by definition  
> an indirect question is a subordinate clause that pertains to an unasked question  
> and it is different from a relative clause that points to the answer of such a question  
> the Biblish ‘he who…’ might be easier to understand, I guess  
> ’I don't know him who did that’ – I don't know the person  
> ’I don't know who did that’ – I don't know the answer to the question: ‘Who did that?’  
> <https://en.wikipedia.org/wiki/Content_clause#Interrogative_content_clauses>  
**mı shủao**
> Are there not less nonsensical methods with the same effect?  

**mı chảı**
> > [T]hey are often direct objects of verbs of cognition, reporting, and perception, but here they emphasize knowledge or lack of knowledge of one element of a fact[.]  
>
> no  
> if you have content clauses, you have to have indirect questions too  
> in case of Toaq, you have:  
> **bủ dủa jı́ tâo hı ráı máq da.** – I don't know who did that.  
> **bủ rảqdūa jı́ lú tảo hóa máq da.** – I don't know the one who did that.  
> **dua** can be applied to context clauses only; I used **raqdūa** here for the meaning: ‘I know of him.’  
> @**shủao** of course, you might try making a language where, instead of indirect questions, you have predicates like ‘X doesn't know what has property Y,’ but indirect questions are handier in that they don't require you to know that you're going to use one before the moment they're stated  
> in general, every sentence with an interrogative content clause can be transformed into one with declarative content clauses only:  
> **bủ dủa jı́ tâo hı ráı máq da.** (I don't know who did that.) → **sa dó tǔq lủ tảo hóa máq bı, bủ dủa jı́ tâo dó máq da.** (There's somebody who did that for which I don't know to have done that.)  
> but, as you can see, the above is messy  
> and, to nitpick even further, the above transformation relies on the assumption that there is somebody who did that  
> in the end, you'd need to construct a sentence like: ‘If there isn't anybody who *X*-es, then I don't know that there is nobody who *X*-es; and if there is somebody who *X*-es, then for all people *p* such that *p* *X*-es, I don't know that *p* *X*-es’  
> or, even better: ‘For all plural constants *pp*, I know that *pp* has p-ty *X* if *pp* has p-ty *X*, and I know that *pp* doesn't have p-ty *X* if *pp* doesn't have p-ty *X*.‘  

**mı chảı**
> the need for indirect questions could also be avoided with a predicate with a definition like: ‘*X* knows what *n*-tuple of arguments satisfies *n*-ary relation *Y*’ (for any *n*, including 0)

[…]

**mı hỏaqgı̄o**
> uakci, your expansion of the indirect question was wrong […]  

**mı chảı**
> @**hỏaqgı̄o** therefore, I am asking to nitpick and correct  
> I should emphasise that it’s my understanding of indirect questions that I was dwelling  
> it isn’t necessarily the most elegant definition  
> I, too, would like indirect questions gone  

**mı hỏaqgı̄o**
> First problem:  
> > **bủ dủa jı́ tâo hı ráı máq da.** – I don't know who did that.  
> > **bủ rảqdūa jı́ lú tảo hóa máq da.** – I don't know the one who did that.  
>
> These sentences aren't alike  

**mı chảı**
> I’m aware  
> what point are you trying to make here?  

**mı hỏaqgı̄o**
> I'm not really making a point, unless you consider "that's wrong" to be a point  
> (Which I do – retracting incorrect information is important even if you don't have correct information to replace it with)  
> But that there wasn't my main correction  

**mı chảı**
> I was showing an example of the almost same sentence and its not so same translation  
> they were somewhat supposed to turn out as different from each other  
> but, to the main tea, please  

**mı hỏaqgı̄o**
> Ah wait, I just found:  
> or, even better: ‘For all plural constants *pp*, I know that *pp* has p-ty *X* if *pp* has p-ty *X*, and I know that *pp* doesn't have p-ty *X* if *pp* doesn't have p-ty *X*.‘  
> I was going to correct you on:  
> in the end, you'd need to construct a sentence like: ‘If there isn't anybody who *X*-es, then I don't know that there is nobody who *X*-es; and if there is somebody who *X*-es, then for all people *p* such that *p* *X*-es, I don't know that *p* *X*-es’  
> But the "even better" one isn't wrong  

**mı chảı**
> are you saying that the one above is correct and the one below is wrong?  
> because if so, I agree  

**mı hỏaqgı̄o**
> Yes  
> (Or slightly more accurately: that the one above is a plausible rendition. We might not go with that)  

**mı chảı**
> I didn’t say we should go with any of that – again, it’s my interpretation specifically  
> although indeed it would be beneficial to keep this definition at the back of your head and see if it works in different, more convoluted sentences  
> note, however, how such an îndirect quẻstion is dependent in meaning on the containing predication  
> which means that ◌̂ + hi dó attains special semantic powers, just like ◌̀ in Toaq and macros in Scheme  
> (not Scheme macros, because they can only operate on their own arguments and not on their surroundings, and I’m trying to make the point that ◌̂ + hi dó does transform the outer clause)  

**mı hỏaqgı̄o**
> How do they transform the outer clause?  

**mı chảı**
> ‘I don’t know what caused this’ → ‘for all pp, I don’t know that pp caused this if pp caused this, and I don’t know that pp didn’t cause this if pp didn’t cause this.’  
> the italic parts are attachments onto the outer clause; moreover, this clause, with the modification (did → didn’t), is copied to make a second claim (underlined)  

**mı hỏaqgı̄o**
> Hmm, I think I understand  
> Are you saying that Bủ dủa jí câ hi ráı ní should be the same as Bủ dûa jí câ hi ráı ní, since there is no change in scope, but it requires special semantics to do so?  

**mı chảı**
> this is not what I’m scared about – serial predicates and scoping in sentences where they’re present don’t bother me because they’re lightweight and predictable  
> (lightweight = requiring little thinking power to crack, allowing one to gain an intuitive, no-brainer understanding over time)  
> what I’m scared about is this:  
> you can’t consider **râi hı rái** in isolation, but only **raı râi hı rái** – one level up from the clause  
> furthermore, if you answer a question with a fragment that is a case of ◌̂ + **hı dó**, you’re actively transforming the asker’s sentence  
> and the change is not lightweight  
> this means that the answer doesn’t really answer the original question, but a transformed version of it  
> this is different from, for example, ‘**ma shıe súq moq**’ — ‘**[jeo hóq] rào dı́o**’  
> because the answerer gives an explicit condition of the sentence being true, using an afterthought sentence transformer that ◌̀ is one of  
> with ◌̂ + **hı dó**, it’s nothing like that  

**mı hỏaqgı̄o**
> So would **dủa súq hı ráı** → **câ hı dó be** an example of this?  

**mı chảı**
> yes, I was going to type this exact example in right now  
> the question is transformed opaquely  
> and it’s done with what’s supposed to be the most transparent and well-behaved construct in the grammar, namely ◌̂  

**mı hỏaqgı̄o**
> But isn't your interpretation -- that an indirect Q is just a statment in disguise -- the antidote for this problem?  
> In that interpretation, the sentence isn't transformed  

**mı chảı**
> I’ve come to realise that indirect questions can’t be statements in disguise  
> they do complex stuff  
> all their heavy work is abstracted out into a mere collocation of a tone and a question word  
> so I can no longer accept an interpretation where the outer claim isn’t transformed  

**mı hỏaqgı̄o**
> I still don't understand what transformation is necessary  

**mı chảı**
> I, on the other hand, don’t understand how it can be not essential  
> of course, we can keep indirect q’s as an inanalysable construct that you’re just supposed to understand  
> if you find a satisfactory transformation that is bounded by the ◌̂, let me know  

**mı hỏaqgı̄o**
> What's wrong with "what caused this" → "that whatever caused this caused this and whatever didn't didn't"?  

**mı chảı**
> »[…] the philosophy that indirect questions are their own type of semantic object and cannot be reduced to statements to be fed into "**dua**".«  
> (this is what I’m trying to put into doubt and see if there are alternatives)  

**mı hỏaqgı̄o**
> What's wrong with "what caused this" → "that whatever caused this caused this and whatever didn't didn't"?

**mı chảı**
> there are two issues here

**mı hỏaqgı̄o**
> Oh wait a second wait a second  
> The quantification leaks out into the outer claim, right?  

**mı chảı**
> 1) **bu dua jı́ câ hı rái** → either **bu dua jı́ câ cá**, which is a tautology, or **sa dó ca3 bı bu dua jı́ câ dó** (same problem)  
> yes ^^  
> smart one  

**mı hỏaqgı̄o**
> Now I see  
> Okay, that sucks  

**mı chảı**
> 2) even if there’s a way to keep the quantification inside, there’s still relativism that ought to be remembered. I might know what caused this, but it might not be the actual things that caused this  
> …and implementing this behaviour would require to… know the outer predication  

**mı hỏaqgı̄o**
> Hmm, what now?  
> I don't know what you mean by that  
> I might know what caused this, but it might not be the actual things that caused this
> this  

**mı chảı**
> okay, let’s switch around the outer predicate:  
> **dua jı́ chı̂aidua jı́ câ hı rái**  
> we would somehow need to transform this into dua jí chîaidua jí câ + an argument phrase that would signify some referent for which the chîaidua clause holds  
> because we can’t substitute it with the real cá, because we know we’re supposed to be wrong about what we know  

**mı hỏaqgı̄o**
> Aha  
> So even if "I know [what caused this]" goes magically to "I know [that the candle caused this]", that breaks on "I am wrong about [what cause this]" because that will go to "I am wrong about [that the candle caused this]"  

**mı chảı**
> yes  

**mı hỏaqgı̄o**
> Looks like a big oof for "questions are statements in disguise" theory  

**mı chảı**
> and the ‘questions are black boxes’ theory too, unless we allow ◌̂ to transform their containing clauses  

**mı hỏaqgı̄o**
> Is that so?  
> "I am wrong about [what caused this]" seems fine as a black box  

**mı chảı**
> the indirect questions are black boxes theory would stand solid if either ◌̂ could transform the outer clauses or predicates that expect indirect q’s had rules on handling them  
> the latter is easier to prove the existence of a feasible implementation of, of course  

**mı hỏaqgı̄o**
> Oh, well yes  

**mı chảı**
> let’s call it a small oof  

**mı hỏaqgı̄o**
> I was counting "rules for indirect q's built into the predicate" as part of black box thoery  

**mı chảı**
> okay  
> then give it a better name, if you may  
> »indirect questions are black boxes with special handling from their receiving predicates«  

**mı hỏaqgı̄o**
> black box theory is the perfect name already  

**mı chảı**
> alright  

**mı hỏaqgı̄o**
> Just remember that "black box" is stronger than "opaque in-place transformation"  

**mı chảı**
> or maybe ‘primitive indirect question(s) theory’  
> which makes a looser claim  

**mı hỏaqgı̄o**
> Or "the amiguity approach" (predicates which can take IQs are ambiguos)  
> This one is stolen from a paper than was linked here  

**mı chảı**
> kay  
> the amiguilty approach  
> and its friend, the yesyouare implementation  

**mı hỏaqgı̄o**
> I'm wooshing  
> Anyhow **dủa súq hı ráı** → **bỏao jı́ câ hı ráı** becomes sensible because now the latter is an explicit transformation of the former  

**mı chảı**
> just playing around with words  
> wait  
> how is that a transformation?

**mı hỏaqgı̄o**
> Well  
> The latter stands in for a transformation of the former  
> "**bỏao jı́…**" expands to "**tu … bı dủa jı́ …**]"  
> Thus you get the satisfying "What do you know?" → "I know …" without forcing quantifiers into somebody else's sentence  

**mı hỏaqgı̄o**
> I mean, I propose a texture pack where dua splits into dua and boao but yes  

**mı chảı**
> make an edit for the future generations  
> and smile!  
> 📸

**mı hỏaqgı̄o**
> 😬  

**mı chảı**
> I’m okay with **dua** being polymorphic like it seems to be now  

**mı hỏaqgı̄o**
> Oops, I was making a face  

**mı chảı**
> too late  

**mı hỏaqgı̄o**
> But the polymorphis lets you be lazy and say **câ hı ráı** alone as a response  
> Hoemai, thoughts on this conversation?  

**mı shủao**
> 😬  

**mı chảı**
> @Hỏaqgīo
> > I’m okay with **dua** being polymorphic like it seems to be now  
>
> exactly what I was saying.  

### 2018-11-02, #general

**mı lỏq**
> can someone explain to me **hı** and **ku**? I understand **hı** when the illocution is **moq**. but what is **hı** with **da**? is this an indirect question, similar to how **ma** becomes an indirect question with **da**? I assume so. But then what is **ku**? in **báorēo nủq ku** seems to be used for an indirect question instead of **hı** for the sentence "He went and listened, and then noticed that it was the birds who were chattering together"  
> is this just another instance of my inability to understand {**mı kau**}?  
**mı hỏemāı**
> I think so 😃
> **ku** marks focus.  
> **hı** without **moq** (or **hı** in subordinate statements) is used for indirect questions  
> There are a few examples of that on the website  

**mı lỏq**
> ok. I'll hunt them down and see if i can't finally figure it out
> **kủaq kı̉e ka**  

**mı hỏemāı**
> As for **ku**, compare **mủaqtūa jı́ rúaı** "I killed the royal". to **mủaqtūa ku jı́ rúaı** "It was me who killed the royal". In the latter, it is already known that somebody killed the royal, but it is new information that it was me.  

**mı lỏq**
> What would **mủaqtūa hı jı́ rúai** translate to?
**mı hỏemāı**
> "Which me killed the royal?" ("which thing that is me")  
> (with **moq**, to make the question)  
> **hı** without **moq** is usually not used at top level  
> The **moq** can be implicit (dropped) in casual speech  
> Or when you're just saying a fragment  
> For example, **tı̂o dẻ fō** "How beautiful"  
> Anyway, **hı** is for asking "which/what" things fill a place.  
> (Like {mo'oi} in Lojban)  
> (Except in Lojban, {mo'oi} and all the other question words automatically add an interrogative illocution to the sentence, which is why when you don't want that, you have to undo it with {kau} after the question word.  

**mı lỏq**
> **kủaq kı̉e ka**

## the N-Word Stone

### 2019-03-17, #off-topic

**mı sẻaqtāq**
> **tảoshāo nảıjı̄a kủq jı́ tóa pỏ nı́lāı da…nủtı̄rı̄shōqhēqcāi gủibēaqhāq mủoq go kủorı̄bā (kıo hỏkēı la tủa fỏaq so dảıchı̄ na, kùı lû nảqpı̄a go pó gójı̄ rỏaqpı̄afū ga pảı sa ráı rǒaqpı̄afū sa méahēo mu pǎı sa lú gảq hóa hóı nı̉q rỏaqpı̄afū bòı dêo na ceı jǔlū gủaıgāq hóa sa póq bǒ hóa sa kúnē pảını̄aı, ju cěorı̄aq pỏ máq pó sa méahēo củe nǎqpāo go hóa sa lú pủ lủeq go sỏıfūaı hóa ju pủ bủagāq hó sa chı́egāq rào chı̂etāo na ju jẽo bı chủrı̄e pı̉afū go hó sa lú tủaobū mu pı̉a hóa sa ráı mǎıpāı go hóa sa lú rào kôaqshō tı̀ sa núı bı rảqdūa hó sa jáq pảırūo lẻaqbūe, ju lı̉qfū go hó sa lú geonē sa nı́aqnē rỏaı hó ju chı̉etūa go hó sa ráı hǎo hóı chẻ hóa mu lı̌qpı̄a sa géonēhūaq ju pảı go hó sa lú gảq hóa bòı pó céochı̄ejı̄o ga hóı lı̉qpı̄a  lı̌qpāo sa lú mu rỏaqpı̄afū hóa sa lú kı̉qrūotāo hóa sa núı kı̉q pỏ sa púı gủa ga ju fảq lû mu lı̉qpı̄a sa náq sa lú mu lı̉qpı̄afū hóa sa ráı mǎıpāı sa póq pǎosū sa lú pủ sẻoshō hóa sa náq gǔaı go pó sa dúaogūıjēarı̄aq ru těqdōa hóa sa rótı̄ sa lú dủq tẻq hóa sa kı́aqchē chı̌e chẻ tẻ go bảq kı̉aq hóa mu sòa sa póq mu lı̌qpı̄a hóa sa lú to ru lủı bủadūo pèa sa dáqjāq to jãq jẻo bı rảqdūa hóa sa téqjūqchē mu pǎı hóa sa ráı mu nǎqfū hóa hóa sa lú mu lủeq hóa sa róalūeqdōa kỏqpānı̄ cǔe go hóa sa ráı rǒaqpı̄afū hóa sa nı́q lı̌e jảq bỏmı̄a hóa bòı jı̂u na kùı pó lúo ju bỏ  pó hóa sa lúeqchē mu nǎqpı̄a hóa sa ráı gěonē go hóa sa nı́aqnē shı̉cēı ru chı̌e hóa pó téıdı̄u mu gàq sa lı́q chǒ jãq hó hóa ju mu pảosū hó sa lú pủ chẻ gỏlūfū ju rảo kỏ gủ sa ráı hó sa súaıkōı měa go hóa sa lú mảıgēq hóa sa lı́q lǔı jẻa bỏ hóa sa cháo hảı mu chỏq sa póq lủ mu pı̉a hóa sa lú rı̉ochē hóa  ju rı̉oqhēaqfā pòı lủeq sa rı́okōqpānı̄ lủ põı dảı tủa pı̉aq bı sẻcāq hóa gûaqtı̄shō**

### 2019-03-17, #general

**mı sẻaqtāq**
> It is a copypasta  
> namely this:  
> I’m gonna say the n word… NUTRI-GRAIN BLUEBERRY BREAKFAST GRANOLA BARS (it’s okay, my cousin’s friend has a brother who’s girlfriend has another cousin that has a childhood friend who grew up to work with a guy that has a dog who was originally from an owner that has a husband who’s father met a guy in the military that had a college roommate who actually has a half nephew who has a step brother who has a girlfriend that growing up in a small town had a friendly neighbor who had a 8 year old daughter who had a 4th grade teacher that had a student that actually had an older sister that had an old friend from preschool who’s mom had a 2nd cousin who was in a short international film that starred a guy who’s sister has a niece that has a boyfriend who had a grandmother who has an ex husband that worked in a bakery and sold bread to this guy that had a barber who learned to cut hair from this guy who has a sister that moved to Madagascar and actually knows a local cashier that had a best friend who has a son that has a health insurance provider who’s ran by a guy that’s cousins with a girl that was born into a rich family with a butler who has a 16 year old son that has a trigonometry class with this girl he likes that has a grandfather who was a professional golfer that once got second place behind a guy that was dating this girl that bought a used car from a guy that has a brother who is a pilot and flys for an airline which is surprisingly responsible for the death of some guy who got in a plane crash that before he died had a girlfriend who was an aspiring musician that made a song that this one guy tweeted about that also has a cousin who has a best friend who’s very religious and has a pastor that actually eats nutri-grain breakfast bars. Oh and who’s black)  
> Now yall other humans can practice your vietoaq more [note: the original was in Vietoaq]  
> There are a few errors in my translation I have noticed, but i sped through this one (≈45mins) so i am not too worried  
> I also had to coin some stuff on the fly and quite hastily, like **tẻqjūqchē** for cashier  

## On water, waters, and the idea of water

### 2019-03-18, #general

**mı hẻukūeqchē**
> in the meantime, I have another question about this sentence **chỏ jı́ báq nảo da.**  
> I don't understand why the bab is necesary to say "I like water"  
> wouldn't **chỏ jí náo da** be enough?  

**mı hỏaqgı̄o**
> No  
> The reason is that **náo** means "the water"  
> So if you live by a lake, that would be appropriate to say you like the water in the lake  
> Or if somebody serves you water and asks how it is  

**mı hẻukūeqchē**
> ah, its THE water (only the one referred to at the moment. This water), not water in general  

**mı hỏaqgı̄o**
> Yes  
> (Though not necessarily "this" water. It could be in a cup on the table or it could be on Mars; **náo** just means "the water (the water we're currently talking about, not some random water)")  

**mı hẻukūeqchē**
> like, the UofD?  
> well, A specific water  
> and is that different from the waters?  

**mı hỏaqgı̄o**
> No  
> In fact you've hit on an important point  
> If there are multiple waters in the UoD, then náo is all of them  
> If we are talking about three lakes then **chỏ jı́ náo da** means I like the three lakes  

**mı hẻukūeqchē**
> so the distinction is between the abstract idea of water, and any concrete instance of water  

**mı hỏaqgı̄o**
> Yes, that's between **báq nảo** and **náo**  

**mı hẻukūeqchē**
> is this like Plato's Forms?  

**mı hỏaqgı̄o**
> I am not familiar with those 😛
> Oh wait! Yes I am  
> Yes, I think that's a good way to think about it  

[…]


**mı hẻukūeqchē**
> but one last thing, with the water question. If I wanted to talk about some concrete waterS (plural), would it be like this?  
> **chỏq jí náo sa da**  

**mı hỏaqgı̄o**
> In any case, the answer is no 😛
> sa may be glossed as "some", but it's not a willy-nilly word like English has, it's the E quantifier  
> It's used like this:  
> **chỏ jı́ sa náo da**  

**mı hẻukūeqchē**
> ah, right associating?  

**mı hỏaqgı̄o**
> No associating  
> This is equivalent to the logical proposition:  
> ∃*x*. *x* is-water: I like *x*  
> "There exists some *X* which is water such that: I like *X*"  
> (This *X* still could be singular or plural, it isn't specified)  

**mı hẻukūeqchē**
> hm, I kinda see. So I'm just saying that there is some thing, which is water, and that I like?  
> not how many of that thing there is  

**mı hỏaqgı̄o**
> Yes  
> To specify that there are multiple things, you can use the predicate puq  
> **chỏ jı́ sa púq nảo da** = "I like some multiple waters"  
> Or: **chỏq jı́ púq nảo da** = "I like the multiple waters"  


## On having sex with bees

### 2019-18-03, #totd

**mı shủao**
> TotD 15: **sẻaq sa hápı̄ ba**.

**mı hẻukūeqchē**
> XDDD well done! I'm proud of you (and so is that sexy, sexy bee)

**mı chảı**
> @Heukueqche @Shủao  
> it’s not ‘sexy bee,’ but ‘The bee has (is having) sex.’  
> those are two fundamentally different concepts; you can have sex despite not being sexy and you can have no sex despite being sexy  
> for ‘sexy,’ consider something like **seaqdē** (‘sexually beautiful’)  

**mı shủao**
> @🍵 Fuck bees.

[…]

**mı shủao**
> "Fuck bees."  
> The (meme) phrase I tried to translate; directed at no specific person, yet imperative.  
> … perhaps there should be a specific quantifier on **hápı̄**, and I'm not sure about nothing filling the second spot, but it's nice to have it concise too.  

**mı chảı**
> @Shủao and you’re right. the correct v. would be **sẻaq súq sa hápı̄ ba**.

**mı shủao**
> Why **súq**?

**mı chảı**
> without **súq**, it could be **go**.  
> ‘May (indetermined) have sex with one or more bees.’

**mı shủao**
> The places of **seaq** don't seem that specific.

**mı chảı**
> wdym

**mı shủao**
> In the definition I saw, they seemed interchangable.

**mı chảı**
> **seaq**, I believe, is symmetric.

**mı shủao**
> Then the **go** would be redundant, would it not?

**mı chảı**
> well then, **seaq go hápı** would suffer from the same issue as **seaq hápı**  
> I guess it’s only fair to assume that the **go** omits an implied **suq**, or whoever the command is actually directed towards.

**mı shủao**
> It's not directed towards anyone, as I said.

**mı chảı**
> **seaq sa póq sa hápı ba** = may somebody fuck a bee  

**mı shủao**
> I'm not telling people to go out and fuck bees, I'm just telling bees to get fucked.

**mı chảı**
> okay then, **seaq hápı ba**, then
>

**mı shủao**
> No more **sa**?  

**mı chảı**
> oh yes, **sa**

**mı shủao**
> Would **tu** be bad in place of **sa**?

**mı chảı**
> **tu** would be bad
> as it would imply all sets of bees

**mı shủao**
> Fuck 'em all.  
> Pokémon style.

**mı chảı**
> catch ‘em all first.

## On beer and expanding serial predicates

### 2019-03-18, #general

**mı hẻukūeqchē**
> On the serial expansion of **bủ chỏ jı́ báq bı̉rā da.**
> would it be:  
> **bủ chô jí bâq ja dó bírā da** 

**mı hỏemāı**
> **bâq** is not correct  
> If you want to expand the argument phrase (**báq bı̉rā**) as well, then:  
> **bủ chô jı́ lú bảq bı̉rā hóa da**

**mı chảı**
> you didn’t expand it  

**mı hỏemāı**
> There is also another solution using binary **bủ**, but I see no point  
> Yes true  

**mı chảı**
> **lú baq hóa lı̂ bıra ja dó**

**mı hỏemāı**
> Yes, that.  
> **bủ chô jı́ lú bảq hóa bı̂rā ja dó**
> or **bủ chô jı́ lú bảq hóa lı̂ bı̉rā ja dó**

**mı chảı**
> `%nui` **bu paı go baq raı**

**mı nủogāı**
> (`(#f)` . **lı̂ ja dóshı̄ bı bủ dóshı̄ lı̂ ja dógū bı pảı dógū sa lı́ ja dósāq bı bảq dósāq lı̂ ja dójō bı rảı dójō**)  

[…]

**mı chảı**
> (by the way, they are the same)  

**mı hẻukūeqchē**
> might you tell us the binary solution, @**hỏemāı** ? different versions of the same thing help a lot to learn  

**mı hỏemāı**
> It's what **mıu** would give if it knew **cho**

**mı chảı**
> see what it does with **bu paı**
> `%nui` **bu paı**

**mı nủogāı**
> (`(#f #f)` . **lı̂ ja dóshı̄ ja dógū bı bủ dóshı̄ lı̂ ja dósāq bı pảı dósāq dógū)**

**mı chảı**
> **bu *x₁* lı̂ paı ja dó *x₂***, essentially  

**mı hỏaqgı̄o**
> `%serial` **bu paı**

**mı nủogāı**
> <`[c c]` (**bủ a pâi ja dó b**)>  

**mı chảı**
> @**heukueqche**
> in general, **bu** is binary in serial predicates, so it would work as ‘x₁ doesn’t satisfy property of being a friend to x₂,’ instead of ‘it isn’t the case that x₁ is a friend of x₂’  
> however these are equal by virtue of the ‘JEO-frame equivalence’ we all know and love  
> `%serial` **bu maı**

**mı nủogāı**
> <`[c c]` (**bủ a mâi ja dó b**)>  

**mı chảı**
> `%nui` **bu maı**

**mı nủogāı**
> (`(#f #f)` . **lı̂ ja dóshı̄ ja dógū bı bủ dóshı̄ lı̂ ja dósāq bı mảı dósāq dógū**)

**mı chảı**
> @**heukueqche** if you examine this definition closely, you should get this:  
> λ*a b*. **bu**(*a*, λ*x*. **paı**(*x*, *b*))  

## On a Complete Grammar

### 2019-03-19, #general


**mı jỉmō**
> Hey, I was wondering, how do you ensure that the grammar is actually flexible enough / covers all possibilities etc  

**mı chảı**
> what do you mean?  

**mı jỉmō**
> How do you know you've finished the grammar?  

**mı sẻaqtāq**
> We don't, I mean can you ever know? We don't even think that is the case as we have lists of things we cannot do  
> like measuring and telling time, the big ones  
> Normally and seemingly someone has been doing irl things until their brain is like "Hey, somethings wrong with toaq, alert the others ASAP," or something similar. Another way of finding out that we just can't say something (the way we would like) is by doing translations  
> But that includes grammar and vocab ofc  

**mı hỏemāı**
> The grammar is complete in that you can already say everything using the current available syntax.  
> Making words for measurements is not a matter of grammar.  
 
 **mı sẻaqtāq**
> > But that includes grammar and vocab ofc  
> Ah nope, that doesnt work  

**mı hỏemāı**
> Serial predicates alone have unlimited expressive power.  
> The only way in which the grammar could be incomplete at this point would be a missing terminator (if we find an ambiguity in the syntax).  
> So, how do I know the grammar is finished? I know, because I know what my vision for the grammar was and I made the grammar exactly as I wanted.  
> Writing the PEG grammar was one of the necessary steps from vision to reality.  
> Since we have a working parser which can parse any sentence I would deem correct and rejects ones I would reject (with only very minor exceptions which are due to oversights or due to minor syntax/morphology changes between beta and now), we can use that as another measurement for completeness.  

**mı jỉmō**
Thanks, that's actually pretty insightful


## On Corrections and Connections (huq)

### 2019-03-20, #chiejio

**mı sảılōhōrāq**
> Is there a word for making corrections  
> Like “si” in Lojban,  

**mı shủao**
> **huq**?  

**mı sảılōhōrāq**
> Oh ok! Cool  
> So that’s where you replace one word with another  
> That seems very useful and works for what I’m trying to do, but  
> Now I’m wonder if you really wanted to erase something but not replace it with a new thing how that would work shrugs  
> Also I’m imagining some confusion in the details of how it works  
> If you want to replace one whole phrase with another whole phrase,  
> Like I mean what if you said an argument word but you meant to say a predicate word, could you do a replacement? How in the structure of **huq** would you say you want to replace an argument with a predicate, it seems the grammar might get tricky, I dunno  
> Maybe anything in **huq** has to go in quotes? And the quotes are removed before replacement?  

**mı hỏaqgı̄o**
> I've just coined **è**, an interjection whose purpose is to erase "some" words  
> It doesn't always erase the same number of words or even the same kind of phrase; it cues the listener to figure it out based on context  
> Thus **hảı dủa jı́, è súq** would likely replace **jı́** with **súq**, whereas **mı̉u súq jâq dẻ, è, hı ráı pa mı̉u súq jâq dẻ ráı moq?** starts the sentence over.  

[…]

### Summary

**mı hẻukūeqchē**
> ok, I'm feeling like summarizing. On Xylochoron's idea, of correcting mistakes in speech. They wanted to correct arbitrary arguments and phrases, and **huq** does that job (by replacing the left hand argument with the right hand argument). But it is ambiguous with phrases and single arguments. So Hoamgior coined **ek** to erase words. **ek** is not precise, it just cues the listener to replace based on context.  


## On Single Words and Interjections

### 2019-03-20, #chiejio

**mı hỏaqgı̄o**
> I've just coined **è**, an interjection whose purpose is to erase "some" words  
> It doesn't always erase the same number of words or even the same kind of phrase; it cues the listener to figure it out based on context  
> Thus **hảı dủa jı́, è súq** would likely replace **jı́** with **súq**, whereas **mı̉u súq jâq dẻ, è, hı ráı pa mı̉u súq jâq dẻ ráı moq?** starts the sentence over.  

**mı sảılōhōrāq**
> But every word in Toaq starts with a non-“q” consonant so that one can tell where a root starts and ends without listening for pauses, or…?  

**mı hỏaqgı̄o**
> Yes, there is that  
> E.g. **dẽ** sounds exactly like **dè   é** if you don't pause  
> But Hoemai has declared that the lone vowels, paired with tones, will be interjections, so I think they want us to just pause before them  
> To make it unambiguous  

**mı sảılōhōrāq**
> Oh, ok!  
> Gotta be careful picking them I guess, since there’s only 5 total 😛

**mı shủao**
> I think that does work, given the tones, unambiguously.  

[…]


**mı sảılōhōrāq**
> Can you have dipthong words, like “iao” by itself  
> Or “iaq”  

[…]


**mı hẻukūeqchē**
> from what I remember, Hoemai doesn't want tones to carry semantic meaning, only grammatical meaning.  
> So, no matter what tone you use, **hapı** always means bee. But it can be a verb, a noun, a dependent clause, and any other kind of grammatical role  

**mı sẻaqtāq**
> He does seem to want this with interjections  
> Just look at the m-interjections  

[…]

**mı hẻukūeqchē**
> \[so, for (a u i o e, m l r) there are\]  
> (5+3)\*7=56 interjections  

## On Pain

### 2019-03-20, #general

**mı sẻaqtāq**
> **mm**
> Well on to the next thing while I have your heliosic attention, the **kıeq** vs **kıeqge** and **noı** vs **noılıe** thing brings me terrible memories of esperanto  
> Ah yes, reversability!  
> That thing where you had to remember the inherent part of speech of every root in order to properly apply derivational affixes  
> That sucked  

**mı hỏemāı**
> I see  
> I *t h i n k* the reason for **noı** being defined as it is had to do with pain being in a specific place (?)  
> like, **noı** is not just **lû nỏılīe**  
> or **nỏılīetūe**  
> but the locus etc  

**mı sẻaqtāq**
> Like the lojban word…  

**mı hỏemāı**
> The Lojban word has the experiencer in x₁, which is what you want  
> **noı**1 is the pain  
> (as defined)  
> With **noı** you can say "a pain"  

**mı sẻaqtāq**
> But if **noı** were **noılıe**, could you not just say **noıge**?  
> Or if you find **ge** you be ugly, the "base" of this and related words would be **ge** and we would from there apply **lıe**  

**mı hỏemāı**
> I think **noıgē** would be like the impact of a hammer hitting your thumb  

**mı sẻaqtāq**
> **m̄**  
> m̌akes sense  
> Well, I do not rest my case as a solution hasn't been found if it is even possible, but I rest my case.  
> for now ofc  

**mı hỏemāı**
> The case of "my leg hurts" remains problematic.  

**mı sẻaqtāq**
> Oh you are still here, and I agree. Maybe something like **huatı̄**?  
> Just made that up on the spot so it may not exactly be the best, but I am now trying to think of a definition for that.  
> My leg is the source of my pain? Using **ceorıaq** or something less physical?  
> **nỏı tı̀ gójı̄ shı̉aq**  

**mı hỏemāı**
> Indeed, **tı̀** alone doesn't work.  

## On Starting words with Vowels or glottal stops

### 2019-03-21, #chiejio

**mı sảılōhōrāq**
> I’m still curious if words like “iaq” will be an option at some point……  

**mı hỏemāı**
> Words cannot begin with a vowel or glottal stop, because it would be ambiguous with the ◌̃ tone in environments such as **dẽ** vs **dè é**  
> That's why the currently-proposed interjections have to be considered extra-linguistic or at least grammar-adjacent, the way that laughter or inflating your cheeks with air and the expelling it (to show relief) are meaningful signals, but not grammatical signals, but rather socio-cultural signals.  


## On Voldemort, Zombies, and Cereal Killers. Or, Running from the dead, and inflecting serial predicates.

### 2019-03-21, #general



**mı hẻukūeqchē**
> flee from death: **bủıfā go cúaq mủaq**  

**mı shẻırēq**
> I would go with just **"rı̉eq mủaq"**  
> possibly prefixed with **"dảqmı̄q"**  

**mı hẻukūeqchē**
> **dảqmı́q rı̉eq mủaq**  

**mı shẻırēq**
> Yeah; **lẻo rı̉eq mủaq báq pỏq**  
> **keo bủ lẻo dảqmı̄q rı̉eq mủaq báq pỏq**  

**mı hẻukūeqchē**
> **lẻo rı̉eq mủaq báq pỏq**  
> woud that mean "tries to avoid the many dead"  
> or: avoids zombies?  
> and how does the keo bun changes the phrase? "but doesnt' try to avoid the many dead"?  

**mı shẻırēq**
> **"keo bủ lẻo dảqmı̄q rı̉eq mủaq"** = "But does-not try-to eternally avoid-satisfying-the-property-of being-dead"  

**mı shẻırēq**
> For "avoid" in the sense of "avoid the zombies" you'd want **"rı̉eq tı̉jūi"** = "☆ avoids being near / in the vicinity of ☆"  

**mı hẻukūeqchē**
> ah, I see. You extend the meaning with a serial predicate  
> **rı̉eq tı̉jūı mủaq pỏq nı**  

**mı hẻukūeqchē**
> would that mean "avoids being near to the dead person over there"?  

**mı shẻırēq**
> I think it means "☆ avoids being near ☆ and being a dead person"  
> **rı̉eq tı̉jūi ☆ nı́ mủaq pỏq** = ☆ avoids being near that dead person  

**mı hẻukūeqchē**
> **rı̉eq tı̉jūı jı́ nı́ mủaq pỏq**  

**mı hẻukūeqchē**
> "I avoid being near that dead person"?  

**mı shẻırēq**
> Jẻo da!  

**mı hẻukūeqchē**
> : D thanks!  
> oh, yeah, **nı́** is a predıcate, and its argument is the serial predıcate **mủaq pỏq**  

**mı hỏemāı**
> More like, **nı́ mủaq pỏq** is what you get when you apply the ◌́ tone to the serial predicate **nı̉ mủaq pỏq**  

**mı hẻukūeqchē**
> oh! I see!!! thanks. You first make the serial predicate, and then you transform it into a noun XD thanks!!!!  


## On the Branching of compounds and serials

### 2019-02-07, #general

**mı mỏılūq**
> As for why Toaq compound words are left-branching (i.e. suffixal) whereas serials are right-branching, I don't know; it is the same order as in Lojban compound words and it's also probably for naturalistichood, as most languages with a single affixation direction are suffixal, such as Mandarin or Japanese.  
> There are many natlangs that use both recursive suffixation and recursive prefixation at the same time  
> However exclusive recursive prefixation seems to be uncommon or rare  
> There has been a survey of 55 languages belonging to 28 language families, for which «Recursive derivational prefixation appears to occur in languages in which there is recursive derivational suffixation, with three exceptions in the study sample: Lakhota, Māori and Yoruba (the last of which does not use suffixation for word-formation processes) show recursive prefixation but not recursive suffixation.»  
> "Word-Formation in the World's Languages: A Typological Survey"  


## On the -Ables and Utterance



**mı hẻukūeqchē**
> how are "**choakıu**" and "**choadeq**" different?  

[…]

**mı hỏemāı**
> Anyway, the difference between "**choakı̄u**" and "**choadēq**":  
> deq means "to have an ability" -- the first place is an actor, the second place the ability.  
> "-**kı̄u**" means "-able" -- there is no actor place. It is more of a passivizer.   

> "**choakı̄u**" means "to be utterable", while "**choadēq**" means "to be able to utter".  
> A sound is utterable ("**choakı̄u**"). I am able to utter (it) ("**choadēq**")  
> "-**kı̄u**" is a common suffix. "-**dēq**" is not.  
> If you just want to get "to be able to do X", you can get that with a serial predicate, so there is no need to make a new compound  
> E.g., "**dẻq chỏa**"  

**mı hẻukūeqchē**
> then "**choadeq**" would be the correct one, because @Níucūq wanted to ask if they were able to utter "**shıfuedıaıheı**"  
> how would you say: can I say X?  

**mı hỏemāı**
> **mả dẻq chỏa jı́ x moq**  
> (if say == utter, otherwise use **kuq**)  

**mı sẻaqtāq**
> Other alternatives would be **mả dỉ chỏa (kủq) jí x moq** and **mả tỉao kûq jí x moq**, depending on what you want, which is most likely not **deq**  
> **dı̉** is yet another type of can/able  

**mı hẻukūeqchē**
> so there are three ables: "**kıu**", "**deq**", and "**dı**"  

**mı hỏemāı**
> You can add **daı** to the list  

**mı sẻaqtāq**
> Thinking just about how you can translate to  
> **sủaı súq**!  

**mı hẻukūeqchē**
> The Ables: "**kıu**", "**daı**", "**deq**", "**dı**"  

**mı hỏemāı**
> Another "able" would be "**juaodūe**"  
> "You can't do that" → "Doing this would be illegal"  

**mı hẻukūeqchē**
> so, -unable  
> law-correct  

**mı hỏemāı**
> Well, you could also phrase it positively: "Can I take this?" → "Is it legal to take this?"  

**mı hỏemāı**
> So what seaqtaq said was correct, and important. You wouldn't want to use "**deq**" for most of those situations  
> since it is not about ability, but about other things  

**mı hẻukūeqchē**
> about what is good or bad, about correctness?  

**mı sẻaqtāq**
> And don't forget about "**tıao**" e.g. "Would it be appropriate if I said this"  

**mı hỏemāı**
> possibility, legalilty, appropriateness  

**mı hẻukūeqchē**
> I see, thanks!  

**mı mỏılūq**
> Another meaning of -able is closer to "**tıao**"  
> as in "edible" (eat-able)  
> and "acceptable" maybe  

**mı hẻukūeqchē**
> The Ables: "**daı**", "**deq**", "**dı**",  "**juaodue**", "**kıu**", "**tıao**"  

**mı mỏılūq**
> in a serial, "**tıao**" wouldn't be exactly the appropriate word tho  

## On making names

### 2019-03-28, #chiejio

**mı dảqpēokōıchē**
> So I'm trying to make my username in Toaq, and I've narrowed the meaning down to (essentially) "one who ambulates through time".  
> Would **chẻkōıpēodāq** work, or am I understanding compound predicates wrong?  
**mı hỏaqgı̄o**
> I would reverse the order of the syllables  
> Compound predicates can be defined however you like, but generally if you want to make one that has a meaning related to its parts, you do (descriptor + base)  
> So I'd have:  
> **dảqpēokōıchē**  

## On compound predicates

### 2019-03-30, #chiejio

**mı hẻukūeqchē**
> how do you interpret compound predicates? I've heard there are some association rules?  
> like, is there a grammar for decomposing "**hoaqpı̄otūı**"

**mı hỏaqgı̄o**
> Actual rule: Compound predicates are not related to their parts; they are defined as separate words in the dictionary and their definition could be anything  
> Rule of thumb: For the sake of making it easy to remember them, we usually break concepts down into parts to design the compound word  

**mı hỏaqgı̄o**
> If a concept could be written as a serial with A B̉ C̉ D̉ or something similar, we compoundize it as DC̄B̄Ā  

**mı shủao**
> lujvo  

**mı hẻukūeqchē**
> oh, so as an informal rule, you can make a compound as the reverse of its 'equivalent' serial?  

**mı hỏaqgı̄o**
> Yes  
> E.g. **demīu** = **mıu dẻ**, and **duatūa** = **tua dủa**  
> But some compound words are just made up  
> **cukī** = _ nods is not related to **cu** or **kı** and in fact neither of those words are predicates  

**mı hẻukūeqchē**
> hm, so really a compound is more like a combination of sounds than a composition of words, and the sound unit is a syllable?  
> ah, is that why there is the high tone to denote compound words? so that each of its component syllables is not confused with a word?  
> like **cukī** does not sound like **cu kı**  

**mı hỏaqgı̄o**
> Yes, exactly  

## On the problem of indifference, nesting, and subordination

### 2019-03-31, #chiejio

**mı hẻukūeqchē**
> so, the phrase **súao nỏacā rǎq hóa chémē lỏjı̄bāq**  
> which, if I understood correctly, means "The important problem in the lojban community"  
> I have three questions:  
> 1) I'm surprised that the sentence starts with a noun (from the ◌́) instead of a verb ( ◌̉ ).  Why is that?  
> I thought every sentence had to start with a verb which would take as arguments the rest of the words  

**mı hỏemāı**
> 1) It's not a sentence, just like "The important problem in the lojban community" is not a sentence, but a noun phrase.  
> It's like a single **jí**, except way more complicated. But it's just a single noun  

**mı hẻukūeqchē**
> oh! its a fragment!  
> if we wanted to make it into a whole sentence, like "indifference is a big problem in the lojban community"…  

**mı hỏemāı**
> But now it looks like you turned "the problem" (noun) into a verb ("to be a problem")  

**mı sẻaqtāq**
> so you cannot use "**räq**"  
> but you can say "**lủ**…"  
> and go from there  

**mı hỏemāı**
> You could do "I am aware of the important problem (…)"  
> (for the sake of the exercise)  

**mı hẻukūeqchē**
> **chı̉aq jı́ súao nỏacā rǎq hóa chémē lỏjı̄bāq**  

**mı hẻukūeqchē**
> I am aware of the big problem in the lojban community  

**mı hỏemāı**
> Very good  

**mı hẻukūeqchē**
> thanks! though I still want to say that that problem is indifference  
> let me try it out, so you can see the mistakes in my reasoning  
> **sủao nỏacā bú sủaojı̄e nı̀e lójı̄bāq chẻmē**  

**mı hẻukūeqchē**
> problem important not caring inside lojban community  

**mı hỏemāı**
> Not bad, but there's a slight mistake. "**bú sủaojı̄e**" refers to a person who doesn't find something important, but you want to refer to the situation of not finding something important.  
> And because you used ◌́, the "**nı̀e**" phrase falls out  

**mı hỏemāı**
> The goal is that it groups like this: **sủao nỏacā (bú sủaojı̄e [nı̀e lójı̄bāq chẻmē])**  
> () = the argument phrase, [] the prepositional phrase  
> [] must be inside ()  
> but for it to be inside of it, you can't use ◌́ like that. Instead, you need a tone that "opens" a new statement  
> "(that there is indifference) is a problem"  

[…]

**mı hỏemāı**
> You need something that takes a statement (subordinate sentence) and wraps it into a nice package so you can use it as an argument  

[…]

**mı hẻukūeqchē**
> oh! I need to subordinate it!  

**mı hỏemāı**
> Well yes!  

**mı hẻukūeqchē**
> haha, so it would be…  
> **nı̂e**  

**mı hỏemāı**
> ◌̂ is correct, but put it on the right word  
> ◌̂ is always placed on the verb that starts the subordinate clause  
> (or on lu, which marks the beginning of the subordinate clause without needing to mark it on a verb)  
> How do you say "I know that you are asleep" ?  

**mı hẻukūeqchē**
> hm, let me think  
> **dủa jı́ nûo súq da**  

**mı hỏemāı**
> Perfect. Didn't even need my help.  
> Now step 2  

**mı hẻukūeqchē**
> ganbat[t]e!  

**mı hỏemāı**
> How do you say "I know that (people) do not find things important" (use "**bu sủaojı̄e**" as you did before, but apply what you just learned)  

**mı hẻukūeqchē**
> ok, on it  
> **sủao nỏacā bû sủaojı̄e nı̀e lójı̄bāq chẻmē**  

**mı hỏemāı**
> (I should have asked for a slightly different sentence)  
> Oh you are jumping way ahead  
> But it's spot on. :)  

**mı hẻukūeqchē**
> ?oh, sorry XD **dủ[a] jı́ bû sủaojı̄e póq**  

**mı hỏemāı**
> Yeah yeah, now you don't need to do that anymore, but good job anyway :P  

**mı hẻukūeqchē**
> true, but trying still felt good!  
> thanks for the help 😃

**mı hỏemāı**
> One last challenge before you ask your second question  

**mı hẻukūeqchē**
> ready!  

**mı hỏemāı**
> How would you say this same sentence using the word **lu**?  

**mı hẻukūeqchē**
> **dủa jı́ lû bủ sủaojı̄e póq?**  

**mı hỏemāı**
> Yes, that's correct.  
> **lu** has different (related) functions depending on the tone used.  

**mı hỏemāı**
> The two basic ones are the verbose forms of ◌̂ and ◌̌  
> **lû fả jı́** = **fâ jı́** ("that I go")  
> **póq lǔ fả hóa** = **póq fǎ hóa** ("the person who goes")  
> There are two main reasons why someone would want to use the verbose forms: 
> 1) the added redundancy can make a sentence easier to understand (and it allows a speaker to stall if they need a second to think which verb they want to use), and 
> 2) it's required if you want to use a prenex in the subordinate clause.  
> (<http://toaq.org/#prenex>)  

**mı hẻukūeqchē**
> hm, I see  
> what about the other 5 tones? do they change **lu** too?  

**mı hỏemāı**
> **lū** can be discarded right off the bat, because it's not a possible word  
> So 4 other tones […]  
> **lũ** and **lù** are too complicated for now  
> But **lú** is useful and very common  
> **lủ** is similar  
> **lú** makes nouns like ◌́ normally does  
> but because it's **lu**, it takes a complete statement  
> and the head of the subordinate statement is marked by the pronoun **hoa**  
> This pronoun also appears in relative clauses, and it does the same thing here  
> You could think of "**lú fả hóa**" as a shortcut for "**ráı lǔ fả hóa**"  
> "That which goes"  
> "the goer"  
> It means exactly the same as just "**fá**"  
> What's the point, then? Well  
> since **lú** is followed by a statement, you can fit in a lot more than with plain "**fá**"  
> For example:  
> **lú fả hóa chı́ejı̄o**  
> that which goes to school  
> they who go to school  
> the goers to school  
> If you said "**fá chı́ejı̄o**", you would have two individual nouns: "the goer, the school"  

**mı hẻukūeqchē**
> ok, so it lets you make noun phrases that are as detailed and structured that you want  

**mı hỏemāı**
> Yes, and the important part is that the noun phrases are made from statements.  
> You can make detailed nouns without **lú**, by using serial predicates and relative clauses  
> but the structure is different, and often more complex  
> And advanced way to use **lú** + **hóa** is to bury the **hóa** quite deeply in the subordinate  
> For example  
> **lú dủa jı́ tâo súq hóa**  
> These can quickly become very hard to translate into natural-sounding English  
> This one means "that which I know you are doing", "the thing I know you are doing"  

**mı hẻukūeqchē**
> the knower of the one who does?  

[…]

**mı hỏemāı**
> Actually, since you speak Spanish, you can think of it as "lo que"  
> **lú** = lo que  

**mı hẻukūeqchē**
> oh, I think it makes sense. "Lo que se que tu estas haciendo"  

**mı hỏemāı**
> Yes  
> The difference is that Toaq has an explicit pronoun (**hóa**) where Spanish and many other languages have a gap  

**mı hẻukūeqchē**
> yeah, I had never been conscious of that interpretation of "lo que…", I quite like it, especially because now I'm not really sure what "lo que" means anymore XDD  
> but that's another story, for another time  
> thank you so much! I learned a lot  


## On first and second order quantification. Or, quantification over variables and predicates

### 2019-04-03, #general

**mı hẻukūeqchē**
> what is "second order quantification"?
> is it limited to a single slot of a predicate?  

**mı hỏemāı**
> It means quantifying over predicates  
> First-order: ∃*x* **maı**(**jı**, *x*) "there e*x*ists an *x* such that I love *x*"  
> Second-order predicate logic additionally allows quantification over predicates, e.g.: ∃*P* *P*(**jı**, **suq**) "there exists a predicate *P* such that I *P* you"  

**mı hẻukūeqchē**
> can you use it to imply a relationship between two objects, without saying what relationship they have?  

**mı hỏemāı**
> Yes  
> The example above means "there is some relationship between me and you" (relationship in the broad sense)  

**mı hẻukūeqchē**
> cool  
> are there other use cases?  

**mı hỏemāı**
> Not many… You can restrict the domain of the second-order quantifier (using a relative clause), but not many restrictions make sense.  
> [∃*P* : **de**(*P*)] *P*(**suq**) "There exists a beautiful predicate *P* such that you satisfy that predicate"  
> I.e., "You satisfy some beautiful property"  
> With negation, this would be a stronger claim: ¬[∃*P* : **de**(*P*)] *P*(**suq**) "You satisfy not a single beautiful predicate"  
> (mean!)  
> [∃*P* : **noa**(*P*) ∧ **puı**(*P*)] *P*(**ho**) "They do many difficult things"  
> You can say this very easily without second-order quantification  
> E.g. **tảo hó sa púı nỏa** (or something else in place of tao)  

**mı hẻukūeqchē**
> "there is a predicate that satisfies both the properties of difficult and many, and it applies to them"  

**mı hỏemāı**
> Yes  
> (That particular example requires plural quantification as well, because "to be many" is impossible in normal singular logic)  
> (Toaq uses plural quantification, so it's no problem here)  
> (so, "There are predicates", not "there is a predicate")  
> ((but this seems to be an irrelevant tangent at the moment))  

[…]


**mı hẻukūeqchē**
> would first order quantification be called "quantification over variables"?  

**mı hỏemāı**
> Quantification over individuals  
> They both use variables  
> they differ in what the variables range over  

**mı hẻukūeqchē**
> oh, in the first, the variable is an individual, and in the second the variable is an entire predicate?  

**mı hỏemāı**
> refers to, or has as its value, an individual vs a predicate  

**mı hẻukūeqchē**
all right, thanks!


## On quantification and scope

### 2019-04-04, #general

**mı hẻukūeqchē**
> all right, lets start with terminology: what is a constant?  
> is it like, an unchanging value instead of a variable?  

**mı hỏemāı**
> Yes  
> something that keeps its value within a given scope  

**mı hẻukūeqchē**
> so, a QE (Quantified Expression) is not a constant. That means that its value changes depending on the scope?  

**mı hỏemāı**
> We call anything that isn't a quantified term, a constant  
> A quantified expression opens a new scope, within which its variable acts as a constant  
> but the quantified expression itself is not a constant  
> Something is (a) constant, if moving it around in the sentence doesn't change its meaning  
> So e.g.  
> "**tı̉ bũ sa ráı**" is not the same as "**tı̉ sa ráı bũ**"  
> but  
> "**tı̉ bũ ráı**" is the same as "**tı̉ ráı bũ**"  
> the negation by "**bũ**" does not affect the constant "**ráı**", but it changes the meaning of the sentence when it crosses paths with the quantifier "**sa**" in "**sa ráı**"  
> In logic notation:  
> ∃¬  !=  ¬∃  
> ¬[∃*x*] **tı**(*x*)  !=  [∃*x*] ¬**tı**(*x*)  
> but both "**tı̉ bũ ráı**" and "**tı̉ ráı bũ**" have the logical form ¬**tı**(*c*)  

**mı hẻukūeqchē**
> ok, the place of the negation does not change the truth of the expression, when the argument is a constant  
> but if it is Quantified, its truth changes depending on the place of the negation  
> or at least, its meaning, if not its truth  

**mı hỏemāı**
> Negation being only one example. This applies to all of the following: adverbs (◌̃), prepositions (◌̀), quantifiers, and conjunctions.  
> If you have any two of those four in a sentence, their relative order matters  
> whereas a constant wouldn't care on which side of any of those it appears  

**mı hẻukūeqchē**
> so, in the case above, you have an adverb and a quantifier in the same sentence, so the order matters  

**mı hỏemāı**
> Exactly  

**mı hẻukūeqchē**
> if you had a preposition and a conjunction, the order would matter too?  

**mı hỏemāı**
> Yes  
> 1) **kùı hı̂aq jı́ bı jẻa jı́ nı́jūı ro nı́jāo**  
> vs  
> 2) **jẻa jı́ nı́jūı ro nı́jāo kùı hı̂aq jı́**  

**mı hẻukūeqchē**
> 1) "Because poor I **bı**, Buy I this xor that". Since I am poor, I must buy either this or that.  
> 2) "Buy I this xor that, Because poor I". I have to buy either this or that, because I am poor  

**mı hỏemāı**
> 1) is good, but your 2) doesn't sound right. It sounds identical to 1)  
> In English, the reading that number 2) expresses would usually be discarded (both 1) and 2) have the same form in English, because English has ambiguous scope)  
> but 2) does mean something very different  
> A natural translation of 2) would be "[exactly] one of these two things is bought by me for reasons of poorness". So for example, you can't afford an *X* of good quality, so you buy the cheap version of it, because you are poor.  
> And this says NOTHING about the other thing  
> While 1) says that, because you are poor, you can only buy one of the two.  
> So in 1), the reason applies to [either this or that], and in 2), one of the two choices has poorness as the reason  

**mı hẻukūeqchē**
> hm, I am having trouble seeing the difference. I'll make my breakfast and think about it  
> if you can think of another example in the meantime, that would be very helpful  

**mı hỏemāı**
> If this is still unclear, don't panic. I think this kind of contrast starts out seeming extremely subtle if at all noticeable, but once you understand it, the difference is jarring and you can never unsee it  

**mı hẻukūeqchē**
> XD I think that is a benefit of learning toaq, to learn the subtle clues of logic. That is the unique change to your mind that it does  

**mı hỏemāı**
> Yes, that does happen.  
> So, imagine that I bought two things: a marble and a flower. One of the two was bought for reasons of poorness, THE OTHER WAS NOT. The other one might have been bought for a different reason, perhaps because I'm in love and want to give it to someone. But the marble is the cheapest toy I could affort. Sure, I'd prefer to play with a slingshot, but it's too expensive.  
> So now, imagine I show you the marble and the flower  
> and I tell you **jẻa jı́ nı́jūı ro nı́jāo kùı hı̂aq jı́**  
> And then I ask you to guess which one.  

**mı hẻukūeqchē**
> oh! so the difference is that in 1) I bought one or the other, but not both because I am poor, and 2) I bought both, but this one I bought because I was poor, and the other I just bought, no qualification  

**mı hỏemāı**
> Yes :)  

**mı hẻukūeqchē**
> :D nice!  
> I'll keep an eye out for this difference, and archive this conversation  

**mı hỏemāı**
> (technically, in #2, the other one may or may not have been bought, we don't actually know)  
> (but in the situation, since I show you both, you can assume that I did buy both)  

**mı hẻukūeqchē**
> so, in 1# the **kùı** modifies the **jẻa**, but in 2# the **kùı** modifies the **ro**?  

**mı hỏemāı**
> So in summary, in #1 **kùı** *X* scopes over **ro**, which means that *X* is the reason for the **ro**/either-or.  
> In #2, the **ro** scopes over the **kùı** *X*, which means that only one of the two things has the **kùı** *X*  

**mı chảı**
> `%miu` **kùi rái bı hảo shı́ ra gú**  

**mı nủogāı**
> **({[kùı ráı] bı} {hảo [shı́ ra gú]})** 
> \[℩*S* : **shı**(*S*)\] \[℩*G* : **gu**(*G*)\] \[℩*R* : **raı**(*R*)\] **kuı**({**hao**(*S*) ∨ **hao**(*G*)}, *R*).  

**mı chảı**
> `%miu` **hảo shı́ ra gú kùi rái**  

**mı nủogāı**
> **(hảo {[shı́ ra gú] [kùı ráı]})**  
> \[℩*S* : **shı**(*S*)\] \[℩*R* : **raı**(*R*)\] \[℩*G* : **gu**(*G*)\] **kuı**({**hao**(*S*)}, *R*) ∨ **kuı**({**hao**(*G*)}, *R*).  

**mı chảı**
> see how there are two **kuı** in the latter expansion?  
> you can imagine that **ro** is a kind of branching of a path; this branching can happen before or after the quantification  
> if the branching happens before the quantification, the quantification goes in both of the branches  
> **raı shı́ ro gú** → **raı shı́, na ro raı gú**  
> this branching either is or isn’t in the containing ◌̀ clause  
> somebody explain this better – I have no time now  


## On horses and relative clauses. Or, falling-rising, incidentals, and **lú**

### 2019-04-5, #chiejio

**mı hẻukūeqchē**
> I've also been reading on relative clauses, and there seems to be two types in English:  
> * the ones that distinguish the noun from other similar nouns (in a stable full of horses, "I want the horse THAT is white")
> * and the one that just gives you more information on it ("My horse, WHICH is white, is so pretty!")  

**mı shủao**
> Restrictive and non-restrictive?  

**mı hẻukūeqchē**
> exaclty  
> does that distinction exist in Toaq too?  

**mı hỏaqgı̄o**
> Yes  
> In the sense that it only has restrictive ones, directly speaking  
> Incidental information of any kind can be included with **ju**  

**mı shủao**
> non-restrictive clauses are called 'incidentals'  
> There's a section on those on toaq.org.  

**mı hỏaqgı̄o**
> Like this: "**mảı jí pójī kảtū, ju bảo hó**" = "I like my cat, which is white"  
> As opposed to "**mảı jí pỏjī kảtū bäo**" = "I like my white cat [and maybe not the other one(s)]"  

**mı hẻukūeqchē**
> oh, so all relative clauses are restrictive, and the equivalent of non-restrictive relative clauses are **ju** incidentals  

**mı hỏaqgı̄o**
> Yes, exactly  
> (Though **ju** is more general, you can put anything you like inside a **ju** clause)  

**mı hẻukūeqchē**
> @Hỏaqgīo , you're right, it does seem more general. Like a parenthetical, where you can put anything in there.  Just that it is often used AS a non-restrictive clause  

**mı hỏaqgı̄o**
> Exactly  

**mı hẻukūeqchē**
> the wikipedia article also mentioned bound relative clause (one that refers to a head) and a free relative clause (one that doesn't refer to any head, acting itself as a noun)  
> does that exist in toaq too?  

[…]

**mı hẻukūeqchē**
> my understanding is that it doesn't, because toaq.org DOES say that (in a way) every relative clause refers to a head. And that that's why you can imply **hóa** as the first argument of the relative clause  
> the example they use is: I like *what I see*, where the ‘what I see’ is the free relative clause  

**mı hỏaqgı̄o**
> Oh, I see  
> Those exist in Toaq, but they aren't considered "relative clauses"  
> They are accomplished by using **lu** with ◌́  
> Like this:  
> "**lú pảı jí hóa**" → The one I'm friends with  

**mı hỏemāı**
> We learned about those the other day.  
> (lo que)  

cf. [On the problem of indifference, nesting, and subordination](#On-the-problem-of-indifference-nesting-and-subordination)

**mı hẻukūeqchē**
> oh, ◌́ makes nouns, and combined with lu it makes the special noun  


## On the 5 ways to describe a noun. Or, the yellow flower, **rúa lủe**

**mı hẻukūeqchē**
> since relative clauses modify nouns, would you say that they are like adjectives?  
> and, since we're talking about adjectives, how do they work in toaq? I think I've seen serial predication fill the role of making adjectives  
> like: **bảorēo hı̉uhēkūo nı́**  

**mı sẻaqtāq**
> Relative clauses are also called adjectival clauses  

**mı sẻaqtāq**
> Hoemai explained adjectives in the alpha primer  
> here: <http://selpahi.de/ToaqAlphaPrimer.html>, 6.1  

**mı sẻaqtāq**
> So yeah  
> there are adjective like predicates like **sao**: *X* is big, and combined with **ru** serialization, you get things like **sao pỏq** or **poq sảo** (the order doesn't matter because none of those predicates have a subordinating slot)  
> That last point in parenthesis allows some really fun stuff  
> e.g. **pỏq gẻo sảo bủaı hỏı**  
> although with this you must be careful, because **hoı** does have a slot that subordinates, so you want it either before **poq** or at the end, because with **hoı** in particular it doesnt make that big of a difference whether it subordinates the thing it is meant to or simply connected through **ru**  
> I guess that putting **hoı** before one of the adjectival like predicates in that example wouldn't affect the meaning too much  

**mı hẻukūeqchē**
> I like that "context-aware and"  

[…]

**mı hỏemāı**
> That "**fı**" is what the implied connective may end up being in **sảo pỏq**. But my research isn't complete yet.  
> (of course it wouldn't be spelled "**fı**")  
> (it makes things a lot simpler, logically, but I need to be sure that it's necessary. I have read different opinions)  

**mı hẻukūeqchē**
> so, there are, like, 4 ways to say more about a noun: relative clauses, **ju**, RU serialization, and **fı**/**ru** connective  

**mı sẻaqtāq**
> and **lủ**  

**mı mỏılūq**
> and plain serialization to some extent  
> example: **rúa lủe** = flower (and) yellow  
> here you can add or remove **ru** without difference  

**mı hẻukūeqchē**
> XD all right, like 6: plain serialization, RU serialization, relative clauses, **lủ**, **ju**, and **fı**/**ru** connectives  
> what is RU serialization?  

**mı mỏılūq**
> **rúa ru lủe**  
> **rúa ra lủe** = what is either a flower or is yellow (or both)  

**mı sẻaqtāq**
> What I meant by it were cases when an implicit **ru** is present  
> like in **rủa lủe**  
> :V  

**mı hẻukūeqchē**
> ah, so its a serial where **ru** is implicit  

**mı sẻaqtāq**
> I thought that is what it meant, but ilmen seems to have a different interpretation so im not really sure anymore  

**mı hẻukūeqchē**
> whaddayasay, @Mỏılūq ?  

**mı mỏılūq**
> what is your interpretation of what?  
> **rúa lủe** = **rúa ru lủe**  
> I don't think there's disagreement there  

**mı sẻaqtāq**
> Oh  
> I thought you were saying that RU  serialization is when a member of RU is explicit  

**mı mỏılūq**
> Well, I didn't get what was exactly meant by "RU serialization"  
> you could say "additive serialization" maybe  

**mı sẻaqtāq**
> m̨̄m̨̄m̨̄m̨̄  
> Yeah i think that is better @Mỏılūq  and then we could use RU serialization for when a member of RU is explicit  
> that makes more sense  
> Also I should have just copied and pasted because I wrote the exact same thing  

**mı hẻukūeqchē**
> hey, practice you touch typing!  
> btw, **chủfāq shỏ pảq nı́ káıpūmē**  

**mı hẻukūeqchē**
> for the archive:  
> there are 7 ways to describe a noun: plain serialization, additive serialization, RU serialization, relative clauses, **lủ**, **ju**, and **fı**/**ru** connectives  

**mı mỏılūq**
> the 8th way is to add nothing and leave the details up to the imagination of the reader  

**mı sẻaqtāq**
> %)  

[…]

**mı hỏemāı**
> Isn't RU serialization = **fı**/**ru** connectives ?  

**mı sẻaqtāq**
> No that one is supposed to be additive  
> I think so  
> RU serialization should encompass **fı**/**ru**  

**mı hẻukūeqchē**
> I think the difference is that **fı**/**ru** connection are explicit, while RU serialization leaves the connectives implicit  

**mı hỏemāı**
> Why don't you list it as "serial predicates, (implicit or explicit) RU, relative clauses, **ju**"  

**mı hẻukūeqchē**
> yeah, I like that order better  
> less items to remember too XD  

### Summary:
There are 5 ways to describe a noun: serial predicates, (implicit or explicit) RU, relative clauses, and **ju**.
