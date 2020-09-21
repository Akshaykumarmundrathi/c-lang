#include<stdio.h>
main(){
	int div(int x,int y){int i,k=y,lcm=1;
		for(i=2;i<=k;i++){
		if(x%i==0&&y%i==0){x=x/i;y=y/i;lcm=lcm*i;
		}if(i>y){break;
		}
		}
		return lcm=lcm*x*y;
	}
int a,b,lcm;
printf("enter the 1st number:");
scanf("%d",&a);
printf("enter the 2nd number:");
scanf("%d",&b);
if(a>b){lcm=div(a,b);

}else{lcm=div(b,a);
}
printf("LCM of %d and %d is:%d ",a,b,lcm);
}
