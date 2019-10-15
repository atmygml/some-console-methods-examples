# some-console-methods-examples
some console methods examples

// some console methods examples
//
console.log('Hello World');
console.log(123);
console.log(true);
console.table({ a: 1, b: 2, c: 3 });
console.error('This is some error');
console.clear();
console.warn('This is some warning');

// console.time example to determine the time duration to execute some instructions / code
//
console.time('testTimeHello');
console.log('Hello World');
console.log(123);
console.log(true);
console.table({ a: 1, b: 2, c: 3 });
console.timeEnd('testTimeHello');
