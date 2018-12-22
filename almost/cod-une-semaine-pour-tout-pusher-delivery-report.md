
# Team cod-une-semaine-pour-tout-pusher


## Environment

Latest commit date: `Date:   Fri Dec 21 16:25:17 2018 +0100`

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

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 X
---
> 0 1 2 x
3,4c3,4
< 1.30
< 2.30
---
> 1.0
> 2.9

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 X
---
> 0 1 2 3 4 5 6 x
3,4c3,4
< 1.79
< 22.57
---
> 2.0
> 38.86

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 X
---
> 0 1 2 3 4 5 6 7 8 9 x
3,4c3,4
< 2.57
< 168.85
---
> 2.0
> 426.83

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:hourglass: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```

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

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 X
---
> 0 1 2 3 4 x
3,4c3,4
< 1.07
< 4.07
---
> 1.0
> 5.2

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 X
---
> 0 1 2 3 4 5 6 x
3,4c3,4
< 1.05
< 28.48
---
> 1.0
> 58.47

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 10 11 12 X
---
> 0 1 2 3 4 5 6 7 8 9 10 11 12 x
3,4c3,4
< 1.44
< 269.35
---
> 1.0
> 669.28

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 X
---
> 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 x
3,4c3,4
< 1.45
< 2029.12
---
> 1.0
> 6929.7

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```

```
</details>

___
` ./apb.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 X
---
> 0 1 2 3 4 x
3,4c3,4
< 2.55
< 3.53
---
> 2.0
> 6.3

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 X
---
> 0 1 2 3 4 5 6 7 x
3,4c3,4
< 2.87
< 33.56
---
> 2.0
> 72.69

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 X
---
> 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 x
3,4c3,4
< 4.67
< 322.26
---
> 3.0
> 829.82

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation


### StudentFirst


#### Provided datasets

___
` ./student_first.sh -i ../dataset/samples/sample_10.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 X
---
> 0 1 2 x
3,4c3,4
< 1.30
< 2.22
---
> 1.0
> 2.3

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 1
> 1

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 X
---
> 0 1 2 3 4 5 6 x
3,4c3,4
< 1.62
< 24.12
---
> 2.0
> 38.12

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 15
< 4
---
> 20
> 5

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 X
---
> 0 1 2 3 4 5 6 7 8 9 x
3,4c3,4
< 2.08
< 184.92
---
> 2.0
> 421.87

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 316
< 126
---
> 547
> 158

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 10 11 12 13 X
---
> 0 1 2 3 4 5 6 7 8 9 10 11 12 13 x
3,4c3,4
< 3.52
< 1274.01
---
> 3.0
> 4298.22

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_100_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:hourglass: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```

```
</details>


#### Hidden datasets

___
` ./student_first.sh -i ../baseline/private/_15.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 X
---
> 0 1 2 3 4 x
3,4c3,4
< 1.07
< 4.07
---
> 1.0
> 5.2

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./student_first.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 X
---
> 0 1 2 3 4 5 6 x
3,4c3,4
< 1.05
< 28.48
---
> 1.0
> 58.47

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./student_first.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 10 11 12 X
---
> 0 1 2 3 4 5 6 7 8 9 10 11 12 x
3,4c3,4
< 1.43
< 268.75
---
> 1.0
> 668.72

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./student_first.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 X
---
> 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 x
3,4c3,4
< 1.48
< 2028.63
---
> 1.0
> 6920.65

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```

```
</details>

___
` ./student_first.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 X
---
> 0 1 2 3 4 x
3,4c3,4
< 2.40
< 4.06
---
> 2.0
> 5.95

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 5
< 4
---
> 8
> 7

```
</details>

___
` ./student_first.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 X
---
> 0 1 2 3 4 5 6 7 x
3,4c3,4
< 2.68
< 39.01
---
> 2.0
> 72.28

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 16
< 12
---
> 126
> 42

```
</details>

___
` ./student_first.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 X
---
> 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 x
3,4c3,4
< 3.89
< 365.61
---
> 2.0
> 829.51

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 1155
< 305
---
> 2873
> 513

```
</details>

___
` ./student_first.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
1c1
< 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 X
---
> 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 x
3,4c3,4
< 4.30
< 2717.57
---
> 2.0
> 8361.8

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```

```
</details>

