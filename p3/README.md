# Week #3. Object Detection

## Files description.

### `p3_1.ipynb, p3_2.ipynb,  p3_3.ipynb`

These are `colab`-ready notebooks containing the practical lessons code. Store it somewhere on your Google Drive to run without modifications via the [Google Colab](https://colab.research.google.com/) or modify correspondingly to run via the [Jupyter](https://jupyter.org/).

Please refer to the corresponding lecture for the usage details.

Note: In the lecture, the notebooks were run using local runtime,
so they may have minor differences.

## References
[FiftyOne](https://voxel51.com/fiftyone/) 

### OpenImages Dataset
[OpenImages Dataset](https://storage.googleapis.com/openimages/web/index.html)

```
@article{OpenImages,
  author = {Alina Kuznetsova and Hassan Rom and Neil Alldrin and Jasper Uijlings and Ivan Krasin and Jordi Pont-Tuset and Shahab Kamali and Stefan Popov and Matteo Malloci and Alexander Kolesnikov and Tom Duerig and Vittorio Ferrari},
  title = {The Open Images Dataset V4: Unified image classification, object detection, and visual relationship detection at scale},
  year = {2020},
  journal = {IJCV}
}
```
```
@inproceedings{OpenImagesSegmentation,
  author = {Rodrigo Benenson and Stefan Popov and Vittorio Ferrari},
  title = {Large-scale interactive object segmentation with human annotators},
  booktitle = {CVPR},
  year = {2019}
}
```
```
@inproceedings{OpenImagesLocNarr,
  author    = {Jordi Pont-Tuset and Jasper Uijlings and Soravit Changpinyo and Radu Soricut and Vittorio Ferrari},
  title     = {Connecting Vision and Language with Localized Narratives},
  booktitle = {ECCV},
  year      = {2020}
}
```
```
@article{OpenImages2,
  title={OpenImages: A public dataset for large-scale multi-label and multi-class image classification.},
  author={Krasin, Ivan and Duerig, Tom and Alldrin, Neil and Ferrari, Vittorio and Abu-El-Haija, Sami and Kuznetsova, Alina and Rom, Hassan and Uijlings, Jasper and Popov, Stefan and Kamali, Shahab and Malloci, Matteo and Pont-Tuset, Jordi and Veit, Andreas and Belongie, Serge and Gomes, Victor and Gupta, Abhinav and Sun, Chen and Chechik, Gal and Cai, David and Feng, Zheyun and Narayanan, Dhyanesh and Murphy, Kevin},
  journal={Dataset available from https://storage.googleapis.com/openimages/web/index.html},
  year={2017}
}
```
### SSD: Single Shot MultiBox Detector
```
@inproceedings{conf/eccv/LiuAESRFB16,
  added-at = {2020-02-12T00:00:00.000+0100},
  author = {Liu, Wei and Anguelov, Dragomir and Erhan, Dumitru and Szegedy, Christian and Reed, Scott E. and Fu, Cheng-Yang and Berg, Alexander C.},
  biburl = {https://www.bibsonomy.org/bibtex/2a2b481fd62137855241846b53fc5d4cd/dblp},
  booktitle = {ECCV (1)},
  crossref = {conf/eccv/2016-1},
  editor = {Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max},
  ee = {https://www.wikidata.org/entity/Q60638633},
  interhash = {b446854aff4b39b071b4db6dd7babde3},
  intrahash = {a2b481fd62137855241846b53fc5d4cd},
  isbn = {978-3-319-46447-3},
  keywords = {dblp},
  pages = {21-37},
  publisher = {Springer},
  series = {Lecture Notes in Computer Science},
  timestamp = {2020-02-13T12:33:05.000+0100},
  title = {SSD: Single Shot MultiBox Detector.},
  url = {http://dblp.uni-trier.de/db/conf/eccv/eccv2016-1.html#LiuAESRFB16},
  volume = 9905,
  year = 2016
}
```
### ultralytics/yolov5
[ultralytics/yolov5](https://github.com/ultralytics/yolov5/) 
```
@software{glenn_jocher_2022_6222936,
  author       = {Glenn Jocher and
                  Ayush Chaurasia and
                  Alex Stoken and
                  Jirka Borovec and
                  NanoCode012 and
                  Yonghye Kwon and
                  TaoXie and
                  Jiacong Fang and
                  imyhxy and
                  Kalen Michael and
                  Lorna and
                  Abhiram V and
                  Diego Montes and
                  Jebastin Nadar and
                  Laughing and
                  tkianai and
                  yxNONG and
                  Piotr Skalski and
                  Zhiqiang Wang and
                  Adam Hogan and
                  Cristi Fati and
                  Lorenzo Mammana and
                  AlexWang1900 and
                  Deep Patel and
                  Ding Yiwei and
                  Felix You and
                  Jan Hajek and
                  Laurentiu Diaconu and
                  Mai Thanh Minh},
  title        = {{ultralytics/yolov5: v6.1 - TensorRT, TensorFlow 
                   Edge TPU and OpenVINO Export and Inference}},
  month        = feb,
  year         = 2022,
  publisher    = {Zenodo},
  version      = {v6.1},
  doi          = {10.5281/zenodo.6222936},
  url          = {https://doi.org/10.5281/zenodo.6222936}
}
```







