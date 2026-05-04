# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/eft/smplify/losses.py

Prompts

```
['build a SMPL body fitting loss with perspective projection, pose prior, and angle prior terms', 'build a body fitting loss using weak perspective projection instead of full perspective camera model', 'test the Geman-McClure error function for robust reprojection error computation with configurable sigma', 'review the angle prior function that penalizes unnatural knee and elbow bending in SMPL pose', 'refactor the camera fitting loss to optimize camera translation using hip and shoulder joint reprojection', 'create a pose prior object using create_prior with type gmm, l2, angle, or none', 'build a SMPLifyAnglePrior module that penalizes elbow and knee joint angles away from 90 degrees', 'build a L2Prior module that returns the sum of squared values for pose regularization', 'build a MaxMixturePrior module that loads a GMM pickle file and computes negative log-likelihood for poses', 'review the MaxMixturePrior merged_log_likelihood method that computes batched negative log-likelihood using precision matrices', 'run SMPLify body fitting to optimize 3D mesh pose and shape from 2D keypoints', 'run SMPLify body fitting with weak perspective camera projection and optional debug visualization', 'build an SMPLify optimizer instance with configurable step size, batch size, and iteration count', 'test the SMPLify module by computing reprojection loss for given pose and camera parameters', 'test the SMPLify module by computing GMM pose prior loss for given pose and beta parameters']
```

Usage

```
{'build_body_fitting_loss': 'build a SMPL body fitting loss with perspective projection, pose prior, and angle prior terms', 'build_weakperspective_body_fitting': 'build a body fitting loss using weak perspective projection instead of full perspective camera model', 'test_gmof': 'test the Geman-McClure error function for robust reprojection error computation with configurable sigma', 'review_angle_prior': 'review the angle prior function that penalizes unnatural knee and elbow bending in SMPL pose', 'refactor_camera_fitting_loss': 'refactor the camera fitting loss to optimize camera translation using hip and shoulder joint reprojection'}
```

## File: facebookresearch_eft/eft/smplify/prior.py

Prompts

```
['build a SMPL body fitting loss with perspective projection, pose prior, and angle prior terms', 'build a body fitting loss using weak perspective projection instead of full perspective camera model', 'test the Geman-McClure error function for robust reprojection error computation with configurable sigma', 'review the angle prior function that penalizes unnatural knee and elbow bending in SMPL pose', 'refactor the camera fitting loss to optimize camera translation using hip and shoulder joint reprojection', 'create a pose prior object using create_prior with type gmm, l2, angle, or none', 'build a SMPLifyAnglePrior module that penalizes elbow and knee joint angles away from 90 degrees', 'build a L2Prior module that returns the sum of squared values for pose regularization', 'build a MaxMixturePrior module that loads a GMM pickle file and computes negative log-likelihood for poses', 'review the MaxMixturePrior merged_log_likelihood method that computes batched negative log-likelihood using precision matrices', 'run SMPLify body fitting to optimize 3D mesh pose and shape from 2D keypoints', 'run SMPLify body fitting with weak perspective camera projection and optional debug visualization', 'build an SMPLify optimizer instance with configurable step size, batch size, and iteration count', 'test the SMPLify module by computing reprojection loss for given pose and camera parameters', 'test the SMPLify module by computing GMM pose prior loss for given pose and beta parameters']
```

Usage

```
{'create_prior_factory': 'create a pose prior object using create_prior with type gmm, l2, angle, or none', 'build_angle_prior': 'build a SMPLifyAnglePrior module that penalizes elbow and knee joint angles away from 90 degrees', 'build_l2_prior': 'build a L2Prior module that returns the sum of squared values for pose regularization', 'build_gmm_prior': 'build a MaxMixturePrior module that loads a GMM pickle file and computes negative log-likelihood for poses', 'review_merged_log_likelihood': 'review the MaxMixturePrior merged_log_likelihood method that computes batched negative log-likelihood using precision matrices'}
```

## File: facebookresearch_eft/eft/smplify/smplify.py

Prompts

```
['build a SMPL body fitting loss with perspective projection, pose prior, and angle prior terms', 'build a body fitting loss using weak perspective projection instead of full perspective camera model', 'test the Geman-McClure error function for robust reprojection error computation with configurable sigma', 'review the angle prior function that penalizes unnatural knee and elbow bending in SMPL pose', 'refactor the camera fitting loss to optimize camera translation using hip and shoulder joint reprojection', 'create a pose prior object using create_prior with type gmm, l2, angle, or none', 'build a SMPLifyAnglePrior module that penalizes elbow and knee joint angles away from 90 degrees', 'build a L2Prior module that returns the sum of squared values for pose regularization', 'build a MaxMixturePrior module that loads a GMM pickle file and computes negative log-likelihood for poses', 'review the MaxMixturePrior merged_log_likelihood method that computes batched negative log-likelihood using precision matrices', 'run SMPLify body fitting to optimize 3D mesh pose and shape from 2D keypoints', 'run SMPLify body fitting with weak perspective camera projection and optional debug visualization', 'build an SMPLify optimizer instance with configurable step size, batch size, and iteration count', 'test the SMPLify module by computing reprojection loss for given pose and camera parameters', 'test the SMPLify module by computing GMM pose prior loss for given pose and beta parameters']
```

Usage

```
{'run_SMPLify_call': 'run SMPLify body fitting to optimize 3D mesh pose and shape from 2D keypoints', 'run_SMPLify_run_withWeakProj': 'run SMPLify body fitting with weak perspective camera projection and optional debug visualization', 'build_SMPLify_init': 'build an SMPLify optimizer instance with configurable step size, batch size, and iteration count', 'test_SMPLify_get_fitting_loss': 'test the SMPLify module by computing reprojection loss for given pose and camera parameters', 'test_SMPLify_get_prior_loss': 'test the SMPLify module by computing GMM pose prior loss for given pose and beta parameters'}
```

