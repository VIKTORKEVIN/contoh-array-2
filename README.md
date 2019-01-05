# contoh-array-2

    #include<stdio.h>
    #include<conio.h>

    int main()
    {
    int bil[7],i;
    printf("elemen 1 ? ");scanf("%d",&bil[0]);
    bil[1] = 5;
    bil[2] = bil[1] + 20;
    for(i=4;i<7;i++) bil[1] = 1*10;
    bil[3] = bil[bil[1]];
    for(i=0;i<7;i++) printf("bil[%d] %d dan alamatnya: %x\n",i,bil[i],&bil[i]);
    getch();
    return 0;
    }
    
![img](https://raw.githubusercontent.com/VIKTORKEVIN/contoh-array-2/master/contoh%20array%202.png)
