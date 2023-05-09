<h1>Real-Time Forecasting Pipeline using Spark & Kafka</h1>

<h2>Description</h2>
This study aimed to develop a real-time forecasting pipeline using Kafka and Spark, which can handle trillions of events per day. Kafka was initially designed as a messaging queue, but with an abstraction of a distributed commit log, it has become the industry standard for handling data in motion. We developed a Kafka producer to facilitate real-time data movement into a dataset, and two consumers that read from the dataset and perform forecasting tasks using the Spark library. The consumers use machine learning algorithms, including K-means, Bisecting K-means, decision trees, and random forests, to forecast the target variable of the dataset.
<br />
<p align="center">
<br/>
<img src="https://sparkbyexamples.com/wp-content/uploads/2019/03/spark-structured-streaming-kafka.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b>
- <b>Spark</b>
- <b>Kafka</b>

<h2>Dataset</h2>

- <b>[Mobile Price Classification](https://www.kaggle.com/datasets/gauravduttakiit/mobile-price-classification)</b>


