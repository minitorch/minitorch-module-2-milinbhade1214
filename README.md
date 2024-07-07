[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15359881&assignment_repo_type=AssignmentRepo)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/module.py project/run_manual.py project/run_scalar.py

# Results for training

## Dataset : Simple
Hyperparameter: Num of layers = 4, Learning rate = 0.05
Time per epoch: 0.36
<img src="images/simple_plot.png" width="50%">
<img src="images/simple_graph.png" width="50%">

## Dataset : Diag
Hyperparameter: Num of layers = 4, Learning rate = 0.05
Time per epoch: 0.763s
<img src="images/diag_plot.png" width="50%">
<img src="images/diag_graph.png" width="50%">

## Dataset : Split
Hyperparameter: Num of layers = 16, Learning rate = 0.05
Time per epoch: 2.335s
<img src="images/split_plot.png" width="50%">
<img src="images/split_graph.png" width="50%">

## Dataset : Xor
Hyperparameter: Num of layers = 16, Learning rate = 0.05
Time per epoch: 2.366s
<img src="images/xor_plot.png" width="50%">
<img src="images/xor_graph.png" width="50%">


## Dataset : Circle
Hyperparameter: Num of layers = 12, Learning rate = 0.1
Time per epoch: 1.498s
<img src="images/circle_plot.png" width="50%">
<img src="images/circle_graph.png" width="50%">
<!-- 
## Dataset : Spiral
Hyperparameter: Num of layers = 12, Learning rate = 0.1
Time per epoch: 
<img src="images/spiral_plot.png" width="50%">
<img src="images/spiral_graph.png" width="50%"> -->