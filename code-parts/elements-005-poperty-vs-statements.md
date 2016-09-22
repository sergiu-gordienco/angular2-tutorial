```html
<my-directive [foo]="something"></my-directive>
```
# vs

```html
<my-directive (select)="user.name(name)"></my-directive>
```
