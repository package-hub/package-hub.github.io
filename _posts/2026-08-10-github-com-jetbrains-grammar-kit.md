---
title: Grammar-Kit
categories: ['java', 'grammar', 'intellij']
---
## [Grammar-Kit](https://github.com/JetBrains/Grammar-Kit)

### Grammar files support & parser/PSI generation for IntelliJ IDEA


1. *private* (PSI tree): skip node creation and let its child nodes be included in its parent. 
2. *left* (PSI tree):  take an AST node on the left (previous sibling) and enclose it by becoming its parent. 
3. *inner* (PSI tree):  take an AST node on the left (previous sibling) and inject itself into it by becoming its child.
4. *upper* (PSI tree):  take the parent node and replace it by adopting all its children.

5. *meta* (parser):  a parametrized rule; its parse function can take other parse functions as parameters.
6. *external* (parser):  a rule with a hand-written parse function; no parsing code is generated. 
   
7. *fake* (PSI classes):  a rule for shaping the generated PSI classes; only PSI classes are generated.

Modifiers can be combined, *inner* should only be used together with *left*,
*private left* is equivalent to *private left inner*, 
*fake* should not be combined with *private*.

By default, rules are *public*, i.e. *non-private*, *non-fake*, etc.
