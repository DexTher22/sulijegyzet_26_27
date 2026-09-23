# 2026-09-02

vizsgaremek
git humer_api
git humer_frontend

Angular
signal - több helyről is elérhető

position, employee component

position.component
position.service

ng g c position --type component
ng g s position --type service

# 26-09-09

régen *ngIf
ma: @if
@if() {} @else {}

ng g s services/empapi --type service

új mappa - interface
employees.ts

interface Employee() {
	id: number,
	name: string,
	...
}

empService = inject(EmpapiService)
empList!: Employee[]
this.empList = this.empService.getEmployees()



_Szolgáltatás gyakorlat_
ng new szoli


# 2026-09-16

## urlap/

<button></button>
type="submit"
type="button"
type="reset" -- formban kitörli az összes elemet

### Form összekötése

app.ts
```
export class App {
  protected readonly title = signal('urlap');

  name : string = 'asdf';
  onStart() {
    console.log('Műkszik...')
    console.log(this.name)
    this.name = 'pali'
    console.log(this.name)
  }
}
```
app.html
```
<form (ngSubmit)="onStart()" >
  <div>
    <label for="name">Név</label>
    <input id="name" type="text" [(ngModel)]="name" name="name" >
  </div>
  <div>
    <button type="submit" >Küld</button>
  </div>
</form>
```


### Legördülő mező for ciklussal

html
```
<label for="city">Település</label>
  <select name="city" id="city" [(ngModel)]="city" name="city">
    @for(city of cities ; track city.id ) {
      <option value="{{city.id}}">{{city.name}}</option>
    }
  </select>
```

## signup/  -- regisztrációs felület
 https://github.com/DexTher22/signup_page_gyak
 
 
#2026-09-23

## /loginha

https://github.com/DexTher22/loginha

### Dolgozat:  

?  

### Gyakorlás:
Feladat 302

https://github.com/DexTher22/gula_feladat_302

















