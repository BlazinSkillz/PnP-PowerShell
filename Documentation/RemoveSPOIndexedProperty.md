#Remove-SPOIndexedProperty
Removes a key from propertybag to be indexed by search. The key and it's value remain in the propertybag, however it will not be indexed anymore.
##Syntax
```powershell
Remove-SPOIndexedProperty [-Web <WebPipeBind>] -Key <String>
```


##Parameters
Parameter|Type|Required|Description
---------|----|--------|-----------
|Key|String|True||
|Web|WebPipeBind|False|The web to apply the command to. Omit this parameter to use the current web.|
