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

urlap/

<button></button>
type="submit"
type="button"
type="reset" -- formban kitörli az összes elemet

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



















