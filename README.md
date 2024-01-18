# React-Hook-Form-ve-React-Toastify-K-t-phaneleri
Görev 1: Başarılı Giriş Toastify Mesajı

Çalıştığın şirkette yakın zamanda yaptığın bir projede toastify mesajlarını kullanmayı öğrendin. Hemen kendi sitene de eklemek istiyorsun.

Kullanıcı başarılı login olduğunda Merhaba {userName}, tekrar hoş geldin., başarısız bir girişte de bir hata mesajı olarak Girdiğiniz bilgilerle bir kullanıcı bulamadık. göstereceksin.

Örnek kullanıcı:

İpucu: toast.success(MESAJ) toast.error(MESAJ) şeklinde kullanabilirsin.
İpucu: Başarılı giriş testi için erdem.guntay@wit.com.tr adresini 9fxIH0GXesEwH_I şifresini kullanabilirsin.

Gün Projesi: Task Yönetimi -> React Hook Form Geçişi

Çalıştığın şirkette task yönetimi için geliştirilmiş uygulamada, form validasyonu için Yup kütüphanesi kullanılmış. Fakat, Yup'da keşfedilen bir güvenlik açığı yüzünden validasyon'ları react-hook-forma dönüştürülmesi isteniyor.

Bunun için TaskForm component'indeki formSemasi değişkeninde tamamlanmış validasyon kurallarını aynı html yapısı ile TaskHookForm component'inde yapman isteniyor. (Görev 1/3)

Test yaparken de tamamlandı butonunun çalışmadığını fark ettin. Tıklandığında ilgili task'in status'ünü 'yapıldı' yaparak bu sorunu çözebilirsin. (Görev 2/3)

Hazır form'a el atmışken de başarı mesajlarını react-toastifyile ekranda çıkarman isteniyor. (Görev 3/3)

Yeni bir kişi eklendiğinde "Yeni kişi oluşturuldu." mesajını,
Yeni bir task eklendiğinde "Yeni görev oluşturuldu." mesajını,
Bir görev tamamlandı olduğunda "{id} idli görev tamamlandı." mesajını kullanabilirsin.

