# 14-10

1.1
let str = 'ahb acb aeb aeeb adcb axeb'.replace(/a..b/g, "");
console.log(str);

1.2
let str = 'aba aca aea abba adca abea'.match(/a..a/g);
console.log(str);

1.3
let str = 'aba aca aea abba adca abea'.match(/ab.a/g, "");
console.log(str);

2.1
let str = 'aa aba abba abbba abca abea'.match(/ab+a/g, '!');
console.log(str);

2.2
let str = 'aa aba abba abbba abca abea'.match(/ab*a/g, '!');
console.log(str);

2.3
let str = 'aa aba abba abbba abca abea'.match(/ab?a/g, '!');
console.log(str);

2.4
let str = 'aa aba abba abbba abca abea'.match(/ab*a/g, '!');
console.log(str);

3.1
let str = 'ab abab abab abababab abea'.match(/(ab)+/g, ' ');
console.log(str);

4.1
let str = 'a.a aba aea'.match(/a\.a/g, '!');
console.log(str);

4.2
let str = '2+3 223 2223'.match(/2\+3/g, '!');
console.log(str);

4.3
let str = '23 2+3 2++3 2+++3 345 567'.match(/2\++3/g, '!');
console.log(str);

4.4
let str = '23 2+3 2++3 2+++3 445 677'.match(/2\+*3/g, '!');
console.log(str);

4.5
let str = '*+ *q+ *qq+ *qqq+ *qqq qqq+'.match(/\*q+\+/g, '!');
console.log(str);

4.6
let str = '[abc] {abc} abc (abc) [abc]'.replace(/\[abc\]/g, '!');
console.log(str);

5.1
let str = 'aa aba abba abbba abbbba abbbbba'.match(/ab{2,4}a/g, '!');
console.log(str);

5.2
let str = 'aa aba abba abbba abbbba abbbbba'.match(/ab{0,3}a/g, '!');
console.log(str);

5.3
let str = 'aa aba abba abbba abbbba abbbbba'.match(/ab{4,}a/g, '!');
console.log(str);
