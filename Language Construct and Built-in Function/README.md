<!-- @format -->

# Language Construct and Functions

<p>In php there are some keyword which is used with or without parenthesis, generally those keyword known as <b>Language Constructs</b>. The purpose of using Language Construct is almost same as  functions. Although there are many differences.</p>

### What is Language Construct ?

<p> Most of the time people misinterpret about language construct and functions, because these are mostly alike. They have different role and interpreter interprets them their own way. Every programming language consists of tokens and structures which the respective language parser can recognize. So whenever a file is parsed, the parser understands their usage and knows well what to do with them without having the need to examine them further. These tokens and structures are known as language construct. They are the syntax of a language. In other words they are basically keywords. Following are some examples of language constructs</p>

<li>echo()</li>
<li>include()</li>
<li>require()</li>
<li>print()</li>
<li>isset()</li>
<li>die()</li>
<br>

    Note: Language constructs cannot be added to the PHP framework through any plugins or libraries.
    They may or may not return any values although most of them don’t.
    Also, some of them do not need the use of parenthesis.

<br>

### What is built-in function ?

<p>On the other hand, built-in functions are blocks of code that are jotted down in such a way that they can be reused again and again in executing a specific task. They are already present in the PHP installation package. It is due to these built-in functions that PHP is an efficient scripting language.
Some common built-in functions used in PHP are:</p>
    
<li>json_encode()</li>
<li>mail()</li>
<li>explode()</li>
<li>rand()</li>
<li>curl_init()</li>

<br>

    Built-in functions are comparatively slower than their language construct counterparts.
    They have better code organization. They usually take input arguments and always return a
    value. Built-in functions usually comprise of date, numeric and string functions.
