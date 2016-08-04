# 100 Days Of Code - Log

### Day 0: June 22, 2016

**Today's Progress**: Started my Nightlife Tracker app (for [this FCC challenge](https://www.freecodecamp.com/challenges/build-a-nightlife-coordination-app)) in earnest.

**Thoughts**: My first Angular app. So far so good.

**Link to work**: [Nightlife Tracker App](https://github.com/ubershibs/nightlife-tracker)

### Day 1: June 23, 2016

**Today's Progress**: I've got login working, Yelp search results loading, and clicks recording as RSVPs... Not yet pulling click counts, or allowing users to remove RSVPs, but I think I should be able to finish this tomorrow, with a bit of time. Will push my changes to github shortly.

**Thoughts:** It feels like one hour a day is a vast underestimation of what I'll be able to devote to this most days, at least until I find a job.

**Link to work:** [Nightlife Tracker App](https://github.com/ubershibs/nightlife-tracker)

### Day 2: June 24, 2016

**Today's Progress**: Have RSVP result counts pulling properly and listing on user's page. Think I have removal done, but still haven't figured out how to get new clicks listed on profile.

**Thoughts:** A truly one page app like this makes things a bit complicated.

**Link to work:** [Nightlife Tracker App](https://github.com/ubershibs/nightlife-tracker)

### Day 3: June 25, 2016

**Today's Progress**: Ended up re-organizing my app fairly significantly for better usability, and simpler coding. Almost done though!!

**Thoughts:** Just found this Angular Style Guide that I think will be really helpful ([on github](https://github.com/johnpapa/angular-styleguide))

**Link to work:** [Nightlife App](https://github.com/ubershibs/nightlife-tracker)

### Day 4: June 26, 2016

**Today's Progress**: Finished my Nightlife Tracker app. It's up at [https://nightlife-tracker.herokuapp.com](https://nightlife-tracker.herokuapp.com). Gonna update my portfolio to include it + my voting app and other back-end projects. I'm getting pretty close to done with the back-end certification.

**Thoughts**: I think that Angular finally started to click in my brain yesterday/today. So that's good. I still wish that FCC had anywhere near as good material coverage for back-end topics as they do for their front-end program (or that Odin had an up-to-date, thorough, JS course).

**2nd Thoughts**: Two things:
- I just did a great tutorial on Gulp from CSS-Tricks that I would recommend to everyone check it if you aren't already familiar with Gulp. I'd been avoiding it, and had been confused by my interactions with it, but building up a script from scratch really clarified everything for me. You can check out [that tutorial here](https://css-tricks.com/gulp-for-beginners/).
- I've only had my Nightlife Track app up for about 12 hours, and already, people have searched on it 90+ times (and I swear only a couple of those were me). From all over, too (by the cities they searched—-all I'm logging is their search term.) That's pretty neat!

### Day 5: June 27, 2016

**Today's Progress**: Rather than starting in on a new project, I took time today to update my personal website and then dug in on JS unit testing for the first time. Added tests to my [timestamp microservice](https://github.com/ubershibs/timestamp).

**Thoughts**: I'm going to endeavour to add tests to everything I've built for the Back End track so far, and then try TDD for my next bigger project... Not committing to it, just to trying it.

### Day 6: June 28, 2016

**Today's Progress**: Learned more about unit testing. Specifically about writing tests for Mongoose models. Added some to my Voting App. Check them out [on Github](https://github.com/ubershibs/voting-app);

### Day 7: June 29, 2016

**Today's Progress**: I really focused on applying for jobs today, so all I had time to do were two quick exercises on CodeEval, and a couple tutorials for D3 to get myself geared up for the next back end project, the stock market app.

Link to work: you can check out my [CodeEval profile](https://www.codeeval.com/dashboard/), and the [github repo](https://github.com/ubershibs/codeeval) where I put all my solutions.

### Day 8: June 30, 2016

**Todays Progress**: I'm skipping around a little bit, but I'm striking things off my to-do list, so no matter! Today's big accomplishment so far is that I added a new City Stats page to my Nightlife Tracker app. It gives a quick summary of searches performed—-top cities, recent searches, and total and weekly counts. I also (*proud*) wrote tests for the back-end of this new feature—-TDD! Not so much the client-side code, but it's a start!

Link to my work: [City Stats](https://nightlife-tracker.herokuapp.com) / [Github repo](https://github.com/ubershibs/nightlife-tracker)

### Day 9: July 1, 2016

**Today's Progress**: Today I started my Stock Tracker app, but setting up the calls to retrieve data for a given stock, and to store the datasets for all currently displayed companies, and remove a company. There may be additional finessing to do to this data once I figure out how sockets work, and once I pick a charting tool/methodology, but I've got the data feeding into things nicely, and it was simpler than I expected. I'm using Quandl as my data source.

### Day 10: July 2, 2016

**Today's Progress**: Today, I began adding Socket.io to my code. Nothing very exciting to report so far, but I'm tired and literally only had an hour to spend on coding today.

### Day 11: July 3, 2016

**Today's Progress**: Got an initial set of socket.io calls up and running. Next step is to get them working witht real data & database/api calls. This is fun.

### Day 12: July 4, 2016

**Today's Progress**: First time using Socket.io (outside of a tutorial), and it has its complexities. Need to look into the best way to transmit fairly sizeable chunks of data tomorrow.

### Day 13: July 5, 2016

**Today's Progress**: Finally cracked the nut on the Stock Tracker app--'the nut' in this case being the synchronization between the chart, the list of stocks, and the db, light as it is, between all users. Will post the project for feedback tomorrow. Excited!

Link to my work: [Stock Tracker on Github](https://github.com/ubershibs/stock-tracker)

### Day  14: July 6, 2016

**Today's Progress**: Milestone! I got my stock charting app done and out the door. Had to make a few tweaks once it was deployed and up on Reddit/Twitter, namely that I made error messages fade out after 2 seconds. After some job hunting, I started thinking about the design of my next project, a book trading club app.

**Thoughts**: It was pretty cool to watch my stock market app go wild once I posted it on Reddit/FB/Twitter. The chart was changing every couple of seconds. I have no clue how many people used it... Hoping my Google Analytics catch up overnight. In the mid-afternoon, there was a weird issue where every stock I tried entering failed, and it seemed like it was happening across the board--the chart went from jam-packed to empty. Restarting the app on Heroku resolved the issue, but I still have no clue what was going on. Need to look into tools/tips for dealing with logs/tracking down the root causes of issues like that.

Link: [Stock Tracker](https://ubershibs-stock-tracker.herokuapp.com) - live on Heroku

### Day 15: July 7, 2016

**Today's Progress**: Today, I learned about the famo.us physics engine briefly, after seeing it mentioned on a job posting, then I focused my engery on the next project for Free Code Camp--the book trading club. I've decided to make it another Angular app, and to use Angular Material for the design. There's a bit of a learning curve to that so far, but I've got it pulling books from the Google Books API already, and looking half decent in doing it.

![Image of site so far](https://67.media.tumblr.com/fa665c0dd17e5c407a6bea5fa8c65e64/tumblr_o9zcpea2Di1qz7w1oo1_1280.png)

### Day 16: July 8, 2016

**Today's Progress**: Plugged away on my book trading app. Learning about Angular Material... Getting quite a bit more comfortable with Angular. Also did a bunch of Ruby exercises on HackerRank. Drove my rank up ~2000 places in one evening. Nice.

### Day 17: July 9, 2016

**Today's progress**: Still learning more about Angular Material. Added a sidenav to the app, fixed the layout to use ngMaterial rather than fight it, which seems to be my natural instinct. And did a few more Hackerrank challenges. Still finding Codeeval.com to be the better site.

### Day 18: July 10, 2016

**Today's Progres**: Very little. I'm spending too much time trying to figure out the ins and outs of Angular Materials layout. Gonna focus on getting all the functionality I need built, and then circle back to perfecting the layout.

### Day 19: July 11, 2016

**Today's Progress**: Got the back end of the authentication system done. Tomorrow's task will be wiring it up to the front end. Decided to keep on keeping on with Angular Material... The custom directives make it pretty annoying to pull out, or to stick back in later. Getting a lot more comfortable with it now.

### Day 20: July 12, 2016

**Today's Progress**: Got authentication up and running. Working on building out the profile, building up user's collections, and making an all books page next.

### Day 21: July 13, 2016

**Today's Progress**: Made a lot of headway today. You can now log in and add books to your collections, as well as remove them. The sidenav works, and changes state depending on your logged in status. And I'm close to having the All Books page up and running. I think I can wrap this up by the weekend.

![Book Trading Club screenshot](https://66.media.tumblr.com/b48a8f7afd87bf1edd118095724ea0dd/tumblr_oa9yslrf071qz7w1oo1_540.png)

### Day 22: July 14, 2016

**Today's Progress**: Did a bunch of HackerRank challenges, and plugged away at my book site. Starting to feel a bit stuck.

### Day 23: July 15, 2016

**Today's Progress**: There goes my goal of getting this finished off over the weekend. Feel like I'm still fighting with layout more than anything. Well, layout, and data not updating when I think it should, namely my sidenav menu. Ugh.

### Day 24: July 16, 2016

**Today's Progress**: More HackerRank today, to try to get my mind off of the Book Trade site. That and a scan of a few older projects to make notes/start in on things I want to improve on, to have a more solid portfolio.

### Day 25: July 17, 2016

**Today's Progress**: Starting to get some momentum again on the book trading site.

### Day 26: July 18, 2016

**Today's Progress**: Had something of an overnight marathon and finally got a lot of functionality up and running. You can now see a list of all books (de-duped but not yet paginated), and each user has a wishlist to which they can add books, to kick off a trade.

### The profile
![The profile](https://67.media.tumblr.com/a7fd2581983181cd02c97c39ab3bc4e1/tumblr_oaixesHRuc1qz7w1oo1_540.png)

### The all-books page
![The all books page](https://67.media.tumblr.com/2b1798fc85f14b8ae25a9a979e1a2b28/tumblr_oaixesHRuc1qz7w1oo2_1280.png)

### Day 27: July 19, 2016

**Today's progress**: I got the wishlist logic working properly, and began working on the pending trade logic. It's relatively complicated, since I have to get the ID's of each book that has been wish listed, then find all the users with this book currently in their collection, and in their interface, let them know a user from X location has wants the title. Pretty neat. I also figured out how to use md-select on the state/province field, which should keep user input consistent. Next: setting up autosuggestion on the city.

**Thoughts**: Really trying to pack as much learning about Angular Material, as well as best practices for writing Angular apps, as I can into this app. It's definitely slowing me down (I also haven't had as much time each day to devote to coding as I have on other projects, but this is a good app for it, because the relatively large feature set gives me lots of opportunity to try out a lot of directives/really get a handle on the flexbox-based layout system. That said, I am really excited to get a fully functional first iteration out the door.

See my work: https://github.com/ubershibs/book-trading-club/

### Day 28: July 20, 2016

**Today's progress**: Played more with the formatting of the profile page, and added some missing details, like alt tags on images. Started (very initial work only) to layout out trade logic.

### Day 29: July 21, 2016

**Today's progress**: Disaster today: the profile stopped working altogether. I was tired, and wasted most of the hour I had to devote to my book app to figuring out what was going on. Ended up just aplying for jobs.

### Day 30: July 22, 2016

**Today's progress**: Thank god for version history... I had somehow managed to just delete the entire contents of my profile html file, and didn't notice. Easy to fix. Anyway, after today's session, the app can now identify when a user has books that others have wishlisted, and put them in a 'pending trades' table for the user to approve.

### Day 31: July 23, 2016

**Today's progress**: Didn't have a lot of time today, so focused on fixing some issues with my website/old projects.

### Day 32: July 24, 2016

**Today's progress**: Started in on the "Approve/Initiate Trade" logic. It'll be the most complicated piece--when a user clicks Approve Trade:
* They donor sees the recipient's email address and name.
* The donor sees a "Cancel Trade" button, which reads the book to their collection and to the recipient's wishlist.
* The book is removed from the collection (they are kept on as a past owner) - this way, they no longer see trades for titles in their collection already committed to others.
* The book is removed from the recipient's wishlist, but not yet added to their collection, so that they aren't bothered by trade requests before they actually have receive a book.
* The recipient sees a new entry in their in progress trades section, telling them a user has agreed to give them a copy of the book, and provides their name/contact.
* The recipient sees a "Trade Completed" button, which they press to indicate they have received the book.

So far I have just sketched out the functionality and figured out what data I'll need to be able to present at various stages, and made a schema for trades.

### Day 33: July 25, 2016

**Today's progress**: Today, I started in on coding the logic I sorted out yesterday. It proved frustrating... I'm pretty tired. It's not functional yet... But I did significantly improve error handling on the server side of my app, at least.

### Day 34: July 26, 2016

**Today's progress**: Today, I think I've pretty much hammered out the bulk of the functionality required for the Book Trade App. I've got everything except the very last step, indicating your trade is complete), wired up and pretty much good to go. Just having an issue with that last bit, and I believe it may have more to do with my decision to refactor out the original profile controller into smaller chunks, given I've done the same with the views. I'll get it all sorted in the morning.

### Day 35: July 27, 2016

**Today's progress**: I revamped the views, per my plan yesterday. Things are a lot more cohesive and easier to manage than they were before... But I ate up the better part of my day sorting out the changes to the front-end. Haven't gotten to the refactor yet. Did introduce better error handling to the Express side of things... Need to do the same for the Angular side.

### Day 36: July 28, 2016

**Today's progress**: I fucked something up good today. I'm now getting 403 errors from the Google Books API, and can't figure out what the hell is going on.... Crap.

### Day 37: July 29, 2016

**Today's progress**: Today I decided to learn about testing. I downloaded a slightly outdated copy of my code from my last push to github (thank god for git), and wrote some tests for the search component. Then I began reintroducing the changes I'd made since then one by one, running mocha after each file was updated. Also refactored some of the code I'd been wanting to in the process, so I never figured out exactly what was going on... But it likely had something to do with me screwing up promises somewhere, or (or more likely, AND) my attempt to introduce error handling on the back end.

## Day 38: July 30, 2016

**Today's progress**: Today's priority had been to get the initiate/complete/cancel logic all hammered out for trades, but I got sidetracked realizing that some of my pages were fucked up in Safari or on mobile. So I spent quite a while getting them all sorted, but finally managed to, and I feel like I have a much better understanding of Angular Material as a result. So tomorrow... Hopefully tomorrow I'll get the logic all sorted.

## Day 39: July 31, 2016

**Today's progress**: Almost done. Finally. I keep bumping into issues where one change I make proves to be disastrous, and a whole section of my app not to work for a while, but I'm being careful, working incrementally, saving often, and 'testing', aka running my two tests and then checking the rest by hand, often. Will be able to deploy this tomorrow, for sure.

## Day 40: August 1, 2016

**Today's progress**: Finished! Well, finished enough to share for some feedback. Here are some screenshots:
![Book Trade Mobile Screens](http://67.media.tumblr.com/bdcaee3e2fa0a8b16875e1dd1b27f2a0/tumblr_ob9l262lo61qz7w1oo1_1280.png)

I've still got more work to do, but am pretty happy with it for now.

**Links to my work**: [Book Trade on Heroku](http://ubershibs-book-trade.herokuapp.com), [Github repo](https://github.com/ubershibs/book-trading-club)

## Day 41: August 2, 2016

**Today's progress**: Shared my book trading app on Reddit and the FCC Toronto Facebook group, as well as Linked In, and got a little bit of feedback, which I incorporated and redeployed. Nice to have people using things, though would be really nice to build something actually useful. I think that after my pinterest clone, rather than start FCC's data viz track right away, I'm going to try to find something actually useful I can build, or an open-source project I can contribute to (also, a job).

Other than Book Trade improvements, I began planning out the Picterest, my pinterest clone, by checking out the sample app and videos, making note of the user stories, and investigating different libraries and tools I could use to make this a quick job.

## Day 42: August 3, 2016

**Today's Progress**: Began by building an express server, and working on Twitter authentication. I've left room to add Github/FB/etc later, but the stories only require Twitter, so I'm starting there.

Debating whether to use Angular for this, or whether just to use Swig templates. Swig would be faster... I'll get the back-end fleshed out first, then decide.

**Link to my work**: I'll be storing my code in this repo: https://github.com/ubershibs/picterest.
I'll post a Heroku link as soon as i have one, and will post screenshots as often as I can.
