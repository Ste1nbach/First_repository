# Podmínky if, else if

1) Do  ```If()  ```zapisujeme vždy nějakou podmínku např. x > 0, když je pravdivá tak se provede
 	 kod v podmince
 2) Do ``` if else () ``` zapisujeme stejně jako do  ```if() ``` podmínku
 3) Když není ani jedna podmínka pravdivá, tak  program přejde do  ```else  ```a nebude se ptát znovu




```java
int x = 1;
int y = 2;
int c = 3;

if(x>=y && x>=c ) {
     System.out.println( "x je nejvetsi" );
 } else if(y>=x && y>=c){
     System.out.println("y je nejvetsi");
	 } else if(c>=x && c>=y) {
	 System.out.println("c je nejvetsi");
	 }
	 else {
     System.out.println( "cisla se rovnaji" );
 }
 ```