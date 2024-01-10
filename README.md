## Shared Task on Code-mixed Less-resourced Sentiment Analysis for Indo-Aryan Languages

The [Code-mixed Less-Resourced Sentiment analysis (Code-mixed) for Indo-Aryan languages Shared Task](https://github.com/wildre-workshop/wildre-7_code-mixed-sentiment-analysis/) is a part of the [7th Workshop on Indian Language Data: Resources and Evaluation (WILDRE-7)].

## Introduction: 
<p align="justify"> Code-mixing, the dynamic interplay of multiple languages within a single discourse, is a widespread linguistic phenomenon observed in multilingual societies. Code-mixing is particularly intriguing when observed in closely related languages. In such linguistic scenarios, where language boundaries are blurred, code-mixing becomes a dynamic expression of linguistic fluidity. Closely related languages share lexical and syntactic similarities, allowing for seamless transitions between them in communication. This phenomenon reflects the intertwined linguistic histories and presents a rich tapestry of expression. The nuances of code-mixing in closely related languages highlight the intricate ways in which linguistic diversity is woven into everyday discourse, showcasing the versatility and adaptability of language in diverse linguistic landscapes. The pervasive use of the Internet and social media platforms has led to the digital availability of most languages. This digital accessibility has paved the way for a myriad of artificial intelligence (AI) applications. Among these applications, sentiment analysis, machine translation, and hateful content detection stand out. Despite the increasing digital availability of languages due to the Internet and social media, the need for curated datasets for developing AI applications in many languages remains a significant challenge. Notably, numerous Indo-Aryan languages have been underrepresented in terms of linguistic resources. In recent years, demand has increased to create code-mixed and under-resourced Indo-Aryan languages. However, the effectiveness of existing natural language processing (NLP) techniques in utilizing these datasets and the need for novel techniques present key research areas. Understanding the applicability of current NLP methods and innovating new approaches will be crucial in maximizing the potential impact of these datasets across a spectrum of AI applications. 

Sentiment analysis stands as a classic challenge in computational linguistics, demonstrating a profound impact on various real-world applications.  While sentiment analysis as a field has been expanding, and numerous shared tasks have been organised from time to time, some of them are (Patra et al., 2016) ( Patwa et al., 2020), (Chakravarthi et al., 2021), (Debasis et al., 2022),  (Chakravarthi et al., 2022), (Premjith et al., 2023) (Hedge et al., 2023) and so on. However, none of these shared tasks focused on code-mixed closely related low-resource Indo-Aryan languages. Systems have made remarkable progress in setting new performance standards, but the effectiveness of sentiment prediction in the context of code-mixed data still needs to be improved. This limitation is primarily attributed to the variability in language availability and the quality of training data, which directly impacts the precision of sentiment analysis.

## Task Description
This shared task addresses the complexities of code-mixed data from less-resourced similar languages and focuses on sentiment analysis. The task builds on code-mixed sentiment analysis but introduces language pairs and triplets of less-resourced closely related languages, Magahi-Hindi-English, Maithili-Hindi, Bangla-English, and Hindi-English. These four languages come from the Indo-Aryan language family and are spoken in eastern India. Keeping a record of the challenges of processing closely related languages in code-mixed and low-resourced settings. We challenge the participants to explore using different Machine learning and Deep learning approaches to train the model on the given training and validation dataset while testing on a surprise language. In this context, we will provide Hindi-English, Bangla-English and Magahi-Hindi-English datasets for training and validation. This task will allow the participants to use any approach to train their model but robust enough to perform on a closely related language dataset. This would also allow us to understand the language representation in various code-mixed settings and the speakers' preference of language to express their emotions in each language pair.

## Data



## Evaluation 
The shared task is hosted on CodaLab. The standard evaluation metrics for evaluating sytems will be as follows. We will use F1 averaged across the positives, negatives, neutral and mixed. The final ranking would be the average F1 score. However, we will release Precision and Recall across the four classes for a detailed discussion and error analysis. Each participating team will initially have access to the training and Validation data only. Later, test data will be released along with the surprised language. 

The evaluation will be in two different Tracks:

**A. Track 1:** Given training and validation data in a target language pairs, determine the polarity of the comment in the given code-mixed pairs (positive, negative , neutra or mixed).
  1. Hindi-English
  2. Magahi-Hindi-English
  3. Bangla-English
  4. Combined all the language pairs (1+2+3)

**B. Track 2:** Given unlabelled test data for the code-mixed Maithili-Hindi-English language pair leverage any or all of the available training datasets in Track 1 to determine the sentiment of a comment in the target language. 

## Submission Format
We will ask the participants to submit their predictions in a specified format. 


## Paper submission 
Participants will be invited to describe their system in a paper for the WILDRE workshop proceedings. The task organisers will write an overview paper that describes the task and summarises the different approaches taken, and analyses their results. 

Paper submission instructions will be the same as for the workshop. Each team participating in the shared task is expected to submit a paper of 4 to 8 pages, plus additional pages for references, formatted according to the workshop guidelines. The paper should describe the system and the resources used along with the libraries used to develop the system. The methodology/strategy should be documented in such a way that the readers and other researchers are able to replicate the work from the system description in the paper. 

# Shard Task Dates
```
Dec 22, 2023: Registration- https://forms.gle/HVRK1W1hHqBwtgpu6
Jan 10, 2024: Train and Validation Data set Release [to get the data please register]
Feb 15, 2024: Test Set Release
Feb 23, 2024: System Submission Due
Feb 29, 2024: System Results
March 15, 2024: System Description Paper Due
March 28, 2024: Paper notification of acceptance
```

## Important Links
[**Registration**](https://forms.gle/HVRK1W1hHqBwtgpu6)
[**Worshop Page**](http://sanskrit.jnu.ac.in/conf/wildre7/index.jsp)

## Task Organizers 

* **Priya Rani**, SFI Centre for Research and Training in AI, Data Science Institute, University of Galway 
* **Gaurav Negi**, Insight SFI Research Centre for Data Analytics, Data Science Institute, University of Galway 
* **Shardul Suryawanshi**, Insight SFI Research Centre for Data Analytics, Data Science Institute, University of Galway 
* **Saroj Jha**, Indian Institute of Technology, Patna, India
* **John P. McCrae**, Insight SFI Research Centre for Data Analytics, Data Science Institute, University of Galway
* **Paul Buitelaar**, Insight SFI Research Centre for Data Analytics, Data Science Institute, University of Galway


## References 

Patra, Braja Gopal, Dipankar Das, Amitava Das and R. Rajendra Prasath. 2015. Shared Task on Sentiment Analysis in Indian Languages (SAIL) Tweets - An Overview. In: Prasath, R., Vuppala, A., Kathirvalavakumar, T. (eds) Mining Intelligence and Knowledge Exploration. MIKE 2015. Lecture Notes in Computer Science(), vol 9468. Springer, Cham. https://doi.org/10.1007/978-3-319-26832-3_61

Parth Patwa, Gustavo Aguilar, Sudipta Kar, Suraj Pandey, Srinivas PYKL, Björn Gambäck, Tanmoy Chakraborty, Thamar Solorio, and Amitava Das. 2020. SemEval-2020 Task 9: Overview of Sentiment Analysis of Code-Mixed Tweets. In Proceedings of the Fourteenth Workshop on Semantic Evaluation, pages 774–790, Barcelona (online). International Committee for Computational Linguistics.

Bharathi Raja Chakravarthi, Ruba Priyadharshini, Sajeetha Thavareesan, Dhivya Chinnappa, Durairaj Thenmozhi, Elizabeth Sherly, John P. McCrae, Adeep Hande, Rahul Ponnusamy, Shubhanker Banerjee, Charangan Vasantharajan. 2021. Findings of the Sentiment Analysis on Dravidian Languages in Code-Mixed Text. In Proceedings of the 13th Forum for Information Retrieval Evaluation, Gandhinagar, India.

Subalalitha Chinnaudayar Navaneethakrishnan, Bharathi Raja Chakravarthi, Kogilavani Shanmugavadivel, Malliga Subramanian, Prasanna Kumar Kumaresan, Bharathi, Lavanya Sambath Kumar, and Rahul Ponnusamy. 2023. Findings of shared task on Sentiment Analysis and Homophobia Detection of YouTube Comments in Code-Mixed Dravidian Languages. In Proceedings of the 14th Annual Meeting of the Forum for Information Retrieval Evaluation (FIRE '22). Association for Computing Machinery, New York, NY, USA, 18–21. https://doi.org/10.1145/3574318.3574347


Bharathi Raja Chakravarthi, Ruba Priyadharshini, Subalalitha Cn, Sangeetha S, Malliga Subramanian, Kogilavani Shanmugavadivel, Parameswari Krishnamurthy, Adeep Hande, Siddhanth U Hegde, Roshan Nayak, and Swetha Valli. 2022. Findings of the Shared Task on Multi-task Learning in Dravidian Languages. In Proceedings of the Second Workshop on Speech and Language Technologies for Dravidian Languages, pages 286–291, Dublin, Ireland. Association for Computational Linguistics.

Premjith B, Jyothish Lal G, Sowmya V, Bharathi Raja Chakravarthi, Rajeswari Natarajan, Nandhini K, Abirami Murugappan, Bharathi B, Kaushik M, Prasanth Sn, Aswin Raj R, and Vijai Simmon S. 2023. Findings of the Shared Task on Multimodal Abusive Language Detection and Sentiment Analysis in Tamil and Malayalam. In Proceedings of the Third Workshop on Speech and Language Technologies for Dravidian Languages, pages 72–79, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Asha Hegde, Bharathi Raja Chakravarthi, Hosahalli Lakshmaiah Shashirekha, Rahul Ponnusamy, Subalalitha Cn, Lavanya S K, Thenmozhi D., Martha Karunakar, Shreya Shreeram, and Sarah Aymen. 2023. Findings of the Shared Task on Sentiment Analysis in Tamil and Tulu Code-Mixed Text. In Proceedings of the Third Workshop on Speech and Language Technologies for Dravidian Languages, pages 64–71, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.


# License
Please see the [LICENSE](https://github.com/wildre-workshop/wildre-7_code-mixed-sentiment-analysis/blob/main/LICENSE) file.

# Acknowledgments

