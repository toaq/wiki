<style>
@font-face {
  font-family: 'ToaqScript';
  src: url({{ 'assets/ToaqScript_v0.341.ttf' | relative_url }});
}
u {
  text-decoration: none;
  font-family: ToaqScript;
  font-size: 150%;
}
</style>

<h1 style="font-size: 500%; font-family: ToaqScript; text-align: center;">EhNoykR</h1>

<b>ToaqScript</b>, hereafter referred to as Hoelai, is a writing system developed by **mı hỏemāı**.

*Note: the following is not endorsed by **mı hỏemāı** himself. Not only that, but most of the linked material is his. I am sharing it under his permission. All credit should go to him, not me.*

@@toc@@

## Description

**mı hỏemāı** has shared a list of glyphs in a PDF. You can get it [here]({{ 'assets/script-sheet.pdf' | relative_url }}).

A Toaq syllable is analysed into four Hoelai parts:
1. the consonant, which becomes the glyph in the middle;
2. the first phoneme in the nucleus, which is written right of the consonant (unless it is **a**, in which case it should be omitted);
3. the rest of the nucleus, written left of the consonant (optional);
4. the tone, together with the coda (presence/absence of **-q**), written above. (This part is empty for neutral tone syllables without **-q**.)

Note that if the nucleus ends in a diphthong – one of **-ai, -ao, -oi, -ei** – it is treated as a `(3)`. Moreover, if this diphthong is the whole nucleus, `(2)` is omitted in favour of it. For example, **maı** is understood to be `m--ai`, not `m-a-i`; it would be written with the **-ai** glyph from `(3)`.

### Reference sheet

![Reference sheet]({{ 'assets/reference-sheet.png' | relative_url }})

Here's how your browser renders these characters:

<div>
  <u>
    <p>q qQ&ensp;qR qL&ensp;qP qB&ensp;qX qZ&ensp;qN qM&ensp;qT qD&ensp;qK qG&ensp;qF qV</p>
    <p>m p b&ensp;f&ensp;n t d c s r l&ensp;w j x&ensp;qQ k g&ensp;h</p>
    <p>A_a&ensp;U_u&ensp;I_i&ensp;O_o&ensp;E_e&ensp;y_&ensp;v_&ensp;z_&ensp;W_&ensp;qY</p>
  </u>
</div>

In this reference sheet, there are three rows:
1. All the tones with and without **-q** (`(4)` in the list above), in the usual order.
2. All the consonant glyphs (`(1)` in the list above), in this order: **m p b – f – n t d c s r l – ch j sh – q k g h**.
3. All the vowel and diphthong glyphs (`(2)` and `(3)`), in this order: **a u i o e ai ao oi ei**.

The circle ‘consonant’ signifies the lack of a consonant; an underdot signifies the lack of a vowel. This is the reason why **q** from the second row was written as a null consonant + **-q**.

## The font

Get the latest version: [v0.341]({{ 'assets/ToaqScript_v0.341.ttf' | relative_url }}).

The reference sheet from above is typed as follows:
```
q qQ  qR qL  qP qB  qX qZ  qN qM  qT qD  qK qG  qF qV 
m p b  f  n t d c s r l  w j x  qQ k g  h 
A_a  U_u  I_i  O_o  E_e  y_  v_  z_  W_  qY
```

1. Consonants stay as they are, with the exception of the two digraphs, **ch** and **sh**, which are mapped to `w` and `x` respectively.
2. First vowels stay as they are.
3. Last vowels are capitalised, with **-ai -ao -oi -ei** mapped to `y v z W` respectively.
4. The tone mark (if present) is written with a capital letter – the corresponding [Vietoaq](vietoaq.md) final. In short: **aq ā āq á áq ǎ ǎq ả ảq â âq à àq ã ãq** are mapped to `Q R L P B X Z N M T D K G F V`.

`(3)` comes first, then `(1)`, then `(4)`, then `(2)`. The null consonant (circle) is `q`; the null vowel (underdot) is `Y`. The first sentence from the sample text below would be `pFuvjR bi EmNi s xPi yrNuAjLo AdXo tKi tu lPu pM AhPo AgPu n, AdTugRi AhPo d`.

Automated ways of converting plain Toaq into ToaqScript input will be made publicly available soon. Currently, [the Discord bot](nuogai.md) can generate an image of the script for you: use `%hoe` with plain Toaq as input.

## Demonstration

1. <span style="color: #ffaa00;"><code>(3)</code> last vowels</span>
2. <span style="color: #770033;"><code>(1)</code> consonants</span>
3. <span style="color: #aa3333;"><code>(4)</code> tone + <strong>-q</strong></span>
4. <span style="color: #ff44ff;"><code>(2)</code> first vowels</span>

<u>OjFe bi mQY dMmLi ymT qNe rG pBo vkNu</u>

<!-- This is the dumbest ever way to do this, I know. -->

<u style="font-size: 300%">
<span style="color: #fa0;">O</span><!--
  --><span style="color: #703;">j</span><!--
  --><span style="color: #a33;">F</span><!--
  --><span style="color: #f4f;">e</span> <!--
  --><span style="color: #703;">b</span><!--
  --><span style="color: #f4f;">i</span> <!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #a33;">Q</span><!--
  --><span style="color: #f4f;">Y</span> <!--
  --><span style="color: #703;">d</span><!--
  --><span style="color: #a33;">M</span><!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #a33;">L</span><!--
  --><span style="color: #f4f;">i</span> <!--
  --><span style="color: #fa0;">y</span><!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #a33;">T</span> <!--
  --><span style="color: #703;">q</span><!--
  --><span style="color: #a33;">N</span><!--
  --><span style="color: #f4f;">e</span> <!--
  --><span style="color: #703;">r</span><!--
  --><span style="color: #a33;">G</span> <!--
  --><span style="color: #703;">p</span><!--
  --><span style="color: #a33;">B</span><!--
  --><span style="color: #f4f;">o</span> <!--
  --><span style="color: #fa0;">v</span><!--
  --><span style="color: #703;">k</span><!--
  --><span style="color: #a33;">N</span><!--
  --><span style="color: #fa0;">u</span>
</u>

<pre>
<span style="color: #fa0;">O</span><!--
  --><span style="color: #703;">j</span><!--
  --><span style="color: #a33;">F</span><!--
  --><span style="color: #f4f;">e</span> <!--
  --><span style="color: #703;">b</span><!--
  --><span style="color: #f4f;">i</span> <!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #a33;">Q</span><!--
  --><span style="color: #f4f;">Y</span> <!--
  --><span style="color: #703;">d</span><!--
  --><span style="color: #a33;">M</span><!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #a33;">L</span><!--
  --><span style="color: #f4f;">i</span> <!--
  --><span style="color: #fa0;">y</span><!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #a33;">T</span> <!--
  --><span style="color: #703;">q</span><!--
  --><span style="color: #a33;">N</span><!--
  --><span style="color: #f4f;">e</span> <!--
  --><span style="color: #703;">r</span><!--
  --><span style="color: #a33;">G</span> <!--
  --><span style="color: #703;">p</span><!--
  --><span style="color: #a33;">B</span><!--
  --><span style="color: #f4f;">o</span> <!--
  --><span style="color: #fa0;">v</span><!--
  --><span style="color: #703;">k</span><!--
  --><span style="color: #a33;">N</span><!--
  --><span style="color: #fa0;">u</span>
</pre>

<strong style="font-size: 150%">
<span style="color: #703;">J</span><!--
  --><span style="color: #f4f;">e</span><!--
  --><span style="color: #a33;">&#x303;</span><!--
  --><span style="color: #fa0;">o</span> <!--
  --><span style="color: #703;">b</span><!--
  --><span style="color: #f4f;">ı</span> <!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #a33;">&#x304;</span> <!--
  --><span style="color: #703;">d</span><!--
  --><span style="color: #f4f;">a</span><!--
  --><span style="color: #a33;">&#x309;</span><!--
  --><span style="color: #a33;">q</span><!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #f4f;">ı</span><!--
  --><span style="color: #a33;">&#x304;</span><!--
  --><span style="color: #a33;">q</span> <!--
  --><span style="color: #703;">m</span><!--
  --><span style="color: #fa0;">a</span><!--
  --><span style="color: #a33;">&#x302;</span><!--
  --><span style="color: #fa0;">ı</span> <!--
  --><span style="color: #f4f;">e</span><!--
  --><span style="color: #a33;">&#x309;</span> <!--
  --><span style="color: #703;">r</span><!--
  --><span style="color: #f4f;">a</span><!--
  --><span style="color: #a33;">&#x300;</span><!--
  --><span style="color: #a33;">q</span> <!--
  --><span style="color: #703;">p</span><!--
  --><span style="color: #f4f;">o</span><!--
  --><span style="color: #a33;">&#x301;</span><!--
  --><span style="color: #a33;">q</span> <!--
  --><span style="color: #703;">k</span><!--
  --><span style="color: #f4f;">u</span><!--
  --><span style="color: #a33;">&#x30c;</span><!--
  --><span style="color: #fa0;">a</span><!--
  --><span style="color: #fa0;">o</span>
</strong>

## Sample text

(Note: The Toaq font is rendered at 150% of its nominal size.)

> <u>pFuvjR bi EmNi s xPi yrNuAjLo AdXo tKi tu lPu pM AhPo AgPu n, AdTugRi AhPo d.</u>
> > **pũjāo bı mỉe sa shí rủaıjōaq döa tì tu lú pảq hóa gúa na, dûagī hóa da.**  
>
> <u>bNu ygN hPo Asi yrP n, ru dNu tNiAtRu bB cu hPo nBivdR rZ AhPo sBo IxNu n, OpKe OrPi d.</u>
> > **bủ gảı hó sıa ráı na, ru dủ tỉtūa báq cu hó níqdāo räq hóa sóq shủı na, pèo río da.**  
>
> <u>Oke dMu hPo s AjPu d. </u>
> > **keo dủq hó sa júa da.**  
>
> <u>vrK tu wB EbKi wDu hPo OrBehL n, vrK tTiAxRe tBoAfRu n, ru tNi Asi AmPeOhRe bi, ydNu tNiAtRu s xPi AwMe ElMuwRe s xPi AmNeOhRe hM d.</u>
> > **rào tu cháq bìe chûq hó réoqhāq na, rào tîshēa tóqfūa na, ru tỉ sıa méahēo bı, dủaı tỉtūa sa shí chẻaq lủeqchē sa shí mẻahēo hảq da.**  
>
> <u>Oke mu EtNi mB n, ru AjMu bNu AdNu ElBuwRe hDe mB hi yrP d.</u>
> > **keo mu tỉe máq na, ru jủaq bủ dủa lúeqchē hêq máq hı ráı da.**  
