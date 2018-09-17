# Using Spark from Python and Jupyter

This repo contains slides and a demo notebook from my talk at PyCon UK 2018.

## Content

In this talk I presented:

* A brief introduction to [Apache Spark][spark].
* Connecting to a Spark cluster running the [Apache Livy][livy] REST interface
  from Jupyter with [sparkmagic][sparkmagic] and any Python code with
  [pylivy][pylivy].
* The basics of loading data into Spark, manipulating it and doing analysis
  with [MLlib][mllib].
* Retrieving data back into Jupyter or Python for further analysis.
* An example web app using [Plotly Dash][dash], [Python RQ][rq] and pylivy to
  build a Spark-powered dashboard using only Python.

## Questions and feedback

Any questions or feedback are welcome either as GitHub issues on this repo, or
directly over email at wacrozier@gmail.com.

## Contribute

[pylivy][pylivy] doesn't yet support nearly all the features provided by Livy.
If you'd like to contribute please get in touch!

[spark]: https://spark.apache.org
[livy]: https://livy.incubator.apache.org
[sparkmagic]: https://github.com/jupyter-incubator/sparkmagic
[pylivy]: https://github.com/acroz/pylivy
[mllib]: https://spark.apache.org/docs/latest/ml-guide.html
[dash]: https://dash.plot.ly
[rq]: https://python-rq.org
