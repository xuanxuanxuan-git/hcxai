[![License](https://img.shields.io/github/license/xuanxuanxuan-git/facelift)](https://github.com/xuanxuanxuan-git/facelift/blob/main/LICENSE)
[![arXiv](https://img.shields.io/badge/arXiv-2309.08438-red.svg)](https://arxiv.org/abs/2309.08438)

# Comprehension Is a Double-Edged Sword: <br>Over-Interpreting Unspecified Information in Intelligible Machine Learning Explanations


This repository hosts source code and data for the XAI user study paper ([Paper Link](https://www.sciencedirect.com/science/article/pii/S1071581924001599)).

```bibtex
@article{xuan2024comprehension,
  title={Comprehension is a double-edged sword: Over-interpreting unspecified information in intelligible machine learning explanations},
  author={Xuan, Yueqing and Small, Edward and Sokol, Kacper and Hettiachchi, Danula and Sanderson, Mark},
  journal={International Journal of Human-Computer Studies},
  pages={103376},
  year={2024},
  publisher={Elsevier}
}
```


## Supplementary material of the user study

### For generating ML explanations in the survey
- This [file](explainers.ipynb) contains code for generating ML explanations used in the actual survey.
- This [dataset](diabetes_dataset.csv) is the diabetes dataset where the use case scenario and ML explanations are based upon.

### Actual Survey
- This [pdf](Actual_survey_to_participants.pdf) contains the screenshots of one version (decision tree) of the survey received by participants. The other version uses the same template with contents adjusted for explanations of logistic regression. 

### Survey results and analysis
- This [notebook](survey_analysis.ipynb) contains code for running statistical analysis on the 200 survey responses we collect.
- This [file](/XAI_user_study_one_scenario_only_response/XAI_user_study_one_scenario_only_August%2028,%202023_12.17.csv) contains the survey responses we collected from 200 participants.

### Code Environment
- To install the packages for running python code, execute

    <code>pip install -r requirements.txt</code>