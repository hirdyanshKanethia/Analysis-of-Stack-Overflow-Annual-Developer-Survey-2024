# Data Analysis-of-Stack-Overflow-Annual-Developer-Survey-2024
Data Analysis of Stack Overflow Annual Developer Survey 2024 using Python and Python tools (Pandas, Matplotlib, Numpy, Jupyter and RISE)   

The main purpose of doing this analysis was to learn and hone my skills of Python and it's essential tools. 
The project contains a data folder that contains the stack overflow developer survey 2024 data in csv formats. There is a notebooks folder that contains the notebook used for the data analysis. There is a requirements.txt file that has all the python dependencies for the jupyter notebook.  

## To setup the environment

Open a new terminal in the project folder  
Make a new virtual environment inside the folder using pip  
Install pip and the virtualenv library  

To install the virtual env library, run- `pip install virtualenv`  

To make a new virtual env, run- `python -m venv myenv`  

To activate the virtual environment, run - `myenv\Scripts\activate` on Windows and `source myenv/bin/activate` on MacOS  

Now to install the required python packages, run- `pip install -r requirements.txt`  

To enable RISE, run- `jupyter-nbextension enable rise --py --sys-prefix`  

To run the jupyter web client, run- `jupyter notebook`  

Now you can navigate to the notebooks/survey-notebook.ipynb file and open it in jupyter. To start the RISE slideshow, click the button in the following picture- 
![RISE Slideshow Button](images/Screenshot%202024-12-29%20203046.png)

Now you are all set up and can work with jupyter and rise for a slideshow  

To compile survey-notebook.ipynb into a .slides.html file, run- `jupyter nbconvert notebooks/survey-notebook.ipynb --to slides --post serve`. This will automatically start a reveal.js server to run your slideshow.  

## Running the slideshow

There are two ways to run the slideshow.  

1) Navigate to the survey-notebook.slides.html file and run it in a web browser to view the slideshow. (Recommended)

2) Simply open the pdf file in the repository (Not recommended as the pages in it got tore somehow).

## Conclusion

Thank you for exploring the Stack Overflow Developer Survey 2024 Data Analysis project. The goal of this analysis was to gain deeper insights into the developer community and hone Python skills using libraries like Pandas, Matplotlib, and Numpy. Feel free to explore the notebook, adjust the analysis, and expand on the findings!

## Contributions

Feel free to fork the repository, make improvements, or submit pull requests. If you encounter any issues or have suggestions, please open an issue in the repository.