# Oracle SQLDeveloper custom color schemes
Custom color schemes for Oracle SQL Developer.

### <a name="halloween"></a>Halloween color scheme ###
![](screenshots/halloween_select.png)
  
### <a name="dracula"></a>Dracula based color scheme ###
> #### _Theme moved to: [dracula-sqldeveloper](https://github.com/apercova/dracula-sqldeveloper)_ ####

![](https://raw.githubusercontent.com/apercova/dracula-sqldeveloper/master/images/dracula_syntax.png)

### <a name="install"></a>Installation  ###
__See original instructions providing by [Ozmoroz](https://github.com/ozmoroz/ozbsidian-sqldeveloper/blob/master/README.md)__
> Unfortunately Oracle doesn't make it easy to import a new colour scheme into SQL Developer, thus a little bit of hacking is required.  
- Close SQL Developer. This is important. If you modify the scheme file while SQL Developer is open, your changes won't be saved.

- Locate file `dtcache.xml` in the [SQL Developer's settings directory](https://docs.oracle.com/en/database/oracle/sql-developer/19.1/rptig/installing-sql-developer.html#GUID-16F0A7C3-6EC1-4176-9B15-FE4AA8D70D5F).  
&nbsp;  
Windows:  
```%APPDATA%\SQL Developer\systemn.n.n.n.n.n\o.ide.n.n.n.n.n.n.n```  
Example:  
```C:\Users\alonperezext\AppData\Roaming\SQL Developer\system3.2.20.09.87\o.ide.11.1.1.4.37.59.48```  
&nbsp;  
Linux or Mac OS X:  
```~/.sqldeveloper/systemn.n.n.n.n.n/o.ide.n.n.n.n.n.n.n```  
Example:  
```~/.sqldeveloper/system19.1.0.094.2042/o.ide.13.0.0.1.42.170225.201```  
&nbsp;  

- Locate `<schemeMap>` tag inside dtcache.xml file. Insert the content of the color scheme xml file inside `<schemeMap>` alongside the other colour schemes. Be careful not to break the XML.  
![Insert the contents of color scheme xml file after opening schemeMap tag](screenshots/theme_insert_here.png)

- Launch SQL Developer. Navigate to menu Tools->Preferences, then select item Code Editor -> PL/SQL Syntax Colors in the left pane.

- Select theme in the "Scheme" drop down list on the top.  
![](screenshots/schema_select.png)

### <a name="others"></a>Other awesome themes for SQL Developer ###  
- [OzBsidian colour scheme for Oracle SQL Developer](https://github.com/ozmoroz/ozbsidian-sqldeveloper/blob/master/README.md)
- [sqldeveloper-syntax-highlighting](https://github.com/Gillisdc/sqldeveloper-syntax-highlighting)
- [atom-one-theme-for-sql-developer](https://github.com/sonnyksimon/atom-one-theme-for-sql-developer)
- [solarized-dark-sqldeveloper](https://github.com/mpicker0/solarized-dark-sqldeveloper)
