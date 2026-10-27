#include<iostream>
using namespace std;
class basic_info
{
protected:
char name[30];
int emp_Id;
public:
basic_info()
{
cout<<"\nEnter name of employee:";
cin>>name;
cout<<"\nEnter employee ID:";
cin>>emp_Id;
}
};

class Dept_info
{
protected:
char Dept_name[15];
char work_assign[50];
public:
Dept_info()
{
cout<<"\nEnter name of department:";
cin>>Dept_name;
cout<<"\nEnter work assigned:";
cin>>work_assign;
}
};
class employee_info:public basic_info,public Dept_info
{
public:
employee_info()
{
cout << "\nEmployee information entered successfully.\n";
}
void basic_info()
{
cout<<"Basic information is:";

basic_info();
cout<<"\nDepartment information is:";
Dept_info();
}
void display_info()
{
cout << "\nEmployee Basic info is:\n";
basic_info();
cout << "\nEmployee dept info is:\n";
Dept_info();
}
};
int main()
{
int i,n;
employee_info emp[50];
cout<<"Enter no. of employee:";
cin>>n;
for(i=0;i<n;i++)
emp[i].display_info();
return 0;
}
