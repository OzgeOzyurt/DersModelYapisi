# DersModelYapisi

1) DersModelYapisi isminde yeni bir MVC projesi oluşturuldu.<br>
2) Product isminde bir model sınıfı oluşturuldu.<br>
  int Id <br>
  string Name<br>
  decimal Price<br><br>
3) CartProduct isminde bir model sınıfı oluşturuldu. <br>
  int Id<br>
  Product Product<br>
  int Quantity<br>
  decimal Price<br><br>
4) CartController controller'ı oluşturuldu.<br><br>
5) İçerisinde Index metodunda; 3 tane Product oluşturuldu.<br><br>
6) Bu 3 product nesnesini içeren 3 tane CartProduct nesnesi oluşturuldu. <br><br>
7) cartProducts isminde bir listede bu 3 tane CartProduct nesnesi View'e ViewModel olarak gönderildi.<br><br>
8) CartController içerisinde Index View oluşturuldu. Bu View içerisinde Sepet tablo olarak gösterildi.<br>
  https://getbootstrap.com/docs/5.1/content/tables/#overview<br><br>
9) Tablonun en altında sepet tutarının toplamı, KDV'si ve KDV'li tutarı da gösterildi.<br><br>
