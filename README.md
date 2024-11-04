#include <stdio.h>
int main(){
printf("Exercice 01:\n   Question 1.1:\n"); 
printf("\n");
int A[20][20],i,O[20][20],j,n; 
char R[5][5]={{'1','2','3','4','5'},{'7','a','c','8','d'},{'c','9','4','z','8'},{'5','6','p','n','3'},{'2','9','t','m','k'}};

for(i=0;i<5;i++){
for(j=0;j<5;j++){
printf("\t%c",R[i][j]);}
printf("\n");}

printf("\n pair=\n");
for(i=0;i<5;i+=2){
 for(j=0;j<5;j++){
printf("\t%c",R[i][j]);
}
printf("\n");
}

printf("\n impair=\n");
for(i=1;i<5;i+=2){
 for(j=0;j<5;j++){
printf("\t%c",R[i][j]);
}
printf("\n");
}
printf("\n");  

printf("   Question 1.2:\n"); 
printf("\nla 1e diagonale=\tla 2e diagonale=\n");
for(i=0,j=4;i<5;i++,j--){
printf("%c",R[i][i]);
printf("\t\t\t  %c",R[i][j]);
printf("\n");
}
return 0;
}
