---
title: "Getting Started with R"
author:    
    -  "RSN_Thinklabz_Chennai"

output:
  html_document:
    keep_md: true
    
---








![ Get inspired](https://user-images.githubusercontent.com/92445009/145365296-540f23e2-4344-4e46-9e82-ace0532325c2.jpg)


# Preamble 
R is a powerful statistical programming language that is built to work well with large and diverse datasets.   
This notes aims at giving readers a routemap to get started with programming language R and its IDE (Integrated Development Environment) RStudio. We are going to look at how to download, install and understand the basic components of R and RStudio.
 
 
## Downloading And installing R
R software can be downloaded from website  https://cran.r-project.org/
   
The website looks like this. 

![ **Cran website**](https://user-images.githubusercontent.com/92445009/145388643-071f666c-7aae-4cf9-b817-09ae6ee17e31.png)

 
   
From this we can  choose the option whether we wish to download for Windows or Mac or Linux OS

*The following page is for Windows*

 ![ **Windows**](https://user-images.githubusercontent.com/92445009/145388743-5b42f731-9265-4536-b23c-1d615a4403e7.png)
   
   
*The following page is for Mac* 

 ![ **mac** ](https://user-images.githubusercontent.com/92445009/145391417-14caaf88-36c5-4471-9f99-a129fe4d5a66.png)
    
        
*The following page is for Linux*  

 ![ **LINUX** ](https://user-images.githubusercontent.com/92445009/145391522-06d008b5-3f12-4274-8570-58e9b00c70c3.png)
    
    
Once downloaded R can be installed by clicking the file which is downloaded and by following the instructions. After installing the Software we can see the welcome page as shown below

![ **WELCOME** ](https://user-images.githubusercontent.com/92445009/145391708-fac5a951-2e99-4993-97ad-8ff4ab9ae795.png)
    
Since we have done installing R we can move forward with RStudio

## Downloading and installing RStudio

RStudio web page URL is https://www.rstudio.com/products/rstudio/ 


![ ](https://user-images.githubusercontent.com/92445009/145392064-c99cdbd5-25af-4363-84a2-0216c1bf1b12.png)

**Version available**


![Version1](https://user-images.githubusercontent.com/92445009/145392153-3597f731-63e3-4954-b3f0-2289570f386e.png)
**based on OS choose the file to download**


![Version2](https://user-images.githubusercontent.com/92445009/145392168-647eefd9-3a05-45c0-bfd3-20457965d444.png)

**Installing**

![Install](https://user-images.githubusercontent.com/92445009/145392632-8b8ff514-5cdc-437a-b4da-d69267fa8b3a.png)

### Components of RStudio   
RStudio is divided into 4 Panes

![Components](https://user-images.githubusercontent.com/92445009/145394433-15934add-45da-4ecc-943b-447eab45b00b.png)
Description of these components


![Co D](https://user-images.githubusercontent.com/92445009/145394526-da06d306-5ef7-432d-b236-ae766fb7021b.png)


### Menu bar
Menu bar consists of various actions which can be performed, Let us see some of most used options
   
   1)File
   used to create various Documents such as R Script, R Markdown, R Shiny etc
   
![File](https://user-images.githubusercontent.com/92445009/145394588-fccb20c2-6837-4e06-8b33-2657b70fb844.png)
   
   2)Edit
   Consists of various editing options


![edit](https://user-images.githubusercontent.com/92445009/145394646-816031bb-8ba6-40d9-a0d1-b72c5a2308d5.png)


   3)View
   Used to customise look and feel


![view](https://user-images.githubusercontent.com/92445009/145394712-e9bc4a08-f2f9-4a1d-9f9d-7fbf148a70a4.png)   
   4)Tools    
   Tools provide various useful options of tasks which can be performed.   

![tools](https://user-images.githubusercontent.com/92445009/145395126-0bcf9185-26e8-4814-a4da-544fc3477f3e.png)   
   Global options is an important tool which we will be interested in, we can change theme, default settings like saving workspace image(history of commands performed ) etc can be changed 
   

![global_op](https://user-images.githubusercontent.com/92445009/145395215-9cace1ed-c509-43de-8978-adc2df6c4487.png)

### Console Pane (Bottom Left)
Console is the place where R codes are executed 

![console](https://user-images.githubusercontent.com/92445009/145395281-0ce79d99-489f-45d1-b273-1a4a836664c9.png)



### Environment and History (Top Right)

The values and data we load in R is stored in Environment

 
![Environment](https://user-images.githubusercontent.com/92445009/145396975-69ebf050-66d4-4435-983e-5184ab15984d.png)

We can see previously executed commands using history section
 
![history](https://user-images.githubusercontent.com/92445009/145397682-ce065505-3a4b-41c6-a434-ae17031998db.png)

**Importing dataset**

 
![Excel_i](https://user-images.githubusercontent.com/92445009/145397729-e36cfddf-6846-4675-95c9-7e7fbdc64f90.png)
**Importing an Excel file**


![Excel_i2](https://user-images.githubusercontent.com/92445009/145397780-02f88134-63de-41db-887c-4e2bf6bd82ba.png)


Using code
![excel2](https://user-images.githubusercontent.com/92445009/145397814-d7cee39d-999c-477d-ad0c-bed231744076.png)



### Help and Packages (Bottom Right) 

**Help** Section is used to know more about function, dataset, package

![help](https://user-images.githubusercontent.com/92445009/145397972-3ccea0d7-0730-4e84-9ba8-ff149c6c2ecd.png)

**Package** section aids us in accessing packages in R (To know more about packages please refer http://rpubs.com/Thinklabz/Intro_to_R_packages )


![Install1](https://user-images.githubusercontent.com/92445009/145398071-6a5ab533-bad5-471d-a521-61c10a9a356a.png)

To install a package using RStudio we can search the package's name here


![search](https://user-images.githubusercontent.com/92445009/145398172-11aa13f5-2029-45aa-9b8b-e0a5f583bb3a.png)


![p_install](https://user-images.githubusercontent.com/92445009/145398231-cc3d1532-fc49-42fc-a394-d7dcfdfed226.png)
 
![p_down](https://user-images.githubusercontent.com/92445009/145398358-8a5eec85-0bf2-46a0-abb9-92202ab3e751.png)

 
![p_view](https://user-images.githubusercontent.com/92445009/145398296-15098ce2-d995-4bef-956f-25d9cb56da29.png)
**Loading package**

![load_p](https://user-images.githubusercontent.com/92445009/145398431-b9053ebb-1080-4a18-9a52-70196d6b065e.png)



### Source (Top Left)
Source is the place where we have various files which we can work with R. We can edit source files and run it either line by line or full document also.  
**Using R Script for writing code**


![script](https://user-images.githubusercontent.com/92445009/145398488-df85d06b-c522-46a1-9646-594f4b90c99c.png)

# Final Note
This notes has given an introduction to R and RStudio. Feel free to reach out for queries.


