# Configuration schemas

## C3

C3js is a wrapper around D3js, that provides simple, out-of-the-box charts. Visit [c3js.org](http://c3js.org) for more.

#### Line chart

...

#### Bar chart

...

#### Timeseries

...

#### Step

...

#### Step

...

#### PIe

...

#### Area

...

#### Donut

...

#### Spline

...

#### Gauge

...

#### Scatter

...

#### Area spline

...

## D3

D3js is a powerful SVG based "dynamic document" drawing library that can create just about any imaginable visualization. Visit [d3js.org](http://d3js.org) for more.

#### Dendrogram

...

#### Treemap

A recursive json config that uses `name` and `children` as its main keys of arbitrary depth.

```json
{
    "name": "chartname",
    "children": [
        {
            "name": "childelements",
            "children": []
        }
    ]
}
```

#### Voronoi

...

#### Circlepack

A recursive json config that uses `name` and `children` as its main keys of arbitrary depth.

```json
{
    "name": "chartname",
    "children": [
        {
            "name": "childelements",
            "children": []
        }
    ]
}
```

## Basic

One-off, simple, ad-hoc displays.

#### Custom

...

#### Iframe

...

#### Number

...

## Datatables

#### Datatables standard

A table with automatic styling, sorting, filtering and pagination. Format is a list of objects, where values can be any key and value, but all elements in the list **must** have matching key names.

```json
[
    {
        "name": "foo",
        "age": 30
    },
    {
        "name": "bar",
        "age": 20
    }
]
```

## Timeline

#### Timeline standard

A timeline using timeline.js. Format requirements are [available here](https://github.com/christabor/flask_jsondash/blob/master/examples/timeline3.json).

## VennJS

VennJS is a wrapper for d3js that provides an easy to use api for Venn and Euler diagrams. Visit [https://github.com/benfred/venn.js](https://github.com/benfred/venn.js) for more.

#### VennJS standard

...

## Sparklines

Sparklines are "mini" charts that can be used inline. They most often make sense as complementing a larger context, for example, a paragraph of text. See [http://omnipotent.net/jquery.sparkline/](http://omnipotent.net/jquery.sparkline/) for more.

#### Sparklines bar chart

...

#### Sparklines tristate chart

...

#### Sparklines discrete chart

...

#### Sparklines bullet chart

...

#### Sparklines pie chart

...

#### Sparklines box chart

...