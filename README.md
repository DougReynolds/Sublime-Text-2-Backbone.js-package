----

# [Backbone.js](http://backbonejs.org) snippets and tab completions for [Sublime Text 2](http://www.sublimetext.com/2)
----

+ suports both JavaScript and CoffeScript
+ covers tab completions for full 0.9 public API
+ adds few convenience snippets


###JavaScript Scope
    
    bd - Module definition (requirejs)
    bv - Backbone.View.extend({$1})
    bm - Backbone.Model.extend({$1})
    bc - Backbone.Collection.extend({$1})
    br - Backbone.Router.extend({$1})
  
###CoffeeScript Scope  
        
    bc - Backbone.Collection
    bd - Backbone requirejs Module definition   
    bm - Backbone.Model    
    br - Backbone.Router
    bv - Backbone.View

    *MODEL*
    bme         - Create a Model class 
    clear       - Removes all attributes from the model
    def         - Specify default attributes for model
    esc         - Returns HTML-escaped model attribute
    fetch       - Resets the model state from server
    get         - Get the current value of an attribute from the model
    has         - True if attribute is non-null or non-undefined
    id          - Special property of models
    idAttrib    - Map a model id attribute
    new         - Create an instance model
    off         - Remove all previously-bound callbacks
    on          - Bind a callback function to an object
    set         - Set the current value of a model attribute
    json        - Return a JSON copy of model attributes
    tr          - Trigger callbacks for the given event
    unset       - Remove an attribute

    *COLLECTION*

    *ROUTER*

    *HISTORY*

    *SYNC*

    *VIEW*

    *UTILITY*

    



Available from [Sublime Package Control](http://wbond.net/sublime_packages/package_control) default channel or if you prefer to install manually just clone/copy to your Sublime Text 2 packages folder


Any requests to add more snippets? ideas to make it better? random requests? just ping me or open a pull request straight away.


CoffeScript support added by @dougrdotnet
  