
|Injecting submodule| :white_check_mark:|
# Team firewall-vs-yellow-vests-b


## Environment

Latest commit date: `Date:   Thu Dec 20 19:57:55 2018 +0100`

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

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 X
8 1 1 0
1.3
2.3
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 X
70 12 6 2 3 6 0 1
1.79
22.34
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 7 8 9 X
587 134 61 36 17 38 53 21 21 9 23
2.566
164.968
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 7 8 9 10 11 12 13 X
5081 958 368 330 384 364 206 276 316 319 429 229 250 54 436
4.1222
1120.5652
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


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

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 X
14 1 0 0 0 0
1.0666667
4.0666666
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 X
143 6 1 0 0 0 0 0
1.0533333
28.48
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 7 8 9 10 11 12 X
1118 190 107 84 1 0 0 0 0 0 0 0 0 0
1.44
269.34668
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 X
11909 2027 379 190 122 68 77 57 58 23 27 35 6 16 3 3 0 0 0
1.4491333
2029.1248
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 X
9 4 1 2 1 3
2.55
3.0
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 7 X
112 19 23 7 1 3 4 3 28
2.87
28.86
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 X
969 234 55 43 51 89 75 38 55 55 19 66 16 27 9 199
4.6715
290.192
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>

___
` ./apb.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 X
8682 2556 1710 773 439 414 229 207 252 186 332 199 318 260 204 529 293 80 220 97 2020
5.71905
2082.3857
```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
0
0


```
</details>


### StudentFirst

