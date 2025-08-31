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

### GitHub Terminolojisi

#### Repository (Repo) / Depo

<p align="justify">Projenizin tüm dosyalarının, klasör yapısının ve bu dosyalardaki tüm değişiklik geçmişinin (commit'lerin) saklandığı yerdir.
<em>Projenizin için özel bir "klasör" ya da "proje dosyası" gibi düşünebilirsiniz.</em> Ancak bu klasör, dosyalarınızın yanı sıra yaptığınız her değişikliğin de kaydını tutan akıllı bir zaman makinesi gibidir.<br>
Türleri:
<li>Yerel (Local) Repo: Bilgisayarınızın hard disk'inde bulunur.</li>
<li>Uzak (Remote) Repo: GitHub, GitLab gibi bir bulut sunucusunda bulunur.</li><br>
<em>Kısacası: Repository, projenizin tamamıdır.</em>

#### Branch (Dal)

<p align="justify"> Projenizin farklı versiyonlarını veya farklı özelliklerini birbirinden bağımsız ve paralel olarak geliştirmenizi sağlayan bir hat.<br> 
Bir ağacın ana gövdesi (main branch) vardır. Siz yeni bir özellik üzerinde çalışmaya başladığınızda, bu gövdeden yeni bir dal (branch) oluşturursunuz. Ana gövdeyi bozmadan, risksiz bir şekilde daldaki çalışmanızı bitirirsiniz. İşiniz bittiğinde, bu dalı ana gövdeye birleştirirsiniz (merge).<br>
<em>Kısacası: Branch, projenizin içinde açılmış paralel ve bağımsız bir çalışma alanıdır.</em>

#### Clone (Klonlama)

<p align="justify">Bir uzak depoyu (örneğin, GitHub'daki bir projeyi) tüm versiyon geçmişiyle birlikte kendi bilgisayarınıza kopyalama işlemidir.
<em> git clone "repo-url" komutuyla yapılır.</em>
Bir dosyayı buluttan (Google Drive) kendi bilgisayarınıza indirmek gibidir.<br>
<em>Kısacası: Clone ile bilgisayarına indirirsin.</em>

#### Fork (Çatallama)

<p align="justify">Bir başkasının GitHub'daki reposunu kendi GitHub hesabınıza kopyalamaktır. GitHub arayüzündeki "Fork" butonuna tıklanarak yapılır. Bir belgeyi alıp "Farklı Kaydet" diyerek kendi adınızla kaydetmek gibidir. <br>
<em>Kısacası: Fork ile GitHub hesabına kopyalarsın.</em>

#### Main (Ana Dal)

<p align="justify">Bir projedeki ana, kararlı ve çalışan sürümün bulunduğu varsayılan branch'tir (dal). Eskiden master olarak adlandırılırdı. <br>
<em>Kısacası:Main projenin ana gövdesidir. </em>

#### Pull (Çekme)

<p align="justify">Uzak depodaki (GitHub'daki) güncel değişiklikleri kendi yerel deponuza indirme işlemidir. Ekip çalışmasında, başkalarının yaptığı değişikliklerle yerel reponuzu güncel tutmak için.<br>
<b>Komut: git pull</b><br>
<em>Kısacası: Pull/Push senkronizasyon içindir.</em>

#### Push (İtme)

<p align="justify">Yerel deponuzdaki commit'leri uzak depoya (GitHub'a) gönderme işlemidir. Yaptığınız değişiklikleri diğer ekip üyeleriyle paylaşmak veya yedeklemek için.<br>
<b>Komut: git push</b><br>
<em>Kısacası: Pull/Push senkronizasyon içindir.</em>

#### Merge (Birleştirme)

<p align="justify">İki dalı (branch) birleştirme işlemidir. Bir özellik branch'inde yapılan değişiklikleri ana dala (main) eklemek için. Bir repository üzerinde bulunan bir branch'in başka bir branch ile birleştirilme işlemidir.<br>
<em>Kısacası: Merge birleştirme içindir.</em>

#### Conflict (Çakışma)

<p align="justify">Aynı dosyanın aynı satırında, farklı kişiler tarafından yapılan ve Git'in otomatik olarak birleştiremediği değişiklikler. Manuel olarak müdahale edip hangi değişikliklerin kalacağına karar vermeniz gerekir. Örneğin, iki kişi aynı Word belgesinin aynı yerini farklı şekilde düzenlerse çakışma olur.<br>
<em>Kısacası: Conflict iki kodun çakışmasıdır çözülmesi gereken sorundur.</em>

#### Pull Request (PR) / Merge Request (MR)

<p align="justify">Bir branch'deki değişiklikleri, ana branch'e birleştirme talebi göndermektir. Kod incelemesi (code review) yapılması, tartışılması ve test edilmesi için bir mekanizma sağlar. <br>
<em>Kısacası: Pull Request ise iş birliği ve kalite kontrol mekanizmasıdır.</em>

#### Stash (Geçici Saklama)

<p align="justify">Henüz commit etmediğiniz değişiklikleri geçici olarak bir kenara saklamanızı sağlar. Aniden başka bir branch'e geçmeniz gerektiğinde veya acil bir düzeltme yapmanız gerektiğinde, yarım kalan işinizi kaybetmeden saklarsınız.<br>
<b>Komutlar:
<li>git stash → Değişiklikleri saklar.</li>
<li>git stash pop → Saklanan değişiklikleri geri yükler.</li></b><br>
<em>Kısacası: Stash askıya alma işlemidir.</em>

#### Discard (Atma)

<p align="justify">Commit edilmemiş değişiklikleri tamamen iptal etmek, dosyayı son commit haline geri döndürmek. Yaptığınız değişikliklerden memnun değilseniz ve baştan başlamak isterseniz.<br>
<b>Komut: 
<li>git restore "dosya-adi"</li>  
<li>git checkout --"dosya-adi"</li></b><br>
<em>Kısacası: Discard iptal etme işlemidir.</em>

#### Remote (Uzak)

<p align="justify">Projenizin bulut sunucusunda (örn. GitHub, GitLab) bulunan kopyası. Ekip çalışması, yedekleme ve projeyi dağıtım için merkezi bir depo görevi görür.<br>
<em>Kısacası: Remote bulut işlevi görür.</em>

#### Local (Yerel)

<p align="justify">Projenizin kendi bilgisayarınızda bulunan kopyası. Geliştirme yapmak, test etmek ve değişiklikleri commit etmek için kullanırsınız.<br>
<em>Kısacası: Local sizin makineniz işlevi görür.</em>




## Bu Github paylaşımının IEEE ve APA formatlarınada atıf verilme şekli:
- IEEE--> C. Yasar, "Git-vs-Github" GitHub, [Online]. Erişim Linki: https://github.com/cyasar34/Git-vs-Github Son Erişim Tarihi: Gün Ay Yıl.
- APA--> Yasar, C. (2024). Git-vs-Github[GitHub Deposu]. GitHub. Erişim Linki: https://github.com/cyasar34/Git-vs-Github Son Erişim Tarihi: Gün Ay Yıl.
  
> **Proje Durumu:** İlgili dokümanların paylaşımı ders kapsamında gerçekleştirilmiştir. GitHub bölümünden beğeni bildirimi olarak bir yıldız vererek çalışmalarımı destekleyebilirsiniz. <br>
> **Katkıda Bulunma:** Dokümanlarınızda kullanılacaksanız ilgili atıf yöntemlerini kullanmanız ve haber vermeniz çok önemlidir. <br>
> **Lisans:** MIT Lisansı altında yayımlandı.  




