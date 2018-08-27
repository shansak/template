#include<iostream>


using namespace std;

template<class T>
void swap(T x,T y)
{
    T temp=x;
    x=y;
    y=temp;
}


    void fun(int m,int n, float a,float b)
   {
      cout<<"before"<<m<<" "<<n;
      swap(m,n);

      cout<<"after"<<m<<" "<<n;

      cout<<"before"<<a<<" "<<b ;
       swap(a,b);

       cout<<"after"<<a<<" "<<b;

    }

int main()
{
    fun(100,200,11.22,33.13);

    return 0;
}

