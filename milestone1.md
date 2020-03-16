# Milestone 1 - Project Proposal

For our project, we want to study the structure of pop/rock songs and its evolution over time.
Specifically we want to characterize the different parts of a song (typically the verse and the chorus). 
The verse-chorus structure is fairly common in these types of popular music and we want to find out what differentiates them 
and make it fairly easy to recognize a chorus when you hear it. The time dimension is also important to us as we want to analyze 
pop and rock songs over a few decades and hopefully find an evolution in the song structure and different parts characteristics. In general, in rock and pop songs the structure relies mainly on verse and chorus, with the first serving to build the narrative and the latter being the focal point, as discussed in [1]. Howeover other sections can be found, especially after 1960s with the democratization of the prechorus to build up momentum towards the chorus (whereas before it was mainly done in the small transition section after the verse). 

Of course there are some obvious answers here such as a chorus usually being repeated nearly identical several times in a piece or 
having other singing voices joining the main one. However we believe there are also other differences more on a technical level 
such as chords distribution, the use of specific words (or grammatical categories) and a change in the rhythm.

In practice we will compare musical features and lyrics in the different parts of a song in order to find defining characteristics. 
The musical features we can analyze mainly depend on the data we have but we will mainly focus on chords. Lyrics will also be compared. 
To do so we will rely on statistics and distributions of these features on the different parts. 

In terms of dataset, a starting point could be the Rolling Stone corpus but a larger dataset such as https://www.ultimate-guitar.com/ 
could also be used. The RS corpus comprehends harmonic analyses, melodic transcriptions, stressed-syllables lyrics and timing data for 200 songs from the top songs of the 1950s to the 1990s. On the other hand, the guitar tabs dataset presents lyrics with corresponding chords as well as the tempo for more than 600000 songs (divided by sections such as chorus, verse...).

The state-of-the-art in this domain is

### References
* [1]: https://mtosmt.org/issues/mto.11.17.3/mto.11.17.3.summach.pdf
    * evolution of verse-chorus form in pop/rock music from strophic forms to four-part formal disposition
    * focus on prechorus, new section that appears in the 1960s
    * chorus is focal point, verses build up narrative, prechorus goal is to gain momentum towards the chorus (without, momentum is only gained during transition)
* [2]: https://mtosmt.org/issues/mto.11.17.3/mto.11.17.3.doll.pdf
    * expressive modulation in rock music (full-scale change of tonal center from minor tonic to its relative major)
    * focus on breakout chorus (contrasts with its preceding verse by conveying an increase in intensity with regard to loudness,     rhythmic and textural activity, timbral noise, lyrical content, and/or pitch level)
    * shared expectation to "rock out" at the chorus in rock music

* [3]: https://mtosmt.org/issues/mto.17.23.3/mto.17.23.3.de_clercq.pdf
    * central concern for theories of form in pop/rock music is the division of songs into sections and their categorizations
    * this process is often ambiguous because it depends on many factors and sections can have blending roles
    * discuss 3 types of ambiguity, each based on the main section role involved (verse, chorus or bridge)
    * individual perception of what constitutes more or less representatives examples of each section type due to individual listening history & complexity of both real world music and perceptual process
* [4]: http://www.personal.kent.edu/~sbirch/Theory/21341%20CMT/Form%20in%20Rock%20Music.pdf
   * Description of different common forms of rock songs
   * Harmonic structures play a central role in the differentiation of units of a song
   * The verse-chorus form is only one among other various forms
* [5]: https://s3.amazonaws.com/academia.edu.documents/31853711/Biamonte_Fonctions_Modales.pdf?response-content-disposition=inline%3B%20filename%3DLes_fonctions_Modales_dans_le_Rock_et_la.pdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWOWYYGZ2Y53UL3A%2F20200315%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200315T220733Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=29ccb8fa2e60f6a1487e17776b7d561a728e83b8876e9281352b12ac8f9642b8 (french version, english also available)
   * Some specific non-digital modal analysis of rock songs
* [6]: https://www.researchgate.net/publication/4068537_Summarizing_popular_music_via_structural_similarity_analysis
   * Segmentation of pop songs
