UPPC (Urdu Paraphrase Plagiarism Corpus)
========================================

The corpus contains 160 Urdu text documents in total. 20 documents are original Wikipedia articles on well-known people whereas 140 documents (manually created by volunteers) are paraphrase plagiarise and non-plagiarise versions of the original articles. 75 documents are paraphrased by 5 university students using different paraphrasing techniques. 65 documents are independently written without considering the source article.

Licence of the Corpus:
----------------------
The corpus is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

Corpus Statistics:
------------------
The corpus contains 20 original documents (Wikipedia excerpts), 75 plagiarised and 65 non-plagiarised documents of length between 200-300 words. Total number of words (tokens) in the corpus are 46,729 words (tokens), 6,201 unique words and 2,711 sentences.

Corpus Format:
------------------
The corpus has been saved in standard XML format for easy access and use. All documents of the corpus are saved inside the “data” directory. Each document start with XML declaration tag. Corpus text has been inclosed within <UPPC_document> tag which contains 3 attributes;
classification: Three possible values O (Original), P (Paraphrased), NP (Non-Paraphrased)
title: Name of the personality on which the document is written 
file: Filename of the document

The “all_files.txt” file provided with the corpus contains, in CSV format, list of plagiarised and non-plagiarised file names and their relationship (P or NP) with the source(s).


Acknowledging the Corpus:
-------------------------

We release this corpus with an intention that it will foster the research in Urdu paraphrase plagiarism detection systems. If you use the corpus we kindly ask you to refer to it in your publications as follows:

Bibtex:
@inproceedings{sharjeel2016uppc,
  title={UPPC - Urdu Paraphrase Plagiarism Corpus},
  author={Sharjeel, Muhammad and Rayson, Paul and Nawab, Rao Muhammad Adeel},
  booktitle={The 10th edition of the Language Resources and Evaluation Conference (LREC)},
  year={2016}
}

Contact Information:
--------------------
If you have any questions or suggestions, or any other feedback please send an email to ucrel@lancaster.ac.uk.


Note: The use of this corpus is restricted to research and/or academic purposes only. 