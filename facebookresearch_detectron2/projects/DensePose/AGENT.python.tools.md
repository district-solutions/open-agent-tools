# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/DensePose/apply_net.py

Prompts

```
['run the apply_net dump action to save DensePose model outputs to a pickle file', 'run the apply_net show action to visualize DensePose results with contour or segmentation overlays', 'run the apply_net show action with texture atlas to visualize IUV texture transfer on images', 'review the DumpAction class that extracts DensePose predictions and saves them to a pickle file', 'review the ShowAction class that creates visualizers and saves annotated DensePose result images', 'run the query_db CLI with the print action to output selected dataset entries to stdout', 'run the query_db CLI with the show action to visualize DensePose annotations on images', 'run an EntrywiseAction to iterate over dataset entries filtered by an EntrySelector', 'review the ShowAction VISUALIZERS dict to see available DensePose visualization types like dp_segm and dp_pts', 'review the register_action decorator that auto-registers action classes into the _ACTION_REGISTRY dict', 'parse the detectron2 version string from its __init__.py file using regex', 'install the detectron2-densepose package with all required dependencies via pip', 'run the DensePose training script with a config file and GPU count via command line', 'run the DensePose evaluation only mode using a pre-trained model weights file', 'build a DensePose model from config using Trainer.build_model for evaluation or training', 'resume a DensePose training run from a checkpoint using DensePoseCheckpointer', 'setup a DensePose config by merging a config file and command line options']
```

Usage

```
{'run_densepose_dump': 'run the apply_net dump action to save DensePose model outputs to a pickle file', 'run_densepose_show': 'run the apply_net show action to visualize DensePose results with contour or segmentation overlays', 'run_densepose_texture_visualization': 'run the apply_net show action with texture atlas to visualize IUV texture transfer on images', 'review_dump_action': 'review the DumpAction class that extracts DensePose predictions and saves them to a pickle file', 'review_show_action': 'review the ShowAction class that creates visualizers and saves annotated DensePose result images'}
```

## File: facebookresearch_detectron2/projects/DensePose/query_db.py

Prompts

```
['run the apply_net dump action to save DensePose model outputs to a pickle file', 'run the apply_net show action to visualize DensePose results with contour or segmentation overlays', 'run the apply_net show action with texture atlas to visualize IUV texture transfer on images', 'review the DumpAction class that extracts DensePose predictions and saves them to a pickle file', 'review the ShowAction class that creates visualizers and saves annotated DensePose result images', 'run the query_db CLI with the print action to output selected dataset entries to stdout', 'run the query_db CLI with the show action to visualize DensePose annotations on images', 'run an EntrywiseAction to iterate over dataset entries filtered by an EntrySelector', 'review the ShowAction VISUALIZERS dict to see available DensePose visualization types like dp_segm and dp_pts', 'review the register_action decorator that auto-registers action classes into the _ACTION_REGISTRY dict', 'parse the detectron2 version string from its __init__.py file using regex', 'install the detectron2-densepose package with all required dependencies via pip', 'run the DensePose training script with a config file and GPU count via command line', 'run the DensePose evaluation only mode using a pre-trained model weights file', 'build a DensePose model from config using Trainer.build_model for evaluation or training', 'resume a DensePose training run from a checkpoint using DensePoseCheckpointer', 'setup a DensePose config by merging a config file and command line options']
```

Usage

```
{'run_query_db_print': 'run the query_db CLI with the print action to output selected dataset entries to stdout', 'run_query_db_show': 'run the query_db CLI with the show action to visualize DensePose annotations on images', 'run_entrywise_action_execute': 'run an EntrywiseAction to iterate over dataset entries filtered by an EntrySelector', 'review_showaction_visualizers': 'review the ShowAction VISUALIZERS dict to see available DensePose visualization types like dp_segm and dp_pts', 'review_register_action_decorator': 'review the register_action decorator that auto-registers action classes into the _ACTION_REGISTRY dict'}
```

## File: facebookresearch_detectron2/projects/DensePose/setup.py

Prompts

```
['run the apply_net dump action to save DensePose model outputs to a pickle file', 'run the apply_net show action to visualize DensePose results with contour or segmentation overlays', 'run the apply_net show action with texture atlas to visualize IUV texture transfer on images', 'review the DumpAction class that extracts DensePose predictions and saves them to a pickle file', 'review the ShowAction class that creates visualizers and saves annotated DensePose result images', 'run the query_db CLI with the print action to output selected dataset entries to stdout', 'run the query_db CLI with the show action to visualize DensePose annotations on images', 'run an EntrywiseAction to iterate over dataset entries filtered by an EntrySelector', 'review the ShowAction VISUALIZERS dict to see available DensePose visualization types like dp_segm and dp_pts', 'review the register_action decorator that auto-registers action classes into the _ACTION_REGISTRY dict', 'parse the detectron2 version string from its __init__.py file using regex', 'install the detectron2-densepose package with all required dependencies via pip', 'run the DensePose training script with a config file and GPU count via command line', 'run the DensePose evaluation only mode using a pre-trained model weights file', 'build a DensePose model from config using Trainer.build_model for evaluation or training', 'resume a DensePose training run from a checkpoint using DensePoseCheckpointer', 'setup a DensePose config by merging a config file and command line options']
```

Usage

```
{'get_detectron2_current_version': 'parse the detectron2 version string from its __init__.py file using regex', 'setup_detectron2_densepose': 'install the detectron2-densepose package with all required dependencies via pip'}
```

## File: facebookresearch_detectron2/projects/DensePose/train_net.py

Prompts

```
['run the apply_net dump action to save DensePose model outputs to a pickle file', 'run the apply_net show action to visualize DensePose results with contour or segmentation overlays', 'run the apply_net show action with texture atlas to visualize IUV texture transfer on images', 'review the DumpAction class that extracts DensePose predictions and saves them to a pickle file', 'review the ShowAction class that creates visualizers and saves annotated DensePose result images', 'run the query_db CLI with the print action to output selected dataset entries to stdout', 'run the query_db CLI with the show action to visualize DensePose annotations on images', 'run an EntrywiseAction to iterate over dataset entries filtered by an EntrySelector', 'review the ShowAction VISUALIZERS dict to see available DensePose visualization types like dp_segm and dp_pts', 'review the register_action decorator that auto-registers action classes into the _ACTION_REGISTRY dict', 'parse the detectron2 version string from its __init__.py file using regex', 'install the detectron2-densepose package with all required dependencies via pip', 'run the DensePose training script with a config file and GPU count via command line', 'run the DensePose evaluation only mode using a pre-trained model weights file', 'build a DensePose model from config using Trainer.build_model for evaluation or training', 'resume a DensePose training run from a checkpoint using DensePoseCheckpointer', 'setup a DensePose config by merging a config file and command line options']
```

Usage

```
{'run_densepose_training': 'run the DensePose training script with a config file and GPU count via command line', 'run_densepose_evaluation': 'run the DensePose evaluation only mode using a pre-trained model weights file', 'build_densepose_model': 'build a DensePose model from config using Trainer.build_model for evaluation or training', 'resume_densepose_training': 'resume a DensePose training run from a checkpoint using DensePoseCheckpointer', 'setup_densepose_config': 'setup a DensePose config by merging a config file and command line options'}
```

