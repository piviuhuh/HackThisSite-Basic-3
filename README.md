# HackThisSite - Basic 3
## Description
Some intuition is needed to find the location of the hidden password file. Requirements: Basic HTML knowledge

We will be doing Basic 3 from HackThisSite
https://www.hackthissite.org/missions/basic/3/

## Solution
Upon accessing the challenge page, we observe:

`This time Network Security Sam remembered to upload the password file, but there were deeper problems than that.`

Sam fixed the problem and uploaded the password file, let’s check the source code.

During our inspection, we identified a hidden field named 'file' containing the value 'password.php'. This could be the password file Sam mentioned. Let's explore this potential lead by navigating to https://www.hackthissite.org/missions/basic/3/password.php

Excellent! Our investigation led us to 'password.php,' which seems to be the missing password file. With the file in hand, let's submit the password and move on to the next exciting challenge.

I appreciate you taking the time to review my write-up. If you have any inquiries or comments, please feel free to reach out. See you on the next challenge.








