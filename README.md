# Scripting Lesson 5 Demo Starter

Run local development using the following:

```
npm install
npm start
```

## Instructions

### Inspecting the DOM and Selecting with jQuery

Preview this file and turn on the inspector to view what you now know is the DOM.

But first we need to add jQuery. 

1. Link to the Google Hosted Libraries.
2. Add a script in which to place some script.
3. Test by adding a DRE and console message.

Now we select elements in the DOM using `$()` and a CSS-style selector passed in as a string.

1. Select `h1`.
2. Select `p`.
3. Select the `.jumbotron`.
4. Select the `p` inside `.jumbotron`.
5. Select `.list-group-item`.

### Practice with Reading

1. Select the `p` in `.jumbotron` and change its plain text value.
2. Select the `.well` and place a `p` inside it with text as you see fit.
3. Select the first paragraph inside `#info` and set its class attribute to `.lead`.

### Practice with Modifying

1. Retrieve the plain text content of `h1`.
2. Retrieve the plain text content of `#info`.
3. Retrieve the HTML content of `h1`.
4. Retrieve the HTML content of `#info`.
5. Retrieve the `id` attribute of `.jumbotron`.
6. Retrieve the `class` attribute of `main`.

### Working with Classes

1. Select  `#shopping-list` and add the class `panel`. 
2. Select the first `.list-group-item` and remove the class `active` from it. Then add the class `disabled` instead.
3. Select the second `list-group-item` and toggle its class of `active`.
   
### Replacing and Removing

1. Remove the last paragraph from `#info`. 
2. Replace the first grocery list item with `Beef`.
3. Add a new item to the end of the grocery list as you see fit.
4. Add a new paragraph after the grocery list as you see fit.
