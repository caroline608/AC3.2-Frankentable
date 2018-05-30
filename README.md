# AC3.2-Frankentable

# Object

Build a TableView based app that parses a block of text and displays a concordance of 
Mary Wollstonecraft (Godwin) Shelley's **Frankenstein** in a table. Each row of the table should display a
unique word in it and its frequency count next to it. 

# Steps

1. The usual forking and cloning. This time there is a project inside named Frankentable.
  Open it.
2. The project has a Table View controller and a Data.txt file with a small excerpt from the book. 
  This file is opened and spat out in viewDidLoad to get you going.
3. Split the block of text into unique words and count their frequency. Probably going to want 
  to use a Dictionary.
4. Display one row per word, showing the word and its frequency,
  Example cell:
  
    ```
    ***********************************
    *                                 *
    *   Albatross (12)                *
    *                                 *
    ***********************************
    ```
  
5. Sort alphabetically, with a section for each letter of the alphabet, grouping by
  the initial letter of each word.

6. Sort by frequency, ordered reverse. I.e. the most frequent word should be in the
  first cell, the least in the last. Section by distinct freqency counts. For example,
  say the highest frequency was 43 and there was 1 word with that frequency, then a
  section named "43" would have that one row. If the next most frequent word occurred 22 times, and
  there were three such words, they would be in the "22" section.  And so on.

7. Optional: If you feel ambitious you could grab the full data via an web request to http://www.gutenberg.org/cache/epub/84/pg84.txt.
  It would be wrong to call this an API call because it's just a text file. Don't try to turn it
  into JSON. Just read it like we're doing with the local file. It should still be done
  asynchronously.
  
  # Caroline Cruz	

646.548.6795  
Cruz.Caroline08@gmail.com  
[LinkedIn](http://www.linkedin.com/in/caroline-cruz)  
[GitHub](https://github.com/caroline608)  

## SKILLS

Swift, Xcode, Git, GitHub, JSON, Programmatic Autolayout, Firebase, Core Data, CocoaPods, Web APIs, Storyboard, MapKit, Core Location, Project Management  

## PROJECTS

**SpotSwap - [currently on TestFlight](https://github.com/Yaseen-al/SpotSwap/tree/qa)**  
* Collaborated with a team of four to develop an efficient way to swap parking spots in NYC
* Integrated Firebase as a back-end server, utilized real-time database to update live changes on the map, stored user images, and authenticated users
* Created programmatic views, timer, and objects for swapping logic  
* Served as the project manager; was responsible for keeping peers on task, planning weekly sprints on Trello, and facilitating daily stand-ups
  
**Parent Approved - [Parent Approved](https://github.com/wsmaragh/SafeSpace/tree/dev-caroline3)**    
* Collaborated in a team of four during New York Open Source hackathon to create “The Yelp of pre-Kindergarten”
* Developed a map feature using MapKit and Core location to display users location
* Created a search bar that filters schools by zip code and displayed in a tableview
* Parsed several JSON to build models of the information displayed to parents
* Developed a favorites tab where parents can save schools using NSUserDefaults

## EXPERIENCE

**C4Q (Coalition For Queens)**, Long Island City, NY		September 2017 - Present
*iOS Development Fellowship*  
* Enrolled in an intensive 9 month, Google-funded software engineering fellowship with a 9% acceptance rate (out of 1500+ applicants) whose graduates are prepared with both technical and professional skills and have been hired as developers at leading companies such as Pinterest, JP Morgan, and Spotify.  Projected graduation: June 2018.
* Gained hands-on experience with Swift, Git, Data Structures, Algorithms, APIs, and tech principles and culture via both team/individual projects, code reviews, and pair programming.
   
**Kobre and Kim LLP**, New York, NY				July 2014 - September 2017
*Accounting Assistant*  
* Reconciled bank and credit card statements
* Assisted with month-end processes and adhered to deadline
* Performed various accounting and analytical functions related to Accounts Payable: ensuring all the submitted invoices and expense reports had approvals and correspondent backup documentation, overviewed coding and input of invoices, expense reports and credit card vouchers in Elite 3E and chromeRiver, and resolved various issues with vendors and internal staff
* Prepared, posted and entered journal entries

## EDUCATION

**State University of New York, Plattsburgh**,  
Bachelor of Science, Accounting, *May 2012*  
Bachelor of Science, Business Administration, *May 2012*
