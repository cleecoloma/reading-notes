# Class 04 Summary
## Code 301 - Intermediate Software Development

> These topics relates because forms are vital when getting information from the web application user.

### React Docs - Forms
1. What is a ‘Controlled Component’?
> 'Controlled Component' is a components which state is controlled by React. These are usually used in `form` elements.
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
> Both options are viable. Waiting until submit will reduce rerendering but slower feedback. Updating as they enter them will provide real-time feedback but requires more rerendering.
3. How do we target what the user is entering if we have an event handler on an input field?
> We target what the user is entering by utilizing onChange event handler.

### The Conditional (Ternary) Operator Explained
1. Why would we use a ternary operator?
> We use a ternary operator to shorten if statements into one line of code.
2. Rewrite the following statement using a ternary statement:
```javascript
//old
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
//new
(x===y) ? console.log(true) : console.log(false);
```

### Things I want to learn more about.
> None.


###### I also utilized ChatGPT to help with the questions.