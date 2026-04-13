# Bookstore Database + Python CLI

**Name:** Ananya Devraj

## About

A music-themed bookstore database built with SQLite and Python. It stores books across four categories — Biographies, Learn to Play, Music Theory, and Scores & Collections. It lets you browse, search, add, update, and delete books from the command line.

## Create the database

Run these two commands in the terminal from the `bookstore_src` folder:

```bash
sqlite3 bookstore.db < createTables.sql
sqlite3 bookstore.db < insertRows.sql
```

## Run the Python CLI

```bash
python3 bookstore_cli.py
```

## Menu options

1. View all categories
2. View all books
3. View books in a category
4. Search books by title
5. Add a new book
6. Update a book price
7. Delete a book
8. Search books by author
9. Quit
