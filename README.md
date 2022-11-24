Link to my unit test (Boyuan Shao): https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-2-pitcrew/blob/main/Education_Pathways/tests/test_app.py#L48-L54

Pros of TDD:

* Mistakes are caught immediately and will not propagate to other modules.
* Small step development is encouraged and it improves the design because unnecessary dependencies are cut to facilitate the setup.
* It forces code to be modular because developers have to test them along the way. This is particular helpful when writing the software using OOP, for example.
* Good software architecture is enforced.
* Makes code easier to maintain.
* Makes code easier to refactor since every feature is thoroughly tested. There will be no suprises.
* Reduces debugging time since most of bugs are caught in unit tests.

Cons of TDD:
* Slows down the development process since a lot of time is spent on writting unit tests.
* When requirements change, all unit tests have to be re-written. This is nearly the same amount of work as re-writing the code.
* Bugs in unit tests are dangerous and may break the app, espeically when the developer is convinced that his/her unit tests are correctly written.
* Hard to apply to existing code.
* The entire team has to do it.
* Unit tests have to be maintained as well.
* Hard to balance between the amount of code written and the amount of unit tests written. If the developer writes more unit tests than necessary, it would just be a waste of resources.
