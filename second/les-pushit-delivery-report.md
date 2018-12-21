
|Injecting submodule| :white_check_mark:|
# Team les-pushit


## Environment

Latest commit date: `Date:   Thu Dec 20 17:50:20 2018 +0100`

:white_check_mark: - TAG second

:white_check_mark: - 0 `.class` files

:white_check_mark: - 0 `.DS_Store` files

:white_check_mark: - 0 `.idea` folders

:white_check_mark: - 0 `target` folders

:white_check_mark: - 0 `.iml` files

:white_check_mark: - 0 `conflict marker` found

:white_check_mark: - Compilation

:white_check_mark: - Tests

:white_check_mark: - Module [commons]

:white_check_mark: - Module [commons] has a pom description

:white_check_mark: - Module [commons] declared as a maven module


## Business features

### APB

#### Provided datasets

___
` ./apb.sh -i ../dataset/samples/sample_10.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 2
Done
Result : 
 0 1 2 X
 8 1 1 0
1.3
2.3

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 2
Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 7
...................................................................................................Done
Result : 
  0  1  2  3  4  5  6  X
 70 12  6  2  3  6  0  1
1.79
22.565656565656564

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 9
...................................................................................................Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 39
...................................................................................................Done
Result : 
   0   1   2   3   4   5   6   7   8   9  X
 587 134  61  36  17  38  53  21  21   9  23
2.56
168.8515864892528

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 41
...................................................................................................Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 230
...................................................................................................Done
Result : 
    0    1    2    3    4    5    6    7    8    9   10   11   12   13   X
 5081  958  368  330  384  364  206  276  316  319  429  229  250   54  436
4.12
1171.6491007946465

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 231
...................................................................................................Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:hourglass: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 1361
.......................................................................
```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 1410
.......................................................................
```
</details>


#### Hidden datasets

___
` ./apb.sh -i ../baseline/private/_15.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 3
Done
Result : 
 0 1 2 3 4 X
14 1 0 0 0 0
1.06
4.066666666666666

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 3
Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 11
...................................................................................................Done
Result : 
  0  1  2  3  4  5  6  X
143  6  1  0  0  0  0  0
1.05
28.48

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 10
...................................................................................................Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 67
...................................................................................................Done
Result : 
   0   1   2   3   4   5   6   7   8   9  10  11  12  X
1118 190 107  84   1   0   0   0   0   0   0   0   0   0
1.44
269.3466666666667

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 70
...................................................................................................Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 396
...................................................................................................Done
Result : 
    0    1    2    3    4    5    6    7    8    9   10   11   12   13   14   15   16   17   X
11909 2027  379  190  122   68   77   57   58   23   27   35    6   16    3    3    0    0    0
1.44
2029.125

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 330
...................................................................................................Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 3
Done
Result : 
 0 1 2 3 4 X
 9 4 1 2 1 3
2.55
3.5294117647058822

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 3
Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 14
...................................................................................................Done
Result : 
  0  1  2  3  4  5  6  7  X
112 19 23  7  1  3  4  3 28
2.87
33.55813953488372

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 15
...................................................................................................Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 95
...................................................................................................Done
Result : 
   0   1   2   3   4   5   6   7   8   9  10  11  12  13  14  X
 969 234  55  43  51  89  75  38  55  55  19  66  16  27   9 199
4.67
322.2565241532482

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 82
...................................................................................................Done
Result : 
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Done
Result : 
1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Parsing time: 456
...................................................................................................Done
Result : 
    0    1    2    3    4    5    6    7    8    9   10   11   12   13   14   15   16   17   18   19   X
 8682 2556 1710  773  439  414  229  207  252  186  332  199  318  260  204  529  293   80  220   97 2020
5.71
2316.335428253615

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Parsing time: 458
...................................................................................................Done
Result : 
0
0

```
</details>


### StudentFirst

