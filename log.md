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

## Day  14: July 6, 2016

**Today's Progress**: Milestone! I got my stock charting app done and out the door. Had to make a few tweaks once it was deployed and up on Reddit/Twitter, namely that I made error messages fade out after 2 seconds. After some job hunting, I started thinking about the design of my next project, a book trading club app.

**Thoughts**: It was pretty cool to watch my stock market app go wild once I posted it on Reddit/FB/Twitter. The chart was changing every couple of seconds. I have no clue how many people used it... Hoping my Google Analytics catch up overnight. In the mid-afternoon, there was a weird issue where every stock I tried entering failed, and it seemed like it was happening across the board--the chart went from jam-packed to empty. Restarting the app on Heroku resolved the issue, but I still have no clue what was going on. Need to look into tools/tips for dealing with logs/tracking down the root causes of issues like that.

Link: [Stock Tracker](https://ubershibs-stock-tracker.herokuapp.com) - live on Heroku

## Day 15: July 7, 2016

**Today's Progress**: Today, I learned about the famo.us physics engine briefly, after seeing it mentioned on a job posting, then I focused my engery on the next project for Free Code Camp--the book trading club. I've decided to make it another Angular app, and to use Angular Material for the design. There's a bit of a learning curve to that so far, but I've got it pulling books from the Google Books API already, and looking half decent in doing it.

![Image of site so far](https://67.media.tumblr.com/fa665c0dd17e5c407a6bea5fa8c65e64/tumblr_o9zcpea2Di1qz7w1oo1_1280.png)

## Day 16: July 8, 2016

**Today's Progress**: Plugged away on my book trading app. Learning about Angular Material... Getting quite a bit more comfortable with Angular. Also did a bunch of Ruby exercises on HackerRank. Drove my rank up ~2000 places in one evening. Nice.

## Day 17: July 9, 2016

**Today's progress**: Still learning more about Angular Material. Added a sidenav to the app, fixed the layout to use ngMaterial rather than fight it, which seems to be my natural instinct. And did a few more Hackerrank challenges. Still finding Codeeval.com to be the better site.

## Day 18: July 10, 2016

**Today's Progres**: Very little. I'm spending too much time trying to figure out the ins and outs of Angular Materials layout. Gonna focus on getting all the functionality I need built, and then circle back to perfecting the layout.
