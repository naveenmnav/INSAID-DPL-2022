
Hello Everyone,

This repository contains the files that I have used during the **INSAID's Data Premier League - 2022** Hackathon that took place on 28th - 29th May 2022.

This has been my First Hackathon I have ever attended and I have achieved a Milestone on coming **3rd Place** among the 200+ participants who have registered and participated. 


![Certificate](https://lh3.googleusercontent.com/hW6Ow_mblVjg4uS7khvhN54qbYfS-b4SHlEOglkHwkd9mv3RMmMR3t5nF5SYnot-81LSZDhhVER7xc98D10Kg3tgdbD_ir2UWdE8ylHDpwaIfSo36qfb2RpWW08n9LoSLUHDTt-wP9Yi_Bp3HPHqtlQhShMIZK5K203gCTiMLDDOvH64cbH4P3wwjMD1TrkUk8qrRGKQQgXK8CiySqssRraty6FRsOPv1khR9B3V_j-gv8hDEbK8bZLGMyfIEXjTk6xgUZfpz0sg2K64nbIBxmSIZNs9kqvpCFwWEvZrbeerFC6XPHmSQLNqpwceGwU0A3dVLvTRLYSzDIsCHgZdb7lTdbgsZJGj4x7XO1lkYaZUUSoRLjdzAnahgQS-_zxPuWcFRmuEC7jNE_v4ReRCam0wv1kPi-F4uKO_D48u4qCMfNJhzLCIKWKskQpEir-zinun-4KCOKOekBluYPDFEJ0YkGyTz75DCKaQlzfqF6HbIhGBUDHNXHwWIQBHdq7rJIJWJpeI7AvgOe1SHXvMgJbrtQl7MepiQjGsC6n23kGDdrfdCHKJn_woo7tgkI7DikcnkbwV4HsrF_obtXqzD69_2-f_WmAv6keLu84Glw0WwhPPvVe7VH6RwOnv_RGMRtSWddDy-sq_nhs7iJCU3eveCYT3wGSMQH_ijzgqbPYEH6vg9xJbS4bkmRUQLChMiVhHcUNzvqikCXJP_91aPeZKjIneo4puB7cJZl25kmQOL05MqNHdOYwm1gx8nB4wZfayDO_y34gm_a4T-giD87Du2b5SNe_1apwrycrMQEtVwY-vADJbn8ZFxOinf4tr0E9dHw=w373-h208-no?authuser=0)



**CONTENTS OF THE REPOSITORY:**

 - DPL.ipynb -> Jupyter Notebook containing the code
 - Test_Data.csv -> The test data provided
 - Training_Data.csv -> The training data provided
 - actual_labels.csv -> The actual labels provided
 - submission.csv -> The predicted labels from the ML models

# **Challenge - DPL Match Winners Prediction**


# **1.Company Introduction**

----------


-   Your client for this project is  **One-shot Association**.
-   **INSAID Corp**  is an Indian analytics company.
-   Established in  **2018**, it is one of the  **top analytics companies**  in  **India**.
-   They provide  **regular maintenance**  for their  **clients**  and  **customers**  which enables them to make their products more robust and their services promote longevity.
-   With a recent project requirement from  **One-shot Association**, the official partners of  **DPL**,  **INSAID Corp**  has boarded a project that requires making an  **automatic system**  that can predict the winner of the  **Data Premier League**

# **About Data Premier League (DPL)**

----------

-   **DPL**  is a cricket tournament, unlike  **IPL**, and is played between  **4 teams**.
-   The teams are respectively:
-   **Kolkata Superstars**
-   **Chennai Strikers**
-   **Bangalore Royals**
-   **Mumbai Lords**
-   However, this is a tournament that has been going on for more than  **15 years**  now.
-   As a result, a total number of  **797 data points**  has been collected.

### **Current Scenario**

----------

-   The company is planning to introduce a system that can help them to determine the match winners for the game in  **DPL**  based on the dataset provided.

# **3. Problem Statement**

----------


-   The current process suffers from the following problems:
-   The project that has been onboarded needs to be done automatically.
-   **Prediction of the winner**  is a very  **resource-heavy**  and  **time-consuming**  process.
-   The company has hired you as a  **data scientist.**
-   They want to automate the process of  **Predicting the match-winner**

### **Your Role**

----------

-   You are given a data set that contains information about the client’s  **data.**
-   Your task is to build a  **multi-label classification model**  using the  **dataset.**
-   Because there was  **no machine learning model**  for this problem in the company, you don’t have a  **quantifiable win condition.**
-   You need to build the best  **possible model.**

### **Project Deliverables**

----------

-   **Deliverable:**  Predict the winner of the game.
-   **Machine Learning Task:**  Multilabel Classification
-   **Target Variable:**  winner
-   **Win Condition:**  N/A (best possible model)

### **Evaluation Metric**

----------

-   The model evaluation will be based on the  **AUC- ROC Score**.
-   To Learn how to apply AUC ROC Score as an evaluation metric visit  [here](https://www.youtube.com/watch?v=ZlGz9Nl5irs)

# **4. Dataset Description**

----------


-   You are given a data set that contains information about the  **DPL Data**.
-   The dataset contains  **train**  and  **test**  datasets.
-   You need to train the machine learning model using the  **Train**  data and predict the  **winner**  using the  **test**  dataset.
-   The  **test**  dataset is itself the  **unseen data**.

### **Feature Description**

----------

The feature description is as follows


![](https://lh3.googleusercontent.com/39Er4B7MD9Lz_ZankhsGOSPKz0JmxNbyTRzG6Fy6Uzmr81gn4BPDThmw6zasVZd_yOmhpvmE6LXAzrpIHDlOaec4yhxMNG2jXh7r8wRZKIF4Z0xTDrBYTRWnwPcb0G5lFd0e0z4tLyWq1YNJNxuBy_s7GRdCSlchxvjT1T1coEoqRPnEc0QSucvDkXBufzodmE3a3adIoUk6SKPYw7QuJCKVcMkKNDUotBvvxme6kbw_BaBQgpwanloDAhyL487bxh_4cYd0Hy3Rd-3CfQtfE_w6AnV7QwFS92cNdzSYgrlriZezVqkQUbQK2jzZvMjHvz1DrUiFKuFlSXeHptm9sDntJ-Q69lH9VN4GXqYVnnMgIgF_KJGTvIuSnzCplbo_RHSGHXl9q8qbwi2npohtqVAbhxtwVGnebKUw3C-xKGojcHsugzexhoJhf-5qlGECIhbnwaXsMFKWiSldL9JjISkNMTwCnwXRs1Ztld1BcGdAZPCdfFYZ4qVDHN25Lq1vT9zWz9ef8ktaVsFJdUuaTX08ct4qpSD2XlSzW4o-D6TJmFulTtYm_lUp2iIL0tb87LA0hox3_4KClCFwbbXcTn1RVzTpO55OjBgDPUVsHtydpJDkKThINuRExfYc5Ba3b3YtIqvXTzAiWabMZ1gSctHsSJOLXUx0Z2qJlwItN_6Tvr-j6rL2B_mKxwVZ7yUC2Mt9pO503oHNCAwQ-JGRwvB29uh3JA3NJEPBvJx4sHOv6GDHK2QEkRjAWA2etSW0_A-piaCUpqQ95v1bMCo5Mbd-sZqAQ67t9zDSuGfdZpKeLmh-RAqXel3lEDssIYd84W7ScA=w434-h533-no?authuser=0)

# **5. Making the Submission File**

----------


-   The submission file should be in the csv format.
-   It should only have  **2**  columns, 1st column:  **Id**  values, and 2nd column: predicted  **winner**  values.
-   The size of the submission file should be  **164 rows**  and  **2 columns.**
-   Make your submission file with the following command  
    **`submission = pd.DataFrame({'id':data_test['id'],'winner':y_pred[:,1]})`**
-   Here  **`data_test`**  is the  **test dataset**  and  **`y_pred1`**  is the  **predicted winners**  .
-   Once you get the output copy and paste it into a notepad and then save the notepad as  **submission.csv**  .
