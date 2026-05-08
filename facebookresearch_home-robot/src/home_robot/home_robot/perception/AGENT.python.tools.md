# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/perception/constants.py

Prompts

```
['create an HM3DtoCOCOIndoor mapping to convert HM3D goal IDs to COCO indoor category IDs and names', 'create an HM3DtoLongTailIndoor mapping to convert HM3D goal IDs to long-tail indoor category IDs', 'create a RearrangeDETICCategories mapping with custom category indexes for open-vocabulary visual manipulation tasks', 'create a LanguageNavCategories mapping to convert semantic annotations to language navigation category IDs', 'create a FloorplannertoMukulIndoor mapping to convert Floorplanner scene IDs to Mukul 33 indoor category IDs', 'initialize a Midas depth estimation model on a given device using the DPT Beit Large 512 weights', 'run depth_estimate on an RGB image and ground truth depth to get adjusted depth, MSE, and mean error', 'review the Midas class and its depth estimation workflow using the MiDaS DPT Beit Large model', 'refactor the depth_estimate method to handle torch Tensor inputs by converting them to numpy arrays', 'summarize the depth_estimate method which solves a linear system to adjust MiDaS predictions against observed depth', 'create a semantic sensor with OvmmPerception using DETIC or GroundedSAM for scene segmentation and labeling', 'build a vocabulary from object and receptacle category ID-to-name mappings for semantic segmentation', 'read a JSON category map file and extract object and receptacle name-to-ID mappings', 'set the active vocabulary by ID on an OvmmPerception instance to switch segmentation classes at runtime', 'run the segmentation model on an Observations object and update it with semantic labels']
```

Usage

```
{'create_HM3DtoCOCOIndoor_mapping': 'create an HM3DtoCOCOIndoor mapping to convert HM3D goal IDs to COCO indoor category IDs and names', 'create_HM3DtoLongTailIndoor_mapping': 'create an HM3DtoLongTailIndoor mapping to convert HM3D goal IDs to long-tail indoor category IDs', 'create_RearrangeDETICCategories_mapping': 'create a RearrangeDETICCategories mapping with custom category indexes for open-vocabulary visual manipulation tasks', 'create_LanguageNavCategories_mapping': 'create a LanguageNavCategories mapping to convert semantic annotations to language navigation category IDs', 'create_FloorplannertoMukulIndoor_mapping': 'create a FloorplannertoMukulIndoor mapping to convert Floorplanner scene IDs to Mukul 33 indoor category IDs'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/perception/midas.py

Prompts

```
['create an HM3DtoCOCOIndoor mapping to convert HM3D goal IDs to COCO indoor category IDs and names', 'create an HM3DtoLongTailIndoor mapping to convert HM3D goal IDs to long-tail indoor category IDs', 'create a RearrangeDETICCategories mapping with custom category indexes for open-vocabulary visual manipulation tasks', 'create a LanguageNavCategories mapping to convert semantic annotations to language navigation category IDs', 'create a FloorplannertoMukulIndoor mapping to convert Floorplanner scene IDs to Mukul 33 indoor category IDs', 'initialize a Midas depth estimation model on a given device using the DPT Beit Large 512 weights', 'run depth_estimate on an RGB image and ground truth depth to get adjusted depth, MSE, and mean error', 'review the Midas class and its depth estimation workflow using the MiDaS DPT Beit Large model', 'refactor the depth_estimate method to handle torch Tensor inputs by converting them to numpy arrays', 'summarize the depth_estimate method which solves a linear system to adjust MiDaS predictions against observed depth', 'create a semantic sensor with OvmmPerception using DETIC or GroundedSAM for scene segmentation and labeling', 'build a vocabulary from object and receptacle category ID-to-name mappings for semantic segmentation', 'read a JSON category map file and extract object and receptacle name-to-ID mappings', 'set the active vocabulary by ID on an OvmmPerception instance to switch segmentation classes at runtime', 'run the segmentation model on an Observations object and update it with semantic labels']
```

Usage

```
{'init_midas_model': 'initialize a Midas depth estimation model on a given device using the DPT Beit Large 512 weights', 'run_depth_estimate': 'run depth_estimate on an RGB image and ground truth depth to get adjusted depth, MSE, and mean error', 'review_Midas_class': 'review the Midas class and its depth estimation workflow using the MiDaS DPT Beit Large model', 'refactor_depth_estimate_tensor_handling': 'refactor the depth_estimate method to handle torch Tensor inputs by converting them to numpy arrays', 'summarize_depth_adjustment': 'summarize the depth_estimate method which solves a linear system to adjust MiDaS predictions against observed depth'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/perception/wrapper.py

Prompts

```
['create an HM3DtoCOCOIndoor mapping to convert HM3D goal IDs to COCO indoor category IDs and names', 'create an HM3DtoLongTailIndoor mapping to convert HM3D goal IDs to long-tail indoor category IDs', 'create a RearrangeDETICCategories mapping with custom category indexes for open-vocabulary visual manipulation tasks', 'create a LanguageNavCategories mapping to convert semantic annotations to language navigation category IDs', 'create a FloorplannertoMukulIndoor mapping to convert Floorplanner scene IDs to Mukul 33 indoor category IDs', 'initialize a Midas depth estimation model on a given device using the DPT Beit Large 512 weights', 'run depth_estimate on an RGB image and ground truth depth to get adjusted depth, MSE, and mean error', 'review the Midas class and its depth estimation workflow using the MiDaS DPT Beit Large model', 'refactor the depth_estimate method to handle torch Tensor inputs by converting them to numpy arrays', 'summarize the depth_estimate method which solves a linear system to adjust MiDaS predictions against observed depth', 'create a semantic sensor with OvmmPerception using DETIC or GroundedSAM for scene segmentation and labeling', 'build a vocabulary from object and receptacle category ID-to-name mappings for semantic segmentation', 'read a JSON category map file and extract object and receptacle name-to-ID mappings', 'set the active vocabulary by ID on an OvmmPerception instance to switch segmentation classes at runtime', 'run the segmentation model on an Observations object and update it with semantic labels']
```

Usage

```
{'create_semantic_sensor': 'create a semantic sensor with OvmmPerception using DETIC or GroundedSAM for scene segmentation and labeling', 'build_vocab_from_category_map': 'build a vocabulary from object and receptacle category ID-to-name mappings for semantic segmentation', 'read_category_map_file': 'read a JSON category map file and extract object and receptacle name-to-ID mappings', 'set_vocabulary_OvmmPerception': 'set the active vocabulary by ID on an OvmmPerception instance to switch segmentation classes at runtime', 'predict_OvmmPerception': 'run the segmentation model on an Observations object and update it with semantic labels'}
```

