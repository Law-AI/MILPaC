# MILPaC: A Novel Benchmark for Evaluating Translation of Legal Text to Indian Languages

Paper accepted for publication in the **Transactions on Asian and Low-Resource Language Information Processing (ACM TALLIP)!**

## The MILPaC Dataset 
<b> MILPaC </b> (**M**ultilingual **I**ndian **L**egal **Pa**rallel **C**orpus) is the first parallel corpus of legal text in Indian languages, consisting of 3 high-quality datasets (**MILPaC-IP**, **MILPaC-CCI-FAQ**, and **MILPaC-Acts**) compiled from reliable sources of legal information in India. It includes parallel text units in English and 9 Indian languages, covering Indo-Aryan (Hindi, Bengali, Marathi, Punjabi, Gujarati, and Oriya) and Dravidian (Tamil, Telugu, and Malayalam) languages, many of which are low-resource. **MILPaC** serves as a robust resource for evaluating Machine Translation (MT) systems in translating legal text between English and Indian languages or between Indian languages. Additionally, **MILPaC-IP** and **MILPaC-CCI-FAQ** datasets can be applied to other NLP tasks, such as cross-lingual question answering, further enhancing their utility. For more details regarding this dataset, please refer to our paper.

### Dataset Structure

All three datasets are stored under the `Data/MILPaC` folder and are provided in `.xlsx` format. Each dataset file includes the following attributes:

| Attribute      | Description                                         |
|----------------|-----------------------------------------------------|
| **id**         | Unique identifier for each text unit                |
| **src_lang**    | Source language code (e.g., "EN" for English)      |
| **src**         | Source text in the source language                 |
| **tgt_lang**    | Target language code (e.g., "HI" for Hindi)        |
| **tgt**         | Translated text in the target language             |

Each `.xlsx` file corresponds to one of the datasets (**MILPaC-IP**, **MILPaC-CCI-FAQ**, **MILPaC-Acts**) and follows the same schema as described above.

### Folder Structure

This repository is organized as follows:
```
MILPaC/
├── README.md                              # Repository README file
├── LICENSE                                # Repository License file
└── Data/
    └── MILPaC/
        ├── MILPaC_IP_dataset.xlsx         # Intellectual property dataset
        ├── MILPaC_CCI_FAQ_dataset.xlsx    # The Competition Act FAQ dataset
        └── MILPaC_Acts_dataset.xlsx       # Legislative and legal acts dataset
```

#### Usage

Each dataset file can be loaded using Python libraries like `pandas` for data manipulation or `openpyxl` for working with Excel files directly.

## License
The MILPaC dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Citation
If you use this dataset, please cite the following paper:
```
@misc{mahapatra2023improvingaccessjusticeindian,
      title={Improving Access to Justice for the Indian Population: A Benchmark for Evaluating Translation of Legal Text to Indian Languages}, 
      author={Sayan Mahapatra and Debtanu Datta and Shubham Soni and Adrijit Goswami and Saptarshi Ghosh},
      year={2023},
      eprint={2310.09765},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2310.09765}, 
}
```


## Contact
For any inquiries, feedback, or collaboration opportunities, please contact to {debtanudatta04 [at] gmail [dot] com}. Collaborations are welcome, and feedback on the dataset is appreciated to further refine and enhance its utility for research in the Indian Legal domain.
