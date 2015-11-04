# Mandarin-Neighborhood-Statistics
Database of Mandarin neighborhood statistics 

This database provides statistics for words and nonwords of Mandarin, Chinese. Lexical statistics include subtitle corpus frequency, phonological neighborhood density, neighborhood frequency, and homophone density. The accompanying word descriptors include pinyin, ascii phonetic transcription, tone, syllable structure, dominant PoS, and syllable, segment and pinyin lengths for each word. It is designed for researchers particularly concerned with language processing of isolated words. The database is divided into multiple files according to the desired search criteria: 1) the syllable segmentation schema used to calculate density measures, and 2) whether the search is for words or nonwords.

The database is made of 28 files, organized according to words with tone, words without tone,
nonwords with tone, and nonwords without tone.
Words with tone files: C_V_C_T, C_V_V_X_T, C_V_VX_T, C_VVX_T, CV_V_X_T, CV_VX_T, CVVX_T
Words without tone files: C_V_C, C_V_V_X, C_V_VX, C_VVX, CV_V_X, CV_VX, CVVX
Nonwords with tone files: Same as words with tone plus "nonword_"
Nonwords without tone files: Same as words without tone plus "nonword_"

The contents of each file are structured by columns with the titles defined below:

Key: The database was made according to phonological words. Therefore, in each file the "Key" 
column features the phonological words from which all phonologically related manipulations 
were made. Thus, each of the following column titles are in reference to the phonological word 
presented in "Key". The phonological words are in sampa. See the Dictionary.txt for help in 
translating Sampa-IPA-Pinyin. 

PY+T: Pinyin plus tone

Pho+T: Phonological word plus tone

PY-T: Pinyin minus tone

Pho-T: Phonological word minus tone

Tone: Tone number

SyStruct: Syllable structure according to the CVVX system

SyLen: Syllable length

OrthLen: Orthographic length here refers to the number of pinyin characters per each word

PhoLen: Phonological length

FreqPM: Frequency per million adapted from Cai & Brysbaert (2010)

Words: Simplified Chinese character/s that correspond to the phonological word presented 
in "Key"

HomoDensity: Homophone density

Dominate-POS: Dominant part of speech (POS)

Freq-Dominate-POS: Frequency of the dominant POS

Percent-Dominate-POS: The percent that the Dominate-POS represents "Key" in comparison to 
other POS assignments for the same "Key"

Other-POSes: The other parts of speech assignments that were not of the highest percentage

Num-Neighbors: The total number of phonological neighbors after calculating the 
replacement, addition, and substitution of a single phonological unit

R-Neighbors: Number of replacement neighbors

A-Neighbors: Number of addition neighbors

S-Neighbors: Number of substitution neighbors

Neighbors: All phonological neighbors presented in sampa

Freq-Neighbors: The summed raw frequency of all of the phonological neighbors
