# Mandarin-Neighborhood-Statistics
Database of Mandarin neighborhood statistics 

***This database is no longer being maintained. For the updated version of this database please see the github files https://github.com/karlneergaard/Database_of_word-level_statistics, or go to the website http://dowls.site/, where you can access lexical information on Mandarin phonology through an convenient interface.

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
presented in "Key". The phonological words are in sampa. For translations of IPA and their 
corresponding sampa and pinyin, go below the column name definitions.

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

_____________________________________________
IPA to sampa conversion chart with examples

IPA -> Sampa -> Pinyin -> Sampa -> Character

a -> a -> ba3 -> pa3 -> 把

ə -> @ -> she4 -> S@4 -> 蛇

e -> e -> gei3 -> keI3 -> 给

ɛ -> E -> ye3 -> iE3 -> 也

ɨ -> 1 -> zhi1 -> Z11 -> 之

i -> i -> di4 -> ti4 -> 第

ɪ -> I -> sui4 -> sueI4 -> 岁

o -> o -> ruo4 -> ruo4 -> 若

ʊ -> U -> chou3 -> CoU3 -> 丑

u -> u -> wo3 -> uo3 -> 我

y -> y -> yuan2 -> yEn2 -> 元

m -> m -> ma1 -> ma1 -> 妈

n -> n -> neng2 -> n@N2 -> 能

ŋ -> N -> xiang3 -> XiaN3 -> 想

l -> l -> lie4 -> liE4 -> 列

r -> r -> rang4 -> raN4 -> 让

p -> p -> bu4 -> pu4 -> 不

pʰ -> P -> pao3 -> PaU3 -> 跑

k -> k -> ge0 -> k@0 -> 个

kʰ -> K -> ke4 -> K@4 -> 课

t -> t -> dou1 -> toU1 -> 都

tʰ -> T -> ta1 -> Ta1 -> 他

s -> s -> suo3 -> suo3 -> 所

f -> f -> fang4 -> faN4 -> 放

x -> x -> hui4 -> xueI4 -> 会

ʂ -> S -> shi4 -> S14 -> 是

ɕ -> X -> xia4 -> Xia4 -> 下

tɕ -> J -> jiu4 -> JioU4 -> 就

tɕʰ -> Q -> qing3 -> QiN3 -> 请

tsʰ -> c -> cong2 -> coN2 -> 从

tʂʰ -> C -> chu1 -> Cu1 -> 出

ts -> z -> zi4 -> z14 -> 字

tʂ -> Z -> zhe -> Z@4 -> 这
