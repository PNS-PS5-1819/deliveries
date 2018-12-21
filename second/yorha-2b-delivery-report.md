
|Injecting submodule| :white_check_mark:|
# Team yorha-2b


## Environment

Latest commit date: `Date:   Thu Dec 20 17:08:17 2018 +0100`

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

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@24a50c76
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "2
[ERROR] "
[ERROR] -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@15dd77bd

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@585d98cb

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@24a50c76
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "X" -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@3ce8915a

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@2d2477cb

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@6cd5dcdc
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "X" -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@24a50c76

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@24a50c76

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@55dc989
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "X" -> [Help 1]
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
org.apache.commons.cli.CommandLine@7f746c72

```
</details>

:hourglass: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@3ce8915a

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

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@24a50c76
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "4
[ERROR] "
[ERROR] -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@650f0b62

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@3474b77b

```
</details>

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@585d98cb
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "6
[ERROR] "
[ERROR] -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@68e13bc7

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@63e6dade

```
</details>

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@3ce8915a
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "27
[ERROR] "
[ERROR] -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@2f21cdf6

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@24a50c76

```
</details>

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@3ce8915a
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "13
[ERROR] "
[ERROR] -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@1a60409

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@24a50c76

```
</details>

___
` ./apb.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@63e6dade
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "X" -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@24a50c76

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@650f0b62

```
</details>

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@63e6dade
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "X" -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@585d98cb

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@650f0b62

```
</details>

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:boom: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
org.apache.commons.cli.CommandLine@1a60409
[ERROR] Failed to execute goal org.codehaus.mojo:exec-maven-plugin:1.6.0:java (default-cli) on project apb: An exception occured while executing the Java class. For input string: "X" -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
org.apache.commons.cli.CommandLine@2d2477cb

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
org.apache.commons.cli.CommandLine@3ce8915a

```
</details>

___
` ./apb.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation


### StudentFirst

