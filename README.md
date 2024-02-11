<h1>Visualize Data using Amazon QuickSight</h1>


<h2>Description</h2>
This project focuses on creating visualizations from a large dataset containing information about 50,000 best-selling products on Amazon.com. 
The goal is to leverage Amazon S3 for data storage and Amazon QuickSight for visualization to gain insights into the trends and patterns of these products.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Amazon S3</b> 
- <b>Amazon Quicksight</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Step #1: Download the Dataset
- Navigate to [2-s3-quicksight](https://github.com/techwithlucy/youtube) to download the "Amazon Bestseller Dataset" CSV file and the "manifest.json" file.
- Click on "raw" and Control+S to save both files onto your computer.
: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step #2: Store the Dataset in Amazon S3
Open the Amazon S3 console and click "Create Bucket."
Name the bucket (e.g., "lucy-amazon-project") and keep the settings as default.
Upload the CSV file and the "manifest.json" file into the bucket.
Replace the URL in the "manifest.json" file with the S3 URL of your dataset.
:  <br/>
<img https://imgur.com/a/xAxQwnK"/>
<br />
<br />
Step #3: Connect S3 Bucket with Amazon Quicksight
Open the AWS management console and navigate to Amazon Quicksight.
Sign up for a free trial of the Enterprise edition if you don't have an account.
Select Amazon S3 and tick the box for the S3 etcbucket you created.
Enter the link to your "manifest.json" file and connect to Quicksight.
Select "interactive sheet" to start creating visualizations.
: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step #4: Create Visualizations
Drag fields into the graph to create visualizations (e.g., Most popular brands).
Sort, filter, and customize the graphs as desired.
Experiment with different types of graphs like bar charts, pie charts, line graphs,
:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step #4: Create Visualizations
Drag fields into the graph to create visualizations (e.g., Most popular brands).
Sort, filter, and customize the graphs as desired.
Experiment with different types of graphs like bar charts, pie charts, line graphs,
:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
