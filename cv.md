#Mozgovoy Anton

##About me:  
_I'm loving code. I like to solve problems, find new non-standard solutions. I want to be a useful person, learn, and mean something._

###Skills:

- HTML;
- CSS;
- JavaScript(in process);
- React (in process);

###Code examples:

```
function duplicateCount(str) {
  let a = 0;
  let massiv = [];
  let b = str.toLowerCase();
  let t = b.split('');
  function filterItems(query) {
    return t.filter(function(el) {
        return el.indexOf(query) > -1;
    })
  }
  for (let key of t){
      a = filterItems(key);
        if (a.length > 1 && massiv.indexOf(key) < 0){
           massiv.push(key);
        }
  }
  return massiv.length;
}
```

###Contact:
VK: [Solarios](https://vk.com/id6659601);
Github: [Solarkas](https://github.com/Solarkas);
e-mail: [G-mail](vseigru@gmail.com);
Discord nickname: Antony (@Solarkas)

```

```
