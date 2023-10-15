Dataset **Cocoa Diseases** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/W/u/w9/LPB57TH3waUVr2SrqMMX5dnK5pw2K9OiL20C8oOaAkUHESIhhtZwMpfMPE0bFYftWD2O0N1rK9A3fpo7HSnqOywxswYg1NrB5cWKgEth5ucV0PxUUngpn0UxTZWQ.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Cocoa Diseases', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/serranosebas/enfermedades-cacao-yolov4/download?datasetVersionNumber=2).