# &lt;nvd3-line&gt;  [![Build Status](https://travis-ci.org/saeidzebardast/nvd3-line.svg?branch=master)](https://travis-ci.org/saeidzebardast/nvd3-line)

A polymer element to create line chart using nvd3. It's part of [nvd3 charting elements](https://github.com/saeidzebardast/nvd3-elements).

## Install
```
$ bower install nvd3-line
```

## Usage

### Tag

```
<nvd3-line data="[[data]]" auto-resize></nvd3-line>
```

### Data Format

```
[
  {
    "key": "Sine Wave",
    "color": "#ff7f0e",
    "values": [{
      "x": 0,
      "y": 0
    }, {
      "x": 1,
      "y": 0.09983341664682815
    }, {
      "x": 2,
      "y": 0.19866933079506122
    }, {
      "x": 3,
      "y": 0.29552020666133955
    }, {
      "x": 4,
      "y": 0.3894183423086505
    }, {
      "x": 5,
      "y": 0.479425538604203
    }]
  }, {
    "key": "Cosine Wave",
    "color": "#2ca02c",
    "values": [{
      "x": 0,
      "y": 0.5
    }, {
      "x": 1,
      "y": 0.49750208263901285
    }, {
      "x": 2,
      "y": 0.4900332889206208
    }, {
      "x": 3,
      "y": 0.477668244562803
    }, {
      "x": 4,
      "y": 0.46053049700144255
    }, {
      "x": 5,
      "y": 0.4387912809451864
    }]
  }
]
```
## License

MIT © [Saeid Zebardast](http://zebardast.com)
