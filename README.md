# Multilingual Text Detoxification Datasets (MTDD) 
## Introduction
<p align="justify">
This work focuses on text detoxification, i.e., automatically converting toxic text into non-toxic text. This task contributes to safer and more respectful online communication and can be considered a Text Style Transfer (TST) task, where the text style changes while its content is preserved. We present three approaches: knowledge transfer from a similar task, multi-task learning approach, combining sequence-to-sequence modeling with various toxicity classification tasks, and, delete and reconstruct approach. To support our research, we utilize a dataset provided by Dementieva et al.(2021), which contains multiple versions of detoxified texts corresponding to toxic texts. In our experiments, we selected the best variants through expert human annotators, creating a dataset where each toxic sentence is paired with a single, appropriate detoxified version. Additionally, we introduced a small <a href="https://github.com/panlingua/multilingual_text_detoxification_datasets"> Hindi parallel dataset</a>, aligning with a part of the English dataset, suitable for evaluation purposes. Our results demonstrate that our approach effectively balances text detoxication while preserving the actual content and maintaining fluency. For further read, please refer <a href="https://arxiv.org/abs/2402.07767"> our paper</a>.</p>

# Structure of the MTST datasets:
```
📂 multilingual_text_detoxification_datasets/
    📂  hindi/
        ├── hi_parallel_detoxification.test.csv
        └── ..
    📂  refined-english/
        ├── en_parallel_detoxification.test.csv
        └── ..
    ├── LICENSE.md
    ├── README.md
```

# License
Please read the [License](https://github.com/panlingua/multilingual_text_detoxification_datasets/blob/main/LICENSE) file.

# Acknowldegments
<p align="justify">
This research was supported by the <a href="https://erc.europa.eu/homepage">European Union</a> (ERC, NG-NLG, 101039303) and by <a href="https://cuni.cz/">Charles University </a> projects GAUK 392221 and SVV 260575. We acknowledge of the use of resources provided by the <a href="https://ufal.mff.cuni.cz/">LINDAT/CLARIAH-CZ Research Infrastructure</a> (Czech Ministry of Education, Youth, and Sports project No. LM2018101). We would also like to acknowledge <a href="panlingua.co.in"> Panlingua Language Processing LLP </a> for this collaborative research project and for providing the dataset.

Atul Kr. Ojha and John P. McCrae would like to acknowledge the support of the <a href="https://www.sfi.ie/"> Science Foundation Ireland (SFI)</a> as part of Grant Number SFI/12/RC/2289_P2 Insight_2, <a href="https://www.insight-centre.org/">Insight SFI Research Centre for Data Analytics</a>. </p>
# References
If you use this data, please cite:
```
@article{mukherjee2024text,
      title={Text Detoxification as Style Transfer in English and Hindi}, 
      author={Sourabrata Mukherjee and Akanksha Bansal and Atul Kr. Ojha and John P. McCrae and Ondřej Dušek},
      journal={arXiv preprint arXiv:2402.07767},
      eprint={2402.07767},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2402.07767},
      year={2024}
}
```
</pre>

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) =====================================================
Data available since: Multilingual Text Detoxification Datasets (MTDD)@2023
License: See the <i>LICENSE.md</i>
=======
Includes text: Yes
Contact:info@panlingua.co.in or atulkumar.ojha@insight-centre.org/shashwatup9k@gmail.com 
Contributor/&copy; holder: Panlingua Language Processing LLP, India; Institute of Formal and Applied Linguistics, Faculty of Mathematics and Physics Charles University, Czech Republic; and Insight Centre for Data Analytics, Data Science Institue, University of Galway, Ireland
=======================================================================================================
</pre>

