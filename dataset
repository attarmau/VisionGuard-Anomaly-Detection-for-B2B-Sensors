# Please Download from: https://www.mvtec.com/company/research/datasets/mvtec-ad

import fiftyone as fo # base library and app
import fiftyone.brain as fob # ML methods
import fiftyone.zoo as foz # zoo datasets and models
from fiftyone import ViewField as F # helper for defining views
import fiftyone.utils.huggingface as fouh # Hugging Face integration

dataset = fouh.load_from_hub("Voxel51/mvtec-ad", persistent=True, overwrite=True)

from anomalib.data import MVTec
datamodule = MVTec()
