# Component

```js
@Component({
  selector: 'some-component'
})
class SomeComponent {

}
```

```html
<some-component></some-component>
```
----

```js
@Component({
  selector: 'some-component'
})
@View({
  template: `<ul><li>1</li><li>2</li><li>3</li></ul>`
})
class SomeComponent {

}
```
# OR

```js
@Component({
  selector: 'some-component',
  template: `<ul><li>1</li><li>2</li><li>3</li></ul>`
})
class SomeComponent {

}
```
