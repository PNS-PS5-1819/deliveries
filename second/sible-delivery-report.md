
|Injecting submodule| :white_check_mark:|
# Team sible


## Environment

Latest commit date: `Date:   Thu Dec 20 00:56:48 2018 +0100`

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

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--distance, -b, ../dataset/solutions/solution_10.txt, -o, /tmp/computed-soluc-team.sol]
Cheated solution used as input for metrics computations : exit code 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--satisfaction, -i, ../dataset/samples/sample_10.txt, -o, /tmp/computed-soluc-team.sol]
0     1     2     X
8     1     1     0
1.3
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  0.449 s
[INFO] Finished at: 2018-12-20T23:18:40+01:00
[INFO] ------------------------------------------------------------------------

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--stability, -i, ../dataset/samples/sample_10.txt, -o, /tmp/computed-soluc-team.sol]
0
0
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  0.443 s
[INFO] Finished at: 2018-12-20T23:18:41+01:00
[INFO] ------------------------------------------------------------------------

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--distance, -b, ../dataset/solutions/solution_100.txt, -o, /tmp/computed-soluc-team.sol]
Cheated solution used as input for metrics computations : exit code 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--satisfaction, -i, ../dataset/samples/sample_100.txt, -o, /tmp/computed-soluc-team.sol]
0     1     2     3     4     5     6     X
70     12     6     2     3     6     0     1
1.79
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  0.428 s
[INFO] Finished at: 2018-12-20T23:18:46+01:00
[INFO] ------------------------------------------------------------------------

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--stability, -i, ../dataset/samples/sample_100.txt, -o, /tmp/computed-soluc-team.sol]
0
0
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  0.424 s
[INFO] Finished at: 2018-12-20T23:18:47+01:00
[INFO] ------------------------------------------------------------------------

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--distance, -b, ../dataset/solutions/solution_1_000.txt, -o, /tmp/computed-soluc-team.sol]
Cheated solution used as input for metrics computations : exit code 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--satisfaction, -i, ../dataset/samples/sample_1_000.txt, -o, /tmp/computed-soluc-team.sol]
0     1     2     3     4     5     6     7     8     9     X
587     134     61     36     17     38     53     21     21     9     23
2.566
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  0.477 s
[INFO] Finished at: 2018-12-20T23:18:52+01:00
[INFO] ------------------------------------------------------------------------

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--stability, -i, ../dataset/samples/sample_1_000.txt, -o, /tmp/computed-soluc-team.sol]
0
0
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  0.498 s
[INFO] Finished at: 2018-12-20T23:18:54+01:00
[INFO] ------------------------------------------------------------------------

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--distance, -b, ../dataset/solutions/solution_10_000.txt, -o, /tmp/computed-soluc-team.sol]
Cheated solution used as input for metrics computations : exit code 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--satisfaction, -i, ../dataset/samples/sample_10_000.txt, -o, /tmp/computed-soluc-team.sol]
0     1     2     3     4     5     6     7     8     9     10     11     12     13     X
5081     958     368     330     384     364     206     276     316     319     429     229     250     54     436
4.1222
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  1.050 s
[INFO] Finished at: 2018-12-20T23:19:00+01:00
[INFO] ------------------------------------------------------------------------

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< fr.uca.polytech.2018.si3.ps5.21:apb >-----------------
[INFO] Building apb 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ apb ---
Running APB process
Args = [--stability, -i, ../dataset/samples/sample_10_000.txt, -o, /tmp/computed-soluc-team.sol]
0
0
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  1.063 s
[INFO] Finished at: 2018-12-20T23:19:02+01:00
[INFO] ------------------------------------------------------------------------

```
</details>

___
` ./apb.sh -i ../dataset/samples/sample_100_000.txt -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation


#### Hidden datasets

___
` ./apb.sh -i ../baseline/private/_15.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./apb.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./apb.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./apb.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./apb.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./apb.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./apb.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./apb.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation


### StudentFirst

