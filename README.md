# cs193-reading-tracker

# BookQueue

A command-line app that keeps a prioritized to-read list and recommends
what to read next.

## Project Goal

I bookmark more books than I can read, and I never know which one
to pick up next. BookQueue stores my to-read list with priorities
and  suggests a book based on priority, genre, length, author, etc.

## MVP Scope

- Add, list, and remove books (title, author, pages, genre, priority 1-5)
- Save and load the list from a file between runs
- Sort by priority, date added, or length
- Filter by book information
- Provide recommendation with a short explanation
- Basic input validation and empty-queue handling

## Future Plans

- Mark a book as finished and record a personal user rating
- Look up title, author, and page count by ISBN (Open Library API)
- User-adjustable scoring weights for recommendations
- Reading stats (books per month, favorite genre)

## Tech Stack

- Language: Java 17
- Storage: Plain text file, `|`-delimited
- Version control: Git
