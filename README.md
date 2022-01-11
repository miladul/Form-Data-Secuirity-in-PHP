# Form-Data-Secuirity-in-PHP
Data Security for HTML form in PHP/Laravel

$a = '#include <stdio.h>int main() {
   printf("Hello, World!");
   return 0;
}';

//encode for store database

$b = base64_encode($a);

//decode for view the orginal formate

$c = base64_decode($b);

dd( $a, $b, $c);
