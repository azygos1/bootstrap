# Bootstrap

Bootstrap is a free and open-source front-end web framework for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. Unlike many web frameworks, it concerns itself with front-end development only.

### Buttons

Buttons in Bootstrap are pretty simple. The usual `<button>` tag is given a class `btn` and it becomes a Bootstrap button.
If you want to change the colors, you can **add** (along with the existing `btn`) a class `btn-default` for whiteish, `btn-primary` for blue, `btn-info` for light blue, and `btn-danger` for red.

Besides that, the `btn-block` class makes the button span the entire width of the page.
Example:

```
<button class="btn btn-block btn-danger>Click me!</button>
```

### The column grid layout

This is probably the most useful thing about Bootstrap. You can arrange your content with ease that will satisfy your inner perfectionist.
Here's a diagram of Bootstrap's 12-column grid layout:

![Bootstrap grid system](http://bootstrapbay.com/blog/wp-content/uploads/2014/09/bootstrap-grid-system.jpg)

The Bootstrap grid system has four classes: xs (phones), sm (tablets), md (desktops), and lg (larger desktops). The classes can be combined to create more dynamic and flexible layouts.

[Further reading on Bootstrap grids](https://www.w3schools.com/bootstrap/bootstrap_grid_examples.asp)

The elements (for example, buttons) that you want to arrange according to the grid system should be nested in a `<div class="row">`, and each element should be in a div with a `col` class, for example:
```
<div class="row">
    <div class="col-xs-4">
      <button class="btn btn-block btn-primary">Like</button>
    </div>
    <div class="col-xs-4">
      <button class="btn btn-block btn-info">Info</button>
    </div>
    <div class="col-xs-4">
      <button class="btn btn-block btn-danger">Delete</button>
    </div>
  </div>
```
The column grid layout also works on forms (labels, radio buttons) and images.

### Images

The `img-responsive` tag adjusts the image on the page so that it takes up the whole width of the screen. 

### Spans for inline elements

Regular HTML, just that you can add, for example, `text-danger` as a class of `span`. The word inside `span` becomes red.

### Styling text inputs in forms

```<input class="form-control" type="text" placeholder="Name (required)>```

### Bonus

Bootstrap has a class called well that can create a visual sense of depth for your columns.
