# cpiabotData
The CPIAbot glossary is a collection of simplified terms and definitions of high-frequency words that can be consulted through the CPIAbot chatbot.
The idea of developing a simplified interactive glossary, aimed at learners with poor language skills in Italian, stems from the lack of similar resources open-source or available online free of charge.

# Target
The reference target group of the glossary is made up of learners of Italian as L2, illiterated or low-educated adult immigrants.

The reference syllable 

Borri, A., Minuz, F., Rocca, L. & Sola, C. (2014). Italiano L2 in contesti migratori. Sillabo e descrittori dall’alfabetizzazione all’A1. Torino, IT: Loecher.

identifies 4 profiles/stages for adults with low skills in Italian L2:

+ PreAlphaA1 (pre-alphabetized)
+ AlphaA1(illiterate)
+ PreA1(weakly literate)
+ A1(literate)


 
# Glosses list
The list of words contained in the glossary has been extracted from the syllable of reference for weakly or not at all schooled adult learners cited before

Specifically, the words of the domains have been extracted:

"La mia vita in Italia: le cose che compro" (My life in Italy: the things I buy)
"Io e il lavoro" (Me and the Job)

You can view the list of words within the Tables:

TSB3.4
TSB3.5

of the reference syllable

The tables enclose the high-frequency words used by <A1/A1 level learners

The words are organized in the tables according to the 4 profiles /stages provided by the syllable



# Data structure
The glossary is a .JSON file where each NAME corresponds to a gloss and each gloss's VALUE is an object itself.

Evry value has the same properties, that correspond to the gloss metadata.

Here an example for the gloss "casalinga"

  "casalinga": {
    category: lavoro,
    text: Donna. Lavora solo in casa,
    grammar: ca-sa-lin-ga. Sostantivo. Singolare femminile di CASALINGO,
    inflections: {
      singularMasculine: casalingo,
      singularFeminine: casalinga,
      pluralMasculine: casalinghi,
      pluralFeminine: casalinghe
    },
    examples: [
      Faccio la casalinga,
      Che lavoro fai? Faccio la casalinga
    ],
    image: casalinga.jpg,
    group: professioni,
    simplified: false,
    level: Pre-A1
  },
  
Here you can find a brief description for each property:
  
  - category: indicates the domain to which each gloss belongs, according to the categorisation adopted in the reference syllabus
  - text: contains a simplified definition of the gloss
  - grammar: describes the grammatical attributes of the gloss (Division into syllables, Part of Speech, number and gender + corresponding to the masculine singular)
  - inflections : inflecions of the gloss (singular masculine, singular feminine, plural masculine, plural feminine)
  - examples: short sentences presenting the gloss in a meaningful context
  - image: pointer to the file (if any) contained in the image database
  - video: pointer to the file (if any) contained in the video database
  - gif: pointer to the file (if any) contained in the gif database
  - group: indicates the semantic field to which the gloss belongs indicates the semantic field to which the gloss belongs (classification formalised by the glossary contributors)
  - simplified: Boolean value indicating whether the simplified definition (text) was crowdsourced by teachers (true) or not (false).
  - level: Indicates at which of the four stages, indicated by the signing syllabus, the student is expected to learn the gloss term. 
  
  
# Notes
The glossary has been designed and implemented as an integrated resource in the CPIAbot chatbot.
Within the system, the glossary has a dual function:

multimedia resource that can be consulted by illiterate/weakly literate students
database for exercises and dialogues contained in CPIAbot

The original objective of the glossary, therefore, was to build a support resource for the teaching of Italian L2 focused on:

Learning units oriented to target words
Expansion of lexical knowledge (also in relation to its relationship with the learning of reading and writing)
Use of textual and para-textual elements
Use of materials anchored to the student's personal experience

The data base shared here, therefore, is an integral part of the experimental attempt to build interactive (and conversational) tools to support L2 literacy courses for adults with little or no schooling.



# CPIAbot official page
https://www.itd.cnr.it/Progetti_Rispo1.php?PROGETTO=1193


# Academic papers 

Torsani S., Robino G., Ravicchio F. (2021). A conversational agent to learn Italian as a Second Language. Invited chapter for the book “CPIAbot: a conversational assistant for learning Italian as second language”, Trentin G. (ed), Nova Science Publishers,  2021.

Ravicchio F., Robino R., Torsani S. (2020). Un assistente conversazionale a supporto dell’apprendimento dell’italiano L2 per migranti: CPIAbot. Italian Journal of Educational Technology (IJET).

Robino G., Torsani S., Ravicchio F. (2020). Conversational agent in Mobile Assisted Language Learning: CPIAbot. Submitted 05.08.2020 to eLmL 2020 conference, 21-25.11.2020, Valencia.

Ravicchio F., Robino G., Trentin G, Bernava L. (2019). CPIAbot: un chatbot nell’insegnamento dell’Italiano L2 per stranieri. Atti di Didamatica 2019, Best Paper Award in section: BYOD. Mobile e Mixed Learning (ISBN 978-88-98091-50-8 p. 77-86).

Robino, G., Torsani, S., Ravicchio, F. (2020, November 21-25). Conversational agent in Mobile Assisted Language Learning: CPIAbot [Conference session]. eLmL 2020: The Twelfth International Conference on Mobile, Hybrid, and On-line Learning, Valencia, Spain. http://bit.ly/elml20cpiabotpresentation

Trentin, G. Robino, G., Ravicchio, F.(2019, November 15). CPIAbot: a conversational assistant supporting Italian L2 learning for immigrants [Conference session]. C1A0 EXPO – Artificial Intelligence for a Changing Planet. Genoa, Italy. http://bit.ly/itdcnr-c1a0-slides

Ravicchio F., Robino G., Bernava L., Torsani S. (2019, September 21-25). Chatbot e italiano L2. Chatbot e italiano L2 CPIAbot -Un agente automatico per il Pre-A1/A1 [Conference session], Quarto Convegno Internazionale di Linguistica e Glottodidattica Italiana (CILGI). Campobasso, Italy. http://bit.ly/cilgi4cpiabotpresentation

Robino, G. (2018, October 24) Conversational Paradigm. Much more than chatbots [ITD-CNR, internal talk]. Genoa, Italy. www.bit.ly/introforitd
  




