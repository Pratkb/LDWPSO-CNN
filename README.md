# Research of Hyperparameter Optimization (JAIHC)

メタヒューリスティックアルゴリズムを用いてCNNのHyperparameter最適化を行います．  

1. このディレクトリにHyperactiveをcloneして置きます．
2. Hyperactive内のPSOのプログラムをこのディレクトリにある``particle_swarm_optimization.py``と入れ替えます．
3. ``pso_mnist.py``または``cifer10.py``を実行することで，それぞれのデータセットに対してLDWPSOによるCNN最適化を行います．
4. ``pso_mnist_result.py``または``cifar10_result.py``で最適化されたパラメータを入力して実行することで，検証を行います．

## Use data

- MNIST
- CIFAR-10

## file

- lent5.py: Baselineとなる基本的なCNN
- pso_mnist.py: MNISTをLDWPSO CNNで分類
- pso_mnist_result.py: MNIST分類の検証用
- pso_cifar10.py: CIFAR-10をLDWPSO CNNで分類
- pso_cifar10_result.py:CIFAR-10分類の検証用