# C++ Snippets 👓

Ugh, tired of writing same code again and again in c++, well if you're using Vscode we
have ***snippets*** for you.

## Installation
### Follow given steps to get snippets work
- Open your VS code Editor.
- Press `ctrl+shift+p` or `cmd+shift+p` and search for snippets.
- Select "Preferences: Configure User Snippets".
- then, type "New Global Snippets file" and select that.
- type file name as you're desire but, for now let's go with "cppSnippets".
- now go to this [link](https://github.com/its-kunal/CPP_snippets/blob/master/.vscode/cppSnippets.code-snippets) and copy and paste the code.
- save the file and you're good to go.
---
## Basic Templates
Now after following above steps you just need to type snippets prefix and wallah 😎.
<br/>
*for example*

``` cpp
// "iiom","mi","#include","main" type this to get a template with including iostream library
// iiom --> include iostream and main function
#include <iostream>
using namespace std;
int main()
{
    /* code */
    return 0;
}
```

``` cpp
// "ibm", "mi", "main","#include" type this to get a template with stdc++ included from bits within main function
// ibm --> include bits and main function
#include <bits/stdc++.h>
using namespace std;
int main()
{
    /* code */
    return 0;
}
```

```cpp
// "itc" for input test case template as for
// competitive programming or problems
int t;
cin >> t;
while (t--)
{
    // Code
}
```

## Nested ***For-Loop***, ***if***, ***if-else*** templates
*for example*

```cpp
// "for_2", "f_2" type this to get nested two for loops
// for_2 , f_2 --> two nested for loops
for (int i = 0; i < n; i++)
{
    for (int j = 0; j < m; j++)
    {
        // code
    }
    /*code*/ // pointer comes here at the end
}
```

```cpp
// "for_3", "f_3" type this to get nested three for loops
// for_3 , f_3 --> three nested for loops
for (int i; i < n; i++)
{
    for (int j; j < m; j++)
    {
        for (int k; k < o; k++)
        {
            // code
        }
        // code
    }
    // code // Pointer comes here at the end
}
```

```cpp
if (/*condition 1*/)
{
    if (/*condition 2*/)
    {
        /*code*/
    }
    /*code*/ // pointer comes here at the end
}
```

```cpp
// "if_3" type this to get nested if template
// if_3 --> three times nested if
if (/*condition 1*/)
{
    if (/*condition 2*/)
    {
        if (/*condition 3*/)
        {
            /*code*/
        }
        /*code*/
    }
    /*code*/ // pointer comes here at the end
}
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)