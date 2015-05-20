# rowlow.type.text-align
This text util helps you to fully control text aligns amog all responsive breakpoints.

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
    {rowlow-text-align-namespace}text-align--{breakpoint-name}--{left, right, center, justify}
```


### HTML
```
    <p class="text-align--s--center text-align--m--right"></p>
```

