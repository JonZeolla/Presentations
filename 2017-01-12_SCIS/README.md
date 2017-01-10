# 2017-01-12 Steel City InfoSec
## Security Data Analytics For the Masses
[Event Posting](https://www.meetup.com/Steel-City-InfoSec/events/235321688/)

### Related Materials
I started putting these materials in my presentation but it became too many pages of links, so I moved it here.

#### Table of Contents
- [Semi-Recent News](#semi-recent-news)
- [Programming](#programming)
- [Training/Conferences](#trainingconferences)
- [Datasets](#datasets)
- [Podcasts](#podcasts)
- [RSS/ATOM Feeds](#rssatom-feeds)
- [Presentations/Videos](#presentationsvideos)
- [Papers](#papers)
- [Books](#books)
- [Blogs/Articles](#blogsarticles)
- [MOOCs](#moocs)
- [Mailing Lists](#mailing-lists)
- [Aggregated Materials](#aggregated-materials)
- [Enterprise tools](#enterprise-tools)
- [Upstarts](#upstarts)
- [Miscellaneous](#miscellaneous)


#### [Semi-]Recent News
* "[Preparing for the future of Artificial Intelligence](https://www.whitehouse.gov/sites/default/files/whitehouse_files/microsites/ostp/NSTC/preparing_for_the_future_of_ai.pdf)"
* [AI XPRIZE Pittsburgh](https://www.eventbrite.com/e/xprize-pittsburgh-ai-hackathon-pitch-night-tickets-30452947586).  More details [here](http://ai.xprize.org/)
* [Brains vs AI](http://www.cmu.edu/news/stories/archives/2017/january/poker-pros-vs-AI.html) - 20-day contest at Rivers Casino in Pittsburgh beginning January 11th 2017.

#### Programming
* Java
  * If you want to do big data stuff, you really should know some Java.  It's very predominent.
  * There are **so** many tutorials available online for free, but just for fun, [here's one explicitly](http://docs.oracle.com/javase/tutorial/).
* Scala
  * Scala is similarly popular with big data software, especially because it is so tighly integrated with Java.
    * Scala runs on the JVM. Java and Scala classes can be freely mixed, no matter whether they reside in different projects or in the same.
    * Java libraries, frameworks and tools are all available. Build tools like ant or maven, IDEs like Eclipse, IntelliJ, or Netbeans, frameworks like Spring or Hibernate all work seamlessly with Scala.
  * Here's a [tour](http://docs.scala-lang.org/tutorials/tour/tour-of-scala.html) of Scala.
* Python
  * Packages
    * [pandas](http://pandas.pydata.org/)
    * [scikit-learn](http://scikit-learn.org/stable/)
    * [NumPy](http://www.numpy.org/)
    * [SciPy](https://www.scipy.org/)
    * [Dedupe](https://github.com/datamade/dedupe)
    * [Fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy)
    * [scrubadub](https://github.com/datascopeanalytics/scrubadub)
    * [arrow](https://github.com/crsmithdev/arrow)
    * [datacleaner](https://github.com/rhiever/datacleaner)
    * [quandl](https://www.quandl.com/tools/python)
    * [emcee](http://dan.iel.fm/emcee/current/)
    * [pyparsing](https://pypi.python.org/pypi/pyparsing/2.1.10) - it's not old, it's "seasoned."
    * [Cython](https://github.com/cython/cython)
    * Some more "[Awesome Python Packages](https://github.com/vinta/awesome-python/blob/master/README.md)"
  * Development Environments
    * [Canopy](https://store.enthought.com/downloads/#default)
    * [Jupyter Notebooks](http://jupyter.org/)
  * Other
    * Did you know that you can include R in Python via [rpy2](http://rpy2.bitbucket.org/)?
    * Try out [this brief intro](https://www.stavros.io/tutorials/python/) if you're new to the language.
    * For those of you who love Python and Spark, check out [PySpark](http://spark.apache.org/docs/0.9.0/python-programming-guide.html).
    * [TF Learn](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/learn/python/learn) (previously SkFlow) is a simplified interface for TensorFlow, to get people started on predictive analytics and data mining.
    * [CNTK](https://github.com/Microsoft/CNTK/wiki), a Microsoft competitor to tensorflow.
* R
  * Development Environment
    * [RStudio](https://www.rstudio.com/) is *pretty much* your only option
  * Other
    * Did you know that you can include Python in R via [rJython](https://cran.r-project.org/web/packages/rJython/index.html)?
    * Try out [this brief intro](https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf) if you're new to the language.  Also, a lot of the [MOOCs](#moocs) cover R really well, especially [this class](https://www.coursera.org/learn/r-programming) which focuses on teasing out the nuances of the language and assumes you already know how to code.
    * For those of you who love R and Spark, check out [SparkR](http://spark.apache.org/docs/latest/sparkr.html).
* Apache Zeppelin
  * Zeppelin gets an honorable mention here even though it isn't a programming language.  It is a "A web-based notebook that enables interactive data analytics."  You really should [check it out](https://zeppelin.apache.org/).

#### Training/Conferences
Unfortunately, training in this area is severely lacking in availability, however here's a start.

* [Black Hat](http://www.blackhat.com/upcoming.html) conference
  * Crash Course in Data Science for Hackers
  * Visual Analytics - Delivering Actionable Security Intelligence
* [PyData](http://pydata.org/events.html) events
* [useR!](https://www.r-project.org/conferences.html) conference
* [Strata + Hadoop World](http://conferences.oreilly.com/strata) conference
* [BSidesLV Ground Truth track](https://www.youtube.com/channel/UCpNGmljppAJbTIA5Msms1Pw/videos) (Look for "GT -")
* Here's a [related podcast episode](http://datadrivensecurity.info/podcast/data-driven-security-episode-25.html)

#### Datasets
* [Kaggle](https://www.kaggle.com/datasets)
* [KDD99](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)
* [City of Pittsburgh](https://data.wprdc.org/organization/city-of-pittsburgh) data.  Check out [this page](http://wprdc.org/crime/) for some interesting analytics and visualizations.
* [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets)
* GitHub's [Open Data Showcase](https://github.com/showcases/open-data)

#### Podcasts
* [Hadooponomics](http://bluehillresearch.com/hadooponomics/)
* [Super Data Science](http://feeds.soundcloud.com/users/soundcloud:users:253585900/sounds.rss)
* [Data Driven Security](http://datadrivensecurity.info/podcast/) (Potentially dead?)
* [Talk Python To Me](https://talkpython.fm/)/[Python Bytes](https://pythonbytes.fm/)
* [AI Review](https://itunes.apple.com/us/podcast/ai-review/id1142140410)

#### RSS/ATOM Feeds
* [Top Data News](https://topdata.news/feed/)
* [Datanami](https://www.datanami.com/feed/)
* [Data School](http://www.dataschool.io/rss/)
* [Junk Charts](http://junkcharts.typepad.com/junk_charts/atom.xml)
* [Flowing Data](http://flowingdata.com/feed)
* [R-Bloggers](https://www.r-bloggers.com/feed/)
* [StatsBlogs](http://feeds.feedburner.com/statsblogs)

#### Presentations/Videos
* [The Five Tribes of Machine Learning](https://www.youtube.com/watch?v=oxWruJZ-BbU)
* [Hadoop Safari](https://2016.zeronights.ru/wp-content/uploads/2016/12/Wavestone-ZeroNights-2016-Hadoop-safari-Hunting-for-vulnerabilities-v1.0.pdf)
* [Practical Machine Learning Tutorial with Python](https://www.youtube.com/playlist?list=PLQVvvaa0QuDfKTOs3Keq_kaG2P55YRn5v)
* [Advanced Security Analytics - BSides Vancouver 2015](https://www.youtube.com/watch?v=6SuTaEiYHtI)
* [Data Science or Data Pseudo-Science?](https://www.youtube.com/watch?v=1CQWJDfyQu0)

#### Papers
There are a ton of papers in this area so I'm only going to provide a few.

* [Scale-up vs Scale-out for Hadoop: Time to rethink?](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/a20-appuswamy.pdf)
* Google [Dremel](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf)
* Google [MapReduce](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)
* Google [BigTable](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)

#### Books
* [Data Driven Security](http://datadrivensecurity.info/book/)
* [Hadoop Operations](http://shop.oreilly.com/product/0636920038993.do)
* [Applied Security Visualization](https://www.amazon.com/gp/product/B001FBFH3I/ref=oh_aui_d_detailpage_o09_?ie=UTF8&psc=1)
* [Python for Data Analytics](http://shop.oreilly.com/product/0636920023784.do)
* [R for Everyone: Advanced Analytics and Graphics](https://www.amazon.com/Everyone-Advanced-Analytics-Graphics-Addison-Wesley/dp/0321888030/ref=sr_1_1)
* [Machine Learning Algorithms From Scratch With Python](https://machinelearningmastery.com/machine-learning-algorithms-from-scratch/)
* [Big Data: Principles and best practices of scalable realtime data systems](https://www.amazon.com/dp/1617290343)

#### Blogs/Articles
* [A tour of Machine Learning Algorithms](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/)
* [Top 10 Data Mining Algorithms, Explained](http://www.kdnuggets.com/2015/05/top-10-data-mining-algorithms-explained.html)

#### MOOCs
* [Coursera](https://www.coursera.org/browse/data-science)
* [Udemy](https://www.udemy.com/courses/search/?q=data science&src=sac&kw=data sci&lang=en)
* [stackskills](https://stackskills.com/courses)
* [MIT Big Data and Social Analytics Certificate Course](http://getsmarter.mit.edu/big-data-and-social-analytics-course/)
* [Big Data Analysis with Apache Spark](https://www.edx.org/course/big-data-analysis-apache-spark-uc-berkeleyx-cs110x)

#### Mailing Lists
* [Security Metrics](http://www.securitymetrics.org/mailing-list.html)

#### Aggregated Materials
* [The Definitive Security Data Science and Machine Learning Guide](http://www.covert.io/the-definitive-security-datascience-and-machinelearning-guide/)
* [Data Driven Security Resources](http://datadrivensecurity.info/blog/pages/resources.html)
* [Big Data Ecosystem](https://github.com/zenkay/bigdata-ecosystem)
* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
* [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)
* [Awesome Hadoop](https://github.com/youngwookim/awesome-hadoop)
* [Awesome Data Engineering](https://github.com/igorbarinov/awesome-data-engineering)
* Or many of the other [awesome lists](https://github.com/sindresorhus/awesome)

#### Enterprise tools
* [HUNK](http://docs.splunk.com/Documentation/Hunk/6.4.5/Hunk/MeetHunk) with various Apps
* [Splunk](https://www.splunk.com/) with the [ML Toolkit](http://docs.splunk.com/Documentation/MLApp)
* [Prelert](http://info.prelert.com/) and the [Elastic Stack](https://www.elastic.co/webinars/introduction-elk-stack) (previously ELK)
  * Prelert used to have a [Splunk app](http://info.prelert.com/products/anomaly-detective-app) which I heard was good, but it was EOL once they got acquired by Elastic.
* ... so many more.  These were just top of mind/easily retrievable.

#### Upstarts
* [Apache Metron (incubating)](http://metron.incubator.apache.org/)
* [Apache Spot (incubating)](http://spot.incubator.apache.org/)
* [Panaseer](https://www.panaseer.com/)
* [Niddel](http://www.niddel.com/)
* [LogicHub](http://www.logichub.com/)
* [BluVector](https://www.bluvectorcyber.com/)
* ... so many more.  These were just top of mind/easily retrievable.

#### Miscellaneous
* The Chrome Extension [NoCoffee](https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl?hl=en-US) - key for for visualizations.
* [MLSec](https://github.com/mlsecproject)
* [Stratosphere IPS](https://stratosphereips.org/)
* Some people to follow: [Ken Westin](https://twitter.com/kwestin) ([website](http://www.cybersecurity.io/)), [Casey Stella](https://twitter.com/casey_stella) ([website](http://www.caseystella.com/)), [Rocky DeStefano](https://twitter.com/rockyd), [Alex Pinto](https://twitter.com/alexcpsec), [Bob Rudis](https://twitter.com/hrbrmstr), [Jay Jacobs](https://twitter.com/jayjacobs), [Raffael Marty](https://twitter.com/raffaelmarty) ([website](http://raffy.ch/)), [Davi Ottenheimer](https://twitter.com/daviottenheimer) ([website](http://www.flyingpenguin.com/)), [Nathan Marz](https://twitter.com/nathanmarz), and more people I definitely forgot.
* [OpenAI](https://openai.com/about/) which is a non-profit artificial intelligence research company. Our mission is to build safe AI, and ensure AI's benefits are as widely and evenly distributed as possible.  Invested in by Elon Musk, Peter Thiel, and others including Microsoft, AWS, YCR (Y Combinator).
* [Data Science Ontology](http://collaboratescience.com/WDS/)
* [Awesome Data Science](https://github.com/bulutyazilim/awesome-datascience)

