### Javascript:  Immutable Copy
A javascript class named MyClass has three properties (a,b and c) and a method called sum().

#### Implement two additional methods:
- ```getImmutableCopy```: return immutable copy of the instanace, disallowing changes to  properties a,b and c
- `isMutable`: returns true if the instance is mutable and false otherwise

#### Problem:
```
class MyClass {
  constructor() {
  }

  sum() {
  }

  isMutable() {
  }

  getImmutableCopy() {
  }
}
```
#### Example usage:
```
const input1 = new MyClass(1,2,3);
console.log(input1.isMutable()); // true
console.log(input1.getImmutableCopy()); // true
console.log(input1.isMutable()); // false
```