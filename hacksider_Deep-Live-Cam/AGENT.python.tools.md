# Agent Python Tools

- repo: hacksider/Deep-Live-Cam
- repo_uri: https://github.com/hacksider/Deep-Live-Cam

## File: hacksider_Deep-Live-Cam/benchmark_pipeline.py

Prompts

```
['run the standalone pipeline benchmark that captures 200 webcam frames and measures per-stage face swap timing and effective FPS', 'test the face swap pipeline by running 200 frames through detection, ONNX inference, and paste-back stages with per-stage timing', 'benchmark face detection performance by running detection every 3rd frame with cached face tracking across 200 webcam frames', 'review the _fast_paste_back face swap compositing function used in the benchmark pipeline for in-place frame modification', 'summarize the capture thread implementation that reads webcam frames into a bounded queue with overflow handling', 'review the tkinter_fix.py apply_patch function that monkey patches tkinter.Tk.__init__ to define the missing ::tk::ScreenChanged Tcl procedure', 'create a monkey patch for tkinter.Tk.__init__ that defines a missing ::tk::ScreenChanged procedure to fix Tk deprecation warnings', 'run the tkinter_fix.py module to auto-apply the TkScreenChanged monkey patch on import', 'refactor the apply_patch function in tkinter_fix.py to support custom Tcl procedure definitions beyond ::tk::ScreenChanged', 'test the tkinter_fix.py apply_patch function to verify it patches tkinter.Tk.__init__ and defines ::tk::ScreenChanged']
```

Usage

```
{'run_benchmark_pipeline': 'run the standalone pipeline benchmark that captures 200 webcam frames and measures per-stage face swap timing and effective FPS', 'test_face_swap_pipeline': 'test the face swap pipeline by running 200 frames through detection, ONNX inference, and paste-back stages with per-stage timing', 'benchmark_face_detection': 'benchmark face detection performance by running detection every 3rd frame with cached face tracking across 200 webcam frames', 'review_fast_paste_back': 'review the _fast_paste_back face swap compositing function used in the benchmark pipeline for in-place frame modification', 'summarize_capture_thread': 'summarize the capture thread implementation that reads webcam frames into a bounded queue with overflow handling'}
```

## File: hacksider_Deep-Live-Cam/tkinter_fix.py

Prompts

```
['run the standalone pipeline benchmark that captures 200 webcam frames and measures per-stage face swap timing and effective FPS', 'test the face swap pipeline by running 200 frames through detection, ONNX inference, and paste-back stages with per-stage timing', 'benchmark face detection performance by running detection every 3rd frame with cached face tracking across 200 webcam frames', 'review the _fast_paste_back face swap compositing function used in the benchmark pipeline for in-place frame modification', 'summarize the capture thread implementation that reads webcam frames into a bounded queue with overflow handling', 'review the tkinter_fix.py apply_patch function that monkey patches tkinter.Tk.__init__ to define the missing ::tk::ScreenChanged Tcl procedure', 'create a monkey patch for tkinter.Tk.__init__ that defines a missing ::tk::ScreenChanged procedure to fix Tk deprecation warnings', 'run the tkinter_fix.py module to auto-apply the TkScreenChanged monkey patch on import', 'refactor the apply_patch function in tkinter_fix.py to support custom Tcl procedure definitions beyond ::tk::ScreenChanged', 'test the tkinter_fix.py apply_patch function to verify it patches tkinter.Tk.__init__ and defines ::tk::ScreenChanged']
```

Usage

```
{'review_apply_patch': 'review the tkinter_fix.py apply_patch function that monkey patches tkinter.Tk.__init__ to define the missing ::tk::ScreenChanged Tcl procedure', 'create_tkinter_patch': 'create a monkey patch for tkinter.Tk.__init__ that defines a missing ::tk::ScreenChanged procedure to fix Tk deprecation warnings', 'run_tkinter_fix': 'run the tkinter_fix.py module to auto-apply the TkScreenChanged monkey patch on import', 'refactor_apply_patch': 'refactor the apply_patch function in tkinter_fix.py to support custom Tcl procedure definitions beyond ::tk::ScreenChanged', 'test_apply_patch': 'test the tkinter_fix.py apply_patch function to verify it patches tkinter.Tk.__init__ and defines ::tk::ScreenChanged'}
```

