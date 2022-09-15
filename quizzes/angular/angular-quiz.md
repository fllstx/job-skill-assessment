## Angular

### What is the correct template syntax for using the built-in ngFor structural directive to render out a list of productNames?

- [ ]

```html
<ul>
  <li [ngFor]="let productName of productNames">{{ productName }}</li>
</ul>
```

- [ ]

```html
<ul>
  <li ngFor="let productName of productNames">{{ productName }}</li>
</ul>
```

- [checked ]

```html
<ul>
  <li *ngFor="let productName of productNames">{{ productName }}</li>
</ul>
```

- [ ]

```html
<ul>
  <? for productName in productNames { ?>
  <li>{{ productName }}</li>
  <? } ?>
</ul>
```

### Finish this markup using the `ngIf` directive to implement an else case that will display the text "User is not active":

```angular2html
<div *ngIf="userIsActive; else inactive">
  Currently active!
</div>
```

- [ ]

```angular2html
<div #inactive>
  User is not active.
</div>
```

- [ ]

```angular2html
<div *ngIf="inactive">
  User is not active.
</div>
```

- [ ]

```angular2html
<ng-template #else="inactive">
  <div>User is not active.</div>
</ng-template>
```

- [checked ]

```angular2html
<ng-template #inactive>
  <div>User is not active.</div>
</ng-template>
```

### What is the purpose of the ViewChild decorator in this component class?

```angularjs
@Component({
    ...
    template: '<p #bio></p>'
})
export class UserDetailsComponent {
    @ViewChild('bio') bio;
}
```

- [checked ] It provides access from within the component class to the ElementRef object for the `<p>` tag that has the bio template reference variable in the component's template view.
- [ ] It indicates that the `<p>` tag be rendered as a child of the parent view that uses this component.
- [ ] It makes the `<p>` tag in the template support content projection.
- [ ] It makes the `<p>` tag visible in the final render. If the #bio was used in the template and the @ViewChild was not used in the class, then Angular would automatically hide the `<p>` tag that has #bio on it.

### What are the two component decorator metadata properties used to set up CSS styles for a component?

- [ ] viewEncapsulation and viewEncapsulationFiles.
- [ ] There is only one and it is the property named css.
- [ ] css and cssUrl.
- [checked ] styles and styleUrls.

### Based on the following usage of the async pipe, and assuming the users class field is an Observable, how many subscriptions to the users Observable are being made?

```html
<h2>Names</h2>
<div *ngFor="let user of users | async">{{ user.name }}</div>
<h2>Ages</h2>
<div *ngFor="let user of users | async">{{ user.age }}</div>
<h2>Genders</h2>
<div *ngFor="let user of users | async">{{ user.gender }}</div>
```

- [ ] None. The async pipe does not subscribe automatically.
- [ ] None. The template syntax is not correct.
- [checked ] Three. There is one for each async pipe.
- [ ] One. The async pipe caches Observables by type internally.

### What is the RouterModule.forRoot method used for?

- [ ] Registering any providers that you intend to use in routed components.
- [checked] Registering route definitions at the root application level.
- [ ] Indicating that Angular should cheer on your routes to be successful.
- [ ] Declaring that you intend to use routing only at the root level.

### With the following component class, what template syntax would you use in the template to display the value of the title class field?

```javascript
@Component({
  selector: 'app-title-card',
  template: '___',
})
class TitleCardComponent {
  title = 'User Data';
}
```

- [ ] `{{ 'title' }}`
- [checked ] `{{ title }}`
- [ ] `[title]`
- [ ] A class field cannot be displayed in a template via the template syntax.

### What directive is used to link an `<a>` tag to routing?

- [ ] routeTo
- [checked ] routerLink
- [ ] routePath
- [ ] appLink

### Based on the following component, what template syntax would you use to bind the TitleCardComponent's titleText field to the h1 element title property?

```javascript
@Component({
  selector: 'app-title-card',
  template: '<h1 title="User Data"> {{titleText}}</h1>',
})
export class TitleCardComponent {
  titleText = 'User Data';
}
```

- [ ] `<h1 data-title="titleText">{{ titleText }}</h1>`
- [ ] `<h1 title="titleText">{{ titleText }}</h1>`
- [checked ] `<h1 [title]="titleText">{{ titleText }}</h1>`
- [ ] `<h1 titleText>{{ titleText }}</h1>`


### Pick the best description for this template syntax code:

```html
<span>Boss: {{job?.bossName}} </span>
```

- [ ] The ? is shorthand for the async pipe. The job value must be an Observable.
- [ ] It is using the safe navigation operator (?) on the job field. If the job field is undefined, the access to the bossName will be ignored and no error will occur.
- [checked ] There is an error in the template syntax. The ? is not valid here.
- [ ] It is diplaying the job value if it has one; otherwise it is displaying the bossName.

### What are the HostListener decorators and the HostBinding decorator doing in this directive?

```javascript
@Directive({
  selector: '[appCallout]',
})
export class CalloutDirective {
  @HostBinding('style.font-weight') fontWeight = 'normal';

  @HostListener('mouseenter')
  onMouseEnter() {
    this.fontWeight = 'bold';
  }

  @HostListener('mouseleave')
  onMouseLeave() {
    this.fontWeight = 'normal';
  }
}
```

- [ ] They are setting the CalloutDirective.fontWeight field based on whether or not the mouse is over the DOM element. The HostListener then sets the font-weight CSS property to the fontWeight value.
- [ ] They are setting up the directive to check the DOM element that it is on. If it has event bindings added for mouse enter and leave it will use this code. Otherwise nothing will happen.
- [ ] This is an incorrect use of HostListener and HostBinding. The HostListener and HostBinding decorators do not do anything on directives; they work only when used on components.
- [ ] If the DOM element that this directive is placed on has the CSS property font-weight set on it, the mouseenter and mouseleave events will get raised.

### What is the purpose of the ContentChildren decorator in this component class?

```javascript
@Component({
 . . .
 template: '<ng-content></ng-content›'
})
export class TabsListComponent {
 @ContentChildren(TabComponent) tabs;
}
```

- [ ] If any _TabsComponent_ elements are added to the _TabsListComponent_ template, they will get put into the <ng-content> element at runtime.
- [ ] It creates _TabComponent_ components in the _TabsListComponent_ template when a _TabsListComponent_ is instantiated.
- [ ] It provides access from within the component class to any _TabComponent_ components that were content projected into the <ng-content> for this component.
- [ ] It restricts the allowed elements that can be put into a _TabsListComponent_ element to allow only _TabComponent_ elements.

### In order for Angular to process components in an application, where do the components need to be registered?

- [ ] within a script tag in the index.html file
- [ ] in an NgModule decorator metadata tag named _components_
- [ ] No registration is needed simply include the component files in an app directory.
- [checked ] in an NgModule decorator metadata property named _declarations_

### What is the HostBinding decorator doing in this directive?

```javascript
@Directive({
  selector: ' [appHighlight] ',
})
export class HighlightDirective {
  @HostBinding('class.highlighted') highlight = true;
}
```

- [ ] It is adding the CSS class named highlighted to any DOM element that has the appHighlight directive on it.
- [ ] HostBinding does not do anything on directives, only on components.
- [ ] It is specifying if the host element gets the highlighted class added to its class attribute, then the directive class field highlight will get set to true; and if it is not added on the host it will get set to false.
- [ ] It is creating an inline style on the host element with a CSS property named highlight set to true.

### When a service requires some setup to initialize its default state through a method, how can you make sure that said method is invoked before the service gets injected anywhere?

- [checked ] Put the logic of that service method into the service constructor instead.
- [ ] Use a factory provider at the root AppModule level that depends on the service to call that service method.
- [ ] it is not possible to do it at application start; you can do it only at a component level.
- [ ] Instantiate an instance of the service at the global level (window scope) and then call that method.

### What is an alternative way to write this markup to bind the value of the class field `userName` to the `h1` element title property?

```html
<h1 [title]="userName">Current user is {{ userName }}</h1>
```

- [ ] title="userName"
- [ ] title="{{ userName }}"
- [ ] title="{{ 'userName' }}"
- [checked ] The only way to do it is by using the square brackets.
