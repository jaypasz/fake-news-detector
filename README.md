[![Build Status][ci-svg]][ci-url]

[ci-svg]: https://circleci.com/gh/fake-news-detector/robinho.svg?style=shield
[ci-url]: https://circleci.com/gh/fake-news-detector/robinho

Robinho
=======

## How to run

First you need to install the dependencies:

```
pip3 install -r requirements.txt
```

Then you can use the saved model to do predictions:

```
python3 . "notícia do mbl"
>> Extremely Biased

python3 . "notícia do neymar"
>> Legitimate
```

To retrain the model:

```
python3 . --retrain
```

To run tests:

```
python3 -m unittest tests/*_test.py
```

## Deploy

Read more about deploying docker with heroku [on the oficial docs](https://devcenter.heroku.com/articles/container-registry-and-runtime).