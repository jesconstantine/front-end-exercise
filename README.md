Frontend Challenge for Developer Candidates
===========================================

To better assess a candidates development skills, we would like to provide the following exercise. This is intended to be an exercise that can be developed within a few hours.

Prerequisites (mandatory)
-------------------------

* [Git](http://git-scm.com/)

Prerequisites (optional)
------------------------
* [nodejs](https://nodejs.org/)
* [npm](https://www.npmjs.org/)
* [Bower](http://bower.io/)

Installation
------------

Clone the project

```bash
git clone git@github.com:massgov/front-end-exercise.git && cd front-end-exercise/
```

Set up your local server with the dependencies and / or task runners that you see fit for this project.  

You can use any library/framework/plugin you want.

You can write html/js/css or in languages which compile into html/js/css.  

Project description
-------------------

We want to develop a small checklist component, based on a [visual design spec](https://projects.invisionapp.com/share/59FOTMHR2X4#/screens/277498035).

On page load, the checklist of items should be displayed.

When the user selects a checkbox, the item should appear crossed out, as shown in the design.

When the user selects a checkbox, holds down the `SHIFT` key and selects a checkbox further down the list, every item in between should also be selected.

The un/check all items should either check or uncheck all items.

Bonus
-----

See if you can develop this component in a way that it (or pieces of it) could be reused elsewhere in our project.

See if you can connect with an external data source to load the todo items and check / maintain the state of those items. (Psst! [json-server](https://github.com/typicode/json-server#readme) could be helpful here ;)

See if you can add any considerations for cross/legacy browser support.

See if you can add considerations for accessibility.

Evaluation
----------

Our goal is to find answers to get a feel for your favorite front end tools, workflow, methodologies, and standards.

Due to the limited time, develop just for the latest version of Google Chrome.
