# MILPaC: A Novel Benchmark for Evaluating Translation of Legal Text to Indian Languages

Paper accepted for publication in the **Transactions on Asian and Low-Resource Language Information Processing (ACM TALLIP)!**

## The MILPaC Dataset 
<b> MILPaC </b> (**M**ultilingual **I**ndian **L**egal **Pa**rallel **C**orpus) is the first parallel corpus of legal text in Indian languages, consisting of 3 high-quality datasets (**MILPaC-IP**, **MILPaC-CCI-FAQ**, and **MILPaC-Acts**) compiled from reliable sources of legal information in India. It includes parallel text units in English and 9 Indian languages, covering Indo-Aryan (Hindi, Bengali, Marathi, Punjabi, Gujarati, & Oriya) and Dravidian (Tamil, Telugu, & Malayalam) languages, many of which are low-resource. **MILPaC** serves as a robust resource for evaluating Machine Translation (MT) systems in translating legal text between English and Indian languages or between Indian languages. Additionally, **MILPaC-IP** and **MILPaC-CCI-FAQ** datasets can be applied to other NLP tasks, such as cross-lingual question answering, further enhancing their utility.

### Folder Structure

This repository is organized as follows:
```
MILPaC/
├── README.md                       # Repository README file
├── LICENSE                         # Repository License file
└── Data/
    └── MILPaC/
        ├── MILPaC-IP.xlsx          # Intellectual property dataset
        ├── MILPaC-CCI-FAQ.xlsx     # The Competition Act FAQ dataset
        └── MILPaC-Acts.xlsx        # Legislative and legal acts dataset
```

#### Usage

Each dataset file can be loaded using Python libraries like `pandas` for data manipulation or `openpyxl` for working with Excel files directly.

## License
This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Citation
If you use this dataset, please cite the following paper:
```
```


## Contact
For any inquiries, feedback, or collaboration opportunities, please contact to {debtanudatta04 [at] gmail [dot] com}. Collaborations are welcome, and feedback on the dataset is appreciated to further refine and enhance its utility for research in the Indian Legal domain.
