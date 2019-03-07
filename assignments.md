---
layout: page
title: Assignments
permalink: /assignments/
---

* TOC
{:toc}
{::options toc_levels="2" /}

Assessment is weighted as follows:

10%
: Participation

35%
: Weekly transcriptions (due 17:00 Thursdays)

10%
: Manuscript collation (due 27 February and 8 March)

15%
: Group edition draft (due 15 March)

30%
: Group edition (due 5 April)

All assignments must be submitted in either English or French through Quercus. Any citation style may be used in this course as long as it is consistent: I recommend either the [*MHRA Style Guide*](http://mhra.org.uk/style) or the [*Chicago Manual of Style*](https://chicagomanualofstyle.org).

## Participation

As a seminar, this course can only function with your contribution. In each class, we will take up the previous week's transcription exercises, read an additional passage without preparation, and discuss the historical development of scripts and textual transmission based on the assigned readings.

## Weekly transcriptions

Every week, you will transcribe passages from two manuscripts using the TEI markup demonstrated in-class. See my page on [Getting started with editing TEI XML using Atom
](https://andrewdunning.ca/getting-started-editing-tei-xml-atom) to download the software for this. The class [TEI transcription template](../assets/transcription-template.xml) provides a framework for your submissions.

## Collation exercise

As a preliminary to the final project, we will create an edition of the *Passion of Perpetua and Felicity,* chapter 5, with the aim of showing what the text might have looked like around the tenth century (as opposed to the archetype, as represented in Heffernan's edition). Submit this in three parts:

1. Transcribe the three assigned manuscripts (due 27 February)

2. Create an edition from the three sources (due 8 March)
    - Use the [edition template](../assets/perpetua-template.xml) as a starting point for your edition, which lists the manuscripts we're using.
    - Paste each of your transcriptions into the [TEI Web Editor](https://tei-web-editor.herokuapp.com) and paste the version stripped of its tags into [CollateX](https://collatex.net/demo/).
    - Decide on a manuscript to use as a base text and record the significant differences (not mere spelling variants) using the TEI `<app>` tag, as the [Digital Latin Library guidelines](https://digitallatin.github.io/guidelines/LDLT-Guidelines.html) describe. Add punctuation to your text, either based on the manuscript or a modern system, to make it usable for a reader.
    - If you want to see what your work would look like as a printed critical edition, you can upload it to the [TEI Critical Apparatus Toolbox](http://teicat.huma-num.fr).
      
3. Make a translation of the passage to document how you are understanding your choices of variants. You can submit the translation in any format you wish; it does not need to be in TEI.

## Group edition: The Romsey Legendary

Our final project will be an edition of selections from the Romsey Legendary ([London, British Library, Lansdowne MS 436](https://www.bl.uk/catalogues/illuminatedmanuscripts/record.asp?MSID=5273)), a mostly-unpublished collection of saints' lives from the early fourteenth century that once belonged to the nuns at Romsey Abbey. But did the nuns either compose or write it? Was it written for them? Or did they just randomly get hold of this manuscript? I hope that we'll be able to answer these questions by the end of the course by editing and translating some of its texts.

I will assemble our work into a single file at the end of the year and submit it to a publisher. I have created an [online sample](https://andrewdunning.ca/romsey-legendary/) to give you some idea of what the texts look like. The online [*Life of St Winifred*](https://doi.org/10/gftm82) is an example of one of the stories with an introduction and translation, and is worth reading to get an idea of some of the questions involved. (I do not expect your introduction to be so detailed as this.)

Some of the vocabulary might be unfamiliar if you haven't read much medieval Latin, but it's fairly limited, and they don't tend to do anything fancy with the syntax. Look up any words you don't know using the *Dictionary of Medieval Latin from British Sources*, available on [Logeion](http://logeion.uchicago.edu).

To complete the project:
 
1. Choose a life from the collection. You can partner with someone else on a longer text if you wish.

2. Transcribe the relevant section of the manuscript. See the [TEI source](https://github.com/adunning/romsey-legendary/blob/master/romsey-legendary.xml) as an example of the conventions to follow:
      - Use `<lb/>` or `<lb break="no">` as appropriate to indicate new lines.
      - Follow the manuscript's punctuation and capitalization -- it uses a capital letter for the beginning of a sentence and occasionally a proper noun. Mark any names using `<persName>`, `<placeName>`, `<geoName>`, or `<orgName>` as appropriate (which will be formatted with a capital letter in the final version).
      - To save time, you do not need to indicate the letters you have added to expand an abbreviation.
      - Mark the beginning of a new page with `<pb n="103r"/>` (providing the appropriate reference) and new columns with `<cb n="a"/>` ('a' for column one, 'b' for column two).

3. You will also transcribe one of your peers' sections to provide a control. When doing this, it is not necessary to transcribe the text using TEI, since you will simply be comparing the two transcriptions using [CollateX](https://collatex.net/demo/) to find errors.

4. Make a translation of your text, adjusting your edition as you work.

5. Write a brief introduction to your section. This should include:
    - A summary of the text;
    - Any hints we might have as to the work's author(s);
    - Any major sources for the text that you can identify (try searching for similar texts in the [Acta Sanctorum](http://acta.chadwyck.com.myaccess.library.utoronto.ca));
    - Discussion of any interesting features in the manuscript.

## Analytical writing rubric

I will grade your written work based on a set of six criteria.

| Characteristic                    | Exceptional (A, 80–100)                                                                                                                                                 | Well-Done (B, 70–79)                                                                                                    | Fair (C, 60–69)                                                                                                                 | Needs Work (D, 50–59)                                                                                                         | Poor (F, 0–49)                                                                                                    |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| Argumentation (20 marks)          | Robust and clear arguments that go beyond description, offering nuanced and sophisticated insights; all sections directly support a precise and coherent thesis (16–20) | Discernible arguments, offering sound insights; most sections directly support an explicit and plausible thesis (14–15) | Somewhat unclear or weak arguments, offering mostly sound insights; thesis may be too vague or broad a claim to support (12–13) | Arguments often fall into description or summary, with weak or logically inconsistent insights or an ambiguous thesis (10–11) | Makes no attempt to construct an argument, presenting unsupported generalizations or no identifiable thesis (0–9) |
| Analytical Originality (20)       | Demonstrates exceptional analytical originality, both in creating new arguments and in relating facts in new ways (beyond what is covered in course material) (16–20)   | Demonstrates analytical originality, either in creating new arguments or in relating facts in new ways (14–15)          | Demonstrates only some analytical originality, often relying on arguments and evidence already covered in class (12–13)         | Demonstrates little analytical originality, mostly dependent on arguments and evidence already covered in class (10–11)       | Makes no attempt to provide original analysis (0–9)                                                               |
| Research and Evidence (20)        | Detailed and comprehensive evidence demonstrates wide reading of relevant literature; quotations are pertinent and fully integrated with argument (16–20)               | Thorough evidence from appropriate sources supports arguments; quotations carefully selected (14–15)                    | Evidence generally supports arguments, but may need more depth or rely too heavily on quotations (12–13)                        | Needs more thorough or additional evidence to support arguments; sources are unsound (10–11)                                  | Fails to offer evidence to support arguments (0–9)                                                                |
| Content Knowledge (20)            | Demonstrates superlative mastery of material (16–20)                                                                                                                    | Demonstrates excellent understanding of content and is comfortable with nuances in material (14–15)                     | Conveys content adequately but fails to elaborate (12–13)                                                                       | Gets basic content correct but is otherwise uncomfortable with material (10–11)                                               | Basic content is wrong, incorrect, or substantially incomplete (0–9)                                              |
| Structure and Organization (10)   | Logical structure with clear organization that walks the reader through arguments and evidence (8–10)                                                                   | Logical structure with clear organization (7)                                                                           | Clear organization, but veers at times from logical structure (6)                                                               | Veers significantly from logical structure and/or is not well organized (5)                                                   | No logical structure; poorly organized (0–4)                                                                      |
| Grammar, Syntax, Punctuation (10) | No errors; properly and consistently uses an appropriate citation style (8–10)                                                                                          | No major errors, a few minor errors that do not distract; no significant faults in citation style (7)                   | One major error or several minor errors that do not distract; a few faults in citation style (6)                                | Two or three major errors combined with minor errors; several faults in citation style (5)                                    | Numerous major errors; serious faults in citation style (0–4)                                                     |

Adapted from Maria Rost Rublee, ‘Rubrics in the Political Science Classroom: Packing a Serious Analytical Punch’, *PS: Political Science & Politics* 47, no. 1 (January 2014): 201, <https://doi.org/10.1017/S1049096513001704>.
