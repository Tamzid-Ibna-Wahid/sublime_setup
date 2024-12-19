# Windows setup
## To pre_compile header file <bits/stdc++.h>

Step 1 : go to ->  C:\MinGW\lib\gcc\mingw32\6.3.0\include\c++\mingw32\bits this path 
Step 2 : Open terminal 
Step 3 : run ( g++ -std=c++17 stdc++.h ) this command
Step 4 : for details watch https://www.youtube.com/watch?v=ynHKYjBpzBw this video



## To use order set
- Usethis two header file ->
 #include<ext/pb_ds/assoc_container.hpp>  
#include<ext/pb_ds/tree_policy.hpp>
- Use this -> using namespace __gnu_pbds;
- Use this -> 
typedef tree<int, null_type, less<int>, rb_tree_tag, tree_order_statistics_node_update> pbds;  // less ,less_equal , greater, greater_equal, cmp, *a.find_by_order() , order_of_key()
- If the compile error comes then go this path -> C:\MinGW\lib\gcc\mingw32\6.3.0\include\c++\ext\pb_ds\detail\resize_policy
- In this path you can see a file with .h0045 . just remove the number after the 'h' and you are good to go.
- for more details watch this -> https://www.youtube.com/watch?v=IWyIwLFucU4&t=303s
- Read this -> https://codeforces.com/blog/entry/11080

# Debug file
- Go to my Code_library reporsitory there you can find a debug.h file copy it and paste it in the directory where the cpp file is
- in the cpp file include this things ->
#ifndef ONLINE_JUDGE
#include "debug.h"
#else
#define deb(x)
#endif
- you are good to go

# For sublime setup
- Go this path ->  C:\Users\tamzi\AppData\Roaming\Sublime Text\Packages\User
- paste all file
