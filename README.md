//# CGOJ-C081004
//成功電研108學年上學期C++基礎班10月賽 CGOJ C081004解密-電神們的莊若法言(單字版) 
#include<iostream>
#include<string>
using namespace std;
int main(){
	char q;
	cin>>q;
		if(q>=65&&q<=82){
			cout<<char(q+8);
		}else if(q>82&&q<=90){
			cout<<char(q-18);
		}else if(q>=97&&q<=114){
			cout<<char(q+8);
		}else if(q>114&&q<=121){
			cout<<char(q-18);
		}else if(q=='!'){
			cout<<"~";
		}else if(q=='.'){
			cout<<"。";
		}else if(q==','){
			cout<<" ";
		}
	return 0;
}
