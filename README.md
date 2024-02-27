# matplotlib_challenge

The goal of this project was to perform a high level data analysis for cancer treating drugs that were tested on mice diagnosed with squamous cell carcinomas. One drug of interest, Capomulin, was compared to other cancer treating drugs over the course of 45 days. 

Visualizations were created with matplotlib and a linear regression was performed to see if there was a correlation between mouse weight and average tumor volume. The calculated r-value, 0.84, indicates that there is a strong correlation between the two.

Analysis began with removing duplicate records which were identified as having more than one timepoint associated with a mouse id.

After removing the duplicated records (in this case, all records belonging to mouse g989 were removed), summary statistics were calculated on the overall dataset using pandas. There are several visualizations created with matplotlib summarizing the dataset within the the notebook found in this repository.

Further analysis was performed on just four of the drugs, Capomulin, Ramicane, Infubinol, and Ceftamin. It was observed that Capomulin's results were very close to those of Ramicane. Both drugs had the smallest variability in tumor volume and the subjects also had the smallest tumor volume.

The linear regression performed on mouse weight and average tumor volume does indicate that there is a strong positive correlation between the two, meaning that as a mouse's weight increases, the tumor volume tends to increase as well.



