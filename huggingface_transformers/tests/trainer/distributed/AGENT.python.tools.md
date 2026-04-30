# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/trainer/distributed/test_trainer_distributed_ddp.py

Prompts

```
['test the DDPCommandsMixin.get_torchrun_cmd method to build torchrun distributed launch commands', 'test the DDPCommandsMixin.get_accelerate_cmd method to build accelerate launch distributed commands', 'test the test_loss_averaging method to verify DDP loss averaging across single-GPU and multi-GPU runs', 'test the test_torchrun_accelerate_env_parity method to verify torchrun and accelerate produce identical distributed environment variables', 'test the TestTrainerDistributedDDPCommon.test_training method to run DDP training with pure dtype configurations', 'test the FSDP config parsing for accelerate with sharding strategy and dtype parameters', 'test the torchrun-style FSDP config parsing with --fsdp and --fsdp_config flags', 'test FSDP non-rank-0 weight initialization moves meta tensors to CPU without re-initializing parameters', 'test that torchrun and accelerate launch produce the same FSDP1 distributed environment', 'test that torchrun and accelerate launch produce the same FSDP2 distributed environment', 'test FSDP distributed training with pure dtype across fsdp1 and fsdp2 versions', 'test FSDP distributed training with mixed precision using bf16 or fp16', 'test FSDP checkpoint resume with FULL_STATE_DICT and SHARDED_STATE_DICT', 'test that context parallelism produces equivalent losses to non-CP FSDP training', 'test FSDP model generation using accelerate launch with fsdp config']
```

Usage

```
{'test_DDPCommandsMixin_get_torchrun_cmd': 'test the DDPCommandsMixin.get_torchrun_cmd method to build torchrun distributed launch commands', 'test_DDPCommandsMixin_get_accelerate_cmd': 'test the DDPCommandsMixin.get_accelerate_cmd method to build accelerate launch distributed commands', 'test_TestTrainerDistributedDDP_test_loss_averaging': 'test the test_loss_averaging method to verify DDP loss averaging across single-GPU and multi-GPU runs', 'test_TestTrainerDistributedDDP_test_torchrun_accelerate_env_parity': 'test the test_torchrun_accelerate_env_parity method to verify torchrun and accelerate produce identical distributed environment variables', 'test_TestTrainerDistributedDDPCommon_test_training': 'test the TestTrainerDistributedDDPCommon.test_training method to run DDP training with pure dtype configurations'}
```

## File: huggingface_transformers/tests/trainer/distributed/test_trainer_distributed_fsdp.py

Prompts

```
['test the DDPCommandsMixin.get_torchrun_cmd method to build torchrun distributed launch commands', 'test the DDPCommandsMixin.get_accelerate_cmd method to build accelerate launch distributed commands', 'test the test_loss_averaging method to verify DDP loss averaging across single-GPU and multi-GPU runs', 'test the test_torchrun_accelerate_env_parity method to verify torchrun and accelerate produce identical distributed environment variables', 'test the TestTrainerDistributedDDPCommon.test_training method to run DDP training with pure dtype configurations', 'test the FSDP config parsing for accelerate with sharding strategy and dtype parameters', 'test the torchrun-style FSDP config parsing with --fsdp and --fsdp_config flags', 'test FSDP non-rank-0 weight initialization moves meta tensors to CPU without re-initializing parameters', 'test that torchrun and accelerate launch produce the same FSDP1 distributed environment', 'test that torchrun and accelerate launch produce the same FSDP2 distributed environment', 'test FSDP distributed training with pure dtype across fsdp1 and fsdp2 versions', 'test FSDP distributed training with mixed precision using bf16 or fp16', 'test FSDP checkpoint resume with FULL_STATE_DICT and SHARDED_STATE_DICT', 'test that context parallelism produces equivalent losses to non-CP FSDP training', 'test FSDP model generation using accelerate launch with fsdp config']
```

Usage

```
{'test_FSDPConfig_accelerate_fsdp_config': 'test the FSDP config parsing for accelerate with sharding strategy and dtype parameters', 'test_FSDPConfig_torchrun_fsdp_config': 'test the torchrun-style FSDP config parsing with --fsdp and --fsdp_config flags', 'test_InitializeMissingKeys_fsdp_non_rank0_end_to_end_no_reinit': 'test FSDP non-rank-0 weight initialization moves meta tensors to CPU without re-initializing parameters', 'test_TrainerDistributedFSDP_torchrun_accelerate_fsdp1_env_parity': 'test that torchrun and accelerate launch produce the same FSDP1 distributed environment', 'test_TrainerDistributedFSDP_torchrun_accelerate_fsdp2_env_parity': 'test that torchrun and accelerate launch produce the same FSDP2 distributed environment', 'test_TrainerDistributedFSDPCommon_training': 'test FSDP distributed training with pure dtype across fsdp1 and fsdp2 versions', 'test_TrainerDistributedFSDPCommon_training_mixed_precision': 'test FSDP distributed training with mixed precision using bf16 or fp16', 'test_TrainerDistributedFSDPCommon_training_and_can_resume_normally': 'test FSDP checkpoint resume with FULL_STATE_DICT and SHARDED_STATE_DICT', 'test_TrainerDistributedFSDPCommon_cp_equivalence': 'test that context parallelism produces equivalent losses to non-CP FSDP training', 'test_TrainerDistributedFSDPCommon_fsdp_generate': 'test FSDP model generation using accelerate launch with fsdp config'}
```

