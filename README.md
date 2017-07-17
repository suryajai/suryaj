#include <stdio.h>
#include <conio.h>
void main() {
	char *b;
	int i,len,flag=0;
	clrscr();
	printf("\nENTER A STRING: ");
	gets(b);
	len=strlen(b);
	for (i=0;i<len;i++) {
		if(a[i]==b[len-i-1])
		     flag=flag+1;
	}
	if(flag==len)
	             printf("\nTHE STRING IS PALINDROME");
               else
	             printf("\nTHE STRING IS NOT PALINDROME");
	getch();
}
