# Human-Pose:

**Human Pose Pose Estimation In The Wild**

_Kaio's Development_

[[`densepose.org`](https://densepose.org)] [[`arXiv`](https://arxiv.org/abs/1802.00434)] [[`BibTeX`](#CitingHumanPose)]

Human Pose pose estimation aims at mapping all human pixels of an RGB image to the 3D surface of the human body.
Human-Pose-RCNN is implemented in the [Detectron](https://github.com/facebookresearch/Detectron) framework and is powered by [Caffe2](https://github.com/caffe2/caffe2).

In this repository, I provide the code to train and evaluate Human-Pose-RCNN. I also provide notebooks to visualize the collected Human-Pose-COCO dataset and show the correspondences to the SMPL model.

## Important Note

Human-Pose is now part of Detectron2 (https://github.com/facebookresearch/detectron2/tree/master/projects/HumanPose). There you can find the most up-to-date architectures/models. If you think some feature is missing from there, please post an issue in [Detectron2 Human-Pose](https://github.com/facebookresearch/detectron2/tree/master/projects/HumanPose).

## Installation

Please find installation instructions for Caffe2 and Human-Pose in [`INSTALL.md`](INSTALL.md), a document based on the [Detectron](https://github.com/facebookresearch/Detectron) installation instructions.

## Inference-Training-Testing

After installation, please see [`GETTING_STARTED.md`](GETTING_STARTED.md) for examples of inference, training, and testing.

## Notebooks

### Visualization of Human-Pose-COCO annotations:

See [`notebooks/Human-Pose-COCO-Visualize.ipynb`](notebooks/Human-Pose-COCO-Visualize.ipynb) to visualize the Human-Pose-COCO annotations on the images.

---

### Human-Pose-COCO in 3D:

See [`notebooks/Human-Pose-COCO-on-SMPL.ipynb`](notebooks/Human-Pose-COCO-on-SMPL.ipynb) to localize the Human-Pose-COCO annotations on the 3D template ([`SMPL`](http://smpl.is.tue.mpg.de)) model.

---

### Visualize Human-Pose-RCNN Results:

See [`notebooks/Human-Pose-RCNN-Visualize-Results.ipynb`](notebooks/Human-Pose-RCNN-Visualize-Results.ipynb) to visualize the inferred Human-Pose-RCNN Results.

---

### Human-Pose-RCNN Texture Transfer:

See [`notebooks/Human-Pose-RCNN-Texture-Transfer.ipynb`](notebooks/Human-Pose-RCNN-Texture-Transfer.ipynb) to localize the Human-Pose-COCO annotations on the 3D template ([`SMPL`](http://smpl.is.tue.mpg.de)) model.

## License

This source code is licensed under the license found in the [`LICENSE`](LICENSE) file in the root directory of this source tree.

## <a name="CitingHumanPose"></a>Citing Human-Pose

If you use Human-Pose, please use the following BibTeX entry.

```
  @InProceedings{Guler2018HumanPose,
  title={Human-Pose: Human Pose Pose Estimation In The Wild},
  author={R\{i}za Alp G"uler, Natalia Neverova, Iasonas Kokkinos},
  journal={The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2018}
  }
```
