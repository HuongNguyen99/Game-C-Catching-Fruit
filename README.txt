Game Catching Fruit: (Visual Studio 2017)

1, Cac chuc nang chinh
* Luat choi:
  - Di chuyen ech de an hoa qua roi
  - An hoa qua +1 diem, an ong sao +5 diem
  - An bom se game over
  - An không trung 3 qua se game over 
  - An không trung ong sao cung không sao

* Gom 4 module và main.cpp:
   - (game.h , game.cpp): khoi tao các doi tuong bien chung và các ham chung
   - (BaseObject.h, BaseOject.cpp): các ham co so cho doi tuong
   - (MainObject.h, MainObject.cpp): khoi tao cac thong so cua doi tuong chinh, dung class, các ham di chuyen
   - (FruitObject.h. FruitObject.cpp): khoi tao các thong so cua hoa qua, dung class, các ham di chuyen, reset qua, toc do qua
   - main.cpp: ham menu, ham gameover, xu li di chuyen ðoi tuong, chay qua, ghi diem so
