# CSSRecommends
Recommendations from the Computational Social Science team at UK Data Service

## I want to ask for recommendations
Go to the [Issues page](https://github.com/UKDataServiceOpen/CSSRecommends/issues) and create a new issue for your recommendations. Make sure you read the below section or check your prompt isn't currently in issues. Most of these resources will be collated in response to questions from the UK Data Service Data Drop-ins.

## Getting Started with:
* [Statistics](#statistics)
* [Linear Algebra](#linear-algebra)
* [Machine Learning and AI](#machine-learning-and-ai)
* [Data Environments](#data-environments)
* [Network Analysis](#network-analysis)
* [Geographic plots in R](#geographic-plots-in-r)
* [Computer Vision](#computer-vision)

### Statistics  
Statistics focuses on gathering, reviewing, analyzing and drawing conclusions from data. A lot of Machine Learning is reliant on an understanding of these statistical concepts.
* [Crash course Stats](https://thecrashcourse.com/courses/statistics)
* [Stats Fundamentals with StatQuest](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9)

### Linear Algebra
Linear algebra concerns itself with matrices, linear equations and more. While it may seem abstract many Machine Learning techniques are based in or around linear algebra. 
* [Fundamentals of Linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab )

### Machine Learning and AI 
Machine Learning refers to algorithms which produce a model which can make predictions on a value, using input values. AI is often used a synonym, though usually refers self-learning systems which apply Machine Learning. Most use-casesrequire ML, not AI.
* [Crash course AI](https://thecrashcourse.com/courses/ai )
* [ML with StatQuest](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF)

## Recommendations
### Data Environments
Learning Python or R is an undertaking, you need more than just these languages to work with data. There are a wealth of community packages that make sentiment analysis, entity-matching and more accessible. Package management isn't easy.

* [Day 1 setup](https://towardsdatascience.com/an-environment-for-data-d03c6767efe2) - [Joe](https://twitter.com/JosephAllen1234) summarises his Day 1 setup at the [UKDS](https://www.ukdataservice.ac.uk/), covering Python and R with Anaconda.
* [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) -  is great if your work is notebook based (a collection of data cells and markdown cells explaining your work). You don't need to maintain any environments here, but you will have to remake them for each project.
* [PyCharm](https://www.jetbrains.com/pycharm/) - PyCharm is a developer environment specifically for Python users.

### Network Analysis
Network Analysis involves reducing real-world situations to graph views. Generally, the advice was to learn R or Python for more mature network analysis tooling.
* [Gephi](https://gephi.org/users/) - A great graphing tool with a detailed quick start section.
* [GraphiPu](https://pypi.org/project/GraphiPy/) - For a Gephi Python libarary, and more, check out the docs for GraphiPy.
* [Social Networking Code Demo 1](https://www.youtube.com/watch?v=4Jcwc9fApnI) - [Diarmuid](https://twitter.com/DiarmuidMc) recently ran a series of interactive coding sessions on Social Networking.
* [Social Networking Code Demo 2](https://www.youtube.com/watch?v=a1oJiBo14u0) - Part 2 of [Diarmuids](https://twitter.com/DiarmuidMc) Social Networking sessions.

### Geographic plots in R
Nice visualizations of a local area in response to a new dataset is a great way to visualize a story. Telling a good story with data is key to getting more buy-in, resources, data access an more!

* [Crime data in R](https://t.co/5cYy3gHBJP?amp=1) - the UKDS is running a multi-day event covering these visualizations. Recording will be availible shortly!
* [ggplot2](https://www.r-graph-gallery.com/327-chloropleth-map-from-geojson-with-ggplot2.html) - A mature R library covering most data viz needs. The link is a quick intro to chloropleth maps.
* [Visualize London boundaries with ggplot2](https://datatricks.co.uk/london-map-in-3-easy-steps) - A tutorial on visualizing London boundaries.
* [Boundary data tool](https://borders.ukdataservice.ac.uk/bds.html) - The UKDS maintains a Boundary Data Selector, if this doesn't bring up what you are looking for usually googling something like "London GIS boundaries" will do.

### Computer Vision
To begin talking about Computer Vision, I think it makes sense to look at image processing while we are here. Image processing is about taking an individual image, or colelction of images and trying to do something with those images. It could be detecting edges, blobs, sharpening the image, changing it's color. Most of this resolves to clever combinations of matrix multiplications. The [Processing IDE](https://processing.org/reference/environment/) is a wonderful tool to build digital art from such image information. It's the harder parts of image processing such as segmenting an image, or classifier what's in that image where Computer Vision steps in.

Computer Vision, takes these methods and adds AI into the mix. Computer vision is a field of artificial intelligence that trains computers to interpret and understand the visual world. This might be classifying products in a supermarket, to making sure a self-driving car can tell the difference between a person and a tree. Due to how practical Computer Vision is, Google already has a [Vision AI](https://cloud.google.com/vision) to make use of. A fantastic place to learn about computer vision is the [Kaggle MNIST Challenge](https://www.kaggle.com/c/digit-recognizer) where you can learn to train a model to recognize handwritten digits. computer Vision benefits from having such tanglible and visual examples in comparison to other fields. We mostly, know how eyes work!

Links:
* [Processing IDE](https://processing.org/reference/environment/)
* [Vision AI](https://cloud.google.com/vision)
* [Kaggle MNIST Challenge](https://www.kaggle.com/c/digit-recognizer)
* [Neural Style Transfer](https://medium.com/x8-the-ai-community/neural-style-transfer-using-deep-learning-to-generate-art-651d9ccf740c)




