# new
```
Sub test()
'Dim con As ADODB.Connection
'Set con = New ADODB.Connection

'Dim con As New ADODB.Connection


'con.Open "provider=microsoft.ace.oledb.12.0;data source=" & ThisWorkbook.Path & "\ikea.accdb"
'con.Open "provider=microsoft.ace.oledb.12.0;extended properties=excel 12.0;data source=" & ThisWorkbook.Path & "\ITALIA_PG_version.xlsx"
'With con
'    .Provider = "microsoft.ace.oledb.12.0"
'    .ConnectionString = ThisWorkbook.Path & "\ikea.accdb"
'    .Open
'End With
'With con
'    .Provider = "microsoft.ace.oledb.12.0;extended properties=excel 12.0"
'    .ConnectionString = ThisWorkbook.Path & "\ITALIA_PG_version.xlsx"
'    .Open
'End With
'insert into 表名(列1,列2,、、、) values(值1,值2,、、、)


MsgBox "连接成功"
End Sub
```
