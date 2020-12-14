# Some offline API documentations

### How to build from html to docset

```
pip install doc2dash

doc3dash [-n "Name"] html_floder_path
```

e.g.
"index.html" is in "./numpy/doc/index.html"
then use `doc2dash -n Python.numpy ./numpy/doc` to build `Python.numpy.docset`



## Src List

|          |                      Src                       |           Docset           | Docset Build Time |
| :------: | :--------------------------------------------: | :------------------------: | :---------------: |
|  Numpy   |          https://docs.scipy.org/doc/           |  [Python.Numpy.docset]()   |    2020/12/14     |
|  Pandas  | https://pandas.pydata.org/pandas-docs/stable/  |  [Python.Pandas.docset]()  |    2020/12/14     |
| pymongo  | https://github.com/mongodb/mongo-python-driver | [Python.pymongo.docset]()  |    2020/12/13     |
| requests |        https://github.com/psf/requests         | [Python.requests.docset]() |    2020/12/13     |

