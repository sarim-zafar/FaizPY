# FaizPY
The aim of this project is to play around with literary works of Faiz Ahmad Faiz and generate similar text. Right now the performance isnt as great as I wanted it to be but nonethless it works. I do plan to upload the trained models in the near future after trying to tune things a bit more. I will also upload some genrated samples in the future.

## Dataset
I am not sure about the legalities around sharing literary works of the said author so it is not included in this repository. So I have collected the dataset in three files ghazals.xlsx , nazams.xlsx and faiz.txt. The xlsx files contain the name of the ghazal or nazam along with whole text of it. The text file has all of the faiz literature preprocessed.

I would love to hear from you guys. If you find any bugs or any suggestions for improvment let me know.

I have included three models that were trained
* 1D Convolution Model
* Encoder Decoder Model
* Markov Model
* GAN Model(future)

## Getting Started

You'll need to setup python 3 or Anaconda.

### Prerequisites

You need following packages
* jupyter
* pandas
* keras
* numpy

```
pip install jupyter pandas sklearn keras numpy
```

## Authors

* **Sarim Zafar** - *Initial work* - [sarim-zafar](https://github.com/sarim-zafar)

## License

This is yet to be determined

## Acknowledgments

* Keras tutorials on Encoder Decoder LSTM networks
* Would like to thank all the stackoverflow authors who helped us out on every step of our learning
* Inspiration: All the cool kids on the block