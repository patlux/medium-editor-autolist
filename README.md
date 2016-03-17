# Autolist Extension for [Medium Editor](https://github.com/varun-raj/medium-editor-autolist)
### Simple implementation
**Installation**
```
bower install medium-editor-autolist --save
```

**Import the javascript**

```
<script src="bower_components/medium-editor/dist/js/medium-editor.js"></script>
<script src="/bower_components/medium-editor-autolist/dist/autolist.js"></script>
```
**Add the extension**

```
var autolist = new AutoList();
var editor = new MediumEditor('.editable', {
    buttonLabels: 'fontawesome',
    extensions: {
        'autolist': autolist
    }
}),
```

### License

MIT: [https://github.com/yabwe/medium-editor/blob/master/LICENSE](https://github.com/yabwe/medium-editor/blob/master/LICENSE)