# MongoDB Blog and City Data Analysis Project

This project was made in collaboration with [mariamagro](https://github.com/mariamagro) for the Databases subject in the Carlos III university.

This project explores the use of MongoDB to model and query non-relational data for blog posts and city information. It demonstrates how to manage complex data relationships using MongoDB's flexible schema.

## 📋 Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Exercise 1: Blog Data Model](#exercise-1-blog-data-model)
- [Exercise 2: City Data Analysis](#exercise-2-city-data-analysis)

## 🚀 Introduction

This project involves two main tasks:
1. **Exercise 1**: Designing a blog data model, inserting data, and querying specific posts and comments.
2. **Exercise 2**: Importing city data and performing various queries, including population analysis and geographic queries.

The project demonstrates how MongoDB can manage document-based data, such as blogs and city records, in an efficient and scalable manner.

## 📁 Project Structure

The project contains two exercises:

1. **Exercise 1: Blog Data Model** - A MongoDB collection that models users, blog posts, comments, and tags.
2. **Exercise 2: City Data Analysis** - A MongoDB collection that stores city-related data, including population, geographic coordinates, and state information.

## 📝 Exercise 1: Blog Data Model

### Schema

In this exercise, blog data is modeled in a single MongoDB collection where each document represents a user, along with their posts and comments. The schema includes:
- **User Information**: Name, username, Twitter account, email, and phone numbers.
- **Posts**: A user can have multiple posts, each containing a title, body, tags, comments, and publication date.
- **Comments**: Each post can have multiple comments from different users, with the author's username, comment content, and timestamp.
  
Then some inserts and queries had to be computed.

## 🏙️ Exercise 2: City Data Analysis

### Data Import

In this exercise, a dataset of city information is imported into MongoDB. The data includes fields such as city name, population, and geographic coordinates.

The data was imported using the mongoimport tool and stored in a collection called city, then some queries were computed.

