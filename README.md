#ajax error representater

You have an ajax form, you have put up server side validations errors over fields and return you return those 
validations in json format from server.

Now if you want to show those json errors inline, then this plugin can help you to display errors in a cool way.


## Installation

Just copy the javascripts, stylesheets and copy them inside yours application's respective folders and include them in your template.


## Usage
To apply js on the ajax form easy. The plugin takes some assumptions. Later on i will update it to make it more flexible.
Suppose you are creating messages, so here is an assumption that the 'entity_type' of the form is 'message' and ids of the fields 
in the form should be prepended with 'message', the entity type. If you are using Rails, it happens automatically.
