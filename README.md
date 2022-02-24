
## Project 1 - IMDB 

The goal in this project is to train a binary classifier to distinguish highly rated movies from low rated movies.

Submissions for this project will be shown on the [IMDB Leaderboard](http://big-data-competitions.westeurope.cloudapp.azure.com:8080/imdb).


#### Training Data

The primary files contain an identifier, as well as title, release, runtime and voting information for several movies. The label column denotes whether a movie was highly rated or not.

`train-*.csv`

| tconst  |  primaryTitle | originalTitle | startYear | endYear | runtimeMinutes | numVotes | label |
|---|---|---|---|---|---|---|---|

In addition, there are two files that contain information about directors and writers of the movies.

`directing.json`


| tconst  |  director_id |
|---|---|


`writing.json`

| tconst  |  writer_id |
|---|---|

#### Validation & Test Data

We provide validation and test data as input for the submissions. This data has the same format as the training data, but does not contain the corresponding label.

`validation_hidden.csv` `test_hidden.csv`

| tconst  |  primaryTitle | originalTitle | startYear | endYear | runtimeMinutes | numVotes | 
|---|---|---|---|---|---|---|


----

## Product Reviews 

learn to identify helpful product reviews

[Leaderboard](http://big-data-competitions.westeurope.cloudapp.azure.com:8080/reviews)

### Data

product_id, product_parent, product_title, vine, verified_purchase, review_headline, review_body, review_date, marketplace_id, product_category_id


category.json

category_id, name


marketplace.json

marketplace_id, name

---

## Duplicate Detection - learn to identify duplicate bibliography entries

[Leaderboard](http://big-data-competitions.westeurope.cloudapp.azure.com:8080/dblp)

### Data

dblp-*.csv

pauthor, peditor, ptitle, pyear, paddress, ppublisher, pseries, pid, pkey, ptype_id, pjournal_id, pbooktitle_id, pjournalfull_id, pbooktitlefull_id

pbooktitle.json

pbooktitle_id, name

pbooktitlefull.json

pbooktitlefull_id, name


pjournal.json

pjournal_id, name


pjournalfull.json

pjournalfull_id, name


train.csv / validation_hidden.csv / test_hidden.csv
key1,key2,[label]
