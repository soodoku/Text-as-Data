## Text as Data

### Get Text Data

You can get text data from scraping, APIs, searchable pdfs, images of paper, etc. Some examples:
* [Get Congressional Speech Data](https://gist.github.com/soodoku/85d79275c5880f67b4cf) using Capitol Words API from the Sunlight Foundation
* [Get data from Wisconsin Ads storyboards](https://gist.github.com/soodoku/62a3172eb1b4a55dee1a)
* [Get text from images of text](https://github.com/soodoku/image-to-text)

### Preprocess Text
Preprocess text for text-as-data analysis. 

Depending on the need, remove stop words, punctuation, capitalization, special characters, and stem.

* [preprocess_txt](https://github.com/soodoku/text-as-data/tree/master/preprocesstxt) takes a directory of 'raw' text files and outputs processed text files in the same directory structure. 
* [preprocess_csv](https://github.com/soodoku/text-as-data/tree/master/preprocess_csv) takes a csv with 'raw' text and outputs a csv with processed text.

### Subset Data

Output a simple or stratified random sample of a csv, and only the columns you need. Get summary of crucial aspects of the data. See [Subset](https://github.com/soodoku/text-as-data/blob/master/subset/).

### Get TDF

### Sentiment Analysis in Python
* [Basic sentiment analysis](https://gist.github.com/soodoku/22e4cff2eb6a05be3c0d) using AFINN

### Analyze Text in R

* Classify text in R using SVM or Lasso. See [Basic Text Classifier](https://gist.github.com/soodoku/e34dbe0219b0f00a74d5)

### License

Scripts are released under the [MIT License](https://github.com/soodoku/Weather-Data/License%20for%20Scripts.md).