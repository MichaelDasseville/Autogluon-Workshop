# Setting up Your Environment

Follow these instructions to get set up with a SageMaker notebook environment and to clone the [workshop code repository](https://github.com/MichaelDasseville/Autogluon-Workshop.git).

## Navigate to Amazon SageMaker

Use the search bar in the top of the console to open the [Amazon SageMaker Console](https://console.aws.amazon.com/sagemaker/).

![](/static/images/setup/AWS-Open-SageMaker.png "Check region and open SageMaker from the AWS Console home page")

### Open SageMaker Studio

Amazon SageMaker Studio should already have been provisioned for you.

- From the SageMaker Console, click **Amazon SageMaker Studio** in the left sidebar menu
![](/static/images/setup/SAgeMakerStudioClick.png "Open Studio")
- Create your SageMaker Domain
![](/static/images/setup/SageMakerDomainCreate.png "Create SageMaker Domain")
- Select the quick set up creation
![](/static/images/setup/DomainQuickSetUp.png "Quick Set Up")
- Click **Open Studio** next to your username to open SageMaker Studio
![](/static/images/setup/OpenStudio.png "Open Sage Maker studio")

A new tab will open to the SageMaker Studio UI for your user, as shown below.

![](/static/images/setup/Launcher.png "SageMaker Studio launcher screen")

> **Note**
> If you see a loading screen when opening Studio for the first time, don't worry: This initial process can sometimes take a few minutes to complete. If it's been longer than ~5 minutes, try refreshing the tab or closing it and clicking **Open Studio** again.

## Fetch the Workshop Code

In the "Launcher" tab, scroll down to "Image Terminal" and click on it.

![](/static/images/setup/Studio-Launcher-Term-Highlight.png "SageMaker Studio launcher screen with system terminal highlighted")

In the terminal window, type the following command:

```
git clone https://github.com/MichaelDasseville/Autogluon-Workshop.git
```

![](/static/images/setup/Studio-Git-Clone-Workshop.png)

Once done, you should see the workshop code in the folder sidebar.
Double Click the workshop folder.

![](/static/images/setup/Git-folder.png)

## Open the First Notebook

Open the notebook **Tabular_data_example.ipynb** (Double click it).
You are prompeted to select a Notebook Environment.
Choose: **PyTorch 1.12 Python 3.8 CPU Optimized**

![](/static/images/setup/notebook-env.png)

You will see an indication that the notebook kernel is starting. Wait few minutes for the process to finish.

![](/static/images/setup/starting-lernel.png)

**Congratulations!!** You are now ready to tackle the labs!
