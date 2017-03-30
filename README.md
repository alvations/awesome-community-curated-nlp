# Awesome Community-Curated NLP List


**To contribute**: This list is community curated, anyone can do a pull-request to add to the list. And it will be merged once 5 person have verified that the PR is not spam. 



Speech NLP
====

 - Automatic Speech Recognition (Speech-to-Text)
   - [Kaldi](http://kaldi-asr.org)
   - [CMU Sphinx](http://cmusphinx.sourceforge.net)
   - [Julius](http://julius.osdn.jp/en_index.php)
   - [RWTH ASR](http://www-i6.informatik.rwth-aachen.de/rwth-asr/)
 
 - Speech Synthesis (Text-to-Speech)
   - [Merlin](http://www.cstr.ed.ac.uk/projects/merlin/)
   - [Festival](http://www.cstr.ed.ac.uk/projects/festival/)
   - [HTS](http://hts.sp.nitech.ac.jp)
   - [eSpeak](http://espeak.sourceforge.net)
   - [Covarep](https://github.com/covarep/covarep)
   - [Free TTS](http://freetts.sourceforge.net/docs/index.php)
   - [Ekho](https://sites.google.com/site/readtextextension/home/announcements/ekho)

 - Generic Speech Analysis/Modelling Tools
   - [Hidden Markov Model Toolkit](http://htk.eng.cam.ac.uk)
   - [Praat](http://www.fon.hum.uva.nl/praat/)
 
 - List of Lists of Speech tools
   - https://en.wikipedia.org/wiki/Comparison_of_speech_synthesizers 
   - https://en.wikipedia.org/wiki/List_of_speech_recognition_software 
 

Text NLP Suites
====

 - [NLTK](https://github.com/nltk/nltk)
 - [Gensim](https://radimrehurek.com/gensim/)
 - [SpaCy](https://spacy.io)
 - [Stanford CoreNLP](http://stanfordnlp.github.io/CoreNLP/)
 - [Freeling](http://nlp.cs.upc.edu/freeling/)
 - [OpenNLP](https://opennlp.apache.org)
 - [DKPro](https://dkpro.github.io/dkpro-core/)
 - [PyNLPl](https://github.com/proycon/pynlpl/)
 - [IXA Pipes](http://ixa2.si.ehu.es/ixa-pipes/)
 - [NLP4J](https://emorynlp.github.io/nlp4j/)
 - [CogComp's NLP libraries](https://github.com/CogComp/cogcomp-nlp)
 - [Stanbol NLP](https://stanbol.apache.org/docs/trunk/components/enhancer/nlp/)
 - [LIMA](http://aymara.github.io/lima/)
 - [Corpus.Tools](http://corpus.tools)
 - [NooJ](http://www.nooj4nlp.net)
 - [SALAT](http://www.kristopherkyle.com/tools.html)


Language Specific Text NLP Suites
====

 - Arabic
   - [SAFAR](http://arabic.emi.ac.ma/safar/): Software Architecture For Arabic language pRocessing
   
 - Chinese
   - [SnowNLP](https://github.com/isnowfy/snownlp): Simplified Chinese Text Processing
   
 - Persian
   - [Hazm](https://github.com/sobhe/hazm): Python library for digesting Persian text.
 
 - Dutch
   - [Frog](https://languagemachines.github.io/frog): An advanced NLP suite for Dutch
   
 - Italian
   - [Tint](http://tint.fbk.eu): Lend color to your Italian texts!
 
 - Korean
   - [KoNLPy](http://konlpy.org): Korean NLP in Python

Pre-processing (Tokenization / Stemming / POS Tagging / etc.)
====

 - Ngrams
   - [Colibri Core](https://proycon.github.io/colibri-core) - C++ and Python tools for n-grams and skipgrams
 
 
 - Stemming
   - [Snowball Stemmers](http://snowball.tartarus.org)
   - [SerbianStemmer](https://github.com/nikolamilosevic86/SerbianStemmer)
   - [Whoosh Stemmers](https://bitbucket.org/mchaput/whoosh/wiki/Home)
   
 - Tokenizers
   - [Elephant](http://gmb.let.rug.nl/elephant/about.php): Sequence labeling for word and sentence segmentation
   - [Toktok](https://github.com/jonsafari/tok-tok): A fast, simple, multilingual tokenizer
   - [Ucto](https://languagemachines.github.io/ucto): An advanced rule-based unicode-aware tokenizer

Deep Linguistic Processing
====

The *deep* here isn't *"deep learing"* deep ;P , see https://en.wikipedia.org/wiki/Deep_linguistic_processing

 - Head-drive Phrase Structure Grammar (HPSG)
   - [DELPH-IN](http://www.delph-in.net/wiki/index.php/Home): Deep Linguistic Processing with HPSG 
   - [English Resource Grammar](http://moin.delph-in.net/ErsTutorial)
   
 - Combinatory Categorial Grammar (CCG)
   - [CCG2PST](https://github.com/jkkummerfeld/berkeley-ccg2pst) : A tool for converting CCG derivations into PTB-style phrase structure trees
   
 

Word Embeddings
====

 - [Word2Vec](https://code.google.com/archive/p/word2vec/)
 - [GloVe](https://nlp.stanford.edu/projects/glove/)
 - [COMPOSE](http://clic.cimec.unitn.it/composes/semantic-vectors.html)
 - [Polyglot](http://polyglot.readthedocs.io/en/latest/)
 - [FastText](https://github.com/facebookresearch/fastText/blob/master/pretrained-vectors.md)

Twitter
====

- [PyTweet](https://github.com/Reflejo/pytweet)
- [Twitter4J](http://twitter4j.org/en/)
- [Affective Tweets](http://github.com/felipebravom/AffectiveTweets)


Task Specific
====

 - Entity Linking / Relation Extraction
   - [KNEWS](https://github.com/valeriobasile/learningbyreading): Knowledge Extraction With Semantics
   - [Deep Dive](http://deepdive.stanford.edu/relation_extraction): Relation Extraction
   
   
 - Coreference
   - [Berkley Coreference Error Analyser](https://github.com/jkkummerfeld/berkeley-coreference-analyser) - A tool for classifying errors in coreference resolution

 
 - Parsing
   - [Berkley Parse Error Analyser](https://github.com/jkkummerfeld/berkeley-parser-analyser): A tool for classifying mistakes in the output of parsers
 


Machine Translation
====

 - Neural MT
   - [OpenNMT](http://opennmt.net/)
   - [Amunmt](https://github.com/amunmt/amunmt)
   - [Google Seq2Seq](https://github.com/google/seq2seq)
   - [Eske Seq2seq](https://github.com/eske/seq2seq)
   
 - Phrased-based MT
   - [Moses MT](http://www.statmt.org/moses)
   - [Joshua](https://cwiki.apache.org/confluence/display/JOSHUA/Apache+Joshua+%28Incubating%29+Home)
   - [Jane](http://www-i6.informatik.rwth-aachen.de/jane/)
   - [Phrasal](https://nlp.stanford.edu/phrasal/)
   - [Kriya](http://natlang.cs.sfu.ca/software/kriya.html)
 
 - Rule-based MT
   - [Apertium MT](http://wiki.apertium.org/wiki/Apertium)
 
 - Example-based MT
   - [Kyoto EBMT](http://nlp.ist.i.kyoto-u.ac.jp/EN/index.php?KyotoEBMT)
   
 - MT-related tools
 
 - MT List of lists
   - [Friends of Moses](http://www.statmt.org/moses/?n=Moses.ExternalTools)
   - [Let’s MT](http://opus.lingfil.uu.se/letsmt-trac/wiki/DataProcessingTools)
   - [Neural Machine Translation Implementations](https://bitbucket.org/hy-crossNLP/neuralmt/wiki/Tools)
   - @jonsafari [A list of Neural MT implementations](https://github.com/jonsafari/nmt-list)

  

Language Modelling
====

 - [SRILM](http://www.speech.sri.com/projects/srilm/)
 - [IRSTLM](http://hlt-mt.fbk.eu/technologies/irstlm)
 - [KenLM](https://kheafield.com/code/kenlm/)
 - [NPLM](http://nlg.isi.edu/software/nplm/)
 - Mikolov's [RNNLM](http://www.fit.vutbr.cz/~imikolov/rnnlm/)
 - Yandex [Fast-RNNLM](https://github.com/yandex/faster-rnnlm)
  
Annotation Related
====

 - Annotation Platforms
   - [Brat Rapid Annotation Tool](http://brat.nlplab.org): Online environment for collaborative text annotation
   - [PyBossa](http://pybossa.com): The ultimate crowdsourcing framework
   - [FLAT](https://github.com/proycon/flat/): FoLiA Linguistic Annotation Tool
   
 - Annotation Toools
   - [TableAnnotator](https://github.com/nikolamilosevic86/TableAnnotator) and [TabInOut](https://github.com/nikolamilosevic86/TabInOut)
   - [Marvin](https://github.com/nikolamilosevic86/Marvin): Semantic text annotation tools using Wordnet and DBPedia 

Others
====
 
 - Author Attribution
    - [Java Graphical Authorship Attribution Program](https://github.com/evllabs/JGAAP)

 - Orthography
    - [Gecco](https://github.com/proycon/gecco): Generic Environment for Context-Aware Correction of Orthography
    - [Charguana](https://github.com/alvations/charguana): Character Vomitting for CJK Unicode
    
    
 - NLP API / Workflow
   - [CLAM](https://proycon.github.io/clam): Turn command-line applications into RESTful webservices with web front-end.
   - [LuigiNLP](https://github.com/languagemachines/luiginlp): Experimental NLP Pipeline system built on top of SciLuigi
   - [TextFlows](http://textflows.org) / [ClowdFlows](http://clowdflows.org/existing-workflows/)
   
 - Misc
   - [Vinci generative environment](http://research.cs.queensu.ca/CompLing/)


NLP Related Machine Learning Tools
====

 - [Timbl](https://languagemachines.github.io/timbl) - Memory-based machine learning 
 - [KeLP](http://sag.art.uniroma2.it/demo-software/kelp/): Kernel-based Learning Platform
 

List of Lists of NLP Resources/Tools
====

 - [Awesome NLP](https://github.com/keon/awesome-nlp) (The original one, curated by @keon and @outpark)
 - [Repo tagged with `nlp` on Github.com](https://github.com/search?q=topic%3Anlp&type=Repositories)
 - [Java or Python for NLP?](http://stackoverflow.com/questions/22904025/java-or-python-for-natural-language-processing)
 - [OpenSource Deep QA Resources](https://docs.google.com/document/d/1XCHWQkgFBS8Iy_y9-1-R82jGS8T_CrKiMxleqpqtmJg/edit?usp=sharing) (also [nice talk](https://www.slideshare.net/jackpark/jst-talk-final))
 - [Sibawayh Repository for Arabic NLP](http://www.sibawayh-nlp.org)
 - @proycon [La Machine](https://proycon.github.io/LaMachine/)
 - [Ruby NLP Resources/Tools](https://github.com/diasks2/ruby-nlp)


See Also
====

 - [Corpora List](http://mailman.uib.no//public/corpora/): Your source of all thing computational linguistics / NLP / corpora 
 - [LT World](http://www.lt-world.org): Language Technology World
 - [META Net](http://www.meta-net.eu)
 - [LDC](https://www.ldc.upenn.edu/): Linguistic Data Consortium
 - [OLAC](http://www.language-archives.org): Open Language Archives Community
 - [NLSR](http://registry.dfki.de): Natural Language Software Registry

