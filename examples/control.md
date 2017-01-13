# Example
If else
```
<?php
if ($expr1) {
    // if body
} elseif ($expr2) {
    // elseif body
} else {
    // else body;
}

```
Switch case
```
<?php
switch ($expr) {
    case 0:
        echo 'First case, with a break';
        break;
    case 1:
        echo 'Second case, which falls through';
        // no break
    case 2:
    case 3:
    case 4:
        echo 'Third case, return instead of break';
        return;
    default:
        echo 'Default case';
        break;
}

```
While
```
<?php
while ($expr) {
    // structure body
}

```

For loop.
```<?php
for ($i = 0; $i < 10; $i++) {
    // for body
}

```
Foreach loop
```
<?php
foreach ($iterable as $key => $value) {
    // foreach body
}

```
[Home](../index.md)
