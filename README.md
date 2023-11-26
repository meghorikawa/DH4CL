# DH4CL
A project for my Digital Humanities for Computational Linguistics Course from Sommer 2022 semester dealing with a lexicon approach for Affect analysis. I plan to continue this project by fine-tuning a model to identify affective states in Japanese text. 

![alt text](https://github.com/meghorikawa/DH4CL/blob/main/affectivescores.png)

## Abstract

Previous research has been done in analyzing
the affective orientation of song lyrics, however,
not in Japanese. Here an affect analysis
package for Japanese was used to identify
affective states in a corpus of Japanese
rock music. Lyrics were given an affective
score to quantitatively measure the prevalence
of affective states which was then compared
across the time span of the corpus. An increasing
use of negatively oriented affective expressions
was found. Challenges when working
with Japanese text, as well as linguistically
unique characteristics when expressing emotions
in Japanese were also identified, to encourage
further research and improvement in
this area.

## Conclusion

While ML Ask overall is able to identify affective
oriented expressions using its lexicon based
method, it is also limited by this approach. A package
 is limited by the size of it’s lexicon,
especially when dealing with orthographic variation,
which is very common in Japanese text. The
affective classes most detected in the corpus were
also the classes which had the largest lexicons.
The higher the quantity of affective expressions a
lexicon,the higher the chance for recognizing affective
oriented words. However, with a lexicon based
approach there is also the risk that any instance
of an expression in the lexicon will be counted as
emotional, even if it is used in a non-affective context.
I do believe that a system that goes beyond a
lexical approach, will be needed to more accurately
analyze texts for their affective states.
Analyzing text at the sentence level, also leaves
out important details in context beyond the sentence,
and how the sentence my fit in with the rest
of the document. For example, being able to identify
emotions behind actions described in a text,
as well as metaphors and sarcasm is essential for
affect analysis to correctly identify affective statements
in a text, especially when working with literature
and other creative text mediums. Just identifying
a use (or non-use) of an affective expression
is not enough to determine if an utterance/sentence
is actually affectively oriented or not. For example,
recognizing in the correct context, an expression
such as, ”I only see you,” as having an attitude
for liking someone, versus when describing the
number of people in a room which wouldn’t be an
affectively aligned statement.
While Nakamura’s Emotional Expressions Dictionary
emotional classes mostly align with
Scherer’s more recent study on affective classes,
more recent research on affective states in Japanese
is needed. This may show alignment with findings
from studies done in other languages of universal
affective classes, or may also provide insight into
linguistically unique features of Japanese, that will
need to be considered when developing a system
to analyzing affective expressions. Affective states
may not overlap semantically between languages
so it is important that any systems developed to
identify affective expressions should take this into
account.
As development continues in this
field,improvement in detecting negatives and
orthographic variation in Japanese, along with
further research into the linguistic structure of
emotive expressions in Japanese, will allow
development of a system that can provide an affect
analysis of Japanese text on a document level.
