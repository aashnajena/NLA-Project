# NLA-Project
We formulate the problem of Extractive Summarization as a Problem of Regression where we assign an importance score to every sentence in the input document.

Still under maintenance, intro, results and other details to be added.

For Implementation Details on Modelling and saved Pretrained models, go [here](https://github.com/sayarghoshroy/Summarization).

## Data 
This project uses a part of the CNN/Daily mail dataset.
- Our labelled data can be found [here](https://drive.google.com/drive/folders/1hNik2G9hdFf1NlnADgxxAxwrQEmDoEyq?usp=sharing)
- Pretrained embeddings on our data can be found [here](https://drive.google.com/open?id=1IDFgrT8kXDSo-gocku1rARS0gRM3iWdz)
- Trained infersent and fasttext models can be found [here](https://drive.google.com/open?id=1IDFgrT8kXDSo-gocku1rARS0gRM3iWdz)

## Code
Along with the code in the repository, you can download the colab notebooks here :
- [Get fasttext embeddings](https://colab.research.google.com/drive/1LoW4-OHA8a3HQ1vj8ge3Bmjfky1h5nvb)
- [Model for fasttext](https://colab.research.google.com/drive/1Z5O4f4HwO9nIqav1IohP4GZUk184wS83)
- [Model for Infersent](https://colab.research.google.com/drive/1THULtJaG_VDhLjyehaSsjSlYqL4326Nw)

## Evaluation scores

### For fasttext
|                     | fscore               | precision            | recall               |
|---------------------|----------------------|----------------------|----------------------|
| top 3 sentences     |                      |                      |                      |
| rouge_1             | 0.147817491063985    | 0.1191565027549791   | 0.21764581086768142  |
| rouge_2             | 0.032386031740500275 | 0.025221901049095097 | 0.048653199042364106 |
| rouge_l             | 0.12486465817585539  | 0.10309968285602499  | 0.17325227575193802  |
| top 4 sentences     |                      |                      |                      |
| rouge_1             | 0.23079145635431822  | 0.16910484132552217  | 0.407750460829676    |
| rouge_2             | 0.07574577683375168  | 0.05437105405999294  | 0.1374281904099026   |
| rouge_l             | 0.2050603948271745   | 0.15447521739850095  | 0.33267502866279164  |
| top 5 sentences     |                      |                      |                      |
| rouge_1             | 0.22238089529088254  | 0.15288740384962163  | 0.45631344462363566  |
| rouge_2             | 0.07475935402793302  | 0.05056098905490247  | 0.15767976167084463  |
| rouge_l             | 0.2044236926545439   | 0.14525485867624255  | 0.3750272634696634   |

### For infersent

|                     | fscore              | precision           | recall              |
|---------------------|---------------------|---------------------|---------------------|
| for top 3 sentences |                     |                     |                     |
| rouge_1             | 0.23837762616307634 | 0.17870970342922088 | 0.3948210652772677  |
| rouge_2             | 0.0782952265255066  | 0.0586625199432189  | 0.1290943302874871  |
| rouge_l             | 0.20978198592978672 | 0.16219584658887584 | 0.32059361189593455 |
| top 4 sentences     |                     |                     |                     |
| rouge_1             | 0.2263082742007271  | 0.15504706773578525 | 0.4615344756485788  |
| rouge_2             | 0.07889476867782748 | 0.05397341665789107 | 0.16101318569672227 |
| rouge_l             | 0.2087232440138955  | 0.14863005286219036 | 0.3777621191330641  |
| top 5 sentences     |                     |                     |                     |
| rouge_1             | 0.21218549949989918 | 0.13743780821078694 | 0.514433460338619   |
| rouge_2             | 0.07780463190895977 | 0.05039379155868287 | 0.18894813470729832 |
| rouge_l             | 0.20578917643633968 | 0.13901717381078943 | 0.427076310748189   |


