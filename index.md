### Welcome to Kanban.js.
This library is a simple way to make kanban boards in your web projects:

```
<link href="kanban.css" rel="stylesheet" type="text/css">
<script type="text/javascript" src="kanban.js"></script>
```

It's really simple!

### Usage
```
<script>
     //Set a Workspace 
     var nw = new Workspace();

     window.onload=function(){

       //Initizalize and create a Workspace DIV
       nw.init();

       //Add a column to the Workspace
       nw.add_column('NewColumn',nw.get_name());

       // Creates a new Card
       var myCard = new Card('New Card Title','New Task',nw.card_counter,nw.get_name());

       //Add the new Card to a initial Column
        nw.add_card_to_column('NewColumn',myCard);
     };

</script>
```

### Demo 
http://fernandorodas.github.io/kanba.js/example

### Authors and Contributors
Now, I'm only one, but I hope people can help to make it a better library.

### Support or Contact
You can contact me at: fer.darklogic@gmail.com