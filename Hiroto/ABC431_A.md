<!--
https://atcoder.jp/contests/abc431/tasks/abc431_a
高橋くんは、頭パーツを 
1 個と体パーツを 
1 個組み合わせてロボットを 
1 体作ることができます。 ロボットは頭パーツの重さが体パーツの重さより大きいと倒れてしまいます。

現在、高橋くんは頭パーツと体パーツを 
1 個ずつ持っています。 高橋くんが持っている頭パーツの重さは 
H グラム、体パーツの重さは 
B グラムです。

高橋くんは、体パーツを重くすることで、ロボットを倒れないようにしたいです。 高橋くんが作るロボットが倒れないようにするためには、体パーツをあと何グラム重くする必要があるか求めてください。
-->
```c++
#include <bits/stdc++.h>
using namespace std;
typedef long long int ll;

int main(){
    ll h,b; cin >> h >> b;
    
    if(h <= b)cout << 0 << endl;
    else cout << h-b << endl;
}
```