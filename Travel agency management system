#include <iostream>
#include <string>
#include <cstdlib>
using namespace std;

class travel
{
  string name;
  int pass_no;
  string place;

  public:

    travel()
      {
          name="######";
          pass_no=0;
          place="######";
      }


    void del_travel()
      {
          name="######";
          pass_no=0;
          place="######";
      }


    void details()
      {
          cout<<"\n\t\tEnter name :  ";
          cin>>name;
          cout<<"\n\t\tEnter number of passengers :  ";
          cin>>pass_no;
          cout<<"\n\t\tEnter travel destination :  ";
          cin>>place;
      }


    void d_display()
      {
           cout<<" \n\t\tName :  "<<name<<endl;
           cout<<" \n\t\tNumber of passengers :  "<<pass_no<<endl;
           cout<<" \n\t\ttravel destination :  "<<place<<endl;
      }

    void edetails()
      {
          system("clear");

          int ch,flag=1;

    while(flag)
       {
           system("clear");

        cout<<"\n\t\t*************** EDIT DETAILS ***************"<<endl;
        cout<<"\n\t\t\t1)Name :  "<<name<<endl;
        cout<<"\n\t\t\t2)Number of passengers :  "<<pass_no<<endl;
        cout<<"\n\t\t\t3)Travel destination :  "<<place<<endl;
        cout<<"\n\t\t\t4)Exit"<<endl;
        cout<<"\n\t\t--------------------------------------------";
        cout<<"\n\t\tYour Choice :   ";
        cin>>ch;

    switch(ch)
        {
            case 1: cout<<"\n\t\tEnter name :  ";
                    cin>>name;
                    break;
            case 2: cout<<"\n\t\tEnter number of passengers :  ";
                    cin>>pass_no;
                    break;
            case 3: cout<<"\n\t\tEnter travel destination :  ";
                    cin>>place;
                    break;
            case 4: flag=0;
                    break;
            default: cout<<"\n\t\tWrong Choice"<<endl;
                            break;
        } } }
};


class booking:public travel
{
   string date;
   string transport;
   string hotel;
   int no_of_days;

   public:

    booking()
       {
           date="##/##/##";
           transport="######";
           hotel="######";
           no_of_days=0;
       }


    void del_booking()
       {
           date="##/##/##";
           transport="######";
           hotel="######";
           no_of_days=0;
       }


    void book_transport()
       {
           cout<<"\n\t\tEnter date of travel :  ";
           cin>>date;
           cout<<"\n\t\tEnter type of transport :  ";
           cin>>transport;
       }

    void book_stay()
       {
           cout<<"\n\t\tEnter number of days :  ";
           cin>>no_of_days;
           cout<<"\n\t\tEnter name of the hotel :  ";
           cin>>hotel;
       }


    void tran_display()
      {
           cout<<" \n\t\tDate of travel :  "<<date<<endl;
           cout<<" \n\t\tType of transport :  "<<transport<<endl;
      }

    void stay_display()
      {
           cout<<" \n\t\tNumber of days :  "<<no_of_days<<endl;
           cout<<" \n\t\tName of the hotel :  "<<hotel<<endl;
      }

    void ebook_tran()
      {
          system("clear");

          int ch,flag=1;

    while(flag)
       {
           system("clear");

        cout<<"\n\t\t************** EDIT TRANSPORT **************"<<endl;
        cout<<"\n\t\t\t1)Date of travel :  "<<date<<endl;
        cout<<"\n\t\t\t2)Type of transport :  "<<transport<<endl;
        cout<<"\n\t\t\t3)Exit"<<endl;
        cout<<"\n\t\t--------------------------------------------";
        cout<<"\n\t\tYour Choice :   ";
        cin>>ch;

    switch(ch)
        {
            case 1: cout<<"\n\t\tEnter date of travel :  ";
                    cin>>date;
                    break;
            case 2: cout<<"\n\t\tEnter type of transport :  ";
                    cin>>transport;
                    break;

            case 3: flag=0;
                    break;
            default: cout<<"\n\t\tWrong Choice"<<endl;
                            break;
        } } }


    void ebook_stay()
      {
          system("clear");

          int ch,flag=1;

    while(flag)
       {
           system("clear");

        cout<<"\n\t\t**************** EDIT STAY ****************"<<endl;
        cout<<"\n\t\t\t1)Number of days :  "<<no_of_days<<endl;
        cout<<"\n\t\t\t2)Name of the hotel :  "<<hotel<<endl;
        cout<<"\n\t\t\t3)Exit"<<endl;
        cout<<"\n\t\t-------------------------------------------";
        cout<<"\n\t\tYour Choice :   ";
        cin>>ch;

    switch(ch)
        {
            case 1: cout<<"\n\t\tEnter number of days :  ";
                    cin>>no_of_days;
                    break;
            case 2:  cout<<"\n\t\tEnter name of the hotel :  ";
                     cin>>hotel;
                    break;

            case 3: flag=0;
                    break;
            default: cout<<"\n\t\tWrong Choice"<<endl;
                            break;
        } } }

};


class payment:public booking
{
    string ph_no;
    int tran_price;
    int stay_price;

    public:

    payment()
        {
           ph_no="##########";
           tran_price=0;
           stay_price=0;
        }


    void del_payment()
        {
           ph_no="##########";
           tran_price=0;
           stay_price=0;
        }


    void total_price()
        {
            cout<<"\n\t\tEnter phone number :  ";
            cin>>ph_no;
            cout<<"\n\t\tEnter transport price :  ";
            cin>>tran_price;
            cout<<"\n\t\tEnter stay price :  ";
            cin>>stay_price;
        }


    void price_display()
        {
            cout<<" \n\t\tPhone number :  "<<ph_no<<endl;
            cout<<" \n\t\tTransport price :  "<<tran_price<<endl;
            cout<<" \n\t\tStay price :  "<<stay_price<<endl;
            cout<<" \n\t\tTotal price : "<<tran_price + stay_price<<endl;
        }


    void etotal_price()
      {
          system("clear");

          int ch,flag=1;

    while(flag)
       {
           system("clear");

        cout<<"\n\t\t*************** EDIT PAYMENT ***************"<<endl;
        cout<<"\n\t\t\t1)Phone number :  "<<ph_no<<endl;
        cout<<"\n\t\t\t2)Transport price :  "<<tran_price<<endl;
        cout<<"\n\t\t\t3)Stay price :  "<<stay_price<<endl;
        cout<<"\n\t\t\t4)Exit"<<endl;
        cout<<"\n\t\t--------------------------------------------";
        cout<<"\n\t\tYour Choice :   ";
        cin>>ch;

    switch(ch)
        {
            case 1: cout<<"\n\t\tEnter phone number :  ";
                    cin>>ph_no;
                    break;

            case 2: cout<<"\n\t\tEnter transport price :  ";
                    cin>>tran_price;
                    break;
            case 3: cout<<"\n\t\tEnter stay price :  ";
                    cin>>stay_price;
                    break;

            case 4: flag=0;
                    break;
            default: cout<<"\n\t\tWrong Choice"<<endl;
                            break;
        } } }

    void edit()
        {
            system("clear");

            int ch,flag1=1;

        while(flag1)
           {
               system("clear");

                cout<<"\n\t\t******************* EDIT *******************"<<endl;
                cout<<"\n\t\t\t1)Edit Details  "<<endl;
                cout<<"\n\t\t\t2)Edit Transport  "<<endl;
                cout<<"\n\t\t\t3)Edit Stay  "<<endl;
                cout<<"\n\t\t\t4)Edit Payment "<<endl;
                cout<<"\n\t\t\t5)Exit"<<endl;
                cout<<"\n\t\t--------------------------------------------";
                cout<<"\n\t\tYour Choice :   ";
                cin>>ch;

                switch(ch)
                {
                    case 1: payment::edetails();
                            break;
                    case 2: payment::ebook_tran();
                            break;
                    case 3: payment::ebook_stay();
                            break;
                    case 4: etotal_price();
                            break;
                    case 5: flag1=0;
                            break;
                    default: cout<<"\n\t\tWrong Choice"<<endl;
                                    break;
                } } }


    void show()
        { system("clear");

         int flag=1;

    while(flag)
        {
            payment::d_display();
            payment::tran_display();
            payment::stay_display();
            payment::price_display();
            cout<<"\n\t\t--------------------------------------------";
            cout<<"\n\t\tEnter 0 to exit :  ";
            cin>>flag;
        } }

    void cancel()
        {
            system("clear");

            int flag=1;
        while(flag)
          {
            payment::del_travel();
            payment::del_booking();
            del_payment();
            cout<<"\n\n\n\t\t************** Order canceled **************";
            cout<<"\n\n\n\t\t--------------------------------------------";
            cout<<"\n\n\n\t\tEnter 0 to continue : ";
            cin>>flag;
        }}
};


int main()
    {
        system("clear");

        payment order;
        int choice;

    while(1)
        {

            system("clear");

            cout<<"\n\t\t************** TRAVEL AGENCY *************"<<endl;

            cout<<"\n\t\t\t1) Enter Details\n"<<endl;
            cout<<"\t\t\t2) Book Transport\n"<<endl;
            cout<<"\t\t\t3) Book Stay\n"<<endl;
            cout<<"\t\t\t4) Payment\n"<<endl;
            cout<<"\t\t\t5) Preview order\n"<<endl;
            cout<<"\t\t\t6) Edit order\n"<<endl;
            cout<<"\t\t\t7) Cancel order\n"<<endl;
            cout<<"\t\t\t8) Exit"<<endl;
            cout<<"\n\t\t-------------------------------------------";
            cout<<"\n\t\tYour Choice :   ";
            cin>>choice;

        switch(choice)
            {
                case 1: order.details();
                        break;
                case 2: order.book_transport();
                        break;
                case 3: order.book_stay();
                        break;
                case 4: order.total_price();
                        break;
                case 5: order.show();
                        break;
                case 6: order.edit();
                        break;
                case 7: order.cancel();
                        break;
                case 8: cout<<"\n\n\t\tSuccessfully Logged out \n\n\t\tVisit Again!"<<endl<<"\n\t\t<Thank You>\nS";
                        exit(0);
                        break;
                default: cout<<"Wrong Choice"<<endl;
                                break;

            } } }
