# Sublime PHP Snippets

## Instalation

Clone this repo into `Sublime Text 3/Packages/User/`<br><br>
For everybody on Mac's, this will be located in `~/Library/Application Support/Packages/User/`

## Snippets

<h5> pubf / prof / prif </h5>

Expands to a public, protected or private functions, respectivly

```php
class MyClass {
    pubf
}

class MyClass {
    public function {}({}) {
    	{}
    }
}
```

<h5> ppre </h5>

Expands to a `print_r` statment wrapped in \<pre\> tags

```php
ppre

echo "<pre>";
print_r({});
echo "</pre>";
```

<h5> dpre </h5>
Same as `ppre`, but uses `var_dump` instead

```php
dpre

echo "<pre>";
var_dump({});
echo "</pre>";
```
