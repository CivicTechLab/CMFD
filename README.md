# C-MFD 2.0
Chinese Moral Foundation Dictionary 2.0 

Devloped by Weiyu Zhang (National University of Singapore) and Yixiang Calvin Cheng (Oxford University), with assistance by Zhuo Chen (Peking University HSBC Business School), Yipeng Xi (Shanghai Jiaotong University), Haodong Liu (City University of Hong Kong) and Chuyao Wang (King's College London). Special thanks to Zhiyuan Liu (Fudan University) for creating the Python package (https://pypi.org/project/cmfd/). 

The Chinese Moral Foundation Dictionary 2.0 (C-MFD 2.0) is a dictionary to assist the automated moral intuition detection and analysis in the Chinese language context. Starting from the existing Chinese translation of the English MFD, two experts selected additional Chinese moral concepts and used word2vec to fetch related words from an extensive Chinese dictionary. Four experts went through four-rounds of coding, followed by the validation from 202 crowd coders. The CMFD identifies not only the classic five moral foundations but also several potentially novel moral foundation candidates.

Files:
1. R package to run the dictionary - see "cmfd_nus.RData"
2. Excel that includes all words and their moral labels - see "cmfd_civictech.csv"
3. Validity test results - see "cmfd_validitytest"
4. Crowd generated texts - see "cmfd_sampletext"
5. Guide to use CMFD - see "cmfd_guide"
6. Python package installation - "pip install cmfd"

*Our recommendation is to validate CMFD with human coders whenever the dictionary is applied to a new context (e.g., a new issue or a new type of document).* 


CMFD 2.0 has the following features in its development:
1.	CMFD 2.0 includes 6,138 words, the most extensive Chinese moral dictionary as we know. CMFD 2.0 is developed based on BOTH Chinese translations of English moral words AND a collection of Chinese-specific moral words, resulting in an initial pool of 17,033 words.
2.	CMFD 2.0 involves four rounds of coding by four experts. The average intercoder reliability eventually reached .91. In addition to the five moral foundations, experts coded “unknown” words if they were not sure how to map the words. Six potentially novel moral foundations plus one general group emerged out of the procedure.
3.	CMFD 2.0 includes 202 crowd coders to validate the dictionary, by asking them to write short passages related to each of the 11 moral foundations and applying CMFD 2.0 to analyse.
4.	CMFD 2.0’s validation results show that it performs better than CMFD 1.0 to analyse the five moral foundations. For the six potentially novel moral foundations, CMFD 2.0 can identify some (e.g., waste, liberty) better than others (e.g., altruism, resilience), suggesting that some candidates may overlap with the mainstream five.  
5.	CMFD 2.0 can be used to answer many important questions, such as how moral language is used to discuss various issues, or whether moral contagion on social media is possible, or how different moral meanings of the same words develop out of different cultural contexts. 
