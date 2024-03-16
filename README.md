# Engineering Data Mesh in Azure Cloud

<a href="https://www.packtpub.com/product/engineering-data-mesh-in-azure-cloud/9781805120780"><img src="https://content.packt.com/B21084/cover_image_small.jpg" alt="no-image" height="256px" align="right"></a>

This is the code repository for [Engineering Data Mesh in Azure Cloud](https://www.packtpub.com/product/engineering-data-mesh-in-azure-cloud/9781805120780), published by Packt.

**Implement Data Mesh using Microsoft Azure's Well-Architected Framework**

## What is this book about?
This book will help you explore data mesh from theory to strategy, where you’ll implement this approach based on your analytics framework's maturity. You'll cover design, architecture, challenges, and common patterns for analytical workloads.

This book covers the following exciting features:
* Build a strategy for implementing a data mesh in Azure Cloud
* Plan your data mesh journey to build a collaborative analytics platform
* Address challenges in designing, building, and managing data contracts
* Get to grips with monitoring and governing a data mesh
* Understand how to build a self-service portal for analytics
* Design and implement a secure data mesh architecture
* Resolve practical challenges related to data mesh adoption

If you feel this book is for you, get your [copy](https://www.amazon.com/Engineering-Data-Mesh-Azure-Cloud-ebook/dp/B0CW18M6WC/ref=sr_1_1?dib=eyJ2IjoiMSJ9.UK0XzF1gjloZtqkk7IuAxnC16YkPKto2GrTcbX8Vm0JG38M9rRnSjurZ5jOrpuzPX0KkzmIAcw9gMW0C2G-Rvq8lDXbwDywjbcaQGj0ZSIDDTmqu6kjuguqJ7giid9ye.7gl8SkWfyv0U-GImv4m8vRJa0MNvxUtCWn8YaR4PPAg&dib_tag=se&keywords=Engineering+Data+Mesh+in+Azure+Cloud&qid=1710316579&sr=8-1) today!
<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>
## Instructions and Navigations
The GitHub repository functions as a valuable resource for future reference, enabling you to report any issues. Furthermore, the author can upload extra updates and examples to the repository, providing ongoing support.

The code will look like the following:
```
1# Grant access to individual user at a Subscription Level
2 function GrantAccessAtSubscription ($userID, $roleDef, $subScope) {
3 New-AzRoleAssignment -SignInName $userID `
4 -RoleDefinitionName $roleDef `
5 -Scope $subScope
6}
```

**Following is what you need for this book:**
This book is for chief data officers and data architects of large and medium-size organizations who are struggling to maintain silos of data and analytics projects. Data architects and data engineers looking to understand data mesh and how it can help their organizations democratize data and analytics will also benefit from this book. Prior knowledge of managing centralized analytical systems, as well as experience with building data lakes, data warehouses, data pipelines, data integrations, and transformations is needed to get the most out of this book.

With the following software and hardware list you can implement your learnings from the book (Chapter 1-17).
## Software and Hardware List
This book provides documentation references for all the Microsoft Azure services mentioned, but some working knowledge of Microsoft Azure will help you save time reading the docs.
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-17 | Microsoft Azure | NA |
| 1-17 | Great Expectations | Windows or Linux with Python 3.8 to 3.11 |
| 1-17 | Profisee | Deployed using Azure Marketplace |
| 1-17 | PowerShell, Azure Command Line Interface | Windows |
| 1-17 | Python 3.8 to 3.11 | Windows 11 or Ubuntu 22.04 |
| 1-17 | SQL Server Management Studio | Windows 10 or Windows 11 |


## Related products
* Azure Data and AI Architect Handbook [[Packt]](https://www.packtpub.com/product/azure-data-and-ai-architect-handbook/9781803234861) [[Amazon]](https://www.amazon.com/Azure-Data-Architect-Handbook-structured/dp/1803234865/ref=sr_1_1?crid=1BBXSR9SL2FYM&dib=eyJ2IjoiMSJ9.7D9z9wT_CGBxXQYncSz8YCIEtFpQ7LOZUy8xz789dtQpb9PzbLl5xrRm2OTwoQan.kmyMa9PMFyRFjuuhkSgoy18kMU0Rf9dE2_RgAlm7ltQ&dib_tag=se&keywords=Azure+Data+and+AI+Architect+Handbook&qid=1710592378&sprefix=azure+data+and+ai+architect+handbook%2Caps%2C718&sr=8-1)

* Practical Guide to Azure Cognitive Services [[Packt]](https://www.packtpub.com/product/practical-guide-to-azure-cognitive-services/9781801812917) [[Amazon]](https://www.amazon.com/Microsoft-Azure-Cognitive-Services-Accelerate/dp/1801812918/ref=sr_1_1?crid=1F213Z18K2TMS&dib=eyJ2IjoiMSJ9.fIy3uYGPDbwcwl-N32U5M14aEkuJbFL5BuV3LIaSLk3QUOyZcXkbckxF2eu649cVIaZlUGbKXV9MpjrwF2_9Y_qW_nJ3SG99vgYueNEUz1I.Nv5TIVHcVv3XWIZw8rRQdbI67lVzh7htbu5zRq_5yYE&dib_tag=se&keywords=Practical+Guide+to+Azure+Cognitive+Services&qid=1710592511&sprefix=practical+guide+to+azure+cognitive+services%2Caps%2C602&sr=8-1)

## Get to Know the Author
**Aniruddha Deswandikar**
holds a Bachelor&rsquo;s degree in Computer Engineering and is a seasoned Solutions Architect with over 30 years of industry experience as a developer, architect and technology strategist. His experience spans from start-ups to dotcoms to large enterprises. He has spent 18 years at Microsoft helping Microsoft customers build their next generation Applications and Data Analytics platforms. His experience across Application, Data and AI has helped him provide holistic guidance to companies large and small. Currently he is helping global enterprises set up their Enterprise-scale Analytical system using the Data Mesh Architecture. He is a Subject Matter Expert on Data Mesh in Microsoft and is currently helping multiple Microsoft Global Customers implement the Data Mesh architecture.

