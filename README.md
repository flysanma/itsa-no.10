# itsa-no.10
#include <iostream>
  
using namespace std;  
  
int main() 
{  
  
    int a,b; //定義變數 
  
    while (cin >> a >> b)  
    {  
        while (b!=0)  //當變數不等於零時，持續執行迴圈內容
        {  
            int temp=b;  //宣告temp等於b
            b = a % b;  //b等於a除以b
            a = temp;  //a等於temp
        }  
        cout << a << "\n";  //輸出a
    }  
    return 0;  
}  
