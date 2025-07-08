GitHub Üzerinden Çalışma Süreci
Projelerimizde görev takibi ve geliştirme süreci GitHub üzerinden yürütülmektedir. Aşağıda, sürecin adım adım nasıl ilerlediği açıklanmıştır:
1. Task Ataması
GitHub’daki Medyanes > Projects kısmında ilgili proje için oluşturulan taskları görebilirsin.

Sana bir task atandığında, GitHub tarafından mail yoluyla bilgilendirilirsin.

Task başlangıçta Todo (yapılacak) durumundadır. Bu, görevin henüz başlamadığı anlamına gelir.

2. Task İncelemesi ve Başlangıç
Task'ı açıp detaylarını dikkatlice incele.

Eğer task’ı anladıysan, task’ı In-Progress (devam ediyor) durumuna taşı.

Anlamadığın veya net olmayan bir nokta varsa, GitHub üzerinden task’a yorum bırakabilir veya WhatsApp’tan ilgili kişiye sorabilirsin.

3. Projeyi Güncelleme ve Branch Açma
Lokalinde projeyi güncellemek için terminalde şu komutları çalıştır:

```bash
git checkout main
git pull
Ardından, üzerinde çalışacağın task için yeni bir branch aç:

bash
Kopyala
Düzenle
git checkout -b "Task_Adi"
Artık bu branch üzerinde geliştirmeye başlayabilirsin.

Çalışma ve Commit İşlemleri
Yaptığın her değişikliği anlamlı commit mesajları ile kaydet.

Commit mesajlarında yapılan değişikliklerin özeti yer almalı.

Pull Request (PR) Oluşturma
Görevini tamamladıktan sonra, branch’ini ana koda entegre etmek için PR (Pull Request) aç.

PR başlığı olarak, task adı veya yaptığın işlemi açıklayan kısa bir başlık kullan:

Örnek: UI Kısmı İyileştirme - İsim

PR açıklamasına yaptığın işlemleri ve varsa ekran görüntülerini ekleyerek orta düzeyde açıklayıcı bir yazı yaz.

PR Onayı ve Test Süreci
PR merge edildiğinde, sana mail üzerinden bildirim gelir.

Bu aşamadan sonra geliştirdiğin özelliği test ortamına gönderirsin.

Test sırasında sorun çıkmazsa task tamamlanır ve kapatılır.

Eğer test sırasında hata veya eksik bulunursa, tester task’ı tekrar In-Progress durumuna atar ve yorum bırakır. Bu durumda geri dönüp düzeltme yapman gerekir.
