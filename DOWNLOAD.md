Dataset **Pink-Eggs Dataset V1** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/o/V/7m/qKNRmpi8z3G8mPzH0IFlPXvC6JpksR6TRYksyoWwiv3eVaV9tZ4pp8aSzF00bJ5XQeqauOwqbTfCXt2rJWTzjTpyvG4Po4jgCjLGHOObwvANV7xnycgUreOPEvAJ.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Pink-Eggs Dataset V1', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

