

# Team sible


## Environment

Latest commit date: `Date:   Thu Dec 20 19:48:56 2018 +0100`

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
[INFO] Total time:  0.432 s
[INFO] Finished at: 2018-12-21T07:09:06+01:00
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
[INFO] Total time:  0.436 s
[INFO] Finished at: 2018-12-21T07:09:07+01:00
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
[INFO] Total time:  0.432 s
[INFO] Finished at: 2018-12-21T07:09:12+01:00
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
[INFO] Total time:  0.436 s
[INFO] Finished at: 2018-12-21T07:09:13+01:00
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
[INFO] Total time:  0.652 s
[INFO] Finished at: 2018-12-21T07:09:18+01:00
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
[INFO] Total time:  0.489 s
[INFO] Finished at: 2018-12-21T07:09:20+01:00
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
[INFO] Total time:  1.055 s
[INFO] Finished at: 2018-12-21T07:09:26+01:00
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
[INFO] Total time:  1.100 s
[INFO] Finished at: 2018-12-21T07:09:28+01:00
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


#### Provided datasets

___
` ./student_first.sh -i ../dataset/samples/sample_10.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Running Student-First process
Args = [--distance, -b, ../dataset/solutions/solution_10.txt, -o, /tmp/computed-soluc-team.sol]
Cheated solution used as input for metrics computations : exit code 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student-First process
Args = [--satisfaction, -i, ../dataset/samples/sample_10.txt, -o, /tmp/computed-soluc-team.sol]
0     1     2     X
9     0     0     1
1.3

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student-First process
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
Running Student-First process
Args = [--distance, -b, ../dataset/solutions/solution_100.txt, -o, /tmp/computed-soluc-team.sol]
Cheated solution used as input for metrics computations : exit code 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student-First process
Args = [--satisfaction, -i, ../dataset/samples/sample_100.txt, -o, /tmp/computed-soluc-team.sol]
0     1     2     3     4     5     6     X
78     12     0     0     3     5     1     1
1.62

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student-First process
Args = [--stability, -i, ../dataset/samples/sample_100.txt, -o, /tmp/computed-soluc-team.sol]
19
5

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_1_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Running Student-First process
Args = [--distance, -b, ../dataset/solutions/solution_1_000.txt, -o, /tmp/computed-soluc-team.sol]
Cheated solution used as input for metrics computations : exit code 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student-First process
Args = [--satisfaction, -i, ../dataset/samples/sample_1_000.txt, -o, /tmp/computed-soluc-team.sol]
0     1     2     3     4     5     6     7     8     9     X
718     105     27     29     17     35     10     3     23     1     32
2.083

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student-First process
Args = [--stability, -i, ../dataset/samples/sample_1_000.txt, -o, /tmp/computed-soluc-team.sol]
322
79

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_10_000.txt -o /tmp/computed-soluc-team.sol `

:white_check_mark: - Result

:white_check_mark: - output file creation

:hourglass: - Distance computed

<details><summary>:boom: Distance invalid. Expected 1 lines.</summary>

```
Running Student-First process
Args = [--distance, -b, ../dataset/solutions/solution_10_000.txt, -o, /tmp/computed-soluc-team.sol]
Cheated solution used as input for metrics computations : exit code 3

```
</details>

:white_check_mark: - Satisfaction computed

<details><summary>:boom: Satisfaction invalid. Expected 4 lines.</summary>

```
Running Student-First process
Args = [--satisfaction, -i, ../dataset/samples/sample_10_000.txt, -o, /tmp/computed-soluc-team.sol]
0     1     2     3     4     5     6     7     8     9     10     11     12     13     X
6606     541     95     58     329     406     44     180     278     369     76     159     323     42     494
3.5167

```
</details>

:white_check_mark: - Stability computed

<details><summary>:boom: Stability invalid. Expected 2 lines.</summary>

```
Running Student-First process
Args = [--stability, -i, ../dataset/samples/sample_10_000.txt, -o, /tmp/computed-soluc-team.sol]
8093
2087

```
</details>

___
` ./student_first.sh -i ../dataset/samples/sample_100_000.txt -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation


#### Hidden datasets

___
` ./student_first.sh -i ../baseline/private/_15.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./student_first.sh -i ../baseline/private/_150.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./student_first.sh -i ../baseline/private/_1500.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./student_first.sh -i ../baseline/private/_15000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./student_first.sh -i ../baseline/private/_20.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./student_first.sh -i ../baseline/private/_200.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./student_first.sh -i ../baseline/private/_2000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

___
` ./student_first.sh -i ../baseline/private/_20000.in -o /tmp/computed-soluc-team.sol `

:hourglass: - Result

:boom: - output file creation

