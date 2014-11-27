CSV-test-files
==============

CSV test files with different encodings and delimiter.

The data are always the same. Here it is.

```
header;type of data;third_column;fourth_column;fifth_column;sixth_column
doc;type of data;data;idem third column with a space;idem fourth column with a trailing space;idem fifth column wo trailing delimiter
data;ASCII text;aaaaaa; aaaaa; a ;  a
data;Accented french text;démo àéèçÿ; démo àéèçÿ; à ;
data;Accented french text CAP;DÉMO; DÉMO ÀÉÈÇŸ; À ;
data;Euro letter (not in ISO 8859-1 but 8859-15);€; €;  € ;  € 
data;Price in euros;10€; 10€; 10€ ;  10€ 
data;Price in euros;€10; €10; €10 ;  €10 
data;Price in dollars;10$; 10$; 10$ ;  10$ 
data;Price in dollars;$10; $10; $10 ;  $10 
data;Number ten;10; 10;  10 ;  10 
data;Number one hundred thousand;100000; 100000;  100000 ;  100000
data;Number one hundred thousand with a space;100 000; 100 000;  100 000 ; 100 000 
data;Number one hundred thousand with a point;100.000; 100.000;  100.000 ; 100.000 
data;Number one hundred thousand with a comma;100,000; 100,000;  100,000 ; 100,000 
data;Numbers with point;0.5; 0.5; 
data;Numbers with comma;0,5; 0,5; 
data;Numbers;"133.55";"-133.55";"133.55-";"133,55";"-133,55";"133,55-"
data;Numbers as numbers;133.55;-133.55;133.55-;133,55;-133,55;133,55-
data;Numbers (000100);000100; 000100;  000100 ;  0000100 
data;Numbers (000100);"000100";" 000100";" 000100";"  0000100 "
data;Date ISO 8601;1977-04-22; 1977-04-22;  1977-04-22 ;  1977-04-22 
data;Date ISO 8601;19770422; 19770422;  19770422 ;  19770422 
data;Date ISO 8601;1977-04-22T01:00:00-05:00;
data;Date ISO 8601;1977-04-22T06:00:00Z; 
data;Calc;=100/2;"=100/2";'=100/2;"'=100/2";
data;Calc;100/2;"100/2";'100/2;"'100/2";
data;Space, alone; ;  ;   ;    
data;Smiley composed in ASCII letters;:-); :-);  :-) ;  :-) 
data;Smiley as a symbol;☺; ☺;  ☺ ;  ☺ 
data;Omega letter (greek alphabet);ω; ω;  ω ;  ω 
data;G-clef (only UTF8);𝄞; 𝄞;  𝄞 ;  𝄞  
```
