# azureml


The sample code in this repository is for use in hands-on exercises.

## Setup

The exercises are designed to be completed in Visual Studio Codespaces. To complete the labs, you'll need the following:

- A Microsoft Azure subscription. If you don't already have one, you can sign up for a free trial at <a href ='https://azure.microsoft.com' target='_blank'>https://azure.microsoft.com</a>.
- A Visual Studio Codespaces environment. This provides a hosted instance of Visual Studio Code, in which you'll be able to run the notebooks for the lab exercises. To set up this environment:
   1. Open [this link](https://online.visualstudio.com/environments/new?name=azureml&repo=GraemeMalcolm/azureml) in a new tab and create a Visual Studio Codespaces environment. If prompted, sign in using the Microsoft account associated with your Azure subscription.
    2. If you don't already have a Visual Studio Codespaces billing plan, create one. This is used to track resource utilization by your Visual Studio Codespaces environments. Then create an environment with the following settings:
        - **Environment Name**: *A name for your environment - for example, **explore-azureml**.*
        - **Git Repository**: GraemeMalcolm/azureml
        - **Instance Type**: Standard (Linux) 4 cores, 8GB RAM
        - **Suspend idle environment after**: 30 minutes
    3. Wait for the environment to be created. This will take around 4 minutes.
    4. Wait for a minute or so while the environment is set up for you. It might look like nothing is happening, but in the background we are installing some extensions that you will use in the labs. You'll see the following things happen:
        - The files in this repo will appear in the pane on the left.
        - After a few minutes (during which there's no apparent activity, but in the background we're setting up the environment for you), a new file named **REFRESH NOW** will appear in the pane on the left. This is your indication that everything has been installed.
    5. After the **REFRESH NOW** file has appeared, refresh the web page to ensure all of the required extensions are loaded and change the color scheme to a light background. Then you're ready to start.
    6. Note the *.ipynb* files in the **Explorer** pane - these contain the lab exercises.

> **Tip**: You can change the color scheme in Visual Studio Codespaces to suit your preference - just click the **&#9881;** icon at the bottom left and select a new **Color Theme**.

## Contributing

At this time, we are not accepting contributions to this repository.