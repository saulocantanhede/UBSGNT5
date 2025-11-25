<a name="start"></a>

# UBSGNT5 - Features

In Text-Fabric, a *feature* refers to attributes associated with a certain nodes type (like words). The feature value provide additional information specific to the attribute of that node.

[All features listed by feature name](featuresbyname.md#start).

The full featureset of this Text-Fabric dataset can also be viewed by different grouping methods:
* [Grouped by feature type](featuresbytype.md#start)
     * [`Node`](featuresbytype.md#node): the fundamental units or entities in the data model.
     * [`Edge`](featuresbytype.md#edge): relationships or links, establishing connections between nodes in the data model.
* [Grouped by node type](featuresbynodetype.md#start):
     * [`book`](featuresbynodetype.md#book): the highest-level division within the text, corresponding to a bible book.
     * [`chapter`](featuresbynodetype.md#chapter): divisions within the text that group related content together, specificaly the biblical chapter.
     * [`section`](featuresbynodetype.md#section): divisions within the text that group related the same content together.
     * [`parsedtext`](featuresbynodetype.md#parsedtext): divisions within the text that group parsed text.
     * [`sentence`](featuresbynodetype.md#sentence): represents individual sentences in the text.
     * [`tree`](featuresbynodetype.md#tree): divisions within the text that group tree of data.
     * [`verse`](featuresbynodetype.md#verse): pertains to divisions within a larger textual unit, specificaly the biblical verse.
     * [`clause`](featuresbynodetype.md#clause): nodes pertaining to a clause unit.
     * [`phrase`](featuresbynodetype.md#phrase): nodes pertaining to a phrase unit.
     * [`subphrase`](featuresbynodetype.md#subphrase): nodes pertaining to a subphrase unit.
     * [`functionalword`](featuresbynodetype.md#functionalword): represents syntatical functional words in the text.
     * [`word`](featuresbynodetype.md#word): represents individual words in the text.
* [Grouped by datatype](featuresbydatatype.md#start):
     * [`integer`](featuresbydatatype.md#integer): Datatype of feature is integer.
     * [`string`](featuresbydatatype.md#string): Datatype of feature is string.

This repository uses the nomenclature used in the Nestle 1904 GNT dataset. More information can be checked [here](https://centerblc.github.io/N1904/).
