# GitHub Terminalojisi

## GitHub Nedir?
<p align="justify"><b>Git,</b> projenizin her aşamasının bir "fotoğrafını" (commit) çeken ve istediğiniz zaman o fotoğraflara dönebilmenizi sağlayan bir zaman makinesi gibidir. <b>GitHub</b> ise bu fotoğraf albümlerini buluta yükleyip başkalarıyla paylaşabildiğiniz, birlikte düzenleyebildiğiniz bir sosyal platformdur.</p>
<p align="justify"><b>Git,</b> bir versiyon kontrol sistemidir. Yerel bilgisayarınızda çalışır. Komut satırıyla çalışır.<br>
<b>GitHub ise,</b> bu Git depolarınızı (repository) bulutta (internet üzerinde) saklamanızı sağlayan bir hizmet ve web sitesidir. Yani Git reposu için bir "ev sahibi" (host) görevi görür.</p>

### En Basit Haliyle: "Proje Dosyaları için Google Drive"

<p align="justify">GitHub'ı, yazılım projelerinize özel bir Google Drive veya Dropbox gibi düşünebilirsiniz. Ancak çok daha akıllı ve güçlüdür:
<li>Sadece dosyaları saklamaz, her değişikliğin geçmişini de kaydeder.</li>
<li>Aynı dosya üzerinde aynı anda çalışan insanların çakışmasını (conflict) yönetir.</li>
<li>Kodları incelemeye, hata bildirmeye, tartışmaya olanak tanır.</li>

### Neden GitHub Kullanmalıyız?

<li align="justify"><b> Güvenli Bulut Yedekleme:</b> Kodunuz ve tüm versiyon geçmişi bulutta saklanır. Bilgisayarınız bozulsa bile projeniz güvendedir.</li>

<li align="justify"><b> Zaman Makinesi:</b> Projenizin eski haline istediğiniz an dönebilir, kimin ne değişiklik yaptığını görebilirsiniz.</li>

<li align="justify"><b> Kolay İş Birliği: </b> Aynı proje üzerinde, aynı anda, dünyanın her yerinden ekip arkadaşlarınızla sorunsuzca çalışabilirsiniz.</li>

<li align="justify"><b> Proje Yönetimi: </b> Görev takibi (Issues), kod incelemesi (Pull Request) ve proje tahtaları (Projects) ile her şey organize olur.</li>

<li align="justify"> <b> Otomasyon (CI/CD): </b> Kodunuzu gönderdiğinizde testlerin otomatik çalışmasını ve sunucuya otomatik yüklenmesini sağlarsınız.</li>

<li align="justify"><b> Portfolyo & CV: </b> Hesabınız, işverenlere gösterdiğiniz canlı bir yetenek portfolyosudur. </li>

<li align="justify"> <b>Açık Kaynak Katkı: </b> Dünyadaki en büyük yazılım projelerine katkıda bulunmanın en kolay yoludur. </li>



## GitHub Depolarının (Repository) Özellikleri:
<p align="justify">
 
- **Dosya Yönetimi** : Bir GitHub deposu, tüm proje dosyalarını içerir. Kod dosyaları, belgeler, yapılandırma dosyaları, görseller gibi her şey depoda saklanır.
Depo, bu dosyaların geçmişini tutar. Git ile yapılan her değişiklik, depo içinde kaydedilir, böylece eski sürümlere dönmek ve değişiklikleri incelemek mümkün olur.
- **Sürüm Kontrolü**: GitHub, projede yapılan tüm değişiklikleri takip eder. Git, bir değişiklik yapıldığında, bu değişikliği kaydeder ve her değişikliği bir "commit" olarak adlandırır.
Depodaki commit'ler, bir projenin geçmişine dair bilgi sağlar, böylece hangi dosyalarda ne değişiklik yapıldığını görebiliriz.
- **Branch (Dallanma)**: Bir projede ana kod (master/main branch) üzerinden bağımsız olarak çalışmalar yapılabilmesi için branch (dal) özelliği kullanılabilir. Branch’ler, farklı özelliklerin ya da düzeltmelerin ayrı bir dalda geliştirilmesini sağlar. Ana projeye zarar vermeden yeni özellikler veya düzeltmeler üzerinde çalışılabilir.
- **Pull Requests (PR)**: GitHub, bir dalda yapılan değişikliklerin ana koda entegre edilmesini sağlamak için pull request (PR) özelliğini kullanır. PR, yapılan değişikliklerin diğer ekip üyeleri tarafından gözden geçirilmesini sağlar. Değişiklikler onaylandıktan sonra ana dal ile birleştirilir (merge).
- **Collaborators (Katkıcılar)**: GitHub depoları, başkalarının projeye katkıda bulunmasını sağlamak için collaborators (katkıcılar) özelliğine sahiptir. Projenin sahibi, belirli kişilere erişim izinleri vererek onların projeye katkıda bulunmalarını sağlar. Depo sahibi, katkıcıları yönetebilir ve onlara belirli izinler verebilir (okuma, yazma, yönetici vb.).
- **README Dosyası**: Her GitHub deposunda genellikle bir README.md dosyası bulunur. Bu dosya, projenin açıklamasını, nasıl kullanılacağını ve katkıda bulunma yönergelerini içerir.
Markdown formatında yazılabilir ve projeye dair önemli bilgileri sağlar.
- **Issues (Sorunlar)**: GitHub deposunda issues (sorunlar) kullanılabilir. Bu özellik, hata raporları, geliştirme istekleri ve yapılacak görevleri takip etmek için çok kullanışlıdır.
Her issue, bir görev olarak atanabilir ve tartışma yapılabilir.
- **Actions (Otomasyon ve CI/CD)**: GitHub Actions kullanarak sürekli entegrasyon (CI) ve sürekli dağıtım (CD) süreçlerini otomatikleştirebilirsiniz. Bu sayede, kod değişiklikleri yapıldıkça testler çalıştırılabilir ve dağıtımlar yapılabilir. Örneğin, bir pull request açıldığında otomatik olarak testlerin çalıştırılması sağlanabilir.
- **Wiki ve Belgeler**: GitHub, projeler için bir Wiki alanı sunar. Projeyle ilgili daha fazla bilgi, kılavuzlar ve dökümantasyon burada barındırılabilir.
- **Fork ve Clone**: GitHub, kullanıcıların başka bir kullanıcının deposunu "fork" etmelerine izin verir. Fork, başka bir depo üzerinde bağımsız olarak değişiklik yapmanıza olanak sağlar.
Clone ise bir depoyu kendi bilgisayarınıza indirmenizi sağlar. Bu, yerel olarak proje üzerinde çalışabilmenize imkan tanır.
</p>

## GitHub Depolarının Kullanım Alanları:
- **Açık Kaynak Yazılım Geliştirme**: GitHub, açık kaynak projelerinin geliştirilmesi ve paylaşıldığı en yaygın platformdur.
- **Kişisel veya Kurumsal Projeler**: GitHub depoları, kişisel yazılım projelerinizi veya kurumsal yazılım geliştirme projelerinizi yönetmek için kullanılır.
- **Eğitim ve Öğrenme**: Eğitim materyalleri, örnek kodlar ve kişisel projeler GitHub üzerinde barındırılabilir.
- **Portföyler**: Geliştiriciler, GitHub depolarını portföy olarak kullanabilir, yazdıkları kodları paylaşabilirler.

## Bu Github paylaşımının IEEE ve APA formatlarınada atıf verilme şekli:
- IEEE--> C. Yasar, "Git-vs-Github" GitHub, [Online]. Erişim Linki: https://github.com/cyasar34/Git-vs-Github Son Erişim Tarihi: Gün Ay Yıl.
- APA--> Yasar, C. (2024). Git-vs-Github[GitHub Deposu]. GitHub. Erişim Linki: https://github.com/cyasar34/Git-vs-Github Son Erişim Tarihi: Gün Ay Yıl.
  
> **Proje Durumu:** İlgili dokümanların paylaşımı ders kapsamında gerçekleştirilmiştir. GitHub bölümünden beğeni bildirimi olarak bir yıldız vererek çalışmalarımı destekleyebilirsiniz. <br>
> **Katkıda Bulunma:** Dokümanlarınızda kullanılacaksanız ilgili atıf yöntemlerini kullanmanız ve haber vermeniz çok önemlidir. <br>
> **Lisans:** MIT Lisansı altında yayımlandı.  




