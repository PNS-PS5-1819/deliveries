
# Team les-big-b


## Environment

Latest commit date: `Date:   Thu Dec 20 16:21:29 2018 +0100`

:white_check_mark: - TAG almost

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

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
ataset/solutions/solution_10.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../dataset/samples/sample_10.txt, -o, /tmp/computed-soluc-team.sol]
0 1 2 X
8 1 1 0 
1.3
2.3

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../dataset/samples/sample_10.txt, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
ataset/solutions/solution_100.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../dataset/samples/sample_100.txt, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 X
70 12 6 2 3 6 0 1 
1.79
22.565657

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../dataset/samples/sample_100.txt, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
ataset/solutions/solution_1_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../dataset/samples/sample_1_000.txt, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 X
587 134 61 36 17 38 53 21 21 9 23 
2.566
168.8516

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../dataset/samples/sample_1_000.txt, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
ataset/solutions/solution_10_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:hourglass: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../dataset/samples/sample_10_000.txt, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 13 X
5081 958 368 330 384 364 206 276 316 319 429 229 250 54 436 
4.1222
1171.649

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> Running APB process
> Args = [--stability, -i, ../dataset/samples/sample_10_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100_000.txt -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation


#### Hidden datasets

___
` ./apb.sh -i ../baseline/private/_15.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
aseline/private/gs15.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../baseline/private/_15.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 X
14 1 0 0 0 0 
1.0666667
4.0666666

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../baseline/private/_15.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
aseline/private/gs150.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../baseline/private/_150.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 X
143 6 1 0 0 0 0 0 
1.0533333
28.48

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../baseline/private/_150.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
aseline/private/gs1500.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../baseline/private/_1500.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 X
1118 190 107 84 1 0 0 0 0 0 0 0 0 0 
1.44
269.34668

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../baseline/private/_1500.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
aseline/private/gs15000.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../baseline/private/_15000.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 X
11909 2027 379 190 122 68 77 57 58 23 27 35 6 16 3 3 0 0 0 
1.4491333
2029.1251

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../baseline/private/_15000.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
aseline/private/gs20.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../baseline/private/_20.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 X
9 4 1 2 1 3 
2.55
3.5294118

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../baseline/private/_20.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
aseline/private/gs200.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../baseline/private/_200.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 X
112 19 23 7 1 3 4 3 28 
2.87
33.55814

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../baseline/private/_200.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
aseline/private/gs2000.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../baseline/private/_2000.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 X
969 234 55 43 51 89 75 38 55 55 19 66 16 27 9 199 
4.6715
322.25653

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running APB process
Args = [--stability, -i, ../baseline/private/_2000.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./apb.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
aseline/private/gs20000.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:hourglass: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running APB process
Args = [--satisfaction, -i, ../baseline/private/_20000.in, -o, /tmp/computed-soluc-team.sol]

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> Running APB process
> Args = [--stability, -i, ../baseline/private/_20000.in, -o, /tmp/computed-soluc-team.sol]

```
</details>


### StudentFirst


#### Provided datasets

___
` ./student_first.sh -i ../dataset/samples/sample_10.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../dataset/solutions/solution_10.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../dataset/samples/sample_10.txt, -o, /tmp/computed-soluc-team.sol]
0 1 2 X
9 0 0 1 
1.3
2.2222223

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../dataset/samples/sample_10.txt, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../dataset/solutions/solution_100.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../dataset/samples/sample_100.txt, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 X
78 12 0 0 3 5 1 1 
1.62
24.121212

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../dataset/samples/sample_100.txt, -o, /tmp/computed-soluc-team.sol]
15
4

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../dataset/solutions/solution_1_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../dataset/samples/sample_1_000.txt, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 X
718 105 27 29 17 35 10 3 23 1 32 
2.083
184.91736

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../dataset/samples/sample_1_000.txt, -o, /tmp/computed-soluc-team.sol]
316
126

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../dataset/solutions/solution_10_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../dataset/samples/sample_10_000.txt, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 13 X
6606 541 95 58 329 406 44 180 278 369 76 159 323 42 494 
3.5167
1274.0085

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 8400
< 2196
---
> Running Student First process
> Args = [--stability, -i, ../dataset/samples/sample_10_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_100_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../dataset/solutions/solution_100_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:hourglass: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../dataset/samples/sample_100_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 76793
< 13323
---
> Running Student First process
> Args = [--stability, -i, ../dataset/samples/sample_100_000.txt, -o, /tmp/computed-soluc-team.sol]

```
</details>


#### Hidden datasets

___
` ./student_first.sh -i ../baseline/private/_15.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../baseline/private/gs15.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../baseline/private/_15.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 X
14 1 0 0 0 0 
1.0666667
4.0666666

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../baseline/private/_15.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./student_first.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../baseline/private/gs150.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../baseline/private/_150.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 X
143 6 1 0 0 0 0 0 
1.0533333
28.48

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../baseline/private/_150.in, -o, /tmp/computed-soluc-team.sol]
0
0

```
</details>

___
` ./student_first.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../baseline/private/gs1500.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../baseline/private/_1500.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 X
1174 131 95 93 2 0 0 4 1 0 0 0 0 0 
1.4293333
268.74933

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../baseline/private/_1500.in, -o, /tmp/computed-soluc-team.sol]
215
184

```
</details>

___
` ./student_first.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../baseline/private/gs15000.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../baseline/private/_15000.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 X
12665 1572 224 87 76 16 12 11 14 18 17 36 17 123 46 14 10 13 29 
1.4809333
2028.6282

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../baseline/private/_15000.in, -o, /tmp/computed-soluc-team.sol]
3867
634

```
</details>

___
` ./student_first.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../baseline/private/gs20.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../baseline/private/_20.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 X
13 0 1 1 2 3 
2.4
4.0588236

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../baseline/private/_20.in, -o, /tmp/computed-soluc-team.sol]
5
4

```
</details>

___
` ./student_first.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../baseline/private/gs200.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../baseline/private/_200.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 X
129 19 9 6 1 1 3 2 30 
2.68
39.011765

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../baseline/private/_200.in, -o, /tmp/computed-soluc-team.sol]
16
12

```
</details>

___
` ./student_first.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../baseline/private/gs2000.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../baseline/private/_2000.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 X
1276 184 22 24 31 28 51 9 48 15 38 19 7 33 1 214 
3.889
365.60638

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student First process
Args = [--stability, -i, ../baseline/private/_2000.in, -o, /tmp/computed-soluc-team.sol]
1155
305

```
</details>

___
` ./student_first.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Exception relevée : Missing required option: i
, -b, ../baseline/private/gs20000.sol, -o, /tmp/computed-soluc-team.sol]

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student First process
Args = [--satisfaction, -i, ../baseline/private/_20000.in, -o, /tmp/computed-soluc-team.sol]
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 X
13135 1617 730 392 362 185 41 94 142 55 193 14 635 6 29 49 21 42 152 1 2105 
4.29945
2717.5698

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 14162
< 2621
---
> Running Student First process
> Args = [--stability, -i, ../baseline/private/_20000.in, -o, /tmp/computed-soluc-team.sol]

```
</details>

