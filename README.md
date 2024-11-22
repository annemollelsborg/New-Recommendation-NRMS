# New-Recommendation-NRMS

This project is based on the Ekstra Bladet RecSys 2024 challenge. This project aims to introduce a news recommender system that as baseline is on par with the NRMS network described in this paper, while also improving on the model performance through various extensions like adding time embedding or other relevant extensions.

#	File Name	Description
1	behaviors.parquet	Each file consists of seven days of impression logs.
2	history.parquet	    Each file consists of users' click histories collected over 21 days period.
3	articles.parquet	The information on news articles.
4	artifacts.parquet	Article artifacts, such as article embeddings and image embeddings.

Details of the attributes: https://recsys.eb.dk/dataset/
