# chat-space
**Database creation**

* messages table

|body|image|group_id|user_id|
|:--|:--|:--|:--|
|text|string|integer|integer|

* users table

|name|email|password|
|:--|:--|:--|
|text|text|text|

* groups table

|name|user_id||
|:--|:--|:--|
|text|integer||
