# Day 3 Lecture

* make sure that your data in arrays are consistent
* use objects to group data
* martin. 'the dot' is a native search option in java
* and the dot lookup operator returns helpful things to us
* when using numbers in objects, store in whole numbers.
if need cents, explicitly say cents. WHOLE NUMBERS!
* if there's logic within the object, you need it within a function
* need to invoke functions with the ()'s [ex. function()] 
* this. operator allows us to seek variables outside the scope and into the it's parent scop.
* console.table allows you to see objects in a nice way

### Objects:

```javascript
var people = [];

function Person(firstName, lastName, heightInCm) {
  this.id = people.length + 1
  this.firstName = firstName
  this.lastName = lastName
  this.heightInCm = heighInCm
  this.heightInInches: function () {
    return this.heightInCm/ 2.54
  },
  this.hasAnyFriends = function() {
    return this.friends.length > 1
  })
} 
var martin =  {
  firstName: 'Martin',
  lastName: 'Laws',
  heightInCm: 188,
  heightInInches: function () {
    return this.heightInCm/ 2.54
  },
  friends: []
}

