# vangard JS calculator
This is for fun, please dont judge 😄. 
## Instruction
1. Go to Chrome or any mordern browser
2. Mouse Right click -> inspect -> console (Chrome). For mac os, opt + cmd + i
3. Try to paste the following code to your console:
`Math.floor((Date.now() - Date.parse(<your Date>))/ 86400 / 1000 / 7)`
4. Press Enter

This will return you how many weeks have you done the investment.(see the sceenshot below)

<img width="490" alt="Screen Shot 2022-10-03 at 11 28 56 am" src="https://user-images.githubusercontent.com/5242483/193486651-6c137bad-0a81-4004-9a9f-21b931558fd6.png">

So this could help you easily calculate how much money have you put into your vanguard.

## More choice
It's really depends on how frequent your auto investment should be

But, here is more options:
### Monthly based investment
`Math.floor((Date.now() - Date.parse(<your Date>))/ 2592000 / 1000)`
### Fornightly investment
`Math.floor((Date.now() - Date.parse(<your Date>))/ 86400 / 1000 / 14)`


## Example
Eg: your start date is 'April 4 2022'
copy 
`Math.floor((Date.now() - Date.parse('April 4 2022'))/ 86400 / 1000 / 7)`

paste into your browser console
enter.

Then you will get 26 weeks
