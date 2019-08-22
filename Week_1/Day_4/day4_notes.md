# Morning Lecture

## Functions in Objects:

* calling the functions inside the object
* just need to call the 'key' that has the 'value' of the function
* anonymous functions within objects makes sense, because we're calling the key and not the value!

```javascript
allNames: function() {
  let names = [];
  for (let mentor of Object.values(this.mentors)) {
    names.push(mentor.name);
  }
  return names;
}
```
* 'this.mentors' refers to the object the key-value is inside
* don't need to use object.create anymore, the . function is powerful and creates a new key if that key doesn't exist!
* [] notation and . notation are ALMOST the same
* with bracket notation you can put a variable inside

```javascript
const likeTweep = function (name) {
  // have to loop through array
  for (tweep of tweeps) {
    if (tweep.who === name) {
      //.like operator makes a new key if it doesn't exist
      tweep.like = true
    }
  }
}

likeTweep('Someone\'s Name')
```

```javascript
const timestampTweep = function (tweep) {
  tweep.when = new Date()
}
timestampTweep(tweep[3])
```
* when you refer to objects and arrays within your function arguments it affects the original 
* with other primitive value types they are messed around inside the function, but its original are okay (unless you explicitly return and push a changed value towards it)
* declare your variables within the function to avoid confusion