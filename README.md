#include <stdio.h>
#include <conio.h>
#define i 0
int main(int argc, char *argv[])
{
	
	textcolor(CYAN);
	textbackground(BLACK);
	
	char c;
	
	do{
	/*if (getch() == 65)*/
	
	 /*if(getch() == 32)
	{
		break;
	}*/

	c = getch();
	
	/*if (c == 10)
	{
		puts("\n");
	}
	*/
	
	printf("Foi um [%c]e o seu valor na tabela \"ASCII\" é: {%i}\n",c,c);
	
	}while(i < 1);
}
