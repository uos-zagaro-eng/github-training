<!--問題リンク:https://atcoder.jp/contests/abc086/tasks/abc086_a
問題：シカのAtCoDeerくんは二つの正整数 
a,b を見つけました。 
a と b の積が偶数か奇数か判定してください。-->

#　回答(C言語):
```C

include<stdio.c>

int main(void){
    int a,b;
    scanf("%d%d",%a,%b);
    if(a*b%2=0){
        printf("even");
    }else{
        printf("odd);
    }
}
```