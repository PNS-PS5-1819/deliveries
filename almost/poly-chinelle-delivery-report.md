
# Team poly-chinelle


## Environment

Latest commit date: `Date:   Fri Dec 21 16:43:46 2018 +0100`

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
3,4c3,4
< 1.30
< 2.30
---
> 1,30
> 2,30

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 7
> 5

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.79
< 22.57
---
> 1,79
> 22,57

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 377
> 89

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.57
< 168.85
---
> 2,57
> 168,85

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 6293
> 942

```
</details>

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
3,4c3,4
< 1.07
< 4.07
---
> 1,07
> 4,07

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 26
> 11

```
</details>

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.05
< 28.48
---
> 1,05
> 28,48

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 685
> 142

```
</details>

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.44
< 269.35
---
> 1,44
> 269,35

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 15469
> 1459

```
</details>

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

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
` ./apb.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.55
< 3.53
---
> 2,55
> 3,53

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 10
> 10

```
</details>

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.87
< 33.56
---
> 2,87
> 33,56

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 736
> 159

```
</details>

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 4.67
< 322.26
---
> 4,67
> 322,26

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 16342
> 1766

```
</details>

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
3,4c3,4
< 1.30
< 2.22
---
> 1,30
> 2,22

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 8
> 6

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
3,4c3,4
< 1.62
< 24.12
---
> 1,62
> 24,12

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 15
< 4
---
> 390
> 90

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
3,4c3,4
< 2.08
< 184.92
---
> 2,08
> 184,92

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 316
< 126
---
> 7060
> 955

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

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
` ./student_first.sh -i ../dataset/samples/sample_100_000.txt -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation


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
3,4c3,4
< 1.07
< 4.07
---
> 1,07
> 4,07

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 26
> 11

```
</details>

___
` ./student_first.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.05
< 28.48
---
> 1,05
> 28,48

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 685
> 142

```
</details>

___
` ./student_first.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.43
< 268.75
---
> 1,43
> 268,75

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 215
< 184
---
> 15834
> 1470

```
</details>

___
` ./student_first.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

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
` ./student_first.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.40
< 4.06
---
> 2,40
> 4,06

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 5
< 4
---
> 14
> 13

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
3,4c3,4
< 2.68
< 39.01
---
> 2,68
> 39,01

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 16
< 12
---
> 778
> 160

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
3,4c3,4
< 3.89
< 365.61
---
> 3,89
> 365,61

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 1155
< 305
---
> 19652
> 1769

```
</details>

___
` ./student_first.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

