# pagination
Simple pagination generator tool (JS / JQUERY)

## Usage
Quick setup:
```HTML
<div class="book">
  <div id="page1" class="page"></div>
  <div id="page2" class="page"></div>
  <div id="page3" class="page"></div>
 
  <button id="pageUp"></button>
  <button id="pageDown"></button>
</div>
```

```javascript
<script>
pagination.setup();
</script>
```
- By default, setup looks in class "book" for divs with class "page" and preserves the HTML order. 
- Button default names ids are "pageUp" and "pageDown"
- Pages require unique ids, they can be named anything

##### [DEMO](https://nbrosowsky.github.io/pagination/demo.html)

Optionally, you can pass an array of page ids to setup to customize the order of presentation:

```javascript
pagination.setup(["page3","page1","page2"])
```
##### [DEMO](https://nbrosowsky.github.io/pagination/randomOrder-demo.html)

