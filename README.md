# Neuroimaging Data Processing Visualization Web Application 

**Project Overview:**
* Completed as a team project in a Computer Science Senior Design course, the purpose of the project is to develop movement analysis graphs in Python to track excessive head motion during functional MRI (fMRI) scans. Build a React-based frontend for researchers to access fMRI data outputs to reduce manual preprocessing efforts. This website is designed to display and analyze outputs from fMRIprep, specifically the images it produces. It provides different ways to view these images and plots, catering to both specific subjects and subject types.

**Tools & Skills:**
* Python, Flask, React, Google Cloud Platform
* Data Processing, Visualizations in Python, Front-End/Back-End Development
* Acknowledgment: Thank you to the Neuroscience department at UCR for providing this dataset.

**fMRI Subject Image Viewing:**
* Viewing Images for a Specific Subject: You can view all images created for a specific subject on one page. This allows for easy comparison and analysis of different image outputs related to a single subject.
* Viewing Images for a Specific Subject Type: Alternatively, you can view all images created for a specific subject type on one page. This helps in analyzing trends and patterns across multiple subjects of the same type.

**Plotting:**
* For each desc-confounds_timeseries.tsv file, three different types of plots are generated:

* Rotation Plot: Displays rotation values (rot_x, rot_y, rot_z) over time.
* Translation Plot: Displays translation values (trans_x, trans_y, trans_z) over time.
* Framewise Displacement Plot: Displays framewise displacement values over time.

**Threshold/Spikes Functionality:**
* The website includes a threshold/spike function that allows users to input a threshold and a maximum number of spikes. It will output all framewise displacement plots that exceed the specified threshold and have spikes above the given maximum threshold.

To run the website, SSH Tunnel into the VM using VS Code. 
