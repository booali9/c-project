# c-project
FIRST C PROJECT
<br>
AUTHOUR -BOOALI KAZMI


#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
{
	int i,n,sum=0;
	
	printf("\nenter no of dice roll\n");
	scanf ("%d",&n);
	int arr[n];
	srand(time(NULL));
	
	for(i=0;i<=n;i++){
		arr[i]=(rand()%6)+1;
		
		if(arr[i-1]==1)
		{
			sum==0;
			
		}
		if(arr[i-1]==6)
		{
			sum+=(arr[i]*10);
		}
		if(arr[i-1]==3){
			
		sum+=(arr[i]*2);
	}
	
	if(arr[i-1]==2){
		sum+=arr[i]*0;
		
	}
	if(arr[i-1]==5){
		sum+=arr[i]*1;
	}
	if (arr[i-1]==4){
		sum+=arr[i]*0;
	}
	}
	
	printf("prize=%d$",sum);
	
	
	
	
	
	
}

