## indentation

This option allows specification of the indentation level for indent/outdent buttons in the UI.

This defaults to 30px but can be any value.

**Type:** `String`

**Default Value:** `30px`

##### Example

```js
tinymce.init({
  selector: 'textarea',  // change this value according to your HTML
  indentation : '20pt'
});
```

## indent_use_margin

This option sets if the editor should use margin instead of padding when indenting content.

**Type:** `boolean`

**Default Value:** `false`

##### Example

```js
tinymce.init({
  selector: 'textarea',  // change this value according to your HTML
  indentation : '20pt',
  indent_use_margin: true
});
```