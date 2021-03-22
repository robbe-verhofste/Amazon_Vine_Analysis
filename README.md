<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->

Deliverable 1: Perform ETL on Amazon Product Reviews
Deliverable 2: Determine Bias of Vine Reviews
Deliverable 3: A Written Report on the Analysis (README.md)

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Overview"> Overview</a>
      <ul>
        <li><a href="#Subheader">Subheader</a></li>
      </ul>
    </li>
    <li>
      <a href="#Deliverable 1: Perform ETL on Amazon Product Reviews">Deliverable 1: Perform ETL on Amazon Product Reviews</a>
      <ul>
        <li><a href="#prerequisites">Subheader 1</a></li>
        <li><a href="#installation">Subheader 2</a></li>
      </ul>
    </li>
    <li><a href="#Deliverable 2: Determine Bias of Vine Reviews">Deliverable 2: Determine Bias of Vine Reviews</a></li>
    <!-- <li><a href="#roadmap">Roadmap</a></li> -->
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Overview




<!-- Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement. -->

### Subheader




<!-- GETTING STARTED -->
## Deliverable 1: Perform ETL on Amazon Product Reviews



### Overview:

Using your knowledge of the cloud ETL process, you’ll create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets (Links to an external site.), and extract the dataset into a DataFrame. You'll transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, you'll upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded.

We completed the following learning objectives: 

* Define big data and describe the challenges associated with it.
* Define Hadoop and name the main elements of its ecosystem.
* Explain how MapReduce processes data.
* Define Spark and explain how it processes data.
* Describe how NLP collects and analyzes text data.
* Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.
* Complete an analysis of an Amazon customer review.

### Analysis Details

[![Analysis Ouput]](https://github.com/robbe-verhofste/Amazon_Vine_Analysis/images/analysis.png)


<!-- USAGE EXAMPLES -->

## Deliverable 2: Determine Bias of Vine Reviews


## Notes: 

Four Vs of Big Data
There are four characteristics of big data:

* Volume refers to the size of data (e.g., terabytes of product information). For instance, a year's worth of stock market transactions is a large amount of data.
* Velocity pertains to how quickly data comes in (customers across the world purchasing every second). As an example, McDonald's restaurants are worldwide with customers buying food at a constant rate, so the data comes in fast.
* Variety relates to different forms of data (e.g., user account information, product details, etc.). Consider the breadth of Netflix user information, videos, photos for thumbnails, and so forth.
* Veracity concerns the uncertainty of data (e.g., reviews might not be real and could come from bots). As an example, Netflix would want to verify whether users are actively watching the shows, falling asleep, or just playing them in the background.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/robbe-verhofste/
[product-screenshot]: images/screenshot.png
