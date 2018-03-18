# Database Exercise 6 (Indexing and runtimes)
This repository is a exercise project for Software development (PBA) Database course. Daniel (cph-dh136)

## Description
This assignment is to create indices and experiment with runtimes, in addition to joins and more in SQL. This assignment is based on a description which can be found in the buttom of this ressource [Here](https://github.com/datsoftlyngby/soft2018spring-databases-teaching-material/blob/master/lecture_notes/09-Indices%20and%20runtimes.ipynb). There is a pre-existing dataset which has been given beforehand which is in the form of a postgreSQL docker container which can be run with this command
```
docker run -p 5432:5432 --name data jegp/soft2018-data
```
## [Assignment]()
The assignment is written in jupyter notebook, which can be run with this docker command

```
docker run -p 8888:8888 --name jupyter -v `pwd`:/home/jovyan -it jegp/soft2018-jupyter
```

To connect with data from another container via dockers dns, a link can be established with ```--link [containername]```.

[CLICK HERE OR HEADER FOR THE ASSIGNMENT]()
