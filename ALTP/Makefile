compiler: rule.y compiler.l
	yacc -f rule.y
	./flex compiler.l
	cc lex.yy.c y.tab.c -ll -ly
