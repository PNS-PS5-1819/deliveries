
|Injecting submodule| :boom:|
# Team poly-chinelle


## Environment

Latest commit date: `Date:   Thu Dec 20 19:28:47 2018 +0100`

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

:white_check_mark: - Satisfaction

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 5
> 4

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
4c4
< 22.5657
---
> 22.565657

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 366
> 91

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
4c4
< 170.543
---
> 170.54292

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 6669
> 959

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
< 1.0666666666666667
< 4.06667
---
> 1.0666667
> 4.0666666

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 31
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
3c3
< 1.0533333333333332
---
> 1.0533333

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 633
> 145

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
4c4
< 269.347
---
> 269.34668

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 14736
> 1480

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
4c4
< 3.94118
---
> 3.9411764

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 4
< 4
---
> 22
> 15

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
4c4
< 33.9826
---
> 33.98256

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 1
< 1
---
> 800
> 165

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
4c4
< 325.29
---
> 325.28983

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 149
< 135
---
> 20323
> 1791

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
4c4
< 2.22222
---
> 2.2222223

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 4
> 3

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
4c4
< 24.2727
---
> 24.272728

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 18
< 4
---
> 303
> 74

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
4c4
< 185.111
---
> 185.11066

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 309
< 125
---
> 7039
> 959

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
< 1.0666666666666667
< 4.06667
---
> 1.0666667
> 4.0666666

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 31
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
3c3
< 1.0533333333333332
---
> 1.0533333

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 633
> 145

```
</details>

___
` ./student_first.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:white_check_mark: - Distance computed

:white_check_mark: - Distance

:white_check_mark: - Satisfaction computed

:white_check_mark: - Satisfaction

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 213
< 186
---
> 13232
> 1480

```
</details>

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
< 1.4834666666666667
< 2030.61
---
> 1.4834666
> 2030.6158

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
4c4
< 4.05882
---
> 4.0588236

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 6
< 4
---
> 24
> 15

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
4c4
< 39.0235
---
> 39.02353

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 16
< 12
---
> 709
> 163

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
4c4
< 365.776
---
> 365.77628

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 1174
< 314
---
> 21453
> 1778

```
</details>

___
` ./student_first.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

