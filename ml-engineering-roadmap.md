# ML Engineering Roadmap

Sep 28, 2026

Over 88 sessions you'll go from rusty university math to training, evaluating and deploying machine learning models in production. This picks up where the AI Engineering Roadmap ends: you already write Python and ship LLM features, so this program is about how models work underneath and how to run them reliably.

## What you'll have at the end

By session 88 your portfolio repo will hold these working pieces, each with a short write-up of results:

- **From-scratch implementations** of linear and logistic regression, a neural network with backpropagation, a transformer and a small language model. These prove you understand what libraries do for you.
- **A Kaggle-style tabular project** with a documented pipeline, cross-validation, gradient boosting and an honest comparison of models.
- **Mini-projects in four specialized areas:** a time series forecast, a recommender, an anomaly detector and a Bayesian model.
- **Deep learning work** in PyTorch: an image classifier, a fine-tuned pretrained model, a diffusion or VAE demo, a graph model and a reinforcement learning agent.
- **A fine-tuned LLM** trained with LoRA, quantized, and measured against the base model.
- **An end-to-end production ML system:** data pipeline, tracked experiments, a served model, drift monitoring and a system design write-up.

You'll also be able to read the math in ML papers and docs without getting stuck, and to hold your own in ML system design interviews.

## How we'll work together

Each session is a live call with me plus an assignment you build before the next one. Every assignment ends with code that runs or a result you can show.

- **Live call (60 min):** we review your last assignment, go through the new concepts, and start the next build together.
- **Your time between calls:** reading, exercises and building the assignment. Math sessions lean on pen and paper; the rest are notebooks and code.
- **Pace:** two or three sessions a week. Keep it steady rather than fast; theory needs time to settle.
- **One repo:** keep everything in a single Git repo with a folder per session. Push before each call so I can review it.
- **Checkpoints:** each session has a "You're done when" line. If you can't meet it, tell me early and we'll adjust. Don't skip ahead, especially past the math.
- **Build it, then use the library:** for most core ideas you'll write a small version by hand first, then switch to scikit-learn or PyTorch. It's slower at first and pays off every time something breaks.
- **Between calls:** send questions any time. Being stuck for more than an hour on setup or a math step is a message, not a struggle.
- **GPU costs:** most work runs on your laptop or free Colab and Kaggle GPUs. Fine-tuning and training the small language model may need a rented GPU for a few hours; budget roughly $20–50 for the whole program.

## Sessions at a glance

The program runs in nine phases, with two review sessions (39 and 70) to catch up and revisit weak spots. Math comes first so the later theory has something to stand on; the final project ties everything together.

| # | Phase | Session | What you'll learn |
| --- | --- | --- | --- |
| 1 | Math | Vectors | Vectors, norms, dot products, geometric intuition |
| 2 | Math | Matrices | Matrix multiplication, matrices as transformations |
| 3 | Math | Linear systems and least squares | Solving systems, projections, least squares |
| 4 | Math | Eigenvectors and SVD | Eigendecomposition, SVD, why PCA works |
| 5 | Math | Derivatives | Derivative rules, slope intuition |
| 6 | Math | Multivariable calculus | Partial derivatives, gradients, Jacobians |
| 7 | Math | Chain rule and gradient descent | Chain rule, optimizing a function by hand |
| 8 | Math | Probability | Random variables, conditional probability, Bayes' rule |
| 9 | Math | Distributions | Common distributions, expectation, variance |
| 10 | Math | Statistics and likelihood | Sampling, estimation, maximum likelihood |
| 11 | Math | Statistical inference | Confidence intervals, hypothesis tests, A/B tests |
| 12 | Data | NumPy, part 1 | Arrays, indexing, broadcasting |
| 13 | Data | NumPy, part 2 | Vectorized code, linear algebra in NumPy |
| 14 | Data | pandas | Wrangling, joins, group-bys |
| 15 | Data | Polars and larger data | Lazy queries, performance, when to switch |
| 16 | Data | Data cleaning and preparation | Missing values, outliers, data leakage |
| 17 | Data | Exploratory data analysis | Distributions, correlations, asking questions of data |
| 18 | Data | Data visualization | matplotlib, seaborn, charts that explain |
| 19 | Classical ML | Framing ML problems | Supervised vs unsupervised, bias and variance, splits |
| 20 | Classical ML | Linear regression from scratch, part 1 | Loss functions, closed-form solution |
| 21 | Classical ML | Linear regression from scratch, part 2 | Gradient descent in NumPy, regularization |
| 22 | Classical ML | Logistic regression from scratch | Classification, cross-entropy, decision boundaries |
| 23 | Classical ML | Classification metrics | Precision, recall, ROC-AUC, imbalanced data |
| 24 | Classical ML | Regression metrics and calibration | MAE, RMSE, calibration, choosing a metric |
| 25 | Classical ML | Cross-validation and tuning | K-fold CV, hyperparameter search |
| 26 | Classical ML | Trees and random forests | Decision trees, bagging, feature importance |
| 27 | Classical ML | Gradient boosting, part 1 | How boosting works, XGBoost |
| 28 | Classical ML | Gradient boosting, part 2 | LightGBM, CatBoost, tuning boosted models |
| 29 | Classical ML | Feature engineering, part 1 | Encoding, scaling, missing-value strategies |
| 30 | Classical ML | Feature engineering, part 2 | Dates, text, interactions, feature selection |
| 31 | Classical ML | scikit-learn pipelines | Pipelines, column transformers, reproducibility |
| 32 | Classical ML | Experiment tracking | MLflow, comparing runs |
| 33 | Classical ML | SVMs and nearest neighbors | Margins, kernels, kNN |
| 34 | Classical ML | Clustering | k-means, DBSCAN, hierarchical clustering |
| 35 | Classical ML | Dimensionality reduction | PCA, t-SNE, UMAP |
| 36 | Project | Tabular project, part 1 | Problem setup, EDA, validation plan |
| 37 | Project | Tabular project, part 2 | Baselines, features, boosting |
| 38 | Project | Tabular project, part 3 | Final model, error analysis, write-up |
| 39 | Review | Review and catch-up | Revisit weak spots from sessions 1–38 |
| 40 | Specialized | Time series, part 1 | Trend, seasonality, classical forecasting |
| 41 | Specialized | Time series, part 2 | ML forecasting, backtesting |
| 42 | Specialized | Recommender systems, part 1 | Collaborative filtering, matrix factorization |
| 43 | Specialized | Recommender systems, part 2 | Content-based and hybrid, ranking metrics |
| 44 | Specialized | Anomaly detection | Statistical methods, isolation forest |
| 45 | Specialized | Bayesian modeling, part 1 | Priors, posteriors, Bayesian thinking |
| 46 | Specialized | Bayesian modeling, part 2 | PyMC, hierarchical models |
| 47 | Deep learning | Neural networks from scratch, part 1 | Neurons, layers, forward pass |
| 48 | Deep learning | Neural networks from scratch, part 2 | Backpropagation by hand |
| 49 | Deep learning | Neural networks from scratch, part 3 | Training your network on real data |
| 50 | Deep learning | PyTorch fundamentals, part 1 | Tensors, autograd |
| 51 | Deep learning | PyTorch fundamentals, part 2 | Modules, data loaders, training loops |
| 52 | Deep learning | Training deep networks well, part 1 | Optimizers, initialization, learning rate schedules |
| 53 | Deep learning | Training deep networks well, part 2 | Normalization, dropout, debugging training |
| 54 | Deep learning | GPU training basics | CUDA, mixed precision, cloud GPUs |
| 55 | Deep learning | CNNs and vision, part 1 | Convolutions, image classification |
| 56 | Deep learning | CNNs and vision, part 2 | Augmentation, modern architectures |
| 57 | Deep learning | Transfer learning and fine-tuning | Adapting pretrained models |
| 58 | Deep learning | RNNs and LSTMs | Sequence models and their limits |
| 59 | Deep learning | Tokenization and embeddings | BPE, embedding spaces |
| 60 | Deep learning | Transformers from scratch, part 1 | Attention |
| 61 | Deep learning | Transformers from scratch, part 2 | The full transformer block |
| 62 | Deep learning | Transformers from scratch, part 3 | Building a GPT-style model |
| 63 | Deep learning | Transformers from scratch, part 4 | Training and sampling a tiny transformer |
| 64 | Deep learning | Hugging Face ecosystem | Transformers, Datasets, the Hub |
| 65 | Deep learning | Generative models, part 1 | Autoencoders and VAEs |
| 66 | Deep learning | Generative models, part 2 | Diffusion models |
| 67 | Deep learning | Graph neural networks | Message passing, PyTorch Geometric |
| 68 | Deep learning | Reinforcement learning, part 1 | MDPs, Q-learning |
| 69 | Deep learning | Reinforcement learning, part 2 | Policy gradients, how RLHF uses them |
| 70 | Review | Review and catch-up | Revisit weak spots from sessions 40–69 |
| 71 | LLM training | Fine-tuning LLMs, part 1 | When to fine-tune, preparing a dataset |
| 72 | LLM training | Fine-tuning LLMs, part 2 | LoRA, QLoRA |
| 73 | LLM training | Fine-tuning LLMs, part 3 | Evaluating against the base model |
| 74 | LLM training | Quantization and compression | Quantization, distillation, pruning |
| 75 | LLM training | Small language model, part 1 | Data, tokenizer, model setup |
| 76 | LLM training | Small language model, part 2 | Training, sampling, what scale changes |
| 77 | MLOps | Model serving, part 1 | Packaging models, serving APIs |
| 78 | MLOps | Model serving, part 2 | Containers, deployment, scaling |
| 79 | MLOps | Batch vs real-time inference | Batch jobs, online serving, feature stores |
| 80 | MLOps | Monitoring and drift, part 1 | Data drift, model decay, detection |
| 81 | MLOps | Monitoring and drift, part 2 | Alerting, retraining triggers |
| 82 | MLOps | ML system design, part 1 | A framework for designing ML systems |
| 83 | MLOps | ML system design, part 2 | Mock design interview |
| 84 | Final project | Final project, part 1 | Problem, data pipeline, baseline |
| 85 | Final project | Final project, part 2 | Training and tracked experiments |
| 86 | Final project | Final project, part 3 | Serving |
| 87 | Final project | Final project, part 4 | Monitoring and retraining |
| 88 | Final project | Final project, part 5 | Demo, write-up, next steps |
