
#include <iostream>
#include <fstream>
#include <string>
using namespace std;
//it will store contact details in your E drive 
int main()
{ //ofstream outPut("file1.txt");//opening file using constructor for writing
    fstream outPut("E:Contact.txt",ios::out|ios::app);
    if(outPut.is_open())
    {
        cout<<"file open successfully"<<endl;
    }
    else
    cout<<"file not open!"<<endl;
    string myNAME;
    long long Contact;
    cout << "write  your full name : ";
    getline(cin, myNAME);
    cout<<"write your contact number : ";
    cin>>Contact;
    
    // outPut << "I am writing in file" << endl;
    outPut <<"Name:->" <<myNAME<<endl; //in new line
    outPut<<"Contact number:->"<<Contact<<endl;
    outPut.close();
    return 0;
}
