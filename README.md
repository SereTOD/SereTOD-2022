This is the code repository for [SereTOD Challenge](http://seretod.org/Challenge.html), co-located with [EMNLP2022 SereTOD Workshop](http://seretod.org)!

# Introduction
Task-oriented dialogue (TOD) systems are designed to assist users to accomplish their goals, and have gained more and more attention recently in both academia and
industry with the current advances in neural approaches. A TOD system typically consists of several modules, which track user goals to update dialog states, query a
task-related knowledge base (KB) using the dialog states, decide actions and generate responses. 

The purpose of this challenge is to invite researchers from both academia and industry to share their perspectives on building **se**mi-supervised and **re**inforced **TOD** systems and to advance the field in joint effort.
Hence, we refer to this challenge as the sereTOD challenge.
A shared task is organized for benchmarking and stimulating relevant researches. For the first sereTOD challenge, a large-scale TOD dataset is newly released, consisting of 100,000 real-world dialogs, where only 10,000 dialogs are annotated.

The task consists of two tracks:

* Information extraction from dialog transcripts (Track 1)   
* Semi-supervised task oriented dialog systems (Track 2)

**Organizers:** Zhijian Ou, Junlan Feng, Juanzi Li, Yakun Li, Hong Liu, Hao Peng, Yi Huang, Jiangjiang Zhao

# Important Dates (AOE)
| Date  | Item  |
| ---: | :--- |
| July 1, 2022 | Registration deadline for challenge |
| July 1, 2022 | Training data release |
| July 15, 2022 | ACL Rolling Review paper due (submit via [ARR](https://aclrollingreview.org/)) |
| August 14, 2022 | Evaluation data release |
| August 31, 2022 | Entry submission deadline (extended) |
| September 10, 2022 | Evaluation results announced (extended) |
| September 17, 2022 | Regular paper due (via [softconf](https://softconf.com/emnlp2022/seretod/)) (extended) |
| October 2, 2022 | ARR commitment due (via [OpenReview](https://openreview.net/group?id=EMNLP/2022/Workshop/SereTOD_Commitments)) |
| October 7, 2022 | Submission of EMNLP manuscripts with reviews (via [softconf](https://softconf.com/emnlp2022/seretod/)) |
| October 10, 2022 | Notification of paper acceptance |
| October 16, 2022 | Camera-ready papers due |
| December 7, 2022 | EMNLP 2022 Workshop Date |

# Important Links
* [SereTOD Challenge Website](http://seretod.org/Challenge.html)  
* [Challenge Description](http://seretod.org/SereTOD_Challenge_Description_v2.0.pdf)    
* [Track 1 Details](Track1/) (including baseline and evaluation code)
* [Track 2 Details](Track2/) (including baseline and evaluation code) 

If you publish experimental results with the MobileCS dataset, please cite [this challenge description paper](http://arxiv.org/abs/2207.02657):
```
@article{ou2022achallenge,
      title={A Challenge on Semi-Supervised and Reinforced Task-Oriented Dialog Systems}, 
      author={Zhijian Ou and Junlan Feng and Juanzi Li and Yakun Li and Hong Liu and Hao Peng and Yi Huang and Jiangjiang Zhao},
  journal={arXiv preprint arXiv:2207.02657},
  year={2022}
}
```
 For your reference to the baseline models, please cite [this baseline study paper](https://arxiv.org/abs/2209.13464):
```
@article{Liu2022InformationEA,
  title={Information Extraction and Human-Robot Dialogue towards Real-life Tasks: A Baseline Study with the MobileCS Dataset},
  author={Hong Liu and Hao Peng and Zhijian Ou and Juan-Zi Li and Yi Huang and Junlan Feng},
  journal={arXiv preprint arXiv:2209.13464},
  year={2022}
}
```
# Rules
* The challenge website is http://seretod.org/Challenge.html . Teams should submit the registration form to seretod2022 (at) gmail (dot) com, which will be reviewed by the organizers. 
* Teams are required to sign an Agreement for Challenge Participation and Data Usage. Data will be provided to approved teams.
* For teams that participate in Track 1, the scores will be ranked according to the performance for Track 1. The teams can choose to participate only in Track 1.
* For teams that participate in Track 2, they can use the baseline system provided by the organizers or use the system developed by themselves for Track 1. The ranking is based on the performance for Track 2.
* Participants are allowed to use any external datasets, resources or pre-trained models which are publicly available.
* Participants are NOT allowed to do any manual examination or modification of the test data.
    - Cross exploitation of the released test sets between Track1 and Track2 are not allowed. That is, the released test set for Track 1 should be used solely for the testing of Track 1, and the same for Track 2.
* In publishing the results, all teams will be identified as team IDs (e.g. team1, team2, etc). The organizers will verbally indicate the identities of all teams at the Workshop for communicating results.
* For each track, three teams with top performances will be recognized with prizes. The prizes will be awarded at the Workshop.
* Participants may identify their own team label (e.g. team5) and report their own result, in publications or presentations, if they desire.


# Submission Guidelines
* Each team needs to submit a package via email to seretod2022 (at) gmail (dot) com before the Entry Submission Deadline. The submission package should contain the system executable with the model. All dependencies must be contained in the submission package.
    - For track 2, system running is not only for corpus-based automatic evaluation, but also for human evaluation.That is, the submission system for Track 2 should provide an interface, through which real users interact with those systems.
* The submission should provide **clear documentation** for running the system. Direct running the executable without any arguments should output the result file with the required format. See [Track1 README](Track1/README.md#SubmissionFormat) and [Track2 README](Track2/README.md#SubmissionFormat) for the formats.
* The submitted system could be, but not limited to be, encapsulated in a Docker image, as long as the above requirements are satisfied.
* The submission should provide a **System Description Paper**. Teams are also encouraged to submit papers to EMNLP2022 SereTOD Workshop. See important dates and instructions in [Call for Papers](http://seretod.org/Call%20for%20Papers.html).
* Before the Entry Submission Deadline, each team can submit for multiple times for each track. The last entry from each team will be used for the evaluation.

# Contact
For any questions, please feel free to contact: seretod2022 (at) gmail (dot) com

You are welcome to scan the following QR code to join the WeChat group (in Chinese), where we will distribute messages relevant to the Challenge.
<p align="center">
<img src="figs/ewm.png" alt="WeChat QR code" width="200" align="center"/>
</p>
