# dygraph-elements

A set of performant graph elements powered by [dygraphs](https://github.com/danvk/dygraphs).


## Install

```sh
$ bower install dygraph-elements --save
```


## Examples

#### Time Series

```html
<dygraph-line data="[[data]]"></dygraph-line>

<script>
  scope.data = [
    ["x", "January", "February", "March", "April", "May", "June", "July"],
    [1, 65, 59, 80, 81, 56, 55, 40],
    [2, 28, 48, 40, 19, 86, 27, 90]
  ];
</script>
```

#### Cross Plot

```html
<dygraph-scatter data="[[data]]"
                 no-header
                 label="Label"
                 x="January"
                 y="February">
</dygraph-scatter>

<script>
  scope.data = [
    {"Label": 1, "January": 65, "February": 40},
    {"Label": 2, "January": 30, "February": 20},
    {"Label": 3, "January": 50, "February": 30},
    {"Label": 4, "January": 85, "February": 70}
  ];
</script>
```

## Documentation

See the [component page](http://reinert.github.io/dygraph-elements).


## Demo
* [&lt;dygraph-line&gt;](http://reinert.github.io/dygraph-elements/demo/dygraph-line.html)
* [&lt;dygraph-scatter&gt;](http://reinert.github.io/dygraph-elements/demo/dygraph-scatter.html)


## License

MIT
