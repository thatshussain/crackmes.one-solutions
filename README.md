# https://crackmes.one/crackme/6369871233c5d43ab4ece9f0
AntiDecompiler Cleaner ile kullanılan obfuscator kalıntılarını temizleyin, dnSpy32 ile temizlenen çıktıyı açın ve içerisinde kullanıcı adı ve şifreyi kontrol eden döngüyü bulun. Geri kalanını görseller üzerinden takip edebilirsiniz.

Kullanıcı adını bulmak için temizlenen çıktı üzerinde bu iki noktaya breakpoint bırakabilirsiniz.
![image](https://github.com/thatshussain/crackmes.one-solutions/assets/48627621/2489f6c5-0c13-4797-a523-3566bacd1e07)
![image](https://github.com/thatshussain/crackmes.one-solutions/assets/48627621/ab7168fb-a9b9-42c0-98ac-68f05000ceb5)

Şifreyi bulmak adına kullanıcı adının doğru yazıldığı fakat şifrenin yanlış olduğu döngüyü takip ederek belirlenen yerlere breakpoint bırakıyoruz.

![image](https://github.com/thatshussain/crackmes.one-solutions/assets/48627621/20c986ff-a292-4f5a-977d-4d8be30adb64)

# https://crackmes.one/crackme/648b46d733c5d43938913913

Herhangi bir şekilde şifrelenmemiş, dnSpy ile çözümlendiği an ortaya 20. satırda bulunan kullanıcıya ait bilgiler ortaya çıkıyor.
![image](https://github.com/thatshussain/crackmes.one-solutions/assets/48627621/b8a47ed7-065b-4543-9971-6b258e056464)

# https://crackmes.one/crackme/658ccd59edd4fa11fcd59bf3

Dosya içerisinde bulunan .dll uzantılı dosyayı dnSpy'da açıp direkt olarak gerekli satırlara erişebilirsiniz.
![image](https://github.com/thatshussain/crackmes.one-solutions/assets/48627621/cdd9b5f5-64ff-4f55-99c3-d15af0866dd1)

# https://crackmes.one/crackme/628ab7af33c5d45b75903ab4

Herhangi bir şifreleme yok, ana .exe uzantılı uygulamayı dnSpy'a aktarıp "bunifuButton1_Click" fonksiyonunu inceleyerek "8103535" sonucuna erişebilirsiniz.

![image](https://github.com/thatshussain/crackmes.one-solutions/assets/48627621/e11f64d4-c0fe-4ade-8567-04c70ddefeb7)

# https://crackmes.one/crackme/641d471733c5d447bc761c04
https://www.youtube.com/watch?v=fA8H_xInTuQ

# https://crackmes.one/crackme/647d3ade33c5d43938913668
AntiDecompiler Cleaner ile temizleyince direkt olarak uygulamaya ait ana methodların içerisinde sonuç karşımızda çıkıyor.

![image](https://github.com/thatshussain/crackmes.one-solutions/assets/48627621/cd9984a8-29a2-456d-bc88-839bbd7c71cf)

# https://crackmes.one/crackme/62265a2233c5d46c8bcc019f

Cleaner ile temizleyin, dnSpy ile giriş yapıp button1_Click methoduna baktığımızda "string b" değeri açıp hwid adresini önce byte daha sonra Base64 değere çevirerek şifreyi gelen çıktı yapıyor ve "textBox1.Text" ile karşılaştırıyor. Belirli yerlere breakpoint ekleyerek sonuca ulaşabilirsiniz.
![image](https://github.com/thatshussain/crackmes.one-solutions/assets/48627621/064e5023-c247-41a1-a361-4163ff0e1e6e)

