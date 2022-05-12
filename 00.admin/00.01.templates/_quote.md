<%* id = 0 %>
<%* function count(){
	while(tp.file.exists(tp.file.folder() +"."+ id)) {id++};
	return id;
	}
%>
<%* count() %>
<% await tp.file.rename( tp.file.folder() +"." + id ) %>
<% tp.system.clipboard() %>

From [[<% tp.file.folder() %>.source]]

**Notes**
