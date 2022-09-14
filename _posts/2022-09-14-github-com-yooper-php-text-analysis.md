---
title: php-text-analysis
categories: ['php', 'nlp', 'tokenization']
---
## [php-text-analysis](https://github.com/yooper/php-text-analysis)

### PHP Text Analysis is a library for performing Information Retrieval (IR) and Natural Language Processing (NLP) tasks using the PHP language

```php
$tokens = tokenize($text);
```

You can customize which type of tokenizer to tokenize with by passing in the name of the tokenizer class
```php
$tokens = tokenize($text, \TextAnalysis\Tokenizers\PennTreeBankTokenizer::class);
```
The default tokenizer is **\TextAnalysis\Tokenizers\GeneralTokenizer::class** . Some tokenizers require parameters to be set upon instantiation. 
