# Title: Debugging PHP

- Repository: `php-debugging`
- Type of Challenge: `Learning challenge`
- Duration: `1 day`
- Team challenge : `solo`

## Learning objectives
- understanding the root of bug fixing
- know what print_r, var_dump, die, echo, exit, break do
- know what to do the next time you're stuck
- give yourself the `solver's mentality`, a problem is just an opportunity to learn!

## The Mission
Debugging is the pinpoint to being a master in any coding language.  
Everyone gets errors, but the best programmers never let it stop them and they find a way to fix it every time!
I scoured the internet for a debugging guide, that I felt like I could get behind and here it is: [The guide](https://rollbar.com/guides/how-to-debug-php/)

This is what I feel like doing when coding `PHP` that doesn't mean that this should be your way. Discover, look up, research whatever ways work for you to debug you code!

**I very much encourage you to use xDebug as much as possible!**

## Must-have features
Open up the [junior.php.broken](junior.php.broken) file, read the comments, fix the code blocks as requested in the comments
and put the final file [expert.php](expert.php) in the repository folder as requested.

You will change this junior code in expert code!
---
### progress
- -[x] exercise 1
    - give parameter to function calling
- -[x] exercise 2
    - change index number to the right index
- -[x] exercise 3
    - put single quotation marks on string
    - change offset Length to 11
    - add .'"' to the echo to add the " on the end
- -[x] exercise 4
    - add "&" in the foreach at $day so he keeps the value outside of the function
- -[x] exercise 5
    - change $letter <= 'z' -> $letter != 'aa'
- -[x] exercise 6
    - add "&" in the foreach at $param
    - ```implode(" - ", $params);``` instead of ```implode($params," - ");```
    - add semicolon to array hero lastnames
    - count($heroes)-1
    - return $randname instead of echo
- -[x] exercise 7
    - ```copyright(date('Y'));``` changed to ```copyright((int) date('Y'));```
- -[x] exercise 8
    - if statement "&&" instead of "||"
    - echo "welcome John" instead of return
- -[x] exercise 9
    - if statement "== true" changed to "> -1"
    - echo unacceptable found instead of return
    - add return after echo unacceptable
    - echo acceptable instead of return
- -[x] exercise 10
    - ```count($areTheseFruits)+1;``` instead of ```count($areTheseFruits);```
