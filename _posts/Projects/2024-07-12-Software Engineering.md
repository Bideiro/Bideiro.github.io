---
layout: post
title: "Product Management System: Ranil's Poulty Shop"
categories: [Projects]
tags: [Software Engineering, Python, MYSQL, PyQt-5]
---
## Quick Description
This project was completed during my 3rd year in college, I led development of an automated product management system for Ranil’s Poultry Shop to modernize and streamline its daily operations. The system replaces manual processes with automated sales handling, real-time inventory tracking, and secure data management, ensuring faster transactions and reduced human error. Built using Python for the application logic and interface, and MySQL for data storage, it follows the Incremental Model to support gradual improvements and feature expansion. Evaluated by both IT and non-IT professionals, the system was rated highly for its security, functionality, user-friendliness, and overall reliability. This solution significantly enhances operational efficiency and provides a scalable foundation for future business growth.

## Related Images & Videos

<!-- <iframe src="https://drive.google.com/file/d/1QZuXHH1fNfd915L1-qDlK0lhcQBPpd9O/preview" width="640" height="480" allow="autoplay"></iframe> -->
Shown below are some of the features of the created management system.

![Image 1](/assets/images/ranil/r-1.png){:.middle}
_Login Screen_

![Image 2](/assets/images/ranil/r-2.png){:.middle}
_Home Screen_

![Image 3](/assets/images/ranil/r-3.png){:.middle}
_User Selection/Information_

![Image 4](/assets/images/ranil/r-4.png){:.middle}
_Categories of available products_

![Image 5](/assets/images/ranil/r-5.png){:.middle}
_Order Screen_

![Image 6](/assets/images/ranil/r-6.png){:.middle}
_Confirmation of Order_

![Image 7](/assets/images/ranil/r-7.png){:.middle}
_Receipt_

![Image 8](/assets/images/ranil/r-8.png){:.middle}
_Stored Receipts/Records_

![Image 9](/assets/images/ranil/r-9.png){:.middle}
_Preview of Receipt_


> In Depth View: The following parts will contain parts or summaries of what we wrote in the actual paper. For the actual paper click here
{: .prompt-info }

## Introduction 

The poultry shop industry faces complex challenges in managing products, inventory, sales, and daily operations, making an efficient product management system essential. This project focuses on developing an automated product management system for Ranil’s Poultry Shop to streamline key processes such as POS transactions, inventory tracking, supplier and customer management, reporting, and product information management. Because poultry shops handle diverse and sensitive products, even small errors in sales, storage, or tracking can lead to financial losses and product waste. An automated system can improve accuracy, reduce manual workload, predict demand using sales data, prevent stockouts or overstocking, and enhance customer service through faster and more reliable operations. Additionally, computer-based systems offer benefits such as data standardization, reduced paperwork, cost savings, quick data access, and customization to meet business needs. This project also examines the challenges of the current manual system and highlights the importance of implementing a secure, efficient, and adaptable solution that can support long-term growth and improve the overall customer and business experience.

## System Architecture   

The User Interface is the component where users input data and receive displayed information. It features a user-friendly design built using CSS for styling and PyQt5 for creating graphical interface elements. Initial data validation occurs at this layer to ensure that inputs are correct before being sent to the server, providing immediate feedback to the user and reducing server load. The LAN Server serves as the middle layer that connects the user interface to the database. Developed using Python 3.12.3, it processes requests from the interface and returns appropriate responses. It performs an additional validation step to ensure data accuracy before any information is saved to or retrieved from the database, helping to catch errors that may have been missed during initial validation. The Database layer stores all essential information, using MySQL 8.4.0 to manage data related to products, transactions, inventory, and more. It ensures secure data storage, fast retrieval, and consistent data handling as requested by the server.

## Summary of the Study 

This project aims to improve the operations of Ranil’s Poultry Shop in Rodriguez, Rizal by implementing an automated product management system to replace its error-prone manual processes. The shop, founded by Arthur and Linda Tumali and currently managed by their daughter Rachel Manuel, faces challenges such as inaccurate sales tracking, inefficient inventory management, and issues with data security. The proposed system addresses these problems by providing automated sales processing, real-time inventory tracking, secure data storage, and reliable backups. Developed using the Incremental Model, the system was built in phases—requirements, design, testing, and implementation—to ensure continuous improvement and gradual feature expansion across multiple builds.

The system uses a multi-layered architecture consisting of a presentation tier, logic tier, and data tier, with Python 3.12.3 for the front end and MySQL 8.4.0 for the database. Evaluation through surveys completed by IT and non-IT professionals showed strong agreement that the system excels in security, functionality, user-friendliness, robustness, and maintainability. These positive results demonstrate the system’s technical and operational feasibility and confirm its potential to enhance business efficiency, reduce manual errors, improve customer satisfaction, and support long-term growth.