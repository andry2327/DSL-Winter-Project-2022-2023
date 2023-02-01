# DSL Winter Project 2022-2023 - Speech Recognition

This is a project made with [Elisa Cascina](https://github.com/ElisaCascina) for the Data Science and Engineering course [Data Science Lab: Process and Methods](https://dbdmg.polito.it/dbdmg_web/index.php/2022/09/26/data-science-lab-process-and-methods-2022-23/) in PoliTo.

In this project we introduce a possible approach for
classification problem in the field of natural language processing
and speech recognition. In particular, the proposed approach
is based on the Mel-frequency Cepstral Coefficients (MFCC),
a widely used technique for extracting features from the audio
signal. Every mfcc is divided into blocks in the time domain,
some summary statistics are computed and used as input for
a Random Forest classification model. The presented method
overcomes the benchmark set for the issue and delivers overall
acceptable outcomes.

**You can find an in-depth explaination in this [report](shorturl.at/ejsxB).**

## Set up

Install requirements:

```bash
pip3 install -r requirements.txt
```

 Download the dataset [here](https://www.dropbox.com/scl/fo/9bkoxbfhkxrvrkw2ho7md/h?dl=0&rlkey=iggllq102szbg270tpywo8zpa) and move it into the project folder.
