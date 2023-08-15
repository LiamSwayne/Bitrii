# Contributing

Performance:
- [== is slower than ===](https://stackoverflow.com/a/19042070/21247144) because of type conversion. Code that interacts with user input should always prioritize usability over performance. All other engine code should prioritize performance.