# Ryan Jeon, Ph.D. Student, Computer Vision and Data Science

## Programming Languages: 
Python (Pandas, Pytorch, matplotlib, scikit-learn, Tensorflow, OpenCV, nltk, Seaborn, etc), R (dplyr, ggplot2, lme4, etc), UNIX commands (Basic), Hive (Basic), SQL, Microsoft Office.

## Education:
**Doctor of Philosophy (Ph.D.) in Agricultural Engineering** \
Iowa State University \
June 2020 – December 2022

**Masters in Genetics and Genomics**\
Iowa State University \
August 2018 – June 2020

**Bachelor of Science in Bioengineering** \
The Ohio State University \
August 2012 – June 2018


## Ph.D. Research Projects:
### 1) Computer Vision Based Activity Recognition through Pose Estimation of Commercial Swine
#### Iowa State University Graduate Research Assistant 
#### June 2021 - Present


◦ **Machine Learning Object Detection and Activity Classification:** Developed a computer vision based algorithm to identify a piglet and then quantify distance each pig moved using Python. The specific physical activity was further classified using machine learning techniques (Random Forest). Below are two frames captured from a piglet object detector. What is not shown is that the algorithm also measures the pixel distance the centroid of each boundary box moves as the video progresses. Imagine a paintbrush in the center of each green box dragged along as the pig moves- that length is what we can measure.

<p align="center">
  <img alt="3" src="https://user-images.githubusercontent.com/69263707/141250529-8dfa4294-dac8-4d75-8bc9-4ef034cf9f2e.png" width="420"> 
  
  <img alt="1" src="https://user-images.githubusercontent.com/69263707/141250809-e386d872-a132-4327-8092-8585b041a11b.png" width="420">

</p>


◦ **Machine Learning:** Implemented a Resnet34 classification model and a YOLOv5 object detection model on a custom image data set using image segmentation to strategize computer vision based solutions for pose estimation. Below are results from using a custom pig ear detector, to assess the ability to use the pig head as a clue to estimating the pose of the animal.

<p align="center">
  <img alt="3" src="https://user-images.githubusercontent.com/69263707/141251461-35aead94-e8b7-4b55-a7da-0f79f2722d5b.jpeg" width="350">
  
  <img alt="3" src="https://user-images.githubusercontent.com/69263707/141251377-823b3dcb-3b0c-41de-9fa5-31f3c213d8a0.jpeg" width="350">
</p>


◦ **Estimation of Pig Body Pose:** Determined that body pose can be estimated by training the custom object detection model to identify the coordinates of the boundary box that encloses the pig head, to approximate the direction the pig was facing, by determining the side of the pig’s boundary box closest to the centroid of the head.
<p align="center">
    <img alt="3" src="https://user-images.githubusercontent.com/69263707/141256208-6a437048-849d-4760-aa04-6d75a0f87d7a.png" width="400">
  
  <img alt="3" src="https://user-images.githubusercontent.com/69263707/141256211-5299f987-9591-4164-b061-3a3278fa5a7e.png" width="400">
  


</p>

-Image for boundary box coming soon-



◦ **Meta: Augmented Reality in Livestock:** Developing a program to superimpose a segmented pig image onto a rendered pig to estimate body condition and fitness of the animal, from only one side view. This creative solution bypasses many problems associated with traditional computer vision based phenotyping in the livestock industry.


Here is an example of an RGB image we used

<p align="center">
    <img alt="3" src="https://user-images.githubusercontent.com/69263707/141257769-571f0764-7a50-4fdb-973e-378c8cf3bf3d.jpg" width="350">
</p>


Here is what it looks like in RGB-D!
<p align="center">
    <img alt="3" src="https://user-images.githubusercontent.com/69263707/141257780-b685438b-fba5-4059-9650-efd02e34f578.png" width="350">
</p>


Here is the tricky part- we got to mask out the pig to get a clean segmented image. Luckily we have OpenCV functions on Python. 
Here is it segmented!

<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141258311-ffdb49f5-b586-4c40-b019-6690bb89c3fb.jpg" width="350">

</p>






### 2) Time Series of Analysis of Heat Treated Swine
◦ **Leadership:** Directed and managed a team of undergraduates on bimonthly six hour road trips during the summer, to an off campus swine research site for the setup of pigs and environmental sensors for the collection of environmental time series data. 

◦ **Data Collection:** Created a polished time series dataset by pre-processing data and imputing missing values.

◦ **Time Series Analysis:** Conducted the method of least-squares on R to statistically determine the impact of hot
air temperature on six different body parts of the pig, for three different pig body weight groups, on two different pig housing conditions, over four different periods of time.
  
  Here is a plot to illustrate a small part of the time series data I was working with
<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141353586-bc5bb7dd-82f6-42cc-8f75-0dff8e7bb0b2.png" width="650">

</p>




### 3) Estimating Body Condition and Fitness of Swine using Computer Vision
◦ **Feature Extraction:** Built a computer vision based system on Python using OpenCV to objectively calculate various body measurements of pigs for optimized feature extraction. This method implemented image segmentation, contouring, skeletonizing, Douglas Peucker transformation, and trigonometry. Below are some of the body measurement angles I estimated. 

*For those unsure of why this is important...With over 23 million pigs housed across Iowa farms, the pork industry generates over 7 billion dollars to the Iowa economy each year, highlighting the swine industries valuable contribution to the economic vitality of Iowa. One of the most important biological factors that contribute to this prosperity is the reproductive success of the pigs. Improving the selection of gilts, or potential mother pigs, can return an estimated 23 million dollars back into the swine industry each year. The facts are clear: strong, healthy female pigs are a necessity for raising strong healthy piglets. One way we can measure body condition of the female pigs is by looking at the knee and feet angle.*

<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141259292-0a836a18-850c-4302-a2f0-a76026e0e78c.png" width="550">

</p>



◦ **Optimized Phenotyping:** Developed a geometric algorithm that demonstrated higher speed, precision (0.97), and objectivity than data collected from manual body measurements, thereby modernizing and optimizing gilt selection practices in the swine industry.

Here is an award I received for my poster competition. I also was awarded the 3MT award for my graduate seminar course for this presentation. 

<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141258975-28b6d495-7776-4883-a256-6235049ad090.jpeg" width="450">

</p>


## Masters Thesis: 
### Genetic Indicators for Swine Fitness and Body Condition under Stress 
◦ **Correlations between Swine Fitness and Genetics:** Implemented statistical techniques on R to a large immunology dataset to demonstrate that a genetic mutation in swine was significantly associated with higher fitness, body fat percentage, resilience, and health status in pigs.

Here is an example of some code I ran to show that a particular genotype (combinatination of alleles) in the WUR gene was associated with higher weight gain in pigs:
<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141354421-c5460d6f-6a7b-4616-b77e-79ab2d9c7340.png" width="450">

</p>



◦ **Heritability of Swine Fitness:** Collaborated with a team to estimate the heritability of over 100 physiological traits in pigs to determine the genetic correlation between disease traits and immune cell proliferation from a novel mitogen stimulation assay. *Heritability is estimated from the regression of offspring phenotype on the average phenotype of the parents*

Here is an example figure from my Masters dissertation on calculating heritability of certain traits
<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141355085-6a802a5f-4bc3-4075-9f16-3c5ba8318eae.png" width="450">

</p>


## Side Projects
• **LivestockCV:** Published an open source python library for those new to computer vision, undergraduates, veterinarians or animal scientists who wish to implement computer vision strategies on image and video of livestock animals.

• **Apple Watch Body Fat Percentage Tracker:** Visualization of body fat percent changes over a year, regressed against aggregated monthly averages of cardio using the Apple Watch API. Determined through a correlation matrix that increased cardio was associated with decreased body fat percentage. Developed code to further analyze personal cardiovascular activity recognition and classification over different sports and activities. Below is a correlation matrix I made using some fitness variables as well as two synthetic variables I created.


<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141260284-49f231e7-25b4-427e-8e90-74094da8d9bc.png" width="650">

</p>



• **Web Scraping Indeed.com:** Developed a user defined function to web scrape Indeed.com for specified jobs, locations, and important keywords. Outputs a .csv file of the job title, company name, job description, and the indeed.com job posting URL of the first 200 job entries. The job descriptions were further parsed using NLTK to remove stop words and output a histogram of the top twenty most frequently used words in the job description. Below is the histogram.

<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141259672-2e26cb42-d02a-4a37-8a86-4ac9bc26ca0e.png" width="650">

</p>

• **Automated Piglet Wellbeing Dashboard:** Designed an computer vision based HVAC control dashboard for regulating ideal piglet temperatures on C++ using a PixyCam sensor and various different environmental sensors to prevent heat stress by holistically regulating the overall condition of the piglet. Increased temperatures and humidity would turn on an AC unit, while decreased temperatures would turn on a central heating pad for the piglets.

Here is a schematic of the Arduino hardware that I built.
<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141355597-f2fa88ec-cd39-4cde-b58d-a5cb6475da7f.png" width="650">


</p>



• **Automated Fashion Color Palette:** Currently developing a sports fashion data mining program that can data mine different types of shoes from Nike and Adidas to output a color palette of each new shoe using KMeans clustering. Then this program will output a frequency plot to show based on the collected data, which colors are most used, to qualitatively answer the question, which colors are now in style for the season. Results are surprisingly different depending on the type of shoe (basketball vs cleats vs boots), season, and gender). Here are two barplots I created just from mining the Nike website. You can see that the colors most common in cleats are brighter from those in skateboarding shoes, which I thought used more muted colors.  

<p align="center">
   <img alt="3" src="https://user-images.githubusercontent.com/69263707/141364839-c3608e17-66ef-4793-bf3e-f535f4ca6f90.png" width="450">
  <img alt="3" src="https://user-images.githubusercontent.com/69263707/141364841-aed4c6d6-3a07-4a88-a9a5-dd252ab46a11.png" width="450">

</p>


## Publications
• **Effect of a Genetic Marker for the GBP5 Gene on Resilience to a Polymicrobial Natural Disease Challenge in Pigs:** https://doi.org/10.1016/j.livsci.2021.104399

• **An Introduction to Automated Visual Sensemaking for Animal Production Systems:** https://elibrary.asabe.org/abstract.asp?aid=52179

• **Proliferation of Peripheral Blood Mononuclear Cells From Healthy Piglets After Mitogen Stimulation as Indicators of Disease Resilience:** https://doi.org/10.1093/jas/skab084

## Conference Presentations and Professional Seminars

• **Automated Visual Angle Measurements in Gilt Selection:** ASABE Annual International Meeting, July 12, 2021

• **Three Minute Thesis Competition:** Iowa State University, December 1st, 2020

• **Genetic Indicators for Disease Resilience:** Masters Thesis Seminar, Iowa State University, March 13, 2020

• **Effect of Genotype at a Genetic Marker for GBP5 on Resilience to a Polymicrobial Natural Disease
Challenge in Pigs:** Plant and Animal Genome (PAG) Conference, San Diego, California, January 11-15, 2020

• **The Proliferation of Blood Mononuclear Cells in Early Age and Healthy Piglets after Mitogen
Stimulation, as a Possible Indicator of Disease Resilience in Pigs:** Iowa State University, November 20, 2019

• **Effect of Genotype at a Genetic Marker for GBP-5 on Resilience to a Polymicrobial Natural Disease
Challenge in Pigs:** North American PRRS Symposium, Chicago, Illinois, November 2-3, 2019

• **Effect of Genotype at a GBP-5 Marker on Resilience to a Polymicrobial Natural Disease Challenge in
Pigs:** American Society of Animal Science (ASAS) Midwest Section, Omaha, Nebraska, March 11-13, 2019

• **Recyclability of Inedible Plant Biomass:** National Aeronautics and Space Administration (NASA), Kennedy Space
Station, Florida, March 14th, 2016

## Presentation Awards
• **ASABE Student Presentation Competition:** ASABE Annual International Meeting, July 12, 2021

• **First Place (Virtual), Three Minute Thesis:** Iowa State University, December 1st, 2020

• **Elanco Animal Health Travel Fellowship:** North American PRRS Symposium, Chicago, Illinois, November 3, 2019
