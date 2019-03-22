# offer_analyzer
example task to process offers

Please write a program that identify the cheapest offer in a list of offers.


Background:
This repository includes the file: offers.json.
It is a json-file with a subset of real offers which are typically used in the data pipeline for hotel.idealo.de.
Offer-objects including detailed information like meta-info, search parameters, booking policies and of course: the price.


Task:
To get an imagination how you handle data challenges, please try to solve following task:
- create a program that returns the cheapest offer of the file: offers.json
- use one of the following programming languages: java, python, c++ (java prefered, but it's up to you)
- read the file with the list of offers, which you can find as array under the root-object: "offers"
- in most cases there are many different prices for one offer. Please use following price for comparison:
  "offers" -> [] -> "_source" -> "totalNet" -> "origin"                                  ._

  filter out offers which are not 'EUR'
  "offers" -> [] -> "_source" -> "currencyCode" -> "origin"                              ._
- identify the CHEAPEST offer and print its data to console


Some Remarks:
- this task should not take more than 2 hours
- you can use this github repository like you prefer: feel free to perform commits and pushes
- try to find a good project design (more important than solving each edge case)
- think about performance
- be able to explain why you doing stuff
- the aim of this task is NOT to find the most perfect, production ready, enterprise rocket version... it is the base for discussions later on.


Good Luck!
