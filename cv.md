## _Ganisher Khamrayev_

---

### Contacts

- Number +998992348954
- Discor Ganisher (@GanisherHam)
- Gmail ganisherkhamrayev@gmail.com

---

### About Me

I'm from Uzbekistan. I live in Tashkent.
I'm very excting in becoming challenges and being this part of family 'Rs-school'.
I'm trainee web developer

---

## Code examples

### Add and delete function from array

```
let arr = [];
for(i = 0; i  Infinity; i++){
    a = prompt(`Вы можете добавить ползователей add, имя. Через del, имя вы можете удалить ползователя, если напишите stop функция остановится`);
    b = a.split(' ');
    if(b[0] == 'add'  b[0] == 'add,'){
        arr.push(b[1])
        console.log('элемент ' + b[1]);
    }else if(b[0] == 'del'  b[0] == 'del,'){
        for(let key in arr){
            if(b[1] == arr[key]){
                arr.splice(key, 1)
                console.log('удалил ' + b[1]);
            }else if(b[1] != arr[key]){
                console.log(`Несуществуеший ползовать ${b[1]}`);
            }
        }
    }
    if(a == 'stop'  a == 'Stop'){
        break;
    }
}
console.log(arr);
```