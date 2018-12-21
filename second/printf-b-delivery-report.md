
|Injecting submodule| :white_check_mark:|
# Team printf-b


## Environment

Latest commit date: `Date:   Wed Dec 19 18:47:48 2018 +0100`

:boom: - TAG second

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

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.3
< 2.3
---
> 1,30000
> 2,30000

```
</details>

:white_check_mark: - Stability computed

:white_check_mark: - Stability

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.79
< 22.5657
---
> 1,79000
> 22,5657

```
</details>

:boom: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. null: NoSuchElementException -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.566
< 168.852
---
> 2,56600
> 168,852

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 1920
> 387

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 4.1222
< 1171.65
---
> 4,12220
> 1171,65

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 24297
> 4477

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

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
` ./apb.sh -i ../baseline/private/_15.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.0666666666666667
< 4.06667
---
> 1,06667
> 4,06667

```
</details>

:boom: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. null: NoSuchElementException -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.0533333333333332
< 28.48
---
> 1,05333
> 28,4800

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 21
> 7

```
</details>

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.44
< 269.347
---
> 1,44000
> 269,347

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 3950
> 382

```
</details>

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 1.4491333333333334
< 2029.12
---
> 1,44913
> 2029,12

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 43816
> 3091

```
</details>

___
` ./apb.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.55
< 3.52941
---
> 2,55000
> 3,52941

```
</details>

:boom: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. null: NoSuchElementException -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 2.87
< 33.5581
---
> 2,87000
> 33,5581

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 203
> 56

```
</details>

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 4.6715
< 322.257
---
> 4,67150
> 322,257

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 5481
> 824

```
</details>

___
` ./apb.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. Not input file -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction</summary>

```
3,4c3,4
< 5.71905
< 2316.34
---
> 5,71905
> 2316,34

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability</summary>

```
1,2c1,2
< 0
< 0
---
> 79477
> 9287

```
</details>


### StudentFirst

