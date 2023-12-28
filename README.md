![banner](images/project-banner.png)

# About
Goodreads api utilizes a BeautifulSoup webscraper that parses the [goodreads](https://www.goodreads.com/?ref=nav_hom) website to obtain details about various book titles

**Work in progress, additional featurs are planned**

## User guide
### Current requests
1. `/search/{book_title}`
  ```json
  [
    {
        "title": "Spice & Wolf, Vol. 01",
        "author": "Isuna Hasekura"
    },
    {
        "title": "Spice & Wolf, Vol. 1 (Spice & Wolf: Manga, #1)",
        "author": "Isuna Hasekura"
    },
    {
        "title": "Spice & Wolf, Vol. 02",
        "author": "Isuna Hasekura"
    },
    {
        "title": "Spice & Wolf, Vol. 03",
        "author": "Isuna Hasekura"
    }
  ]
  ```
2. `/details/{book_title}`
  ```json
  {
    "title": "Pale Fire",
    "author": "Vladimir Nabokov",
    "description": "The American poet John Shade is dead. His last poem, 'Pale Fire', is put into a book, together with a preface, a lengthy commentary and notes by Shade's editor, Charles Kinbote. Known on campus as the 'Great Beaver', Kinbote is      haughty, inquisitive, intolerant, but is he also mad, bad - and even dangerous? As his wildly eccentric annotations slide into the personal and the fantastical, Kinbote reveals perhaps more than he should be.Nabokov's darkly witty, richly           inventive masterpiece is a suspenseful whodunit, a story of one-upmanship and dubious penmanship, and a glorious literary conundrum.Part of a major new series of the works of Vladimir Nabokov, author of Lolita and Pale Fire, in Penguin    Classics.",
    "image_url": "https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1388155863i/7805.jpg"
  }
  ```
3. *Additional endpoints are planned for the future...*

## Installation
Simply clone this repository onto your local machine, then locate and run the **main.py** file

**NOTE:** In order to run the application you will need the following:

### Dependencies
- For list of dependencies see the **requirements.txt** file located in the project repository
