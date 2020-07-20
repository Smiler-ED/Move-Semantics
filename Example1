#include <iostream>

void value(const int &lref) 
{
    std::cout << "lvalue reference to const\n";
}
void value(int &&rref)
{
    std::cout << "rvalue reference\n";
}
int main()
{
    int a = 6;
    value(a);
    value(6); 
    return 0;
}
