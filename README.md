# SwiftYasamDongusuKonuAnlatimi
iOS uygulama geliştirme çerçevesinde sıkça kullanılan "UIViewController" sınıfının özel metotlarına ait. Bu metotlar, bir view controller'ın yaşam
döngüsünün farklı aşamalarında otomatik olarak çağrılır ve bu aşamalarda çeşitli işlemler gerçekleştirilir. İşte bu özel metotların bazıları ve 
görevleri:

viewDidLoad(): Bu metot, bir view controller'ın görünümü belleğe yüklendiğinde çağrılır. Genellikle, view controller'ın görünümünün başlangıç 
ayarlarını yapmak veya görüntüdeki öğeleri başlatmak için kullanılır. Örneğin, etiket metnini "Hoşgeldin" olarak ayarladığınız gibi.
viewWillAppear(_:): Bu metot, bir view controller'ın görünümü ekranda görüntülenmeye başladığında çağrılır. Genellikle, bu metot içinde 
animasyonlar başlatmak veya verileri güncellemek gibi işlemleri gerçekleştirmek için kullanılır. Bu metot, kullanıcıya görünümün hemen önce 
ne olacağı hakkında bilgi verme fırsatı sunar.
viewWillDisappear(_:): Bu metot, bir view controller'ın görünümü ekrandan kaybolmadan önce çağrılır. Görünümün kaybolmasından hemen önce yapılması
gereken işlemleri burada gerçekleştirebilirsiniz. Özellikle, verileri kaydetmek veya kullanıcı işlemi iptal etmek için kullanışlıdır.
Bu metotlar, bir view controller'ın yaşam döngüsünün farklı aşamalarında geliştiriciye kontrol ve müdahale sağlar. Bu sayede, görünümün doğru bir
şekilde başlatılması, güncellenmesi ve temizlenmesi mümkün olur. Her metotun belirli bir görevi ve çağrılma zamanı vardır, ve bu metotları uygun
şekilde kullanarak iOS uygulamalarınızın davranışını özelleştirebilirsiniz.

Örneğin, bir ekranda yeni veri alındığında viewWillAppear(_:) kullanılabilir ve kullanıcının bu yeni veriye anında erişim sağlayabilir.
Benzer şekilde, viewWillDisappear(_:) kullanılarak kullanıcı veri girişini kaydedebilir veya iptal edebilir. Bu metotları kullanarak uygulamanızın 
kullanıcı deneyimini daha iyi şekillendirebilirsiniz.
