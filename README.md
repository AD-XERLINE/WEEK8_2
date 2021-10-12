# WEEK8_2
โปรแกรมรายสัปดาห์ที่ 8 อันที่ 2

    #include <stdio.h> 

    int main() { 
    int n;     

    printf("Enter number : ");     
    scanf("%d",&n);     

    for(int i=1;i<=n;i++){
    	for(int j=1;j<=n;j++){
    		if (i==1 || i== n){
   			printf("*");
  		}
  	    else if (j==1 || j==n){
 	    	printf("*");
		}
		else
		{
		printf(" ");
		}	
	  }
    printf("\n");
    }
    }
