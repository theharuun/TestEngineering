# HUAWEI TURKİYE STAJIM
- Merhaba amacım huawei stajında öğrendiğim bilgileri yasal süreç ve güvenliğe uygun şekilde kendim için oluşturduğum bir Türkçe Dosya Dokümentasyonudur.

## İCERİK
1. [Yazılım Test Mühendisliğine İlk Adım STLC ile Tanışma ve Örneklerle Anlama](https://github.com/theharuun/TestEngineering/blob/main/1-%20Yazılım%20Test%20Mühendisliğine%20İlk%20Adım%20STLC%20ile%20Tanışma%20ve%20Örneklerle%20Anlama.md)

2. [Yazılım Testinin Prensipleri ve Test Metodolojileri – Derinlemesine Analiz](https://github.com/theharuun/TestEngineering/blob/main/2-%20Yazılım%20Testinin%20Prensipleri%20ve%20Test%20Metodolojileri.md)


# 1. Giriş
    • Bugünkü konuların ne olduğu:
        ○ White Box Testing
        ○ Black Box Testing
        ○ Test Coverage teknikleri (Statement, Decision, Condition Coverage)
        ○ Test Design teknikleri (Equivalence Partitioning, Boundary Value Analysis)
    • Neden önemli oldukları:
        ○ Farklı test teknikleri, yazılımın hem kod hem de kullanıcı seviyesinde kontrolünü sağlar.
        ○ Doğru teknik seçimi, zaman ve maliyet tasarrufu sağlar.

2. White Box vs Black Box Testing
2.1 White Box Testing
    • Tanım: Kodun iç yapısının bilinerek test edilmesi.
    • Avantajlar:
        ○ Kodun derinlemesine test edilmesini sağlar.
        ○ Gizli mantık hataları yakalanır.
    • Dezavantajlar:
        ○ Kaynak kod bilgisi gerekir.
        ○ Zaman alıcı olabilir.
    • Örnek: Bir fonksiyonun tüm if/else bloklarını test etmek.
2.2 Black Box Testing
    • Tanım: Kodun iç yapısını bilmeden, yalnızca giriş–çıkış ilişkisine göre test yapmak.
    • Avantajlar:
        ○ Kullanıcı bakış açısıyla test yapar.
        ○ Gereksinimlere odaklanır.
    • Dezavantajlar:
        ○ Kodun derin hataları gözden kaçabilir.
    • Örnek: Login ekranına doğru ve yanlış bilgiler girip sonucu kontrol etmek.

3. Coverage Techniques (Kapsama Teknikleri)
3.1 Statement Coverage
    • Tanım: Kodun her satırının en az bir kez çalıştırılması.
    • Avantaj: Kodun hiç çalışmayan satırlarını bulur.
    • Dezavantaj: Tüm mantıksal olasılıkları test etmez.
    • Örnek: if bloğunun yalnızca true kısmını test etmek, false kısmı eksik kalabilir.
3.2 Decision Coverage
    • Tanım: Tüm karar noktalarının (if, switch) true ve false durumlarının test edilmesi.
    • Avantaj: Mantıksal kararların tamamını kapsar.
    • Dezavantaj: İç içe mantık koşulları tam kapsanmayabilir.
3.3 Condition Coverage
    • Tanım: Karar ifadelerindeki tüm koşulların ayrı ayrı true/false olarak test edilmesi.
    • Avantaj: Her bir mantık koşulunu kontrol eder.
    • Dezavantaj: Test sayısı artar.

4. Test Design Techniques (Test Tasarım Teknikleri)
4.1 Equivalence Partitioning
    • Tanım: Giriş değerlerini geçerli ve geçersiz gruplara ayırarak her gruptan yalnızca bir değer test etmek.
    • Avantaj: Test sayısını azaltır, verimliliği artırır.
    • Dezavantaj: Bazı özel değerler gözden kaçabilir.
    • Örnek: Yaş alanı için geçerli değerler (18–60), geçersiz değerler (<18, >60).
4.2 Boundary Value Analysis
    • Tanım: Sınır değerlerinin test edilmesi.
    • Avantaj: Hatalar genellikle sınır değerlerde çıkar, bu nedenle etkili bir tekniktir.
    • Dezavantaj: Sınır dışında kalan nadir hataları yakalayamaz.
    • Örnek: Yaş alanı 18 ise 17, 18, 19 test edilir.

5. Kapanış
    • Bugünkü öğrenimden çıkarımlar:
        ○ Kod seviyesinde (white box) ve kullanıcı seviyesinde (black box) testlerin nasıl farklı bakış açıları sağladığı.
        ○ Coverage tekniklerinin eksik kod parçalarını bulmada nasıl yardımcı olduğu.
        ○ Test tasarım tekniklerinin zaman kazandırırken kapsayıcılığı artırma yöntemleri.
    • İleride projelerde sağlayacağı katkılar:
Daha planlı, sistematik ve eksiksiz test senaryoları yazma becerisi.