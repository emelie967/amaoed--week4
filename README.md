# include<iostream>
  
  using namespace std;
  
  class Employee
  {
     int eid;
     char ename[100];
     float basic_saraly,hra,da,i_tax,net_saraly;
     
     public:
     void accept_details()
     {
     
     cout<<"\n Enter Emplyee id:";
     cin>>eid;
     cout<<"\n Enter Employee Name:";
     cin>>ename;
     cout<,"\n Enter Basic Saraly:";
     cin>>basic_saraly;
     
     hra=800;
     da = 0.25*basic_saraly;
     i_tax = 0.15*basic_saraly;
     net_saraly=basic_saraly+da+hra-i_tax;
     
     }
      void display_details()
      {
      cout<<"\n-----------";
      cout<<"\n Employee id    :"<<eid;
      cout<<"\n Employee Name :"<<ename;
      cout<<"\n Basic Saraly :"
  <<basic_saraly;
      cout<<"\n HRA             :"<<hra;
      cout<<"\n DA              :"<<da:
      cout<<"\n I-TAX;          :"<<i_tax;
      cout<<"\n Net Saraly      :"<<net_saraly;
      }
   };
   int main()
   {
     Employee e;
     e.accept_details():
     e.display_details();
     return 0;
   }
   
     
     
