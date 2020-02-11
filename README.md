## App overview
The app uses MVC design pattern. All of the components are loaded in a hierarchical order, as follows:
1. [Helpers](https://github.com/marcinszczodry/enhanced-todo-app/wiki/Helpers-(helpers.js))
2. [Store](https://github.com/marcinszczodry/enhanced-todo-app/wiki/Store-(store.js))
3. [Model](https://github.com/marcinszczodry/enhanced-todo-app/wiki/Model-(model.js))
4. [Template](https://github.com/marcinszczodry/enhanced-todo-app/wiki/Template-(template.js))
5. [View](https://github.com/marcinszczodry/enhanced-todo-app/wiki/View-(view.js))
6. [Controller](https://github.com/marcinszczodry/enhanced-todo-app/wiki/Controller-(controller.js))

## Installation
To get started you need to first install those packages using the following command:

``npm install``

The project uses some dependencies that are essential, including the following:
* todomvc-common,
* todomvc-app-css.

## Serving the content
There are two ways of serving the app:
1. locally (just open index.html in the browser),
2. using local development server (you must install it yourself or use your IDE's function to host the app).

## Testing
It is recommended to test the app while developing, thus following the TDD paradigm. The project uses _Jasmine_ to create and run the test. Adequate dependencies (see below) are installed automatically when running `npm install`.

Dev dependencies required to test the app.
* jasmine,
* jasmine-core.

You can run the test by serving the `test/SpecRunner.html`. You may write your own tests inside `test/ControllerSpec.js`.
