# Spotify Muisc Recommendation System

The goal of this project is to build a song recommendation system for users of Spotify with their streaming history. The models are evaluted by how well they rank the songs in the test set.

The source data was provided by the company Spotify from Kaggle. 

## Datasets
([tracks.csv](tracks.csv)) - Contains the collection of the data where the customer is listening to a track, one event per line. 
* Event ID : The unique identifier of the event where the customer is listening to the track (Integer)
* Customer ID : The customer Id of the customer listening to the track (Integer)
* Track ID : The track Id of the track currently being played (Integer)
* DateTime : The date and tim, the customer is listening to the track (String)
* Mobile : 1, if the customer is listening to the track on a mobile device else 0 (Integer)
* Listening ZIP : The approximate Zip location of the customer listening to the track (Integer)

([cust.csv](cust.csv)) - Contains the details about the customer
* Customer ID: The unique identifier of the customer (Integer)
* Name, Gender, Address, Zip : The information associated with the customer (String, Integer, String, Integer)
* Sign Date : The date the customer has been added to the service (String)
* Level : The level of subscription of the customer 0, 1, 2 for Free, Silver and Gold, respectively (Integer)
* Other fields: Which we are not interested in this example

([music.csv](music.csv)) - Contains the details about the song
* Track ID: The unique identifier of the tracker (Integer)
* Title: The Name of the track (String)
* Artist: The Artist of the track (String)
* Length: The Length of the track (Integer)



## Model

The project was built with Spark on Databricks platform.

The models are evaluated by the __Expected Percentile Ranking__, introduced by the backup paper for Spark MLlib ALS package for implicit feedback datasets [click here to view](http://ieeexplore.ieee.org/document/4781121/).

The project is carried out in 7 steps:
* Data Loading 
* Data Cleaning	
* Data Exploration		
* Model Evaluation
* Benchmarks
* Build ALS Explicit Model	
* Build ALS Implicit Model	

Code with results are viewable at the links: [[__Part I__]](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6373109224204649/3283764495853970/2920490540025139/latest.html)  

A detailed explaination of the project is in the presentation.pdf file.
# Spotify Music Recommendation System Spark
# 加微信 powcoder

# [代做各类CS相关课程和程序语言](https://powcoder.com/)

# Programming Help Add Wechat powcoder

# Email: powcoder@163.com

[成功案例](https://powcoder.com/tag/成功案例/)

[java代写](https://powcoder.com/tag/java/) [c/c++代写](https://powcoder.com/tag/c/) [python代写](https://powcoder.com/tag/python/) [drracket代写](https://powcoder.com/tag/drracket/) [MIPS汇编代写](https://powcoder.com/tag/MIPS/) [matlab代写](https://powcoder.com/tag/matlab/) [R语言代写](https://powcoder.com/tag/r/) [javascript代写](https://powcoder.com/tag/javascript/)

[prolog代写](https://powcoder.com/tag/prolog/) [haskell代写](https://powcoder.com/tag/haskell/) [processing代写](https://powcoder.com/tag/processing/) [ruby代写](https://powcoder.com/tag/ruby/) [scheme代写](https://powcoder.com/tag/drracket/) [ocaml代写](https://powcoder.com/tag/ocaml/) [lisp代写](https://powcoder.com/tag/lisp/)

- [数据结构算法 data structure algorithm 代写](https://powcoder.com/category/data-structure-algorithm/)
- [计算机网络 套接字编程 computer network socket programming 代写](https://powcoder.com/category/network-socket/)
- [数据库 DB Database SQL 代写](https://powcoder.com/category/database-db-sql/)
- [机器学习 machine learning 代写](https://powcoder.com/category/machine-learning/)
- [编译器原理 Compiler 代写](https://powcoder.com/category/compiler/)
- [操作系统OS(Operating System) 代写](https://powcoder.com/category/操作系统osoperating-system/)
- [计算机图形学 Computer Graphics opengl webgl 代写](https://powcoder.com/category/computer-graphics-opengl-webgl/)
- [人工智能 AI Artificial Intelligence 代写](https://powcoder.com/category/人工智能-ai-artificial-intelligence/)
- [大数据 Hadoop Map Reduce Spark HBase 代写](https://powcoder.com/category/hadoop-map-reduce-spark-hbase/)
- [系统编程 System programming 代写](https://powcoder.com/category/sys-programming/)
- [网页应用 Web Application 代写](https://powcoder.com/category/web/)
- [自然语言处理 NLP natural language processing 代写](https://powcoder.com/category/nlp/)
- [计算机体系结构 Computer Architecture 代写](https://powcoder.com/category/computer-architecture/)
- [计算机安全密码学computer security cryptography 代写](https://powcoder.com/category/computer-security/)
- [计算机理论 Computation Theory 代写](https://powcoder.com/category/computation-theory/)
- [计算机视觉(Compute Vision) 代写](https://powcoder.com/category/计算机视觉compute-vision/)

