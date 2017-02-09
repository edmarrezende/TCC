**Windows Samples**

* [Win32 folder](https://github.com/edmarrezende/TCC/tree/master/Samples/Win32): Win32 malware samples collected in the wild. 

* [Microsoft Malware Classification Challenge (BIG 2015)](https://www.kaggle.com/c/malware-classification): malware files representing 9 different families. Each malware file has an Id, a 20 character hash value uniquely identifying the file, and a Class, an integer representing one of 9 family names to which the malware may belong. For each file, the raw data contains the hexadecimal representation of the file's binary content, without the PE header (to ensure sterility).  You are also provided a metadata manifest, which is a log containing various metadata information extracted from the binary, such as function calls, strings, etc. This was generated using the IDA disassembler tool. The dataset contains the following files:
** [train.7z](https://www.kaggle.com/c/malware-classification/download/train.7z) (17.52 GB)- the raw data for the training set (MD5 hash = 4fedb0899fc2210a6c843889a70952ed)
** [trainLabels.csv](https://www.kaggle.com/c/malware-classification/download/trainLabels.csv) (265.34 KB) - the class labels associated with the training set
** [test.7z](https://www.kaggle.com/c/malware-classification/download/test.7z) (17.77 GB)- the raw data for the test set (MD5 hash = 84b6fbfb9df3c461ed2cbbfa371ffb43)
** [sampleSubmission.csv](https://www.kaggle.com/c/malware-classification/download/sampleSubmission.csv) (2.01 MB) - a file showing the valid submission format
** [dataSample.csv](https://www.kaggle.com/c/malware-classification/download/dataSample.7z) (4.06 MB) - a sample of the dataset to preview before downloading

**Android Samples**

* [Drebin dataset](https://www.sec.cs.tu-bs.de/~danarp/drebin/download.html): Android malware dataset containing 5,560 files from 179 different malware families. The samples were collected in the period of August 2010 to October 2012. You can find more details on the dataset in the [paper describing Drebin](https://www.tu-braunschweig.de/Medien-DB/sec/pubs/2014-ndss.pdf).
