# Guidelines for Framenet annotation of Ancient Greek (v.0.1)

**Attention**: this document is intended as a preliminary draft. Its aim is to 
sketch an initial workflow and a series of guidelines to create a FrameNet of 
Ancient Greek based on a full corpus annotation of some selected texts of the same 
type that the original Framenet project does with English.

## Framenet

### Frame semantics

[FrameNet](https://framenet.icsi.berkeley.edu/fndrupal/) is a lexical database of English based on a theory of meaning called "Frame Semantics", which was proposed by Charles Fillmore in a series of publications. According to Frame Semantics, the meaning of a word "can best be understood on the basis of a semantic frame, a description of a type of event, relation, or entity and the participants in it" (quoted from [here](https://framenet.icsi.berkeley.edu/fndrupal/WhatIsFrameNet)).

The goal of this project is to extend this model to Ancient Greek for the first time, by concentrating on a full-text annotation of a number of classical texts. Our annotation builds upon the morphosyntactical annotation of the [Ancient Greek and Latin Deependency Treebank](https://perseusdl.github.io/treebank_data/).

### Theory and Annotation
Frame semantics is based on the notion that the meaning of a word is accessible by referring to the semantic frame (i.e. the schematic representation of the roles, relations, and participants involved) that the word evokes. Thus e.g., the meaning of the verb "to buy" is understandable in reference to a prototypical situation involving a seller, a buyer and the exchanged goods and values.

The goal of FrameNet is to create a lexical resource showing how semantic frames are realized in actual texts, and how frame elements are syntactically linked to the word that evokes the frame. Annotation is performed by tagging a target Lexical Unit (LU), assigning it to a specific semantic frame, and by annotating also the roles that the selected frame evokes. These roles (called “Frame Elements”, FE) are identified by **frame-specific descriptive labels** (e.g. `buyer`).

As an example of how this model can be applied to AG, consider this sentence from Sophocles, Antigone, 127-8:

> **_Ζεὺς_** γὰρ *μεγάλης γλώσσης κόμπους* **ὑπερεχθαίρει**

> For **_Zeus_** **detests** above all *the boasts of a proud tongue*

The target LU (in bold) can be assigned to the frame: [Experiencer_focused_emotion](https://framenet2.icsi.berkeley.edu/fnReports/data/frame/Experiencer_focused_emotion.xml). The core elements that are expressed in this sentence are: the “Experiencer” (Ζεὺς, bold-italic) and the “Content” (μεγάλης γλώσσης κόμπους, italic).

FrameNet distinguish two types of annotation:
* **lexicographical annotation**: usedo to record every semantic and syntactic combination for each target word, for each of its senses. Thus, a series of occurrence of a specific target words in the reference corpus are chosen and annotated.
* **full-text annotation**: given a text, every frame-evoking word is annotated.

### FrameNet and other standards for semantic annotation

## Proposed Workflow

## Annotation concepts

## Special problems
