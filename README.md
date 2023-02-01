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

**You can find an in-depth explaination in this [report](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/55fcc500-73b7-4fa9-8205-4f8c9c1b88a5/_Report_exam_winter_2023_s309855_s318105.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230201%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230201T112306Z&X-Amz-Expires=86400&X-Amz-Signature=ec10ffdd4241cfa8107df989d75b8d758f4c1af4742405f68b7ca97c6fa5b6c4&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22%2520Report.pdf%22&x-id=GetObject).**

## Set up

Install requirements:

```bash
pip3 install -r requirements.txt
```

 Download the dataset [here](https://www.dropbox.com/scl/fo/9bkoxbfhkxrvrkw2ho7md/h?dl=0&rlkey=iggllq102szbg270tpywo8zpa) and move it into the project folder.
