Game C++: Catching Fruit: (Visual Studio 2017)

* Luật chơi:
  - Di chuyển ếch để ăn hoa quả rơi
  - Ăn hoa quả +1 điểm, ăn ngôi sao +5 điểm
  - Đụng phải bom sẽ game over
  - Bỏ sót 3 hoa quả  sẽ game over 
  - Bỏ sót ngôi sao không bị trừ điểm

* Gồm 4 module và main.cpp:
   - (game.h , game.cpp): Khởi tạo các đối tượng biến chung và các hàng chung
   - (BaseObject.h, BaseOject.cpp): các hàm cơ sở cho đối tượng
   - (MainObject.h, MainObject.cpp): khởi tạo các thông số của đối tượng chính (ếch), các hàm di chuyển của đối tượng chính, dùng class
   - (FruitObject.h. FruitObject.cpp): khởi tạo các thông số của đối tượng hoa quả, các hàm rơi, tốc độ rơi, reset hoa quả, dùng class
   - main.cpp: hàm xử lý chính, gồm: hàm menu, hàm gameover, xử lý di chuyển đối tượng chạy qua lại, ghi điểm số.

 
