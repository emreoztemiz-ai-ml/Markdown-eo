# Markdown Kullanımı Türkçe

## Markdown Nedir, Ne Amaçla Kullanılır?

Markdown, yazılarımızı düz metin olarak yazmamıza imkan veren işaretleme/biçimlendirme dilidir (_markup language_).  Markdown'ın temel amacı, metnimizi kolayca hazırlamak ve düz metin haliyle bile metnin rahatça okunmasını sağlamaktır. 

## Örneklerle Sözdizim (_syntax_) kuralları

[Başlık](#Başlık)

[Vurgulama](#Vurgulama)

[Maddeleme ve Sıralama](#Maddeleme-ve-Sıralama)

[Bağlantı](#Bağlantı)

[Tablo](#Tablo)

[Kod](#Kod)

[Alıntı](#Alıntı)

[Resim](#Resim)

[Yatay Çizgi](#Yatay-Çizgi)

[Görev Listesi](#Görev-Listesi)


### Başlık

```
# 1. Başlık
## 2. Alt Başlık
### 3. Alt Başlık
```

# 1. Başlık
## 2. Alt Başlık
### 3. Alt Başlık

### Vurgulama

```
**kalın** __kalın__

*italik* _italik_

**_kalın ve italik_**
```

**kalın** __kalın__

*italik* _italik_

**_kalın ve italik_**

### Maddeleme ve Sıralama

*Maddeleme:*

```
- Maddde 1
- Madde 2
- Madde 3
  * Alt madde a
  * Alt madde b
    - Fıkra i
    - Fıkra ii
```
- Maddde 1
- Madde 2
- Madde 3
  * Alt madde a
  * Alt madde b
    - Fıkra i
    - Fıkra ii

*Sıralama:*

```
1. Birinci
2. İkinci
```
1. Birinci
2. İkinci


### Bağlantı

```
[Bağlantı](https://github.com/emreoztemiz-ai-ml)

[Başlıklı Bağlantı](https://github.com/emreoztemiz-ai-ml "GitHub Sayfam")
```

[Bağlantı](https://github.com/emreoztemiz-ai-ml)

[Başlıklı Bağlantı](https://github.com/emreoztemiz-ai-ml "GitHub Sayfam")


```
[Referans 1][1]
[Referans 2][2]

YazıYazıYazıYazıYazıYazıYazıYazıYazıYazı
YazıYazıYazıYazıYazıYazıYazıYazı.

Referanslar sayfanın en sonuna yazılabilir. Sayfada gozukmez.

[1]: https://github.com/emreoztemiz-ai-ml
[2]: https://github.com/
```

[Referans 1][1]

[Referans 2][2]

YazıYazıYazıYazıYazıYazıYazıYazıYazıYazı
YazıYazıYazıYazıYazıYazıYazıYazı.

[1]: https://github.com/emreoztemiz-ai-ml
[2]: https://github.com/



### Tablo
```
|   | Fiyat   | Adet  |
| --|:-------:| -----:|
| A | 1000TL  | 1     |
| B | 100TL   | 10    |
| C | 1TL     | 1000  |

```
|   | Fiyat   | Adet  |
| --|:-------:| -----:|
| A | 1000TL  | 1     |
| B | 100TL   | 10    |
| C | 1TL     | 1000  |


### Kod

#### Yazı İçinde Kod
```
asdf asdf adf `kod` asdf asdf.
```

asdf asdf adf `kod` asdf asdf.

#### Kod Bloğu
\```\
asdf

\```

```
asdf
```

#### Kod Bloğu (Dil Desteği İle)

Python Örneği:

\```python\
from datetime import date

print(f'Bugün: {date.today()}')

\```

```python
from datetime import date

print(f'Bugün: {date.today()}')
```

Shell Örneği:

\```shell

echo Merhaba

\```

```shell
echo Merhaba
```

### Alıntı
```
> Alıntı 1

>> Alıntı 2

>>> Alıntı 3
```
> Alıntı 1

>> Alıntı 2

>>> Alıntı 3


### Resim

#### Aynı Satıra Yazarak
```
![alt yazı][resim adresi]

![Photo by Emre Öztemiz on ChatGPT](./assets/kodEOn.png "GitHub")
```
 
![Photo by Emre Öztemiz on ChatGPT](./assets/kodEOn.png)

#### Referans İle

```
![Photo by Emre Öztemiz on ChatGPT][resim]

[resim]: ./assets/kodEOn.png "Resim Başlığı"
```
 
![Photo by Emre Öztemiz on ChatGPT][resim]

[resim]: ./assets/kodEOn.png "Resim Başlığı"

#### Resimin Boyutunu Değiştirerek (HTML Kullanarak)

```
<img src="./assets/kodEOn2.png" alt="alt yazı" width="320">
```
 
<img src="./assets/kodEOn2.png" alt="Photo by Emre Öztemiz on ChatGPT" width="320">


### Yatay Çizgi

```
YazıYazıYazıYazıYazıYazıYazıYazıYazıYazı

---

YazıYazıYazıYazıYazıYazıYazıYazıYazıYazı
```

YazıYazıYazıYazıYazıYazıYazıYazıYazıYazı

---

YazıYazıYazıYazıYazıYazıYazıYazıYazıYazı

### Cümle Aralarında kullanım

Python'da toplama işlemi için `a + b` ifadesi kullanılır.
```
Python'da toplama işlemi için `a + b` ifadesi kullanılır.
```
---

### Görev Listesi

- [x] Proje oluşturuldu
- [ ] Belgeler eklenecek
- [ ] Yayınlanacak

```
- [x] Proje oluşturuldu
- [ ] Belgeler eklenecek
- [ ] Yayınlanacak
```
---
**Süpriz**:İlk denemem
