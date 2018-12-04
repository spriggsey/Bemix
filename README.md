# Bemix
## BEM style mixins for Sass

###Installation
via NPM:
`npm install spriggsey/bemix`

In your SCSS:
```scss
@import "~bemix";
```

###Usage

```scss
@include b('block') {
    ...
    
    @include e('element') {
        ...
    }
    
    @include m('modifier') {
        ...
    }
    
    @include s('active') {
        ...
    }
}
```

#### Outputs
```css
.block {
  ...
}
.block .__element {
  ...
}
.block.--modifier {
  ...
}
.block.is-active {
  ...
}
```
