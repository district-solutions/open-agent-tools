# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/tests/core/remotable_test.py

Prompts

```
['test the RemotableAdder class by calling its remote add method via a server and client', 'test the Server class by adding multiple RemotableAdder services and verifying remote calls', 'test the remote_method decorator by invoking a decorated add method through a remote client', 'test remote_utils.make_remote by creating client proxies for RemotableAdder instances and calling add', 'test the Remotable base class by verifying that each instance has a unique identifier', 'test the ReplayBuffer extend method by adding unstacked transition data and verifying returned keys', 'test the ReplayBuffer extend method with stacked tensor data and verify correct key assignment', 'test the ReplayBuffer sample method to verify uniform sampling probabilities and replacement behavior', 'test the ReplayBuffer clear method to verify it empties the buffer and allows re-extending', 'test the PrioritizedSampler update method to verify priority changes affect sampling probabilities', 'test the RMSRescaler class to rescale tensors by root mean square normalization', 'test the MomentsRescaler class to rescale tensors by mean and standard deviation', 'test the SqrtRescaler class to rescale tensors using a signed square root transform', 'run the unittest suite for all rescaler classes including RMS, Moments, and Sqrt rescalers', 'review the recover method across RMSRescaler, MomentsRescaler, and SqrtRescaler for inverse rescaling']
```

Usage

```
{'test_RemotableAdder': 'test the RemotableAdder class by calling its remote add method via a server and client', 'test_Server_add_service': 'test the Server class by adding multiple RemotableAdder services and verifying remote calls', 'test_remote_method_decorator': 'test the remote_method decorator by invoking a decorated add method through a remote client', 'test_make_remote': 'test remote_utils.make_remote by creating client proxies for RemotableAdder instances and calling add', 'test_Remotable_identifier': 'test the Remotable base class by verifying that each instance has a unique identifier'}
```

## File: facebookresearch_rlmeta/tests/core/replay_buffer_test.py

Prompts

```
['test the RemotableAdder class by calling its remote add method via a server and client', 'test the Server class by adding multiple RemotableAdder services and verifying remote calls', 'test the remote_method decorator by invoking a decorated add method through a remote client', 'test remote_utils.make_remote by creating client proxies for RemotableAdder instances and calling add', 'test the Remotable base class by verifying that each instance has a unique identifier', 'test the ReplayBuffer extend method by adding unstacked transition data and verifying returned keys', 'test the ReplayBuffer extend method with stacked tensor data and verify correct key assignment', 'test the ReplayBuffer sample method to verify uniform sampling probabilities and replacement behavior', 'test the ReplayBuffer clear method to verify it empties the buffer and allows re-extending', 'test the PrioritizedSampler update method to verify priority changes affect sampling probabilities', 'test the RMSRescaler class to rescale tensors by root mean square normalization', 'test the MomentsRescaler class to rescale tensors by mean and standard deviation', 'test the SqrtRescaler class to rescale tensors using a signed square root transform', 'run the unittest suite for all rescaler classes including RMS, Moments, and Sqrt rescalers', 'review the recover method across RMSRescaler, MomentsRescaler, and SqrtRescaler for inverse rescaling']
```

Usage

```
{'test_ReplayBuffer_extend': 'test the ReplayBuffer extend method by adding unstacked transition data and verifying returned keys', 'test_ReplayBuffer_extend_stacked': 'test the ReplayBuffer extend method with stacked tensor data and verify correct key assignment', 'test_ReplayBuffer_sample': 'test the ReplayBuffer sample method to verify uniform sampling probabilities and replacement behavior', 'test_ReplayBuffer_clear': 'test the ReplayBuffer clear method to verify it empties the buffer and allows re-extending', 'test_PrioritizedReplayBuffer_update': 'test the PrioritizedSampler update method to verify priority changes affect sampling probabilities'}
```

## File: facebookresearch_rlmeta/tests/core/rescalers_test.py

Prompts

```
['test the RemotableAdder class by calling its remote add method via a server and client', 'test the Server class by adding multiple RemotableAdder services and verifying remote calls', 'test the remote_method decorator by invoking a decorated add method through a remote client', 'test remote_utils.make_remote by creating client proxies for RemotableAdder instances and calling add', 'test the Remotable base class by verifying that each instance has a unique identifier', 'test the ReplayBuffer extend method by adding unstacked transition data and verifying returned keys', 'test the ReplayBuffer extend method with stacked tensor data and verify correct key assignment', 'test the ReplayBuffer sample method to verify uniform sampling probabilities and replacement behavior', 'test the ReplayBuffer clear method to verify it empties the buffer and allows re-extending', 'test the PrioritizedSampler update method to verify priority changes affect sampling probabilities', 'test the RMSRescaler class to rescale tensors by root mean square normalization', 'test the MomentsRescaler class to rescale tensors by mean and standard deviation', 'test the SqrtRescaler class to rescale tensors using a signed square root transform', 'run the unittest suite for all rescaler classes including RMS, Moments, and Sqrt rescalers', 'review the recover method across RMSRescaler, MomentsRescaler, and SqrtRescaler for inverse rescaling']
```

Usage

```
{'test_rms_rescaler': 'test the RMSRescaler class to rescale tensors by root mean square normalization', 'test_moments_rescaler': 'test the MomentsRescaler class to rescale tensors by mean and standard deviation', 'test_sqrt_rescaler': 'test the SqrtRescaler class to rescale tensors using a signed square root transform', 'run_rescaler_tests': 'run the unittest suite for all rescaler classes including RMS, Moments, and Sqrt rescalers', 'review_rescaler_recover': 'review the recover method across RMSRescaler, MomentsRescaler, and SqrtRescaler for inverse rescaling'}
```

