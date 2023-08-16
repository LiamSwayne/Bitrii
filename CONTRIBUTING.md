# Contributing

Performance:
- == is slower than === because of type conversion ([explanation](https://stackoverflow.com/a/19042070/21247144)). Code that interacts with user input should always prioritize usability over performance. All other engine code should prioritize performance.
