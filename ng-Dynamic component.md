#Study case:

##[ViewChild](https://angular.io/docs/ts/latest/api/core/index/ViewChild-decorator.html)
You can select template elements(chidren) by using the @ViewChild  annotation together with the type of the Component that you are selected eg:

Template:
```
<foo-component></foo-component>
```
Component:
```
export class BarComponent {
  @ViewChild(FooComponent)
  private fooComponent: FooComponent;
}
```
