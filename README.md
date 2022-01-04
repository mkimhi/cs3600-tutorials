# Deep learning - tutorials (cs3600)
## Reichman University (former IDC), computer science department 
##
<h1 align="center">
  <br>
  <img src="3600.jpg" height="200">
</h1>



## Run the notebooks
* install [miniconda](https://conda.io/miniconda.html) distribution of python3 using this [instruction](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
* add conda to your bashrc:

```bash
echo "source $HOME/miniconda3/etc/profile.d/conda.sh" >> ~/.bashrc
```


* for windows dont forget to download [VS Build tool](https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019)

* create virtual env and activate it
```bash
 conda env update -f environment.yml
 conda activate cs3600
```


## Sylabus

|Tutorial       | Topics Covered |
|----------------|---------|
|T1| Getting started, python programing, numpy and pytorch basics with automatic difrentiation, logistic regression |
|T2| Reminder on linear models, The MLP and Weights initilization|
|T3| Convolution and Convolutional layers (including dialation, transpose..), Pooling, Batch Normalization, Dropout regulatization,CNN common architecture, examples for diffrent models expresivness, Residual block and Residual nets, feature and weights visualization, inception net, quick overview on adverserial attacks and inherant networks biases |
|T4| Sequence modeling, forms of tasks, classical embedings and aproches (BOW,TF-IDF, N-GRAM), RNN, BPTT,TBTT,Gradient Cliping,LSTM and GRU, Bidirectional RNN, embeding types, Sentiment analysis for movie reviews, Time-Series Forecasting: Predicting Stock Prices Using GRU | 
|T5| Attention: Encoder Decoder and Latent space, Attention mechanisem (scaled dot product attention, Multiplicative attention, Additive attention), Self attention Machine transtlation with Attention for alignment, Bleu Score, Transformers: Multy head attention and possitional encoding, inference with GPT2 from huggingface |
|T6| Generative models, Discriminative Vs. Generative, generate data with KDE and GMM, KL-DIV, VAE and GAN, DCGAN, WGAN, ConditionalGAN and StyleGAN|
|T7| Semantic Segmentation: Task Definision, Evaluation matrics, Old fashion (Threshhlding, Watershed, GrabCut), FCNET, UNET, PSPNET, DEEPLAB |

## License
released under the [MIT license](LICENSE).
