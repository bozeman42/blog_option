---
layout: post
title:  "Reading Uploaded Files In Express"
date:   2018-01-02 5:00:00 -0600
categories: expressJS node.js fast-csv express-fileupload
---
There are a number of tutorials that exist which demonstrate how to take data from an uploaded CSV file and insert it into a database. All of them that I've seen require you to store the uploaded file in a directory on your server prior to parsing the file. In current project, I needed to find a way to read the data from the CSV file without storing the file on the server.