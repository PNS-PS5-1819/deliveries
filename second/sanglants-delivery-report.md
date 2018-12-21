

# Team sanglants


## Environment

Latest commit date: `Date:   Thu Dec 20 18:13:55 2018 +0100`

:white_check_mark: - TAG second

:white_check_mark: - 0 `.class` files

:white_check_mark: - 0 `.DS_Store` files

:white_check_mark: - 0 `.idea` folders

:white_check_mark: - 0 `target` folders

:white_check_mark: - 0 `.iml` files

:white_check_mark: - 0 `conflict marker` found

:white_check_mark: - Compilation

:white_check_mark: - Tests

:boom: - Module [commons]

:boom: - Module [commons] has a pom description

:boom: - Module [commons] declared as a maven module


## Business features

### APB

#### Provided datasets

___
` ./apb.sh -i ../dataset/samples/sample_10.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 0
---
> 1

```
</details>

:white_check_mark: - Satisfaction computed

:white_check_mark: - Satisfaction

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 0
---
> 1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.79
< 22.5657
---
> 1.78
> 13.2

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 2
---
> 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.558
< 168.861
---
> 2.535
> 73.8

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 37
---
> 38

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 4.1172
< 1172.04
---
> 4.0729
> 413.8

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

<details><summary>:boom: Distance</summary>

```
1c1
< 0
---
> 1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.0666666666666667
< 4.06667
---
> 1.0666667
> 4.0

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 0
---
> 1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.0533333333333332
< 28.48
---
> 1.0533333
> 16.8

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 0
---
> 1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
4c4
< 269.347
---
> 156.8

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 0
---
> 1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.4491333333333334
< 2029.12
---
> 1.4491333
> 960.5

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

<details><summary>:boom: Distance</summary>

```
1c1
< 2
---
> 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.5
< 4
---
> 2.35
> 4.7

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 0
---
> 1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.87
< 33.5581
---
> 2.73
> 18.9

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 14
---
> 15

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 4.6525
< 322.415
---
> 4.553
> 158.8

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

<details><summary>:boom: Distance</summary>

```
1c1
< 2
---
> 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.3
< 2.22222
---
> 1.2
> 1.7

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

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
< 1.65
< 24.1717
---
> 1.64
> 13.6

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

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
< 2.175
< 182.607
---
> 2.143
> 77.6

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./student_first.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 3717
---
> 3718

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 3.5856
< 1283.73
---
> 3.5363
> 470.6

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

<details><summary>:boom: Distance</summary>

```
1c1
< 0
---
> 1

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.0666666666666667
< 4.06667
---
> 1.0666667
> 4.0

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./student_first.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 2
---
> 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.0533333333333332
< 28.4667
---
> 1.0533333
> 16.8

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./student_first.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 243
---
> 244

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.4246666666666667
< 270.299
---
> 1.4246666
> 156.1

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
3,4c3,4
< 1.4628666666666668
< 2028.9
---
> 1.4614667
> 961.4

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
< 2.35
< 5.76471
---
> 2.2
> 5.8

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

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
< 2.71
< 39.6213
---
> 2.555
> 22.0

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

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
< 3.9565
< 368.908
---
> 3.851
> 184.4

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./student_first.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

<details><summary>:boom: Distance</summary>

```
1c1
< 9145
---
> 9146

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 4.45685
< 2716.22
---
> 4.35115
> 1158.9

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```

```
</details>

