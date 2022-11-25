# Setting up Your Environment

Follow these instructions to get set up with a SageMaker notebook environment and to clone the [workshop code repository](https://github.com/MichaelDasseville/Autogluon-Workshop.git).

> **Note**
> Only follow the instructions on this tab if you are at an AWS-hosted event with temporary accounts provided.

> **Note**
> Temporary accounts will be terminated after the end of the event. If you want to save any work you've done here, please download it to your local computer.

## Log in to the AWS Workshop Portal

Go to: **[https://dashboard.eventengine.run/](https://dashboard.eventengine.run/)**. You will be redirected to the page below.

![](/static/images/setup/EventEngine-Home.png "Screenshot of Event Engine login page")

Enter the provided **Hash Code** in the text box.
The button on the bottom right corner changes to **Accept Terms & Login**. Click on that button to continue.

You'll be asked to verify your identity either via an **Email One-Time Password** or logging in with your **Amazon.com retail account**.

![](/static/images/setup/EventEngine-Verify-Methods.png "Event Engine identity verification prompt")

> **Note**
> When using Email OTP, be sure to enter an email address you have access to so you can retrieve the code.
<br/><br/>
Email OTPs may take a few minutes to come through, so please be patient and remember to check your junk folder!

![](/static/images/setup/OTP-Login.png "One Time Password Login")

Once verification is complete, you will be directed to your *team dashboard*:

## Open the AWS Console

You are redirected to the Team Dashboard. Click on **AWS Console**.

![](/static/images/setup/EE-TeamDashboard.png "Event Engine team dashboard after login")

On the next screen, click on **Open Console**.

![](/static/images/setup/open-console-2.png "Event Engine AWS Login dialog")

After opening the AWS Console, please do not change the AWS Region for this event.

## Navigate to Amazon SageMaker

Use the search bar in the top of the console to open the [Amazon SageMaker Console](https://console.aws.amazon.com/sagemaker/).

![](/static/images/setup/AWS-Open-SageMaker.png "Check region and open SageMaker from the AWS Console home page")

### Open SageMaker Studio

Amazon SageMaker Studio should already have been provisioned for you.

- From the SageMaker Console, click **Amazon SageMaker Studio** in the left sidebar menu
- You'll see a list of usernames with a user already created for you
- Click **Open Studio** next to your username to open SageMaker Studio

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
