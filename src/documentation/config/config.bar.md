#### **bar** : {<%= type %>}

<% if(defaultValue !== "[object Object]") { %>*default: <%= defaultValue %>* <% }%>

To override any of the default configuration options in a bar chart, include the `bar` configuration object in the configuration options that you pass to your Contour constructor.

**Example:**

	new Contour({
	    el: '.myBarChart',
	    bar: {
	      // bar-specific configuration options
	    }
	  })
	.cartesian()
	.horizontal()
	.bar(data)
	.render()	
	
*[Try it.](<%= jsFiddleLink %>)*	
	
<% if(notes) { %><%= notes %><% } %>

