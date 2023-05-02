# Passive Investing ETF - Module 7 Challenge
In recent years, finance has had an explosion in passive investing. Passive investing means investing in a basket of assets that’s called an exchange-traded fund (ETF). This way, you don’t spend time researching individual stocks or companies or take the risk of investing in a single stock. ETFs offer more diversification.

For this Challenge assignment, I was asked to build a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF. 

---

## *Technologies*

- **Programming Language:** Python, SQL 
- **Libraries:** Pandas, Sqlalchemy, Voilà, Numpy, HvPlot, HoverTool, Warnings
- **Framework:** JupyterLab, VS Code 
- **Operating System:** Mac OS, Microsoft Windows 

---

## *Installation Guide*

**First things first:**
If you don't have Python, Jupyter Lab, or Anaconda installed on your operating system ..

-**[Install Python](https://www.python.org/downloads/)**

-**[Install JupyterLab](https://jupyter.org/install)**

-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**

The SQLAlchemy library should have installed on your computer as part of the Anaconda download. To confirm that SQLAlchemy is installed in your Conda 'dev' environment, open a terminal window, and then complete the following steps:

1. In your terminal, activate your Conda 'dev' environment before checking for installation:
    
        conda activate dev
- If you need to create a new 'dev' environment, type and execute the following in your terminal:
                
        conda create -n dev python=3.7 anaconda
After this you can follow step 1 to activate your 'dev' environment.

2. Run the following command:
                
        conda list sqlalchemy

If sqlalchemy is already installed, sqlalchemy and its version number will display in your terminal, as the following image shows: 

<img width="514" alt="Screenshot 2023-04-29 at 4 29 42 PM" src="https://user-images.githubusercontent.com/123714457/235328186-7913780f-04bb-4ef4-99e9-71b8f70d7ade.png">

- If sqlalchemy doesn’t display in your terminal, you need to install it. To do so, with your Conda 'dev' environment still active, run the following command:
        
        pip install SQLAlchemy 
- You can then use conda 'list' to check for its installation. 

With Voilà, a Python library, you can convert a Jupyter notebook into a live webpage, which is used at the end of the applicaton. To install Voilà, complete the following steps in your terminal window:

1. Activate your Conda 'dev' environment.
2. Run the following command:
        
        conda install -c conda-forge voila
3. Confirm that the installation succeeded by running the following command:

        conda list voila
If Voilà successfully installed, voilà and its version number will display in your terminal window, as the following image shows: 

<img width="520" alt="Screenshot 2023-04-29 at 4 30 00 PM" src="https://user-images.githubusercontent.com/123714457/235328187-4bda82d6-d786-44f4-b781-d9e7e0da9adb.png">

---
## *Web Application Deployment*


https://user-images.githubusercontent.com/123714457/235335141-594e8069-ef22-4040-a8c4-cf2560e0b592.mp4

1. In your terminal, cd to the directory where this repository was cloned/downloaded 
2. Enter 'pwd' - displays the complete path to the current directory
3. Copy path, enter 'voila', then paste and enter path
4. After the web page screen loads, select file 'etf_analyzer.ipynb'
5. Voilà! You are now on the main application web page

---

## *Usage*

- Activate your conda 'dev' environment before opening the main app in jupyter notebooks or vs code 
- With your mouse navigate near the top of the tab, select 'Kernel', then inside Kernel you'll select 'Restart Kernel and Run All Cells...' This will automatically run the whole program for you start to finish. FYI, it may take a few minutes for everything to load!
<img width="400" alt="Screenshot 2023-04-17 at 2 53 35 PM" src="https://user-images.githubusercontent.com/123714457/232619135-6b2f77be-d543-4a59-a4ad-6e62b2113c6c.png">
- Once the jupyter notebook has fully loaded after running all cells, there are a few interactive graphs that the user can manipulate to better understand a trend or explore a hypothesis they might have. The graphs are reltaively very user friendly, but if you find yourself having issues interacting with the them .. 

-**[Configuring hvPlot Tools](https://docs.bokeh.org/en/2.4.0/docs/user_guide/tools.html)**

---

## *Credits*
- [Disabling Scientific Notation w/ HoverTool](https://discourse.holoviz.org/t/how-to-disable-scientific-notation-in-bar-plots-and-in-fact-all-plots/1307)
- [Compress Video](https://clideo.com/compress-video)

For any questions/concerns, anything at all feel free to contact below
- Dylan Johnston
- Email: dylanhjjohnston@gmail.com


---

## *License*

This software is licensed under the MIT License. See the [LICENSE](https://github.com/djohnst914/Passive_Investing/blob/main/LICENSE) file for details.
