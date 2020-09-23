<div align="center">

## Response\.write html without quotes


</div>

### Description

This shows how to Response.write html code without quotations, when I was first learning ASP, I wish I would have known this instead of having to do tons of quotes and chr(34)'s .
 
### More Info
 
chr(34) = "   '1 quote


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[snowboardr](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/snowboardr.md)
**Level**          |Beginner
**User Rating**    |2.4 (12 globes from 5 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__4-33.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/snowboardr-response-write-html-without-quotes__4-7216/archive/master.zip)





### Source Code

```
<%
Response.write ("<font face= Arial color= Arial size= 2>")
%>
OR the old way..
Response.write "<font face= Arial"& "color=#" & chr(34) & "000000" & chr(34) & " size=" & chr(34) & "2" & chr(34) & ">"
```

