# Project : Graphs


# Overview
This project will construct graphs based on a file format and then preform operations on the graph. 
Each node in the graph is given a name and may be connected to an arbitrary number of other nodes. 
Implemented a variety of methods that return answers to questions about the graph, such as finding the neighbors to a string.

# Objectives
This project serves as practice for performing basic graph procedures 

# SymbolGraph
## Constructor/File Format
Each graph file contains a list of vertex descriptions. Each vertex description is separated by a new line. 
Each vertex description is a list. 
The entries in the vertex description are separated by delimiters, such as "/". 
The first entry in the list is the vertex name, and all subsequent entries are the names of the adjacent vertices. 
In the constructor for SymbolGraph, it loads the data in the file and then construct a graph. 


## contains
This method will return true if the graph contains the string

## neighbors
Returns a Bag of all vertices adjacent to the source

## list
Returns a Bag of all the strings in the graph which contains the substring s

## index
Returns the Integer name of the vertex that corresponds with the string s

## name
Returns the String name of the vertex that corresponds with the Integer v

## path
Returns the length of the path from source to sink. If the path does not exist then return null


