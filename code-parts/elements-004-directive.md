
```js
@Directive({
})
class DirectiveName {
}
```
----

```js
@Directive({
  selector: '[tooltip]',
  host: {
    '(mouseover)': 'show()'
  }
})
class Tooltip {
  @Input('tooltip') text: string;

  show() {
    console.log(this.text);
  }
}
```
