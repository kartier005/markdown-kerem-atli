
# 📝 Markdown Nedir ve Nasıl Kullanılır?

Markdown, web üzerinde düz metin formatında yazı yazmayı ve bu yazıları HTML'e dönüştürerek kolayca biçimlendirmeyi sağlayan hafif bir işaretleme dilidir.

Temel amacı, bir metin editöründe dahi okunması kolay ve düzenli görünen metinler oluşturmaktır. Özellikle GitHub, proje dökümantasyonları ve benioku (README) dosyaları için standart haline gelmiştir.

## 🌟 Neden Markdown Kullanılır?

1. Basitlik ve Okunabilirlik: Yazdığınız ham metin bile biçimlendirilmiş hali kadar temiz ve anlaşılırdır.

2. Hafiflik: HTML gibi karmaşık etiketler yerine basit semboller (#, *, >) kullanır.

3. Hız: Biçimlendirme (kalın, başlık vb.) klavyeden ayrılmadan saniyeler içinde yapılabilir.

4. Platform Bağımsızlığı: GitHub, GitLab, Stack Overflow, Reddit ve birçok not alma uygulamasında standart olarak desteklenir.

## 🛠️ Temel Markdown Söz Dizimi (Syntax)

Markdown, metinleri biçimlendirmek için aşağıdaki basit sembolleri kullanır:

### 1. Başlıklar (Headings)
Başlıklar, bir ile altı arasında değişen sayıda # işareti kullanılarak oluşturulur. Tek # en büyük başlığı (H1) temsil eder.

Örnek:
- # Ana Başlık	H1 (En Büyük)
- ## Alt Başlık	H2
- ### Üçüncü Seviye Başlık	H3


### 2. Paragraf ve Satır Sonu

Markdown'da yeni bir paragraf oluşturmak için iki kez enter tuşuna basarak boş bir satır bırakmanız gerekir.     
Aynı paragraf içinde yeni bir satıra geçmek isterseniz, satırın sonuna iki boşluk bırakmanız gerekir.

### 3. Vurgulama (Kalın, İtalik)
Metinleri kalın veya italik yapmak için yıldız (*) veya alt çizgi (_) kullanılır.

italik: *italik metin* veya _italik metin_
kalın: **kalın metin** veya __kalın metin__
ikisi birden: ***kalın ve italik***


### 4. Listeler

**A. Sırasız Liste (Unordered List)**  
Her bir öğenin başına *, + veya - işareti koyulur.

Örnek: 
 * Birinci madde
 * İkinci madde
    * Alt madde

**B. Sıralı Liste (Ordered List)**  
Öğelerin başına rakamlar ve nokta (.) konulur.

Örnek: 
1. Birinci adım
2. İkinci adım
3. Üçüncü adım

### 5. Bağlantılar (Links)
Metni bir web adresine bağlamak için kullanılır.

- [Bağlantı Metni](URL Adresi)

Örnek: [Google'a Gitmek İçin](https://www.google.com)

### 6. Kod Blokları
Yazılımcılar için kodları göstermenin en temel yoludur.

- Satır İçi Kod: Tek bir ters tırnak işareti arasına yazılır.

     - Örnek: `Bu bir tek satırlık koddur.`  
          - `print("Hello")`

**Çok Satırlı Kod Bloğu:** Üç ters tırnak işareti (```) ile başlatılır ve bitirilir. Başlangıç işaretinden sonra dilin adını yazarak kodun söz dizimi vurgusunu (syntax highlighting) açabilirsiniz.

```python
def merhaba_dunya():
    print("Merhaba, GitHub!")
```


### 7. Resimler (Images)

Markdown'da resim eklemek, bağlantı (link) eklemeye çok benzerdir; tek farkı en başta ünlem işareti (!) kullanılmasıdır.

**Yazılışı:**

![Proje Logosu](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTyk8aG1ngkGB5_k74uGlLYcUch2JxUubdg8g&s)  

 Alternatif olarak (Aynı klasördeki resim için):  
![Veri Analizi Grafiği](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTyk8aG1ngkGB5_k74uGlLYcUch2JxUubdg8g&s)

### 8. Alıntılar (Blockquotes)
Bir metni alıntılamak için satırın başına > işareti konulur.

> Bu metin bir alıntıdır.

### 9. Tablo Oluşturma

**Yazılışı:**

| Adı | Tipi | Açıklama |
| :--- | :--- | :--- |
| **Başlıklar** | :--- | (Hizalamayı Belirtir) |
| `#` | Başlık | Ana Başlık Oluşturur |
| `*` | Vurgu | İtalik Yazar |






