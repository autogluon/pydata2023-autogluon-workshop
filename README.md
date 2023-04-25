# AutoGluon: Leveraging Text, Images, and the Kitchen Sink to solve complex ML problems in a few lines of code with AutoGluon

Automated machine learning (AutoML) offers the promise of translating raw data into accurate predictions without the
need for
significant human effort, expertise, and manual experimentation. In this workshop, we
introduce [AutoGluon](https://github.com/autogluon/autogluon),
a state-of-the-art and easy-to-use toolkit that empowers *multimodal* AutoML. Different from most AutoML systems that
focus on solving tabular tasks
containing categorical and numerical features, we consider supervised learning tasks on various types of data including
tabular
features, text, image, time series, as well as their combinations. We will introduce the real-world problems that
AutoGluon can help you
solve within three lines of code and the fundamental techniques adopted in the toolkit.
Rather than diving deep into the mechanisms underlining each individual ML models,
we emphasize on how you can take advantage of a diverse collection of models to build an automated ML pipeline.
Our workshop will also emphasize on the techniques behind automatically building and training deep learning models,
which are powerful yet cumbersome to manage manually.

Join us at the [PyData Seattle 2023](https://seattle2023.pydata.org) located at Microsoft Conference Center on
Wednesday, April 26th at 9:00-10:30am, PDT in
St. Helens.

*Note: Github repository for this website is available at https://github.com/autogluon/pydata2023-autogluon-workshop* .

## Schedule

For each section, there will be a 10-15min QA at the end of section. In addition, there will
be [additional hands-on notebooks](#hands-on-notebooks) after
each session that people can try out asynchronously.

| Topic                                                  | Speaker                                             | Duration (PDT timezone) | Slides                                                                                                                                          | Cheatsheet                                                                                                                                                                                                                                                                                                                              |
|--------------------------------------------------------|-----------------------------------------------------|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Introduction + AutoGluon Tabular](#autogluon-tabular) | [Nick Erickson](https://github.com/Innixma)         | 9:00AM -- 9:40AM        | [link](https://docs.google.com/presentation/d/1whJdw8W0IixwFyRna13AjqlFKwO9ufsR/edit?usp=sharing&ouid=117434028345007023633&rtpof=true&sd=true) | [![tabular-cheatsheet](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/autogluon-cheat-sheet.jpeg)](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/autogluon-cheat-sheet.jpeg) [docs](https://auto.gluon.ai/stable/tutorials/tabular/index.html) |
| [AutoGluon Multimodal](#autogluon-multimodal)          | [Nick Erickson](https://github.com/Innixma)         | 9:40AM -- 9:55AM        | [link](https://docs.google.com/presentation/d/1SlHVzaWtN-75m6mmvapeu4-C2Id7V5wO/edit?usp=sharing&ouid=117434028345007023633&rtpof=true&sd=true) | [![multimodal-cheatsheet](https://automl-mm-bench.s3-accelerate.amazonaws.com/cheatsheet/v0.7.0/AutoGluon_Multimodal_Cheatsheet_v0.7.0.png)](https://automl-mm-bench.s3-accelerate.amazonaws.com/cheatsheet/v0.7.0/AutoGluon_Multimodal_Cheatsheet_v0.7.0.png) [docs](https://auto.gluon.ai/stable/tutorials/multimodal/index.html)     |
| [AutoGluon EDA](#advanced-topics)                      | [Alexander Shirkov](https://github.com/gradientsky) | 9:55AM -- 10:15AM       | [link](https://docs.google.com/presentation/d/1AwZFuUWFT_Dp2wFLh9dk_RYLaYlsbxpN/edit?usp=sharing&ouid=117434028345007023633&rtpof=true&sd=true) | [docs](https://auto.gluon.ai/dev/tutorials/eda/index.html)                                                                                                                                                                                                                                                                              |
| Additional QA + Feedback                               | All speakers                                        | 10:15AM -- 10:30AM      | -                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                         |

## Section Outline and Materials

### AutoGluon Tabular

- AutoML Basics: Discussion of core AutoML principles and historical background (including early AutoML toolkits such as
  AutoWeka and auto-sklearn)
- History of competition ML and how it influenced the design of modern AutoML systems
- Discussion of model combination strategies (stacking, bagging, model aggregation)
- Constraint satisfaction and engineering for a performance envelope (accuracy, speed, compute resources)
- Benchmark comparisons showcasing the advancement of AutoML systems in recent years both compared to earlier AutoML
  systems and human data scientists (4 AutoML frameworks, 104 OpenML datasets, 10 Kaggle datasets)

### AutoGluon Multimodal

- Foundational models for image and text
- Real-world multimodal problems
- Fusion techniques and multimodal distillation

### Advanced Topics

- Exploratory data analysis

### Hands-on Notebooks

For hands-on tutorials, we provide notebooks for you to try out AutoGluon
via [SageMaker Studio Lab](https://aws.amazon.com/sagemaker/studio-lab/)
or [Google Colab](https://colab.research.google.com/).

All notebooks can be found in [notebooks](./notebooks).

**Checkout [AutoGluon Website](https://auto.gluon.ai/) and get started!**
