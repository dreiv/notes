#Study case:

##[ViewChild](https://angular.io/docs/ts/latest/api/core/index/ViewChild-decorator.html)
You can select template elements(chidren) by using the @ViewChild  annotation together with the type of the Component that you are selected eg:

Component:
```
@Component({
    selector: 'bar-component',
    template: `<foo-component></foo-component>`
})
export class BarComponent {
  @ViewChild(FooComponent)
  private fooComponent: FooComponent;
}
```
I've read the viewchild documentation that Angular provides.
