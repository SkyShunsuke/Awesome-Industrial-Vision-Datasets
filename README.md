# Awesome-Industrial-Vision-Datasets

A curated collection of publicly available visual datasets focused on industrial inspection. This repository aims to provide a comprehensive overview of datasets used in computer vision tasks for industrial applications, such as defect detection, quality control, and manufacturing monitoring. Datasets are summarized in a tabular format for easy comparison and access.

We include key properties for each dataset to help researchers and practitioners quickly evaluate suitability. Note: This is a work-in-progress list with placeholder data. Contributions are welcome to add real datasets!

## Datasets

The following table lists datasets with essential details. For quick navigation:
- Sort by columns in your Markdown viewer or convert to HTML for interactive tables.
- Links are provided where available (placeholders for now).
- Use the search function in your browser to filter by domain or year.

| Dataset Name | #Images | Domain | License | Annotation | Dataset Link | Provider | Source | Quality | Proposed Year | Citation (BibTeX) |
|--------------|---------|--------|---------|------------|--------------|----------|--------|---------|---------------|-------------------|
| **MCID** | 285 | Mechanical component inspection ⚙️ | N/A | Pixel-level Anomaly | [Link](https://www.kaggle.com/datasets/satishpaladi11/mechanic-component-images-normal-defected) | N/A | Real Objects | Mid (moderate resolution) | 2025/06/08 | [mcid2020](bibtex/mcid2020.md) |
| **3CAD** | 27039 | Electronics 💻 / Products 📦 / Metal 🔩 | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://github.com/EnquanYang2022/3CAD) | Shanghai Univ. | Real Objects | High | 2025/05/29 | [3cad2025](bibtex/3cad2025.md) |
| **RealIAD D^3** | 8450 | Mechanics ⚙️, Electronics 💻, Toy 🧸 | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://huggingface.co/datasets/YoutuLab/IAD) | Youtu Lab | Real Objects | High | 2025/04/19 | [realiadd32025](bibtex/realiadd32025.md) |
| **ISPAD** | 559049 | Mechanics ⚙️ | CC BY-NC-SA 4.0 | Pixel-level Anomaly | [Link](https://zenodo.org/record/911043) | Polymer Competence Center Leoben GmbH | Real Objects | High | 2025/03/06 | [ispad2025](bibtex/ispad2025.md) |
| **ADFI** | 8 | Toy 🧸, Groceries 🛒, Food & Drinks 🍔, Infrastructure 🏗️, Person 🧍, Electronics 💻 | MIT | Image-level Anomaly | [Link](https://adfi.jp/download/#dataset) | ADFI | Real Objects | Mid | 2025/01/01 | [adfi2025](bibtex/adfi2025.md) |
| **MANTA** | 137338 | Agriculture 🌾, Medicine 💊, Mechanics ⚙️, Groceries 🛒 | CC BY-NC-SA 4.0 | Image-level Anomaly, Caption | [Link](https://grainnet.github.io/MANTA) | UNSW Sydney | Large-scale Repo | High | 2024/12/06 | [manta2024](bibtex/manta2025.md) |
| **ILID** | 12537 | Natural Image 🏞️, Groceries 🛒, Mechanics ⚙️ | N/A | Caption | [Link](https://github.com/kenomo/ilid) | Hamburg University of Technology | Online Catalogs | Mid | 2024/11/27 | [ilid2024](bibtex/ilid2024.md) |
| **AD3** | 10986 | Agriculture 🌾, Electronics 💻, Food & Drinks 🍔, Natural Image 🏞️, Hydraulics 💧, Mechanics ⚙️, Medical 🏥, Metal 🔩, Office 🏢, Pneumatics 🌀, Tools 🛠️ | CC-BY 4.0 | Pixel-level Anomaly | [Link](https://fordatis.fraunhofer.de/handle/fordatis/363) | Fraunhofer IPK | Real Objects | High | 2024/11/21 | [ad32024](bibtex/ad32024.md) |
| **ELPV** | 2624 | Electronics 💻 | CC BY-NC-SA 4.0 | Image-level Anomaly, Pixel-level Anomaly | [Link](https://github.com/zae-bayern/elpv-dataset) | N/A | Real Objects | Low | 2024/10/14 | [elpv2024](bibtex/elpv2024.md) |
| **CableInspect-AD** | 10821 | Infrastructure 🏗️ | CC BY-SA 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](https://drive.google.com/file/d/126i30i7dRkcf4E5k7x8yysay3Snv6NXv/view) | NeurIPS2024 | Real Objects | High | 2024/09/30 | [cableinspect2024](bibtex/cableinspect2024.md) |
| **Casting** | 7348 | Mechanics ⚙️ / Metal 🔩 | CC-BY-NC-ND 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](https://www.kaggle.com/datasets/ravirajsinh45/real-life-industrial-dataset-of-casting-product/data) | N/A | Real Objects | High | 2024/08/06 | [casting2023](bibtex/casting2024.md) |
| **MSDD** | 138585 | Metal 🔩 | CC-BY 4.0 | Pixel-level Anomaly | [Link](https://scidb.cn/en/ae48d8) | Beijing University | Real Objects | Mid | 2024/07/23 | [msdd2024](bibtex/msdd2024.md) |
| **WFDD** | 4141 | Fabric 🧵 / Textures 🎨 | MIT | Pixel-level Anomaly, Image-level Anomaly | [Link](https://drive.google.com/file/d/1P8yfNnfoFsb0Lv-HRzkPQ2nD9qsL--Vk/view?usp=sharing/) | CASI | Real Objects | Mid | 2024/06/12 | [wfdd2024](bibtex/wfdd2024.md) |
| **BTAD** | 2830 | Textures 🎨 | CC BY-NC-SA 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](https://github.com/pan-ali/VT-ADL) | beenTech | Real Objects | Mid | 2024/06/01 | [btad2024](bibtex/btad2024.md) |
| **Anomaly-ShapeNet** | 1600 | Products 📦 / Groceries 🛒 | CC-BY 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](https://github.com/Chopper-233/Anomaly-ShapeNet) | ShanghaiTech University | Real Objects | High | 2024/06/01 | [anomalyshapenet2024](bibtex/anomalyshapenet2024.md) |
| **Real-IAD** | 150000 | Food & Drinks 🍔, Mechanics ⚙️, Tools 🛠️, Electronics 💻 | CC-BY-NC-SA-4.0 | Pixel-level Anomaly | [Link](https://huggingface.co/datasets/Real-IAD/Real-IAD) | Tencent | Real Objects | High | 2024/03/19 | [realiad2024](bibtex/realiad2024.md) |
| **MSAD** | 720 | Pedestrians 🚶, Cars 🚗, Trains 🚆 | CC-BY 4.0 | Image-level Anomaly | [Link](https://msad-dataset.github.io/) | Australian National University | YouTube, Bilibili, Itemfix | High | 2024/02/07 | [msad2024](bibtex/msad2024.md) |
| **LFDDD** | 34684 | Textures 🎨 / Fabric 🧵 | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://kailashhambarde.github.io/Lusitano/) | University of Beira Interior | Real Objects | High | 2024/01/01 | [lfddd2024](bibtex/lfddd2024.md) |
| **CUVA** | 3345097 | Natural Image 🏞️ | CC BY-NC-SA 4.0 | Image-level Anomaly | [Link](https://camo.githubusercontent.com/cd48d95d1e3f4763a8890f2ec179cbfcbcade48fba86050a1db833d9baee887d/68747470733a2f2f68756767696e67666163652e636f2f64617461736574732f68756767696e67666163652f6261646765732f7261772f6d61696e2f646174617365742d6f6e2d68662d6d642d6461726b2e737667) | Beijing Univ. | YouTube, Bilibili | High | 2024/01/01 | [cuva2024](bibtex/cuva2021.md) |
| **PAD** | 10000 | Toy 🧸 | CC BY-NC-SA 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](https://github.com/EricLee0224/PAD) | AIR, Tsinghua University | Real Objects, Simulator | Mid | 2023/10/11 | [pad2024](bibtex/pad2023.md) |
| **InVar-100** | 20800 | Mechanics ⚙️, Electronics 💻 | N/A | N/A | [Link](https://huggingface.co/datasets/ar-100) | Fraunhofer IPK | Real Objects | Mid | 2023/10/06 | [invar2023](bibtex/invar2023.md) |
| **VISION Datasets** | 18422 | Electronics 💻 | CC BY-NC-SA 4.0 | Image-level Anomaly | [Link](https://huggingface.co/datasets) | Apple | Roboflow | High | 2023/06/13 | [vision2023](bibtex/vision2023.md) |
| **AeBAD** | 5570 | Mechanics ⚙️ | CC-BY 4.0 | Pixel-level Anomaly, Image-level Anomaly | [link](https://github.com/zhangzilongc/MMR) | Jiaotong Univ. | Real Objects | High | 2023/04/05 | [aebad2023](bibtex/aebad2023.md) |
| **MIAD** | 15000 | Mechanics ⚙️, Electronics 💻, Infrastructure 🏗️ | CC BY-NC-SA 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](http://miad-2022.github.io/) | Shanghai Jiao Tong University | Simulator | Mid | 2022/11/28 | [miad2023](bibtex/miad2023.md) |
| **DIMO** | 585000 | Metal 🔩 | CC-BY 4.0 | Pixel-level Anomaly | [Link](https://pderoovere.github.io/dimo/) | Ghent Univ. | Real Objects / Simulator | Mid | 2022/08/08 | [dimo2022](bibtex/dimo2022.md) |
| **NEU Surface Defect Dataset** | 1800 | Metal 🔩 / Mechanics ⚙️ | N/A | Pixel-level Anomaly | [Link](http://faculty.neu.edu.cn/yunhyan/NEU_surface_defect_database.html) | Northeastern University | Real Objects | Low | 2022/08/06 | [neusdd2022](bibtex/neusdd2022.md) |
| **Veneer21** | 5158 | Wood 🪵, Textures 🎨 | CC-BY 4.0 | N/A | [Link](https://ieee-dataport.org/open-access/wood-surface-texture-database) | Tampere University | Real Objects | Mid | 2022/05/18 | [veneer2022](bibtex/veneer2022.md) |
| **LAION-5B** | 5000000000 | Natural Image 🏞️ | CC-BY 4.0 | Caption | [Link](https://laion.ai/blog/laion-5b/) | LAION | Common Crawl | High | 2022/03/31 | [laion5b2022](bibtex/laion5b2022.md) |
| **MVTec LOCO** | 3644 | Mechanics ⚙️, Food & Drinks 🍔 | CC BY-NC-SA 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](https://www.mvtec.com/company/research/datasets/mvtec-loco) | MVTec | Real Objects | High | 2022/02/22 | [mvtecloco2022](bibtex/mvtecloco2022.md) |
| **IBAD** | 1255 | Food & Drinks 🍔 | LGPL | Pixel-level Anomaly, Image-level Anomaly | [Link](https://www.kaggle.com/datasets/imonbilk/industry-biscuit-cookie-dataset/data) | N/A | Real Objects | Low | 2022/01/01 | [ibad2022](bibtex/ibad2022.md) |
| **Amazon Berkeley Objects** | 398212 | Natural Image 🏞️, Toy 🧸, Tools 🛠️, Office 🏢, Groceries 🛒 | CC-BY 4.0 | N/A | [Link](https://amazon-berkeley-objects.s3.amazonaws.com/index.html) | Amazon | Online Catalogs | High | 2022/01/01 | [abo2022](bibtex/abo2022.md) |
| **Eyecandies** | 90000 | Food & Drinks 🍔 | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://eyecan-ai.github.io/eyecandies/download) | Eyecan.ai | Simulator | Mid | 2022/01/01 | [eycandies2022](bibtex/eyecandies2022.md) |
| **MPDD** | 1000 | Metal 🔩, Mechanics ⚙️ | CC BY-NC-SA 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](https://vutbr-my.sharepoint.com/:f:/g/personal/xjezek16_vutbr_cz/EhHS_ufVigxDo3MC6Lweau0BVMuoCmhMZj6ddamiQ7-FnA?e=oHKCxI) | Brno University of Technology | Real Objects | High | 2021/12/13 | [mpdd2021](bibtex/mpdd2021.md) |
| **LAION-400M** | 400000000 | Natural Image 🏞️ | CC-BY 4.0 | Caption | [Link](https://laion.ai/blog/laion-400-open-dataset/) | LAION | Common Crawl | High | 2021/11/03 | [laion400m2021](bibtex/laion400m2021.md) |
| **WSD** | 4000 | Wood 🪵, Agriculture 🌾 | CC-BY 4.0 | N/A | [Link](https://www.kaggle.com/datasets/nomihsa965/large-scale-image-dataset-of-wood-surface-defects) | N/A | Real Objects | N/A | 2021/06/21 | [wsd2021](bibtex/wsd2021.md) |
| **WSD** | 4000 | Wood 🪵, Agriculture 🌾 | CC-BY 4.0 | N/A | [Link](https://www.kaggle.com/datasets/nomihsa965/large-scale-image-dataset-of-wood-surface-defects) | N/A | Real Objects | N/A | 2021/06/21 | [wsd2021](bibtex/wsd2021.md) |
| **SynPick** | 503232 | Mechanics ⚙️ / Products 📦 / Groceries 🛒 | N/A | N/A | [Link](http://cloud.vi.cs.uni-bonn.de/index.php/s/Ny3zP6) | University of Bonn | Simulator | Mid | 2021/06/10 | [synpick2021](bibtex/synpick2021.md) |
| **KolektorSDD2** | 3335 | Textures 🎨 | CC BY-NC-SA 4.0 | Image-level Anomaly, Pixel-level Anomaly | [Link](http://go.vicos.si/kolorsdd2) | Visual Cognitive Systems Laboratory | Real Objects | Mid | 2021/04/13 | [kolektorsdd2021](bibtex/kolektorsdd2021.md) |
| **BSData** | 1104 | Metal 🔩 / Mechanics ⚙️ | CC BY-NC-SA 4.0 | Pixel-level Anomaly, Image-level Anomaly | [Link](https://publikationen.bibliothek.kit.edu/1000129520) | WBK | Real Objects | Mid | 2021/03/24 | [bsdata2021](bibtex/bsdata2021.md) |
| **Electric Wires** | 28646 | Electronics 💻 | N/A | Segmentation | [Link](https://gts.ai/dataset-download/electric-wires-dataset/) | University of Bologna | Real Objects | Mid | 2021/01/01 | [ew2021](bibtex/ew2021.md) |
| **Objectron** | 4000000 | Natural Image 🏞️ | Computational Use of Data Agreement | N/A | [Link](https://github.com/google-research-datasets/Objectron/) | Google | Real Objects | Mid | 2021/01/01 | [objectron2021](bibtex/objectron2021.md) |
| **Escalator Steps** | 67 | Infrastructure 🏗️, Electronics 💻 | CC0 | Image-level Anomaly | [Link](https://aistudio.baidu.com/aistudio/datasetdetail/44820) | Baidu | Real Objects | Mid | 2020/07/18 | [esdd2020](bibtex/esdd2020.md) |
| **GC10-DET** | 3570 | Textures 🎨, Metal 🔩, Mechanics ⚙️ | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://www.kaggle.com/datasets/zhangyunsheng/defects-class-and-location) | The State Key Lab | Real Objects | High | 2020/03/11 | [gc2020](bibtex/gcdet2020.md) |
| **Products-10k** | 150000 | Natural Image 🏞️, Food & Drinks 🍔, Groceries 🛒, Electronics 💻, Products 📦 | N/A | N/A | [Link](https://products-10k.github.io/challenge.html) | JDAI | Online Catalogs | High | 2020/01/01 | [products10k2020](bibtex/producs10k2020.md) |
| **Textures** | 8674 | Textures 🎨 | N/A | N/A | [Link](https://github.com/abin24/Textures-Dataset) | N/A | Real Objects | Mid | 2020/01/01 | [td2019](bibtex/td2019.md) |
| **BCI** | 2068 | Infrastructure 🏗️ | N/A | N/A | [Link](https://github.com/Charmve/Surface-Defect-Detection/tree/master/Bridge_Crack_Image) | Hangzhou Dianzi Univ. | Real Objects | Mid | 2019/06/15 | [bci2019](bibtex/bci2019.md) |
| **Oil Storage Tanks** | 10000 | Infrastructure 🏗️ | N/A | N/A | [Link](https://www.kaggle.com/datasets/towardsentropy/oil-storage-tanks) | N/A | Real Objects | Mid | 2019/06/05 | [ost2019](bibtex/ost2019.md) |
| **Deep PCB** | 1500 | Electronics 💻 | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://github.com/Charmve/Surface-Defect-Detection/tree/master/DeepPCB) | Shanghai Jiao Tong University | Real Objects | Low | 2019/02/17 | [deeppcb2019](bibtex/deeppcb2019.md) |
| **TIG Welding** | 33300 | Metal 🔩 | CC BY-NC-SA 4.0 | N/A | [Link](https://www.kaggle.com/danielbacioiu/tig-aluminium-5083) | University of Birmingham | Real Objects | Mid | 2019/01/01 | [tigwelding2019](bibtex/tigwelding2019.md) |
| **Aluminium Profile Surface Defect Dataset (Tianchi)** | 8800 | Metal 🔩, Textures 🎨 | N/A | N/A | [Link](https://tianchi.aliyun.com/competition/entrance/231682/information) | N/A | Real Objects | Low | 2018/11/06 | [apsdd2018](bibtex/apsdd2018.md) |
| **Transmission Line Insulator Dataset** | 600 | Infrastructure 🏗️, UAV 🚁 | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://github.com/InsulatorData/InsulatorDataSet) | CAS | Real Objects | Mid | 2018/10/15 | [cplid2018](bibtex/cplid2018.md) |
| **MVTec D2S** | 21000 | Products 📦 | CC BY-NC-SA 4.0 | Segmentation | [Link](https://www.mvtec.com/company/research/datasets/mvtec-d2s) | MVTec | Real Objects | High | 2018/04/23 | [mvtecd2c](bibtex/mvtecd2s2018.md) |
| **MVTec ITODD** | 2800 | Mechanics ⚙️, Textures 🎨 | CC BY-NC-SA 4.0 | Bounding Box | [Link](https://www.mvtec.com/company/research/datasets/mvtec-itodd) | MVTec | Real Objects | High | 2018/01/22 | [mvteccitodd2017](bibtex/mvteccitodd2017.md) |
| **Magnetic Tile Defect** | 1344 | Textures 🎨 / Mechanics ⚙️ | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://github.com/abin24/Magnetic-tile-defect-datasets.) | CAS | Real Objects | High | 2018/01/01 | [mtd2018](bibtex/mtd2018.md) |
| **RoadCrack** | 40000 | Infrastructure 🏗️ | CC-BY 4.0 | Image-level Anomaly | [Link](https://data.mendeley.com/datasets/g2zt/1) | Temple Univ. | Real Objects | High | 2016/01/01 | [roadcrack2016](bibtex/roadcrack2016.md) |
| **CrackForest** | N/A | Infrastructure 🏗️ | N/A | Pixel-level Anomaly, Image-level Anomaly | [Link](https://github.com/jonathanwvd/awesome-industrial-datasets/blob/master/markdown/road_surface_cracks_dataset.md) | N/A | Real Objects | Low | 2015/09/29 | [crackforest2016](bibtex/crackforest2016.md) |
| **Food101** | 10100 | Food & Drinks 🍔 | N/A | N/A | [Link](https://huggingface.co/datasets/food101) | ETH Zurich | Real Objects | High | 2014/09/01 | [food1012014](bibtex/food1012014.md) |
| **Kylberg Texture Dataset** | 160 | Textures 🎨 | N/A | N/A | [Link](https://filedn.com/lkCRue0RhPO7ercIrqFRl2Y/datasets/KylbergTextureDatasetV1/) | N/A | Real Objects | Low | 2011/01/01 | [ktd2011](bibtex/ktd2011.md) |

### Column Descriptions
- **Dataset Name**: Official name of the dataset.
- **#Images**: Approximate number of images or samples, and number of categories if applicable.
- **Domain**: Primary industrial application area (e.g., Metal 🔩, Infrastructure 🏗️).
- **License**: Usage permissions (e.g., research-only, commercial use allowed).
- **Annotation**: Types of labels provided (e.g., pixel-level, bounding boxes).
- **Dataset Link**: Direct download or access URL.
- **Provider**: Organization or authors responsible for releasing the dataset.
- **Source**: Whether the data is captured from real-world objects or generated via simulation.
- **Quality**: Subjective assessment based on diversity, balance, and realism (High / Mid / Low).
- **Proposed Year**: Year of initial release or publication.
- **Citation (BibTeX)**: Ready-to-use BibTeX reference for citation.

<!-- ## Utilities
This section can include tools or scripts for dataset handling (e.g., download scripts, preprocessing code). Currently placeholders:
- `download_datasets.py`: A Python script to batch-download datasets from links.
- `visualize_anomalies.ipynb`: Jupyter notebook for quick visualization of samples.

## Other Dataset Reviews
Here are links to related surveys and reviews for deeper insights (placeholders):
- [A Survey on Industrial Anomaly Detection Datasets](https://example.com/survey1) - Comprehensive review from IEEE (2023).
- [Benchmarking Visual Anomaly Detection](https://example.com/benchmark) - Paper comparing 20+ datasets (2024).
- [Awesome Anomaly Detection](https://github.com/yzhao062/anomaly-detection-resources) - Broader repo on anomaly detection resources. -->

## Contributing
Feel free to submit pull requests to add real datasets, update placeholders, or improve the table. Follow the template above for new entries.

## License
This repository is licensed under MIT. Individual datasets follow their own licenses.
