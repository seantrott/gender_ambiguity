# Grammatical gender and homophony

## Project Goal

The goal of this project was to determine whether the grammatical gender of homophonous meanings acts as a disambiguating cue––when controlling for phonological factors. This follows up on [past work](https://www.sciencedirect.com/science/article/pii/S0010028518300136?casa_token=8wetuCRO0XIAAAAA:u3HrELjx9aOZJE8Z4ANFPiEXyjnvTRteDXkxP4SqTc0EyxiKPcu34Z1TKyjC85s_3_Yl7j2S_Z2L) suggesting that homophonous meanings are, if anything, *more likely* to belong to the same grammatical gender. The current work attempts to control for the probability of a given wordform being assigned a particular gender based on its phonological characteristics, as outlined [here](https://seantrott.github.io/spanish_homophones/).  

## Collaborators

- [Sean Trott](https://seantrott.github.io/)  
- [Tiago Pimentel](https://tpimentelms.github.io/)  
- [Benjamin Bergen](https://pages.ucsd.edu/~bkbergen/)

## Data

Each raw data file contains (at least) several key columns:

- `gender`: the grammatical gender of this lemma, according to the phonological resource (either **CELEX** or **Lexique**).  
- `orthography`: how the lemma is written.  
- `phonology`: a phonological transcription of the lemma; for Dutch and German, this uses the **PhonDISC** transcription.  
- `Class`: part-of-speech of this lemma.  

