<!-- # NOTE AND PLAYING TECHNIQUE TRANSCRIPTION OF ELECTRIC GUITAR SOLOS IN REAL-WORLD MUSIC PERFORMANCE -->

This is the demo page for paper **NOTE AND PLAYING TECHNIQUE TRANSCRIPTION OF ELECTRIC GUITAR SOLOS IN REAL-WORLD MUSIC PERFORMAN**. 

## Abstract:
Transcribing electric guitar solo in real-world performance is challenging because of the interference of background accompaniments, the strong coupling between music pitch and playing technique, and the limited resource of data annotation. To address these issues, we first propose a new guitar solo dataset for this task. Then, we propose a transcription model which learns an output space jointly constructed with notes, playing techniques, and two sets of meta-class labels named note states and technique groups, such that the model can harness the layered relationship among different note-level event and playing technique classes.
The proposed model outperforms the state-of-the-art guitar solo transcription and note transcription models.

## Dataset
EG-Solo dataset, the first dataset which contains both note labels and technique labels for electric guitar solos with polyphonic backing tracks. EG-Solo contains 76 clips from some professional electric guitar solo demonstration videos available on YouTube. The total length is 40 minutes. These videos are electric guitar solos of popular rock songs with backing tracks. The pitches of the dataset are ranged from E2 to D6. The dataset includes nine classes of playing techniques, namely normal, slide, bend, vibrato (aka trill), mute, pull (aka pull- off), harmonic, hammer (aka hammer-on), and tap. Some are rare playing techniques not seen in any other guitar solo datasets, such as harmonic and tap, are also included. For potential works in the future, we also annotate phrase labels to indicate the timing from the beginning to the end of each phrase in a solo. The note and playing technique annotations are both recorded in MIDI track format. The distribution of note and playing technique annotations are presented in below table. 

|video name / counts | clips | phrases | notes | normal| slide| bend| trill| mute| pull| harmonic| hammer| tap |
|--|--|--|--|--|--|--|--|--|--|--|--|--|
|20 Classic Intermediate Level Solos | 20| 158| 2731| 1543| 111| 315| 157|  32| 345|  5| 179| 44|
|50 Easy Guitar Solos                | 50| 318| 3238| 2274| 201| 243| 262|  77| 100|  8|  73|  0|
|Guitar Gym                          | 6 |  50|  864|  270|  92|  12|  16| 185| 141| 11| 123| 14|
|Total                               | 76| 526| 6833| 4087| 404| 570| 435| 294| 586| 24| 375| 58| 



## Real-world music transcription 


## Contact
