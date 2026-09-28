## Project memory

The memory tools (load_memory, search_memory, save_memory) are this component's,
and the store belongs to the project: the system prompt carries its complete title
list.

- load_memory one whose title relates to the task before exploring, so the work
  follows what earlier sessions already learned.
- search_memory only when no listed title matches: it searches the contents, which
  the titles only summarize.
- save_memory the moment you learn a durable fact — a user preference, a project
  convention, a key decision, a constraint. A later session sees the title and
  nothing else, so the title has to carry the fact.
