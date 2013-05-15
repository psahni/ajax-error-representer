#ajax error representater

You have an ajax form, you have put up server side validations errors over fields and return you return those 
validations in json format from server.

Now if you want to show those json errors inline, then this plugin can help you to display errors in a cool way.


## Installation

Just copy the javascripts, stylesheets and copy them inside yours application's respective folders and include them in your template.


## Usage
To apply this js on the ajax form easy. The plugin takes some assumptions. Later on i will update it to make it more flexible.

Suppose you are creating messages, so here is an assumption that the 'entity_type' of the form is 'message' and ids of the fields 
in the form should be prepended with 'message', the entity type. 

For example, if you have a text field 'subject', then id of the text field should be 'message_subject'
if you have a text field 'body', it id of the text field should be 'message_body'

If you are using Rails, this happens automatically.

Assuming the id of the form is 'new_message'. So, below your form you write

```javascript
var teacher_form = new AjaxErrorRepresenter('message', {form_id: "new_meesage"});
```
