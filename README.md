# Ideas for a One-Day Python Workshop

## Pre-requisites:

- Code Fellows 301 graduate or equivalent experience

## Concepts

- Setting up Sublime Text and verification of Python 3 install
  - Download
  - Install console script
  - Download & use the Flake8 linter
  - Check for Python 3; download if doesn't exist
- What is Python and what can you do with it?
- The Python interpreter
  - Strings, Integers, Floats, Booleans
  - Lists, Dictionaries
  - Functions, Loops, and Conditionals
  - The `print()` statement
- **Script #1: Hello, World!**
  - `print('Hello World!')`
- Importing packages from the Python Standard Library
  - Consuming user input with `sys.argv`
  - `if __name__ == '__main__:'`
- **Script #2: Build the acronym generator -> https://github.com/codefellows/data-structure-challenges/tree/master/acronym**
- Creating a virtual environment
- Installing new packages with the `pip` command
  - Install iPython -> `pip install ipython`
- Talk about request -> response cycle
  - Install requests -> `pip install requests`
  - Install BeautifulSoup -> `pip install bs4`
- **Script #3: Scrape Wikipedia**
  - Retrieve names of all [billboard number one artists](https://en.wikipedia.org/wiki/List_of_artists_who_reached_number_one_in_the_United_States) and links to their wikipedia pages
  - Save those names to file
- Explanation of servers and Python as a server-side language
- **Script #4: Building Flask App**
  - `pip install Flask`
  - Model-View-Controller -> Model-View-Template
  - First route and HTTP response with static file
    - "Hello World!" on route `/`
  - Replace "Hello World" with the list of artist names using a template
  - Create an application for listing and viewing the detail of blog posts
    - Retrieve a file of fake blog posts from GitHub or something
