
# CommandBars.DisableCustomize Property (Office)

Is  **True** if toolbar customization is disabled. Read/write.


## Syntax

 _expression_. **DisableCustomize**

 _expression_ A variable that represents a **CommandBars** object.


## Example

The following example switches the  **DisableCustomize** property on or off.


```vb
Sub ToggleCustomize() 
 With Application.CommandBars 
 If .DisableCustomize = True Then 
 .DisableCustomize = False 
 Else 
 .DisableCustomize = True 
 End If 
 End With 
End Sub
```


## See also


#### Concepts


[CommandBars Object](0e312e21-14ee-5055-d604-b66e61c53b47.md)
