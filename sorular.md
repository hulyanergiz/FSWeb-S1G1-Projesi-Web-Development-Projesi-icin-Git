# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Bir versiyon kontrol sistemidir. Projelerin eş zamanlı olarak farklı kişilerce yapılabilmesine ve güncel tutulabilmesine olanak sağlar.

2. Git ile GitHub arasında ne fark var?
   Git yerel bilgisayara kurulan komut satır arayüzü olarak kullanılan bir versiyon kontrol sistemidir.GitHub ise grafiksel arayüz sunan ve projelerin depolandığı bulut tabanlı sunucudur.

3. Neden bir branch oluşturuyoruz?
   Projeye yeni bir özellik eklerken projenin orijinaline zarar vermemek için branch dediğimiz dallar oluştururuz.

4. Pull Request'in amacı nedir?
   Pull request, forkladığımız projeler üzerinde değişiklikler yapan kullanıcının projeyi proje sahibine göndermesidir. Buradaki amaç yapılan değişikliklerin proje sahibi tarafından onaylanıp projeye merge etmesi için değişiklik yapan kişinin projeye katkı sağlama isteğinde bulunmasıdır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın? git checkout "branch adı" komutu ile geçebilirim.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git fetch, uzaktaki bir depodan dosyaları indirirken, git pull buna ek olarak yerel bilgisayarı getirilen dosyalarla eşleştirerek günceller.
   git merge komutu ile de başka branchtekiler ile bulunulan branchi o branchte birleştirir, yani bulunulan branche diğer branchteki değişiklikleri entegre eder.
7. Merge conflict nedir?
   Conflict'in kelime anlamından anlaşılacağı üzere çaıkşma demektir. Bir proje üzerinde aynı yerde yapılan eş zamanlı değişikliklerden dolayı merge edilememesidir.

8. Merge conflict'i nasıl çözeriz?
   Merge Editör kullanılarak yapılan değişiklikleri kıyaslayıp hangi değişikliklerin korunup hangilerin yoksayılacağına karar verilir.
