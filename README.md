# Detecting-disclosure-of-sensitive-information-on-social-networks
![alt text](https://img.shields.io/badge/python-3.5-green.svg "Python3.5")

### Approach
The first step is to collect images shared on Flickr and Facebook. An existing Flickr images data set was found on the website of the LIACS Media Research Group at Leiden University. The MIRFLICKR data set has a collection of images downloaded from Flickr through its public API coupled with complete annotations and EXIF metadata. The data set is available at http://press.liacs.nl/mirflickr/ under the Creative Commons license. For Facebook, Python is used in the data gathering process by making AJAX requests to Facebook. 

The next step is to build a neural network to recognise handwritten digits with TensorFlow and run against these photos to extract photos containing numbers. After photos with numbers in them are identified, each photo is checked and classified by hand. Personal and confidential information found inclue driver’s license, social security, credit card, zip code, date of birth and phone numbers. 
