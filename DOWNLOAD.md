Dataset **Tomato Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzk4OV9Ub21hdG8gRGV0ZWN0aW9uL3RvbWF0by1kZXRlY3Rpb24tRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiRkRublU4WVZmMndKTUNaUEFSZUo1cWhNK2NXUURNdVpyK2Zraks3dGtlbz0ifQ==)

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

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/andrewmvd/tomato-detection/download?datasetVersionNumber=1).