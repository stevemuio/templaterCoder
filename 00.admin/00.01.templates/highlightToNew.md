<%* id = 0; function count(){while(tp.file.exists(tp.file.folder() +"."+ id)) {id++};return id;}
    count() 
    await tp.file.create_new(tp.file.find_tfile("_highlightquote"), "testtemplate",false) %>
<<<<<<<---------------------------extracted [[<%tp.file.folder() +"." + id %>]]
<% tp.file.selection() %>
-------------------------------------------->>>>>>>
