# Agent Python Tools

- repo: facebookresearch/body2hands
- repo_uri: https://github.com/facebookresearch/body2hands

## File: facebookresearch_body2hands/visualization/POF/nets/CPM.py

Prompts

```
['initialize a CPM network by loading weights from a numpy .npy file into a TensorFlow session', 'initialize a CPM network by loading weights from pickle files with optional variable exclusion', 'initialize a CPM network with ImageNet pretrained VGG16 weights from a numpy file', 'run CPM inference without PAF to produce hand keypoint scoremaps across multiple stages', 'run CPM inference with PAF to produce body keypoint scoremaps and part affinity fields']
```

Usage

```
{'init_CPM_from_npy_weights': 'initialize a CPM network by loading weights from a numpy .npy file into a TensorFlow session', 'init_CPM_from_pickle_weights': 'initialize a CPM network by loading weights from pickle files with optional variable exclusion', 'init_CPM_from_vgg_weights': 'initialize a CPM network with ImageNet pretrained VGG16 weights from a numpy file', 'inference_CPM_hand_net': 'run CPM inference without PAF to produce hand keypoint scoremaps across multiple stages', 'inference_CPM_body_net_with_PAF': 'run CPM inference with PAF to produce body keypoint scoremaps and part affinity fields'}
```

