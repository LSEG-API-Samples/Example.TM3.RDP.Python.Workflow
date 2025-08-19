# A Step By Step TM3 Client File Store (CFS) File API
- version: 1.0.0
- Last update: August 2025
- Environment: Python Jupyter Notebook

Example Code Disclaimer:
ALL EXAMPLE CODE IS PROVIDED ON AN “AS IS” AND “AS AVAILABLE” BASIS FOR ILLUSTRATIVE PURPOSES ONLY. LSEG MAKES NO REPRESENTATIONS OR WARRANTIES OF ANY KIND, EXPRESS OR IMPLIED, AS TO THE OPERATION OF THE EXAMPLE CODE, OR THE INFORMATION, CONTENT, OR MATERIALS USED IN CONNECTION WITH THE EXAMPLE CODE. YOU EXPRESSLY AGREE THAT YOUR USE OF THE EXAMPLE CODE IS AT YOUR SOLE RISK.

## Introduction 

This example demonstrates how to use Python to retrieve the Municipal Market Monitor (TM3) bulk file via the [Delivery Platform](https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis)—also known as the Data Platform or RDP using the Client File Store (CFS) API service.

Please note that this code is intended for demonstration purposes only and is not optimized for production use.

## <a id="how_to_run"></a>How to run the demo application

The first step is to unzip or download the example project folder into a directory of your choice, then set up Python or Postman environments based on your preference.

### <a id="python_example_run"></a>Run the demo Notebook application

1. Open the Command Prompt and go to the project's folder.
2. Create a file name **.env** with the following content

    ```ini
    MACHINE_ID=<RDP Username>
    PASSWORD=<RDP Password>
    APP_KEY=<RDP App Key>
    PACKAGE_ID=<Your Bulk Package ID>
    ```
3. Run the following command in the Command Prompt application to create a virtual environment named *TM3* for the project.
    ``` bash
    $>python -m venv TM3
    ```
4. Once the environment is created, activate a virtual *TM3* environment with this command.
    ``` bash
    #Windows
    $>TM3\Scripts\activate
    ```
5. Run the following command to the dependencies in the *TM3* environment 
    ``` bash
    (TM3) $>pip install -r requirements.txt
    ```
6. Once the dependencies installation process is success, run the following command to start the Jupyter Lab application.
    ``` bash
    (TM3) $>jupyter lab
    ```
7. Open a **TM3_CFS.ipynb**  file and run each cell to learn the RDP CFS File workflow step by step.

