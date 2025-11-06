# Power Automate Action function to remove the last unwanted character in a string.

```javascript
  substring(variables('teamMentionsVar'),0,variables('lengthOfteamMentionsVarInit'))
```

### Method

- Get length of the string stored in lengthOfteamMentionsVarInit using 


- Use command `substring` from 0 to length -1 to remove the last unwanted character.


```javascript
  name: lengthOfteamMentionsVarInit
  command: length(variable('teamMembetVar')
```



```javascript
  concat((substring(variables('teamMentionsVar'),0,variables('lengthOfteamMentionsVarInit')), '.'))
```
