#include<iostream>
using namespace std;
class operation{
	private:
		int a,b;
		public:
			void getdata();
			void sum();
			void sub();
			void mul();
			void div();
			void rem();
};
void operation::getdata(){
	cout<<"enter two numbers:";
	cin>>a>>b;
	}
void operation::sum(){
	cout<<"the sum is:"<<a+b<<endl;
}
void operation::sub(){
	cout<<"the sub is:"<<a-b<<endl;
}
void operation::mul(){
	cout<<"the mul is:"<<a*b<<endl;
}
void operation::div(){
	cout<<"the div is:"<<a/b<<endl;
}
void operation::rem(){
	cout<<"the rem is :"<<a%b<<endl;
}
int main(){
	operation b;
	b.getdata();
	b.sum();
	b.sub();
	b.mul();
	b.div();
	b.rem();
}
