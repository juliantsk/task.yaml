# task.yaml
A flexible human-readable task specification in [YAML], inspired by [todo.txt] and agile work item hierarchy.

## Why?
### Flexibility
Task.yaml allows you to decide how to organize your tasks and store your data. With a flat-file database, you can easily share, store, and secure it how you see fit. Using [YAML] as a backbone, Task.yaml provides a framework for user configuration and task metadata that can fit to the way you work rather than the other way around.

### Readabilitiy
[YAML] rivals [Markdown] for readability, so you can always open the file up yourself and search through it to verify the integrity of your data.

### Hierarachy
Whether you're using the agile work item hierarachy, [heirarchical task analysis], your own system, or no system, task.yaml will work with it. With the ability to establish an arbitary number of connections between tasks and describe that relationship, task.yaml can fit any relational system you desire. Using the user configuration, you can establish a set of naming conventions to describe the different types of tasks in your system (for agile that's normally: Epic, Feature, User Story, and Task).

## Why not \_\_\_?
Projects like [todo.txt] use a flat-file database to be system and software agnostic. It's readable and writable in almost any software environment. You have the control to maintain and store your data. The .txt file uses a learnable syntax, but it is restricted:
- It is not as human-readable nor as useful for computing as simple key-value pairs.
- There is also no ability to self reference, form a heirarchy, or establish your own metadata.

## Why YAML?
It is easier for humans to read and write than other common data formats like XML or JSON. Further, there are libraries available in most programming languages for working with YAML.

## Formatting

### General YAML Formatting
See this [list of Gotchas] for things to avoid in [YAML].

[list of Gotchas]: https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html#gotchas
[YAML]: https://en.wikipedia.org/wiki/YAML
[todo.txt]: https://github.com/todotxt/todo.txt
[hierarachical task analysis]: https://en.wikipedia.org/wiki/Task_analysis#Hierarchical_task_analysis
