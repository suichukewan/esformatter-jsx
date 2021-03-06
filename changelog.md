
# esformatter-jsx - Changelog
## v7.4.1
- **Other changes**
  - Fix restoreContainers regexp - [e11cdb1]( https://github.com/royriojas/esformatter-jsx/commit/e11cdb1 ), [wkich](https://github.com/wkich), 11/01/2017 03:27:07

    
- **Build Scripts Changes**
  - Remove old deprecated node versions - [4bf00d2]( https://github.com/royriojas/esformatter-jsx/commit/4bf00d2 ), [Roy Riojas](https://github.com/Roy Riojas), 29/11/2016 22:58:54

    
## v7.4.0
- **Build Scripts Changes**
  - Remove autogenerated code - [9393386]( https://github.com/royriojas/esformatter-jsx/commit/9393386 ), [Roy Riojas](https://github.com/Roy Riojas), 29/11/2016 21:24:03

    
## v7.3.3
- **Features**
  - Add `JSXAttributeQuotes` option. Closes [#93](https://github.com/royriojas/esformatter-jsx/issues/93) - [ebbbc7c]( https://github.com/royriojas/esformatter-jsx/commit/ebbbc7c ), [Roy Riojas](https://github.com/Roy Riojas), 29/11/2016 21:20:27

    `JSXAttributeQuotes` option will now control whether or not the quotes
    of JSXAttributes should use `single` or `double` quotes. Leave it empty
    to not change the quotes being used.
    
## v7.3.2
- **Documentation**
  - Change JSX Blocks to JSXElements - [e5b19bb]( https://github.com/royriojas/esformatter-jsx/commit/e5b19bb ), [Roy Riojas](https://github.com/Roy Riojas), 25/11/2016 23:57:12

    
## v7.3.0
- **Build Scripts Changes**
  - upgrade deps - [4c07f5a]( https://github.com/royriojas/esformatter-jsx/commit/4c07f5a ), [Roy Riojas](https://github.com/Roy Riojas), 24/11/2016 23:47:31

    
- **Other changes**
  - Remove `object-keys`. - [b5338c3]( https://github.com/royriojas/esformatter-jsx/commit/b5338c3 ), [Mat Garcia](https://github.com/Mat Garcia), 18/11/2016 17:18:13

    
  - Beautify again. - [63af226]( https://github.com/royriojas/esformatter-jsx/commit/63af226 ), [Mat Garcia](https://github.com/Mat Garcia), 18/11/2016 14:44:29

    
  - Beautify. - [9da80c3]( https://github.com/royriojas/esformatter-jsx/commit/9da80c3 ), [Mat Garcia](https://github.com/Mat Garcia), 18/11/2016 14:36:26

    
  - Beautify. - [21817c3]( https://github.com/royriojas/esformatter-jsx/commit/21817c3 ), [Mat Garcia](https://github.com/Mat Garcia), 18/11/2016 14:12:10

    
  - Delete yarn.lock - [fc2f46b]( https://github.com/royriojas/esformatter-jsx/commit/fc2f46b ), [wtgtybhertgeghgtwtg](https://github.com/wtgtybhertgeghgtwtg), 17/11/2016 12:46:54

    
  - Inline `falafel`. - [8c2c7bc]( https://github.com/royriojas/esformatter-jsx/commit/8c2c7bc ), [Mat Garcia](https://github.com/Mat Garcia), 17/11/2016 12:46:07

    
## v7.2.0
- **Build Scripts Changes**
  - Fix [#89](https://github.com/royriojas/esformatter-jsx/issues/89) - Update Babylon - [46d14ff]( https://github.com/royriojas/esformatter-jsx/commit/46d14ff ), [Roy Riojas](https://github.com/Roy Riojas), 02/11/2016 13:38:39

    
- **Other changes**
  - Update README.md - [d189083]( https://github.com/royriojas/esformatter-jsx/commit/d189083 ), [Edan Edison](https://github.com/Edan Edison), 02/11/2016 10:58:25

    Missing comma at end of line. Copying and pasting into sublime caused an error message. Simples ;)
## v7.1.0
- **Other changes**
  - fix for bug34 failure - [86bf05a]( https://github.com/royriojas/esformatter-jsx/commit/86bf05a ), [Sam Thompson](https://github.com/Sam Thompson), 22/10/2016 12:18:23

    
  - Added unit test, beautified format-jsx.jsx - [8ae3530]( https://github.com/royriojas/esformatter-jsx/commit/8ae3530 ), [Sam Thompson](https://github.com/Sam Thompson), 22/10/2016 12:07:28

    
  - closingTagOnNewLine added - [5aba419]( https://github.com/royriojas/esformatter-jsx/commit/5aba419 ), [Sam Thompson](https://github.com/Sam Thompson), 13/10/2016 18:06:29

    
## v7.0.1
- **Other changes**
  - Replace string like placeholder with variable - [edd48ca]( https://github.com/royriojas/esformatter-jsx/commit/edd48ca ), [webcarrot](https://github.com/webcarrot), 22/06/2016 10:58:59

    See issue: https://github.com/millermedeiros/esformatter-quotes/issues/16
## v7.0.0
- **Bug Fixes**
  - closes [#76](https://github.com/royriojas/esformatter-jsx/issues/76). don't replace jsxElements on `stringBefore` hook - [d8c4bf8]( https://github.com/royriojas/esformatter-jsx/commit/d8c4bf8 ), [Roy Riojas](https://github.com/Roy Riojas), 12/06/2016 04:33:20

    
## v6.1.2
- **Bug Fixes**
  - proper fix for [#77](https://github.com/royriojas/esformatter-jsx/issues/77). Don't forget to add semicolons if they were there - [d9c29c0]( https://github.com/royriojas/esformatter-jsx/commit/d9c29c0 ), [Roy Riojas](https://github.com/Roy Riojas), 12/06/2016 03:26:09

    
## v6.1.1
- **Bug Fixes**
  - closes [#77](https://github.com/royriojas/esformatter-jsx/issues/77). Support decorators with parameters - [6f84d29]( https://github.com/royriojas/esformatter-jsx/commit/6f84d29 ), [Roy Riojas](https://github.com/Roy Riojas), 12/06/2016 03:09:38

    
## v6.1.0
- **Bug Fixes**
  - Fix for Bug-78. closes [#78](https://github.com/royriojas/esformatter-jsx/issues/78) - [1deb394]( https://github.com/royriojas/esformatter-jsx/commit/1deb394 ), [Roy Riojas](https://github.com/Roy Riojas), 11/06/2016 05:14:02

    Removed hack to align comments. use:
    
    indent.alignComments=false as suggested
    https://github.com/millermedeiros/esformatter/issues/325
    
## v6.0.0
- **Bug Fixes**
  - closes [#73](https://github.com/royriojas/esformatter-jsx/issues/73). Support decorators on same line - [33b17e7]( https://github.com/royriojas/esformatter-jsx/commit/33b17e7 ), [Roy Riojas](https://github.com/Roy Riojas), 28/05/2016 00:58:56

    
## v5.0.6
- **Build Scripts Changes**
  - update to latest esformatter - [0e926db]( https://github.com/royriojas/esformatter-jsx/commit/0e926db ), [Roy Riojas](https://github.com/Roy Riojas), 23/05/2016 04:41:20

    
## v5.0.5
- **Bug Fixes**
  - Do not break template literals - [2811ca6]( https://github.com/royriojas/esformatter-jsx/commit/2811ca6 ), [Roy Riojas](https://github.com/Roy Riojas), 23/05/2016 04:37:38

    
- **Other changes**
  - Reformat within demo to ensure equal results - [dcf9295]( https://github.com/royriojas/esformatter-jsx/commit/dcf9295 ), [Cameron Knight](https://github.com/Cameron Knight), 19/05/2016 19:53:09

    
## v5.0.4
- **Bug Fixes**
  - Avoid introducing ___AVOID_ESFMT_BUG_WITH_COMMENTS__ tokens. closes [#17](https://github.com/royriojas/esformatter-jsx/issues/17). - [0ac45fb]( https://github.com/royriojas/esformatter-jsx/commit/0ac45fb ), [Roy Riojas](https://github.com/Roy Riojas), 16/05/2016 10:29:51

    
## v5.0.3
- **Bug Fixes**
  - Updated live demo. closes [#61](https://github.com/royriojas/esformatter-jsx/issues/61) - [59ab0b3]( https://github.com/royriojas/esformatter-jsx/commit/59ab0b3 ), [Roy Riojas](https://github.com/Roy Riojas), 02/05/2016 14:00:43

    
- **Other changes**
  - Tried the example and forgot to put variable on new line - [5eae9bb]( https://github.com/royriojas/esformatter-jsx/commit/5eae9bb ), [Kevin Simper](https://github.com/Kevin Simper), 29/04/2016 22:50:19

    
  - Update with a better react component example - [d97f136]( https://github.com/royriojas/esformatter-jsx/commit/d97f136 ), [Kevin Simper](https://github.com/Kevin Simper), 29/04/2016 22:48:21

    The component is always wrapped in two parenteses and 
    this shows a more real example on how esformatter will format things.
## v5.0.2
- **Bug Fixes**
  - Fix the package name - [afc289e]( https://github.com/royriojas/esformatter-jsx/commit/afc289e ), [Roy Riojas](https://github.com/Roy Riojas), 26/04/2016 18:10:37

    
## v5.0.1
- **Bug Fixes**
  - test now verify code passes beautification and lint - [44fe581]( https://github.com/royriojas/esformatter-jsx/commit/44fe581 ), [Roy Riojas](https://github.com/Roy Riojas), 26/04/2016 18:07:06

    
  - Fix style and lint validation - [2078bae]( https://github.com/royriojas/esformatter-jsx/commit/2078bae ), [Roy Riojas](https://github.com/Roy Riojas), 26/04/2016 18:01:50

    
- **Other changes**
  - adding comments about usage and default value - [be0483c]( https://github.com/royriojas/esformatter-jsx/commit/be0483c ), [Samvel Avanesov](https://github.com/Samvel Avanesov), 25/04/2016 16:32:11

    
  - specs - [9103f97]( https://github.com/royriojas/esformatter-jsx/commit/9103f97 ), [Samvel Avanesov](https://github.com/Samvel Avanesov), 24/04/2016 17:05:44

    
  - adding tests to no-space before closing tag - [dceed38]( https://github.com/royriojas/esformatter-jsx/commit/dceed38 ), [Samvel Avanesov](https://github.com/Samvel Avanesov), 24/04/2016 16:20:35

    
  - adding posibility to remove whitespace before closing tag in reformatted jsx elements - [76b0e75]( https://github.com/royriojas/esformatter-jsx/commit/76b0e75 ), [Samvel Avanesov](https://github.com/Samvel Avanesov), 23/04/2016 14:55:49

    
- **Build Scripts Changes**
  - Add small demo example - [f3be6e0]( https://github.com/royriojas/esformatter-jsx/commit/f3be6e0 ), [Roy Riojas](https://github.com/Roy Riojas), 20/04/2016 14:43:02

    
## v5.0.0
- **Features**
  - Add `JSXExpressionsSingleLine` property to control if a jsxExpression will be put into a single line or multiple lines - [7f89846]( https://github.com/royriojas/esformatter-jsx/commit/7f89846 ), [Roy Riojas](https://github.com/Roy Riojas), 25/03/2016 20:40:47

    Closes <a target="_blank" class="info-link" href="https://github.com/royriojas/esformatter-jsx/issues/19"><span>#19</span></a>, <a target="_blank" class="info-link" href="https://github.com/royriojas/esformatter-jsx/issues/30"><span>#30</span></a> and <a target="_blank" class="info-link" href="https://github.com/royriojas/esformatter-jsx/issues/32"><span>#32</span></a>
    
- **Refactoring**
  - Update to latest Esformatter - [55df71e]( https://github.com/royriojas/esformatter-jsx/commit/55df71e ), [Roy Riojas](https://github.com/Roy Riojas), 25/03/2016 18:33:09

    
## v4.1.4
- **Bug Fixes**
  - Remove lint warning - [1a1e360]( https://github.com/royriojas/esformatter-jsx/commit/1a1e360 ), [Roy Riojas](https://github.com/Roy Riojas), 10/03/2016 02:44:19

    
- **Other changes**
  - Added tests, reversed assertion order - [20904fc]( https://github.com/royriojas/esformatter-jsx/commit/20904fc ), [R](https://github.com/R), 09/03/2016 00:35:48

    Added tests for new functionality. Reversed mocha test assertion order
    so that “expected” in console aligns with “expected” files and actual
    in console aligns with formatted code.
    
- **undefined**
  - Added default values for attr indentation - [0e89c2c]( https://github.com/royriojas/esformatter-jsx/commit/0e89c2c ), [R](https://github.com/R), 24/02/2016 15:32:42

    Default values if no indent options specified in htmlOptions
    
  - attribute indentation should respect options - [f498454]( https://github.com/royriojas/esformatter-jsx/commit/f498454 ), [R](https://github.com/R), 24/02/2016 15:29:22

    Previously, the attributes would indent either with the first attribute
    or 2 spaces. Now, it will indent either with the first attribute or by
    the number of spaces defined in htmlOptions.
    
## v4.1.3
- **Bug Fixes**
  - properly format object methods. Fixes [#54](https://github.com/royriojas/esformatter-jsx/issues/54) - [cbc468d]( https://github.com/royriojas/esformatter-jsx/commit/cbc468d ), [Roy Riojas](https://github.com/Roy Riojas), 13/02/2016 22:44:10

    
## v4.1.2
- **Bug Fixes**
  - lock esformatter dependency - [a6cf823]( https://github.com/royriojas/esformatter-jsx/commit/a6cf823 ), [royriojas](https://github.com/royriojas), 29/01/2016 17:37:22

    
- **Other changes**
  - Fix typo in README.md - [932e122]( https://github.com/royriojas/esformatter-jsx/commit/932e122 ), [Dale Jefferson](https://github.com/Dale Jefferson), 29/01/2016 16:43:02

    
## v4.1.1
- **Other changes**
  - Fix the version of babylon in use - [1aa3637]( https://github.com/royriojas/esformatter-jsx/commit/1aa3637 ), [Jess Telford](https://github.com/Jess Telford), 17/01/2016 21:39:35

    To avoid running into this bug: https://phabricator.babeljs.io/T6930
    
## v4.1.0
- **Features**
  - Add option to avoid formatting of JSXExpressions. Fixes [#48](https://github.com/royriojas/esformatter-jsx/issues/48) - [6ce091b]( https://github.com/royriojas/esformatter-jsx/commit/6ce091b ), [royriojas](https://github.com/royriojas), 25/12/2015 07:12:53

    This commit adds a new option `formatJSXExpressions`. The default value is true.
    
    In case you need to stop this behavior, for example when using a plugin that modify the code like the `esformatter-semicolons`.
    
    You should opt out of the formatting of the JSXExpressions to avoid potentially risky issues
    
    ```javascript
    // example of the options
    {
      "jsx": {
        "formatJSX": true,
        "attrsOnSameLineAsTag": true,
        "maxAttrsOnTag": 3,
        "firstAttributeOnSameLine": true,
        "spaceInJSXExpressionContainers": " ",
        "alignWithFirstAttribute": false,
        // default is true, setting it to false JSXExpressions won't be recursively formatted
        "formatJSXExpressions": false,
        "htmlOptions": {
          "brace_style": "collapse",
          "indent_char": " ",
          "indent_size": 2,
          "max_preserve_newlines": 2,
          "preserve_newlines": true
        }
      }
    }
    ```
    
## v4.0.6
- **Bug Fixes**
  - properly format code with comments in decorators. Fix [#45](https://github.com/royriojas/esformatter-jsx/issues/45) - [ac2dc2d]( https://github.com/royriojas/esformatter-jsx/commit/ac2dc2d ), [royriojas](https://github.com/royriojas), 01/12/2015 14:39:24

    
## v4.0.5
- **Bug Fixes**
  - support async ArrowFunctionExpressions - [8ab19cb]( https://github.com/royriojas/esformatter-jsx/commit/8ab19cb ), [royriojas](https://github.com/royriojas), 30/11/2015 14:00:17

    
  - support decorators in classMethods. Fixes [#43](https://github.com/royriojas/esformatter-jsx/issues/43) - [a8940a0]( https://github.com/royriojas/esformatter-jsx/commit/a8940a0 ), [royriojas](https://github.com/royriojas), 30/11/2015 13:01:32

    
## v4.0.4
- **Build Scripts Changes**
  - Use the latest esformatter for the tests - [af472da]( https://github.com/royriojas/esformatter-jsx/commit/af472da ), [Roy Riojas](https://github.com/Roy Riojas), 22/11/2015 17:32:11

    
## v4.0.3
- **Bug Fixes**
  - Proper fix for [#41](https://github.com/royriojas/esformatter-jsx/issues/41). Properly handle the async/await in class methods - [ed76453]( https://github.com/royriojas/esformatter-jsx/commit/ed76453 ), [Roy Riojas](https://github.com/Roy Riojas), 22/11/2015 17:31:01

    
## v4.0.2
- **Bug Fixes**
  - Properly format code with async token on function expressions. Fixes [#42](https://github.com/royriojas/esformatter-jsx/issues/42) - [5715fcb]( https://github.com/royriojas/esformatter-jsx/commit/5715fcb ), [Roy Riojas](https://github.com/Roy Riojas), 22/11/2015 17:09:44

    
## v4.0.1
- **Bug Fixes**
  - Properly format blocks of code containing comments at the end of a function or method body. - [1da006e]( https://github.com/royriojas/esformatter-jsx/commit/1da006e ), [Roy Riojas](https://github.com/Roy Riojas), 22/11/2015 16:33:23

    
## v4.0.0
- **Bug Fixes**
  - Properly format blocks of code containing async/await tokens. Fixes [#41](https://github.com/royriojas/esformatter-jsx/issues/41) - [6a0e044]( https://github.com/royriojas/esformatter-jsx/commit/6a0e044 ), [Roy Riojas](https://github.com/Roy Riojas), 22/11/2015 16:06:19

    
## v3.0.0
- **Enhancements**
  - Use babylon directly instead of `babel-core` Fixes [#38](https://github.com/royriojas/esformatter-jsx/issues/38) - [b4498f3]( https://github.com/royriojas/esformatter-jsx/commit/b4498f3 ), [royriojas](https://github.com/royriojas), 15/11/2015 17:14:59

    
- **Bug Fixes**
  - use babylon directly instead of thru babel - [bb595fb]( https://github.com/royriojas/esformatter-jsx/commit/bb595fb ), [royriojas](https://github.com/royriojas), 15/11/2015 17:14:59

    
## v2.3.11
- **Build Scripts Changes**
  - upgrade babel-core. Fix [#38](https://github.com/royriojas/esformatter-jsx/issues/38) - [4d75188]( https://github.com/royriojas/esformatter-jsx/commit/4d75188 ), [royriojas](https://github.com/royriojas), 14/11/2015 22:54:55

    
- **Bug Fixes**
  - Remove non npm dependencies. Fixes [#40](https://github.com/royriojas/esformatter-jsx/issues/40) - [0ab0a2a]( https://github.com/royriojas/esformatter-jsx/commit/0ab0a2a ), [royriojas](https://github.com/royriojas), 14/11/2015 21:53:02

    
## v2.3.10
- **Bug Fixes**
  - Properly format code that contains a Bind Expression. Fixes [#39](https://github.com/royriojas/esformatter-jsx/issues/39) - [5e3f334]( https://github.com/royriojas/esformatter-jsx/commit/5e3f334 ), [royriojas](https://github.com/royriojas), 13/11/2015 06:42:14

    
  - tab indentation. Fixes [#36](https://github.com/royriojas/esformatter-jsx/issues/36) - [73e5526]( https://github.com/royriojas/esformatter-jsx/commit/73e5526 ), [Lukas Benes](https://github.com/Lukas Benes), 01/11/2015 18:06:51

    
## v2.3.9
- **Bug Fixes**
  - properly support export declarations, even the ones that babel allows. Fixes [#34](https://github.com/royriojas/esformatter-jsx/issues/34) - [cc69735]( https://github.com/royriojas/esformatter-jsx/commit/cc69735 ), [royriojas](https://github.com/royriojas), 29/10/2015 12:05:29

    
  - support inline decorators. Fixes [#35](https://github.com/royriojas/esformatter-jsx/issues/35) - [97e4a28]( https://github.com/royriojas/esformatter-jsx/commit/97e4a28 ), [royriojas](https://github.com/royriojas), 29/10/2015 11:02:51

    
## v2.3.8
- **Bug Fixes**
  - support async/await. Fixes [#33](https://github.com/royriojas/esformatter-jsx/issues/33) - [20d4686]( https://github.com/royriojas/esformatter-jsx/commit/20d4686 ), [royriojas](https://github.com/royriojas), 26/10/2015 22:29:51

    
## v2.3.7
- **Bug Fixes**
  - support async/await - [9e06f36]( https://github.com/royriojas/esformatter-jsx/commit/9e06f36 ), [royriojas](https://github.com/royriojas), 26/10/2015 21:21:21

    
## v2.3.6
- **Bug Fixes**
  - require acorn only if no other parser was set. Fixes [#31](https://github.com/royriojas/esformatter-jsx/issues/31) - [4ae4479]( https://github.com/royriojas/esformatter-jsx/commit/4ae4479 ), [royriojas](https://github.com/royriojas), 11/10/2015 12:55:10

    
## v2.3.5
- **Bug Fixes**
  - properly format ES7 Decorators. Fixes [#29](https://github.com/royriojas/esformatter-jsx/issues/29) - [8f124fd]( https://github.com/royriojas/esformatter-jsx/commit/8f124fd ), [royriojas](https://github.com/royriojas), 08/10/2015 13:43:53

    
- **Build Scripts Changes**
  - Update esformatter-ignore to latest to properly ignore lines that have no empty spaces at the beginning - [e0ce5f3]( https://github.com/royriojas/esformatter-jsx/commit/e0ce5f3 ), [royriojas](https://github.com/royriojas), 08/10/2015 13:32:31

    
## v2.3.4
- **Bug Fixes**
  - support `ExportNamedDeclaration`. Fixes [#28](https://github.com/royriojas/esformatter-jsx/issues/28) - [b968dbf]( https://github.com/royriojas/esformatter-jsx/commit/b968dbf ), [royriojas](https://github.com/royriojas), 06/10/2015 19:39:36

    
## v2.3.3
- **Bug Fixes**
  - Issue with the parser returning negative indexes - [eafe7bf]( https://github.com/royriojas/esformatter-jsx/commit/eafe7bf ), [royriojas](https://github.com/royriojas), 02/10/2015 02:13:17

    
## v2.3.2
- **Features**
  - Support SpreadProperties outside of JSX blocks. Fixes [#27](https://github.com/royriojas/esformatter-jsx/issues/27) - [2ad355d]( https://github.com/royriojas/esformatter-jsx/commit/2ad355d ), [royriojas](https://github.com/royriojas), 02/10/2015 01:34:20

    
## v2.3.1
- **Features**
  - Support for decorators and class properties. Fixes [#26](https://github.com/royriojas/esformatter-jsx/issues/26) - [8d546ef]( https://github.com/royriojas/esformatter-jsx/commit/8d546ef ), [royriojas](https://github.com/royriojas), 02/10/2015 01:02:16

    
## v2.3.0
- **Features**
  - support decorators and static props - [e6e1dc2]( https://github.com/royriojas/esformatter-jsx/commit/e6e1dc2 ), [royriojas](https://github.com/royriojas), 02/10/2015 00:25:39

    Please note that `static props` are just ignored from beautification all together for now
    
    It shouldn't be difficult to format it, but for now it is just OK
    
## v2.2.0
- **Refactoring**
  - use acorn-babel for more es6, es7 features - [6043e32]( https://github.com/royriojas/esformatter-jsx/commit/6043e32 ), [royriojas](https://github.com/royriojas), 01/10/2015 21:38:15

    
## v2.1.4
- **Enhancements**
  - properly ignore blocks with ignore block comments - [b8f5c52]( https://github.com/royriojas/esformatter-jsx/commit/b8f5c52 ), [royriojas](https://github.com/royriojas), 01/10/2015 12:24:18

    
## v2.1.3
- **Enhancements**
  - ignore blocks using esformatter-ignore - [460d6e8]( https://github.com/royriojas/esformatter-jsx/commit/460d6e8 ), [royriojas](https://github.com/royriojas), 01/10/2015 01:40:21

    Required because espree still does not recognize some of the new fancy syntax of ES6 and ES7 and that makes it break badly when trying to beautify new files
    
## v2.1.2
- **Bug Fixes**
  - wrong changelogx section - [a047b49]( https://github.com/royriojas/esformatter-jsx/commit/a047b49 ), [royriojas](https://github.com/royriojas), 21/09/2015 23:33:23

    
## v2.1.1
- **Enhancements**
  - support for spread operator - [b4a36d1]( https://github.com/royriojas/esformatter-jsx/commit/b4a36d1 ), [royriojas](https://github.com/royriojas), 18/09/2015 01:28:16

    
- **Documentation**
  - Update Readme. Fixes [#7](https://github.com/royriojas/esformatter-jsx/issues/7) - [323a2ec]( https://github.com/royriojas/esformatter-jsx/commit/323a2ec ), [Roy Riojas](https://github.com/Roy Riojas), 30/08/2015 01:40:01

    
## v2.1.0
- **Enhancements**
  - support for spread operator - [2c136b4]( https://github.com/royriojas/esformatter-jsx/commit/2c136b4 ), [royriojas](https://github.com/royriojas), 18/09/2015 01:26:41

    
## v2.0.11
- **Bug Fixes**
  - properly handle ObjectExpressions and ArrayExpressions inside JSXContainers - [53941aa]( https://github.com/royriojas/esformatter-jsx/commit/53941aa ), [royriojas](https://github.com/royriojas), 12/08/2015 02:46:59

    
## v2.0.10
- **Bug Fixes**
  - prevent other plugins from messing with the expression containers - [161de77]( https://github.com/royriojas/esformatter-jsx/commit/161de77 ), [royriojas](https://github.com/royriojas), 07/08/2015 13:26:51

    
## v2.0.9
- **Bug Fixes**
  - exclude identifiers from recursive formatting - [db23cd4]( https://github.com/royriojas/esformatter-jsx/commit/db23cd4 ), [royriojas](https://github.com/royriojas), 07/08/2015 02:16:39

    
## v2.0.8
- **Bug Fixes**
  - properly format JSXExpression containers content. Fixes [#14](https://github.com/royriojas/esformatter-jsx/issues/14) - [d8d21e7]( https://github.com/royriojas/esformatter-jsx/commit/d8d21e7 ), [royriojas](https://github.com/royriojas), 07/08/2015 01:54:59

    
## v2.0.7
- **Bug Fixes**
  - nested JSXElements inside JSXExpressionContainers now are properly beautified - [3ef3595]( https://github.com/royriojas/esformatter-jsx/commit/3ef3595 ), [royriojas](https://github.com/royriojas), 06/08/2015 19:35:14

    
## v2.0.6
- **Documentation**
  - document new option `spaceInJSXExpressionContainers` - [5601b77]( https://github.com/royriojas/esformatter-jsx/commit/5601b77 ), [royriojas](https://github.com/royriojas), 05/08/2015 03:02:19

    ```javascript
      "spaceInJSXExpressionContainers": " " // set it to "" to remove spaces in JSXExpressionContainers
    ```
    
## v2.0.5
- **Build Scripts Changes**
  - Add precommit module - [68a7139]( https://github.com/royriojas/esformatter-jsx/commit/68a7139 ), [royriojas](https://github.com/royriojas), 05/08/2015 02:58:39

    
- **Enhancements**
  - Add option to add spaces around JSXExpressionContainers `spaceInJSXExpressionContainers`. Closes [#11](https://github.com/royriojas/esformatter-jsx/issues/11) - [2a11c8b]( https://github.com/royriojas/esformatter-jsx/commit/2a11c8b ), [royriojas](https://github.com/royriojas), 05/08/2015 02:57:19

    
## v2.0.4
- **Bug Fixes**
  - keep selfclosing char (`/>`) in the same of the last attribute - [e066931]( https://github.com/royriojas/esformatter-jsx/commit/e066931 ), [royriojas](https://github.com/royriojas), 28/07/2015 19:34:19

    
## v2.0.3
- **Bug Fixes**
  - Major issue with nodes being deleted because some weird issue with rocambole. - [48a0a71]( https://github.com/royriojas/esformatter-jsx/commit/48a0a71 ), [royriojas](https://github.com/royriojas), 28/07/2015 04:56:49

    Switched back to use falafel-espree. Definitively it works better and do not destroy the code
    
## v2.0.2
- **Build Scripts Changes**
  - Fix pre-version script so it executes tests only once - [384d14e]( https://github.com/royriojas/esformatter-jsx/commit/384d14e ), [royriojas](https://github.com/royriojas), 28/07/2015 03:10:37

    
  - remove unused rocambole-token dep - [116bb31]( https://github.com/royriojas/esformatter-jsx/commit/116bb31 ), [royriojas](https://github.com/royriojas), 28/07/2015 03:09:46

    
## v2.0.1
- **Bug Fixes**
  - missing lib folder - [ec9935a]( https://github.com/royriojas/esformatter-jsx/commit/ec9935a ), [royriojas](https://github.com/royriojas), 28/07/2015 02:08:21

    
## v2.0.0
- **Build Scripts Changes**
  - Add bump to major script - [0bffcba]( https://github.com/royriojas/esformatter-jsx/commit/0bffcba ), [royriojas](https://github.com/royriojas), 28/07/2015 00:18:41

    
- **Refactoring**
  - Big refactoring of the beautifier to address several bugs. Fixes [#4](https://github.com/royriojas/esformatter-jsx/issues/4), Fixes [#9](https://github.com/royriojas/esformatter-jsx/issues/9) - [d1630a9]( https://github.com/royriojas/esformatter-jsx/commit/d1630a9 ), [royriojas](https://github.com/royriojas), 27/07/2015 17:57:02

    
## v1.3.0
- **Enhancements**
  - Make more predictive the parsing of jsx tags - [ca7f190]( https://github.com/royriojas/esformatter-jsx/commit/ca7f190 ), [royriojas](https://github.com/royriojas), 17/06/2015 05:07:13

    
- **Bug Fixes**
  - remove initial and final text surrounding a tag to prevent react from creating span tags - [916c0b2]( https://github.com/royriojas/esformatter-jsx/commit/916c0b2 ), [royriojas](https://github.com/royriojas), 17/06/2015 04:05:36

    
## v1.1.1
- **Build Scripts Changes**
  - simplify bump task - [c4b9582]( https://github.com/royriojas/esformatter-jsx/commit/c4b9582 ), [royriojas](https://github.com/royriojas), 17/06/2015 00:45:25

    
  - Add changelogx generation task - [8b4948e]( https://github.com/royriojas/esformatter-jsx/commit/8b4948e ), [royriojas](https://github.com/royriojas), 17/06/2015 00:44:39

    
  - Add prepush config section - [76c53e2]( https://github.com/royriojas/esformatter-jsx/commit/76c53e2 ), [royriojas](https://github.com/royriojas), 17/06/2015 00:42:00

    
- **Refactoring**
  - update to use falafel-espree - [779afc9]( https://github.com/royriojas/esformatter-jsx/commit/779afc9 ), [royriojas](https://github.com/royriojas), 17/06/2015 00:39:45

    
## v1.0.9
- **Features**
  - Ternary operators in jsx will try to remain in the same line - [eb1ee17]( https://github.com/royriojas/esformatter-jsx/commit/eb1ee17 ), [royriojas](https://github.com/royriojas), 16/06/2015 06:22:31

    
  - adding mocha runner - [6a503cb]( https://github.com/royriojas/esformatter-jsx/commit/6a503cb ), [royriojas](https://github.com/royriojas), 16/06/2015 04:17:22

    
- **Bug Fixes**
  - Fix for nested jsx structures issue - [f10a429]( https://github.com/royriojas/esformatter-jsx/commit/f10a429 ), [Roy Riojas](https://github.com/Roy Riojas), 09/03/2015 15:45:51

    Fixes an issue reported under esformatter-jsx-ignore when using nested jsx blocks.
    
    Check the readme for details about this issue.
    
- **Documentation**
  - minor cosmetic change to make the comments in the json structure be properly highlighted - [5f76bb9]( https://github.com/royriojas/esformatter-jsx/commit/5f76bb9 ), [Roy Riojas](https://github.com/Roy Riojas), 03/03/2015 07:20:04

    
  - Add comment about the best configuration to work with JSX files - [6a1135f]( https://github.com/royriojas/esformatter-jsx/commit/6a1135f ), [Roy Riojas](https://github.com/Roy Riojas), 02/03/2015 13:59:19

    
  - Add example url - [c39b4cc]( https://github.com/royriojas/esformatter-jsx/commit/c39b4cc ), [Roy Riojas](https://github.com/Roy Riojas), 28/02/2015 04:08:08

    
- **Build Scripts Changes**
  - bump minor version - [0dc5f6a]( https://github.com/royriojas/esformatter-jsx/commit/0dc5f6a ), [Roy Riojas](https://github.com/Roy Riojas), 28/02/2015 04:09:12

    
- **Tests Related fixes**
  - Add test for the case of an already formatted component - [4d28556]( https://github.com/royriojas/esformatter-jsx/commit/4d28556 ), [Roy Riojas](https://github.com/Roy Riojas), 27/02/2015 04:31:11

    
#### tag attributes
- **Bug Fixes**
  - prevent some tags from been formatted using the same escape list from `js-beautify.html` related to [#1](https://github.com/royriojas/esformatter-jsx/issues/1) - [3c2e2f7]( https://github.com/royriojas/esformatter-jsx/commit/3c2e2f7 ), [Roy Riojas](https://github.com/Roy Riojas), 01/03/2015 23:27:37

    
  - only try to format the attributes if the flag `attrsOnSameLineAsTag` is not true - [e1b9525]( https://github.com/royriojas/esformatter-jsx/commit/e1b9525 ), [Roy Riojas](https://github.com/Roy Riojas), 01/03/2015 21:29:50

    
- **Tests Related fixes**
  - Update tests - [4f1364b]( https://github.com/royriojas/esformatter-jsx/commit/4f1364b ), [Roy Riojas](https://github.com/Roy Riojas), 01/03/2015 21:36:21

    
- **Documentation**
  - Fixed quotes in the json configuration section in the README - [4ab8683]( https://github.com/royriojas/esformatter-jsx/commit/4ab8683 ), [Roy Riojas](https://github.com/Roy Riojas), 01/03/2015 19:56:32

    
- **Features**
  - Add option to format the attributes of a tag. Fix [#1](https://github.com/royriojas/esformatter-jsx/issues/1) - [653fad8]( https://github.com/royriojas/esformatter-jsx/commit/653fad8 ), [Roy Riojas](https://github.com/Roy Riojas), 01/03/2015 19:53:15

    
## v1.0.1
- **Documentation**
  - Fix formatting of the config example - [ef95fd7]( https://github.com/royriojas/esformatter-jsx/commit/ef95fd7 ), [Roy Riojas](https://github.com/Roy Riojas), 27/02/2015 04:17:06

    
## v1.0.0
- **Documentation**
  - Improved documentation - [b1e0c75]( https://github.com/royriojas/esformatter-jsx/commit/b1e0c75 ), [Roy Riojas](https://github.com/Roy Riojas), 27/02/2015 04:14:46

    
  - Fix incorrect plugin name in Readme - [2c6798a]( https://github.com/royriojas/esformatter-jsx/commit/2c6798a ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 17:19:04

    
  - Fix the build badge - [3988916]( https://github.com/royriojas/esformatter-jsx/commit/3988916 ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 06:20:00

    
  - Add a note about the failure to load the plugin using the configuration JSON - [13a137a]( https://github.com/royriojas/esformatter-jsx/commit/13a137a ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 05:52:32

    
  - Better Readme - [df8d9c1]( https://github.com/royriojas/esformatter-jsx/commit/df8d9c1 ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 05:24:49

    
- **Build Scripts Changes**
  - First commit - [c8d4d2b]( https://github.com/royriojas/esformatter-jsx/commit/c8d4d2b ), [Roy Riojas](https://github.com/Roy Riojas), 27/02/2015 04:13:55

    
  - Bump minor version - [66cd811]( https://github.com/royriojas/esformatter-jsx/commit/66cd811 ), [Roy Riojas](https://github.com/Roy Riojas), 26/02/2015 23:21:31

    
  - Update to latest fresh-falafel - [541d12c]( https://github.com/royriojas/esformatter-jsx/commit/541d12c ), [Roy Riojas](https://github.com/Roy Riojas), 26/02/2015 23:21:08

    
  - Bump the minor version - [dd3c10c]( https://github.com/royriojas/esformatter-jsx/commit/dd3c10c ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 06:27:43

    
  - Update fresh falafel dep - [6d0ccf5]( https://github.com/royriojas/esformatter-jsx/commit/6d0ccf5 ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 06:27:11

    
  - Bump the build version - [caa3306]( https://github.com/royriojas/esformatter-jsx/commit/caa3306 ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 06:20:35

    
  - Add missing travis.yml - [e6c0d3a]( https://github.com/royriojas/esformatter-jsx/commit/e6c0d3a ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 06:10:48

    
  - First commit - [75264a5]( https://github.com/royriojas/esformatter-jsx/commit/75264a5 ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 05:09:29

    
- **Other changes**
  - Add esprima-fb as peer dependecy to make travis happy - [1e73618]( https://github.com/royriojas/esformatter-jsx/commit/1e73618 ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 06:14:20

    
  - Initial commit - [aad4a63]( https://github.com/royriojas/esformatter-jsx/commit/aad4a63 ), [Roy Riojas](https://github.com/Roy Riojas), 24/02/2015 04:48:19

    
