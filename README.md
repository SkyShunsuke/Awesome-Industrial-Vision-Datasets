# Awesome-Industrial-Vision-Datasets

A curated collection of publicly available visual datasets focused on industrial inspection. This repository aims to provide a comprehensive overview of datasets used in computer vision tasks for industrial applications, such as defect detection, quality control, and manufacturing monitoring. Datasets are summarized in a tabular format for easy comparison and access.

We include key properties for each dataset to help researchers and practitioners quickly evaluate suitability. Note: This is a work-in-progress list with placeholder data. Contributions are welcome to add real datasets!

## Datasets

The following table lists datasets with essential details. For quick navigation:
- Sort by columns in your Markdown viewer or convert to HTML for interactive tables.
- Links are provided where available (placeholders for now).
- Use the search function in your browser to filter by domain or year.

| Dataset Name          | Dataset Scale          | Dataset Domain          | License       | Availability | Annotation          | Dataset Link                          | Provider              | Source (Real Objects, Simulated) | Dataset Quality | Proposed Year | Citation (BibTeX) |
|-----------------------|------------------------|-------------------------|---------------|--------------|---------------------|---------------------------------------|-----------------------|----------------------------------|-----------------|---------------|-------------------|
| MVTec AD             | 5,000 images (15 categories) | Manufacturing defects  | CC BY-NC-SA 4.0 | Public     | Pixel-level masks  | [Link](https://example.com/mvtec)    | MVTec Software GmbH  | Real Objects                    | High (diverse anomalies) | 2019         | @article{bergmann2019mvtec,<br>  title={MVTEC AD--A Comprehensive Real-World Dataset for Unsupervised Anomaly Detection},<br>  author={Bergmann, Paul and others},<br>  journal={CVPR},<br>  year={2019}<br>} |
| KolektorSDD          | 3,000 images          | Surface defects in electronics | MIT          | Public     | Bounding boxes     | [Link](https://example.com/kolektorsdd) | University of Ljubljana | Real Objects                    | Medium (imbalanced classes) | 2018         | @article{tabernik2019kolektor,<br>  title={Segmentation-Based Deep-Learning Approach for Surface-Defect Detection},<br>  author={Tabernik, Domen and others},<br>  journal={Journal of Intelligent Manufacturing},<br>  year={2019}<br>} |
| DAGM 2007            | 1,150 images (10 classes) | Optical inspection     | Proprietary  | Public (with registration) | Pixel-level        | [Link](https://example.com/dagm)     | DAGM                  | Simulated                       | High (controlled lighting) | 2007         | @inproceedings{weimer2007dagm,<br>  title={Weakly Supervised Learning for Industrial Optical Inspection},<br>  author={Weimer, Daniel and others},<br>  booktitle={DAGM Symposium},<br>  year={2007}<br>} |
| NEU Surface Defects  | 1,800 images (6 types) | Steel surface defects  | CC0          | Public     | None (class-level) | [Link](https://example.com/neu)      | Northeastern University | Real Objects                    | Medium (noisy backgrounds) | 2013         | @article{song2013neu,<br>  title={A Steel Surface Defect Database for Research},<br>  author={Song, Kechen and Yan, Yunhui},<br>  journal={Measurement Science and Technology},<br>  year={2013}<br>} |
| Simulated FabDefects | 10,000 synthetic images | Fabric anomalies       | Apache 2.0   | Public     | Semantic segmentation | [Link](https://example.com/fabdefects) | Synthetic Data Corp  | Simulated                       | Low (lacks real-world variance) | 2022         | @misc{simfab2022,<br>  title={Synthetic Fabric Defect Dataset},<br>  author={Anon},<br>  year={2022},<br>  howpublished={\url{https://example.com}}<br>} |

### Key Explanations
- **Dataset Scale**: Approximate number of images/samples and categories.
- **Dataset Domain**: Primary industrial application area.
- **License**: Usage permissions (e.g., for research/commercial).
- **Availability**: Public, restricted, or private.
- **Annotation**: Type of labels provided (e.g., pixel-level, bounding boxes).
- **Dataset Link**: Direct download or access URL.
- **Provider**: Organization or authors responsible.
- **Source**: Whether data is from real-world captures or simulations.
- **Dataset Quality**: Subjective assessment based on diversity, balance, and realism (High/Medium/Low).
- **Proposed Year**: Year of initial release or publication.
- **Citation (BibTeX)**: Ready-to-use BibTeX for referencing.

## Utilities
This section can include tools or scripts for dataset handling (e.g., download scripts, preprocessing code). Currently placeholders:
- `download_datasets.py`: A Python script to batch-download datasets from links.
- `visualize_anomalies.ipynb`: Jupyter notebook for quick visualization of samples.

## Other Dataset Reviews
Here are links to related surveys and reviews for deeper insights (placeholders):
- [A Survey on Industrial Anomaly Detection Datasets](https://example.com/survey1) - Comprehensive review from IEEE (2023).
- [Benchmarking Visual Anomaly Detection](https://example.com/benchmark) - Paper comparing 20+ datasets (2024).
- [Awesome Anomaly Detection](https://github.com/yzhao062/anomaly-detection-resources) - Broader repo on anomaly detection resources.

## Contributing
Feel free to submit pull requests to add real datasets, update placeholders, or improve the table. Follow the template above for new entries.

## License
This repository is licensed under MIT. Individual datasets follow their own licenses.
