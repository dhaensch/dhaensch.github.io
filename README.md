### About Me
I am an 11 year insurance professional currently working on an M.S. in business analytics to combine my educational background mathematics with my professional background in insurance. I am interested in deep diving into data to try to uncover meaningful insights for data driven decision making using technology such as Excel, SQL, Tableau, Python and R.

### Table of Contents
- [About](https://github.com/dhaensch/dhaensch.github.io/blob/main/README.md#About_Me)
- [Portfolio Projects](https://github.com/dhaensch/dhaensch.github.io/blob/main/README.md#portfolio-projects)
  - Python
    - [Generating Images Based on the CIFAR-10 Dataset Using a GAN](https://github.com/dhaensch/dhaensch.github.io/blob/main/README.md#Generating_Images_Based_on_the_CIFAR-10_Dataset_Using_a_GAN)
    - [Building a Random Forest Regression Model to Predict Baseball Game Attendance using Local Outlier Factor](https://github.com/dhaensch/dhaensch.github.io/blob/main/README.md#Building_a_Random_Forest_Regression_Model_to_Predict_Baseball_Game_Attendance_using_Local_Outlier_Factor)  
  - SQL
  - R
- [Education](https://github.com/dhaensch/dhaensch.github.io/blob/main/README.md#education)
- [Work Experience](https://github.com/dhaensch/dhaensch.github.io/blob/main/README.md#work_experience)  
 
### Portfolio Projects
**Python**
- **Generating Images Based on the CIFAR-10 Dataset Using a GAN**<br><br>
  - Code: [GAN_CIFAR10.ipynb](GAN_CIFAR10/GAN_CIFAR10.ipynb)<br>
  - Goal: To create a GAN to generate false images based on CIFAR-10 dataset.  <br>
  - Description: This project focused on training a generative adversarial network to generate false images based on the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 color images of size 32×32 pixels, divided into 10 different classes. The GAN's generator and descriminator will be built using convolutional neural networks, and performance will be monitored by graphing the loss functions of the generator and discriminator and through manual inspection of generated images.<br>
  - Skills: Deep Learning, Neural Networks, Generative Adversarial Networks, Data Visualization<br>
  - Technology: Python, PyTorch, Matplotlib, Numpy<br>
  - Result: After running the GAN through 15 epochs, there was significant improvement in the quality of the generator's performance. After viewing the real and generated images side by side, the GAN does not appear to have suffered mode collapse and based on the [loss graph](GAN_CIFAR10/GAN_CIFAR10_losses_during_training.png), the model has not achieved equillibrium yet based on [image comparison](GAN_CIFAR10/GAN_CIFAR10_finale_image_comparison.png). Further parameter tuning and more training epochs are recommended for further study. <br>

- **Building a Random Forest Regression Model to Predict Baseball Game Attendance using Local Outlier Factor**<br><br>
  - Code: [Baseball_Attendance_Regression.ipynb](Baseball_Attendance_Regression/Baseball_Attendance_Regression.ipynb)<br>
  - Goal: To run predict attendance and identify important features using a baseball schedule, random forest and local outlier factor models.  <br>
  - Description: This purpose of this project was to predict attendance using a baseball schedule.  Two differentCSV files were cleaned, wrangled, and combined to form the data set. A Local Outlier Factor (LOF) unsupervised learning model was applied to remove outliers in the data. The data with and without the LOF applied was fed through a Random Forest Regression (RF) model and the outcomes were compared to see if the LOF improved the performance of the RF models. The two outcomes were compared using RMSE, MSE, MAE and R2 to compare the model fit The top 10 most important features to both models were identified.<br>
  - Skills: Data Cleaning and Wrangling, Data Visualization, Random Forest Regression, Local Outlier Factor, Machine Learning<br>
  - Technology: Python, Matplotlib, Seaborn, Numpy, Pandas, Scikit-learn <br>
  - Result: Overall, the models did a good job with the prediction. Applying the local outlier factor to remove outliers prior to the random forest application did show some improvements over a random forest only model. Looking at the predicted vs actual plots, there were still outliers present, but most of the points were clustered around the ideal line. The most important feature to both the RF and RF&LOF models was the day of the week of the game. This is a somewhat unsurprising result because one would expect higher attendance at games that occur on the weekend. Both game day and game month were in the top 10 features, but not the game hour meaning the day and month were more important to our model than the hour the game started. The rest of the top 10 most important feature spots were taken by various home teams. Home team is a large predictor of attendance in both models. <br>


**R**

**SQL**

**Tableau**

### Education
- M.S., Business Analytics | Champlain College (_Anticipated Graduation: August 2026_)
- B.A., Physics With Mathematics Minor | State University of New York College at Geneseo (_Graduation: May 2013_)


### Work Experience
**Auto Service Representative, The Hartford (_October 2021 - Present_)**
- Work independently to triage and analyze vehicle damages in a fast paced high volume atmosphere.
- Build and maintain consumer loyalty and trust while acting as technical expert on their claim.
- Communicate technical information to both a specialist and general consumer audience.
- Investigate and interpret policy contracts as they pertain to physical damage coverages.
- Maintain property and casualty and appraiser licenses across 12 states.

**Auto Damage Adjuster, GEICO (_January 2019- October 2021_)**
- Maintain high level of customer satisfaction while fairly evaluating claims.
- Act as a primary point of contact for consumers for the life of their physical damage claim.            
- Work independently to manage and prioritize large volumes of work.
- Acts as technical expert in insurance policy interpretation, state regulations and automotive repair.
- Communicate coverage and coverage decisions to clients both internal and external
- Balancing stakeholder interests to develop mutually beneficial solutions

**Personal Injury Protection Claims Examiner, GEICO (_August 2016-January 2019_)**
-  Analyze claims details and determine applicable coverage
-  Medically manage injury claims
-  Interface with customers, medical providers, and attorneys 
-  Prioritize and maintain timely and organized diary
-  Interpret and implement New York State No Fault Regulations

**Claims Service Representative, GEICO (_June 2014- August 2016_)**
- Served as primary point of contact for first notice of loss
- Handle inquiry calls on existing claims
- Evaluate claims and classify accordingly
- Provide effective communication between GEICO and diverse relevant parties
- Manage claims of clear liability to completion



