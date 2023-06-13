Dataset **Tomato Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/g/A/Vt/0aqttdMnYsQ5GB4Etpvm4quSHEmjaWZK3skjpQzzGQT9Px05ii7RsfZvzoPe0vilYpOqm0ldTTZtLZ2MWYbNmxrJLoZzjlz0IjbDLNxp5woH3Qzgtz2zaGIUdmTe.tar)

As an alternative, it can be downloaded with dataset-tools package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Tomato Detection', dst_path='~/dtools/datasets/Tomato Detection.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/andrewmvd/tomato-detection/download?datasetVersionNumber=1)