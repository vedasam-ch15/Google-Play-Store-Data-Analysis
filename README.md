# Google-Play-Store-Data-Analysis
<font color="red">A project based on Topic Modeling on the app reviews of various android apps of Google Play Store. </font><br/>
* Among various categories of apps, "Business" category has been chosen. EDA has been done in [colab file](EDA_apps.ipynb)<br/>
* Using inbuilt library of google-play-scraper, app reviews and app details have been scraped in this [colab file](Scrape_PlayStore.ipynb) <br/>
1000 newest reviews of all ratings have been collected for app reviews. <br/>
* Corresponding to these results, two csv files are extracted: [apps](business-apps.csv) and [app reviews](reviews - outputfile (1).csv) <br/>
* Topic Modeling has been done on the app reviews and each of the app is divided into 6 major topics. <br/>
Based on the topics divided, Bug Analysis has been done for the reviews based on the [CWE documentation](https://cwe.mitre.org/data/definitions/699.html)
* Final findings have been reported in the [report](Report.pdf)
