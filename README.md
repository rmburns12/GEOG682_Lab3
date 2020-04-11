### Lab 3: Raster Analysis using Python in the cloud

#### Total Points: 10

In this lab you will learn how to conduct a basic raster analysis using Python in the cloud.  We will use Binder and GitHub to open your Jupyter notebooks in an executable environment online. You can use either the GEOG VMs or your own computer to complete this lab.

Start by downloading this repository as a .zip file, unzipping it onto your desktop, and then uploading the files to a new repository in your GitHub account. Alternatively, you can clone this repository. Then open https://ovh.mybinder.org/ as a new tab in your web browser, copy and paste the URL of this GitHub repository, and click launch.

It will take a few minutes for Binder to create your environment.  If you’ve set up everything correctly, you should see the familiar Jupyter Notebook interface open in your web browser. Open and run through the Lab3_example notebook – this will help you get familiar with raster analysis using the *rasterio* package.

IMPORTANT: Binder will only save your work while your Jupyter Notebook web browser window is open.  To permanently save changes to your notebook, download it to your computer as a Notebook file and then upload it to your GitHub repository.  You can then close your Jupyter Notebook window, and re-launch your environment by going to the Binder website again.  Practice this now to make sure that you understand how to save your work. 


#### Your Assignment

Your assignment is to conduct a basic analysis of two 3 band (RGB) Sentinel-2 scenes. Start by using Binder to create a new Jupyter Notebook named *yourlastname_Lab3*, then add your name, the date, and “GEOG 682 Lab 3” as Markup.

Now import the *matplotlib* and *rasterio* packages and load the two Sentinel-2 scenes I have provided (*image1.tif* and *image2.tif*). Your task is to create a complete Jupyter notebook that meets the following requirements:

- Plot(s) that show both of the Sentinel-2 scenes using the *terrain* colormap. 

- Code that confirms that both Sentinel-2 scenes have the same coordinate reference system. Use a Markup cell to show the name of this CRS. 

- Code that creates a plot showing all of the bands in *image1* individually including an appropriate title and colormap for each. 

- Code that creates a mosaic image from *image1* and *image2* and plots it using the *terrain* colormap.



When you have completed this notebook, upload it to your GitHub repository that contains the Lab3_example notebook, then copy the URL and submit it to Canvas.  Good luck!
