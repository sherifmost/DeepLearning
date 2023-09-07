# Project Proposal

Perhaps the most important delivery since all your project work depends on it. You are required to submit a **quality-document** containing the following requirements.

## Proposal Document Requirements

1. The proposed problem statement and its motivation. Use **figures and plots** to explain your problem statement.
2. Input/Output examples that explain the problem statement, also use **figures and plots** to illustrate those examples.
3. A survey of available evaluation metrics/tools for this problem. Metrics could be accuracy, area under the curve, etc., depending on your problem type.
4. Current state-of-the-art results (**results of correct evaluation metrics**, for example, accuracy in some class classification problems) for the proposed problem. The state of the art refers to the **current best results** in the literature addressing the specific problem you selected.
5. A survey of available datasets for your course project problem. If your proposed problem is a reinforcement learning problem, then provide a survey of available environments that your model can work on. This survey should include examples of the dataset (In **figures** if possible, I want to see an input and an output), **a website link for the dataset** (make sure that the dataset is accessible and downloadable easily from this link, otherwise you may get stuck later when you decide to use it), the dataset storage size (in **MBs or GBs**), the dataset examples size (number of samples in training/validation/testing splits) if splits sizes are defined, and any other important information. This survey should mention the available datasets for this problem in general not just the dataset you selected.
6. A detailed description of the dataset (or environment for reinforcement learning) that you selected to be used. Also, mention **why will you use this particular dataset**.
7. The selected dataset shouldn't exceed 20 GB (12GB maximum is recommended), if otherwise, please **explain why you find using this dataset feasible**.
8. A survey of available models and solutions for the proposed problem. This survey should include details, figures, and plots to explain each model (especially its architecture and main idea proposed to solve the problem), a reference paper for each model, a public repository code link, information about frameworks used in the code, information about available weights/model zoo, information about training resources required for them **if available**, results of each model and comparison between them in a **table**, and any other important information.
9. A detailed description of the model to be used from literature to build on (the baseline model). Also, mention **why you will use this particular model**.
10. The source code URL for the selected baseline model. It should be written in a recent framework, such as Tensorflow 2.x or TF.Keras or PyTorch and in a few files (20 code files or less). If there's no available source code, or the source code doesn't use the mentioned frameworks, **please justify how will you approach your project without them**.
11. The model weights or model zoo URL. If there are no model weights, **please justify how will you approach your project without them**. Note that the model weights refer to the files storing the final/checkpoint weights of the model obtained after training, they help serve as a starting point to avoid long training times when training from scratch.
12. The proposed updates to the literature model. Also, mention **what benefit do you expect from this update and why you think it is a good idea to try it**, its okay if it is just a gut feeling based on your readings, but you need to justify why you want to make such an update.
13. Write in detail about how you will evaluate your results, what kind of **evaluation metric** you will use to compare your results, and what types of **plots/graphs** will be used to point out the comparison results (tell us what figures/plots we should expect. Examples include: histograms, line graphs, confusion matrices, etc. depending on your problem).
14. **Your graduation project (or thesis) brief problem statement (if you are working on it this semester), even if it is not the same as the proposed course problem statement.**
15. **If your proposal is related to your graduation project (or thesis), point out the differences that will be made between this problem statement and your graduation project (thesis) problem statement (regarding either the problem itself or the proposed updates/solutions)**
16. List all other machine learning, deep learning, computer vision, natural language processing, pattern recognition, or any related data science field project you have participated in, **especially if you think they're close to your problem statement**. 
17. Mention all available online resources/papers/references you collected during making the proposal.
18. Each team member's contribution. You should state only the contribution to the technical work (such as thinking of the proposed updates, looking for the data, etc.), so writing the document for example shouldn't be included here. Statements like "we divided the work equally" are **not accepted**; have a clear and fair division of work.

## Deliverables

1. A quality document (PDF) containing the requirements.

## Guidelines for choosing the problem

Those guidelines are not mandatory (as long as you understand what you are doing), however, they might help you avoid struggles past students faced.

### 1. Resources

The following are great hubs to search for a paper with code.

* [Papers with Code SOTA](https://paperswithcode.com/sota) (_Recommended_)
* [Kaggle Datasets](https://www.kaggle.com/datasets) (_If you choose this make sure the code quality is good_)

### 2. Problem Domain

I highly recommend you avoid any problem domain that works with videos or very large datasets unless you're sure the training time is feasible. Also, make sure you are comfortable with the problem and the models/solutions you found (don't select a problem if you think that the model is too complex to build on or the code is too complicated to work with).   

### 3. Dataset

Make sure the dataset is not huge to avoid problems for downloading, preprocessing, loading on memory (RAM), and training time.

### 4. Training Resources & Time

The most common problem is that you cannot train the network due to the lack of resources to meet the required training time, make sure you have this in mind while selecting your problem.

You need to ask yourself the following questions:

1. Can I train the model on a local/lab machine?
2. Can I train the model on Google Colab?
3. Can I train the model on another cloud service?

If you have access to a credit card, then [this tutorial: 'Using Azure Free 200$ Credit for Deep Learning'](https://youtu.be/EFVU8EnibXw) might be beneficial to you.

## Selected Proposals

The following are selected proposals from past years, I highly recommend you take a look at them before writing your proposal.

* [Text to Image](assets/selected_proposals/text_to_image.pdf)
* [Snake Game](assets/selected_proposals/snake_game.pdf)
* [Moving Object Detection](assets/selected_proposals/moving_object_detection.pdf)
* [Food Image Recognition](assets/selected_proposals/food_image_recognition.pdf)
* [Image Colorization](assets/selected_proposals/image_colorization.pdf)
* [Artistic Style Transfer For Videos](assets/selected_proposals/style_transfer.pdf)
* [Anomaly detection using AEs](assets/selected_proposals/anomaly_detection.pdf)

**Note**: Those proposals might have been made under different requirements, just because any of them doesn't meet any of our requirements doesn't give you the ability to do the same.

## FAQs

### 1. What happens next?

We will review your proposal and check that it meets each individual specified requirement and whether **accept, accept with updates, or reject it**.

The proposal update phase (the first week after the proposal submission) will be used to **update the proposal in case of rejection or update request**. We will send you feedback on your proposals pointing out any points you need to update.

### 2. How this phase is graded?

* Each individual specified **requirement** has a grade.
* Clear amount of **effort** done.
* Overall proposal document **quality**.
* The **readability** of the proposal.

### 3. What is not acceptable in this phase?

The following are some examples of unacceptable work in proposals:

* Just copying one or two papers into the proposal and sort the proposal in a different order.
* Having sentences like "We achieved the state of the art results", which shows clearly that you didn't write this proposal specifically to us.
* Some proposals assume that the reader is aware of all the world terminology, sentences like "We will use LR image" and I'm left to figure out what is LR.
* Some proposals don't state clearly the base model or any model, sentences like "we will use sequence to sequence". How am I supposed to know what type of model you will use from the sequence-to-sequence family?
* Missing a requirement or disregarding any of its details without justification.
* Hastily compiling the document without caring about its **readability** and **clarity**.

You need to be precise, discrete, and organized. Make sure to address us and show us your level of understanding in a clear way. Make sure to cite all the references you use and **do not copy**, write in your own words to show us what you understand.

### 4. Can I use the same problem proposed in selected proposals or past project websites?

Unless you provide a **major update** we will most probably reject your proposal.

### 5. Can I use the same problem statement I use in my graduation project (or thesis)?

You can use the same domain, but **you have to tackle a different issue other than the one you're investigating in your graduation project (thesis)**.

### 6. What happens if I miss listing any of the projects I participated in that are similar to my course project?

If we find out that any other course you were enlisted in with a similar problem statement and you haven't notified us, **the cheating and plagiarism policy will be applied**.

### 7. Can I resubmit a better version of the proposal in the update phase?

The update phase is only to consider the points that we mention you need to **update** and shouldn't be regarded as an extension to the original proposal deadline. We might mention that there are missing requirements, etc. in the proposal, **this doesn't have to mean that you should resubmit the proposal**, just consider fulfilling the requirements in the following project stages. **Unless clearly instructed to resubmit the proposal, do not do so**. 

### 8. Is the grade updated after the update phase?

No, the grade is based on the **initial proposal submission** so be sure to make as much effort in it as possible and deliver the best you can.

### 9. Can I change some of the details mentioned in the proposal at a later stage in the project?

Unless you are instructed to do so or there is a reasonable justification for this, we won't accept it. You should stick to what you propose and consider the feedback we send in the update phase.

### 10. What can be considered a major update when selecting a problem proposed in a past project?

This includes for example choosing a different baseline model, proposing new updates rather than those suggested in the past project, and addressing a different issue. The same goes for selecting a problem you already tackled in a machine learning project or are tackling in the graduation project (building in the course project on your work in another project or vice versa is **not accepted**).

### 11. Is there a specific structure required for the proposal document?

You can structure the proposal document the way you like as long as you **cover each individual requirement** with its mentioned details in a **clear and readable** way.

### 12. How do I get the state-of-the-art results for my problem?

You can use the PapersWithCode website (check the shared resources above) or look into the most recent papers in your targetted domain to determine the state-of-the-art in the problem. You need to determine the best quantitative results right now in the problem you chose based on the correct evaluation metrics. State the top 1 or 2 solutions to the problem (what is the name of the paper, for example), and for each, mention their results.

### 13. What models should I include in the survey?

In addition to the model you chose as the baseline, you need to include some models used in solving the problem (this can include but **not limited to** the top models mentioned in the state-of-the-art section). 

### 14. Should I include the code and weights for all models or only the baseline?

You can include it for the baseline only if it is not available for the other models. If it is available, you should include it as it can help later on if the baseline is not suitable. Nevertheless, unless you know what you are doing, you must select a baseline with **available code and weights**, otherwise explicitly justify how you will go on with the project.

### 15. How do I compare the surveyed model results?

You should include a table comparing the results of the models as stated in the requirements above. For a fair comparison, you need to specify the dataset on which the results are obtained (this should be done for **any** results you indicate since the results of a model differ based on the dataset even when the model is unchanged).

### 16. How do I think of updates?

You need to propose updates that can improve the baseline based on your gut feeling. Here are some guidelines:
1. Look into other papers different from your chosen baseline and determine what ideas used there weren't used in the baseline. You can augment your baseline with ideas/parts from other papers or change parts from your baseline with ideas from other papers. 
2. You can also think of other stages rather than the model architecture, for example using data augmentation, using a different type of learning (e.g., ensemble learning), making better model interpretability analysis (using SHAP or CAM - class activation mapping)
3. You can check the past projects' website and proposals and see how your colleagues thought of improvements in the past semesters. This can give you an idea of what to think of when looking into updates in your chosen problem.

### 17. How do I find the correct evaluation metrics for my problem?

1. You can check PapersWithCode website (check the shared resources above) and the papers you collect when surveying for models and solutions to the problem; the papers will include the results using the evaluation metrics used in solving the problem (mainly in the papers, you will find an evaluation section near the end, you can check what metrics were used there).
2. You can also Google for the used evaluation metrics for your targetted domain of problems (For example, accuracy, F1, precision, etc. are used with classification, BLEU, ROUGE, etc. are used with NLP problems, MSE, MAE, RMS, etc. are used with regression problems and so on).
3. Each metric will evaluate your model differently of course, **so you need to understand what this metric calculates**.
