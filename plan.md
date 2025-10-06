## Plan

### Reading List

Book:
- Title
- Author
- ISBN (unique constraint)
- Word count
- Genre(s)

<img width="760" height="372" alt="DB2-Sample-Database" src="https://github.com/user-attachments/assets/1c0d5641-e9ec-41f0-8936-9f6023b630fc" />

Bookshelf:
- Book
- Read status
  - To read
  - Have read (quiz pending)
  - Have read (quiz complete)
 
I don't know if this is how I want to keep track of the reading list, I'll see if there's an easier way to do this. Marking books as read should trigger the option to do the quiz
Once book is marked read (prompting a rating and the quiz) word count is added
You should also be able to rate books, and leave some notes on the book (maybe able to pin to specific pages or chapters but NOT able to take passages from the book. no copyright infringement)

### Quizzes

Quiz:
- Book (unique constraint)
- Level? (if included, combine with book to make the primary key)
- Questions

Option to request a book if there is no quiz for it
Option to set minimum pass score for quizzes (set a default, but make this customisable)
Allow retries, keep history

### Goals

#### Milestones (achievements)

- Word count
  - tracks word count from completed reads
- Books read
- Quiz scores
- Quizzes completed

#### Set Goals

- set goal number of books per week

https://www.goodreads.com/
