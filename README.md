# word2vec

Word2Vec implementation in numpy. Tried out Skip-Gram model on  ```A Storm of Swords``` by ```R.R. Martin``` .</br>
Dataset Link : https://www.kaggle.com/muhammedfathi/game-of-thrones-book-files#got2.txt

-------------------------------------------------------------------------------------------
## Word2Vec Architecture


Dimensions of Input Layer: ```V X 1``` (vocabulary Size)</br>
Dimensions of W1: ```V X Number of Dimensions of Embedding```</br>
Dimensions of Hidden Layer 1: ```Number of Dimnsions of Embedding X 1```</br>
Dimensions of W2: ```Number of Dimensions of Embedding X V ```</br>
Dimensions of Output Layer: ```V X 1```</br>


![Word2vec Architecture](https://github.com/talha1503/word2vec/blob/master/word2vec_architecture.png)
-------------------------------------------------------------------------------------------
## Built With

* [nltk](https://www.nltk.org/)
* [numpy](https://numpy.org/)
* [matplotlib](https://matplotlib.org/3.1.1/contents.html)

## Results

Epochs : ```5``` </br>
Total vocabulary size : ```6633``` words </br>
Number of Dimensions : ```10``` </br>

![Output for a set of words](https://github.com/talha1503/word2vec/blob/master/output1.png)


## To-do
- [ ] CBOW Model
- [ ] Negative Sampling
- [ ] Try out for more epochs and larger dimensions.

## Acknowledgments

* Research paper on Word2Vec https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf
* A YouTube video by Jordan Boyd-Graber https://www.youtube.com/watch?v=QyrUentbkvw
* Medium blog by Derik Chia which helped in the implementation https://towardsdatascience.com/an-implementation-guide-to-word2vec-using-numpy-and-google-sheets-13445eebd281
