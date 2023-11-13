# Melanoma Detection

> Melanoma Detection by Nishadh Shrestha

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

The aim of this project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- The performance of the model can be improved by using a number of optimizations some of which include:
  - Data Augumentation
  - Class Rebalancing
  - Use of dropout layers

The final model in this project reaches training accuracy above 90% while the validation accuracy plateaus at around 80%. While this is significantly better performance compared to model created without using any optimizations like class rebalancing and data augumentation, there still room for improvement specially to bring training and validation accuracy closer to each other.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- tensorflow 2.14.0
- numpy 1.23.5
- pandas 1.5.3
- PIL 9.4.0
- Augmentor 0.2.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- Learning from Convolutional Neural Networks. course by [Prof. G. Srinivasaraghavan](http://iiitb.ac.in/faculty_page.php?name=GSrinivasaraghavan)
- Valuable suggestations in a lecture by Mr. Siva Kumar

## Contact

Created by [@nishadh] - feel free to contact me!
