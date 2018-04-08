# Solr Tutorial

## About:
This a tutorial on how to set up a basic Solr instance on your own machine. Read more about
Solr [here]("http://lucene.apache.org/solr/").
Also, I'm using a Mac. Commands in terminal/command might differ if you're using a Windows or Linux machine.

## Installation and Start up/Shut down
1) Download the latest version of solr [here]("http://www.apache.org/dyn/closer.lua/lucene/solr/7.3.0") <br>
2) Unzip the file and move the solr folder to your desired location <br>
3) Open Terminal and change directory to where you put the solr directory then go to the bin directory
```
bash-3.2$ cd [solr-directory-here]/solr-[version_number]
bash-3.2$ cd bin
```
4) Start solr instance with `./solr start`. Default port number will be 8983. Use `./solar -f start` to run in foreground <br>
5) Open a web browser and go to localhost:8983 to view Solr Admin Page <br>
6) Stop solr instance with `./solr stop -all` to shut down solr on all ports. Use `./solr stop -p [PORT NUMBER]` to shut down an instance at given port number <br>

## Creating a core

## Create and configure Data Import Handler

## Import Data from a Database

## Connect to a Java Application (Solrj)
