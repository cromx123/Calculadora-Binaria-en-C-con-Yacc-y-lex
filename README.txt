***Si descargas solo los 2 principales lo puedes compilar en linux como se muestra mas abajo
1) calc.l 
2) calc.y 

***MODO DE COMPILACION***
//debes estar apuntando a donde guardaste los archivos

1) yacc -d Calculadora.y
1) flex Calculadora.lex
2) gcc -o Calculadora  y.tab.c lex.yy.c -ll
3) ./[nombre con extension .exe]
