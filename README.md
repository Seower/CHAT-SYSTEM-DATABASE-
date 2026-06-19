# Chat System Database Management (SQL)

A relational database project developed using SQL that simulates the backend structure of a messaging application. The system manages users, chats, groups, messages, notifications, attachments, and user settings while demonstrating database design concepts and SQL operations.

## Features

### User Management

* Store user profiles
* Manage contact information
* Track user status messages
* Record last seen activity

### Group Chat Management

* Create public and private groups
* Assign group administrators
* Manage member counts
* Control chat lock permissions

### Messaging System

* Send and receive messages
* Track read/unread status
* Store message attachments
* Maintain message timestamps

### Notification System

* Generate user notifications
* Store notification content
* Track notification timestamps

### Settings Management

* Notification settings
* Chat history preferences
* Storage and data management
* Theme customization
* Blocked contacts management

### Attachment Management

* Store file information
* Track file types and sizes
* Associate attachments with messages

## Database Tables

* Users
* GroupChat
* Messages
* Chat
* Notifications
* Settings
* Attachment

## SQL Concepts Implemented

### DDL (Data Definition Language)

* CREATE DATABASE
* CREATE TABLE
* ALTER TABLE

### DML (Data Manipulation Language)

* INSERT
* UPDATE
* SELECT

### SQL Clauses & Operators

* WHERE
* BETWEEN
* IN / NOT IN
* LIKE / NOT LIKE
* ORDER BY
* DISTINCT
* EXISTS

### Aggregate Functions

* MIN()
* MAX()
* COUNT()
* SUM()
* AVG()

### Joins

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* CROSS JOIN

### Constraints

* PRIMARY KEY
* FOREIGN KEY
* UNIQUE
* NOT NULL
* DEFAULT

## Entity Relationships

* One User can administer multiple Group Chats.
* Users can send and receive Messages.
* Messages can contain Attachments.
* Users can have multiple Notifications.
* Each User can maintain personalized Settings.

## Sample Queries Included

* User filtering and searching
* Data updates
* Aggregate analysis
* Subqueries
* Join operations
* Group management reports
* User activity retrieval

