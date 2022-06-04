## Question:

## Unique Email Addresses

Every valid email consists of a local name and a domain name, separated by the '@' sign. Besides lowercase letters, the email may contain one or more '.' or '+'.

For example, in alice@leetcode.com, alice is the local name, and leetcode.com is the domain name.
If you add periods '.' between some characters in the local name part of an email address, mail sent there will be forwarded to the same address without dots in the local name. Note that this rule does not apply to domain names.

For example, alice.z@leetcode.com and alicez@leetcode.com forward to the same email address.
If you add a plus '+' in the local name, everything after the first plus sign will be ignored. This allows certain emails to be filtered. Note that this rule does not apply to domain names.

For example, m.y+name@email.com will be forwarded to my@email.com.
It is possible to use both of these rules at the same time.

Given an array of strings emails where we send one email to each email[i], return the number of different addresses that actually receive mails.

### Example 1:
```
Input: emails = [test.email+alex@leetcode.com,test.e.mail+bob.cathy@leetcode.com,testemail+david@lee.tcode.com]
Output: 2
Explanation: testemail@leetcode.com and testemail@lee.tcode.com actually receive mails.
```

### Example 2:
```
Input: emails = [a@leetcode.com,b@leetcode.com,c@leetcode.com]
Output: 3
 ```

### Constraints:
```
1 <= emails.length <= 100
1 <= emails[i].length <= 100
email[i] consist of lowercase English letters, '+', '.' and '@'.
Each emails[i] contains exactly one '@' character.
All local and domain names are non-empty.
Local names do not start with a '+' character.
```

## Solutions:
1. [Submission 1](./solution1.java) (Java)
2. [Submission 2](./solution2.py) (Py)
3. [Submission 3](./solution3.py) (Py)
4. [Submission 4](./solution4.py) (Py)
5. [Submission 5](./solution5.py) (Py)
6. [Submission 6](./solution6.py) (Py)
7. [Submission 7](./solution7.py) (Py)
8. [Submission 8](./solution8.py) (Py)
9. [Submission 9](./solution9.py) (Py)