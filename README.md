# II Hafta (6Haziran) Ödevleri 

## Github'ın Gitflow'u ile diğer yaklaşımları arasındaki fark nedir? 
<h5>Github</h5><div>
GitHub, git yazılımı ile entegre olmuş bir depolama alanıdır. GitHub’daki hub komut satırını, Git gibi, geliştiriciler için en büyük sosyal ağa çevirendir.
Eğer ekibiniz sürekli güncelleme gerektiren bir proje üzerinde çalışıyor ve değişikliklerin izini sürmek istiyorsa, GitHub sizin için uygundur.</div>
<h5>Gitflow</h5><div>
Git flow birleşme-kaynaşma (merge) tabanlı bir çözümdür. Merge tabanlı çözümlerde merge işlemi sonucunda bütün değişiklikler kendi dallanmalarındaki commit ile tek bir dala (branch) bağlanır, başlangıç noktası sabittir. Rebase tabanlı çözümlerde ise kendi dalınız (branch) üzerinde yaptığınız değişiklikler, son yapılan commitler başlangıç noktası alınarak ana dal üzerine eklenir.
Git flow .yazılım geliştirmenin her aşamasını kolayca yönetmek için farklı dallarla çalışır, yazılımınızın “release” kavramına sahip olması durumunda kullanılması önerilir. Bu akışın bir başka iyi yanı, birden fazla geliştiricinin aynı özellik için çalışma yapması gerektiğinde mükemmel uyum sağlamasıdır. </div>

## Git and GitHub with Briana Swift Youtube Listesi incelensin. (11 Video) izlendi

## Merge pull request
<div>Pull request, projenizde birlikte çalıştığınız kişileri bir branch’de yaptığınız değişikliği ana repository’e ittiğinize dair bilgilendirdiğiniz anlamına gelmekte. Pull request olarak göndermek demek; ben projede değişiklikleri yaptım, sen de bu bu değişiklikleri onayla ve projene merge et, ben de katkı sağlamış olayım demek.</div>
    <h5>Create a merge commit</h5>
    <div>Hedef branch'de ve kaynak branch'de birbirinden bağımsız değişikliklerin yapılması durumunda "merge commit" adı verilen en son commit ile gerçekleşen değişiklikleri birleştiren otomatik bir commit adımı ekledikten sonra merge işlemini gerçekleştirir.</div>
    <h5> Squash and merge</h5>
    <div>Git squash komutu aslında farklı bir rebase kullanımı olarak değerlendirmek daha doğru olacaktır. Geçmişte atılan commit’leri yeniden düzenlemek, isimlendirmek veya birleştirmek için kullanıyoruz. merge son işlemde ekstra commit ekler.</div>
    <h5>Rebase and merge altında ne fark var</h5>
    <div>Merge komutu ile A dalındaki değişiklikler B dalı ile birleştirildiğinde B dalının commit tarihçesinde merge işleminden kaynaklanan ve merge commit adı verilen otomatik oluşturulmuş bir commit yer alır. Bu commit A ve B dallarının tarihçelerini birbiri ile ilişkilendirir.
Rebase komutu kullandığımızda ise ile A dalındaki her bir commit B dalına sanki commit işlemi B dalında yapılmış gibi yeniden yazılır. Bu sayede B dalının commit tarihçesi sanki tüm değişiklikler bu dalda olmuş gibi düz ve kesintisiz görünür.Yani son işlemde ekstra commit eklenmez.</br>
Rebase komutu yerel ve kısa süreliğine (örneğin bir hata giderme veya deneysel bir çalışma için oluşturulan) geçerli dallar için kullanılmalı. 
</div>

## Ramp up on Git and GitHub (ödev) başlandı

## hackerRank.com --> 30 Days Of Code başlandı

## 7 Haziran Ödevleri:
## Razor Pages Nedir?
<div>ASP.NET Core 2.0 ile beraber hayatımıza giren Razor Pages, ASP.NET Core MVC alt yapısında,
sayfa bazlı web uygulamaları geliştirebileceğimiz bir programlama modelidir. Razor Pages, sayfa bazlı senaryolar için bildiğimiz mvc (model view controller)’a göre daha kolay uygulama geliştirmeyi sağlayan bir platformdur
</div>
## Ayarlardaki Output kısmındaki Console Application nedir? diğerleri arasında fark nedir? [Ders Akışındaki 6. Madde'yi inceleyin.] ( araştırma ödev verildi ).
<div>Console ise grafiksel olmayan bir kullanıcı arayüzüne sahiptir. Kullanıcıdan bilgi alma ve gösterme işlemleri siyah bir ekranda gerçekleşir. Konsol uygulaması, metin terminali, bazı işletim sistemlerinin komut satırı arabirimi veya Grafik Kullanıcı Arabirimi işletim sistemlerinin çoğunda bulunan metin tabanlı arabirim gibi salt metin bilgisayar arabirimi aracılığıyla kullanılmak üzere tasarlanmış bir bilgisayar programıdır.  C# içerisinde görsel ortamlarda Windows form vasıtası ile kod yazabileceğimiz gibi görsel
özellikleri olmayan uygulamaları da konsol ekranında yazabiliriz. Konsol ekranında kullanılan
fonksiyonlar System.Console sınıfına ait fonksiyonlardır. </br>
Windows Application programcılara hazır nesneler sunar (textBox, comboBox, RadioButton vb)
ve grafik arayüzene sahip bir programlama dilidir. Console grafiksel olmayan bir kullanıcı
arayüzüne sahiptir. Kullanıcıdan bilgi alma ve gösterme işlemleri siyah bir ekranda gerçekleşir.
Console ekranında Windows Application da olan hazır nesneler yoktur.
</div>

## c# json serialize / deserialize
Objcet bir veriyi json’a çevirebilmek için o veriyi serialize etmemiz gerekir. Serialize terimi seri hale getirme olarak dilimize çevirebiliriz.
Bir Json veriyi ise istenilen bir object tipine çevirmek için ise json veriyi deserialize etmemiz gerekir. Deserialize terimini de seriyi kaldırma olarak dilimize çevirebiliriz.

## MVC vs MVVM
   <h5> MVP vs MVW vs MVU Pattern arasındaki farkı araştır </h5>
   <h6>MVC (Model-View-Controller)</h6>
   <div>ASP.NET MVC, MVC pattern’ini ASP.NET’e eklemek için Microsoft’un geliştirdiği framework’tür. 
<p>Model : Kullanıcaya göstermek ve manipule etmesini sağlamak istediğimiz verileri içereren nesneler.</p> 
<p>View : Kullanıcıya Model’i gösterdiğimiz ve Model üzerinde çeşitli manipulasyonlara izin verdiğimiz yer, Web olsun, windows olsun fark etmez, amaç kullanıcıya birşeyler göstermek ve inputlar almak.</p> 
<p>Controller: Kullanıcıların View üzerinden gerçekleştirdiği işlemlerle alınan veriyi Model’e taşır, Model’den aldığı veriyi View üzerinden kullanıcıya gösterir.</p> 
 </div>
   <h6>MVVM (Model-View-View Model) </h6>
    <div>MVVM bir projenin “sorumlulukların ayrıştırılması” esasına göre geliştirilmesi temeline dayanan bir tasarım kalıbı sunmaktadır. MVVM bir yazılımı Model, View ve ViewModel adında üç farklı yapıda geliştirmemizi tavsiye etmektedir.Model tarafında bir değişiklik yapılmak istendiğinde UI tarafında hiçbir değişiklik yapılmasına gerek kalmadan geliştirmeler rahatlıkla yapılabilir
    <p>Model: Veritabanından,  web servislerinden ya da herhangi bir veri kaynağından gelen verilerimizi temsil etmek için kullanılan entity sınıflarından oluşmaktadır. Ayrıca veri tutarlığını ve doğruluğunu kontrol eden iş kuralları da burada yer almaktadır.</p>
<p>View: Bu kısım verilerimizi son kullanıcılara aktardığımız görsel arayüzdür. Son kullanıcı ile uygulama arasında bir köprü görevi görür.</p>
    <p>ViewModel: ViewModel ise görsel arayüz ile model arasında köprü görevi görmektedir, yani Model’i View’a bağlayan yapıdır. </p>
 </div>
   <h6>MVP (model view presenter) </h6>
    <div>Model:Presenter’ın ihtiyaç duyduğu bilgileri sağlar. İş mantığı bu kısımda ele alınır.
View: Verilerin görüntülendiği ve işlem yapmak için kullanıcı ile etkileşime geçilen kısımdır. 
Presenter: Model ile View arasındaki bağlantıyı sağlayan kısımdır. Verileri modelden alır ve UI mantığını uygular.
 </div>
   <h6>MVW(Model-View-Whatever) </h6>
    <div> Burada W(Whatever) her hangi bir şey(C-Controller, VM-ViewModel ya da P-Presenter) olabilir.</div>
   <h5> Model-View-Update (MVU) nedir? </h5>
 <div> Son olarak, modeldeki tüm değişiklikler , View tarafından gönderilen mesajları alan ve değişiklikleri buna göre uygulayan saf bir Update  işlevi tarafından uygulanır.
</br>
Farklılıkları:</br>
MVP(Model, View, Presenter)’nin en büyük farklı controller’ı parçalıyor olması. Böylece view/activity doğal bağına devam ederken activity, controller sorumluluklarından arınmış olur. Model MVC’yle aynı. View’de fark olarak bu sefer Activity ve fragment de view’dedir. Ancak herhangi bir logic implement edilmez. Burada hem view hem de presenter birer interface’i implement ediyor. Activity hem view’i hem de presenter’ı create eder.  Presenter kullanıcıdan gelen inputu view’i aracılığıyla alır.
Presenter, MVC’deki controller’dır ancak bu sefer view’e bir bağımlılığı yoktur. Avantajı MVC’de view’e bağımlılığından dolayı Controller’a unit test yazamıyorduk. Burada View mock’lanarak yazılabilir. MVP küçük projelerde avantajlı olmakla beraber büyük projelerde çok fazla class olmasına sebep olabilir, zamanla presenter classlar şişebilir.
MVVM(Model, View, View-Model), View’in değişikliklere yanıt verebileceği event-based bir mimari kurmak istersek de karşımıza MVVM çıkacak. Model, MVC’yle aynı. View, viewmodelden sağlanan observable variable’ları bağlar. ViewModel, Model’i wrapleyip View tarafından ihtiyaç duyulan observable datanın sağlanmasından sorumlu.
Yani aslında yine business logic’den model sorumlu. Data değiştiğinde ViewModel bundan haberdar oldu ve View’e haber verdi. View’de ui’ı update etti diyebiliriz basitçe.
</div>

