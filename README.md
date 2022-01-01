# COCoNIC

[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/aadimator/coconic)

Converts the CoNIC data fromat into [COCO format](https://cocodataset.org/#format-data).

I have utilized the official conversion scripts provided by the COCO Team in the [cocodataset/panopticapi](https://github.com/cocodataset/panopticapi) repository.
I have also commented out the multiprocessing functionality as I was running this on `Windows` and it wasn't working properly there. I didn't have much time and motivation to fix the bugs, so I resorted to single thread execution. If you want multiprocessing ability, you can enable it by uncommenting the old code.

---

You can also view this notebook on [Kaggle](https://www.kaggle.com/aadimator/coconic) and download the converted data from there directly.
