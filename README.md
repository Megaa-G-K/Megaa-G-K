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
	cout<<"Enter two numbers:";
	cin>>a>>b;
	}
void operation::sum(){
	cout<<"The Sum is:"<<a+b<<endl;
}
void operation::sub(){
	cout<<"The Difference is:"<<a-b<<endl;
}
void operation::mul(){
	cout<<"The Product is:"<<a*b<<endl;
}
void operation::div(){
	cout<<"The division is:"<<a/b<<endl;
}
void operation::rem(){
	cout<<"The Modulus is :"<<a%b<<endl;
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
