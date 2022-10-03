# vangard-cal

1. Go to Chrome or any mordern browser
2. Mouse Right click -> inspect -> console (Chrome). For mac os, opt + cmd + i
3. try to paste the following code:
`(Date.now() - Date.parse(<your Date>))/ 86400 / 1000 / 7`

This will return you how many weeks have you done the investment. So that you could calculate how much money have you put into your vanguard


Eg: your start date is 'April 4 2022'
copy 
`(Date.now() - Date.parse('April 4 2022'))/ 86400 / 1000 / 7`

paste into your browser console
enter.

Then you will get 26 weeks
