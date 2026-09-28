# ML Engineering Roadmap

Sep 28, 2026

Over 64 sessions you'll go from rusty university math to training, evaluating and deploying machine learning models in production. This picks up where the AI Engineering Roadmap ends: you already write Python and ship LLM features, so this program is about how models work underneath and how to run them reliably.

## What you'll have at the end

By session 64 your portfolio repo will hold these working pieces, each with a short write-up of results:

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

The program runs in nine phases. Math comes first so the later theory has something to stand on; the final project ties everything together.

| # | Phase | Session | What you'll learn |
| --- | --- | --- | --- |
| 1 | Math | Vectors and matrices | Vectors, dot products, matrices as transformations |
| 2 | Math | Linear algebra for ML | Projections, least squares, eigenvectors, SVD intuition |
| 3 | Math | Derivatives and gradients | Derivatives, partial derivatives, gradients |
| 4 | Math | Chain rule and gradient descent | Chain rule, optimizing a function by hand |
| 5 | Math | Probability | Random variables, distributions, Bayes' rule |
| 6 | Math | Statistics | Expectation, variance, sampling, maximum likelihood |
| 7 | Math | Statistical inference | Confidence intervals, hypothesis tests, A/B tests |
| 8 | Data | NumPy in depth | Arrays, broadcasting, vectorized code |
| 9 | Data | pandas and Polars | Wrangling, joins, group-bys |
| 10 | Data | Data cleaning and preparation | Missing values, outliers, data leakage |
| 11 | Data | Exploring and visualizing data | EDA, matplotlib, seaborn |
| 12 | Classical ML | Framing ML problems | Supervised vs unsupervised, bias and variance, splits |
| 13 | Classical ML | Linear regression from scratch | Loss functions, gradient descent in NumPy |
| 14 | Classical ML | Logistic regression from scratch | Classification, cross-entropy, regularization |
| 15 | Classical ML | Evaluation metrics | Precision, recall, ROC-AUC, regression metrics |
| 16 | Classical ML | Cross-validation and tuning | K-fold CV, hyperparameter search |
| 17 | Classical ML | Trees and random forests | Decision trees, bagging, feature importance |
| 18 | Classical ML | Gradient boosting | XGBoost, LightGBM, CatBoost |
| 19 | Classical ML | Feature engineering | Encoding, scaling, building features |
| 20 | Classical ML | Pipelines and experiment tracking | scikit-learn pipelines, MLflow |
| 21 | Classical ML | SVMs and nearest neighbors | Margins, kernels, kNN |
| 22 | Classical ML | Clustering | k-means, DBSCAN, hierarchical clustering |
| 23 | Classical ML | Dimensionality reduction | PCA, t-SNE, UMAP |
| 24 | Project | Tabular project, part 1 | Problem setup, baseline, validation plan |
| 25 | Project | Tabular project, part 2 | Iteration, final model, write-up |
| 26 | Specialized | Time series, part 1 | Trend, seasonality, classical forecasting |
| 27 | Specialized | Time series, part 2 | ML forecasting, backtesting |
| 28 | Specialized | Recommender systems, part 1 | Collaborative filtering, matrix factorization |
| 29 | Specialized | Recommender systems, part 2 | Content-based and hybrid, ranking metrics |
| 30 | Specialized | Anomaly detection | Statistical methods, isolation forest |
| 31 | Specialized | Bayesian modeling | Priors, posteriors, PyMC |
| 32 | Deep learning | Neural networks from scratch, part 1 | Neurons, layers, forward pass |
| 33 | Deep learning | Neural networks from scratch, part 2 | Backpropagation by hand |
| 34 | Deep learning | PyTorch fundamentals, part 1 | Tensors, autograd |
| 35 | Deep learning | PyTorch fundamentals, part 2 | Modules, data loaders, training loops |
| 36 | Deep learning | Training deep networks well | Initialization, normalization, dropout, learning rate schedules |
| 37 | Deep learning | GPU training basics | CUDA, mixed precision, cloud GPUs |
| 38 | Deep learning | CNNs and vision, part 1 | Convolutions, image classification |
| 39 | Deep learning | CNNs and vision, part 2 | Augmentation, modern architectures |
| 40 | Deep learning | Transfer learning and fine-tuning | Adapting pretrained models |
| 41 | Deep learning | RNNs and LSTMs | Sequence models and their limits |
| 42 | Deep learning | Tokenization and embeddings | BPE, embedding spaces |
| 43 | Deep learning | Transformers from scratch, part 1 | Attention |
| 44 | Deep learning | Transformers from scratch, part 2 | The full transformer block |
| 45 | Deep learning | Transformers from scratch, part 3 | Training a tiny transformer |
| 46 | Deep learning | Hugging Face ecosystem | Transformers, Datasets, the Hub |
| 47 | Deep learning | Generative models, part 1 | Autoencoders and VAEs |
| 48 | Deep learning | Generative models, part 2 | Diffusion models |
| 49 | Deep learning | Graph neural networks | Message passing, PyTorch Geometric |
| 50 | Deep learning | Reinforcement learning, part 1 | MDPs, Q-learning |
| 51 | Deep learning | Reinforcement learning, part 2 | Policy gradients, how RLHF uses them |
| 52 | LLM training | Fine-tuning LLMs, part 1 | LoRA, QLoRA |
| 53 | LLM training | Fine-tuning LLMs, part 2 | Evaluating against the base model |
| 54 | LLM training | Quantization and compression | Quantization, distillation, pruning |
| 55 | LLM training | Small language model, part 1 | Data, tokenizer, model setup |
| 56 | LLM training | Small language model, part 2 | Training, sampling, what scale changes |
| 57 | MLOps | Model serving | Packaging models, serving APIs, containers |
| 58 | MLOps | Batch vs real-time inference | Batch jobs, online serving, feature stores |
| 59 | MLOps | Monitoring and drift | Data drift, model decay, alerting |
| 60 | MLOps | ML system design | Designing ML systems end to end |
| 61 | Final project | Final project, part 1 | Problem, data pipeline, baseline |
| 62 | Final project | Final project, part 2 | Training and tracked experiments |
| 63 | Final project | Final project, part 3 | Serving and monitoring |
| 64 | Final project | Final project, part 4 | Demo, write-up, next steps |
