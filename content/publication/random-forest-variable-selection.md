+++
title = "Assessing the accuracy and stability of variable selection methods for random forest modeling in ecology"
date = "2017-06-06"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Eric W. Fox" , "**Ryan A. Hill**" , "Scott G. Leibowitz" , "Anthony R. Olsen" , "Darren J. Thornbrugh" , "Marc H. Weber"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Environmental Monitoring and Assessment* 189: 316"
#publication_short = ""

# Abstract and optional shortened version.
abstract = "Random forest (RF) modeling has emerged as an important statistical learning method in ecology due to its exceptional predictive performance. However, for large and complex ecological data sets, there is limited guidance on variable selection methods for RF modeling. Typically, either a preselected set of predictor variables are used or stepwise procedures are employed which iteratively remove variables according to their importance measures. This paper investigates the application of variable selection methods to RF models for predicting probable biological stream condition. Our motivating data set consists of the good/poor condition of n = 1365 stream survey sites from the 2008/2009 National Rivers and Stream Assessment, and a large set (p = 212) of landscape features from the StreamCat data set as potential predictors. We compare two types of RF models: a full variable set model with all 212 predictors and a reduced variable set model selected using a backward elimination approach. We assess model accuracy using RF's internal out-of-bag estimate, and a cross-validation procedure with validation folds external to the variable selection process. We also assess the stability of the spatial predictions generated by the RF models to changes in the number of predictors and argue that model selection needs to consider both accuracy and stability. The results suggest that RF modeling is robust to the inclusion of many variables of moderate to low importance. We found no substantial improvement in cross-validated accuracy as a result of variable reduction. Moreover, the backward elimination procedure tended to select too few variables and exhibited numerous issues such as upwardly biased out-of-bag accuracy estimates and instabilities in the spatial predictions. We use simulations to further support and generalize results from the analysis of real data. A main purpose of this work is to elucidate issues of model selection bias and instability to ecologists interested in using RF to develop predictive models with large environmental data sets."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = "https://esajournals.onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Feap.1617&attachmentId=2187835387"
url_dataset = "https://www.epa.gov/national-aquatic-resource-surveys/streamcat"
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
[[url_custom]]
name = "Journal"
url = "https://link.springer.com/article/10.1007%2Fs10661-017-6025-0"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = false
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = ""
#caption = "My caption :smile:"

+++


