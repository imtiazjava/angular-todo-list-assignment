# angular-todo-list-assignment


Develop the TO-DO-LIST-OF-TASK application by using Angular:
---------------------------------------------------------------

- STEP 1 : Create a new todo-list-app application.

- STEP 2 : Inside the app.component.html write the code by using following template:


```
app.component.ts

import { analyzeAndValidateNgModules } from '@angular/compiler';
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
   styleUrls: ['./app.component.css'],
  

})
 export class AppComponent {
   title:string='TO-DO-TASKS';
   listTask:any[]=[];
   addTask(task:any):void{
     //write the code here
   }

   deleteItem(id:any):void{
     //write the code here
   }
}

```

```
app.component.html

<h1>{{ title }}</h1>
<hr />
<div class="c1">
   <!-- write the code here-->
</div>
<hr />
 
 
    <table>
        <tr>
            <th>TASK</th>
            <th>ACTION</th>
        </tr>
         <!-- write the code here-->
    </table>
 

```
```
app.component.css
h1{  
}

.c1{
    
}

input{
     
}

button{
   
}
.c2{
    
}

ul{
    
}

table,th,td{
   
}

.b1{
    
}

```
--------------------------------------------------------------

- STEP3 : Execute the code :
      ng serve -o
      
- http://localhost:4200/

![image](https://user-images.githubusercontent.com/26134506/191482284-e0c5278d-e92f-44a4-ae9b-9e9c1e50758d.png)


- STEP4: After adding the taks:

![image](https://user-images.githubusercontent.com/26134506/191482449-c6c1323b-2aa7-4189-a7ea-703c1298e732.png)

- STEP5 : After deleting 2 task:
![image](https://user-images.githubusercontent.com/26134506/191482570-06ed3f22-32de-4d46-b6d5-fa947d89d97c.png)



