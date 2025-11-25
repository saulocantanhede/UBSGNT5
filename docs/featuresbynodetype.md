Doc4TF pages for UBS GNT5 (converted from Emdros) (version 0.0.8)
# Overview features by node type
Overview by [name](featuresbyname.md), [data type](featuresbydatatype.md), or [feature type](featuresbytype.md).
## book

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`book`](book.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|book name (full name)|`Acts` `Colossians` `Ephesians` `Galatians`
[`book_short`](book_short.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|book name (abbreviated) from Emdros dataset|`1CO` `1JN` `1PE` `1TH`
## chapter

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`book`](book.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|book name (full name)|`Acts` `Colossians` `Ephesians` `Galatians`
[`chapter`](chapter.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|chapter number|`1` `2` `3` `4`
## section

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
## parsedtext

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
## sentence

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`nodeid`](nodeid.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|reference to the structure of a range of words in the dataset (e.g., phrase, subphrase)|`400010010010081` `400010020010181` `400010030020211` `400010040020151`
[`parent`](parent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|parent container {incorretly applied}|`Link`
## tree

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`parent`](parent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|parent container {incorretly applied}|`Link`
## verse

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`book`](book.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|book name (full name)|`Acts` `Colossians` `Ephesians` `Galatians`
[`chapter`](chapter.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|chapter number|`1` `2` `3` `4`
[`verse`](verse.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|verse number|`1` `2` `3` `5`
## clause

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`articular`](articular.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|1 if the syntactic unit contains an article|`1`
[`cltype`](cltype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`VerbalClause` `VerbElided` `Verbless` `Minor`
[`nodeid`](nodeid.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|reference to the structure of a range of words in the dataset (e.g., phrase, subphrase)|`400010010010081` `400010020010181` `400010030020211` `400010040020151`
[`parent`](parent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|parent container {incorretly applied}|`Link`
[`rule`](rule.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`ClCl` `Conj-CL` `V2CL` `CLaCL`
## phrase

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`articular`](articular.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|1 if the syntactic unit contains an article|`1`
[`nodeid`](nodeid.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|reference to the structure of a range of words in the dataset (e.g., phrase, subphrase)|`400010010010081` `400010020010181` `400010030020211` `400010040020151`
[`parent`](parent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|parent container {incorretly applied}|`Link`
[`phrasefunction`](phrasefunction.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`VerbalFunction` `AdverbialFunction` `SubjectFunction` `ObjectFunction`
[`rule`](rule.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`ClCl` `Conj-CL` `V2CL` `CLaCL`
[`type`](type.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`functionalphrase`
## subphrase

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`articular`](articular.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|1 if the syntactic unit contains an article|`1`
[`nodeid`](nodeid.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|reference to the structure of a range of words in the dataset (e.g., phrase, subphrase)|`400010010010081` `400010020010181` `400010030020211` `400010040020151`
[`parent`](parent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|parent container {incorretly applied}|`Link`
[`phrasefunction`](phrasefunction.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`VerbalFunction` `AdverbialFunction` `SubjectFunction` `ObjectFunction`
[`phrasetype`](phrasetype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`NP` `VP` `PP` `ADJP`
[`rule`](rule.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`ClCl` `Conj-CL` `V2CL` `CLaCL`
[`type`](type.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`functionalphrase`
## functionalword

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`adjectivetype`](adjectivetype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|semantic categories for adjectives (e.g, adjectives describing space ['the upper house']) {realized in limited fashion}|`NA` `Interrogative` `Common` `Proper`
[`adjuncttype`](adjuncttype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|semantic features of the phrase functions on word level (e.g., 'generations from Abraham to David': PP 'to David' as indirect object becomes 'GOAL')|`` `Relation` `Source` `Goal`
[`adverbtype`](adverbtype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|semantic features for adverbs|`NA` `Negative` `Emphatic` `Place`
[`after`](after.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|material after a word|` ` `, ` `. ` `· `
[`before`](before.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|material before a word|`[`
[`book`](book.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|book name (full name)|`Acts` `Colossians` `Ephesians` `Galatians`
[`book_short`](book_short.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|book name (abbreviated) from Emdros dataset|`1CO` `1JN` `1PE` `1TH`
[`case`](case.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical case|`nominative` `accusative` `genitive` `dative`
[`chapter`](chapter.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|chapter number|`1` `2` `3` `4`
[`cltype`](cltype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`VerbalClause` `VerbElided` `Verbless` `Minor`
[`conjunctiontype`](conjunctiontype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`NA` `Adverbial` `Logical`
[`criticalsign`](criticalsign.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|critical signs|`[]`
[`degree`](degree.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical degree|`comparative` `superlative`
[`frame`](frame.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|verbal frame|`A0` `A1` `A2` `AA2`
[`frame_translation_english`](frame_translation_english.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|English translation of verbal frame|`A0:Unspecified` `A0:Jesus` `A0:Paul` `A0:disciples`
[`framespec`](framespec.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|id word number of verbal frame|`A0:00000000000` `A1:00000000000` `A0:46003022002` `A0:47010001004`
[`functionalmorph`](functionalmorph.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|functional morphological tag according to Sandborg-Petersen morphology|`CONJ` `PREP` `ADV` `N-NSM`
[`gender`](gender.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical gender|`masculine` `feminine` `neuter`
[`id`](id.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|unique identifier for each word|`40001001001` `40001001002` `40001001003` `40001001004`
[`label`](label.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|label values that appear 'inconsistenly' and sporadically|`` `OC` `COMP` `IO`
[`lemma`](lemma.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma according to the Bible Dictionary of Ancient Greek (BDAG)|`ὁ` `καί` `αὐτός` `σύ`
[`lemma_BarclayNewman`](lemma_BarclayNewman.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma according to A Concise Greek-English Dictionary of the New Testament by Barclay M. Newman, Jr.|`ὁ` `καί` `αὐτός` `σύ`
[`lexdomain_LownNida`](lexdomain_LownNida.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|main section of Louw-Nida lexical semantic domain|`Discourse Referentials` `Relations` `Communication` `Names of Persons and Places`
[`lexdomain_LownNida_num`](lexdomain_LownNida_num.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|number of main section of Louw-Nida lexical semantic domain|`92` `89` `33` `93`
[`loanword`](loanword.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|word from Hebrew or Aramaic|`hebr` `aram`
[`monad_num`](monad_num.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|assigned number for each word in accordance with the canonical order|`1` `2` `3` `4`
[`mood`](mood.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|verbal mood|`indicative` `participle` `infinitive` `imperative`
[`morph`](morph.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|formal morphological tag according to Sandborg-Petersen morphology|`CONJ` `PREP` `ADV` `N-NSM`
[`morphology_ubs`](morphology_ubs.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|UBS morphological tag|`prep-i---------------` `conj-i-----------cbcp` `conj-i-----------cpc-` `advb-i---------------`
[`nodeid`](nodeid.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|reference to the structure of a range of words in the dataset (e.g., phrase, subphrase)|`400010010010081` `400010020010181` `400010030020211` `400010040020151`
[`normalized`](normalized.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|normalized text|`καί` `ὁ` `δέ` `ἐν`
[`notes`](notes.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|text notes|`Event (at own clause level)` `State (at own clause level)` `Direction (at own phrase level)` `Modal (at own clause level)`
[`nountype`](nountype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|noun categories|`NA` `Common` `Proper` `Place`
[`number`](number.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical number|`singular` `plural`
[`parent`](parent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|parent container {incorretly applied}|`Link`
[`particletype`](particletype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|types of particles|`NA` `Conditional` `Negative` `Emphatic`
[`person`](person.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical person|`p3` `p2` `p1`
[`prepositiontype`](prepositiontype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|types of preposition according to their semantic functions|`` `Located inside` `Directed into` `Directed out of`
[`pronountype`](pronountype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|types of pronouns|`NA` `Personal` `Demonstrative` `Relative`
[`punctuation`](punctuation.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|punctuation found after a word|`,` `.` `·` `;`
[`referent`](referent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|textual participant a word is referring to (excluding subject)|`Link`
[`referent_index`](referent_index.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|index number for textual participant a word is referring to (excluding subject)|`1` `2` `3` `4`
[`referent_lemma`](referent_lemma.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma of textual participant a word is referring to (excluding subject)|`Ἰησοῦς` `ἀδελφός` `Παῦλος` `μαθητής`
[`referent_strong`](referent_strong.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Strong's number of textual participant a word is referring to (excluding subject)|`2424` `80` `3972` `3101`
[`referent_translation_english`](referent_translation_english.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|English translation of textual participant a word is referring to (excluding subject)|`Jesus` `brothers` `Paul` `disciples`
[`referentspec`](referentspec.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|id word number of textual participant a word is referring to (excluding subject)|`40005001015` `46003022002` `43014023002` `45001001001`
[`refid`](refid.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|reference to the structure of a range of words in the dataset (e.g., phrase, subphrase) of the textual participant a word is referring to (excluding subject)|`04000100100002` `04000100100004` `04000100100006` `04000100100008`
[`rule`](rule.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`ClCl` `Conj-CL` `V2CL` `CLaCL`
[`section`](section.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|UBS5 title of textual section|`Stephen’s Speech` `The Crucifixion of Jesus` `Jesus Sentenced to Die` `The Feeding of the Five Thousand`
[`semantic_role_LownNida`](semantic_role_LownNida.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|semantic role by Lown-Nida lexical classification|`event` `goal` `state` `source`
[`semantic_role_embedded_LownNida`](semantic_role_embedded_LownNida.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|embedded semantic role by Lown-Nida lexical classification|`event` `state` `direction` `modal`
[`sp`](sp.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|part of speech|`subs` `verb` `art` `conj`
[`sp_functional`](sp_functional.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|functional part of speech|`adjv` `conj` `intj` `adv`
[`sp_ubs`](sp_ubs.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|part of speech (UBS5 version)|`verb` `subs` `art` `conj`
[`strong`](strong.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|Strong number|`3588` `2532` `846` `1161`
[`subjref`](subjref.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|textual subject a word is referring to|`Link`
[`subjref_lemma`](subjref_lemma.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma of subject referent|`Ἰησοῦς` `Παῦλος` `ἀδελφός` `μαθητής`
[`subjref_strong`](subjref_strong.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Strong's number of subject referent|`2424` `3972` `80` `3101`
[`subjref_translation_english`](subjref_translation_english.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|English translation of subject referent|`Jesus` `Paul` `disciples` `brothers`
[`subjrefspec`](subjrefspec.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|id word of textual subject a word is referring to|`46003022002` `66001009002` `45001001001` `47010001004`
[`substantive`](substantive.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|1 if word is substantive|`1`
[`tense`](tense.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|verbal tense|`aorist` `present` `imperfect` `future`
[`text`](text.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|word text|`καὶ` `ὁ` `ἐν` `δὲ`
[`trailer`](trailer.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|material after a word (excluding critical signs)|` ` `, ` `. ` `· `
[`translation_chinese`](translation_chinese.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Chinese translation of the word surface text|`他` `在` `和` `而`
[`translation_english`](translation_english.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|English translation of the word surface text|`the` `and` `-` ``
[`ubsprontype`](ubsprontype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|types of pronouns (UBS5 version)|`prs` `dem` `rel` `irg`
[`unicode`](unicode.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|surface text with Unicode presentation|`καὶ` `ὁ` `ἐν` `δὲ`
[`variant`](variant.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma variant|`2` `1`
[`verbtype`](verbtype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|verb type 'Place' applied only to 'δεῦρο' and 'δεῦτε'|`NA` `Place`
[`verse`](verse.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|verse number|`1` `2` `3` `5`
[`voice`](voice.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|verbal voice|`active` `passive` `middle` `middlepassive`
## word

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`adjectivetype`](adjectivetype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|semantic categories for adjectives (e.g, adjectives describing space ['the upper house']) {realized in limited fashion}|`NA` `Interrogative` `Common` `Proper`
[`adjuncttype`](adjuncttype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|semantic features of the phrase functions on word level (e.g., 'generations from Abraham to David': PP 'to David' as indirect object becomes 'GOAL')|`` `Relation` `Source` `Goal`
[`adverbtype`](adverbtype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|semantic features for adverbs|`NA` `Negative` `Emphatic` `Place`
[`after`](after.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|material after a word|` ` `, ` `. ` `· `
[`before`](before.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|material before a word|`[`
[`book`](book.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|book name (full name)|`Acts` `Colossians` `Ephesians` `Galatians`
[`book_short`](book_short.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|book name (abbreviated) from Emdros dataset|`1CO` `1JN` `1PE` `1TH`
[`case`](case.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical case|`nominative` `accusative` `genitive` `dative`
[`chapter`](chapter.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|chapter number|`1` `2` `3` `4`
[`cltype`](cltype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`VerbalClause` `VerbElided` `Verbless` `Minor`
[`conjunctiontype`](conjunctiontype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|No feature description|`NA` `Adverbial` `Logical`
[`criticalsign`](criticalsign.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|critical signs|`[]`
[`degree`](degree.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical degree|`comparative` `superlative`
[`frame`](frame.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|verbal frame|`A0` `A1` `A2` `AA2`
[`frame_translation_english`](frame_translation_english.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|English translation of verbal frame|`A0:Unspecified` `A0:Jesus` `A0:Paul` `A0:disciples`
[`framespec`](framespec.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|id word number of verbal frame|`A0:00000000000` `A1:00000000000` `A0:46003022002` `A0:47010001004`
[`functionalmorph`](functionalmorph.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|functional morphological tag according to Sandborg-Petersen morphology|`CONJ` `PREP` `ADV` `N-NSM`
[`gender`](gender.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical gender|`masculine` `feminine` `neuter`
[`id`](id.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|unique identifier for each word|`40001001001` `40001001002` `40001001003` `40001001004`
[`label`](label.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|label values that appear 'inconsistenly' and sporadically|`` `OC` `COMP` `IO`
[`lemma`](lemma.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma according to the Bible Dictionary of Ancient Greek (BDAG)|`ὁ` `καί` `αὐτός` `σύ`
[`lemma_BarclayNewman`](lemma_BarclayNewman.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma according to A Concise Greek-English Dictionary of the New Testament by Barclay M. Newman, Jr.|`ὁ` `καί` `αὐτός` `σύ`
[`lexdomain_LownNida`](lexdomain_LownNida.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|main section of Louw-Nida lexical semantic domain|`Discourse Referentials` `Relations` `Communication` `Names of Persons and Places`
[`lexdomain_LownNida_num`](lexdomain_LownNida_num.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|number of main section of Louw-Nida lexical semantic domain|`92` `89` `33` `93`
[`loanword`](loanword.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|word from Hebrew or Aramaic|`hebr` `aram`
[`monad_num`](monad_num.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|assigned number for each word in accordance with the canonical order|`1` `2` `3` `4`
[`mood`](mood.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|verbal mood|`indicative` `participle` `infinitive` `imperative`
[`morph`](morph.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|formal morphological tag according to Sandborg-Petersen morphology|`CONJ` `PREP` `ADV` `N-NSM`
[`morphology_ubs`](morphology_ubs.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|UBS morphological tag|`prep-i---------------` `conj-i-----------cbcp` `conj-i-----------cpc-` `advb-i---------------`
[`nodeid`](nodeid.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|reference to the structure of a range of words in the dataset (e.g., phrase, subphrase)|`400010010010081` `400010020010181` `400010030020211` `400010040020151`
[`normalized`](normalized.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|normalized text|`καί` `ὁ` `δέ` `ἐν`
[`notes`](notes.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|text notes|`Event (at own clause level)` `State (at own clause level)` `Direction (at own phrase level)` `Modal (at own clause level)`
[`nountype`](nountype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|noun categories|`NA` `Common` `Proper` `Place`
[`number`](number.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical number|`singular` `plural`
[`parent`](parent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|parent container {incorretly applied}|`Link`
[`particletype`](particletype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|types of particles|`NA` `Conditional` `Negative` `Emphatic`
[`person`](person.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|grammatical person|`p3` `p2` `p1`
[`prepositiontype`](prepositiontype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|types of preposition according to their semantic functions|`` `Located inside` `Directed into` `Directed out of`
[`pronountype`](pronountype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|types of pronouns|`NA` `Personal` `Demonstrative` `Relative`
[`punctuation`](punctuation.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|punctuation found after a word|`,` `.` `·` `;`
[`referent`](referent.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|textual participant a word is referring to (excluding subject)|`Link`
[`referent_index`](referent_index.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|index number for textual participant a word is referring to (excluding subject)|`1` `2` `3` `4`
[`referent_lemma`](referent_lemma.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma of textual participant a word is referring to (excluding subject)|`Ἰησοῦς` `ἀδελφός` `Παῦλος` `μαθητής`
[`referent_strong`](referent_strong.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Strong's number of textual participant a word is referring to (excluding subject)|`2424` `80` `3972` `3101`
[`referent_translation_english`](referent_translation_english.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|English translation of textual participant a word is referring to (excluding subject)|`Jesus` `brothers` `Paul` `disciples`
[`referentspec`](referentspec.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|id word number of textual participant a word is referring to (excluding subject)|`40005001015` `46003022002` `43014023002` `45001001001`
[`refid`](refid.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|reference to the structure of a range of words in the dataset (e.g., phrase, subphrase) of the textual participant a word is referring to (excluding subject)|`04000100100002` `04000100100004` `04000100100006` `04000100100008`
[`section`](section.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|UBS5 title of textual section|`Stephen’s Speech` `The Crucifixion of Jesus` `Jesus Sentenced to Die` `The Feeding of the Five Thousand`
[`semantic_role_LownNida`](semantic_role_LownNida.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|semantic role by Lown-Nida lexical classification|`event` `goal` `state` `source`
[`semantic_role_embedded_LownNida`](semantic_role_embedded_LownNida.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|embedded semantic role by Lown-Nida lexical classification|`event` `state` `direction` `modal`
[`sp`](sp.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|part of speech|`subs` `verb` `art` `conj`
[`sp_ubs`](sp_ubs.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|part of speech (UBS5 version)|`verb` `subs` `art` `conj`
[`strong`](strong.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|Strong number|`3588` `2532` `846` `1161`
[`subjref`](subjref.md#readme)|[`Edge`](featuresbytype.md#Edge)|[`String`](featuresbydatatype.md#String)|textual subject a word is referring to|`Link`
[`subjref_lemma`](subjref_lemma.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma of subject referent|`Ἰησοῦς` `Παῦλος` `ἀδελφός` `μαθητής`
[`subjref_strong`](subjref_strong.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Strong's number of subject referent|`2424` `3972` `80` `3101`
[`subjref_translation_english`](subjref_translation_english.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|English translation of subject referent|`Jesus` `Paul` `disciples` `brothers`
[`subjrefspec`](subjrefspec.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|id word of textual subject a word is referring to|`46003022002` `66001009002` `45001001001` `47010001004`
[`substantive`](substantive.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|1 if word is substantive|`1`
[`tense`](tense.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|verbal tense|`aorist` `present` `imperfect` `future`
[`text`](text.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|word text|`καὶ` `ὁ` `ἐν` `δὲ`
[`trailer`](trailer.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|material after a word (excluding critical signs)|` ` `, ` `. ` `· `
[`translation_chinese`](translation_chinese.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Chinese translation of the word surface text|`他` `在` `和` `而`
[`translation_english`](translation_english.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|English translation of the word surface text|`the` `and` `-` ``
[`ubsprontype`](ubsprontype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|types of pronouns (UBS5 version)|`prs` `dem` `rel` `irg`
[`unicode`](unicode.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|surface text with Unicode presentation|`καὶ` `ὁ` `ἐν` `δὲ`
[`variant`](variant.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lexical lemma variant|`2` `1`
[`verbtype`](verbtype.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|verb type 'Place' applied only to 'δεῦρο' and 'δεῦτε'|`NA` `Place`
[`verse`](verse.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|verse number|`1` `2` `3` `5`
[`voice`](voice.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|verbal voice|`active` `passive` `middle` `middlepassive`


Created on Nov. 24, 2025 using [Doc4TF version 0.5.2 (July 10, 2024)](https://github.com/tonyjurg/Doc4TF/blob/main/CreateFeatureDoc.ipynb)