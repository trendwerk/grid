# Grid
Item grid.

## Install
```sh
bower install trendwerk/grid --save
```

## Usage
```scss
@include grid((
  'item': '.selector',
));
```

### API
```scss
@include grid((
  'breakpoints': (
    421px: 2,
    641px: 3,
    981px: 4
  ),
  'item': null,
  'margin': 20px,
));
```

#### Item (required)
The selector of the items in the grid.

#### Breakpoints
Specify breakpoints using a Sass map. Format: `minWidth: columnAmount`.

#### Margin
The space between elements.
