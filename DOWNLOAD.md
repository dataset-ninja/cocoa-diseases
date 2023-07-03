Dataset **Cocoa Diseases** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/a/M/K1/7X136vwspUAtkmqcVuT7ZzoPn23QiG7udnECLXbhsP18d9BH1lQHdZdrCHEZ0vLIRrNqzXuZmZBq0duaRyzIcZQELlLZhmtpwINBnqhonuNx4ibLTlDwcJfeONMd.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Cocoa Diseases', dst_path='~/dtools/datasets/Cocoa Diseases.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/serranosebas/enfermedades-cacao-yolov4/download?datasetVersionNumber=2)