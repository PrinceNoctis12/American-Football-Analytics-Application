[![DOI](https://zenodo.org/badge/293692566.svg)](https://zenodo.org/badge/latestdoi/293692566)
[![Build Status](https://travis-ci.org/himol7/American-Football-Analytics-Application.svg?branch=master)](https://travis-ci.org/himol7/American-Football-Analytics-Application)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/himol7/American-Football-Analytics-Application/issues)
[![HitCount](http://hits.dwyl.com/himol7/https://githubcom/himol7/American-Football-Analytics-Application.svg)](http://hits.dwyl.com/himol7/https://githubcom/himol7/American-Football-Analytics-Application)

# TouchDown, an Analytics application for American Football

[![Watch the video](/logo/icon.png)](https://www.youtube.com/watch?v=GLtjMf34_LE&feature=youtu.be&ab_channel=AmitMandliya)

### Project Idea:

Create a web application which can:
* Analyze the football match data
* Show the summary visuals of the analysis

### Why TouchDown?
In 2002, Oakland Atheltics, a seemingly medium-strength team achieved unusual success in their season even after departure of key players. Behind their success was sabermetrics, a field which thrives on quantitative analysis of sports data. Drawing motivation from this success story and understanding the problems which the current football coaches at NC State are facing, we have developed TouchDown - a customer-centric easy-to-use application which provides you a pictorial analysis of position specific player performances.

With a simple UI, all you need to do it just upload the data file<sup>1</sup> and the application promptly outputs the images where you can view your analysis. Furthermore, with some exciting features lined up, we'd be happy to incorporate some new features on demand.

### Plan for project 1:

* Analysis of the input data with the help of python libraries.
* Project the summary of the analysis on the images.
* Sending the images as response to the front end.
* Rendering the images on the front end.

### Plan for project 2:
Below functionalities can be added to the project:
* Take the existing code as reference and generate the visuals for different types of play positions.
* Increase the test coverage.
* Add options for user to choose between match-wise, year-wise or season-wise statistics and generate image corresponding to respective statistic.
* Deploy in AWS.
* Improvise the front end CSS to make it  more responsive

<sup>1</sup> Data file refers to the files which are used by football coaches at NC State. The original source of the files is not known to us but it is believed that the source is widely popular amongst football coaches.


### Instructions to run:
1. Install the dependency.
```
pip install -r requirements.txt
```
2. Please go to vue-app directory for running the front end.

3. Please go to backend/src directory for running the back end.
