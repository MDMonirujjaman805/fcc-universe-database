# FCC Relational Database - Universe Project

This repository contains the database dump file for the freeCodeCamp Relational Database "Universe" project.

## Files

- universe.sql — PostgreSQL dump file that rebuilds the complete database (tables, data, constraints)

## How to Restore the Database

Run the following command in a bash terminal where the file exists:

psql -U postgres < universe.sql