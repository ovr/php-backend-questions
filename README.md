Inverview questions for PHP Backend Developer
=============================================

# Simple

#### 1. Describe all PHP's types.

#### 2. What is a "callable"? Write all allowed values for it.

#### 3. Write down all supported cycles structures

#### 4. Write all magic methods.

#### 5. What is a Closure?

#### 6. When __construct and __deconstruct will be called?

#### 7. What does it mean "GC"?

#### 8. What is dependency injection? Why is used? How does it relate to Composition?

#### 9. What is a "PDO" extension?

#### 10. What is a "ZTS"? Does PHP support thread(s) in core?

# OOP

### 1. What doest it mean OOP?

### 2. Describe the difference between Public, Protected, and Private.

### 3. What is a "class" and "object"?

### 4. What late "static" call is needed?

### 5. What’s the difference between "self" and "this"?

### 6. Why abstract class is needed? What is not allowed for abstract class?

### 7. Why interfaces is needed?

### 8. What is a "trait"? Why is it needed?

# Code Snippets

### 1. What does it output?

```php
class A extends stdClass {
}

$a = new A();
$a->property = 1;

$b = $a;
$a->property = 2;

var_dump($a);
var_dump($b);
```

Is it a same objects? How to get hash of objects?

### 2. What will be caused?

```php
$a = null;
$a->property = 12345;
var_dump($a);
```

# Internal

### 1. What is a "zval"? What is a "zend_value"? What is a union for structure?

### 2. Explain how is it possible "casting variables"? Write it down an example?

### 3. How is it working unary plus and unary minus?

### 3. Arrays? HashTable? What is a complexity of getting element from HashTable? How iteration is working in HashTable?

# Redis

### 1. Is it a persistent db?

### 2. Describe all supported types.

### 3. How to clear 2 database by redis-cli? And how to clear all databases?

### 4. How to get first 10 element(s) from list?

# Databases

### 1. What is a partitioning?

# PostgreSQL

### 1. What is a "hstore" type? For example We are having users table with meta column (hstore type) - How to set value in meta column?
