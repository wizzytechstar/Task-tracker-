Task Management Dashboard Thing I Built

So I was working on this project management tool and thought I'd share it here. Basically it's a simple dashboard that tracks tasks per week using charts and stuff.

What it does
The main thing is it shows your team's task completion in a line chart. Pretty straightforward - you can see how many tasks got done each week.

I added a couple buttons:
One that adds random weeks with random task numbers (between 3-12, seemed reasonable) 
Another that resets everything back to the original data

Oh and it shows the actual arrays at the bottom which is kinda neat for debugging or if you're curious about the data structure.

Tech stuff I used
React (obviously) - used hooks like useState and useEffect
Chart.js for the charts because it's pretty solid
Just regular CSS, nothing fancy, lol

Had some issues with the chart not updating properly at first but figured out I needed to destroy the old chart before creating a new one. Classic Chart.js thing apparently.

Why I built this
Honestly started as a way to practice React and ended up being actually useful for tracking project stuff. The visualization makes it way easier to spot trends than just looking at spreadsheets.

Could probably add more features like:
Different chart types
Export functionality
Maybe some filtering options
Better styling (current CSS is pretty basic)

But for now it does what I need it to do. Sometimes simple is better anyway.
The responsive design works decent on mobile too which was important since people check this stuff on their phones all the time.
