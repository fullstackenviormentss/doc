# Additional Features

#### SQL History

Every interaction the user does with every database is logged in OmniDB's *SQL
History*. To access it you need to click on the icon with an *H* on the upper
right corner. OmniDB will open an inner tab with all actions in a paginated
grid.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_068.png)

Each action shows date time it started, the time it ended, the duration, the
status and the command. As every grid in OmniDB, you can right click on the
command and click *View Content*, where another pop-up will open showing the
content in a larger text editor.

#### User Settings

Also in the upper right corner, by clicking in the gear-like icon, OmniDB will
open the *User Settings* pop-up. It is composed by two tabs:

- **User**: Allows the user to change its password. More user settings will be
added in the future.

- **Editor**: Allows the user to change the font size of the SQL Editor, and
also change the entire OmniDB theme. There are a lot of OmniDB themes, each of
them change the syntax highlight color of the editor. They are also categorized
in light and dark themes. A light theme is the default; a dark theme will change
the entire interface of OmniDB.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_069.png)

Every change in user settings require that you either:

- Refresh the page, if you are using OmniDB server and the interface through a
web browser; or
- Open and close OmniDB, if you are using OmniDB app.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_070.png)

#### Contextual Help

Most of tree nodes (generally grouping ones like *Schemas* or *Tables*) offer
contextual help. This feature can be accessed by right-clicking the tree node.
When you click in the *Doc: ...* option, OmniDB will open an inner tab showing
a web browser pointing to the specific page in the online **PostgreSQL
Documentation**. Also, it will redirect to the specific page considering the
PostgreSQL version you are connected to.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_071.png)

#### Snippets

*Workspace Window* has a fixed outer tab with an useful feature called
*Snippets*. With this feature you can store queries, command instructions and
any other kinds of text you want. You can also structure the snippets in a
directory tree the way you want. All directories and snippets you create are
stored inside of `omnidb.db` user database and persist when you upgrade OmniDB.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_127.png)

#### Backend Management

By right-clicking in the tree root node, then moving mouse pointer to
*Monitoring* and then clicking on *Backends*, the user can see all activities
going on in the database. Some information are hidden for normal users, only
database superusers are allowed to see.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_174.png)

By clicking in the red *X* in the *Actions* column, you can terminate the
backend. A confirmation popup will appear.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_175.png)

#### Properties and DDL

By clicking on most of objects in the treeview (tables, sequences, views, roles,
databases, etc), the user will be able to see a very comprehensive list of
properties of the object.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_176.png)

In the other panel called *DDL*, the user will be able to see the SQL DDL source
code that can be used to re-create the object. The user can copy this text and
paste it wherever he/she wants.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_177.png)

#### Export Data

The *Query Tab* provides a way to save data from query results into a CSV or
XLSX file. Once you click the *Export Data* button, a cancellable backend starts
to save data into the file. Once it is done, OmniDB provides a link called
*Save*, so the user can download the file.

![](https://raw.githubusercontent.com/OmniDB/doc/master/img/image_178.png)

All files are stored in a temporary folder inside OmniDB folder. OmniDB
regularly cleans this folder, keeping only files newer than 24 hours.
