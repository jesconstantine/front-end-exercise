Frontend Challenge for Developer Candidates
===========================================

To better assess a candidates development skills, we would like to provide the following exercise. This is intended to be an exercise that can be developed within a few hours.

Asking questions is part of the job - feel free to ask us for any clarification beyond this readme!

Prerequisites (mandatory)
-------------------------

* [Git](http://git-scm.com/)

Prerequisites (optional)
------------------------
> Please feel free to use any tools you feel comfortable with & you feel are appropriate - below are simply some suggestions.

* [nodejs](https://nodejs.org/)
* [npm](https://www.npmjs.org/)
* [Bower](http://bower.io/)

Installation
------------

1. 'Fork' this repository on Github


2. Clone the project

```bash
git clone git@github.com:<your-username>/front-end-exercise.git && cd front-end-exercise/
```

3. Set up your local server with the dependencies and / or task runners that you see fit for this project.

Definition of Done
-------------------

We want to develop a small checklist component, based on a [visual design spec](https://projects.invisionapp.com/share/59FOTMHR2X4#/screens/277498035).

Acceptance Criteria
-------------------

1. On page load, the checklist of items should be displayed.
1. When the user selects a checkbox, the item should appear crossed out, as shown in the design.
1. When the user selects a checkbox, holds down the `SHIFT` key and selects a checkbox further down the list, every item in between should also be selected.
1. The un/check all items button should either check or uncheck all items.

Implementation Details
----------------------

:heavy_check_mark: You can use any task runner you want.

:heavy_check_mark: You can use any library/framework/plugin you want.

:heavy_check_mark: You can write html/js/css or in languages which compile into html/js/css.

:heavy_check_mark: Due to the limited time, develop just for the latest version of Google Chrome.

Submission / Demo
-----------------

When you're all set, push your branch up to your forked repository.

We must be able to pull your branch down and run the app locally.

Nice-to-haves
-------------
> This is where you have fun - think one of these features makes sense? Try it!

- you can develop this component in a way that it (or pieces of it) could be reused elsewhere in our project
- you can connect with an external data source to load the todo items and check (Psst! [json-server](https://github.com/typicode/json-server#readme) could be helpful here ;)
- you can add any considerations for cross/legacy browser support
- you can add considerations for accessibility - how would a screen-reader interact with this?
- you can maintain the state of checked items when we reload the page


Evaluation
----------

Our goal is to get a feel for your favorite front end tools, workflow, methodologies, and standards.
