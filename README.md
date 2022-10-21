# Thesis
### Department of Engineering, Bilkent University
### MSc Project


# Genre Based Trailer Generation with Deep Multimodal Learning


### Author: Irmak Türköz,        irmak.turkoz@bilkent.edu.tr

### Supervisor: H. Altay Güvenir, guvenir@cs.bilkent.edu.tr                

# Abstract
Promoting movies through their trailers provides valuable information that can
help viewers and investors form expectations about the movie’s future success.
Recent research confirmed that the audience prefers to watch movies through
at-home-streaming services rather than at the theaters which resulted in movie
trailers being shown privately. Moreover, advertisements created for different
interest groups can provide a drastically improved experience for users and advertisers
alike.
There have been few attempts to automatize the trailer generation process
however, AI-generated trailers were considered less attractive than editors’ creations.
Fortunately, the use of the most recent advancements in deep learning
and the greater availability of datasets can accelerate the automated trailer generation
process. Every movie produced is labeled with a set of genres that it
represents. Thus, it is possible to generate multiple trailers of the same movie
for different genres to offer personalized advertisements to the audience. To the
best of our knowledge, personalized advertisements of movies via genre-specific
trailers will be the first attempt in the automated trailer generation studies.
For this task, we needed a tool that extracts representative scenes of a particular
genre from a given movie. Then, these scenes can be concatenated to form a
draft of a trailer for each genre. The draft can be finalized through the creative
post-production process. In this thesis, we developed a deep learning network
that classifies scenes into a set of genres. In order to construct a training dataset
to train this network, we compiled a set of scenes that are labeled with their
representative genres.

Our network accomplishes a multi-label classification task with hyperparameters
learned from experimental binary models. The learning process comprises
the use of visual features, audio features, and their combination. The final
result of the model is evaluated by comparing its classification performance with
human perception.

![Thesis Methodology Pipeline](https://user-images.githubusercontent.com/12885387/159249407-642ac5e0-c033-42c5-8c9e-de03f7ecbcc2.png)
