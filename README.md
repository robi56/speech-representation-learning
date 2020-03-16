# speech-representation-learning



## Dataset [Speech recognition/ Speaker Recognition] 

1. UIDs is collected from anonymized voice search queries. Table 4 lists statistics for the utterances, the durations of which
mostly range from 3 to 5 seconds. The full training partition, Train250k, comprises 249,312 speakers, 12,202,181 utterances, and more than 12,600 hours of speech. The subset Train50k
comprises 46,835 speakers, 2,236,379 utterances, and more than 2,270 hours of speech. The evaluation partition, Eva200, consists of 200 speakers that do not overlap with the training speakers. 380,000 speaker recognition trials were run. [Deep Speaker: an End-to-End Neural Speaker Embedding System]

2. XiaoDu contains Baidu wake-word utterances, “Xiaodu, xiaodu”. The full training dataset comprises 11,558 speakers, 89,227 utterances, and more than 38 hours of speech. The evaluation dataset consists of 844 speakers that do not overlap with the training speakers. 1,001,400 speaker recognition trials were run.  [Deep Speaker: an End-to-End Neural Speaker Embedding System]

3. MTurk contains scripted English utterances collected on Amazon Mechanical Turk. The median utterance length is around 4 seconds, and the 25th and 75th percentile lengths are ∼3 seconds and ∼5 seconds. The full training dataset comprises 2,174 speakers, 543,840 utterances, and more than 620 hours of speech. The evaluation dataset consists of 200 speakers that do
not overlap with the training speakers. 400,000 speaker recognition trials were run.  [Deep Speaker: an End-to-End Neural Speaker Embedding System]

3. VoxForge dataset. VoxForge is an open speech dataset that was set up to collect transcribed speech for use with Free and  Open Source Speech Recognition Engines (on Linux, Windows and Mac).[http://www.voxforge.org/] [Deep Speech 2: End-to-End Speech Recognition in English and Mandarin]

4.  Wall Street Journal (WSJ) corpus. The speech database described in this document is the UK English equivalent of a subset of the US American English WSJ0 database The WSJ0 corpus and associated wordlists and language models are available from the Linguistic Data Consortium, 441 Williams Hall, University of Pennsylvania, Philadelphia, PA 19104-6305, USA. Phone: +1 (215) 898-0464, Fax: +1 (215) 573-2175, e-mail: ldc@unagi.cis.upenn.edu. The name of the UK English version, WSJCAM0, represents the Wall Street Journal recorded at the University of CAMbridge (phase 0). It consists of speaker-independent (SI) read material, split into training, development test and evaluation test sets. There are 90 utterances from each of 92 speakers that are designated as training material for speech recognition algorithms. A further 48 speakers each read 40 sentences utterances containing only words from a fixed 5,000 word vocabulary of 40 sentences from the 64,000 word vocabulary, which will be used as testing material. Each of the total of 140 speakers also recorded a common set of 18 adaptation sentences. Recordings were made from two microphones: a far-field desk microphone and a head-mounted close-talking microphone. [https://catalog.ldc.upenn.edu/docs/LDC95S24/wsjcam0.html] [Deep Speech 2: End-to-End Speech Recognition in English and Mandarin]

5. Switchboard dataset . The Switchboard-1 Telephone Speech Corpus (LDC97S62) consists of approximately 260 hours of speech and was originally collected by Texas Instruments in 1990-1, under DARPA sponsorship. The first release of the corpus was published by NIST and distributed by the LDC in 1992-3. Since that release, a number of corrections have been made to the data files as presented on the original CD-ROM set and all copies of the first pressing have been distributed.

Switchboard is a collection of about 2,400 two-sided telephone conversations among 543 speakers (302 male, 241 female) from all areas of the United States. A computer-driven robot operator system handled the calls, giving the caller appropriate recorded prompts, selecting and dialing another person (the callee) to take part in a conversation, introducing a topic for discussion and recording the speech from the two subjects into separate channels until the conversation was finished. About 70 topics were provided, of which about 50 were used frequently. Selection of topics and callees was constrained so that: (1) no two speakers would converse together more than once and (2) no one spoke more than once on a given topic. [https://catalog.ldc.upenn.edu/LDC97S62] [Deep Speech 2: End-to-End Speech Recognition in English and Mandarin]

6. Fisher English Training Speech dataset. Fisher English Training Speech Part 1 Transcripts represents the first half of a collection of conversational telephone speech (CTS) that was created at LDC in 2003. It contains time-aligned transcript data for 5,850 complete conversations, each lasting up to 10 minutes. In addition to the transcriptions, which are found under the trans directory, there is a complete set of tables describing the speakers, the properties of the telephone calls, and the set of topics that were used to initiate the conversations. The corresponding speech files are contained in Fisher English Training Speech Part 1 Speech (LDC2004S13). [https://catalog.ldc.upenn.edu/LDC2004T19] [Deep Speech 2: End-to-End Speech Recognition in English and Mandarin]

7. LibriSpeech ASR corpus. Large-scale (1000 hours) corpus of read English speech. [http://www.openslr.org/12/] [Deep Speech 2: End-to-End Speech Recognition in English and Mandarin]

8. The Spoken Wikipedia Corpora. The SWC is a corpus of aligned Spoken Wikipedia articles from the English, German, and Dutch Wikipedia. This corpus has several outstanding characteristics:
hundreds of hours of aligned audio
from a diverse set of readers
about a diverse set of topics
in a well-researched textual genre
licensed under a free license (CC BY-SA 4.0)
Annotations can be mapped back to the original html
phoneme-level alignments

[https://nats.gitlab.io/swc/] [German End-to-end Speech Recognition based on DeepSpeech]

9. yt-vad-1k dataset.  ‘yt-vad-1k’ comprising 1000 hours of transcribed
recordings made by thousands of people in various recording conditions and with varying degree of
background noise. We proposed a method to improve the quality of data by automatically removing
the samples that contain cutting errors. The cleaning method was tested and allowed to obtain two
more datasets: ‘voxforge-ru-clean’ и ‘yt-vad-650-clean’. [BUILDING CORPORA OF TRANSCRIBED SPEECH FROM OPEN ACCESS SOURCES] [German End-to-end Speech Recognition based on DeepSpeech]

10. TIMIT dataset. The TIMIT corpus of read speech is designed to provide speech data for acoustic-phonetic studies and for the development and evaluation of automatic speech recognition systems. TIMIT contains broadband recordings of 630 speakers of eight major dialects of American English, each reading ten phonetically rich sentences. The TIMIT corpus includes time-aligned orthographic, phonetic and word transcriptions as well as a 16-bit, 16kHz speech waveform file for each utterance. Corpus design was a joint effort among the Massachusetts Institute of Technology (MIT), SRI International (SRI) and Texas Instruments, Inc. (TI). The speech was recorded at TI, transcribed at MIT and verified and prepared for CD-ROM production by the National Institute of Standards and Technology (NIST). [https://catalog.ldc.upenn.edu/LDC93S1] [EXPLORING SPECTRO-TEMPORAL FEATURES IN END-TO-END CONVOLUTIONAL NEURAL NETWORKS]

11. VoxCeleb2 dataset. VoxCeleb2 contains over 1 million utterances for 6,112 celebrities, extracted from videos uploaded to YouTube. The development set of VoxCeleb2 has no overlap with the identities in the VoxCeleb1 or SITW datasets.
of speakers	5,994	118
of videos	145,569	4,911
of utterances	1,092,009	36,237 

[http://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html] [UTTERANCE-LEVEL AGGREGATION FOR SPEAKER RECOGNITION IN THE WILD]

12. The NIST meeting room pilot corpus.  NIST has collected a pilot corpus of 15 hours of meetings in its specially-instrumented Meeting Data Collection Laboratory. The corpus includes digital recordings from close-talking mics, lapel mics, distantly-placed mics, 5 digitally-recorded camera views, and full speaker/word-level transcripts. This data is being used in the development and evaluation of speech technologies and by the video extraction community under the auspices of the ARDA Video Analysis and Content Exploitation (VACE) program. [The NIST Meeting Room Pilot Corpus][https://www.researchgate.net/publication/228870067_The_NIST_meeting_room_pilot_corpus]

13. The VoxCeleb1 Dataset. VoxCeleb1 contains over 100,000 utterances for 1,251 celebrities, extracted from videos uploaded to YouTube. [http://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html]

14. ETAPE TV subset, The ETAPE TV subset contains 29 hours of TV broadcast (18h for training, 5.5h for development and 5.5h for test) from three French TV channels with news, debates, and en- tertainment [http://www.lrec-conf.org/proceedings/lrec2012/pdf/495_Paper.pdf][TRISTOUNET: TRIPLET LOSS FOR SPEAKER TURN EMBEDDING Herv´e Bredin
LIMSI, CNRS, Universit´e Paris-Saclay arXiv:1609.04301v3]



## Dataset [Music Recommendation]

 





