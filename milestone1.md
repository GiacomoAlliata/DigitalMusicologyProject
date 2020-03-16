# Milestone 1 - Project Proposal

For our project, we want to study the structure of pop/rock songs and its evolution over time.
Specifically we want to characterize the different parts of a song (typically the verse and the chorus). 
The verse-chorus structure is fairly common in these types of popular music. We want to find out what makes a chorus distinct, why it is so easily able to catch our attention, to be recognized as the peak of the song. The time dimension is also important to us as we want to analyze pop and rock songs over a few decades and hopefully find an evolution in the song structure and different parts characteristics. To sum up, our final goal is to provide an evolutive caracterization of what distinguishes a chorus from other parts of a song, and maybe understand better what makes it so special in the way we perceive and interpret it.

In general, in rock and pop songs the structure relies mainly on verse and chorus, with the first serving to build the narrative and the latter being the focal point, as discussed in [1]. However other sections can be found, especially after 1960s with the democratization of the prechorus to build up momentum towards the chorus (whereas before it was mainly done in the small transition section after the verse). 

Of course there are some obvious answers to our question, such that a chorus is usually being repeated nearly identical several times in a piece or that other singing voices sometimes join the main one. However we believe there are also other differences more on a technical level such as chords distribution, the use of specific words (or grammatical categories) and a change in the rhythm.

In practice we will compare musical features and lyrics in the different parts of a song in order to find defining characteristics. 
The musical features we can analyze mainly depend on the data we have but we will mainly focus on chords. Lyrics will also be compared. 
To do so we will rely on statistics and distributions of these features on the different parts. 

In terms of dataset, a starting point could be the Rolling Stone corpus but a larger dataset such as https://www.ultimate-guitar.com/ 
could also be used. The RS corpus comprehends harmonic analyses, melodic transcriptions, stressed-syllables lyrics and timing data for 200 songs from the top songs of the 1950s to the 1990s. On the other hand, the guitar tabs dataset presents lyrics with corresponding chords as well as the tempo for more than 600000 songs (divided by sections such as chorus, verse...).

Lots of research have already been conducted on this domain to understand the structure of pop and rock songs. [2] describes the different common forms in rock songs and states that harmonic structures play a central role in their differentiation. Even though the verse-chorus form is only one of the many existing structures, it certainly is the most common one and thus it makes sense to focus on the verse-chorus differences. [3] for instance focus on the breakout chorus, a particular type that best embodies the idea to "rock out" at the chorus in rock songs. To do so, it contrants with the preceding verse by conveying an increase in intensity with regard to loudness, rhythmic and textural activity, timbral noise, lyrical content, and pitch level. This last element, called expressive modulation by the author can be considered a defining characteristic of this type of chorus. It is also important to consider the problem from a psychological point of view in order to take into account the inherent ambiguity in the segmentation of a song and the categorization of its different parts. Indeed, as [4] suggests, the individual perception of what constitutes more or less representative examples of each section type is due to individual listening histories and the complexity of both real world music and perceptual processes. Finally, [5] presents the segmentation of pop songs using a similarity matrix and correlating a kernel along its diagonal to find the the segment boundaries such as verse-chorus transitions. Then, by spectral analysis and clustering, each segment is categorized, showing there are indeed defining characteristics of the different sections, at least from a technical point of view.

### References
* [1]: "The Structure, Function, and Genesis of the Prechorus", Jay Summach https://mtosmt.org/issues/mto.11.17.3/mto.11.17.3.summach.pdf
* [2]: "Form in Rock Music", by John Covach http://www.personal.kent.edu/~sbirch/Theory/21341%20CMT/Form%20in%20Rock%20Music.pdf
* [3]: "Rockin’ Out: Expressive Modulation in Verse-Chorus Form", by Christopher Doll https://mtosmt.org/issues/mto.11.17.3/mto.11.17.3.doll.pdf
* [4]: "Embracing Ambiguity in the Analysis of Form in Pop/Rock Music, 1982–1991", by Trevor de Clercq
https://mtosmt.org/issues/mto.17.23.3/mto.17.23.3.de_clercq.pdf
* [5]: "Summarizing popular music via structural similarity analysis", by Matthew Cooper and Jonathan Foote https://www.researchgate.net/publication/4068537_Summarizing_popular_music_via_structural_similarity_analysis
* https://s3.amazonaws.com/academia.edu.documents/31853711/Biamonte_Fonctions_Modales.pdf?response-content-disposition=inline%3B%20filename%3DLes_fonctions_Modales_dans_le_Rock_et_la.pdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWOWYYGZ2Y53UL3A%2F20200315%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200315T220733Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=29ccb8fa2e60f6a1487e17776b7d561a728e83b8876e9281352b12ac8f9642b8 (french version, english also available)

