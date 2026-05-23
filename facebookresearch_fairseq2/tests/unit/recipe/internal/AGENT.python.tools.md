# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/recipe/internal/test_lr_schedulers.py

Prompts

```
['create a CosineAnnealingLR scheduler with cycle length, warmup steps, and start and final learning rates', 'create a PolynomialDecayLR scheduler with warmup steps, decay power, and start and final learning rates', 'create a TriStageLR scheduler with stage ratios and start and final learning rate scales', 'create a MyleLR scheduler with warmup steps and a start learning rate for the optimizer', 'create a NoamLR scheduler with warmup steps for use with an optimizer', 'test the _AdamWFactory.create method with AdamWConfig to build an optimizer with correct param groups', 'test the _AdamWFactory.create method with AdamWGroupConfig regex patterns to create multiple optimizer param groups', 'test the _AdamWFactory.create method with auto, foreach, fused, and naive impl modes', 'test the _AdafactorFactory.create method with AdafactorConfig to build an optimizer with correct param groups', 'test the _AdafactorFactory.create method with AdafactorGroupConfig regex patterns to create multiple optimizer param groups']
```

Usage

```
{'create_cosine_annealing_scheduler': 'create a CosineAnnealingLR scheduler with cycle length, warmup steps, and start and final learning rates', 'create_polynomial_decay_scheduler': 'create a PolynomialDecayLR scheduler with warmup steps, decay power, and start and final learning rates', 'create_tri_stage_scheduler': 'create a TriStageLR scheduler with stage ratios and start and final learning rate scales', 'create_myle_scheduler': 'create a MyleLR scheduler with warmup steps and a start learning rate for the optimizer', 'create_noam_scheduler': 'create a NoamLR scheduler with warmup steps for use with an optimizer'}
```

## File: facebookresearch_fairseq2/tests/unit/recipe/internal/test_optim.py

Prompts

```
['create a CosineAnnealingLR scheduler with cycle length, warmup steps, and start and final learning rates', 'create a PolynomialDecayLR scheduler with warmup steps, decay power, and start and final learning rates', 'create a TriStageLR scheduler with stage ratios and start and final learning rate scales', 'create a MyleLR scheduler with warmup steps and a start learning rate for the optimizer', 'create a NoamLR scheduler with warmup steps for use with an optimizer', 'test the _AdamWFactory.create method with AdamWConfig to build an optimizer with correct param groups', 'test the _AdamWFactory.create method with AdamWGroupConfig regex patterns to create multiple optimizer param groups', 'test the _AdamWFactory.create method with auto, foreach, fused, and naive impl modes', 'test the _AdafactorFactory.create method with AdafactorConfig to build an optimizer with correct param groups', 'test the _AdafactorFactory.create method with AdafactorGroupConfig regex patterns to create multiple optimizer param groups']
```

Usage

```
{'test_AdamWFactory_create': 'test the _AdamWFactory.create method with AdamWConfig to build an optimizer with correct param groups', 'test_AdamWFactory_create_with_groups': 'test the _AdamWFactory.create method with AdamWGroupConfig regex patterns to create multiple optimizer param groups', 'test_AdamWFactory_parametrized_impl': 'test the _AdamWFactory.create method with auto, foreach, fused, and naive impl modes', 'test_AdafactorFactory_create': 'test the _AdafactorFactory.create method with AdafactorConfig to build an optimizer with correct param groups', 'test_AdafactorFactory_create_with_groups': 'test the _AdafactorFactory.create method with AdafactorGroupConfig regex patterns to create multiple optimizer param groups'}
```

