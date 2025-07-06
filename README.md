# Work Journal
A system for both journaling your daily work related activities along with a task management system.

## Idea
A task management system based on task lists - todo, done, etc. might not be sufficient for everyone.
It is often desirable to -
1. Have a daily plan of what tasks you want to get done in a day.
2. To keep a record later of what tasks you actually got to do in the day.
3. This might also include tasks that were unplanned.
4. Also while working on tasks you might want to keep notes on each of these tasks.

Such details are also what is required during a typical daily stand-up as well.
While full blown solutions like Trello and the like exist for doing such things,
sometimes a simple LaTeX based solution might be all that is needed.
## Features Implemented
- Use the `tufte-book` template for journaling aesthetics and margin notes.
- Mark text as a task using the `todo` macro.
- Tasks have continously incrementing internal numbering.
- Mark task as done.
- List of Todos and List of Done Todos with hyperlinks.
- Give colors to tasks when displayed in the list of todos.
- Pass `strike` to strikeout tasks in the journal but not in the list of done todos.

## To be Implemented
- Serial numbering in the list of todos to see number of pending tasks.
- Track when a todo is done - if not completed on the day it was added.
