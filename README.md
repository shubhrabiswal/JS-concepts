# JS-concepts

### Map & WeakMap

- Map ---  The Map object holds key-value pairs. Any value (both objects and primitive values) may be used as either a key or a value.

We can create Object literals as Maps like this:

let old_map = {
  "key1":"value1",
  "key2":"value2",
  "key3":"value3",
}
console.log(old_map.key1); // output value1
console.log(old_map.toString()) // output [object Object]


### Set & WeakSet
A WeakMap is a Map where the keys are weak — in other words, if all references to the key are lost and there are no more references to the value it 
can be garbage collected, unlike Map.

One problem with Map is the possibility of memory leak because the arrays ensure that references to each key and each value are maintained indefinitely. 
These references prevent the keys from being garbage collected, even if there are no other references to the object. This would also prevent the corresponding 
values from being garbage collected. 
WeakMap has the same API as Map, but one big difference: you cannot iterate over it, neither the keys, nor the values, nor the entries and you cannot clear a WeakMap, either.
