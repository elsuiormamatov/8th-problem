# 8th-problem
#include <iostream>
#include <cmath>

using namespace std;

int main() {
  float x, y, z;
  cout << "Введите количество жителей? ";
  cin >> x;
  cout << "Введите площадь территории? ";
  cin >> y;
  z = x/y;
  cout << "Плотность население этого территории "<< z<<endl;

  return 0;
  // cout << ". Известны количество жителей в государстве и площадь его территории. Определить плотность населения в этом государстве";
}
