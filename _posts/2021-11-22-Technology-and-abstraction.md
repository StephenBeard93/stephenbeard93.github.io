---
title:  "Technology and Abstraction"
header:
  overlay_color: "#000"
  overlay_filter: "0.0"
  overlay_image: Panoramic.png
excerpt: "A look at the extent to which economics has embraced AI and a discussion of how best to utilise machine learning in Economic research"
modified: 2020-11-04T16:03:49-04:00
---
## Technology and Abstraction:

A dramatic increase in the computing power over the last decade has led to a surge in the development and use of artificial intelligence (AI). In 2011 IBM’s Watson computer defeated the previous human champions of the television game show <em>Jeopardy!</em>, an impressive feat as the show requires contestants to guess the question after being told the answer, so the computer could effectively be asked anything in all of human knowledge, all while having to deal with puns, idioms and other nuances of human language. 

So has economic research leveraged the new power of AI showcased by IBM’s Watson computer? The short answer is an emphatic no, most economic researchers are not utilising AI. This excellent <a href="https://towardsdatascience.com/use-of-machine-learning-in-economic-research-what-the-literature-tells-us-28b473f26043" target="_blank">article</a> summarises the number of published papers in four major Economic journals by decade. In the last decade just 48 papers contained the keyword ‘machine learning’. This is slightly over 1% of the total 3,820 papers published in this period. The lack of adoption rate of AI in economics is doubly intriguing when we consider that economic forecasting is often sighted by machine learning specialists as one of the clear potential use cases of AI. 

So why has the AI adoption rate been so poor in economics? The most obvious issue facing an individual researcher is the problem caused by abstraction. Abstraction means that to some degree we ignore the details of how something works, and generally simplify it down to a concept which we can grasp and easily explain. For instance, when you drive a car you do not consciously think about how an internal combustion engine works, all you need to know is that pressing the accelerator pedal causes the car to go faster.

However for an economic researcher the issue is that AI often abstracts too much. AI, and in particular machine learning, works by using algorithms which start with no knowledge of how to predict an accurate answer. These algorithms are then trained by feeding the model well labelled training data. 
Imagine that we want to use a neural network (a type of machine learning) to predict whether someone will default on a loan or not. We would first start with an algorithm that knew nothing about how to predict loan defaults rates. We would then train it on a historic dataset of well labelled information. This dataset would contain input factors (such as credit score, annual salary, profession) and the actual historical outcome (i.e. did they default or not). The algorithm then makes a prediction for each person in the historic dataset and checks to see if it got it right or wrong. It then uses math to decide how to change the weighting of each input factor. Given enough well labelled data the algorithm will end up with larger weights on more important factors and smaller weights on less important ones.

The power of the neural network example above comes from the fact that it can find tiny relationships between thousands of variables and an outcome. Each variable may have almost negligible prediction power taken on its own, but combing thousands together can lead to a level of forecasting accuracy that no man-made algorithm could achieve. Another advantage of machine learning is that it doesn't rely on a researcher to explicitly pick which input variables to test, instead all possible variables can be fed into the neural network and it will determine which variables are important. This helps to eliminate selection bias in the variables.

The downside to all of this is that neural networks and deep learning (a branch of machine learning) often feels like a black box. It can make powerful predictions, but we have no understanding as to why it made those predictions. It does not lend itself to the creation of economic theories with a clear cause and effect narrative, and so AI has yet to find a home in the traditional approach to economic research.

Technology evangelists see economics as a prime target for AI because it’s a clear example of a complex system, one where thousands of variables interact with each other, and so assume that AI will soon replace economists. However this is likely an oversimplification, and it seems unlikely that we can simply create a model solely driven by AI which will make meaningful forecasts. Instead I believe that AI needs to be deployed to model certain aspects of the economy where it is clearly the best tool for the job. These are parts of an economic model where outcomes are likely influenced by a huge number of factors and conventional cause and effect models simply don’t work. Examples could be in agent behaviour-based simulations, GDP prediction based on a country's input factors (education level, stability, geography, etc.) and exchange rate prediction.

There must be an acceptance that the best way to model certain parts of the economy will require non-abstracted analysis beyond the point of easy understanding, but that this does not somehow detract from economics as a discipline. Creating accurate AI driven models for specific parts of the economy facilitates the building of superior global economic models, which in turns allows higher level overarching questions to be tested and then proved or disproved via the use of simulation and predictions. 

Arguably AI is an essential tool to building global economic models, and it may not even be possible to build a truly useful model without the use of AI. However it is still just one aspect in an overall approach to building a global economic model and is unlikely to be a silver bullet in it’s own right.