[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/dongminlee94/meta-learning-for-everyone.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/dongminlee94/meta-learning-for-everyone/context:python)
[![License: Apache 2.0](https://img.shields.io/badge/license-Apache--2.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.8.8](https://img.shields.io/badge/python-3.8.8-blue.svg)](https://www.python.org/downloads/release/python-388/)
[![PyTorch 1.9.1](https://img.shields.io/badge/pytorch-1.9.1-red.svg)](https://pytorch.org/blog/pytorch-1.9-released/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports: isort](https://img.shields.io/badge/imports-isort-white)](https://pycqa.github.io/isort/)
[![Linting: flake8 & pylint](https://img.shields.io/badge/linting-flake8%20%26%20pylint-deepblue)](https://pypi.org/project/pytest-pylint/)
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-4-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

<p align="center">
  <img src='img/cover.jpeg' width="400" />
</p>

# 모두를 위한 메타러닝: PyTorch를 활용한 Few-shot 학습 모델과 빠른 강화학습 에이전트 만들기

"모두를 위한 메타러닝" 책을 읽으면서 실습을 진행한 코드 레포지토리입니다.
[원본 저장소](https://github.com/dongminlee94/meta-learning-for-everyone)



<h2>0. Load-dataset code</h2>

- [Omniglot](https://github.com/ChoiDae1/Meta-learning-Study/blob/main/src/meta_sl/load_dataset/load_omniglot_my.ipynb)</br>
- [Sinusoid](https://github.com/ChoiDae1/Meta-learning-Study/blob/main/src/meta_sl/load_dataset/load_sinusoid_my.ipynb)</br>
- [Half-Cheetah](https://github.com/ChoiDae1/Meta-learning-Study/tree/main/src/meta_rl/envs)

<h2>1. Meta-Supervised-learning code</h2>

- model-based </br>
(1) [MANN](https://github.com/ChoiDae1/Meta-learning-Study/blob/main/src/meta_sl/model-based/mann_my.ipynb) &nbsp;&nbsp;(2) [SNAIL](https://github.com/ChoiDae1/Meta-learning-Study/blob/main/src/meta_sl/model-based/snail_my.ipynb)

- optimization-based</br>
(1) [MAML-Regression](https://github.com/ChoiDae1/Meta-learning-Study/blob/main/src/meta_sl/opt-based/maml_regression_my.ipynb)&nbsp;&nbsp;(2) [MAML-Classification](
https://github.com/ChoiDae1/Meta-learning-Study/blob/main/src/meta_sl/opt-based/maml_classification_my.ipynb)

- metric-based</br>
(1) [MachingNet](https://github.com/ChoiDae1/Meta-learning-Study/blob/main/src/meta_sl/metric-based/matching_network_my.ipynb)&nbsp;&nbsp;(2) [PrototypicalNet](
https://github.com/ChoiDae1/Meta-learning-Study/blob/main/src/meta_sl/metric-based/prototypical_network_my.ipynb)

<h2>2. Meta-Reinforce-learning code</h2>

- recurrent-policies-based </br>
(1) [RL^2](https://github.com/ChoiDae1/Meta-learning-Study/tree/main/src/meta_rl/rl2) &nbsp;&nbsp;

- optimization-based</br>
(1) [MAML-RL](https://github.com/ChoiDae1/Meta-learning-Study/tree/main/src/meta_rl/maml)&nbsp;&nbsp;

- context-based</br>
(1) [PEARL](https://github.com/ChoiDae1/Meta-learning-Study/tree/main/src/meta_rl/pearl)

