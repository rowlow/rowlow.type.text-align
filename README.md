# rowlow.type.text-align
Defining a map of color name and color code pairs, this module generates css selectors for each background, border and text colors.

## Install

```
    bower install --save rowlow.type.text-align
```

## Variables

```
    $rowlow-text-align-namespace // Specific module namespace
```


## Usage

### Setup
```
    /* Set modules namespace (optional) */
    $rowlow-text-align-namespace: "namespace-";

    @import "bower_components/rowlow.type.text-align/main.scss"
```

### CSS Selector Naming Scheme
```
    {rowlow-text-align-namespace}text-aling--{breakpoint-name}--{left, right, center, justify}
```


### HTML
```
    <p class="text-align--s--center text-align--m--right"></p>
```

