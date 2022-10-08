# Awesome List
A list of useful stuff in Machine Learning, Computer Graphics, Software Development, Mathematics, ...

> For specific paper or algorithm, refer to
> [Paper & Algorithm list](/paper_algorithm_list.md)

> For machine learning datasets, refer to
> [Dataset List](dataset_list.md)

> References:
> [github.com/ml-tooling/best-of-ml-python](https://github.com/ml-tooling/best-of-ml-python)

---

# Table of Contents

- [Machine Learning](#machine-learning)
  - [Deep Learning Framework](#deep-learning-framework)
  - [Machine Learning Framework](#machine-learning-framework)
  - [Computer Vision](#computer-vision)
  - [Natural Language Processing](#natural-language-processing)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Graph](#graph)
  - [Causal Inference](#causal-inference)
  - [Recommendation, Advertisement & Ranking](#recommendation-advertisement--ranking)
  - [Time-Series & Financial](#time-series--financial)
  - [Linear Algebra / Statistics Toolkit](#linear-algebra--statistics-toolkit)
  - [Data Processing](#data-processing)
  - [Data Visualization](#data-visualization)
  - [Machine Learning Tutorials](#machine-learning-tutorials)
- [Full-Stack Development](#full-stack-development)
  - [Web Development](#web-development)
  - [Data Management & Processing](#data-management--processing)
- [Academic](#academic)
  - [Mathematics](#mathematics)
  - [Paper Reading](#paper-reading)
- [Useful Tools](#useful-tools)
  - [MacOS](#macos)
  - [Cross-Platform](#cross-platform)

---

# Machine Learning

## Deep Learning Framework

* [PyTorch](https://github.com/pytorch/pytorch) - An open source deep learning framework by Facebook, with GPU and dynamic graph support.
  * Supported platform: *Linux, Windows, MacOS, Android, iOS*
  * Language API: *Python, C++, Java*
  * <details open><summary>Related projects (click to expand):</summary>

    * [TorchVision](https://github.com/pytorch/vision) - Datasets, Transforms and Models specific to Computer Vision for PyTorch
    * [TorchText](https://github.com/pytorch/text) - Data loaders and abstractions for text and NLP for PyTorch
    * [TorchAudio](https://github.com/pytorch/audio) - Data manipulation and transformation for audio signal processing for PyTorch
    * [TorchRec](https://github.com/pytorch/torchrec) - A PyTorch domain library built to provide common sparsity & parallelism primitives needed for large-scale recommender systems (RecSys).
    * [TorchServe](https://github.com/pytorch/serve) - Serve, optimize and scale PyTorch models in production
    * [TorchHub](https://github.com/pytorch/hub) - Model zoo for PyTorch
    * [Ignite](https://github.com/pytorch/ignite) - High-level library to help with training and evaluating neural networks for PyTorch
    * [Captum](https://github.com/pytorch/captum) - A model interpretability and understanding library for PyTorch
    * [Glow](https://github.com/pytorch/glow) - Compiler for Neural Network hardware accelerators
    * [BoTorch](https://github.com/pytorch/botorch) - Bayesian optimization in PyTorch
    * [TNT](https://github.com/pytorch/tnt) - A library for PyTorch training tools and utilities
    * [tensorboardX](https://github.com/lanpa/tensorboardX) - Tensorboard for pytorch (and chainer, mxnet, numpy, ...)
    * [TorchMetrics](https://github.com/Lightning-AI/metrics) - Machine learning metrics for distributed, scalable PyTorch applications
    * [Apex](https://github.com/NVIDIA/apex) - Tools for easy mixed precision and distributed training in Pytorch
    * [HuggingFace Accelerate](https://github.com/huggingface/accelerate) - A simple way to train and use PyTorch models with multi-GPU, TPU, mixed-precision
    * [PyTorch Metric Learning](https://github.com/KevinMusgrave/pytorch-metric-learning) - The easiest way to use deep metric learning in your application. Modular, flexible, and extensible, written in PyTorch
    * [Auto-PyTorch](https://github.com/automl/Auto-PyTorch) - Automatic architecture search and hyperparameter optimization for PyTorch
    * [torch-optimizer](https://github.com/jettify/pytorch-optimizer) - Collection of optimizers for PyTorch compatible with optim module
    * [PyTorch Sparse](https://github.com/rusty1s/pytorch_sparse) - PyTorch Extension Library of Optimized Autograd Sparse Matrix Operations
    * [PyTorch Scatter](https://github.com/rusty1s/pytorch_scatter) - PyTorch Extension Library of Optimized Scatter Operations
    * [Torch-Struct](https://github.com/harvardnlp/pytorch-struct) - A library of tested, GPU implementations of core structured prediction algorithms for deep learning applications
    * [higher](https://github.com/facebookresearch/higher) **(not actively updated)** - A pytorch library allowing users to obtain higher order gradients over losses spanning training loops rather than individual training steps
    </details>

* [TensorFlow](https://github.com/tensorflow/tensorflow) - An open source deep learning framework by Google, with GPU support.
  * Supported platform: *Linux, Windows, MacOS, Android, iOS, Raspberry Pi, Web*
  * Language API: *Python, C++, Java, JavaScript*
  * <details open><summary>Related projects (click to expand):</summary>

    * [TensorBoard](https://github.com/tensorflow/tensorboard) - TensorFlow's Visualization Toolkit
    * [TensorFlow Text](https://github.com/tensorflow/text) - A collection of text related classes and ops for TensorFlow
    * [TensorFlow Recommenders](https://github.com/tensorflow/recommenders) - A library for building recommender system models using TensorFlow.
    * [TensorFlow Ranking](https://github.com/tensorflow/ranking) - A library for Learning-to-Rank (LTR) techniques on the TensorFlow platform.
    * [TensorFlow Serving](https://github.com/tensorflow/serving) - A flexible, high-performance serving system for machine learning models based on TensorFlow
    * [TFX](https://github.com/tensorflow/tfx) - An end-to-end platform for deploying production ML pipelines.
    * [TFDS](https://github.com/tensorflow/datasets) - A collection of datasets ready to use with TensorFlow and Jax
    * [TensorFlow Addons](https://github.com/tensorflow/addons) - Useful extra functionality for TensorFlow 2.x maintained by SIG-addons
    * [TensorFlow Transform](https://github.com/tensorflow/transform) - A library for preprocessing data with TensorFlow
    * [TensorFlow Model Garden](https://github.com/tensorflow/models) - Models and examples built with TensorFlow
    * [TensorFlow Hub](https://github.com/tensorflow/hub) - A library for transfer learning by reusing parts of TensorFlow models
    * [TensorFlow.js](https://github.com/tensorflow/tfjs) - A WebGL accelerated JavaScript library for training and deploying ML models based on TensorFlow
    * [TensorFlow Probability](https://github.com/tensorflow/probability) - Probabilistic reasoning and statistical analysis in TensorFlow
    * [TensorFlow Model Optimization Toolkit](https://github.com/tensorflow/model-optimization) - A toolkit to optimize ML models for deployment for Keras and TensorFlow, including quantization and pruning
    * [TensorFlow Model Analysis](https://github.com/tensorflow/model-analysis) - A library for evaluating TensorFlow models
    * [Trax](https://github.com/google/trax) **(successor of Tensor2Tensor)** - Deep Learning with Clear Code and Speed
    * [tf_numpy](https://www.tensorflow.org/guide/tf_numpy) - A subset of the NumPy API implemented in TensorFlow
    * [TensorFlowOnSpark](https://github.com/yahoo/TensorFlowOnSpark) - Brings TensorFlow programs to Apache Spark clusters
    * [Tensor2Tensor](https://github.com/tensorflow/tensor2tensor) **(no longer maintained)** - Library of deep learning models and datasets designed to make deep learning more accessible and accelerate ML research
    </details>

* [MXNet](https://github.com/apache/incubator-mxnet) - An open source deep learning framework by Apache, with GPU support.
  * Supported platform: *Linux, Windows, MacOS, Raspberry Pi*
  * Language API: *Python, C++, R, Julia, Scala, Go, Javascript*

* [PaddlePaddle](https://github.com/PaddlePaddle/Paddle) - An open source deep learning framework by Baidu, with GPU support.
  * Supported platform: *Linux, Windows, MacOS, Android, iOS, Web*
  * Language API: *Python, C++, Java, JavaScript*
  * <details open><summary>Related projects (click to expand):</summary>

    * [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) - Multilingual OCR toolkits based on PaddlePaddle
    * [PaddleDetection](https://github.com/PaddlePaddle/PaddleDetection) - Object detection toolkit based on PaddlePaddle
    * [PaddleSeg](https://github.com/PaddlePaddle/PaddleSeg) - Image segmentation toolkit based on PaddlePaddle
    * [PaddleClas](https://github.com/PaddlePaddle/PaddleClas) - Visual classification and recognition toolkit based on PaddlePaddle
    * [PaddleGAN](https://github.com/PaddlePaddle/PaddleGAN) - Generative Adversarial Networks toolkit based on PaddlePaddle
    * [PaddleVideo](https://github.com/PaddlePaddle/PaddleVideo) - Video understanding toolkit based on PaddlePaddle
    * [PaddleRec](https://github.com/PaddlePaddle/PaddleRec) - Recommendation algorithm based on PaddlePaddle
    * [PaddleNLP](https://github.com/PaddlePaddle/PaddleNLP) - Natural language processing toolkit based on PaddlePaddle
    * [PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech) - Speech Recognition/Translation toolkit based on PaddlePaddle
    * [PGL](https://github.com/PaddlePaddle/PGL) - An efficient and flexible graph learning framework based on PaddlePaddle
    * [PARL](https://github.com/PaddlePaddle/PARL) - A high-performance distributed training framework for Reinforcement Learning based on PaddlePaddle
    * [PaddleHub](https://github.com/PaddlePaddle/PaddleHub) - Pre-trained models toolkit based on PaddlePaddle
    * [Paddle-Lite](https://github.com/PaddlePaddle/Paddle-Lite) - Multi-platform high performance deep learning inference engine for PaddlePaddle
    * [Paddle.js](https://github.com/PaddlePaddle/Paddle.js) - An open source deep learning framework running in the browser based on PaddlePaddle
    * [VisualDL](https://github.com/PaddlePaddle/VisualDL) - A visualization analysis tool of PaddlePaddle
    </details>

* [MegEngine](https://github.com/MegEngine/MegEngine) - An open source deep learning framework by MEGVII, with GPU support.
  * Supported platform: *Linux, Windows, MacOS*
  * Language API: *Python, C++*

* [MACE](https://github.com/XiaoMi/mace) - A deep learning inference framework optimized for mobile heterogeneous computing by XiaoMi.
  * Supported platform: *Android, iOS, Linux and Windows*

* [Neural Network Libraries](https://github.com/sony/nnabla) - An open source deep learning framework by Sony, with GPU support.

* [fastai](https://github.com/fastai/fastai) - A high-level deep learning library based on PyTorch.

* [Lightning](https://github.com/Lightning-AI/lightning) - A high-level deep learning library based on PyTorch.

* [Lightning Flash](https://github.com/Lightning-AI/lightning-flash) - Your PyTorch AI Factory - Flash enables you to easily configure and run complex AI recipes for over 15 tasks across 7 data domains

* [tinygrad](https://github.com/geohot/tinygrad) - A deep learning framework in between a pytorch and a karpathy/micrograd.

* [ktrain](https://github.com/amaiya/ktrain) - A high-level deep learning library based on TensorFlow.

* [Thinc](https://github.com/explosion/thinc) - A high-level deep learning library for PyTorch, TensorFlow and MXNet.

* [Ludwig](https://github.com/ludwig-ai/ludwig) - A declarative deep learning framework that allows users to train, evaluate, and deploy models without the need to write code.

* [Jina](https://github.com/jina-ai/jina) - A high-level deep learning library for serving and deployment.

* [Haiku](https://github.com/deepmind/dm-haiku) - A high-level deep learning library based on JAX.

* [Triton](https://github.com/openai/triton) - A language and compiler for writing highly efficient custom Deep-Learning primitives.

* [Hummingbird](https://github.com/microsoft/hummingbird) - A library for compiling trained traditional ML models into tensor computations.

* [m2cgen](https://github.com/BayesWitnesses/m2cgen) - Transform ML models into a native code (Java, C, Python, Go, JavaScript, Visual Basic, C#, R, PowerShell, PHP, Dart, Haskell, Ruby, F#, Rust) with zero dependencies.

* [DeepSpeed](https://github.com/microsoft/DeepSpeed) - An easy-to-use deep learning optimization software suite that enables unprecedented scale and speed for Deep Learning Training and Inference.

* [Analytics Zoo](https://github.com/intel-analytics/analytics-zoo) **(no longer maintained)** - Distributed Tensorflow, Keras and PyTorch on Apache Spark/Flink & Ray.

* [BigDL](https://github.com/intel-analytics/BigDL) **(successor of Analytics Zoo)** - Building Large-Scale AI Applications for Distributed Big Data.

* [FairScale](https://github.com/facebookresearch/fairscale) - A PyTorch extension library for high performance and large scale training.

* [ColossalAI](https://github.com/hpcaitech/ColossalAI) - Provides a collection of parallel components and user-friendly tools to kickstart distributed training and inference in a few lines.

* [Ray](https://github.com/ray-project/ray) - A unified framework for scaling AI and Python applications. Ray consists of a core distributed runtime and a toolkit of libraries (Ray AIR) for accelerating ML workloads.

* [BentoML](https://github.com/bentoml/BentoML) - BentoML is compatible across machine learning frameworks and standardizes ML model packaging and management for your team.

* [cortex](https://github.com/cortexlabs/cortex) - Production infrastructure for machine learning at scale.

* [Horovod](https://github.com/horovod/horovod) - Distributed training framework for TensorFlow, Keras, PyTorch, and Apache MXNet.

* [Elephas](https://github.com/maxpumperla/elephas) **(no longer maintained)** - Distributed Deep learning with Keras & Spark.

* [Elephas](https://github.com/danielenricocahall/elephas) **(successor of maxpumperla/elephas)** - Distributed Deep learning with Keras & Spark.

* [ONNX](https://github.com/onnx/onnx) - Open standard for machine learning interoperability.

* [Core ML Tools](https://github.com/apple/coremltools) - Contains supporting tools for Core ML model conversion, editing, and validation.

* [Petastorm](https://github.com/uber/petastorm) - Enables single machine or distributed training and evaluation of deep learning models from datasets in Apache Parquet format.

* [Hivemind](https://github.com/learning-at-home/hivemind) - Decentralized deep learning in PyTorch. Built to train models on thousands of volunteers across the world.

* [Mesh Transformer JAX](https://github.com/kingoflolz/mesh-transformer-jax) - Model parallel transformers in JAX and Haiku.

* [Nebullvm](https://github.com/nebuly-ai/nebullvm) - An open-source tool designed to speed up AI inference in just a few lines of code.

* [NNI](https://github.com/microsoft/nni) - An open source AutoML toolkit for automate machine learning lifecycle, including feature engineering, neural architecture search, model compression and hyper-parameter tuning.

* [AutoKeras](https://github.com/keras-team/autokeras) - AutoML library for deep learning.

* [KerasTuner](https://github.com/keras-team/keras-tuner) - An easy-to-use, scalable hyperparameter optimization framework that solves the pain points of hyperparameter search.

* [Talos](https://github.com/autonomio/talos) - Hyperparameter Optimization for TensorFlow, Keras and PyTorch.

* [AI Explainability 360](https://github.com/Trusted-AI/AIX360) - An open-source library that supports interpretability and explainability of datasets and machine learning models.

* [explainerdashboard](https://github.com/oegedijk/explainerdashboard) - Quickly build Explainable AI dashboards that show the inner workings of so-called "blackbox" machine learning models.

* [iNNvestigate](https://github.com/albermax/innvestigate) - A toolbox to innvestigate neural networks' predictions.

* [Foolbox](https://github.com/bethgelab/foolbox) - A Python toolbox to create adversarial examples that fool neural networks in PyTorch, TensorFlow, and JAX.

* [AdvBox](https://github.com/advboxes/AdvBox) - A toolbox to generate adversarial examples that fool neural networks in PaddlePaddle、PyTorch、Caffe2、MxNet、Keras、TensorFlow.

* [Adversarial Robustness Toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox) - Python Library for Machine Learning Security - Evasion, Poisoning, Extraction, Inference.

* [Fairlearn](https://github.com/fairlearn/fairlearn) - A Python package to assess and improve fairness of machine learning models.

* [AI Fairness 360](https://github.com/Trusted-AI/AIF360) - A comprehensive set of fairness metrics for datasets and machine learning models, explanations for these metrics, and algorithms to mitigate bias in datasets and models.

* [CNTK](https://github.com/microsoft/CNTK) **(not actively updated)** - An open source deep learning framework by Microsoft, with GPU support.
  * Supported platform: *Linux, Windows*
  * Language API: *Python, C++, Java, C#, .Net*

* [DyNet](https://github.com/clab/dynet) **(not actively updated)** - A C++ deep learning library by CMU.
  * Supported platform: *Linux, Windows, MacOS*
  * Language API: *C++, Python*

* [Chainer](https://github.com/chainer/chainer) **(not actively updated)** - A flexible framework of neural networks for deep learning.

* [skorch](https://github.com/skorch-dev/skorch) **(not actively updated)** - A scikit-learn compatible neural network library based on PyTorch.

* [MMF](https://github.com/facebookresearch/mmf) **(not actively updated)** - A modular framework for vision and language multimodal research by Facebook AI Research, based on PyTorch.

* [Tensorpack](https://github.com/tensorpack/tensorpack) **(not actively updated)** - A high-level deep learning library based on TensorFlow.

* [Sonnet](https://github.com/deepmind/sonnet) **(not actively updated)** - A high-level deep learning library based on TensorFlow.

* [Ivy](https://github.com/unifyai/ivy) **(not actively updated)** - A high-level deep learning library that unifies NumPy, PyTorch, TensorFlow, MXNet and JAX.

* [Turi Create](https://github.com/apple/turicreate) **(not actively updated)** - A machine learning library for deployment on MacOS/iOS.

* [Apache SINGA](https://github.com/apache/singa) **(not actively updated)** - A distributed deep learning platform.

* [BytePS](https://github.com/bytedance/byteps) **(not actively updated)** - A high performance and generic framework for distributed DNN training.

* [MMdnn](https://github.com/microsoft/MMdnn) **(not actively updated)** - MMdnn is a set of tools to help users inter-operate among different deep learning frameworks.

* [Hyperas](https://github.com/maxpumperla/hyperas) **(not actively updated)** - A very simple wrapper for convenient hyperparameter optimization for Keras.

* [Model Search](https://github.com/google/model_search) **(not actively updated)** - A framework that implements AutoML algorithms for model architecture search at scale.

## Machine Learning Framework

* [scikit-learn](https://github.com/scikit-learn/scikit-learn) - Machine learning toolkit for Python.
  * <details open><summary>Related projects (click to expand):</summary>

    * [imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn) - A python package offering a number of re-sampling techniques commonly used in datasets showing strong between-class imbalance
    * [category_encoders](https://github.com/scikit-learn-contrib/category_encoders) - A set of scikit-learn-style transformers for encoding categorical variables into numeric by means of different techniques
    * [lightning](https://github.com/scikit-learn-contrib/lightning) - Large-scale linear classification, regression and ranking in Python
    * [sklearn-pandas](https://github.com/scikit-learn-contrib/sklearn-pandas) - Pandas integration with sklearn
    * [HDBSCAN](https://github.com/scikit-learn-contrib/hdbscan) - A high performance implementation of HDBSCAN clustering
    * [metric-learn](https://github.com/scikit-learn-contrib/metric-learn) - Metric learning algorithms in Python
    * [scikit-optimize](https://github.com/scikit-optimize/scikit-optimize) - Sequential model-based optimization with a `scipy.optimize` interface
    * [scikit-image](https://github.com/scikit-image/scikit-image) - Image processing in Python
    * [auto-sklearn](https://github.com/automl/auto-sklearn) - An automated machine learning toolkit and a drop-in replacement for a scikit-learn estimator.
    * [scikit-multilearn](https://github.com/scikit-multilearn/scikit-multilearn) - A Python module capable of performing multi-label learning tasks
    * [scikit-lego](https://github.com/koaning/scikit-lego) - Extra blocks for scikit-learn pipelines.
    * [scikit-opt](https://github.com/guofei9987/scikit-opt) - Genetic Algorithm, Particle Swarm Optimization, Simulated Annealing, Ant Colony Optimization Algorithm,Immune Algorithm, Artificial Fish Swarm Algorithm, Differential Evolution and TSP(Traveling salesman)
    * [sklearn-porter](https://github.com/nok/sklearn-porter) - Transpile trained scikit-learn estimators to C, Java, JavaScript and others.
  </details>

* [XGBoost](https://github.com/dmlc/xgboost) - Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library.
  * Supported platform: *Linux, Windows, MacOS*
  * Supported distributed framework: *Hadoop, Spark, Dask, Flink, DataFlow*
  * Language API: *Python, C++, R, Java, Scala, Go*

* [LightGBM](https://github.com/microsoft/LightGBM) - A fast, distributed, high performance gradient boosting (GBT, GBDT, GBRT, GBM or MART) framework based on decision tree algorithms.
  * Supported platform: *Linux, Windows, MacOS*
  * Language API: *Python, C++, R*

* [CatBoost](https://github.com/catboost/catboost) - A fast, scalable, high performance Gradient Boosting on Decision Trees library.
  * Supported platform: *Linux, Windows, MacOS*
  * Language API: *Python, C++, R, Java*

* [JAX](https://github.com/google/jax) - Automatical differentiation for native Python and NumPy functions, with GPU support.

* [Flax](https://github.com/google/flax) - A high-performance neural network library and ecosystem for JAX that is designed for flexibility.

* [Equinox](https://github.com/patrick-kidger/equinox) - A JAX library based around a simple idea: represent parameterised functions (such as neural networks) as PyTrees.

* [cuML](https://github.com/rapidsai/cuml) - A suite of libraries that implement machine learning algorithms and mathematical primitives functions that share compatible APIs with other RAPIDS projects.

* [Mlxtend](https://github.com/rasbt/mlxtend) - A library of extension and helper modules for Python's data analysis and machine learning libraries.

* [Annoy](https://github.com/spotify/annoy) - Approximate Nearest Neighbors in C++/Python optimized for memory usage and loading/saving to disk.

* [Hnswlib](https://github.com/nmslib/hnswlib) - Header-only C++/python library for fast approximate nearest neighbors.

* [NMSLIB](https://github.com/nmslib/nmslib) - Non-Metric Space Library (NMSLIB): An efficient similarity search library and a toolkit for evaluation of k-NN methods for generic non-metric spaces.

* [ann-benchmarks](https://github.com/erikbern/ann-benchmarks) - Benchmarks of approximate nearest neighbor libraries in Python.

* [FilterPy](https://github.com/rlabbe/filterpy) - Python Kalman filtering and optimal estimation library.

* [igel](https://github.com/nidhaloff/igel) - A delightful machine learning tool that allows you to train, test, and use models without writing code.

* [fklearn](https://github.com/nubank/fklearn) - A machine learning library that uses functional programming principles.

* [SynapseML](https://github.com/microsoft/SynapseML) - An open-source library that simplifies the creation of massively scalable machine learning pipelines.

* [Dask](https://github.com/dask/dask) - A flexible parallel computing library for NumPy, Pandas and Scikit-Learn.
  * <details open><summary>Related projects (click to expand):</summary>

    * [Distributed](https://github.com/dask/distributed) - A distributed task scheduler for Dask
  </details>

* [H2O](https://github.com/h2oai/h2o-3) - An in-memory platform for distributed, scalable machine learning.

* [Optuna](https://github.com/optuna/optuna) - An automatic hyperparameter optimization software framework, particularly designed for machine learning.

* [Ax](https://github.com/facebook/Ax) - An accessible, general-purpose platform for understanding, managing, deploying, and automating adaptive experiments.

* [AutoGluon](https://github.com/awslabs/autogluon) - Automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications.

* [Nevergrad](https://github.com/facebookresearch/nevergrad) - A Python toolbox for performing gradient-free optimization.

* [MLJAR](https://github.com/mljar/mljar-supervised) - Python package for AutoML on Tabular Data with Feature Engineering, Hyper-Parameters Tuning, Explanations and Automatic Documentation.

* [MLflow](https://github.com/mlflow/mlflow) - A platform to streamline machine learning development, including tracking experiments, packaging code into reproducible runs, and sharing and deploying models.

* [PyCaret](https://github.com/pycaret/pycaret) - An open-source, low-code machine learning library in Python that automates machine learning workflows.

* [Aim](https://github.com/aimhubio/aim) - An open-source, self-hosted ML experiment tracking tool.

* [labml](https://github.com/labmlai/labml) - Monitor deep learning model training and hardware usage from your mobile phone.

* [ClearML](https://github.com/allegroai/clearml) - Auto-Magical Suite of tools to streamline your ML workflow Experiment Manager, MLOps and Data-Management.

* [DVC](https://github.com/iterative/dvc) - A command line tool and VS Code Extension for data/model version control.

* [Metaflow](https://github.com/Netflix/metaflow) - A human-friendly Python/R library that helps scientists and engineers build and manage real-life data science projects.

* [Weights&Biases](https://github.com/wandb/wandb) - A tool for visualizing and tracking your machine learning experiments.

* [Yellowbrick](https://github.com/DistrictDataLabs/yellowbrick) - Visual analysis and diagnostic tools to facilitate machine learning model selection.

* [dtreeviz](https://github.com/parrt/dtreeviz) - A python library for decision tree visualization and model interpretation.

* [InterpretML](https://github.com/interpretml/interpret) - An open-source package that incorporates state-of-the-art machine learning interpretability techniques.

* [Shapash](https://github.com/MAIF/shapash) - A Python library which aims to make machine learning interpretable and understandable by everyone.

* [Alibi](https://github.com/SeldonIO/alibi) - An open source Python library aimed at machine learning model inspection and interpretation.

* [mlpack](https://github.com/mlpack/mlpack) **(not actively updated)** - A header-only C++ machine learning library.
  * Language API: *C++, Python, R, Julia, Go*

* [xLearn](https://github.com/aksnzhy/xlearn) **(not actively updated)** - A C++ machine learning library for linear model (LR), factorization machines (FM), and field-aware factorization machines (FFM).

* [ThunderGBM](https://github.com/Xtra-Computing/thundergbm) **(not actively updated)** - Fast GBDTs and Random Forests on GPUs.

* [ThunderSVM](https://github.com/Xtra-Computing/thundersvm) **(not actively updated)** - A Fast SVM Library on GPUs and CPUs.

* [BayesianOptimization](https://github.com/fmfn/BayesianOptimization) **(not actively updated)** - A Python implementation of global optimization with gaussian processes.

* [Hyperopt](https://github.com/hyperopt/hyperopt) **(not actively updated)** - Distributed Asynchronous Hyperparameter Optimization in Python.

* [Dragonfly](https://github.com/dragonfly/dragonfly) **(not actively updated)** - An open source python library for scalable Bayesian optimisation.

## Computer Vision

* [OpenCV](https://github.com/opencv/opencv) - Open Source Computer Vision Library.
  * <details open><summary>Related projects (click to expand):</summary>

    * [opencv_contrib](https://github.com/opencv/opencv_contrib) - Repository for OpenCV's extra modules.
  </details>
  
* [opencv-python](https://github.com/opencv/opencv-python) - Pre-built CPU-only OpenCV packages for Python.

* [Detectron](https://github.com/facebookresearch/Detectron/) **(no longer maintained)** - A research platform for object detection research, implementing popular algorithms by Facebook, based on Caffe2.

* [Detectron2](https://github.com/facebookresearch/detectron2) **(successor of Detectron)** - A platform for object detection, segmentation and other visual recognition tasks, based on PyTorch.

* [OMMCV](https://github.com/open-mmlab/mmcv) - OpenMMLab Computer Vision Foundation.
  * <details open><summary>Related projects (click to expand):</summary>

    * [MMClassification](https://github.com/open-mmlab/mmclassification) - OpenMMLab Image Classification Toolbox and Benchmark
    * [MMDetection](https://github.com/open-mmlab/mmdetection) - OpenMMLab Detection Toolbox and Benchmark
    * [MMDetection3D](https://github.com/open-mmlab/mmdetection3d) - OpenMMLab's next-generation platform for general 3D object detection
    * [MMOCR](https://github.com/open-mmlab/mmocr) - OpenMMLab Text Detection, Recognition and Understanding Toolbox
    * [MMSegmentation](https://github.com/open-mmlab/mmsegmentation) - OpenMMLab Semantic Segmentation Toolbox and Benchmark.
    * [MMTracking](https://github.com/open-mmlab/mmtracking) - OpenMMLab Video Perception Toolbox
    * [MMPose](https://github.com/open-mmlab/mmpose) - OpenMMLab Pose Estimation Toolbox and Benchmark
    * [MMSkeleton](https://github.com/open-mmlab/mmskeleton) - A OpenMMLAB toolbox for human pose estimation, skeleton-based action recognition, and action synthesis
    * [MMGeneration](https://github.com/open-mmlab/mmgeneration) - MMGeneration is a powerful toolkit for generative models, based on PyTorch and MMCV
    * [MMEditing](https://github.com/open-mmlab/mmediting) - MMEditing is a low-level vision toolbox based on PyTorch, supporting super-resolution, inpainting, matting, video interpolation, etc
    * [MMDeploy](https://github.com/open-mmlab/mmdeploy) - OpenMMLab Model Deployment Framework
    * [OpenPCDet](https://github.com/open-mmlab/OpenPCDet) - OpenPCDet Toolbox for LiDAR-based 3D Object Detection
  </details>

* [Norfair](https://github.com/tryolabs/norfair) - Lightweight Python library for adding real-time multi-object tracking to any detector.

* [PyTorchVideo](https://github.com/facebookresearch/pytorchvideo) - A deep learning library for video understanding research, based on PyTorch.

* [Lightly](https://github.com/lightly-ai/lightly) - A computer vision framework for self-supervised learning, based on PyTorch.

* [ClassyVision](https://github.com/facebookresearch/ClassyVision) - An end-to-end framework for image and video classification, based on PyTorch.

* [pycls](https://github.com/facebookresearch/pycls) - Codebase for Image Classification Research, based on PyTorch.

* [SlowFast](https://github.com/facebookresearch/SlowFast) - Video understanding codebase from FAIR, based on PyTorch.

* [SAHI](https://github.com/obss/sahi) - Platform agnostic sliced/tiled inference + interactive ui + error analysis plots for object detection and instance segmentation.

* [GluonCV](https://github.com/dmlc/gluon-cv) - A high-level computer vision library for PyTorch and MXNet.

* [InsightFace](https://github.com/deepinsight/insightface) - An open source 2D&3D deep face analysis toolbox, based on PyTorch and MXNet.

* [Scenic](https://github.com/google-research/scenic) - A codebase with a focus on research around attention-based models for computer vision, based on JAX and Flax.

* [Deepface](https://github.com/serengil/deepface) - A Lightweight Face Recognition and Facial Attribute Analysis (Age, Gender, Emotion and Race) Library for Python.

* [Kornia](https://github.com/kornia/kornia) - Open source differentiable computer vision library, based on PyTorch.

* [Kubric](https://github.com/google-research/kubric) - A data generation pipeline for creating semi-realistic synthetic multi-object videos with rich annotations such as instance segmentation masks, depth maps, and optical flow.

* [pytorch-image-models](https://github.com/rwightman/pytorch-image-models) - A collection of CV models, scripts, pretrained weights, based on PyTorch.

* [vit-pytorch](https://github.com/lucidrains/vit-pytorch) - A collection of Vision Transformer implementations, based on PyTorch.

* [vit-tensorflow](https://github.com/taki0112/vit-tensorflow) - A collection of Vision Transformer implementations, based on TensorFlow.

* [EasyOCR](https://github.com/JaidedAI/EasyOCR) - Ready-to-use OCR with 80+ supported languages and all popular writing scripts.

* [Python-tesseract](https://github.com/madmaze/pytesseract) - A Python wrapper for Google's Tesseract-OCR Engine.

* [tesserocr](https://github.com/sirfz/tesserocr) - A simple, Pillow-friendly, wrapper around the tesseract-ocr API for OCR.

* [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) - Adds an OCR text layer to scanned PDF files, allowing them to be searched.

* [LayoutParser](https://github.com/Layout-Parser/layout-parser) - A Unified Toolkit for Deep Learning Based Document Image Analysis, based on Detectron2.

* [pdftabextract](https://github.com/WZBSocialScienceCenter/pdftabextract) **(no longer maintained)** - A set of tools for extracting tables from PDF files helping to do data mining on (OCR-processed) scanned documents.

* [segmentation_models](https://github.com/qubvel/segmentation_models) **(not actively updated)** - Python library with Neural Networks for Image Segmentation based on Keras and TensorFlow.

* [Face Recognition](https://github.com/ageitgey/face_recognition) **(not actively updated)** - A facial recognition api for Python and the command line.

## Natural Language Processing

* [HuggingFace Transformers](https://github.com/huggingface/transformers) - A high-level machine learning library for text, images and audio data, with support for Pytorch, TensorFlow and JAX.

* [HuggingFace Tokenizers](https://github.com/huggingface/tokenizers) - A high-performance library for text vocabularies and tokenizers.

* [NLTK](https://github.com/nltk/nltk) - An open source natural language processing library in Python.

* [spaCy](https://github.com/explosion/spaCy) - Industrial-strength Natural Language Processing (NLP) in Python.

* [ScispaCy](https://github.com/allenai/scispacy) - A Python package containing spaCy models for processing biomedical, scientific or clinical text.

* [PyTextRank](https://github.com/DerwenAI/pytextrank) - A Python implementation of TextRank as a spaCy pipeline extension, for graph-based natural language work.

* [textacy](https://github.com/chartbeat-labs/textacy) - a Python library for performing a variety of natural language processing tasks, based on spaCy.

* [spacy-transformers](https://github.com/explosion/spacy-transformers) - Use pretrained transformers in spaCy, based on HuggingFace Transformers.

* [Spark NLP](https://github.com/JohnSnowLabs/spark-nlp) - An open source natural language processing library for Apache Spark.

* [Flair](https://github.com/flairNLP/flair) - An open source natural language processing library, based on PyTorch.

* [Fairseq](https://github.com/facebookresearch/fairseq) - A sequence-to-sequence toolkit by Facebook, based on PyTorch.

* [ParlAI](https://github.com/facebookresearch/ParlAI) - A python framework for sharing, training and testing dialogue models from open-domain chitchat, based on PyTorch.

* [Stanza](https://github.com/stanfordnlp/stanza) - An open source natural language processing library by Stanford NLP Group, based on PyTorch.

* [ESPnet](https://github.com/espnet/espnet) - An end-to-end speech processing toolkit covering end-to-end speech recognition, text-to-speech, speech translation, speech enhancement, speaker diarization, spoken language understanding, based on PyTorch.

* [SpeechBrain](https://github.com/speechbrain/speechbrain) - An open-source and all-in-one conversational AI toolkit based on PyTorch.

* [NeMo](https://github.com/NVIDIA/NeMo) - A toolkit for conversational AI, based on PyTorch.

* [Sockeye](https://github.com/awslabs/sockeye) - An open-source sequence-to-sequence framework for Neural Machine Translation, based on PyTorch.

* [DeepPavlov](https://github.com/deeppavlov/DeepPavlov) - An open-source conversational AI library built on TensorFlow, Keras and PyTorch.

* [Spleeter](https://github.com/deezer/spleeter) - A source separation library with pretrained models, based on TensorFlow.

* [TTS](https://github.com/coqui-ai/TTS) - A library for advanced Text-to-Speech generation.

* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - A Python library for audio feature extraction, classification, segmentation and applications.

* [Porcupine](https://github.com/Picovoice/porcupine) - On-device wake word detection powered by deep learning.

* [NLP Architect](https://github.com/IntelLabs/nlp-architect) - A Deep Learning NLP/NLU library by Intel AI Lab, based on PyTorch and TensorFlow.

* [LightSeq](https://github.com/bytedance/lightseq) - A high performance training and inference library for sequence processing and generation implemented in CUDA, for Fairseq and HuggingFace Transformers.

* [fastNLP](https://github.com/fastnlp/fastNLP) - A Modularized and Extensible NLP Framework for PyTorch and PaddleNLP.

* [Rubrix](https://github.com/recognai/rubrix) - A production-ready Python framework for exploring, annotating, and managing data in NLP projects.

* [OpenNMT-py](https://github.com/OpenNMT/OpenNMT-py) - The PyTorch version of the OpenNMT project, an open-source neural machine translation framework.

* [OpenNMT-tf](https://github.com/OpenNMT/OpenNMT-tf) - The TensorFlow version of the OpenNMT project, an open-source neural machine translation framework.

* [Gensim](https://github.com/RaRe-Technologies/gensim) - A Python library for topic modelling, document indexing and similarity retrieval with large corpora, based on NumPy and SciPy.

* [CLTK](https://github.com/cltk/cltk) - A Python library offering natural language processing for pre-modern languages.

* [Rasa](https://github.com/RasaHQ/rasa) - Open source machine learning framework to automate text- and voice-based conversations.

* [SentencePiece](https://github.com/google/sentencepiece) - Unsupervised text tokenizer for Neural Network-based text generation.

* [subword-nmt](https://github.com/rsennrich/subword-nmt) - Unsupervised Word Segmentation for Neural Machine Translation and Text Generation.

* [OpenNRE](https://github.com/thunlp/OpenNRE) - An open-source and extensible toolkit that provides a unified framework to implement relation extraction models.

* [sumy](https://github.com/miso-belica/sumy) - Module for automatic summarization of text documents and HTML pages.

* [OpenPrompt](https://github.com/thunlp/OpenPrompt) - An Open-Source Framework for Prompt-Learning.

* [Language Interpretability Tool](https://github.com/PAIR-code/lit) - Interactively analyze NLP models for model understanding in an extensible and framework agnostic interface.

* [TextAttack](https://github.com/QData/TextAttack) - A Python framework for adversarial attacks, data augmentation, and model training in NLP.

* [CheckList](https://github.com/marcotcr/checklist) - Behavioral Testing of NLP models with CheckList.

* [Magenta](https://github.com/magenta/magenta) **(no longer maintained)** - Music and Art Generation with Machine Intelligence.

* [FARM](https://github.com/deepset-ai/FARM) **(not actively updated)** - Fast & easy transfer learning for NLP, which focuses on Question Answering.

* [Haystack](https://github.com/deepset-ai/haystack) **(successor of FARM)** - A high-level natural language processing library for deployment and production, based on PyTorch and HuggingFace Transformers.

* [SpeechRecognition](https://github.com/Uberi/speech_recognition) **(not actively updated)** - Library for performing speech recognition, with support for several engines and APIs, online and offline.

* [AllenNLP](https://github.com/allenai/allennlp) **(not actively updated)** - An open source natural language processing library, based on PyTorch.

* [GluonNLP](https://github.com/dmlc/gluon-nlp) **(not actively updated)** - A high-level NLP toolkit, based on MXNet.

* [jiant](https://github.com/nyu-mll/jiant) **(no longer maintained)** - The multitask and transfer learning toolkit for natural language processing research.

* [fastText](https://github.com/facebookresearch/fastText) **(not actively updated)** - A library for efficient learning of word representations and sentence classification.

* [TextBlob](https://github.com/sloria/TextBlob) **(not actively updated)** - A Python library for processing textual data.

## Reinforcement Learning

* [Gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms by OpenAI.

* [TF-Agents](https://github.com/tensorflow/agents) - A reliable, scalable and easy to use TensorFlow library for Contextual Bandits and Reinforcement Learning.

* [TensorLayer](https://github.com/tensorlayer/TensorLayer) - A novel TensorFlow-based deep learning and reinforcement learning library designed for researchers and engineers.

* [Tensorforce](https://github.com/tensorforce/tensorforce) - A TensorFlow library for applied reinforcement learning.

* [Acme](https://github.com/deepmind/acme) - A research framework for reinforcement learning by DeepMind.

* [RLax](https://github.com/deepmind/rlax) - A library built on top of JAX that exposes useful building blocks for implementing reinforcement learning agents.

* [ReAgent](https://github.com/facebookresearch/ReAgent) - An open source end-to-end platform for applied reinforcement learning by Facebook.

* [Dopamine](https://github.com/google/dopamine) - A research framework for fast prototyping of reinforcement learning algorithms.

* [Vowpal Wabbit](https://github.com/VowpalWabbit/vowpal_wabbit) - A fast, flexible, online, and active learning solution for solving complex interactive machine learning problems.

* [PFRL](https://github.com/pfnet/pfrl) - A PyTorch-based deep reinforcement learning library.

* [garage](https://github.com/rlworkgroup/garage) - A toolkit for reproducible reinforcement learning research.

* [OpenAI Baselines](https://github.com/openai/baselines) **(no longer maintained)** - A set of high-quality implementations of reinforcement learning algorithms.

* [Stable Baselines](https://github.com/hill-a/stable-baselines) **(no longer maintained)** - A fork of OpenAI Baselines, implementations of reinforcement learning algorithms.

* [Stable Baselines3](https://github.com/DLR-RM/stable-baselines3) **(successor of OpenAI Baselines and Stable Baselines)** - A set of reliable implementations of reinforcement learning algorithms in PyTorch.

* [ViZDoom](https://github.com/mwydmuch/ViZDoom) - Doom-based AI Research Platform for Reinforcement Learning from Raw Visual Information.

* [FinRL](https://github.com/AI4Finance-Foundation/FinRL) - The first open-source framework to show the great potential of financial reinforcement learning.

## Graph

* [DGL](https://github.com/dmlc/dgl) - An easy-to-use, high performance and scalable Python package for deep learning on graphs for PyTorch, Apache MXNet or TensorFlow.

* [NetworkX](https://github.com/networkx/networkx) - A Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.

* [PyG](https://github.com/pyg-team/pytorch_geometric) - A Graph Neural Network Library based on PyTorch.

* [OGB](https://github.com/snap-stanford/ogb) - Benchmark datasets, data loaders, and evaluators for graph machine learning.

* [Spektral](https://github.com/danielegrattarola/spektral) - A Python library for graph deep learning, based on Keras and TensorFlow.

* [Graph4nlp](https://github.com/graph4ai/graph4nlp) - A library for the easy use of Graph Neural Networks for NLP (DLG4NLP).

* [Jraph](https://github.com/deepmind/jraph) - A Graph Neural Network Library in Jax.

* [cuGraph](https://github.com/rapidsai/cugraph) - A collection of GPU accelerated graph algorithms that process data found in GPU DataFrames (cuDF).

* [GraphEmbedding](https://github.com/shenweichen/GraphEmbedding) - Implementation and experiments of graph embedding algorithms.

* [PyTorch-BigGraph](https://github.com/facebookresearch/PyTorch-BigGraph) **(not actively updated)** - Generate embeddings from large-scale graph-structured data,  based on PyTorch.

* [TensorFlow Graphics](https://github.com/tensorflow/graphics) **(not actively updated)** - Differentiable Graphics Layers for TensorFlow.

* [StellarGraph](https://github.com/stellargraph/stellargraph) **(not actively updated)** - A Python library for machine learning on graphs and networks.

## Causal Inference

* [DoWhy](https://github.com/py-why/dowhy) - A Python library for causal inference that supports explicit modeling and testing of causal assumptions.

* [CausalNex](https://github.com/quantumblacklabs/causalnex) - A Python library that helps data scientists to infer causation rather than observing correlation.

## Recommendation, Advertisement & Ranking

* [Recommenders](https://github.com/microsoft/recommenders) - Best Practices on Recommendation Systems.

* [Surprise](https://github.com/NicolasHug/Surprise) - A Python scikit for building and analyzing recommender systems.

* [Implicit](https://github.com/benfred/implicit) - Fast Python Collaborative Filtering for Implicit Feedback Datasets.

* [LightFM](https://github.com/lyst/lightfm) - A Python implementation of LightFM, a hybrid recommendation algorithm.

* [RecBole](https://github.com/RUCAIBox/RecBole) - A unified, comprehensive and efficient recommendation library for reproducing and developing recommendation algorithms.

## Time-Series & Financial

* [Prophet](https://github.com/facebook/prophet) - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth.

* [darts](https://github.com/unit8co/darts) - A python library for easy manipulation and forecasting of time series.

* [GluonTS](https://github.com/awslabs/gluonts) - Probabilistic time series modeling in Python.

* [tslearn](https://github.com/tslearn-team/tslearn) - A machine learning toolkit dedicated to time-series data.

* [sktime](https://github.com/sktime/sktime) - A unified framework for machine learning with time series.

* [PyTorch Forecasting](https://github.com/jdb78/pytorch-forecasting) - Time series forecasting with PyTorch.

* [STUMPY](https://github.com/TDAmeritrade/stumpy) - A powerful and scalable Python library for modern time series analysis.

* [StatsForecast](https://github.com/Nixtla/statsforecast) - Offers a collection of widely used univariate time series forecasting models, including automatic ARIMA and ETS modeling optimized for high performance using numba.

* [Orbit](https://github.com/uber/orbit) - A Python package for Bayesian time series forecasting and inference.

* [Pmdarima](https://github.com/alkaline-ml/pmdarima) - A statistical library designed to fill the void in Python's time series analysis capabilities, including the equivalent of R's auto.arima function.

* [Qlib](https://github.com/microsoft/qlib) - An AI-oriented quantitative investment platform, which aims to realize the potential, empower the research, and create the value of AI technologies in quantitative investment.

* [IB-insync](https://github.com/erdewit/ib_insync) - Python sync/async framework for Interactive Brokers API.

* [ffn](https://github.com/pmorissette/ffn) - A financial function library for Python.

* [bt](https://github.com/pmorissette/bt) - A flexible backtesting framework for Python used to test quantitative trading strategies, based on ffn.

* [finmarketpy](https://github.com/cuemacro/finmarketpy) - Python library for backtesting trading strategies & analyzing financial markets.

* [TensorTrade](https://github.com/tensortrade-org/tensortrade) - An open source reinforcement learning framework for training, evaluating, and deploying robust trading agents, based on TensorFlow.

* [TF Quant Finance](https://github.com/google/tf-quant-finance) - High-performance TensorFlow library for quantitative finance.

* [Pandas TA](https://github.com/twopirllc/pandas-ta) - An easy to use library that leverages the Pandas package with more than 130 Indicators and Utility functions and more than 60 TA Lib Candlestick Patterns.

* [pyts](https://github.com/johannfaouzi/pyts) **(not actively updated)** - A Python package for time series classification.

* [CryptoSignal](https://github.com/CryptoSignal/Crypto-Signal) **(not actively updated)** - A command line tool that automates your crypto currency Technical Analysis (TA).

* [Catalyst](https://github.com/scrtlabs/catalyst) **(no longer maintained)** - An algorithmic trading library for crypto-assets written in Python.

## Linear Algebra / Statistics Toolkit

* [NumPy](https://github.com/numpy/numpy) - The fundamental package for scientific computing with Python.

* [SciPy](https://github.com/scipy/scipy) - An open-source software for mathematics, science, and engineering in Python.

* [ArrayFire](https://github.com/arrayfire/arrayfire) - A general-purpose tensor library that simplifies the process of software development for the parallel architectures found in CPUs, GPUs, and other hardware acceleration devices

* [CuPy](https://github.com/cupy/cupy) - A NumPy/SciPy-compatible array library for GPU-accelerated computing with Python.

* [PyCUDA](https://github.com/inducer/pycuda) - Pythonic Access to CUDA, with Arrays and Algorithms.

* [torchdiffeq](https://github.com/rtqichen/torchdiffeq) - Differentiable ordinary differential equation (ODE) solvers with full GPU support and O(1)-memory backpropagation.

* [Statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.

* [Theano](https://github.com/Theano/Theano) **(no longer maintained)** - A Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently.

* [Aesara](https://github.com/aesara-devs/aesara) **(successor of Theano)** - A Python library that allows one to define, optimize/rewrite, and evaluate mathematical expressions, especially ones involving multi-dimensional arrays.

* [einops](https://github.com/arogozhnikov/einops) - A tensor operation library for NumPy, PyTorch, TensorFlow and JAX.

* [Milvus](https://github.com/milvus-io/milvus) - An open-source vector database built to power embedding similarity search and AI applications.

* [Faiss](https://github.com/facebookresearch/faiss) - A library for efficient similarity search and clustering of dense vectors.

* [shap](https://github.com/slundberg/shap) - A game theoretic approach to explain the output of any machine learning model.

* [Pyro](https://github.com/pyro-ppl/pyro) - Deep universal probabilistic programming with Python and PyTorch.

* [GPyTorch](https://github.com/cornellius-gp/gpytorch) - A highly efficient and modular implementation of Gaussian Processes in PyTorch.

* [PyMC](https://github.com/pymc-devs/pymc) - Probabilistic Programming in Python: Bayesian Modeling and Probabilistic Machine Learning with Aesara.

* [hmmlearn](https://github.com/hmmlearn/hmmlearn) - Hidden Markov Models in Python, with scikit-learn like API.

* [emcee](https://github.com/dfm/emcee) - The Python ensemble sampling toolkit for affine-invariant Markov chain Monte Carlo (MCMC).

* [pgmpy](https://github.com/pgmpy/pgmpy) - A python library for working with Probabilistic Graphical Models.

* [pomegranate](https://github.com/jmschrei/pomegranate) - Fast, flexible and easy to use probabilistic modelling in Python.

* [Orbit](https://github.com/uber/orbit) - A Python package for Bayesian forecasting with object-oriented design and probabilistic models under the hood.

* [GPflow](https://github.com/GPflow/GPflow) - Gaussian processes in TensorFlow.

* [ArviZ](https://github.com/arviz-devs/arviz) - A Python package for exploratory analysis of Bayesian models.

* [openTSNE](https://github.com/pavlin-policar/openTSNE) - Extensible, parallel Python implementations of t-SNE.

* [UMAP](https://github.com/lmcinnes/umap) - Uniform Manifold Approximation and Projection, a dimension reduction technique that can be used for visualisation similarly to t-SNE.

## Data Processing

* [cuDF](https://github.com/rapidsai/cudf) - GPU DataFrame Library.

* [DALI](https://github.com/NVIDIA/DALI) - A library for data loading and pre-processing to accelerate deep learning applications.

* [Pillow](https://github.com/python-pillow/Pillow) - The friendly PIL fork (Python Imaging Library).

* [Imageio](https://github.com/imageio/imageio) - Python library for reading and writing image data.

* [MoviePy](https://github.com/Zulko/moviepy) - Video editing with Python.

* [Wand](https://github.com/emcconville/wand) - The ctypes-based simple ImageMagick binding for Python.

* [VidGear](https://github.com/abhiTronix/vidgear) - A High-performance cross-platform Video Processing Python framework powerpacked with unique trailblazing features.

* [Albumentations](https://github.com/albumentations-team/albumentations) - A Python library for image augmentation.

* [Augmentor](https://github.com/mdbloice/Augmentor) - Image augmentation library in Python for machine learning.

* [imutils](https://github.com/PyImageSearch/imutils) - A basic image processing toolkit in Python, based on OpenCV.

* [Towhee](https://github.com/towhee-io/towhee) - Data processing pipelines for neural networks.

* [ffcv](https://github.com/libffcv/ffcv) - A drop-in data loading system that dramatically increases data throughput in model training.

* [ImageHash](https://github.com/JohannesBuchner/imagehash) - An image hashing library written in Python.

* [image-match](https://github.com/ProvenanceLabs/image-match) - a simple package for finding approximate image matches from a corpus.

* [pandas-profiling](https://github.com/ydataai/pandas-profiling) - Create HTML data profiling reports for pandas DataFrame.

* [FiftyOne](https://github.com/voxel51/fiftyone) - An open-source tool for building high-quality datasets and computer vision models.

* [dedupe](https://github.com/dedupeio/dedupe) - A python library that uses machine learning to perform fuzzy matching, deduplication and entity resolution quickly on structured data.

* [Ciphey](https://github.com/Ciphey/Ciphey) - Automatically decrypt encryptions without knowing the key or cipher, decode encodings, and crack hashes.

* [jellyfish](https://github.com/jamesturk/jellyfish) - A library for approximate & phonetic matching of strings.

* [TextDistance](https://github.com/life4/textdistance) - Python library for comparing distance between two or more sequences by many algorithms.

* [NLPAUG](https://github.com/makcedward/nlpaug) - Data augmentation for NLP.

* [Texthero](https://github.com/jbesomi/texthero) - A python toolkit to work with text-based dataset, bases on Pandas.

* [ftfy](https://github.com/rspeer/python-ftfy) - Fixes mojibake and other glitches in Unicode text.

* [librosa](https://github.com/librosa/librosa) - A python package for music and audio analysis.

* [Pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface.

* [Audiomentations](https://github.com/iver56/audiomentations) - A Python library for audio data augmentation.

* [torch-audiomentations](https://github.com/asteroid-team/torch-audiomentations) - Fast audio data augmentation in PyTorch, with GPU support.

* [DDSP](https://github.com/magenta/ddsp) - A library of differentiable versions of common DSP functions.

* [TSFRESH](https://github.com/blue-yonder/tsfresh) - Automatic extraction of relevant features from time series.

* [Qdrant](https://github.com/qdrant/qdrant) - A vector similarity search engine for text, image and categorical data in Rust.

* [TA](https://github.com/bukosabino/ta) - A Technical Analysis library useful to do feature engineering from financial time series datasets, based on Pandas and NumPy.

* [stockstats](https://github.com/jealous/stockstats) - Supply a wrapper ``StockDataFrame`` based on the ``pandas.DataFrame`` with inline stock statistics/indicators support.

* [Featuretools](https://github.com/alteryx/featuretools) - An open source python library for automated feature engineering.

* [fancyimpute](https://github.com/iskandr/fancyimpute) **(not actively updated)** - A variety of matrix completion and imputation algorithms implemented in Python.

## Data Visualization

* [Matplotlib](https://github.com/matplotlib/matplotlib) - A comprehensive library for creating static, animated, and interactive visualizations in Python.

* [Seaborn](https://github.com/mwaskom/seaborn) - A high-level interface for drawing statistical graphics, based on Matplotlib.

* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Data Visualization in the browser, from Python.

* [Plotly.js](https://github.com/plotly/plotly.js) - Open-source JavaScript charting library behind Plotly and Dash.

* [Plotly.py](https://github.com/plotly/plotly.py) - An interactive, open-source, and browser-based graphing library for Python, based on Plotly.js.

* [Datapane](https://github.com/datapane/datapane) - An open-source framework to create data science reports in Python.

* [HyperTools](https://github.com/ContextLab/hypertools) - A Python toolbox for gaining geometric insights into high-dimensional data, based on Matplotlib and Seaborn.

* [Dash](https://github.com/plotly/dash) - Analytical Web Apps for Python, R, Julia and Jupyter, based on Plotly.js.

* [mpld3](https://github.com/mpld3/mpld3) - An interactive Matplotlib visualization tool in browser, based on D3.

* [Vega](https://github.com/vega/vega) - A visualization grammar, a declarative format for creating, saving, and sharing interactive visualization designs.

* [Vega-Lite](https://github.com/vega/vega-lite) - Provides a higher-level grammar for visual analysis that generates complete Vega specifications.

* [Vega-Altair](https://github.com/altair-viz/altair) - A declarative statistical visualization library for Python, based on Vega-Lite.

* [PyQtGraph](https://github.com/pyqtgraph/pyqtgraph) - Fast data visualization and GUI tools for scientific / engineering applications.

* [VisPy](https://github.com/vispy/vispy) - A high-performance interactive 2D/3D data visualization library, with OpenGL support.

* [PyVista](https://github.com/pyvista/pyvista) - 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK).

* [Holoviews](https://github.com/holoviz/holoviews) - An open-source Python library designed to make data analysis and visualization seamless and simple.

* [Graphviz](https://github.com/xflr6/graphviz) - Python interface for Graphviz to create and render graphs.

* [PyGraphistry](https://github.com/graphistry/pygraphistry) - A Python library to quickly load, shape, embed, and explore big graphs with the GPU-accelerated Graphistry visual graph analyzer.

* [Apache ECharts](https://github.com/apache/echarts) - A powerful, interactive charting and data visualization library for browser.

* [pyecharts](https://github.com/pyecharts/pyecharts) - A Python visualization interface for Apache ECharts.

* [word_cloud](https://github.com/amueller/word_cloud) - A little word cloud generator in Python.

* [Datashader](https://github.com/holoviz/datashader) - A data rasterization pipeline for automating the process of creating meaningful representations of large amounts of data.

* [Perspective](https://github.com/finos/perspective) - A data visualization and analytics component, especially well-suited for large and/or streaming datasets.

* [ggplot2](https://github.com/tidyverse/ggplot2) - An implementation of the Grammar of Graphics in R.

* [plotnine](https://github.com/has2k1/plotnine) - An implementation of the Grammar of Graphics in Python, based on ggplot2.

* [bqplot](https://github.com/bqplot/bqplot) - An implementation of the Grammar of Graphics for IPython/Jupyter notebooks.

* [D-Tale](https://github.com/man-group/dtale) - A visualization tool for Pandas DataFrame, with ipython notebooks support.

* [missingno](https://github.com/ResidentMario/missingno) - A Python visualization tool for missing data.

* [HiPlot](https://github.com/facebookresearch/hiplot) - A lightweight interactive visualization tool to help AI researchers discover correlations and patterns in high-dimensional data.

* [Sweetviz](https://github.com/fbdesignpro/sweetviz) - Visualize and compare datasets, target values and associations, with one line of code.

* [Netron](https://github.com/lutzroeder/netron) - Visualizer for neural network, deep learning, and machine learning models.

* [livelossplot](https://github.com/stared/livelossplot) - Live training loss plot in Jupyter Notebook for Keras, PyTorch and others.

* [Scattertext](https://github.com/JasonKessler/scattertext) **(not actively updated)** - A tool for finding distinguishing terms in corpora and displaying them in an interactive HTML scatter plot.

## Machine Learning Tutorials

* [labml.ai](https://nn.labml.ai/) - A collection of PyTorch implementations of neural networks and related algorithms, which are documented with explanations and rendered as side-by-side formatted notes.

* [PyTorch official tutorials](https://pytorch.org/tutorials/) - Official tutorials for PyTorch.

* [numpy-100](https://github.com/rougier/numpy-100) - 100 numpy exercises (with solutions).

# Full-Stack Development

## Web Development

* [Mercury](https://github.com/mljar/mercury) - Convert Python notebook to web app and share with non-technical users.

* [D3](https://github.com/d3/d3) - A JavaScript library for visualizing data using web standards.

## Data Management & Processing

* [Apache Flink](https://github.com/apache/flink) - An open source stream processing framework with powerful stream- and batch-processing capabilities.

---

# Academic

## Mathematics

## Paper Reading


---

# Useful Tools

## MacOS

* [Scroll-Reverser](https://github.com/pilotmoon/Scroll-Reverser) - Reverses the direction of macOS scrolling, with independent settings for trackpads and mice.

## Cross-Platform

* [gpustat](https://github.com/wookayin/gpustat) - A simple command-line utility for querying and monitoring GPU status.

* [LANDrop](https://github.com/LANDrop/LANDrop) - A cross-platform tool that you can use to conveniently transfer photos, videos, and other types of files to other devices on the same local network.
