<a id="landousergetuid"></a>

<h2 id="landousergetuid" style="color: #ED3F7A; margin: 10px 0px; border-width: 2px 0px; padding: 25px 0px; border-color: #664b9d; border-style: solid;">
  lando.user.getUid([username]) ⇒ <code>String</code></h2>
<div class="api-body-header"></div>

Returns the id of the current user or username.

Note that on Windows this value is more or less worthless and `username` has
has no effect

**Since**: 3.0.0  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [username] | <code>String</code> | <code>&#x27;$(whoami)&#x27;</code> | The username to get the ID for |

**Returns**: <code>String</code> - The user ID.  
**Example**  
```js
// Get the id of the user.
const userId = lando.user.getUid();
```
<div class="api-body-footer"></div>
<a id="landousergetgid"></a>

<h2 id="landousergetgid" style="color: #ED3F7A; margin: 10px 0px; border-width: 2px 0px; padding: 25px 0px; border-color: #664b9d; border-style: solid;">
  lando.user.getGid([username]) ⇒ <code>String</code></h2>
<div class="api-body-header"></div>

Returns the id of the current user or username.

Note that on Windows this value is more or less worthless and `username` has
has no effect

**Since**: 3.0.0  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [username] | <code>String</code> | <code>&#x27;$(whoami)&#x27;</code> | The username to get the ID for |

**Returns**: <code>String</code> - The group ID.  
**Example**  
```js
// Get the id of the user.
const groupId = lando.user.getGid();
```
<div class="api-body-footer"></div>
