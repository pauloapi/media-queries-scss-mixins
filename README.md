# media-queries-scss-mixins
Media Queries SCSS Mixins based on Angular FlexLayout

### Installation
Download and include `custom-queries.scss`.

```scss
@import 'custom-queries.scss';
```

### Example
```scss
.container {
  @include xs {
    background: blue;
  }
  
  @include gt-md {
    color: green
  }
}
```
Demo: [Stackblitz](https://stackblitz.com/edit/angular-utnmic?file=src%2Fapp%2Fapp.component.scss)

### MediaQueries and Aliases
You can associate breakpoints with mediaQuery definitions using breakpoint alias(es):

| Breakpoint | Media Query |
| :----: | ------ |
| xs | 'screen and (max-width: 599px)' |
| sm |'screen and (min-width: 600px) and (max-width: 959px)' |
| md | 'screen and (min-width: 960px) and (max-width: 1279px)' |
| lg |'screen and (min-width: 1280px) and (max-width: 1919px)' |
| xl |	'screen and (min-width: 1920px) and (max-width: 5000px)' |
| | |
| lt-sm |	'screen and (max-width: 599px)' |
| lt-md |	'screen and (max-width: 959px)' |
| lt-lg |	'screen and (max-width: 1279px)' |
| lt-xl |	'screen and (max-width: 1919px)' |
| | |
| gt-xs |	'screen and (min-width: 600px)' |
| gt-sm |	'screen and (min-width: 960px)' |
| gt-md |	'screen and (min-width: 1280px)' |
| gt-lg |	'screen and (min-width: 1920px)' |

Reference: [Angular Flex Layout MediaQueries](https://github.com/angular/flex-layout/wiki/Responsive-API#mediaqueries-and-aliases)
