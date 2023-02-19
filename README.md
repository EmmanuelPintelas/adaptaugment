# LCA-A-Novel-Image-Augmentation-Framework-for-Few-Shot-Learning-Tasks
LCA: Less Confident Augmentations

The evaluation protocol is based on [1], [2].
[1]	Ullah, I., Carrión-Ojeda, D., Escalera, S., Guyon, I. M., Huisman, M., Mohr, F., ... & Vu, P. A. (2022). Meta-Album: Multi-domain Meta-Dataset for Few-Shot Image Classification. In Thirty-sixth Conference on Neural Information Processing Systems Datasets and Benchmarks Track.
[2]	Carrión-Ojeda, D., Chen, H., El Baz, A., Escalera, S., Guan, C., Guyon, I., ... & Zhu, W. (2022, December). NeurIPS’22 Cross-Domain MetaDL competition: Design and baseline results. In ECMLPKDD Workshop on Meta-Knowledge Transfer (pp. 24-37). PMLR.


To run the framework:

1. Download repository
2. Download cross domains datasets from: https://www.kaggle.com/datasets/emmanuelpintelas/few-shot-datasets, (due to storage limitations of github, the datasets are stored in other public cloud storage)
and then _copy_ the contents of data A and data B and _paste_ to the empty folders data A and data B  respectively, of this github repository.
3. Then go to _run_ script which runs the whole expiremental simulations
4. In the _run_ script you can specify the number of _test_tasks_per_dataset_, the domains to meta-train/test, and the selection of models (all models codes is on _baselines_ folder)
