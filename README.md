# Distributed optimisation
Research into distibuting optimisation algorithms, either their data, memory and/or processing

# Background
A distinguished _operations research_ (OR) professor asked me how will "big data" affect his field, namely operations research and optimisation. I gave some vague answers, but this question has been on my mind and after speaking to a few of my colleagues, I realised this is not a simple answer and I could learn a lot about "big data" and O by trying to answer (or explore) this question, namely the technology underlying it and how "OR" algorithms function with computer technology. So more than anything this repo does not necessarily add any novelty, or even contributions, it's for me, and hopefully any other novices, to understand how OR/optimisation algotithms are setup on a machine.

# Mehtodology
Plan is to infer some observations by solivng benchmark problems with different solvers utilising differnt "big data" (spark, etc.) and distributed computing tools.

# Some initial probing questions
On what type of problems, solvers, and size instances and would the following be of benefit
- Distributed  processors
- Spark
- ...

Solvers could be mathematical programming tehcniques, such as linear/integer programming or rather search based heuristcs (metaheuristics spring to mind).


# Intial references
- https://github.com/ehsanmok/spark-lp
- https://www.reddit.com/r/apachespark/comments/3nqplu/spark_linear_programming/
- https://databricks.com/blog/2015/11/02/announcing-the-spark-tfocs-optimization-package.html

- https://deap.readthedocs.io/en/master/tutorials/basic/part4.html
- https://stackoverflow.com/questions/45607035/using-deap-genetic-algorithm-library-with-spark

- Alba E, Luque G & Nesmachnow S, 2013, _Parallel metaheuristics: Recent advances and new trends_, International Transactions in Operational Research, *20(1)*, pp. 1–48.
- http://CRAN.R-project.org/package=doParallel
- http://CRAN.R-project.org/package=foreach





