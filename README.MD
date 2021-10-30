# Exact.DB


<img src="https://coursework.vschool.io/content/images/2016/04/json-banner-750x220.jpg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

<br><br><br><br><br><br><br><br>

## Setup
<br>

> First we need to install the package!
<br><br>

> For npm use
```txt
npm install exact.db
```
<br>

> For yarn use
```txt
yarn install exact.db
```
<br><br>

> Now we need to setup our variables and call the package

```javascript
const Database = require('exact.db')
const db = new Database('json-file-name-here')
```
<br><br><br>

## Example
<br>

```javascript
const Database = require('exact.db')
const db = new Database('./Data/database.json')
```

<img src="https://cdn.discordapp.com/attachments/854934272502136913/897704166242275328/unknown.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

# .set

Use `.set` to put a value into the database that can be called using the key

```javascript
db.set('key', 'value')
```


# .delete

Use `.delete` to delete a value and a key using the key

```javascript
db.delete('key')
```



# .deleteAll

Use `.deleteAll` to completely wipe your database and restore it to brand new

```javascript
db.deleteAll()
```



# .fetch

Use `.fetch` to get the a value from the database using the key

```javascript
db.fetch('key')
```

<br><br><br><br><br>

> I do not own the JSON banner at the top all credit for that goes to [https://coursework.vschool.io/jsons-deli/](https://coursework.vschool.io/jsons-deli/)
