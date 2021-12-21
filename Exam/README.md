# ADA Final Exam

This repository contains the final exam for Applied Data Analysis (CS-401).

The questions and the data will be made available to you at 8:15 A.M. on January 25th, 2022 via the Jupyter Notebook named "exam.ipynb" and the folder named `data`, respectively.

All the logistical details, rules, and guidelines pertaining to the exam are stated below. 

Additionally, to iron-out critical logistical aspects, such as execution environment setup, sharing of high-level rules, and submission process of your solved exam, we would like each of you to participate in a dry-run of the exam. Please see the [dry-run instructions](#Dry-run-Instructions) section at the bottom of this document for details.

## Conda Environment
We have prepared a conda environment, named `adaexam`, with all the Python packages that you might need for the exam. You can install it with the following command:   
`conda env create -f adaexam_crossplatform.yml`

Once installed, to activate the environment, please use `conda activate adaexam`. To use it in Jupyter, please initiate Jupyter from a terminal with adaexam as the active conda environment. Alternatively, you can add the conda environment as a custom kernel by using the following command:   
`python -m ipykernel install --user --name=adaexam`

*Note-1: You are of course welcome to install any additional package to the aforementioned conda environment.*   
*Note-2: The aforementioned setup has already been tested by the ADA teaching staff on Mac OS Big Sur 11.4, Ubuntu 20.04, and Windows 10.*

## Timeline
**Exam date:** Tuesday, January 25th, 2022   
**Exam start:** 8:15 A.M. (CET/UTC+1h)   
**Exam end:** 11:15 A.M. (CET/UTC+1h)   
We allow a grace period of 15 minutes for you to submit your solved IPython notebooks. The strict deadline is at 11:30 A.M. **Later submissions will not be accepted!**

## High-level Guidelines and Rules

1. You cannot leave the room in the first and last 15 minutes.
2. You can use all the online resources you want except for communication tools (emails, web chats, forums, phone, etc.). We will be monitoring the network for unusual activity between 8:00 and 11:30 AM.
3. Announcements during the exam, if any, would be made under the *"Announcements"* section of [this Google document](https://docs.google.com/document/d/e/2PACX-1vScUO5POEwsmVHCdq3NIe1lcooBRKr88QxgtdCcZss_DwEESene0yhndIod2EQ_wV_QoG_CkHgqSYPY/pub).   
   *Note: For sharing documents with more than 100 viewers, Google recommends publishing them to the web (details [here](https://support.google.com/a/users/answer/9308870?hl=en)). As a consequence, the document may no longer be updated in real time by your Web browser. Thus, in order to view an up-to-date version of the document you might need to periodically refresh the page.*   
4. You have to open "exam.ipynb" in Jupyter, edit it, and submit it with your solutions.
5. You have *3 hours* (8:15 -- 11:15) to solve the exam and upload your solved iPython (.ipynb) notebook.
6. We have prepared a conda environment with all the necessary Python packages. If not done already, you can install it with the following command:   
`conda env create -f adaexam_crossplatform.yml`
7. You are allowed to use any built-in Python library that comes with Anaconda.
8. You are allowed to use [Google Colab](https://colab.research.google.com/) or [EPFL Noto](https://noto.epfl.ch), however, it's your responsibility to ensure that the required Python packages (see the section [Conda environment](#Conda-environment) for details) are accessible in the execution environment and platform of choice.
9. There are **two tasks:** A and B, which are further split into several subtasks.
10. The tasks are **independent** of each other, and you can solve them in your order of preference.
11. For questions containing the **/Discuss:/** prefix, answer not with code, but with a textual explanation (in markdown).
12. Don't forget to add a textual description of your thought process, the assumptions you made, and your results!
13. Please write all your comments in English, and use meaningful variable names in your code.
14. As we have seen during the semester, data science is all about multiple iterations on the same dataset. We suggest that you not obsess over small details in the beginning, and try to complete as many tasks as possible during the first 2 hours. Then, go back to the obtained results, write meaningful comments, and debug your code if you have found any glaring mistake.
15. Fully read the instructions for each question before starting to solve it to avoid misunderstandings, and remember to save your notebook often!
16. We will **not run your notebook for you**! Rather, we will grade it as is, which means that only the results contained in your evaluated code cells will be considered, and we will not see the results in unevaluated code cells. Thus, be sure to hand in a **fully-run and evaluated notebook**.
17. In continuation to the previous point, interactive plots, such as those generated using `plotly`, should be **strictly avoided**!
18. Remember, this is not a homework assignment -- no teamwork allowed!

## Submission
* You will have until 11:30 (strict deadline) to turn in your submission. **Late submissions will not be accepted.**
* For students **with** an EPFL email address:
   * Your file has to be named as "YourSCIPERNumber.ipynb". For example, if your SCIPER number is '123456', please name your file as '123456.ipynb'.   
   **Note-1: We won't grade your exam if the file is not properly named, thus, be extra careful in this regard.**   
   *Note-2: The Google form upload utility might automatically append the name on your EPFL account to the filename provided by you, thus, don't be alarmed if this happens. For instance, if your name on the EPFL account is 'Abc Xyz' and you upload the file '123456.ipynb', it might be renamed to '123456 - Abc Xyz.ipynb'*
   * Upload your Jupyter Notebook (1 file) to [this Google form](https://forms.gle/uhJxN2ie4nD4CV1t7) at the end of the exam, with all the cells already evaluated. You need to **sign in to Google** using your **EPFL credentials** in order to access the form. Please see [this EPFL Wiki](https://wiki.epfl.ch/help-gdrive-en) (accessible only from the EPFL network or via VPN if not physically on campus) for more details on how to use Google services via your EPFL credentials.   
   *Note-1: If you get a *'You need permission'* message, then it means you are trying to access the Google form via a non-EPFL account. This can be fixed by opening the submission link in a private/incognito window and signing in using your EPFL credentials.   
   *Note-2: You can correct 'typos' in your name using the "edit response" option, however, the uploaded 'ipynb' file cannot be modified. If you need to modify the ‘ipynb’ file, please create a new submission.*   
   *Note-3: Multiple submissions are allowed. We will only consider the **latest** submission before the deadline and ignore all other previous submissions.*
   * On successful submission, you should receive an acknowledgement email from forms-receipts-noreply@google.com. If you don't receive an acknowledgement email (check your ‘spam’ and ‘junk’ folders as well) by 12:30 PM, please notify us by sending an email to ada-core-assistants-2021@groupes.epfl.ch.
   * In case of problems with the form, send your Jupyter Notebook via email to ada-core-assistants-2021@groupes.epfl.ch. This is reserved only for those who encounter problems with the submission - you need to have a **reasonable justification** for using this backup.
* For students **without** an EPFL email address:
   * Your file has to be named (in *titlecase*) as "YourFirstName_YourLastName.ipynb". For example, if your first name is 'Abc', and last name is 'Xyz', please name your file as 'Abc_Xyz.ipynb'.   
   **Note: We won't grade your exam if the file is not properly named, thus, be extra careful in this regard.**   
   * Send your Jupyter Notebook (1 file) via email to ada-core-assistants-2021@groupes.epfl.ch.

## Dry-run Instructions

Complete the following steps for a smooth exam experience on the day of the exam:
1. Carefully read and familiarize yourself with all the aforementioned rules and instructions.
2. Set up the `adaexam` [conda environment](#Conda-Environment).
3. Execute all the cells of `exam_dryrun.ipynb` in Jupyter with `adaexam` as the active conda environment. On successful execution, it should print **'Package import test successful!'** without throwing any errors!
4. Make sure you can access the [Google document](https://docs.google.com/document/d/e/2PACX-1vScUO5POEwsmVHCdq3NIe1lcooBRKr88QxgtdCcZss_DwEESene0yhndIod2EQ_wV_QoG_CkHgqSYPY/pub) containing the *"Announcements"* section. This document would be used for sharing the announcements during the exam.
5. **[Only for students with an EPFL email address]** Test the [submission](#Submission) utility by submitting any 'ipynb' file using [the Google form](https://forms.gle/uhJxN2ie4nD4CV1t7). On successful submission, you should receive an acknowledgement email from forms-receipts-noreply@google.com.

*Note: **Please don't skip any step, and also don't wait until the last moment to perform the dry-run.** Additionally, if you face any problems in carrying out the aforementioned steps or have any doubts regarding the rules, please reach out to us via Zulip by posting your questions (please use meaningful topic categorizations) in the public stream named **[#Exam](https://ada2021epfl.zulipchat.com/#narrow/stream/310586-Exam)**.*
