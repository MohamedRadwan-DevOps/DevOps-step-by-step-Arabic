
# Advanced Introduction to DevOps

## Course Demos/Labs (83 Demos/Labs)
  - [Module 1: Introduction to Agile and DevOps](#module-1-introduction-to-agile-and-devops)
    - [No Demos](#no-demos)
  - [Module 2: Application Development Lifecycle in Action](#module-2-application-development-lifecycle-in-action)
    - [Demo 1: Examine SRS vs. Well-structured Backlog items (Epic, Features, PBIs).](#demo-1-examine-srs-vs-well-structured-backlog-items-epic-features-pbis)
    - [Demo 2: Create and examine Windows 11 VM (created) from gallery.](#demo-2-create-and-examine-windows-11-vm-created-from-gallery)
    - [Demo 3: Create and examine Ubuntu 20.04 VM (created) from gallery.](#demo-3-create-and-examine-ubuntu-2004-vm-created-from-gallery)
    - [Demo 4: Create and examine Ubuntu 18.04 VM (created) from gallery.](#demo-4-create-and-examine-ubuntu-1804-vm-created-from-gallery)
    - [Demo 5: Create Windows 10 from ISO file.](#demo-5-create-windows-10-from-iso-file)
    - [Demo 6: Create a Console App for calc (Average, Largest, Smallest).](#demo-6-create-a-console-app-for-calc-average-largest-smallest)
    - [Demo 7: Create a Desktop App for calc (Average, Largest, Smallest).](#demo-7-create-a-desktop-app-for-calc-average-largest-smallest)
    - [Demo 8: Create an API App for calc (Average, Largest, Smallest).](#demo-8-create-an-api-app-for-calc-average-largest-smallest)
    - [Demo 9: Create a Class Library for Calc (Average, Largest, Smallest)- amend the console app to use it.](#demo-9-create-a-class-library-for-calc-average-largest-smallest--amend-the-console-app-to-use-it)
    - [Demo 10: Amend the API App to use the Class Library.](#demo-10-amend-the-api-app-to-use-the-class-library)
    - [Demo 11: Amend the Console App to use the API.](#demo-11-amend-the-console-app-to-use-the-api)
    - [Demo 12: Amend the Desktop App to use the API.](#demo-12-amend-the-desktop-app-to-use-the-api)
    - [Demo 13: Create another API that consumes the 1st API.](#demo-13-create-another-api-that-consumes-the-1st-api)
    - [Demo 14: Examine Several API requests and well form the JSON return.](#demo-14-examine-several-api-requests-and-well-form-the-json-return)
    - [Demo 15: Package API and Deploy it to local IIS and expose to public.](#demo-15-package-api-and-deploy-it-to-local-iis-and-expose-to-public)
    - [Demo 16: Intro to nuget package management.](#demo-16-intro-to-nuget-package-management)
    - [Demo 17: Package the class library and publish it to nuget package.](#demo-17-package-the-class-library-and-publish-it-to-nuget-package)
    - [Demo 18: Replace the class library in the API with the nuget package library.](#demo-18-replace-the-class-library-in-the-api-with-the-nuget-package-library)
    - [Demo 19: Create Unit test for the class library.](#demo-19-create-unit-test-for-the-class-library)
    - [Demo 20: Explain and examine code coverage, code metrics.](#demo-20-explain-and-examine-code-coverage-code-metrics)
    - [Demo 21: Configure unit test run-settings to generate test results and code coverage.](#demo-21-configure-unit-test-run-settings-to-generate-test-results-and-code-coverage)
    - [Demo 22: Examine a UI test and run it.](#demo-22-examine-a-ui-test-and-run-it)
  - [Module 3: Introduction to Cloud](#module-3-introduction-to-cloud)
    - [Demo 1: Create an Azure Subscription Free account.](#demo-1-create-an-azure-subscription-free-account)
    - [Demo 2: Create Ubuntu on Azure and connect to it using SSH and remote desktop.](#demo-2-create-ubuntu-on-azure-and-connect-to-it-using-ssh-and-remote-desktop)
    - [Demo 3: Exploring cloud flexibility and scalability by adding/removing resources to VM .](#demo-3-exploring-cloud-flexibility-and-scalability-by-addingremoving-resources-to-vm-)
    - [Demo 4: Create Windows 10 VM on Azure and enable IIS, install .NET core runtime, expose port 80 and deploy the API app.](#demo-4-create-windows-10-vm-on-azure-and-enable-iis-install-net-core-runtime-expose-port-80-and-deploy-the-api-app)
    - [Demo 5: Create a Web App on Azure and deploy the API using FTP.](#demo-5-create-a-web-app-on-azure-and-deploy-the-api-using-ftp)
    - [Demo 6: Examine SaaS products like office-365.](#demo-6-examine-saas-products-like-office-365)
  - [Module 4: Tooling for DevOps](#module-4-tooling-for-devops)
    - [Demo 1: Examine Azure DevOps docs, create org and examine all services.](#demo-1-examine-azure-devops-docs-create-org-and-examine-all-services)
    - [Demo 2: Using Azure DevOps API to create items through Postman and Azure DevOps CLI.](#demo-2-using-azure-devops-api-to-create-items-through-postman-and-azure-devops-cli)
    - [Demo 3: Use Demo generator to generate several projects and examine them.](#demo-3-use-demo-generator-to-generate-several-projects-and-examine-them)
  - [Module 5: Evolution of Computing Options](#module-5-evolution-of-computing-options)
    - [Demo 1: Install-uninstall Docker on Ubuntu on HV and create some containers.](#demo-1-install-uninstall-docker-on-ubuntu-on-hv-and-create-some-containers)
    - [Demo 2: Run a .NET core app container from GitHub on Ubuntu.](#demo-2-run-a-net-core-app-container-from-github-on-ubuntu)
  - [Module 6: Managing Version Control](#module-6-managing-version-control)
    - [Demo 1: Examine a History of repo on GitHub.](#demo-1-examine-a-history-of-repo-on-github)
    - [Demo 2: Install Git on Windows and Ubuntu.](#demo-2-install-git-on-windows-and-ubuntu)
    - [Demo 3: Hand-typed text files Vs. Generated text files.](#demo-3-hand-typed-text-files-vs-generated-text-files)
    - [Demo 4: Use git as a local repo (config, init, commit, etc).](#demo-4-use-git-as-a-local-repo-config-init-commit-etc)
    - [Demo 5: Use git as a remote repo from the local one (clone, pull, push, etc) Azure Repo.](#demo-5-use-git-as-a-remote-repo-from-the-local-one-clone-pull-push-etc-azure-repo)
    - [Demo 6: Use git remote repo with GitHub.](#demo-6-use-git-remote-repo-with-github)
    - [Demo 7: Work with git using IDE (Visual Studio) to interact with Azure Repo and GitH.](#demo-7-work-with-git-using-ide-visual-studio-to-interact-with-azure-repo-and-gith)
    - [Demo 8: Work with git using IDE (VS Code) to interact with Azure Repo.](#demo-8-work-with-git-using-ide-vs-code-to-interact-with-azure-repo)
  - [Module 7: Defining and Implementing Continuous Integration (CI)](#module-7-defining-and-implementing-continuous-integration-ci)
    - [Demo 1: Create and configure Continuous Integration (CI) pipeline for a .NET class library.](#demo-1-create-and-configure-continuous-integration-ci-pipeline-for-a-net-class-library)
    - [Demo 2: Create and configure Continuous Integration (CI) pipeline for API.](#demo-2-create-and-configure-continuous-integration-ci-pipeline-for-api)
    - [Demo 3: Build hosted agent vs self-hosted agent and run self-hosted to examine build folder.](#demo-3-build-hosted-agent-vs-self-hosted-agent-and-run-self-hosted-to-examine-build-folder)
    - [Demo 4: Use YAML over classic Continuous Integration (CI).](#demo-4-use-yaml-over-classic-continuous-integration-ci)
    - [Demo 5: Create and configure Continuous Integration (CI) for .NET core app on docker image.](#demo-5-create-and-configure-continuous-integration-ci-for-net-core-app-on-docker-image)
    - [Demo 6: Create and configure Continuous Integration (CI) for PartsUnlimited App.](#demo-6-create-and-configure-continuous-integration-ci-for-partsunlimited-app)
  - [Module 8: Designing a Dependency Management Strategy](#module-8-designing-a-dependency-management-strategy)
    - [Demo 1: Create and examine feed on Azure artifact with different options.](#demo-1-create-and-examine-feed-on-azure-artifact-with-different-options)
    - [Demo 2: Package and publish the class library to NuGet.](#demo-2-package-and-publish-the-class-library-to-nuget)
    - [Demo 3: Use feed views to share packages.](#demo-3-use-feed-views-to-share-packages)
    - [Demo 4: Package and publish class library to Azure Artifact feed and use it from Visual Studio.](#demo-4-package-and-publish-class-library-to-azure-artifact-feed-and-use-it-from-visual-studio)
    - [Demo 5: Package and publish the API App to Azure Pipeline Artifact.](#demo-5-package-and-publish-the-api-app-to-azure-pipeline-artifact)
    - [Demo 6: Package and publish PartsUnlimited App to Azure Pipeline Artifact.](#demo-6-package-and-publish-partsunlimited-app-to-azure-pipeline-artifact)
    - [Demo 7: Package and publish a .NET Docker image to Docker Hub.](#demo-7-package-and-publish-a-net-docker-image-to-docker-hub)
  - [Module 9: Defining and Implementing a Continuous Delivery & Release Strategy](#module-9-defining-and-implementing-a-continuous-delivery--release-strategy)
    - [Demo 1: Create a CD for API.](#demo-1-create-a-cd-for-api)
    - [Demo 2: Create a CD for Parts-Unlimited.](#demo-2-create-a-cd-for-parts-unlimited)
    - [Demo 3: Configure Azure Pipeline as a process for self-hosted and run UI tests.](#demo-3-configure-azure-pipeline-as-a-process-for-self-hosted-and-run-ui-tests)
    - [Demo 4: Deploy docker image to Azure Container App Service.](#demo-4-deploy-docker-image-to-azure-container-app-service)
    - [Demo 5: Enable Continuous Integration and Continuous Deployment.](#demo-5-enable-continuous-integration-and-continuous-deployment)
  - [Module 10: Managing Configuration Management for Infrastructure and Database](#module-10-managing-configuration-management-for-infrastructure-and-database)
    - [Demo 1: Provision infrastructure (Web App and Azure SQL on Azure) using ARM and Azure Pipeline.](#demo-1-provision-infrastructure-web-app-and-azure-sql-on-azure-using-arm-and-azure-pipeline)
    - [Demo 2: Provision infrastructure (Web App on Azure) using Terraform and Azure Pipeline.](#demo-2-provision-infrastructure-web-app-on-azure-using-terraform-and-azure-pipeline)
    - [Demo 3: Install and Configure Liquibase on Azure pipeline self-hosted agent.](#demo-3-install-and-configure-liquibase-on-azure-pipeline-self-hosted-agent)
    - [Demo 4: Using Liquibase for DB configuration management with H2 DB.](#demo-4-using-liquibase-for-db-configuration-management-with-h2-db)
    - [Demo 5: Deploy DB changes to Snowflake using Liquibase and Azure Pipeline.](#demo-5-deploy-db-changes-to-snowflake-using-liquibase-and-azure-pipeline)
    - [Demo 6: End-to-End CI-CD to Deploy Infrastructure and Web application.  (Free session)](#demo-6-end-to-end-ci-cd-to-deploy-infrastructure-and-web-application--free-session)
  - [Module 11: Team Collaboration and Work Tracking](#module-11-team-collaboration-and-work-tracking)
    - [Demo 1: Structure People Dimension in Portfolio Management.](#demo-1-structure-people-dimension-in-portfolio-management)
    - [Demo 2: Structure Time Dimension in Portfolio Management.](#demo-2-structure-time-dimension-in-portfolio-management)
    - [Demo 3: Structure Business Dimension in Portfolio Management.](#demo-3-structure-business-dimension-in-portfolio-management)
    - [Demo 4: Assigning Who Do what and when in Portfolio Management.](#demo-4-assigning-who-do-what-and-when-in-portfolio-management)
    - [Demo 5: Agile Planning and Portfolio Management with Azure Boards.](#demo-5-agile-planning-and-portfolio-management-with-azure-boards)
    - [Demo 6: Plan work using Azure Boards.](#demo-6-plan-work-using-azure-boards)
    - [Demo 7: Manage Agile software delivery plans across teams.](#demo-7-manage-agile-software-delivery-plans-across-teams)
  - [Module 12: Examples Of Different Practices Improvement in Several Areas](#module-12-examples-of-different-practices-improvement-in-several-areas)
  - [**Module 13: Overview of SRE and Monitoring Practices](#module-13-overview-of-sre-and-monitoring-practices)
    - [Demo 1: Create a monitoring dashboards of Log Analytics data.](#demo-1-create-a-monitoring-dashboards-of-log-analytics-data)
    - [Demo 2:  Create and use Log Analytics workspace.](#demo-2--create-and-use-log-analytics-workspace)
    - [Demo 3: Create, view, and manage metric alerts.](#demo-3-create-view-and-manage-metric-alerts)
  - [Module 14: Digital Transformation and DevOps](#module-14-digital-transformation-and-devops)
  - [**Module 15: Analyzing The Current Maturity of DevOps and Applying the Transformation](#module-15-analyzing-the-current-maturity-of-devops-and-applying-the-transformation)
  - [**Module 16: Applying Quality and Security for DevOps](#module-16-applying-quality-and-security-for-devops)
    - [Demo 1: Run Static Application Security Testing (SAST) using Azure Pipeline.](#demo-1-run-static-application-security-testing-sast-using-azure-pipeline)
  - [Module 17: Version Control in More Details](#module-17-version-control-in-more-details)
    - [Demo 1: Use git branch and merge.](#demo-1-use-git-branch-and-merge)
    - [Demo 2: Use git PR with Azure Repo and GitHub.](#demo-2-use-git-pr-with-azure-repo-and-github)
    - [Demo 3: Create fork with GitHub and use PR.](#demo-3-create-fork-with-github-and-use-pr)
  - [Module 18: Docker in More Details](#module-18-docker-in-more-details)
    - [Demo 1: Working with Docker in more details on Linux.](#demo-1-working-with-docker-in-more-details-on-linux)
    - [Demo 2: Working with Docker on Windows.](#demo-2-working-with-docker-on-windows)
    - [Demo 3: More about Docker and how to use Docker compose.](#demo-3-more-about-docker-and-how-to-use-docker-compose)
  - [Module 19: Mentoring, CV and Interpersonal Skills](#module-19-mentoring-cv-and-interpersonal-skills)
    - [Demo 1: Examine more than 10 real professional CVs that passed the screening and they have been accepted.](#demo-1-examine-more-than-10-real-professional-cvs-that-passed-the-screening-and-they-have-been-accepted)

##  Module 1: Introduction to Agile and DevOps 

 ### No Demos

## Module 2: Application Development Lifecycle in Action 

 ### Demo 1: Examine SRS vs. Well-structured Backlog items (Epic, Features, PBIs). 
 
  In this demo, you will learn and understand the difference between classic and modern requirements engineering processes and tools.

  Also, you will learn how to capture the requirements in classic software engineering using SRS (Software Requirements Specification), how the SRS document includes all details of the requirements like Actors, Use Case diagram, domain model, Sequence diagram, and Activity diagram.

  Also, you will learn how to capture the requirements in modern software engineering using Azure DevOps Product Backlog, and how the requirements can be organized into Themes, Epics, Features, and the Product Backlog Items (PBIs).

  Also, you will understand how to write the acceptance criteria, and how to divide it into functional, usability, and data criteria for the PBI, how to set the priority, estimated and actual effort, and the expected time (Iteration) for delivering this PBI.
    
 
  ### Demo 2: Create and examine Windows 11 VM (created) from gallery. 
 
  In this demo, you will learn and understand how to enable virtualization to your processor, and enable windows to feature Hyper-V to configure your machine to work with virtual machines (VMs).

  Also, you will learn how to create Windows 11 VM from gallery on the cloud using Windows 11 image, and how to connect, start, sign in to to the created VM, and start exploring it.

  Also, you will explore the VM settings, and learn how to configure them (Memory, Hard Disk, CPU, etc). After that, you will learn how to create multiple checkpoints, and learn how every checkpoint includes only the diff/ delta between the current and the previous version of the hard disk, how to apply one of the created checkpoints and revert the previous version, also how to delete, export the checkpoint, and how to create a virtual switch so that you can communicate over the internet. 


 ### Demo 3: Create and examine Ubuntu 20.04 VM (created) from gallery. 
 
  In this demo, you will learn and understand how to create Ubuntu 20.04 VM from gallery on the cloud using Ubuntu 20.04 image.

  Also, you will learn and examine how to set the machine configuration (language, keyboard layout, location, user name, password, etc), how to apply your configuration changes and login to the created VM using the set username and password. After that, you can start exploring your VM, do your work and finally how to shut it down.


 ### Demo 4: Create and examine Ubuntu 18.04 VM (created) from gallery. 
 
  In this demo, you will learn and understand how to create Ubuntu 18.04 VM from gallery on the cloud using Ubuntu 18.04 image.

  Also, you will learn and examine how to set the machine configuration (language, keyboard layout, location, user name, password, etc), how to apply your configuration changes and login to the created VM using the set username and password. After that, you can connect and start exploring your VM, do your work and finally how to shut it down.
    

 ### Demo 5: Create Windows 10 from ISO file. 
 
  In this demo, you will learn and understand how to create an empty VM, apply all its configurations, how to assign its memory either dynamic or static, configure networking and virtual switch, connect to Virtual Hard Disk (VHD) and set its size.

  Also, you will learn how to start your configured machine, insert an ISO file to install Windows 10, configure your installed Windows, explore it and finally shut down your machine.


 ### Demo 6: Create a Console App for calc (Average, Largest, Smallest). 
 
  In this demo you will learn and understand how to download and install Visual Studio 2019, open VS, create a new Console Application project, configure your new project, choose your target Framework, and ensure that your app is running fine.

  How to add a new class to write your app business logic and write the code for the Average, largest, and Smallest methods.

  Average to calculate the average of an array of numbers, 
  Smallest to calculate the smallest number of an array of numbers, 
  Largest to calculate the largest number of an array of numbers.

  Also, you will learn how to use your created class and create an object from it, call its three methods, run your app and make sure it is working as expected, and finally how to distribute and publish your app, explore your published folder and run the .exe file to make sure everything works as expected.
    

 ### Demo 7: Create a Desktop App for calc (Average, Largest, Smallest). 
 
  In this demo, you will learn and understand how to create a new Desktop Application project, configure your new project, and how create a button, and a textbox and configure them.

  How to add a new class to write your app business logic and write the code for the Average, largest, and Smallest methods (same as the business logic of the console app of [demo 6](https://github.com/MohamedRadwan-DevOps/devops-step-by-step/blob/main/source/devops-course-demos-labs.md#demo-6-create-a-console-app-for-calc-average-largest-smallest) ).

  Also, you will learn how to use your created class and create an object from it, call its three methods, run your app and make sure it is working as expected, and finally how to distribute and publish your app, explore your published folder, setup and install your published app and make sure it is working as expected.
    

 ### Demo 8: Create an API App for calc (Average, Largest, Smallest). 
 
  In this demo, you will learn and understand how to create a new API App project, configure it, create a new controller, and write the business logic of the calc app (Average, Smallest, Largest) inside it.

  Also, you will learn how to build your app, configure your launch settings, run your app on IIS Express (built-in web server on VS), call all APIs with different numbers to make sure all working as expected, and finally publish your created API App and explore the published folder.
    

 ### Demo 9: Create a Class Library for Calc (Average, Largest, Smallest)- amend the console app to use it. 
 
  In this demo, you will learn and understand how to create a new Class Library project, configure it, add new class, and write the business logic of the calc app (Average, Smallest, Largest) inside it.

  Also, you will learn how to build your app, explore the build folder and examine the DLL file.

  How to replace the business logic inside your [Console App](https://github.com/MohamedRadwan-DevOps/devops-step-by-step/blob/main/source/devops-course-demos-labs.md#demo-6-create-a-console-app-for-calc-average-largest-smallest) with using the DLL of the Class Library, and make sure it is working as expected.


 ### Demo 10: Amend the API App to use the Class Library. 
 
  In this demo, you will learn and understand how to use the Class Library to separate the logic from the app and understand how DLLs can make your code flexible and efficient.

  Also, you will learn how to add the DLL file to your created [API App](https://github.com/MohamedRadwan-DevOps/devops-step-by-step/blob/main/source/devops-course-demos-labs.md#demo-8-create-an-api-app-for-calc-average-largest-smallest), and a reference to it, and replace the business logic code inside by the added Class Library, build and run your app and make sure it is working as expected.
    

 ### Demo 11: Amend the Console App to use the API. 
 
  In this demo, you will learn and understand how to replace the Class Library inside your created Console App by calling the APIs of the [API App](https://github.com/MohamedRadwan-DevOps/devops-step-by-step/blob/main/source/devops-course-demos-labs.md#demo-8-create-an-api-app-for-calc-average-largest-smallest), using them, build and run your app to make sure it is working as expected.
    

 ### Demo 12: Amend the Desktop App to use the API. 
 
  In this demo, you will learn and understand how to replace the business logic inside  your created [Desktop App](https://github.com/MohamedRadwan-DevOps/devops-step-by-step/blob/main/source/devops-course-demos-labs.md#demo-7-create-a-desktop-app-for-calc-average-largest-smallest) by calling the APIs of the [API App](https://github.com/MohamedRadwan-DevOps/devops-step-by-step/blob/main/source/devops-course-demos-labs.md#demo-8-create-an-api-app-for-calc-average-largest-smallest) and using them, build and run your app to make sure it is working as expected

 ### Demo 13: Create another API that consumes the 1st API. 
 
  In this demo, you will learn how to Create a 2nd API app and understand how to call the 1st API from the 2nd API. 

  Also, you will learn how Modern Software Architecture can make improve your code by introducing modularization versus old monolithic applications. 
    

 ### Demo 14: Examine Several API requests and well form the JSON return. 
 
  In this demo, you will learn and understand how to make and examine several public APIs, and format the APIs results to JSON format.
  
  Also, you will learn how to make a Get API request to retrieve all projects in your Azure DevOps organization, and also a Post API request to create a project, item, etc.
    

 ### Demo 15: Package API and Deploy it to local IIS and expose to public. 
 
  In this demo, you will learn and understand how to package the API app, turn on the Windows feature Internet Information Service (IIS), and how download ASP.NET core runtime and Windows Server Hosting (Windows Hosting Bundle) to make the IIS web server understand the API App, and how to deploy your API package to the local IIS web server, and finally call all API methods (Average, Smallest, and Largest) and make sure it's working as expected.
  
  Also, you will learn how to expose port 800 (port forward), so that your local machine becomes a web server and is accessible to the public.


 ### Demo 16: Intro to NuGet package management. 
 
  In this demo, you will learn more about the public package management NuGet, which is the package manager for .NET. The NuGet client tools provide the ability to produce and consume packages. The NuGet Gallery is the central package repository used by all package authors and consumers.

  Explore Nuget packages list, how to search for any package by its name or author, its download numbers, its author's profile, explore its commands to install it, reference to it, etc.

  Also, you will learn how to open package management inside Visual Studio (client for NuGet package), browse packages, and install/uninstall any package you want.


 ### Demo 17: Package the class library and publish it to nuget package. 
 
  In this demo, you will learn and understand a mechanism through which developers can create, share, and consume useful code.
  
  How the code is bundled into "packages" that contain compiled code (as DLLs) along with other content needed in the projects that consume these packages.

  Also, you will learn how to create an account on the Nuget, sign in, generate an API key to use to push the Class Library to NuGet, and finally push it.


 ### Demo 18: Replace the class library in the API with the nuget package library. 
 
  In this demo, you will learn and understand the difference between Modern Software Architecture and Classic Software Architecture, and how to remove the class library that contained the logic in the API app and replace it with the package that was published to NuGet package management.

  How to search for your published package from VS, install it, build and run your app and make sure everything works as expected.
  
  Also, you will learn how is important to restore the packages before building your app if they were deleted as the app is using the deleted DLL and there is a dependency on it.


 ### Demo 19: Create Unit test for the class library. 
 
  In this demo you will learn and understand how to add and perform Unit Testing on the Calc Class library to know if the business logic for the Class library working properly or not, you will learn the triple A (Arrange, Act, Assert) method to measure the code coverage and to know if the business logic is returning the targeted values.
  
  Also, you will learn the difference between the Static Analysis and Dynamic Analysis and know the components of Unit test and how to create it.


 ### Demo 20: Explain and examine code coverage, code metrics. 
 
   In this demo you will learn and understand how to calculate code coverage and code metrics for the three methods (Average, Largest, Smallest) in the Calc Class Library App.

   Also, you will learn the different quality metrics, what is Cyclomatic Complexity, Maintainability Index metric, Depth of Inheritance metric, Class Coupling metric, Lines of Source code metric, and how can we use them to measure the quality of code.


 ### Demo 21: Configure unit test run-settings to generate test results and code coverage. 
 
  In this demo, you will learn and understand how to configure Unit tests in Visual Studio by using a .runsettings file, and how to configure your project run settings to the added .runsettings file.

  Also, you will learn and explore that after adding the .runsettings file the TestResults folder will contain the TestResult file (trx) which contains the details about the run test like the result summary, and an HTML file which includes the test run details.

 ### Demo 22: Examine a UI test and run it. 
 
  In this demo, you will learn and understand the concept of UI Testing and how to run it on a specific project.
  
  Also, you will learn how to control the sleep threading for each UI test and use the NuGet package management to update any package required to run a UI test like Selenium.Webdriver.ChromeDriver in our example.



##  Module 3: Introduction to Cloud 

 ### Demo 1: Create an Azure Subscription Free account. 
 
  In this demo you will learn and understand the steps to setting up a free Azure account.
  
  Also, you will learn the different cloud deployments available within major cloud providers like (IaaS,PaaS,SaaS,FaaS),and the different cloud offerings like (storage & compute).


 ### Demo 2: Create Ubuntu on Azure and connect to it using SSH and remote desktop. 
 
  In this demo you will learn and understand how to create and use secure shell (SSH) keys to connect to Linux virtual machine (VM) in Azure.
  
  Also, you will learn how to generate and store SSH keys in the Azure portal to use when creating VMs in the portal as well as configuring a desktop environment and remote desktop for your Linux VM running Ubuntu.


 ### Demo 3: Exploring cloud flexibility and scalability by adding/removing resources to VM . 
 
  In this demo you will learn the different sizes available for virtual machines (VMs) and how quick it is to deploy a VM and understand how to change the required computation power based on your needs (scale-up vs scale-out).
  
  Also, you will learn how enterprises used to managed their on-premise infrastructure vs cloud managed infrastructure. 


 ### Demo 4: Create Windows 10 VM on Azure and enable IIS, install .NET core runtime, expose port 80 and deploy the API app. 
 
  In this demo you will learn and understand how create a Windows 10 VM using Readily available image repository, how to enable IIS (windows webserver) from windows features, and how to install a .NET core runtime from the web.
  
  Also, you will learn how to port forward and expose port 80 to allow traffic to reach your API app, which you will deploy on IIS. 


 ### Demo 5: Create a Web App on Azure and deploy the API using FTP. 
 
  In this demo you will learn and understand how to deploy a Web App resource on Azure and add it to a resource group.
  
  Also, you will learn how to deploy the API to the Web App service using FTP (File Transfer Protocol). 


 ### Demo 6: Examine SaaS products like office-365. 
 
  In this demo you will learn and understand how SaaS products (like office-365) differ from other type of cloud offerings.
  
  Also, you will learn how SaaS is considered a consumerism service compared to PaaS and IaaS, where you don't manage anything but your own data.



##  Module 4: Tooling for DevOps 

 ### Demo 1: Examine Azure DevOps docs, create org and examine all services. 
 
  In this demo you will learn and understand how to create an Azure DevOps account, how to create your first organization, and a look at Azure DevOps available docs.
  
  Also, you will learn about the available services and features that Azure DevOps provide over other CI/CD platforms.


 ### Demo 2: Using Azure DevOps API to create items through Postman and Azure DevOps CLI. 
 
  In this demo you will learn and understand how install Postman and create items through it, how to install Azure DevOps CLI and create items through it.
  
  Also, you will learn how creating items through Postman and Azure DevOps CLI differ from one another. 


 ### Demo 3: Use Demo generator to generate several projects and examine them. 
 
  In this demo you will learn and understand how generate Demo projects in Azure DevOps, that contain items in different stages.
  
  Also, you will learn how to process certain items in different stages and how monitoring Azure DevOps makes it easier to manage your pipelines.



##  Module 5: Evolution of Computing Options 

 ### Demo 1: Install-uninstall Docker on Ubuntu on HV and create some containers. 
 
  In this demo you will learn and understand the steps to install Docker container on an Ubuntu OS on HyperV and create some containers.
  
  Also, you will learn how to uninstall the installed container.


 ### Demo 2: Run a .NET core app container from GitHub on Ubuntu. 
 
  In this demo you will learn and understand how to run a .NET core app container on Ubuntu OS from GitHub.
  
  Also, you will learn how to gather information about the running app.


 
##  Module 6: Managing Version Control 

 ### Demo 1: Examine a History of repo on GitHub. 
 
  In this demo you will learn and understand how to get the history of all the actions made on a git repo.
  
  Also, you will learn how to go to a certain commit from the history and make it the current head.


 ### Demo 2: Install Git on Windows and Ubuntu. 
 
  In this demo you will learn and understand how to install git on a Windows machine.
  
  Also, you will learn how to install git on Ubuntu machine.


 ### Demo 3: Hand-typed text files Vs. Generated text files. 
 
  In this demo you will learn and understand how to auto generate text files using command line interface or GUI.
  
  Also, you will learn the difference between hand-typed text files and the generated text files.


 ### Demo 4: Use git as a local repo (config, init, commit, etc). 
 
  In this demo you will learn and understand how to deal with your local repo and use git commands to configure your repo and initialize git on it.
  
  Also, you will learn how to commit your changes to keep track of your work locally or publish them to the remote repo.


 ### Demo 5: Use git as a remote repo from the local one (clone, pull, push, etc) Azure Repo. 
 
  In this demo you will learn how to use version control to sync your local repo with the remote repo, and understand how git technology works.
  
  Also, you will learn how to use the git commands (clone, pull, push, etc) and keep your work updated with your teammates work.


 ### Demo 6: Use git remote repo with GitHub. 
 
  In this demo you will learn and understand how to use Github to create a remote repo.
  
  Also, you will learn how your local and remote repos can be connected together through git version control.


 ### Demo 7: Work with git using IDE (Visual Studio) to interact with Azure Repo and GitH. 
 
  In this demo you will learn and understand how to use Visual Studio Code -an example of a popular IDE- to interact with your remote repo on Github and Azure Repo.
    
  Also, you will learn and see how you can keep your local repo synced with the remote one.


 ### Demo 8: Work with git using IDE (VS Code) to interact with Azure Repo. 
 
  In this demo you will learn and understand how actions can be made on Azure Repo from your machine through VS Code terminal.
  
  Also, you will learn how to create a new branch, pull from remote repo and push your changes to it. 



##  Module 7: Defining and Implementing Continuous Integration (CI) 

 ### Demo 1: Create and configure Continuous Integration (CI) pipeline for a .NET class library. 
 
  In this demo you will learn and understand how to create Continuous Integration (CI) pipeline that checks for all code quality criteria like automated testing, code coverage, etc. You will also learn how to sit code coverage threshold to make sure your code has the minimum quality to be accepted in the remote repo. Also, you will learn how to create package management of the class library and to be ready to be pushed to public or private feeds.
    
    
 ### Demo 2: Create and configure Continuous Integration (CI) pipeline for API. 
 
  In this demo you will learn and understand how to perform Continuous Integration (CI), the case behind developing CI pipelines, and how it improves the overall software development lifecycle.
  
  Also, you will learn how to use Azure DevOps to deploy a CI pipeline and how to implement a CI Strategy. 


 ### Demo 3: Build hosted agent vs self-hosted agent and run self-hosted to examine build folder. 
 
  In this demo you will learn the difference between hosted agents vs a self hosted agent and understand how run a self hosted agent to perform CI.
  
  Also, you will learn the benefits of each approach and the use case for each of them.


 ### Demo 4: Use YAML over classic Continuous Integration (CI). 
 
  In this demo you will learn and understand how to use YAML over classic GUI CI pipeline, and how YAML can improve the flexibility you have over your pipelines.
  
  Also, you will learn how to write a .yml file and attach it to the repo. 


 ### Demo 5: Create and configure Continuous Integration (CI) for .NET core app on docker image. 
 
  In this demo you will learn and understand how to create and configure a CI pipeline for a .NET core app hosted on docker image repository.
  
  Also, you will learn the workflow needed to pull the docker image and perform the build pipeline.


 ### Demo 6: Create and configure Continuous Integration (CI) for PartsUnlimited App. 
 
  In this demo you will learn and understand how to create and configure a CI pipeline for one of the available demos in Azure DevOps demo generator (PartsUnlimited App).
  
  Also, you will learn the difference between continuos integration, where each change will initiate a pipeline and how you can add approvals to the workflow. 


 
##  Module 8: Designing a Dependency Management Strategy 

  ### Demo 1: Create and examine feed on Azure artifact with different options. 
 
  In this demo you will learn what are feeds and understand how to use them to share packages, while also controlling permissions to those packages.
  
  Also, you will learn how Azure artifact provide different options to create and use feeds.


 ### Demo 2: Package and publish the class library to NuGet. 
 
  In this demo you will learn and understand how to package your class library and also how to publish it through CLI or NuGet dashboard.
  
  Also, you will learn how to install the new package from NuGet Package Management. 
    

 ### Demo 3: Use feed views to share packages. 
 
  In this demo you will learn and understand how to use feed views , and how feeds can steamline the process of sharing your packages.
    
     
 ### Demo 4: Package and publish class library to Azure Artifact feed and use it from Visual Studio. 
 
  In this demo you will learn how to package and publish a class library to Azure Artifact feed, and understand how this process streamlime package management.
  
  Also, you will learn how to use that package from Visual Studio and how to manage the package. 
    

 ### Demo 5: Package and publish the API App to Azure Pipeline Artifact. 
 
  In this demo you will learn and understand how to package and publish the API App by generating the artifact from Azure Pipeline.
  
  Also, you will learn the ease of use that Azure DevOps provides to manage your packages.


 ### Demo 6: Package and publish PartsUnlimited App to Azure Pipeline Artifact. 
 
  In this demo you will learn and understand how to package and publish the PartsUnlimited App by generating the artifact from Azure Pipeline.
  
  Also, you will learn the ease of use that Azure DevOps provides to manage your packages. 
    

 ### Demo 7: Package and publish a .NET Docker image to Docker Hub. 
 
  In this demo you will learn and understand how package and publish a .NET docker image to Docker Hub, which is a docker repo for to store your packages.
  
  Also, you will learn how this process improves collaboration on package management and ensures a consistent process for delivering a packaged app.



##  Module 9: Defining and Implementing a Continuous Delivery & Release Strategy 


 ### Demo 1: Create a CD for API. 
 
  In this demo you will learn and understand how to setup a continuos delivery pipeline for an API app.
  
  Also, you will see how to create a CD for an API which has been created from scratch in previous lessons.
    

 ### Demo 2: Create a CD for Parts-Unlimited. 
 
  In this demo you will learn and understand how to create a CD for a Web App.
  
  Also, you will learn and apply what you have learned on a Web App we already created in previous lesson(Parts-Unlimited).
    

 ### Demo 3: Configure Azure Pipeline as a process for self-hosted and run UI tests. 
 
  In this demo you will learn and understand how to configure Azure pipeline as a self-hosed agents. 
  
  Also, you will learn the process to run UI tests for your self-hosted agent.
    

 ### Demo 4: Deploy docker image to Azure Container App Service. 

  In this demo you will learn how to create a container image for your application, and understand how to push the image to a container registry.
  
  Also, you will learn how to deploy the image to Azure App Service, and understand how to deploy the image to Azure Container Instances (ACI).
    

 ### Demo 5: Enable Continuous Integration and Continuous Deployment. 
 
  In this demo you will learn how to enable continuos integration and continuous delivery in your pipeline.
  
  Also, you will learn how to disable some features in the CD or CI and leave the rest enabled.

 
 
##  Module 10: Managing Configuration Management for Infrastructure and Database 

  ### Demo 1: Provision infrastructure (Web App and Azure SQL on Azure) using ARM and Azure Pipeline. 
 
  In this demo you will learn and understand how to provision azure resources (Web App and Azure SQL) using Azure Resource Manager (ARM) Template, and adding an initiation step in Azure Pipelines.
  
  Also, you will learn how IaC can improve your infrastructure provisioning process and deliver the flexibility that the cloud provides.


 ### Demo 2: Provision infrastructure (Web App on Azure) using Terraform and Azure Pipeline. 
 
  In this demo you will learn and understand how  provision azure resource (Web App) using Terraform by HashiCorp, and adding an initiation step in Azure Pipelines.
  
  Also, you will learn how IaC can improve your infrastructure provisioning process by procuring the required resources when they are only needed.
    

 ### Demo 3: Install and Configure Liquibase on Azure pipeline self-hosted agent. 
 
  In this demo you will learn and understand how download and configure Liquibase and it's extensions and the jdbc driver on your self-hosted machine.
  
  Also, you will learn and how to define it as global variable to all users to be able to communicate for pipeline agent run as service.
    

### Demo 4: Using Liquibase for DB configuration management with H2 DB. 
 
  In this demo you will learn and understand how to used the installed Liquibase on Azure pipeline for DB configuration management with H2 DB.
    

 ### Demo 5: Deploy DB changes to Snowflake using Liquibase and Azure Pipeline. 
 
  In this demo you will learn and understand how we can utilize Liquibase, a Database Change Management Tool, to deploy database changes in Snowflake using Liquibase and Azure Pipeline.


 ### Demo 6: End-to-End CI-CD to Deploy Infrastructure and Web application.  (Free session)

  In this demo you will learn and understand how to create an Azure repo and how to push the code to the remote repo, create and configure a Continuous Integration (CI) pipeline that will build/test the application and the infrastructure as code as well. Also, you will learn and understand how to create two packages, the application package which includes all the app code like CSS, HTML, java-scripts, etc, and the infra package which includes all the terraform code of the environment on Azure. After that you will learn how to push and store the two packages to Azure artifacts, then create and configure a Continuous Deployment (CD) pipeline that picks the packages from the artifacts, after that it will provision App service on Azure, Azure SQL Server and Database using the infra package, and in the end, deploy the app package to the provisioned environment.



##  Module 11: Team Collaboration and Work Tracking 

 ### Demo 1: Structure People Dimension in Portfolio Management. 
 
  In this demo you will learn and understand how to create a new project in an Azure DveOps organization, and create multiple teams in the created project.
  Also, you will learn and understand how to structure people in the created teams.


 ### Demo 2: Structure Time Dimension in Portfolio Management. 
 
  In this demo you will learn and understand how to structure time dimension in Portfolio Management.
  Also, you will learn and understand how to structure Scenarios, Seasons, Releases and Sprints.

 ### Demo 3: Structure Business Dimension in Portfolio Management. 
 
  In this demo you will learn and understand how to structure business dimension, and know the difference between Theme, Epic, Feature, User Story, and how to create them.
  Also, you will learn and understand how to add description, Acceptance criteria (Functional Criteria - Usability Criteria - Data Criteria) to your Product Backlog Item.


 ### Demo 4: Assigning Who Do what and when in Portfolio Management. 
 
  In this demo you will learn and understand how to specify the time that the work item should be on, and how to assign it to a speciific iteration (sprint).
  Also, you will learn and understand for whom you should assign the work item.

 ### Demo 5: Agile Planning and Portfolio Management with Azure Boards. 
 
  In this demo you will learn and understand how to work with teams, areas and iterations, work items, and how to create different work items types like Epics, Features, PBIS and tasks.
  Also, you will learn and understand how to Manage the project sprints and capacity, and also learn how to customize Kanban boards.


 ### Demo 6: Plan work using Azure Boards. 
 
  In this demo you will learn and understand how to create an Azure DevOps project, create teams, and how to add team members.
  Also, you will learn and understand how to create boards, define sprints, and how to assign tasks and set the iteration.

 ### Demo 7: Manage Agile software delivery plans across teams. 
 
  In this demo you will learn and understand how delivery plans enable multiple teams to plan, schedule, and coordinate their work.
  Also, you will learn and understand how to create a delivery plan and adjust a team's sprint workload to optimize delivery efficiency, and how to review dependencies between work items shown in a delivery plan.



##  Module 12: Examples Of Different Practices Improvement in Several Areas 

  - **No Demos**



## Module 13: Overview of SRE and Monitoring Practices 

  ### Demo 1: Create a monitoring dashboards of Log Analytics data. 
 
  In this demo you will learn and understand how to Log Analytics dashboards can visualize all of your saved log queries, giving you the ability to find, correlate, and share IT operational data in the organization.


 ### Demo 2:  Create and use Log Analytics workspace. 
 
  In this demo you will learn and understand how to create a Log Analytics workspace, Also, you will learn and how to collect logs and data.
    

 ### Demo 3: Create, view, and manage metric alerts. 
 
  In this demo you will learn and understand how to create, view, and manage metric alert rules through Azure portal and Azure CLI.



##  Module 14: Digital Transformation and DevOps 

   - **No Demos**

## Module 15: Analyzing The Current Maturity of DevOps and Applying the Transformation 

  - **No Demos**



## Module 16: Applying Quality and Security for DevOps 

  ### Demo 1: Run Static Application Security Testing (SAST) using Azure Pipeline. 
 
  In this demo you will learn and understand how to Integrate static application security testing into DevOps pipeline when you develop applications for the cloud.
 
 
 
##  Module 17: Version Control in More Details  

 ### Demo 1: Use git branch and merge. 
 
  In this demo you will learn and understand about Git branching and how to merge these branches to a local or remote repository.

 ### Demo 2: Use git PR with Azure Repo and GitHub. 
 
  In this demo you will learn and understand how to create pull requests (PRs) to change, review, and merge code in a Git repository.
  
  Also, you will learn review pull requests in Azure Repo and GitHub.


 ### Demo 3: Create fork with GitHub and use PR. 
 
  In this demo you will learn and understand about how to fork a repo with GitHub and how to use use pull requests( PRs).



##  Module 18: Docker in More Details  

 ### Demo 1: Working with Docker in more details on Linux. 
 
  In this demo you will learn and understand more about docker, container, image, also understand different between docker and virtual machine, 
  and how to install docker on linux.


 ### Demo 2: Working with Docker on Windows. 
 
 In this demo you will learn more about how to use docker on window. 

 ### Demo 3: More about Docker and how to use Docker compose. 
 
  In this demo you will learn and understand more about docker compose, and also how to create docker compose file and run multiple container on same time.



##  Module 19: Mentoring, CV and Interpersonal Skills  

 ### Demo 1: Examine more than 10 real professional CVs that passed the screening and they have been accepted. 

  In this demo you will learn and understand how to write your CV based on some real CVs with no names either for the person or the company, but they passed the screening phase and the interview for more than one big company.
