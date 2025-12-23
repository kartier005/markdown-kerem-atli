# 📝 Temel Sözdizimi Rehberi (Markdown Guide)
## **Kerem Atlı**

Markdown, web üzerinde düz metin formatında yazı yazmayı ve bu yazıları HTML'e dönüştürerek kolayca biçimlendirmeyi sağlayan hafif bir işaretleme dilidir. Neredeyse tüm Markdown uygulamaları, orijinal tasarım belgesinde ana hatlarıyla belirtilen temel sözdizimini destekler.

## Başlıklar (Headings)

Başlık oluşturmak için kelime veya ifadenin önüne kare (#) işareti ekleyin. Kullandığınız kare sayısı HTML'deki başlık seviyesine (H1-H6) karşılık gelir.

| Markdown | HTML | Görünüm |
| :--- | :--- | :--- |
| `# Başlık Seviyesi 1` | `<h1>Başlık Seviyesi 1</h1>` | <h1>Başlık Seviyesi 1</h1> |
| `## Başlık Seviyesi 2` | `<h2>Başlık Seviyesi 2</h2>` | <h2>Başlık Seviyesi 2</h2> |
| `### Başlık Seviyesi 3` | `<h3>Başlık Seviyesi 3</h3>` | <h3>Başlık Seviyesi 3</h3> |

### Başlıklar İçin En İyi Uygulamalar

Markdown işlemcileri arasında uyumluluk sağlamak için her zaman `#` işaretinden sonra bir boşluk bırakın.

> [!TIP]
> **Doğru Kullanım:** `## Başlık`  
> **Yanlış Kullanım:** `##Başlık`

---

## Vurgulama (Emphasis)

Metni kalın veya italik yaparak önemli kısımları vurgulayabilirsiniz.

### Kalın (Bold)
Metni kalın yapmak için iki yıldız (`**`) veya iki alt çizgi (`__`) kullanın.

*   **Örnek:** `**Kalın Metin**` -> **Kalın Metin**

### İtalik (Italic)
Metni italik yapmak için tek yıldız (`*`) veya tek alt çizgi (`_`) kullanın.

*   **Örnek:** `*İtalik Metin*` -> *İtalik Metin*

### Kalın ve İtalik (Bold and Italic)
Her ikisini aynı anda uygulamak için üç yıldız (`***`) kullanın.

*   **Örnek:** `***Kalın ve İtalik***` -> ***Kalın ve İtalik***

---

## Listeler (Lists)

Öğeleri sıralı veya sırasız listeler halinde düzenleyebilirsiniz.

### Sırasız Listeler (Unordered Lists)
Öğelerin başına tire (`-`), artı (`+`) veya yıldız (`*`) ekleyin.

```markdown
- Elma
- Armut
  - Amasya Elması (Alt madde için 2 boşluk bırakın)
```

### Sıralı Listeler (Ordered Lists)
Öğelerin başına rakam ve nokta (`1.`) ekleyin.

1. Birinci Adım
2. İkinci Adım
3. Üçüncü Adım

---

## Bağlantılar (Links)

Bağlantı oluşturmak için bağlantı metnini köşeli parantez içine, URL'yi ise normal parantez içine alın.

**Sözdizimi:** `[Metin](URL)`

*   **Örnek:** `[Google'a Git](https://www.google.com)` -> [Google'a Git](https://www.google.com)

---

## Resimler (Images)

Resim eklemek bağlantı eklemeye benzer, ancak başında bir ünlem işareti (`!`) bulunur.

**Sözdizimi:** `![Alt Metin](Resim-URL-veya-Yolu)`

*   **Örnek:** `![Markdown Logosu](https://markdown-here.com/img/icon256.png)`

---

## Kod (Code)

### Satır İçi Kod
Kısa kod parçalarını tek ters tırnak (`` ` ``) içine alın.

*   **Örnek:** `print("Merhaba Dünya")` bir Python komutudur.

### Kod Blokları
Daha uzun kod blokları için üç ters tırnak (``` ``` ```) kullanın.

```python
def selamla():
    print("Merhaba, Markdown dünyasına hoş geldin!")
```

---

## Alıntılar (Blockquotes)

Alıntı oluşturmak için satırın başına `>` işareti ekleyin.

> Markdown, yazarların yazılarını hızlıca biçimlendirmesine olanak tanır.
>
> — Markdownguide.org

---

## Tablolar (Tables)

Sütunları ayırmak için dik çizgi (`|`), başlık satırını ayırmak için tire (`-`) kullanın.

| Özellik | Açıklama |
| :--- | :--- |
| Sola Hizalı | `:---` |
| Ortalanmış | `:---:` |
| Sağa Hizalı | `---:` |
