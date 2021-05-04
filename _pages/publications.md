---
layout: archive
title: "Projects"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Movie Recommendation System Feb 2021 – Apr 2021
======
* Done in Python
* Created a movie recommendation system based on the data set from MovieLens.
* Used K-means and Hierarchical Agglomerative clustering along with Louvain Community Detection to classify users into groups.
* Recommend for a given user movies based on the group they belong to with the two clustering algorithms if they already have some watching history. If the user has no previous watching history, then recommend them the top movies from each group classified by the community detection algorithm.

Man-In-The-Middle Attack Feb 2021 – Mar 2021
======
* Done in Python
* When a client queries a DNS record for bank.com, the program sends a spoofed response containing the attacker's address. This is sent in under 2 seconds to beat the real DNS server's response.
* Whenever a client makes a POST request to the bank's /login endpoint, the program steals the username and password of the client.
* Whenever a client makes a POST request to the bank's /transfer endpoint, the program changes the to parameter in the body to Jason when forwarding the request to the bank. When responding to the client the program reverses the change so the to parameter contains the value which the client actually sent.
* Whenever the client makes a GET request to the bank's /download endpoint, the program steals any file that the server provides.

Music Player (Fullstack) August 2020 - September 2020
======
* Created using PHP, JS, and MySQL
* Has a login/registration page that stores and gets user data from MySQL database.  Hashes the passwords with md5 before storing.
* Has a side navigation bar with a search tool, a main display page for showing songs/albums, and a currently playing bar at the bottom
* Gives user ability to create/add to playlists and manipulate song volume, repeating, and skipping.

Popular Movies May 2020 - May 2020
======
* Queried non-relational data to and from MongoDB on a list of movies and performed MapReduce to get the most popular using Scala.

Fibonacci Calculator May 2020 - May 2020
======
* Created Fibonacci calculator web app using Node JS
* Set up Travis CI by configuring a Travis.yml file to allow for automatic build creation
* Used AWS Elastic Beanstalk for deployment

Instagram Clone (Fullstack) Jan 2020 – Mar 2020
======
* Initially utilized HTML/CSS with Jinja frameworks to develop a static version of Instagram. It had the ability to link between different static pages.
* Later implemented server-side dynamic functionality using sqlite and Python/Flask, adding features such as like/unlike, adding/removing users, logging in/logging out, creating accounts, adding/removing posts, and adding/removing comments.
* Lastly implemented client side dynamic functionality with a REST API and JavaScript that fetches data in the background using AJAX

Fakebook Database Jan 2020 – Feb 2020
======
* First creates ER diagram to graph out relations between users in Fakebook, then creates data tables of users with all their information using SQL. Also uses external views to allow for data visualization.
* Retrieves data from database and store them for querying.

Database Structure Dec 2019 – Jan 2020
======
* Implement a database structure - grace hash join using C++ language.
* Use PostgresSQL to investigate query optimization.

Import and Query MongoDB Database Dec 2019
======
* Using a public database, implements nine MongoDB queries in JavaScript.
* Extract data from tables in public database and exporting a JSON file that contains information.
* Importing exported JSON file into MongoDB to create a mongo collection.

Budget Tracker Nov 2019
======
* An android app that keeps track of a user's budget
* User enters the category, the name, and the cost of the object
* Keeps a running total of all their costs
* Also keeps record of each transactions, most recent at the top
* Uses Java

Log Manager Oct 2019 – Nov 2019
======
* Stores and accesses data contained in log files
* Takes user input from Command Line Arguments to determine which what the user is looking for in the log files
* Uses Unordered Maps, Vectors, Deques, and Tuples to store and access data
* Uses C++

Pokemon Finder Nov 2019
======
* Given each Pokemon's position, find the smallest path to get to each Pokemon.
* Uses Branch and Bound
* Implements three different methods, one using Prim's algorithm, one using Minimum Spanning Tree algorithm, one using modified version of Traveling Salesman Problem
* Uses C++

The Walking Deadline Oct 2019
======
* Takes as input a series zombies which the player shoots based on their ETA and health.
* Implements an interface that uses inheritance and dynamic polymorphism.
* Uses Unordered Priority Queues, Sorted Priority Queues, Binary Heaps, Pairing Priority Queues, and Command Line Arguments.
* C++

Wheel of Fortune Oct 2019
======
* Simulates a simple game of Wheel of Fortune
* Uses GUI interfaces to create window for users to play the game
* Uses action listeners to take user input and update player scores, letters that were used, uncovered letters in the puzzle, and the wheel image
* Uses Java

Cache Simulator Mar 2019 – Apr 2019
======
* Simulates a CPU cache
* Executes assembly-language program by accessing instructions and data
* Accesses serviced by the cache, which transfers data to and from the memory as needed
* LC-2K machine code, C

Pipelined Processor Mar 2019
======
* Pipeline processor that simulates the travel of higher level code commands through a processor
* Uses pipelining in the processor rather than delay and stall
* LC-2K machine code, C

Assembly File Converter Feb 2019
======
* Assembles an assembly file into an object file
* Links objects files into one executable consisting of machine code, then uses a simulator to run the executable and output into standard output
* LC-2K machine code, C

Classify Piazza Posts Nov 2018 – Dec 2018
======
* Uses Machine Learning to classify Piazza posts based on post content
* Trains the classifier using example posts
* Predicts the label for a new post based on what it learned from the example posts
* C++

Postfix Calculator Oct 2018 – Nov 2018
======
* A calculator that uses Postfix operations to calculate results.
* Uses user-implemented versions of List and Stack classes
* C++

Euchre Sep 2018 – Oct 2018
======
* Simulator for a game of Euchre
* Uses abstract data types, object-oriented programming, and polymorphism
* C++

Auto-mining Bot for Runescape Jul 2016 – Aug 2016
======
* Program/Bot that allows for the in-game character to continuously mine ore to train their mining level without the need of a player
* Evades detection from adversarial bot detector to prevent the character from being banned through a few methods.
* Distancing time between each ore mined using random distribution to make it mimic human clicking intervals
* Differentiates where it clicks on the ore each time to make it mimic human clicking locations
* Uses Java

​Auto-Alchemy Bot for Runescape Jun 2016 – Jul 2016
======
* Program/Bot that allows for the in-game character to continuously cast alchemy to train their magic level without the need of a player.
* Evades detection from adversarial bot-detector to prevent the character from being banned by distancing time between alchemy casts using random distribution to make it mimic human clicking intervals
* Uses Java
