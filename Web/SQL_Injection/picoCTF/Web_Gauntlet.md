# Web Gauntlet ❓
Tags: Web Exploitation<br>
Point: 200<br>
AUTHOR: MADSTACKS<br>
Description:<br>
Can you beat the filters? Log in as admin http://jupiter.challenges.picoctf.org:54319/ <br>
http://jupiter.challenges.picoctf.org:54319/filter.php


## Write-up: 📝
We have to get through all 5 SQLi challenges. One link gives the form , display query after wrong credential submission or nothing if the query statement contains filtered words.
The other links show the filtered words.
## Solution: 💯
### Round 1:

Login as admin so the username=admin, and sqli here.

Filter: `or`

User: `admin' --`

Pass: `123456` (arbitary string)

### Round 2:
### Round 3:
### Round 4:
### Round 5:

#### The Flag (for reference): ✔️
```
CTFlearn{p0st_d4t4_4ll_d4y}
```
