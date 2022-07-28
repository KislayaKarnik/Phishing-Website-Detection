# Data Files

This folder has the raw & extracted datafiles of this project. The description of each file is as follows:

* [Benign_list_big_final.csv -](https://github.com/KislayaKarnik/Phishing-Website-Detection/tree/main/Datasets/Benign_list_big_final.csv) This file has list of legitimate urls. The total count is 35,300. The source of the dataset is University of New Brunswick, https://www.unb.ca/cic/datasets/url-2016.html. 

* [online-valid.csv -](https://github.com/KislayaKarnik/Phishing-Website-Detection/tree/main/Datasets/online-valid.csv) This file is downloaded from the opensource service called PhishTank. This service provide a set of phishing URLs in multiple formats like csv, json etc. that gets updated hourly. To download the latest data: https://www.phishtank.com/developer_info.php.

* [legitimate.csv -](https://github.com/KislayaKarnik/Phishing-Website-Detection/tree/main/Datasets/legitimate.csv) This file has the extracted features of the 5000 legitimate URLs which are randonmly selected from the 'Benign_list_big_final.csv' file.

* [phishing.csv -](https://github.com/KislayaKarnik/Phishing-Website-Detection/tree/main/Datasets/phishing.csv) This file has the extracted features of the 5000 phishing URLs which are randonmly selected from the 'online-valid.csv' file.

* [urldata.csv -](https://github.com/KislayaKarnik/Phishing-Website-Detection/tree/main/Datasets/urldata.csv) This file is nothing but a combination of the above two files. It contains extracted features of 10,000 URLs both legitimate & phishing.
