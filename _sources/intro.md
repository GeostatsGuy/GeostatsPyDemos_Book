# e-Book Introduction

## Applied Geostatistics in Python: A Hands-on Guide with GeostatsPy 

#### Michael Pyrcz, Professor, The University of Texas at Austin 

##### [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

This e-book provides an accessible, online version of my GeostatsPyDemos GitHub repository. This repository includes well-documented demonstration Python Jupyter workflows for many common geostatistical modeling workflows with the GeostatsPy geostatistics Python package converted into a book with the [jupyter-book package](https://jupyterbook.org/en/stable/intro.html). The goal of the e-book is to share this content beyond the GitHub users that are often experts and developers.

```{admonition} Welcome!
:class: remove-from-content-only

The goal of this e-book is to teach the application of geostatistics in Python, for those new to geostatistics I provide theory and links to my course content, and for those experienced practitioners I provide example workflows and plots that you can implement.
```

This is my first attempt to convert my repository of well-documented Python workflows, [GeostatsPyDemos: GeostatsPy Python Package for Spatial Data Analytics and Geostatistics Demonstration Workflows Repository](https://github.com/GeostatsGuy/GeostatsPyDemos) {cite}`pyrczdemos2024` into an online e-book. Given this source for the content of this e-book, there are natural consequences on the e-book scope, i.e., what is included and what is not? All the workflows demonstrate the functionality of GeostatsPy and the use of GeostatsPy to accomplish fundamental geostatistics workflow steps. Therefore, this is not a general introduction to statistics nor is it a comprehensive treatment of geostatistics. For this I invite you to refer to a standard textbook like, [Geostatistical Reservoir Modeling](https://a.co/d/4tspALH) {cite}`pyrcz2014`. Alternatively, you can review the linked lectures from my [Data Analytics and Geostatistics Lecture Series](https://youtube.com/playlist?list=PLG19vXLQHvSB-D4XKYieEku9GQMQyAzjJ&si=zBls7dCMaYLzraoe) {cite}`pyrczyoutube` for a deeper dive into the theory and practice of geostatistics. Also, I have a recent book chapter that summarizes GeostatsPy, [GeostatsPy: Open-Source Geostatistics in Python](https://www.intechopen.com/online-first/89590){cite}`pyrczchapter2024` that may be helpful.

```{admonition} Linked Recorded Lectures are Available
:class: remove-from-content-only

For a deeper dive into the theory and practice of geostatistics follow the links at the top of each chapter to my recorded YouTube lectures.
```

All the original geostatistics Python Jupyter notebook workflows are available in my [GeostatsPyDemos](https://github.com/GeostatsGuy/GeostatsPyDemos) GitHub repository. 

<h1 align="center"<p>
    <img src="https://github.com/GeostatsGuy/GeostatsPy/blob/master/geostatspy_logo.png?raw=true" width="200" height="200" />
</p></h1>

<h1 align="center">GeostatsPyDemos: GeostatsPy Python Package for Spatial Data Analytics and Geostatistics Demonstration Workflows Repository (0.0.1)</h1>

<h3 align="center">Approximately 40 Well-Documented Spatial Data Analytics and Geostatistics Workflows with the GeostatsPy Package!</h3>

* It is challenging to learn a new Python package. For me, great examples for common workflows are critical. So I built out over 40 well-documented demonstration workflows that apply GeostatsPy to accomplish common spatial modeling tasks to support my students in my courses:

1. [Data Analytics and Geostatistics Course](https://youtube.com/playlist?list=PLG19vXLQHvSB-D4XKYieEku9GQMQyAzjJ&si=MzTdgS7IfHEhvF4Q) {cite}`pyrczyoutube`
2. [Spatial Data Analytics Course](https://youtube.com/playlist?list=PLG19vXLQHvSDUmEOmBoaxGbFAbvaLdfx4&si=Pd9bNQLVFZ9Yqz6-)
3. [Machine Learning](https://youtube.com/playlist?list=PLG19vXLQHvSC2ZKFIkgVpI9fCjkN38kwf&si=tfOVljWgWiduwGYl)

* Note, I have made modifications to improve the formatting in the book, including the simplification of the workflow headers and suppression of diagnostic output and status bars during model run. 

***

### Cite this e-Book as:

Pyrcz, M.J., 2024, Applied Geostatistics in Python: A Hands-on Guide with GeostatsPy, https://geostatsguy.github.io/GeostatsPyDemos_Book.

### Cite GeostatsPyDemos GitHub Repository {cite}`pyrczdemos2024` as:

Pyrcz, M.J., 2024, GeostatsPyDemos: GeostatsPy Python Package for Spatial Data Analytics and Geostatistics Demonstration Workflows Repository (0.0.1). Zenodo. https://zenodo.org/doi/10.5281/zenodo.12667035

[![DOI](https://zenodo.org/badge/777871341.svg)](https://zenodo.org/doi/10.5281/zenodo.12667035)

#### Table of Contents

```{tableofcontents}
```

#### Recent Updates

Here's some highlights from recent updates:

##### What's New with Version 0.0.1

* there are many minor formatting issues that I will resolve over the next couple of months.
* I will be looking at practice methods to integrate my [Interactive Educational Data Science Python Dashboards](https://github.com/GeostatsGuy/DataScienceInteractivePython) interactive dashboards {cite}`pyrczdemos2021`, and more from my [Data Analytics and Geostatistics Lecture Series](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446/ref=sr_1_fkmr0_1?crid=3ED1DD48WEOWY&dib=eyJ2IjoiMSJ9.Zc8BcsVFjZWavjbNy9lsWGaxzrh1IbDo_8cC252-nSoYSry6LMr4MhaEEpxz35qu.T6Wztji_XQB6K-vAL0kGZFPNBMAu0iK75zaAU2tNLH4&dib_tag=se&keywords=geostatistics+pyrcz&qid=1723129932&sprefix=geostatistics+pyrcz%2Caps%2C89&sr=8-1-fkmr0) {cite}`pyrczyoutube`.

Yet, I'm excited to compile all this content into an accessible format, linked to lectures and with repeatable code. My goal is to help folks get started and improve their application of geostatistics. With an e-book, I realize the dream of sharing educational content with:

* **living documents**, I will continuously make improvements and add new content over time, so send me suggestions and errata and return often!
* **repeatable results**, all examples and plots show the code and anyone can reproduce all the results! The code is immediately downloadable, and all data are online available.
* **links** for rapid access to all associated resources.
* **no pay wall** for anyone around the world to access my content.

For me, this is a wonderful vehicle to combine and share all my educational content. Yes, thousands can follow my workflows on GitHub, but the e-book will share this content much more widely. Accessible and actionable educational content is my personal mantra. Some might wonder, why does Michael do this? Check out my story and you will learn that education changed my life. I grew up in a low income family in a small town in Canada. In middle school (junior high for my Canadian friends), I delivered newspapers for over a year to save up for my first computer that our school guidance councilor helped me buy at a local used computer store. A random engineering student talked to me in a gas station late one cold evening and that got me interested in an university education. Education changed my life, so it is my mission to share all my university educational content. Perhaps, I may lift someone as I was lifted. 

Before we get started, here's more information about the associated repository, the source of the workflows for this e-book.

#### The Workflow Repository

The [GeostatsPyDemos: GeostatsPy Python Package for Spatial Data Analytics and Geostatistics Demonstration Workflows Repository](https://github.com/GeostatsGuy/GeostatsPyDemos){cite}`pyrczdemos2024` hosts more than 40 well-documented demonstration workflow for common geostatistical workflows with GeostatsPy. 

* utilizing synthetic data from my [GeoDataSets](https://github.com/GeostatsGuy/GeoDataSets) repository
* small and often 2D examples for fast run times and ease of interpretation
* often used and cited in my courses for repeatable educational content

Common geostatistical workflows that are included:

* data visualization
* distribution transformation
* spatial data debiasing with declustering
* spatial continuity calculation and modeling with variograms
* spatial estimation
* spatial trend modeling
* spatial simulation
* indicator based estimation and simulation
* cosimulation with secondary data
* summarization over multiple simulated realizations
* spatial model checking
* volume variance relations

and now, here is some information about the GeostatsPy package, first setting it up and then what is it. Note, you can use this e-book, i.e., read and review the workflows, without ever running the code. You only need to install GeostatsPy and the dependency Python packages if you want to download and run these workflows for yourself.

#### Installing GeostatsPy

Firstly, if you haven't installed GeostatsPy, here's the GitHub repository [GeostatsPy GitHub](https://github.com/GeostatsGuy/GeostatsPy/tree/master) {cite}`pyrczetal2021`. GeostatsPy is available on the Python Package Index (PyPI) [GeostatsPy PyPI](https://pypi.org/project/geostatspy/).

To install GeostatsPy, use pip

```console
pip install geostatspy
```
***

#### GeostatsPy Package Dependencies

The functions rely on the following packages:

1. **numpy** - for ndarrays
2. **pandas** - for DataFrames
3. **numpy.linalg** - for linear algebra
4. **numba** - for numerical speed up
5. **scipy** - for fast nearest neighbor search
6. **matplotlib.pyplot** - for plotting
7. **tqdm** - for progress bar
8. **statsmodels** - for weighted (debiased) statistics                

These packages should be available with any modern Python distribution, e.g. [Anaconda](https://www.anaconda.com/download/).

If you get a package import error, you may have to first install some of these packages. This can usually be accomplished by opening up a command window on Windows and then typing 'python -m pip install [package-name]'. More assistance is available with the respective package docs.  

***

#### Information about the [GeostatsPy Python Package](https://github.com/GeostatsGuy/GeostatsPy) for Spatial Data Analytics and Geostatistics

The GeostatsPy Package brings [GSLIB: Geostatistical Library](http://www.gslib.com/){cite}`deutsch1997` functions and more geostatistics to Python. GSLIB is a practical and extremely robust set of code for building spatial modeling workflows. 

I created the GeostatsPy Python Package to support my students in my courses:

1. [Data Analytics and Geostatistics Course](https://youtube.com/playlist?list=PLG19vXLQHvSB-D4XKYieEku9GQMQyAzjJ&si=MzTdgS7IfHEhvF4Q) {cite}`pyrczyoutube`
2. [Spatial Data Analytics Course](https://youtube.com/playlist?list=PLG19vXLQHvSDUmEOmBoaxGbFAbvaLdfx4&si=Pd9bNQLVFZ9Yqz6-)
3. [Machine Learning](https://youtube.com/playlist?list=PLG19vXLQHvSC2ZKFIkgVpI9fCjkN38kwf&si=tfOVljWgWiduwGYl)

I find my students benefit from hands-on opportunities, in fact it is hard to imagine teaching these topics without providing the opportunity to handle the numerical methods and build workflows. In 2017, I tried to have my students use the original FORTRAN executables, and even with support and worked out examples, it was an uphill battle. In addition, all my students and I are now working in Python for our research. Thus, having access to geostatistical methods in Python directly impacts and facilitates the research of my group. This package retains the spirit of GSLIB:

* **modularity** - a collection of standalone functions that may be applied in sequence for maximum flexibility for building workflows
* **minimalist** - the simplest possible code to support the "look at the code" approach to learning
* **fundamental** - based on the well-established geostatistical theory by avoiding ad hoc methods and assumptions

The work on this Python package deepened my respect to the original geostatistics open-source authors, Prof. Clayton V. Deutsch and Prof. Andre G. Journel (emeritus). 

This package contains 2 parts:

1. **geostatspy.geostats** includes GSLIB functions rewritten in Python. This currently includes all the variogram, distribution transformations, and spatial estimation and simulation methods. I will continue adding functions to support modeling operations for practical subsurface model construction. 

2. **geostatspy.GSLIB** includes reimplementation of the GSLIB visualizations and low tech wrappers of the numerical methods (note: the low-tech wrapper require access to GSLIB executables as they write the parameter files, run the GSLIB .exe and read in the outputs).

#### The GeostatsPy Authors

The GeostatsPy package is being developed at The University of Texas in the Texas Center for Geostatistics.

* **Professor Michael J. Pyrcz, Ph.D., P.Eng.** - professor with The University of Texas at Austin. Primary author of the package, translated and wrote many of the functions and maintains the package.

* **Professor Honggeun Jo** - assistant professor with Inha University, South Korea. Author of 3D subroutines, 3D variogram calculation and modeling and wrapper for sgsim for 3D modeling and more! Thank you, Professor Jo!

* **Anton Kupenko** - bug fixes, added docstrings, code refractory for PEP8, removed duplicated functions and variables. Thank you, Anton!

* **Wendi Liu, Ph.D.** - while a Ph.D. student working with Michael Pyrcz at The University of Texas at Austin. Author of 3D subroutines and gammabar method. Also, GSLIB compiles in Mac OSX, and 3D variogram calculation wrapper. Thank you, Dr. Wendi Liu!

* **Alex E. Gigliotti** - undergraduate student working with Michael Pyrcz at The University of Texas at Austin. Established unit testing.  Thank you Alex!

* **Travis Salomaki** - as an undergraduate student research project with Michael Pyrcz at The University of Texas at Austin. Improving package docs. Thank you, Travis!

* **Javier Santos, Ph.D.** - while a Ph.D. student working with Michael Pyrcz at The University of Texas at Austin. Author of the post processing algorithm for summarizing over multiple realizations. Thank you, Javier!

#### Package Inventory

Here's a list and some details on each of the functions available.

##### geostatspy.GSLIB Functions

Utilities to support moving between Python DataFrames and ndarrays, Data Tables, Gridded Data and Models in Geo-EAS file format (standard to GSLIB):

1. **ndarray2GSLIB** - utility to convert 1D or 2D numpy ndarray to a GSLIB Geo-EAS file for use with GSLIB methods 
2. **GSLIB2ndarray** - utility to convert GSLIB Geo-EAS files to a 1D or 2D numpy ndarray for use with Python methods
3. **Dataframe2GSLIB(data_file,df)** - utility to convert pandas DataFrame to a GSLIB Geo-EAS file for use with GSLIB methods
4. **GSLIB2Dataframe** - utility to convert GSLIB Geo-EAS files to a pandas DataFrame for use with Python methods
5. **DataFrame2ndarray** - take spatial data from a DataFrame and make a sparse 2D ndarray (NaN where no data in cell)

Visualization functions with the same parameterization as GSLIB using matplotlib:

6. **pixelplt** - reimplementation in Python of GSLIB pixelplt with matplotlib methods
7. **pixelplt_st** - reimplementation in Python of GSLIB pixelplt with matplotlib methods with support for sub plots
8. **pixelplt_log_st** - reimplementation in Python of GSLIB pixelplt with matplotlib methods with support for sub plots and log color bar
9. **locpix** - pixel plot and location map, reimplementation in Python of a GSLIB MOD with MatPlotLib methods
10. **locpix_st** - pixel plot and location map, reimplementation in Python of a GSLIB MOD with MatPlotLib methods with support for sub plots
11. **locpix_log_st** - pixel plot and location map, reimplementation in Python of a GSLIB MOD with MatPlotLib methods with support for sub plots and log color bar
12. **hist** - histograms reimplemented in Python of GSLIB hist with MatPlotLib methods
13. **hist_st** - histograms reimplemented in Python of GSLIB hist with MatPlotLib methods with support for sub plots

Data transformations

14. **affine** - affine distribution transformation to correct feature mean and standard deviation
15. **nscore** - normal score transform, wrapper for nscore from GSLIB (GSLIB's nscore.exe must be in working directory)
16. **declus** - cell-based declustering, 2D wrapper for declus from GSLIB (GSLIB's declus.exe must be in working directory)

Spatial Continuity

17. **make_variogram** - make a dictionary of variogram parameters to for application with spatial estimation and simulation 
18. **gamv** - irregularly sampled variogram, 2D wrapper for gam from GSLIB (.exe must be in working directory)
19. **varmap** - regular spaced data, 2D wrapper for varmap from GSLIB (.exe must be in working directory)
20. **varmapv** - irregular spaced data, 2D wrapper for varmap from GSLIB (.exe must be in working directory)
21. **vmodel** - variogram model, 2D wrapper for vmodel from GSLIB (.exe must be in working directory)

Spatial Modeling

22. **kb2d** - kriging estimation, 2D wrapper for kb2d from GSLIB (GSLIB's kb2d.exe must be in working directory)
23. **sgsim_uncond** - sequential Gaussian simulation, 2D unconditional wrapper for sgsim from GSLIB (GSLIB's sgsim.exe must be in working directory)
24. **sgsim** - sequential Gaussian simulation, 2D and 3D wrapper for sgsim from GSLIB (GSLIB's sgsim.exe must be in working directory)
25. **cosgsim_uncond** - sequential Gaussian simulation, 2D unconditional wrapper for sgsim from GSLIB (GSLIB's sgsim.exe must be in working directory)

Spatial Model Resampling

26. **sample** - sample 2D model with provided X and Y and append to DataFrame
27. **gkern** - make a Gaussian kernel for convolution, moving window averaging (from Teddy Hartano, Stack Overflow)
28. **regular_sample** - extract regular spaced samples from a 2D spatial model 
29. **random_sample** - extract random samples from a 2D spatial model  
30. **DataFrame2ndarray** - convent spatial point data in a DataFrame to a sparse ndarray grid

##### geostatspy.geostats Functions

Numerical methods in GSLIB (Deutsch and Journel, 1997){cite}`deutsch1997` translated to Python:

31. **correct_trend** - correct the order relations of an indicator-based trend model
32. **backtr** - GSLIB's backtr function  to transform a distribution
33. **declus** - GSLIB's DECLUS program reimplemented for cell-based declustering in 2D
34. **gam** - GSLIB's GAM program reimplemented for variogram calculation with regular data in 2D
35. **gamv** - GSLIB's GAMV program reimplemented for variogram calculation with iregular data in 2D 
36. **varmapv** - GSLIB's VARMAP program reimplemented for irregularly spaced spatial data in 2D 
37. **vmodel** - GSLIB's VMODEL program reimplemented for visualization of nested variogram models in 2D
38. **nscore** - GSLIB's NSCORE program reimplemented for normal score distribution transformation
39. **kb2d** - GSLIB's KB2D program reimplemented for 2D kriging-based spatial estimation
40. **ik2d** - GSLIB's IK3D program reimplemented for 2D indicator-based kriging estimation
41. **kb3d** - GSLIB's kt3d program reimplemented for 3D kriging-based spatial kriging estimation
42. **sgsim** - GSLIB's sgsim program reimplemented for 2D spatial simulation
43. **postsim** - GSLIB's postsim program reimplemented for summarizing over multiple realizations

#### How to Use this e-book?

This is a topical approach to the hands-on application of geostatistics. Each chapter stands alone and covers a unique demonstration or workflow using GeostatsPy. Want to visualize univariate distributions, debias your spatial data with declustering, make estimates in space with kriging or simulate a spatial heterogeneity model? Open up the respective chapter and walkthrough the example with all requisite steps, including data loading, data visualization and geostatistics steps, all codes and results shown. Go to the linked lecture to fill any gaps in your knowledge and then download and update the workflow for your application, please remember to cite the e-book in your work, so that others will see and use this resource! Remember, that this content is for educational purposes only and I do not provide any guarantees. There may be errors in the codes, there may be issues with your case that invalidate the assumptions of the e-book's workflows. It is up to you to evaluate your results.

```{warning}
If you adopt any workflows from this e-book or any codes from the GeostatsPy Python package you must check your own work.
```

#### Want to Work Together?

I hope this content is helpful to those that want to learn more about subsurface, spatial modeling, data analytics and geostatistics. Students and working professionals are welcome to participate. I'm happy to collaborate with your organization.

* Want to invite me to visit your company for training, mentoring, project review, workflow design and / or consulting? I'd be happy to drop by and work with you! 

* Interested in partnering, supporting my graduate student research or my Subsurface Data Analytics and Machine Learning consortium (co-PIs including Profs. Foster, Torres-Verdin and van Oort)? My research combines data analytics, stochastic modeling and machine learning theory with practice to develop novel methods and workflows to add value. We are solving challenging subsurface problems!

* I can be reached at mpyrcz@austin.utexas.edu.

I'm always happy to discuss,

*Michael*

Michael Pyrcz, Ph.D., P.Eng. Professor, Cockrell School of Engineering and The Jackson School of Geosciences, The University of Texas at Austin

#### More Resources Available at: [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)