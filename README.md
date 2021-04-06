# To Do List
This application is built with simplicity in mind, it is all about getting the person focused on what needs to get done, without them getting distracted with other items on their to-do list.

**Link to project:** https://app-que-hacer.herokuapp.com/

![alt tag](https://github.com/diannedejesus/100devs_todo/blob/main/todoapp.PNG)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, Node.js, Express, MongoDB, EJS (for building a template)

This is a one-page application (using EJS for the template) that handles the six routes or actions I built for the app. You use the form at the bottom of the page to create a to-do item with a due date and type. If no due date is provided the current date will be automatically applied. If the item is tagged as a priority it will be displayed in that section if it is tagged as additional it will be placed in a hidden menu. If you select the item as an event it will be placed in the event section but only if it is one of the three most recent events.

When an event or priority item is checked it is placed in the completed section. This lets the user have a tally of what they have accomplished since we tend to underestimate or overestimate the work we do, it is nice to have a visual representation. You cant do this with additional items (since you aren't supposed to be working on them) until you move them to your priority section.

Additional items can be viewed by pressing the + button. Events are marked with a blank calendar icon and priority items with a full star and additional with an empty star. By clicking on the star you can move items from one section to another (priority to additional or vice versa). You can't move events since they are automatically handled. Once you mark an event as completed or delete an event the next one is placed.

## Optimizations

The next thing I would do with this application is building a couple of more layouts, and add a bit more functionality behind the scenes for prioritizing items. I would implement a quotes API to provide daily inspiration for the user and move the add section.

## Lessons Learned:

No matter what your experience level, being an engineer means continuously learning. Every time you build something you always have those *whoa this is awesome* or *fuck yeah I did it!* moments. This is where you should share those moments! Recruiters and interviewers love to see that you're self-aware and passionate about growing.

## Other Projects:
Take a look at these couple examples that I have in my portfolio:

**Tic Tac Toe:** https://github.com/diannedejesus/knowledge-aquisition/tree/main/tictactoe

**Coin Flipper:** https://github.com/diannedejesus/knowledge-aquisition/tree/main/coin-flipper

**Portfolio:** https://diannedejesus.netlify.app/
