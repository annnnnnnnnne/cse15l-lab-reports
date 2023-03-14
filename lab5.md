# Week 10 Lab Report 5
## Ways To Use `Find`
### 1. `find <path>`
This command lists out the files in the `<path>`.

The `<path>` here is `berlitz2`.

command:
```
$ find berlitz2
```

output:
```
berlitz2
berlitz2/Algarve-History.txt
berlitz2/Algarve-Intro.txt
berlitz2/Algarve-WhatToDo.txt
berlitz2/Algarve-WhereToGo.txt
berlitz2/Amsterdam-History.txt
berlitz2/Amsterdam-Intro.txt
berlitz2/Amsterdam-WhatToDo.txt
berlitz2/Amsterdam-WhereToGo.txt
berlitz2/Athens-History.txt
berlitz2/Athens-Intro.txt
berlitz2/Athens-WhatToDo.txt
berlitz2/Athens-WhereToGo.txt
berlitz2/Bahamas-History.txt
berlitz2/Bahamas-Intro.txt
berlitz2/Bahamas-WhatToDo.txt
berlitz2/Bahamas-WhereToGo.txt
berlitz2/Bali-History.txt
berlitz2/Bali-WhatToDo.txt
berlitz2/Bali-WhereToGo.txt
berlitz2/Barcelona-History.txt
berlitz2/Barcelona-WhatToDo.txt
berlitz2/Barcelona-WhereToGo.txt
berlitz2/Beijing-History.txt
berlitz2/Beijing-WhatToDo.txt
berlitz2/Beijing-WhereToGo.txt
berlitz2/Berlin-History.txt
berlitz2/Berlin-WhatToDo.txt
berlitz2/Berlin-WhereToGo.txt
berlitz2/Bermuda-history.txt
berlitz2/Bermuda-WhatToDo.txt
berlitz2/Bermuda-WhereToGo.txt
berlitz2/Boston-WhereToGo.txt
berlitz2/Budapest-History.txt
berlitz2/Budapest-WhatToDo.txt
berlitz2/Budapest-WhereoGo.txt
berlitz2/California-History.txt
berlitz2/California-WhatToDo.txt
berlitz2/California-WhereToGo.txt
berlitz2/Canada-History.txt
berlitz2/Canada-WhereToGo.txt
berlitz2/CanaryIslands-History.txt
berlitz2/CanaryIslands-WhatToDo.txt
berlitz2/CanaryIslands-WhereToGo.txt
berlitz2/Cancun-History.txt
berlitz2/Cancun-WhatToDo.txt
berlitz2/Cancun-WhereToGo.txt
berlitz2/China-History.txt
berlitz2/China-WhatToDo.txt
berlitz2/China-WhereToGo.txt
berlitz2/Costa-History.txt
berlitz2/Costa-WhatToDo.txt
berlitz2/Costa-WhereToGo.txt
berlitz2/CostaBlanca-History.txt
berlitz2/CostaBlanca-WhatToDo.txt
berlitz2/Crete-History.txt
berlitz2/Crete-WhatToDo.txt
berlitz2/Crete-WhereToGo.txt
berlitz2/CstaBlanca-WhereToGo.txt
berlitz2/Cuba-History.txt
berlitz2/Cuba-WhatToDo.txt
berlitz2/Cuba-WhereToGo.txt
berlitz2/Nepal-History.txt
berlitz2/Nepal-WhatToDo.txt
berlitz2/Nepal-WhereToGo.txt
berlitz2/NewOrleans-History.txt
berlitz2/Paris-WhatToDo.txt
berlitz2/Paris-WhereToGo.txt
berlitz2/Poland-History.txt
berlitz2/Poland-WhatToDo.txt
berlitz2/Portugal-History.txt
berlitz2/Portugal-WhatToDo.txt
berlitz2/Portugal-WhereToGo.txt
berlitz2/PuertoRico-History.txt
berlitz2/PuertoRico-WhatToDo.txt
berlitz2/PuertoRico-WhereToGo.txt
berlitz2/Vallarta-History.txt
berlitz2/Vallarta-WhatToDo.txt
berlitz2/Vallarta-WhereToGo.txt
```

### 2. `find -name "filename"
By adding `-name` after `find`, it will search for the given filename.

command:
```
find -name "Paris-WhatToDo.txt"
```
output:
```
./Paris-WhatToDo.txt
```

### 3. `find . -size <size>`
By adding '-size <size>`, it will search for the files that has this given size.

command:
```
find . -size 16k
```
output:
```
./Algarve-History.txt
./Algarve-WhatToDo.txt
./Amsterdam-History.txt
./Amsterdam-WhatToDo.txt
./California-WhatToDo.txt
./CanaryIslands-WhatToDo.txt
./Cancun-History.txt
./Costa-History.txt
./Crete-History.txt
```
### 4. `find -name "*<pattern>*"`
By putting "*<pattern>*", it will search the filenames that contains the `<pattern>`
command:
```
find -name "*Histo*"
```
  
ouptput:
```
./Algarve-History.txt
./Amsterdam-History.txt
./Athens-History.txt
./Bahamas-History.txt
./Bali-History.txt
./Barcelona-History.txt
./Beijing-History.txt
./Berlin-History.txt
./Budapest-History.txt
./California-History.txt
./Canada-History.txt
./CanaryIslands-History.txt
./Cancun-History.txt
./China-History.txt
./Costa-History.txt
./CostaBlanca-History.txt
```
