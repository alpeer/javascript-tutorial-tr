# Developer console

# Geliştirici Komut Dizesi

Kod yazmak yanlışa eğilimli bir iştir. Bu süreç içerisinde görünüşe bakılırsa yanlışlıklar yapacaksınız. Ya da yok! Kesinlikle yanlış yapacaksınız, en azından [robot](<https://tr.wikipedia.org/wiki/Bender_(Futurama)>) değilseniz.

Kullanıcı, tarayıcıda oluşan yanışları göremez. Eğer yazdığınız kodda bir yanlışlık varsa, yanlış kısımları göremez ve bunu düzeltemezsiniz.

Yanlışları ve diğer kullanışlı bilgileri görebilmek için tarayıcılara bütünleştirilmiş "Geliştirici Araçları"'nı kullanmalısınız.

Genelde geliştiriciler Chrome veya Firefox'a yoğunlaşmaktadırlar çünkü ikisinin de geliştirme araçları çok iyidir. Diğer tarayıcılar da geliştirme araçları sunarlar, bazen daha farklı özelliklerle bile olsa genelde amaçları Chrome veya Firefox'u yakalamaktır.  Bundan dolayı çoğu kişi "yeğlenen" tarayıcıya iyedir ve eğer tarayıcı tabanlı bir sorunla karşılaşırsa diğer tarayıcıyı denetler.

Geliştirici araçları gerçekten güçlüdür ve bir çok farklı özelliği yapısında barındırır. Öncelikle bu araçların nasıl açılacağını ve yanlışları nasıl inceleyeceğimizi göreceğiz. Tabi bunlar için JavaScript kodları da çalıştıracağız.

[cut]

## Google Chrome

[bug.html](bug.html) belgesini açın.

Bu belgede bulunan JavaScript kodunda bir yanlışlık var. Kullanıcı bunu göremiyor, öyleyse geliştirici araçlarından bakıp bu yanlışlığı tanılayabilirsiniz.

`key:F12`'ye veya `key:Cmd+Opt+J`'ye basarak geliştirici araçlarını açabilirsiniz.

Geliştirici araçları komut dizesiyle açılacaktır. Aşağıdaki ekranda ilk yanlışlığı göreceksiniz:

![chrome](chrome.png)

Chrome'un geliştirme aracı sürüme göre değişiklik gösterecektir. Ancak genel olarak bu gördüğünüze benzeyecektir.

- Komut dizesinde, kırmızı renk ile yazılmış yanlışlığı görebilirsiniz. Bu durumda kodunuzun bilinmeyen "lalala" komutunda bir yanlışlık var.

- Sağ yanında bu yanlışlığın hangi dizede olduğunu görebilirsiniz. Bu alan tıklanabilirdir. Şu anda hata `bug.html:12`'de bulunmaktadır.

Hatanın altında `>` sembolünü görebilirsiniz. Bu "komut dizesi"'ni gösterir. Komutunuzu yazdıktan sonra `key:Enter`'a basarak o dizedeki komutu çalıştırabilirsiniz. Birden fazla dize kod yazabilmek için ise `key:Shift+Enter` tuş birliklerini kullanabilirsiniz.

Başlangıç için yanlışlıkları görmek yeterli olacaktır. Daha sonra geliştirme aracını <info:debugging-chrome> bölümünde derinlemesine öğreneceksiniz.

## Firefox, Edge ve diğerleri

Çoğu tarayıcı geliştirme aracını `key:F12` tuşu ile açar.

Görüntü ve kullanım olarak çoğu birbirine benzer. Birini öğrendiğinizde diğerine geçişiniz oldukça kolay olur.

## Safari

Safari ( Sadece MacOs için desteklenmektedir ) biraz özeldir. Geliştirici araçlarını kullanabilmek için önce "Geliştirici Seçkesi"'ni enkinleştirmeniz gerekmektedir. Bunun için özellikler sayfasını açıp "Gelişmiş" duvarından aşağıdaki gibi "Show Develop menu in menu bar"'ı seçmelisiniz.

![safari](safari.png)
Bu işlemi yaptıktan sonra `key:Cmd+Opt+C` ile geliştirici aracını açıp kapayabilirsiniz. Ayrıca özenle bakarsanız, üst menüde "Develop" adında yeni bir başlık göreceksiniz. Buradan da bir çok komutu çalıştırabilirsiniz.

## Özet
- Geliştirici araçları yanlışlıkları görmenizi, komutları çalıştırmanızı, değişkenleri izlemenizi sağlar.
-  Windows işletim dizgesinde `key:f12` tuşu ile açılır. Çoğu tarayıcıda bu tuş çalışır. MacOS işletim dizgesi için ise Chrome : `key:Cmd+Opt+J`,  ile Safari ise: `key:Cmd+Opt+C` tuşu ile açılır. ( Safari'de bu geliştirici kipini açmanız gerekmekte)

Artık çalışma ortamınızı da ayarladığınıza göre artık JavaScript öğrenmeye başlayabilirsiniz.
