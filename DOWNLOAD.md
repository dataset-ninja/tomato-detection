Dataset **Tomato Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/i/6/97/mGUuXFJGk0ofyDLU7Hm0TCTC26F8XvG1m09p0VUPj2ZORrjG6O0gmnzhFaD6JNp5S90fVi995DaFsJE49BCF212rnKUG4QiK8J0OmvYRr374Ey2ZnZcEmX6Z997W.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Tomato Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/andrewmvd/tomato-detection/download?datasetVersionNumber=1)