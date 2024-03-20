#include<iostream>
using namespace std;
class dayofyear{
	private:
	const	int date;
	const	int month;
	const	int year;
		public:
			dayofyear(int d,int m,int y):date(d),month(m),year(y){
				
			}
			int getdate() const{
				return date;
			}
			int getmonth() const{
				return month;
			}
			int getyear() const{
				return year;
			}
			
			
			
};
int main(){
const dayofyear ind(14,8,1947);
	
	cout<<ind.getdate()<<" / "<<ind.getmonth()<<" / "<<ind.getyear()<<endl;
}
