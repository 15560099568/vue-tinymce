# vue-tinymce
tinymce by vue component

## Example
```
//js
new Vue({
    data: function(){
       return {
           content: '<p>html content</p>'
       }
    },
    ready: function(){
       //��Ҫ�ڸ�Ŀ¼����tinymce
       require('tinymce')
    },
    components: {
       tinymce: require('components/tinymce/vue-tinymce')
    }
})

//html
<form>
    <tinymce :model.sync="content"></tinymce>
</form>
```
