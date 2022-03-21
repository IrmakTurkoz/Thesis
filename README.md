# Thesis
### Department of Engineering, Bilkent University
### MSc Project


# Genre Based Trailer Generation with Deep Multimodal Learning


### Author: Irmak Türköz,        irmak.turkoz@bilkent.edu.tr

### Supervisor: H. Altay Güvenir, guvenir@cs.bilkent.edu.tr                

# Abstract
Trailer advertising provides crucial information that can help viewers and investors form expectations about the movie's future success. Recently, there have been few attempts to automatize the trailer generation however, AI-generated trailers were considered less attractive than editors’ creation. Fortunately, usage of the most recent advancements in deep learning and greater availability of datasets can accelerate the automated trailer generation and it is possible to generate multiple trailers to offer personalized advertisements to the audience to provide a drastically improved experience for users and advertisers alike. To the best of our knowledge, personalized advertisements of the movies via genre-specific trailers will be the first research in the automated trailer generation studies. Instead of using long movies, the multimodal network will learn from shorter trailers, with accessing 14 multi-class input of trailers and 14 multi-class output tasks. The feature learning will be made with automatized scene detection of the trailers, and the sound based Mel-frequency cepstral coefficients (MFCCs).  Later, this pre-trained model will be used on actual movies in an unsupervised manner to detect the individual segments belongs to each genre. The final result of the model will be cut scenes and these will be sent to post production of the editors and will be evaluated with the surveys presented to the diverse interests groups.

![Thesis Methodology Pipeline](https://user-images.githubusercontent.com/12885387/159249407-642ac5e0-c033-42c5-8c9e-de03f7ecbcc2.png)
