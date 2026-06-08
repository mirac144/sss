# 🌊 Akışkanlar — Tam ve Ayrıntılı Fizik Rehberi

> Bu doküman; basınç, sıvı basıncı, açık hava basıncı, Pascal Yasası, Arşimet İlkesi ve Bernoulli İlkesi konularını sınav düzeyinin çok ötesinde, kavramsal derinlikte ele almaktadır.

---

## İçindekiler

1. [Temel Kavramlar ve Tanımlar](#1-temel-kavramlar-ve-tanımlar)
2. [Katı Basıncı](#2-katı-basıncı)
3. [Sıvı Basıncı](#3-sıvı-basıncı)
4. [Açık Hava Basıncı](#4-açık-hava-basıncı)
5. [Pascal Yasası](#5-pascal-yasası)
6. [Arşimet İlkesi ve Kaldırma Kuvveti](#6-arşimet-i̇lkesi-ve-kaldırma-kuvveti)
7. [Bernoulli İlkesi](#7-bernoulli-i̇lkesi)
8. [Karşılaştırmalı Özet Tabloları](#8-karşılaştırmalı-özet-tabloları)
9. [Sık Yapılan Hatalar](#9-sık-yapılan-hatalar)
10. [Soru Çözüm Stratejileri](#10-soru-çözüm-stratejileri)

---

## 1. Temel Kavramlar ve Tanımlar

### 1.1 Basınç Nedir?

Basınç, bir yüzeyin birim alanına **dik** olarak uygulanan kuvvetin büyüklüğüdür. Yalnızca kuvvetin büyüklüğü değil, o kuvvetin hangi alana uygulandığı da kritiktir.

$$\boxed{P = \frac{F}{A}}$$

| Sembol | Açıklama | SI Birimi |
|--------|----------|-----------|
| $P$ | Basınç | Pascal (Pa = N/m²) |
| $F$ | Yüzeye dik kuvvet | Newton (N) |
| $A$ | Yüzey alanı | metre kare (m²) |

> [!info] Skaler Büyüklük
> Basınç bir **skaler** büyüklüktür; yani yönü yoktur, yalnızca büyüklüğü vardır. Kuvvet ise vektöreldır. Bu fark sınavlarda önemlidir.

**Günlük Hayat Örnekleri:**
- Topuk ile basılan zemin → küçük alan → **büyük basınç**
- Kar ayakkabısı → büyük alan → **küçük basınç**
- Bıçağın keskin tarafı → çok küçük alan → **son derece büyük basınç**
- Enjeksiyon iğnesinin ucu → mikro alan → **yüksek basınç ile deri delme**

---

### 1.2 Akışkan Nedir?

Akışkan; molekülleri birbirine göre kolaylıkla yer değiştirebilen, yani **akan** maddelerdir. İki alt kategorisi vardır:

| Kategori | Açıklama | Örnek |
|----------|----------|-------|
| **Sıvı** | Hacmi sabit, şekli kaba uyar | Su, cıva, zeytinyağı |
| **Gaz** | Hacmi ve şekli kaba uyar | Hava, helyum, buhar |

Akışkanların temel özelliği: **kayma gerilmesine dayanamamaları.** Bir katı, yamulduğunda şeklini korumaya çalışır; akışkan ise yalnızca normal (dik) kuvvetlere karşı koyabilir.

---

### 1.3 Yoğunluk

$$\rho = \frac{m}{V}$$

| Madde | Yoğunluk (kg/m³) |
|-------|-----------------|
| Hava (deniz seviyesi) | ≈ 1.29 |
| Su | 1000 |
| Deniz suyu | ≈ 1025 |
| Cıva | 13 600 |
| Demir | 7 874 |
| Altın | 19 300 |

> [!tip] Ezber Kolaylığı
> Sıvı basıncı formülünde geçen $d$ sembolü yoğunluğu ifade eder. Türkçe kaynaklarda $d$ veya $\rho$ (rho) kullanılır; ikisi de aynı kavramdır.

---

## 2. Katı Basıncı

### 2.1 Temel Formül ve Özellikler

$$P = \frac{F}{A}$$

**Katıların Basıncı ile İlgili Kritik Kurallar:**

1. **Kuvvet iletimi:** Katılar, üzerlerine uygulanan kuvvetin hem **yönünü** hem **büyüklüğünü** değiştirmeden iletir.
2. **Basınç değişimi:** Ancak basınç, temas yüzeyine bağlı olduğundan farklı yüzeylerde farklı olabilir.
3. **Dik kuvvet şartı:** Formüldeki $F$, yüzeye **dik** bileşendir. Eğik kuvvetlerde yalnızca dik bileşen hesaba katılır.

### 2.2 Basıncı Etkileyen Faktörler

```
Basınç ARTAR eğer:
├── Kuvvet artar (F ↑ → P ↑)
└── Alan azalır  (A ↓ → P ↑)

Basınç AZALIR eğer:
├── Kuvvet azalır (F ↓ → P ↓)
└── Alan artar    (A ↑ → P ↓)
```

### 2.3 Çok Katmanlı Cisim Basıncı

Bir cisim birden fazla yüzey üzerinde duruyorsa, her yüzey için basınç ayrı hesaplanır:

$$P_1 = \frac{G}{A_1} \quad \text{ve} \quad P_2 = \frac{G}{A_2}$$

Eğer $A_1 \neq A_2$ ise $P_1 \neq P_2$ olur; ağırlık aynı olmasına rağmen basınçlar farklıdır.

---

## 3. Sıvı Basıncı

### 3.1 Temel Formül

$$\boxed{P = h \cdot d \cdot g}$$

| Sembol | Anlam | Birim |
|--------|-------|-------|
| $h$ | Sıvı yüzeyinden derinlik | m |
| $d$ | Sıvının yoğunluğu | kg/m³ |
| $g$ | Yer çekimi ivmesi | m/s² (≈ 10) |

### 3.2 Sıvı Basınç Kuvveti

Belirli bir yüzeye etki eden toplam basınç kuvveti:

$$F = P \cdot A = h \cdot d \cdot g \cdot A$$

### 3.3 Sıvı Basıncını Etkileyen ve Etkilemeyen Faktörler

> [!important] Kritik Ayrım — Sınavda Çok Çıkar

**BAĞLIDIR:**
- ✅ Derinlik ($h$) — ne kadar derine inilirse basınç o kadar artar
- ✅ Sıvının yoğunluğu ($d$)
- ✅ Yer çekimi ivmesi ($g$)

**BAĞLI DEĞİLDİR:**
- ❌ Kabın şekli (silindir, koni, küp, eğik — fark etmez)
- ❌ Sıvının toplam miktarı / hacmi
- ❌ Kabın genişliği
- ❌ Sıvının üzerindeki yüzeyin alanı

**Bunu Neden Önemli?**
Aşağıdaki üç kaptaki A, B, C noktalarının derinlikleri eşit ve sıvı yoğunlukları aynıysa basınçları **eşittir** — kapların şekilleri tamamen farklı olsa bile.

```
    |   |      \   /      |     |
    |   |       \ /       |_____|
    |...|        |..|      |...|
     Dar         Geniş      Normal
    
    Hepsi aynı derinlikte → Aynı basınç
```

### 3.4 Bağlı Kaplar İlkesi

Birbirine bağlı kaplarda, **aynı yoğunluktaki** sıvı aynı seviyeye ulaşır. Kapların şekli, büyüklüğü ne olursa olsun sıvı yüzeyleri eşit yükseklikte olur.

Farklı yoğunluktaki sıvılar bağlandığında:

$$h_1 \cdot d_1 = h_2 \cdot d_2$$

Yoğun sıvı daha **alçak** kolda durur; hafif sıvı daha **yüksek** kolda yükselir.

### 3.5 Derinlikle Basınç Değişimi

```
Yüzey (h=0)       → P = 0 (görecel)
1 m derinlik       → P = 1 × 1000 × 10 = 10 000 Pa
10 m derinlik      → P = 100 000 Pa = 1 atm ek basınç
100 m derinlik     → P = 1 000 000 Pa = 10 atm ek basınç
```

> [!warning] Dikkat
> Dalış yaparken her 10 metre aşağıya inildikçe 1 atm ek basınç oluşur. 40 metrede toplam basınç 5 atm'ye ulaşır. Bu yüzden derin dalış ekipmanı zorunludur.

---

## 4. Açık Hava Basıncı

### 4.1 Tanım ve Temel Değer

Atmosfer; azot, oksijen ve diğer gazlardan oluşan devasa bir gaz kütlesidir. Bu gazlar, ağırlıkları nedeniyle altlarındaki yüzeylere basınç uygular. Bu basınca **açık hava basıncı** veya **atmosfer basıncı** denir.

$$P_0 = 1 \text{ atm} = 76 \text{ cmHg} = 101\,325 \text{ Pa} \approx 10^5 \text{ Pa}$$

### 4.2 Torricelli Deneyi (1644)

İtalyan bilim insanı Evangelista Torricelli, atmosfer basıncını ilk ölçen kişidir.

**Deney Düzeneği:**
1. Bir ucu kapalı, uzun cam boru cıva ile tamamen doldurulur.
2. Boru parmakla kapatılarak ağzı aşağıya gelecek şekilde cıva dolu kaba daldırılır.
3. Parmak kaldırıldığında cıva boru içinde belirli bir seviyede kalır.

**Sonuç:** Deniz seviyesinde ve 0°C'de cıva sütunu yüksekliği **76 cm** olarak ölçülür.

**Neden 76 cm?**

$$P_{\text{atm}} = h \cdot d_{\text{cıva}} \cdot g$$
$$101\,325 = 0.76 \times 13\,600 \times 9.81 \approx 101\,396 \text{ Pa} ✓$$

> [!note] Kritik Detay
> Borunun çapı, eğimi veya şekli bu yüksekliği **değiştirmez.** Atmosfer basıncı sabit olduğu sürece cıva hep 76 cm'de kalır. Bu, sınavlarda sıkça sorulan bir ayrıntıdır.

**Borudaki Boşluk:** Cıvanın üzerinde kalan boşluk neredeyse tam vakumdur (**Torricelli vakumu**). Orada gaz yok denecek kadar azdır.

### 4.3 Magdeburg Deneyi (1654)

Otto von Guericke'nin ünlü deneyi: İki bronz yarım küre birbirine yerleştirilerek içindeki hava vakum pompasıyla boşaltıldı. Ardından iki yana 16 at bağlandı; atlar iki yarım küreyi ayıramadı.

**Neden?**
İçeride basınç sıfıra yakın, dışarıda ise 1 atm basınç var. Bu basınç farkı, küreyi birbirine son derece kuvvetlice bastırıyordu.

$$F = P_0 \times A = 10^5 \times \pi r^2$$

Yarıçap 30 cm için bu kuvvet yaklaşık **28 000 N** olur — gerçekten devasa bir kuvvet.

### 4.4 Açık Hava Basıncını Etkileyen Faktörler

#### Rakım (Yükseklik)

Deniz seviyesinden yukarı çıkıldıkça:
- Üstteki hava tabakası **azalır**
- Havanın **yoğunluğu** düşer
- Atmosfer basıncı **azalır**

```
Deniz seviyesi      → 1.000 atm (76 cmHg)
1 000 m yükseklik   → ≈ 0.887 atm
3 000 m yükseklik   → ≈ 0.692 atm
8 849 m (Everest)   → ≈ 0.337 atm
```

**Pratik Sonuçları:**
- Yüksekte kaynama noktası **düşer** (basınç azalır → su daha erken kaynar)
- Dağcılar ek oksijen taşır
- Uçaklar kabinleri yapay olarak basınçlandırır

#### Sıcaklık

- Sıcaklık artar → hava genleşir → yoğunluk azalır → **alçak basınç** oluşur
- Sıcaklık düşer → hava büzülür → yoğunluk artar → **yüksek basınç** oluşur

Bu ilişki, hava durumu tahminlerinin temelini oluşturur:
- **Alçak basınç** → hava yükselir → soğur → yoğuşur → **yağmur**
- **Yüksek basınç** → hava alçalır → ısınır → nem düşer → **açık hava**

### 4.5 Ölçüm Araçları

| Alet | Ölçüm Yöntemi | Kullanım Alanı |
|------|---------------|----------------|
| **Cıvalı Barometre** | Torricelli düzeneği | Sabit istasyonlar |
| **Aneroid Barometre** | Vakumlu metal kutu deformasyonu | Taşınabilir |
| **Dijital Barometre** | Elektronik sensör | Hava durumu istasyonları |
| **Altimetre** | Basınca göre yükseklik hesabı | Uçak, dağcılık |

---

## 5. Pascal Yasası

### 5.1 İfade ve Formül

> **Pascal Yasası:** Kapalı bir kaptaki durgun sıvıya herhangi bir noktada uygulanan basınç değişimi, sıvının her noktasına ve kabın iç yüzeyine **aynen** ve **her yönde** iletilir.

$$\Delta P_1 = \Delta P_2$$

$$\frac{F_1}{A_1} = \frac{F_2}{A_2}$$

Bu denklemden:

$$\frac{F_1}{F_2} = \frac{A_1}{A_2}$$

### 5.2 Hidrolik Sistemin Çalışma Mantığı

```
Küçük piston          Büyük piston
   F₁ →                    ← F₂
  [====]──────────────[===========]
    A₁                      A₂

Eğer A₂ = 100 × A₁  →  F₂ = 100 × F₁
```

**Enerji Korunumu:** Kuvvet büyümesi, mesafe küçülmesiyle dengelenir.

$$W_1 = W_2 \Rightarrow F_1 \cdot x_1 = F_2 \cdot x_2$$

Büyük piston 100 kat daha fazla kuvvet uygularken, küçük pistonun 100 kat daha fazla hareket etmesi gerekir.

### 5.3 Teknolojik Uygulamalar

| Uygulama | Açıklama |
|----------|----------|
| **Hidrolik Frenler** | Fren pedalına basılan küçük kuvvet, tüm tekerleklere büyük kuvvet olarak iletilir |
| **Hidrolik Kriko** | Arabayı kaldırmak için küçük kolla büyük kaldırma kuvveti üretilir |
| **Damperli Kamyon** | Pistonla kasayı kaldırma |
| **İtfaiye Merdiveni** | Hidrolik kollarla yükseğe uzanma |
| **Uçak İniş Takımı** | İniş/kalkışta hidrolik açma-kapama |
| **Buldozer/Kazıcı** | Kürek ve kolların kontrolü |
| **Su Cenderesi** | Malzemeleri sıkıştırma ve şekillendirme |
| **Diş Koltuğu** | Koltuğun yukarı-aşağı hareketi |

### 5.4 Pascal Deneyi — Patlayan Fıçı

Blaise Pascal, dar bir boruya az miktarda su ekleyerek sağlam meşe fıçısını patlattı.

**Neden?**

$$P = h \cdot d \cdot g$$

Boru uzun ama çok dardı. Suya bağlı olarak derinlik ($h$) çok büyüktü, bu nedenle oluşan basınç devasa boyutlara ulaştı. Basınç her yöne eşit iletildiğinden fıçının her noktasına büyük kuvvet uygulandı ve fıçı patladı.

**Ders:** Önemli olan sıvının miktarı değil, **derinlik ve basınç** değeridir.

---

## 6. Arşimet İlkesi ve Kaldırma Kuvveti

### 6.1 İlkenin Keşfi

MÖ 287-212 yılları arasında yaşayan Yunan matematikçi ve fizikçi **Arşimet**, Kral Hiero'nun tacının saf altın mı olduğunu anlamak için görevlendirildi. Banyo yaparken çözümü keşfeden Arşimet'in "Eureka!" diye bağırarak sokağa fırladığı söylenir.

### 6.2 Arşimet İlkesi

> **Arşimet İlkesi:** Bir akışkana tamamen veya kısmen batırılan bir cisme, cismin yer değiştirdiği akışkanın ağırlığına eşit büyüklükte ve yukarı yönde bir **kaldırma kuvveti** uygulanır.

$$\boxed{F_k = V_{batan} \cdot d_{sıvı} \cdot g}$$

| Sembol | Anlam |
|--------|-------|
| $F_k$ | Kaldırma kuvveti (N) |
| $V_{batan}$ | Cismin sıvıya batan kısmının hacmi (m³) |
| $d_{sıvı}$ | Sıvının yoğunluğu (kg/m³) |
| $g$ | Yer çekimi ivmesi (m/s²) |

**Alternatif ifade:**

$$F_k = m_{yerinden\ edilen\ sıvı} \cdot g$$

### 6.3 Kaldırma Kuvvetini Etkileyen ve Etkilemeyen Faktörler

**BAĞLIDIR:**
- ✅ Cismin sıvıya batan hacmi
- ✅ Sıvının yoğunluğu
- ✅ Yer çekimi ivmesi

**BAĞLI DEĞİLDİR:**
- ❌ Cismin kütlesi veya yoğunluğu
- ❌ Cismin şekli (aynı hacim → aynı kaldırma kuvveti)
- ❌ Sıvının derinliği (cisim tamamen batmışsa derinlik artışı $F_k$'yı değiştirmez)
- ❌ Cismin bulunduğu derinlik (tam batmışsa)

> [!warning] Sık Hata
> "Cisim daha derin yere gittiğinde kaldırma kuvveti artar" — **YANLIŞ!**
> Cisim tamamen batmışsa batan hacim değişmez, dolayısıyla $F_k$ aynı kalır.

### 6.4 Denge Durumları

#### Durum 1: Yüzme ($d_{cisim} < d_{sıvı}$)

Cisim kısmen batar. Denge şartı:

$$F_k = G \Rightarrow V_{batan} \cdot d_{sıvı} \cdot g = V_{toplam} \cdot d_{cisim} \cdot g$$

$$\frac{V_{batan}}{V_{toplam}} = \frac{d_{cisim}}{d_{sıvı}}$$

**Örnek:** Buzdağının %90'ı suyun altındadır çünkü buz yoğunluğu (917 kg/m³) su yoğunluğuna (1000 kg/m³) yakın ama altında.

$$\frac{V_{batan}}{V_{toplam}} = \frac{917}{1000} = 0.917 \approx \%92$$

#### Durum 2: Askıda Kalma ($d_{cisim} = d_{sıvı}$)

$$F_k = G$$

Cisim tamamen batmıştır ama ne yükselir ne de batar. Dengede asılı kalır.

**Örnek:** Deniz suyu ile tatlı su arasındaki tuzluluk farklılıklarını kullanan bazı canlılar, vücut yoğunluklarını ayarlayarak belirli derinlikte asılı kalabilir.

#### Durum 3: Batma ($d_{cisim} > d_{sıvı}$)

$$F_k < G$$

Net kuvvet aşağıya yöneliktir ve cisim dibe çöker.

$$F_{net} = G - F_k = V \cdot g \cdot (d_{cisim} - d_{sıvı})$$

**Görünür Ağırlık:**

$$G_{görünür} = G - F_k$$

Bu değer terazide ölçülen değerdir ve her zaman gerçek ağırlıktan küçüktür (sıvı içindeyken).

### 6.5 Gemiler Nasıl Yüzer?

Demir yoğunluğu ≈ 7874 kg/m³ olmasına rağmen demir gemiler yüzer. Neden?

Gemi içi boş olduğundan, geminin **ortalama yoğunluğu** (demir + hava + içindeki her şey) suyun yoğunluğunun altına düşer.

$$d_{ortalama} = \frac{m_{toplam}}{V_{toplam}} < 1000 \text{ kg/m}^3$$

Gemi batarken ortalama yoğunluğu artmaktadır; yeterince su girdiğinde artık yüzemez.

### 6.6 Balıkların Derinlik Kontrolü

Kemikli balıkların çoğu, **yüzme kesesi** (hava kesesi) adı verilen bir organa sahiptir. Bu kesedeki hava miktarını ayarlayarak ortalama yoğunluklarını değiştirir ve istedikleri derinlikte asılı kalırlar.

- Hava artar → yoğunluk azalır → yukarı çıkar
- Hava azalır → yoğunluk artar → aşağı iner

Denizaltılar da aynı prensiple çalışır: balast tankları su ile doldurulur veya boşaltılır.

### 6.7 Sıcak Hava Balonu

$$F_k = V_{balon} \cdot d_{hava(soğuk)} \cdot g$$

$$G = V_{balon} \cdot d_{hava(sıcak)} \cdot g + G_{sebet}$$

Sıcak hava; soğuk havadan daha az yoğun olduğundan balonun kaldırma kuvveti ağırlığını aşar ve balon yükselir.

---

## 7. Bernoulli İlkesi

### 7.1 Temel İfade

> **Bernoulli İlkesi:** Sürtünmesiz, sıkıştırılamaz ve kararlı akışta; akışkan hızlandıkça basıncı azalır, yavaşladıkça basıncı artar.

Enerji korunumuna dayanan **Bernoulli Denklemi:**

$$\boxed{P + \frac{1}{2} \rho v^2 + \rho g h = \text{sabit}}$$

| Terim | Anlam |
|-------|-------|
| $P$ | Statik basınç |
| $\frac{1}{2}\rho v^2$ | Dinamik basınç (kinetik enerji yoğunluğu) |
| $\rho g h$ | Hidrostatik basınç (potansiyel enerji yoğunluğu) |

İki nokta arasında:

$$P_1 + \frac{1}{2}\rho v_1^2 + \rho g h_1 = P_2 + \frac{1}{2}\rho v_2^2 + \rho g h_2$$

### 7.2 Süreklilik Denklemi

Sıkıştırılamaz akışkan için bir borudan geçen akış hızı, kesitin **ters orantılı** olarak değişir:

$$A_1 \cdot v_1 = A_2 \cdot v_2$$

$$A_1 > A_2 \Rightarrow v_1 < v_2$$

Kesit daralır → hız **artar** → basınç **azalır** (Bernoulli)

### 7.3 Venturi Borusu

```
Geniş kesit              Dar kesit              Geniş kesit
   A₁                       A₂                      A₁
──────────────────╮    ╭────────────╮    ╭──────────────────
      v₁ →        ╰────╯    v₂→    ╰────╯      ← v₁
──────────────────╯                   ╰──────────────────

P₁ (yüksek)         P₂ (düşük)         P₁ (yüksek)
|                        |
▼ yüksek su sütunu   ▲ alçak su sütunu
```

Venturi borusu, akış hızını ölçmek için kullanılan en temel araçtır. Manometre ile iki noktadaki basınç farkı ölçülür ve buradan hız hesaplanır.

### 7.4 Günlük Hayat Uygulamaları

#### Uçak Kanadı (Aerodinamik Kaldırma)

Uçak kanadının üst yüzeyi kavisli, alt yüzeyi düzdür. Havayı yukarıdan geçen kısım daha uzun yol kateder, dolayısıyla daha hızlı akar.

- Üst yüzey: $v$ büyük → $P$ küçük
- Alt yüzey: $v$ küçük → $P$ büyük
- Net basınç farkı → yukarı yönde kaldırma kuvveti oluşur

> [!note] Not
> Modern aerodinamikte kaldırma kuvveti yalnızca Bernoulli ile açıklanmaz; akış üzerindeki *açı etkisi* (angle of attack) de önemli rol oynar. Ancak lise düzeyinde Bernoulli yeterlidir.

#### Fırtınada Çatı Uçması

Fırtınada rüzgar çatının **üstünden** hızla geçer:
- Üst yüzey: hız büyük → basınç **düşük**
- Alt yüzey (ev içi): hız yok → basınç yüksek (atmosfer basıncı)

Bu basınç farkı çatıyı yukarı doğru iter; yeterince büyük olursa çatı uçar.

#### Şemsiyenin Ters Dönmesi

Aynı mantık: rüzgar şemsiyenin dış yüzeyinden hızla geçerken iç kısmı görece durgun hava içindedir. Basınç farkı şemsiyeyi tersine çevirir.

#### Sprey (Atomizer) Püskürtücü

Parfüm, boyа ve bazı tıbbi cihazlarda kullanılır:
1. Pompa kolu sıkılır → boru içinden hızla hava geçer
2. Hızlı hava → düşük basınç
3. Alttaki sıvı kap atmosfer basıncıyla yukarı itilir
4. Sıvı hava akımına karışır → ince damlacıklar halinde püskürtülür

#### Magnus Etkisi (Dönen Top)

Üst etkiyle dönen bir top (spin atış) neden eğri gider?

Topun üst yarısı: dönüş hava akışıyla aynı yönde → toplam hız **artar** → basınç **düşer**
Topun alt yarısı: dönüş hava akışına karşı → toplam hız **azalır** → basınç **artar**

Basınç farkı topu yukarıdan aşağıya iter → top yay çizer.

Futbolda "frikik" topları, tenis ve beyzbolda "eğri atış" bu etkiyle gerçekleşir.

#### Hızlı Araçların Birbirini Çekmesi

İki araç yan yana hızla geçerken aralarındaki bölgede hava sıkışır ve hızlanır:
- Aralar: hız büyük → basınç **düşük**
- Dışlar: normal basınç

Bu fark araçları birbirine doğru iter. Yüksek hızda tehlike oluşturabilir.

### 7.5 Bernoulli vs. Pascal — Temel Fark

| Özellik | Pascal Yasası | Bernoulli İlkesi |
|---------|---------------|-----------------|
| Akışkan durumu | **Durgun** sıvı | **Akan** akışkan |
| Konu | Basınç iletimi | Hız-basınç ilişkisi |
| Formül | $\Delta P_1 = \Delta P_2$ | $P + \frac{1}{2}\rho v^2 = sabit$ |
| Örnek | Hidrolik kriko | Uçak kanadı |

---

## 8. Karşılaştırmalı Özet Tabloları

### 8.1 Tüm Formüller Bir Arada

| Konu | Formül | Birim |
|------|--------|-------|
| Basınç | $P = F/A$ | Pa |
| Sıvı basıncı | $P = h \cdot d \cdot g$ | Pa |
| Sıvı basınç kuvveti | $F = h \cdot d \cdot g \cdot A$ | N |
| Pascal | $F_1/A_1 = F_2/A_2$ | — |
| Kaldırma kuvveti | $F_k = V_b \cdot d_s \cdot g$ | N |
| Bernoulli | $P + \frac{1}{2}\rho v^2 + \rho gh = C$ | Pa |
| Süreklilik | $A_1 v_1 = A_2 v_2$ | m³/s |

### 8.2 İlke-Örnek Eşleştirmesi

| İlke | Örnek |
|------|-------|
| **Pascal** | Hidrolik fren, kriko, damperli kamyon, vinç, su cenderesi, diş koltuğu |
| **Arşimet** | Gemi yüzmesi, buz/buzdağı, sıcak hava balonu, balık yüzme kesesi, denizaltı |
| **Bernoulli** | Uçak kanadı, çatı uçması, şemsiye dönmesi, sprey, Magnus etkisi, Venturi |
| **Torricelli** | Barometre, cıvalı basınç ölçer |
| **Magdeburg** | Atmosfer basıncının gücü, vakum kapları |

---

## 9. Sık Yapılan Hatalar

> [!warning] Hata 1
> **"Sıvı miktarı artarsa basınç artar"** → YANLIŞ
> Sıvı basıncı miktara değil **derinliğe** bağlıdır.

> [!warning] Hata 2
> **"Cisim daha derin batarsa kaldırma kuvveti artar"** → YANLIŞ
> Cisim tamamen batmışsa batan hacim sabittir, $F_k$ değişmez.

> [!warning] Hata 3
> **"Torricelli deneyinde boru çapı değişince cıva yüksekliği değişir"** → YANLIŞ
> Yükseklik yalnızca atmosfer basıncına bağlıdır.

> [!warning] Hata 4
> **"Pascal yasası gazlar için geçerli değildir"** → YANLIŞ
> Pascal yasası her akışkan için (sıvı ve gaz) geçerlidir; ancak sıvılarda daha verimli çalışır çünkü sıvılar sıkıştırılamaz.

> [!warning] Hata 5
> **"Kaldırma kuvveti her zaman cismi yukarı taşır"** → YANLIŞ
> Kaldırma kuvveti her zaman yukarı yönlüdür ama ağırlıktan küçük olduğunda cisim yine de batar. Sadece ağırlığa eşit veya büyük olduğunda cisim yüzer ya da asılı kalır.

> [!warning] Hata 6
> **"Bernoulli ilkesi sadece sıvılar için geçerlidir"** → YANLIŞ
> Bernoulli ilkesi sıvı ve gazlar dahil tüm akışkanlar için geçerlidir.

---

## 10. Soru Çözüm Stratejileri

### 10.1 Basınç Sorularında

1. Yüzeye **dik** kuvveti belirle (eğik kuvvetlerde $F_\perp = F \sin\theta$ veya $F \cos\theta$)
2. Temas alanını belirle
3. $P = F/A$ uygula

### 10.2 Sıvı Basıncı Sorularında

1. Referans noktasının **derinliğini** bul (yüzeyden aşağıya)
2. Sıvının yoğunluğunu kullan
3. Kabın şeklini yok say — **sadece derinlik önemli**

### 10.3 Kaldırma Kuvveti Sorularında

```
Adım 1: Cisim tamamen mı batmış, kısmen mi?
  ↓ Tamamen: V_batan = V_cisim
  ↓ Kısmen:  V_batan < V_cisim (yüzme dengesiyle bul)

Adım 2: Fk = V_batan × d_sıvı × g

Adım 3: G = m × g = V_cisim × d_cisim × g

Adım 4: Karşılaştır → Fk vs G
  Fk > G → cisim yükselir
  Fk = G → denge (yüzme veya askı)
  Fk < G → cisim batar
```

### 10.4 Pascal Yasası Sorularında

1. Her iki pistona etki eden basınçları eşit yaz: $P_1 = P_2$
2. $F_1/A_1 = F_2/A_2$ oranını kur
3. Enerji korunumu gerekiyorsa: $F_1 x_1 = F_2 x_2$

### 10.5 Bernoulli Sorularında

1. Süreklilik denklemini kullan: $A_1 v_1 = A_2 v_2$
2. Bernoulli denklemini yaz (yükseklik farkı yoksa $\rho g h$ terimleri düşer)
3. Hangi noktada hız büyük → o noktada basınç küçük

---

## Biyomimikri Notu

Doğadaki akışkan sistemleri mühendisliğe ilham vermiştir:

| Doğal Sistem | Teknolojik Uygulama |
|--------------|---------------------|
| Nautilus kabuklusu | Denizaltı basınç gövdesi tasarımı |
| Balık yüzme kesesi | Denizaltı balast tank sistemi |
| Kuş kanadı | Uçak kanat profili (airfoil) |
| Köpek balığı derisi | Düşük sürtünmeli yüzücü kıyafetleri |
| Kalp-damar sistemi | Hidrolik pompa ve boru tasarımı |

---

*Son güncelleme: Haziran 2026 | Fizik — Akışkanlar Ünitesi*
