Following datasets are found in the <b>datasets</b> folder.

---------

<b>Compositionality ratings for Estonian particle verbs (folder compositionality_ET_PV)</b>

<p align="justify">Compositionality ratings for Estonian particle verbs collected via Qualtrics. We collected judgements for 211 PVs asking 110 judges to evaluate <b>how much the meaning of a PV agrees with the meanings of its components</b>. We collected compositionality ratings via Qualtrics, only Estonian native speakers were asked to participate. Each annotator evaluated 21 PVs on a scale from 1 (not at all) to 5 (fully), with the 6th option <i>I don't know</i> included. Each PV was evaluated at least 10, maximum 20 times.</p>

54 PVs got at least once rating "I don't know". 

<p align="justify">File <b>211_comp_unit_ratings.csv</b> - ratings for 211 PVs (column 1: particle verb (adverb[space]verb), column 2-21: ratings);</p>

<p align="justify"><b>File 157_comp_unit_ratings.csv</b> - ratings for PVs that didn't get any "I don't know" rating (column 1: particle verb (adverb[space]verb), column 2-21: ratings);</p>

<p align="justify"><b>File 157_comp_unit_ratings_SD.csv</b> - ratings and standard deviation for PVs that didn't get any "I don't know" rating (column 1: particle verb (adverb[space]verb), column 2-21: ratings, column 22: value of standard deviation);</p>

<p align="justify"><b>File 157_comp_unit_ratings_avg_SD.csv</b> - ratings, average compositionality rate, number of rates, and standard deviation for PVs that didn't get any "I don't know" rating (column 1: particle verb (adverb[space]verb), column 2-21: ratings, column 22: average rating, column 23: number of ratings, column 24: value of standard deviation);</p>

---------

<b>Abstractness/concreteness ratings for Estonian words (folder abstractness_ET)</b>

File <b>abstractness_ET.csv</b> - abstractness/concreteness ratings for Estonian lemmas (column 1: WORD (indicates Estonian lemma), column 2: Rating expresses lemma's concreteness/abstractness score (higher score indicates higher concreteness), lemmas are sorted according to the score in descending order (concrete to abstract))

---------

<b>Literal/non-literal usage of Estonian particle verbs (folder literalness_ET_PV)</b>

File <b>literalness_ET_PV.csv</b> - dataset of literal/non-literal usage of Estonian particle verbs, containing 1490 sentences

Format: id;class;avg;sentence;particle;verb;all;objcase;objanimacy;objabs;subjcase;subjabs;nounsabs;subjanimacy;casegovernment

Explanation: 

id - number of the sentence (value: 1-1838)

class - usage (according to the average score by human annotators) (value: literal or non-literal)

avg - average literalness score by human annotators(value: numerical)

sentence - lemmatized sentence

particle - particle of the PV 

verb - verbal component of the PV 

all - abstractness score of all nouns in the sentence (value: numerical)

objcase - case of the object of the PV in the sentence (value: nom (nominative) OR gen (genitive) OR part (partitive) OR noobj (no object in the sentence))

objanimacy - animacy of the object (value: yes - object is alive OR no - object is not alive OR 0 - no object)

objabs - abstrcatness score of the object of the PV (value: numerical)

subjcase - case of the subject of the PV (value: nom (nominative) OR gen (genitive) OR part (partitive) OR nosubj (no subject in the sentence))

subjabs - abstractness score of the subject (value: numerical)

nounsabs - average abstractness score of all nouns in the sentence (value: numerical)

subjanimacy - animacy of the subject (value: yes - subject is alive OR no - subject is not alive OR 0 - no subject)

casegovernment - case of the argument of the verb (value: nom (nominative) OR gen (genitive) OR part (partitive) OR el (elative) OR all (allative) OR ill (illative) OR tr (translative) OR adt (short illative) OR kom (comitative) OR in (inessive) OR abl (ablative) OR ad (adessive) OR es (essive) OR 0 (no government))

File <b>1481_literalness_ET_PV.csv</b> - dataset of literal/non-literal usage of Estonian particle verbs, contains 1481 sentences
Format: id;class;avg;sentence;particle;verb;unigrams;all;nounsabs;subjabs;objabs;subjcase;objcase;objanimacy;subjanimacy;casegovernment;advfreq;vfreq;pvfreq

Explanation: 

id - number of the sentence (value: 1-1838)

class - usage (according to the average score by human annotators) (value: literal or non-literal)

avg - average literalness score by human annotators(value: numerical)

sentence - lemmatized sentence

particle - particle of the PV 

verb - verbal component of the PV 

unigrams - binary classification of sentences based on the unigrams feature (taking account words that appear at least 6 times)

all - abstractness score of all nouns in the sentence (value: numerical)

nounsabs - average abstractness score of all nouns in the sentence (value: numerical)

subjabs - abstractness score of the subject (value: numerical)

objabs - abstrcatness score of the object of the PV (value: numerical)

subjcase - case of the subject of the PV (value: nom (nominative) OR gen (genitive) OR part (partitive) OR nosubj (no subject in the sentence))

objcase - case of the object of the PV in the sentence (value: nom (nominative) OR gen (genitive) OR part (partitive) OR noobj (no object in the sentence))

subjanimacy - animacy of the subject (value: yes - subject is alive OR no - subject is not alive OR 0 - no subject)

objanimacy - animacy of the object (value: yes - object is alive OR no - object is not alive OR 0 - no object)

casegovernment - case of the argument of the verb (value: nom (nominative) OR gen (genitive) OR part (partitive) OR el (elative) OR all (allative) OR ill (illative) OR tr (translative) OR adt (short illative) OR kom (comitative) OR in (inessive) OR abl (ablative) OR ad (adessive) OR es (essive) OR 0 (no government))

advfreq - frequency of the adverb (particle) in the corpus

vfreq - frequency of the verb in the corpus

pvfreq - cooccurrence frequency of the adverb and verb in the corpus



 




