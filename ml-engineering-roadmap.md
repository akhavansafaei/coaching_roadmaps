# ML Engineering Roadmap

Sep 28, 2026

Over 91 sessions you'll go from rusty university math to training, evaluating and deploying machine learning models in production. This picks up where the AI Engineering Roadmap ends: you already write Python and ship LLM features, so this program is about how models work underneath and how to run them reliably.

## What you'll have at the end

By session 91 your portfolio repo will hold these working pieces, each with a short write-up of results:

- **From-scratch implementations** of linear and logistic regression, a neural network with backpropagation, a transformer and a small language model. These prove you understand what libraries do for you.
- **A Kaggle-style tabular project** with a documented pipeline, cross-validation, gradient boosting and an honest comparison of models, explained with SHAP.
- **Mini-projects in six specialized areas:** a time series forecast, a recommender, an anomaly detector, a Bayesian model, a classical NLP model and a causal analysis.
- **Deep learning work** in PyTorch: an image classifier, an object detector, a BERT-based text model, a vision transformer, a fine-tuned pretrained model, a diffusion or GAN demo, a graph model and a reinforcement learning agent.
- **A fine-tuned LLM** trained with LoRA, aligned with DPO, quantized, and measured against the base model.
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

The program runs in nine phases, with two review sessions (32 and 71) to catch up and revisit weak spots. Math comes first so the later theory has something to stand on; the final project ties everything together.

| # | Phase | Session | What you'll learn |
| --- | --- | --- | --- |
| 1 | Math | Vectors and matrices | Dot products, matrix multiplication, matrices as transformations |
| 2 | Math | Eigenvectors and SVD | Least squares, eigendecomposition, SVD, why PCA works |
| 3 | Math | Derivatives and gradients | Partial derivatives, gradients, Jacobians |
| 4 | Math | Chain rule and gradient descent | Chain rule, optimizing a function by hand |
| 5 | Math | Probability and distributions | Bayes' rule, common distributions, expectation, variance |
| 6 | Math | Statistics and inference | Maximum likelihood, confidence intervals, A/B tests |
| 7 | Data | NumPy essentials | Arrays, broadcasting, vectorized code |
| 8 | Data | pandas and Polars | Wrangling, joins, group-bys |
| 9 | Data | Cleaning, EDA and visualization | Missing values, leakage, exploring and plotting data |
| 10 | Classical ML | Framing ML problems | Supervised vs unsupervised, bias and variance, splits |
| 11 | Classical ML | Linear regression from scratch, part 1 | Loss functions, closed-form solution |
| 12 | Classical ML | Linear regression from scratch, part 2 | Gradient descent in NumPy, regularization |
| 13 | Classical ML | Logistic regression from scratch | Classification, cross-entropy, decision boundaries |
| 14 | Classical ML | Classification metrics | Precision, recall, ROC-AUC, imbalanced data |
| 15 | Classical ML | Regression metrics and calibration | MAE, RMSE, calibration, choosing a metric |
| 16 | Classical ML | Cross-validation and tuning | K-fold CV, hyperparameter search |
| 17 | Classical ML | Trees and random forests | Decision trees, bagging, feature importance |
| 18 | Classical ML | Gradient boosting, part 1 | How boosting works, XGBoost |
| 19 | Classical ML | Gradient boosting, part 2 | LightGBM, CatBoost, tuning boosted models |
| 20 | Classical ML | Stacking and blending | Combining models, when ensembles help |
| 21 | Classical ML | Feature engineering, part 1 | Encoding, scaling, missing-value strategies |
| 22 | Classical ML | Feature engineering, part 2 | Dates, text, interactions, feature selection |
| 23 | Classical ML | scikit-learn pipelines | Pipelines, column transformers, reproducibility |
| 24 | Classical ML | Experiment tracking | MLflow, comparing runs |
| 25 | Classical ML | Model interpretability | SHAP, permutation importance, partial dependence |
| 26 | Classical ML | SVMs and nearest neighbors | Margins, kernels, kNN |
| 27 | Classical ML | Clustering | k-means, DBSCAN, hierarchical clustering |
| 28 | Classical ML | Dimensionality reduction | PCA, t-SNE, UMAP |
| 29 | Project | Tabular project, part 1 | Problem setup, EDA, validation plan |
| 30 | Project | Tabular project, part 2 | Baselines, features, boosting |
| 31 | Project | Tabular project, part 3 | Final model, error analysis, write-up |
| 32 | Review | Review and catch-up | Revisit weak spots from sessions 1–31 |
| 33 | Specialized | Time series, part 1 | Trend, seasonality, classical forecasting |
| 34 | Specialized | Time series, part 2 | ML forecasting, backtesting |
| 35 | Specialized | Recommender systems, part 1 | Collaborative filtering, matrix factorization |
| 36 | Specialized | Recommender systems, part 2 | Content-based and hybrid, ranking metrics |
| 37 | Specialized | Anomaly detection | Statistical methods, isolation forest |
| 38 | Specialized | Bayesian modeling, part 1 | Priors, posteriors, Bayesian thinking |
| 39 | Specialized | Bayesian modeling, part 2 | PyMC, hierarchical models |
| 40 | Specialized | Classical NLP | TF-IDF, text classification, topic models |
| 41 | Specialized | Causal inference basics | Confounding, experiments vs observational data, uplift |
| 42 | Deep learning | Neural networks from scratch, part 1 | Neurons, layers, forward pass |
| 43 | Deep learning | Neural networks from scratch, part 2 | Backpropagation by hand |
| 44 | Deep learning | Neural networks from scratch, part 3 | Training your network on real data |
| 45 | Deep learning | PyTorch fundamentals, part 1 | Tensors, autograd |
| 46 | Deep learning | PyTorch fundamentals, part 2 | Modules, data loaders, training loops |
| 47 | Deep learning | Training deep networks well, part 1 | Optimizers, initialization, learning rate schedules |
| 48 | Deep learning | Training deep networks well, part 2 | Normalization, dropout, debugging training |
| 49 | Deep learning | GPU training basics | CUDA, mixed precision, cloud GPUs |
| 50 | Deep learning | CNNs and vision, part 1 | Convolutions, image classification |
| 51 | Deep learning | CNNs and vision, part 2 | Augmentation, modern architectures |
| 52 | Deep learning | Object detection and segmentation | YOLO-style detectors, U-Net |
| 53 | Deep learning | Transfer learning and fine-tuning | Adapting pretrained models |
| 54 | Deep learning | Self-supervised and contrastive learning | Learning without labels, SimCLR-style training |
| 55 | Deep learning | RNNs and LSTMs | Sequence models and their limits |
| 56 | Deep learning | Tokenization and embeddings | BPE, embedding spaces |
| 57 | Deep learning | Transformers from scratch, part 1 | Attention |
| 58 | Deep learning | Transformers from scratch, part 2 | The full transformer block |
| 59 | Deep learning | Transformers from scratch, part 3 | Building a GPT-style model |
| 60 | Deep learning | Transformers from scratch, part 4 | Training and sampling a tiny transformer |
| 61 | Deep learning | Encoder models for NLP | BERT, text classification, named entity recognition |
| 62 | Deep learning | Vision transformers and CLIP | ViT, image-text models |
| 63 | Deep learning | Hugging Face ecosystem | Transformers, Datasets, the Hub |
| 64 | Deep learning | Generative models, part 1 | Autoencoders and VAEs |
| 65 | Deep learning | Generative models, part 2 | GANs |
| 66 | Deep learning | Generative models, part 3 | Diffusion models |
| 67 | Deep learning | Graph neural networks | Message passing, PyTorch Geometric |
| 68 | Deep learning | Reinforcement learning, part 1 | MDPs, Q-learning |
| 69 | Deep learning | Reinforcement learning, part 2 | Deep Q-networks |
| 70 | Deep learning | Reinforcement learning, part 3 | Policy gradients, PPO |
| 71 | Review | Review and catch-up | Revisit weak spots from sessions 33–70 |
| 72 | LLM training | Modern LLM architecture | RoPE, KV cache, mixture of experts, efficient attention |
| 73 | LLM training | Fine-tuning LLMs, part 1 | When to fine-tune, preparing a dataset |
| 74 | LLM training | Fine-tuning LLMs, part 2 | LoRA, QLoRA |
| 75 | LLM training | Fine-tuning LLMs, part 3 | Evaluating against the base model |
| 76 | LLM training | Alignment: RLHF and DPO | Preference data, reward models, DPO |
| 77 | LLM training | Quantization and compression | Quantization, distillation, pruning |
| 78 | LLM training | Small language model, part 1 | Data, tokenizer, model setup |
| 79 | LLM training | Small language model, part 2 | Training, sampling, what scale changes |
| 80 | MLOps | Model serving, part 1 | Packaging models, serving APIs |
| 81 | MLOps | Model serving, part 2 | Containers, deployment, scaling |
| 82 | MLOps | Batch vs real-time inference | Batch jobs, online serving, feature stores |
| 83 | MLOps | Monitoring and drift, part 1 | Data drift, model decay, detection |
| 84 | MLOps | Monitoring and drift, part 2 | Alerting, retraining triggers |
| 85 | MLOps | ML system design, part 1 | A framework for designing ML systems |
| 86 | MLOps | ML system design, part 2 | Mock design interview |
| 87 | Final project | Final project, part 1 | Problem, data pipeline, baseline |
| 88 | Final project | Final project, part 2 | Training and tracked experiments |
| 89 | Final project | Final project, part 3 | Serving |
| 90 | Final project | Final project, part 4 | Monitoring and retraining |
| 91 | Final project | Final project, part 5 | Demo, write-up, next steps |
