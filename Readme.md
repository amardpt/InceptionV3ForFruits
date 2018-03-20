# Fruits Image recognition with Spring Boot Integration

## Right now model is trained only for Apple, Papaya, Cherry, Banana, Jackfruit

[![Build Status](https://travis-ci.org/florind/inception-serving-sb.svg?branch=master)](https://travis-ci.org/florind/inception-serving-sb)
[![Coverage Status](https://coveralls.io/repos/github/florind/inception-serving-sb/badge.svg?branch=master)](https://coveralls.io/github/florind/inception-serving-sb?branch=master)


Screenshot (non clickable)<br/>
<div align="center" style="text-align:center"><img src="cat_classified.jpg" width="560"/></div>

## Why
Tensorflow is hard enough to wrap one's head around. It has several parts that deal with preparing data, defining and training a model and finally, outputting a model that can then be used to categorize (infer) other data. There's math involved, new vocabulary to learn and on top, a toolchain which revolves around Python.
This project only addresses serving a Tensorflow pre-trained image categorization model, otherwise called the Inception model.  

## Prerequisites
- JDK 8

## Run
```./gradlew bootrun```

Navigate to http://localhost:8080 and upload an image. The backend will categorize the image and output the result along with the probability.
