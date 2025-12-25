Input_Set_Type_#.*
Input 	- 0 (scan) or 1 (photo)
Set 	- number of set (1-7 for photo, 0 and 1 for scna)
Type 	- 01-11
#	- number of sample (1-5)

Types:
1)	Договор аренды; 
2)	Акт приёма-передачи; 
3)	Заявление на отпуск.
4)	Договор купли-продажи; 
5)	Авансовый отчёт; 
6)	Торговая накладная (ТОРГ-12); 
7)	Налоговая справка (2-НДФЛ);
8)	Универсальный передаточный документ (УПД);
9)	Доверенность; 
10)	Счёт оплаты;
11)	Устав организации;

Folders:
IMA 	- jpeg images 
CSV	-  result of reconition converted from *.TXT. Format:
		W; X1;Y1; X2;Y1; X2;Y2; X1;Y2; NB;NP;NL; SW; 
		set of chars:
			number of chars (N); <N chars>
			one char:
				bound rectangle of char C; NC; char name C; score of char SC; ... ;

