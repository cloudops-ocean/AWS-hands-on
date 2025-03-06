**Description:**

Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing
capacity in the Amazon Web Services (AWS) cloud. Using Amazon EC2
eliminates your need to invest in hardware up front so you can develop
and deploy applications faster. You can use Amazon EC2 to launch as many
or as few virtual servers as you need, configure security and
networking, and manage storage. Amazon EC2 enables you to scale up or
down to handle changes in requirements or spikes in popularity, reducing
your need to forecast traffic.

**Problem Statement:**

Company ABC wants to move their product to AWS. They have the following
things set up right now:

1\. MySQL DB

2\. Website (PHP)

The company wants high availability on this product, therefore wants
Auto Scaling to be enabled on this website

**Solution:**

Steps To Solve:

1\. Launch an EC2 Instance

![A screenshot of a computer AI-generated content may be
incorrect.](media/image1.png){width="6.007531714785652in"
height="3.1565212160979876in"}  
  
![A screenshot of a computer AI-generated content may be
incorrect.](media/image2.png){width="6.5in" height="3.3875in"}

2\. Enable Auto Scaling on these instances (minimum 2)

![](media/image3.png){width="6.5in" height="2.8055555555555554in"}  
  
![A screenshot of a computer AI-generated content may be
incorrect.](media/image4.png){width="6.5in"
height="2.821527777777778in"}  
  
![A screenshot of a computer AI-generated content may be
incorrect.](media/image5.png){width="6.5in"
height="2.7819444444444446in"}  
  
![A screenshot of a computer AI-generated content may be
incorrect.](media/image6.png){width="6.5in"
height="2.7847222222222223in"}

3\. Create an RDS Instance

![A screenshot of a computer AI-generated content may be
incorrect.](media/image7.png){width="6.5in"
height="2.8020833333333335in"}

4\. Create Database & Table in RDS instance:

a\. Database name: intel

b\. Table name: data

c\. Database password: intel123

![](media/image8.png){width="6.5in" height="3.3986111111111112in"}

![A screenshot of a computer AI-generated content may be
incorrect.](media/image9.png){width="6.5in"
height="3.3986111111111112in"}

5\. Using ELB hosted the webpage

![A screenshot of a computer AI-generated content may be
incorrect.](media/image10.png){width="6.5in"
height="3.3958333333333335in"}

6\. Modified the source code to see traffic is served by multiple server

![A screenshot of a computer AI-generated content may be
incorrect.](media/image11.png){width="6.5in"
height="3.217361111111111in"}

![A screenshot of a computer AI-generated content may be
incorrect.](media/image12.png){width="6.5in"
height="3.2256944444444446in"}
