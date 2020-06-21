# BANGKIT JKT6-B FINAL PROJECT
Thank you to Bangkit program and thank you to Google, Gojek, Tokopedia, and Traveloka for give us the chance to learn about Machine Learning. This is the documentation from final project that bangkit give to us. This is may be not so great result and really far from perfect but this is our contribution as a team and we perform experiment using try and error for the perfect result. We hope this program can make people understand about simple model of Batik in Indonesia.

## Table Of Content
* [Dataset](README.md#Dataset)
* [Problem](README.md#Problem)
* [Documentation](README.md#Documentation)
* [References](README.md#References)

## Dataset 
 We make sure to thank you to Mr Agus that provide us with [Batik300 dataset](https://github.com/agusekominarno/Batik) for public consumption. Batik300 datasets really help us to explore batik much more and gave us knowledge about batik. 
 We also use [Bed furniture image Dataset](https://www.kaggle.com/c/imaterialist-challenge-furniture-2018/) as helper to create binary classification in transfer learning with resnet_v2 task.
 
## Problem
 We tried to make this project as optimal for the result as good as we can. For the time being we already tried every method and every algorithm, but for this case our problem is only small data for every class. We already tried to classify every images. the result still need more images for every 1 model batik image. We understand this problem may not sure to make our result better but we must try our best to finish this project as natural as possible.
 
## Documentation
For basic use Batik-group.rar to learn about the data partition before we start the project
### 1. Inception_v3 and mobile_v2
* You can try the code in this repo Batik-inception_v3.ipynb and Batik-mobilenet_v2.ipynb
* Get the dataset and import into notebook.
* This model using transfer learning to improve the optimization and getting the loss function.
* Try to configure the model from conv2D or using other optimization or loss to make the data more optimal
* You can use other sample image using this code and try it yourself.
### 2. Resnet50_v2
* You can try the code in this repo Batik-resnet_v2_metric.ipynb.
* Get the dataset and import into notebook.
* This model using transfer learning to improve the optimization and getting the loss function.
* Try to configure the model from conv2D or using other optimization or loss to make the data more optimal
* Try to change path for target image and collection of images.
* You can use other sample image using this code and try it yourself.
### 3. Siamese Neural Network
* You can try the code in this repo, even though we have 2 files.
* Batik-Siamese-4_2.ipynb in folder program is recognizing batik with 4 images for train and 2 for test
* Batik-Siamese-5_1.ipynb in folder program is recognizing batik with 5 images for train and 1 for test
* This program surely call model Siamese Neural network and you can try using another
model image to implement using this algorithm

## References

[Minarno, A. E. et al. (2018). Comparison of Classification Method for Batik Classification Using Multi Texton Histogram. TELKOMNIKA (Telecommunication Computing Electronics and Control), 16](https://scholar.google.co.id/scholar?hl=id&as_sdt=0%2C5&q=Minarno%2C+A.+E.+et+al.+%282018%29.+Comparison+of+Classification+Method+for+Batik+Classification+Using+Multi+Texton+Histogram.+TELKOMNIKA+%28Telecommunication+Computing+Electronics+and+Control%29%2C+16.&btnG=)

[Minarno, A. E., Munarko, Y., Kurniawardhani, A., & Bimantoro, F. (2016, January). Classification of Texture Using Multi Texton Histogram and Probabilistic Neural Network. In IOP Conference Series: Materials Science and Engineering (Vol. 105, No. 1, p. 012022). IOP Publishing.](https://scholar.google.co.id/scholar?hl=id&as_sdt=0%2C5&q=Minarno%2C+A.+E.%2C+Munarko%2C+Y.%2C+Kurniawardhani%2C+A.%2C+%26+Bimantoro%2C+F.+%282016%2C+January%29.+Classification+of+Texture+Using+Multi+Texton+Histogram+and+Probabilistic+Neural+Network.+In+IOP+Conference+Series%3A+Materials+Science+and+Engineering+%28Vol.+105%2C+No.+1%2C+p.+012022%29.+IOP+Publishing.&btnG=)

[Mardani, Danis & Pranowo, Pranowo & Santoso, Albertus. (2020). Deep learning for recognition of Javanese batik patterns. AIP Conference Proceedings. 2217. 030012. 10.1063/5.0000686.](https://www.researchgate.net/publication/340642530_Deep_learning_for_recognition_of_Javanese_batik_patterns)

# Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
   <td align="center"><img src="https://avatars1.githubusercontent.com/u/57791152?s=96&v=4" width="100px;" alt=""/><br /><sub><b>Asriyanti Ali</b></sub></a><br /></td>   
    <td align="center"><img src="https://avatars1.githubusercontent.com/u/53148786?s=460&u=dacb93f2cc602a32c8a96ae63335d224da6126a7&v=4" width="100px;" alt=""/><br /><sub><b>Jeremy Christian W</b></sub></a><br /></td>
    <td align="center"><img src="https://avatars3.githubusercontent.com/u/47228746?s=60&v=4" width="100px;" alt=""/><br /><sub><b>Kemal Maulidiasani</b></sub></a><br /></td>
   <td align="center"><img src=MyAusweis width="100px;" alt=""/><br /><sub><b>Limin Mandrawa</b></sub></a><br /></td> 
   
  </tr>
 
 </table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the specification.
Contributions of any kind welcome!
