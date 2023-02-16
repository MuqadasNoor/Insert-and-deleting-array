# Insert-and-deleting-array
REMOVING ARRAY



#include <iostream>
using namespace std;
int main() {
   int arr[5]={2 ,4,5,7,8},pos,i;
   cout<<"enter the pos of the element" <<endl;
   cin>>pos;
   for(int i=pos;i<5; i=i+1){
       arr[i]=arr[i+1];
       
   }
   cout<<"postion of the new arry is :"<<endl;
   for(i=0;i<4;i=i+1)
cout<<arr[i];
    return 0;
}
OUTPUT OF THE ARRAY:



enter the pos of the element
2
postion of the new arry is :
2478





STORING ARRAY 


 #include <iostream>
using namespace std;

int main() {
    int dragen[5];
    cout<<"enter 5 element:"<<endl;
    for(int i=0;i<5;i++)
    {
        cin>>dragen[i];
    }
    cout<<"first element is:"<<dragen[0]<<endl;
    cout<<"last element is:"<<dragen[4]<<endl;
    

    return 0;

}

OUTPUT:
enter 5 element:
1
2
3
4
5
first element is:1
last element is:5




