[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/BbkuIk5w)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=21971402&assignment_repo_type=AssignmentRepo)
# Algoritma ve Programlama I – Lab S1 Week 11

## Methods and Testing (Think Java Chapter 4)

Bu laboratuvar çalışmasında **Think Java Bölüm 4: Methods and Testing** içindeki tüm egzersizleri Java kullanarak uygulayacaksınız. Her egzersiz kendi dosyası içinde yer alacak ve tek bir `.java` dosyası olarak teslim edilecektir.

---

## 📌 Genel Kurallar

* Her egzersiz **kendi klasörü** içinde yapılacaktır.
* Kodunuzu **derlenebilir** durumda bırakmak sizin sorumluluğunuzdadır.
* **Java kaynak kodlarında Türkçe karakter KULLANMAYIN.**

  * ASCII uyumlu olmalı.
  * `System.out.println("cikti")` gibi.
* README veya açıklama dosyalarında Türkçe karakter kullanabilirsiniz.
* Kodunuzu adım adım commit etmeyi ve pushlamayı unutmayın.

---

## 📝 Egzersizler

Aşağıdaki maddeler Think Java Bölüm 4'teki resmi egzersizlerin birebir karşılığıdır.
Detaylar için kitap web sayfasını da inceleyebilirsiniz.

---

## 📘 Exercise 4.1 – Tarih Yazdırma Metotları

**Görev:**

`printAmerican(day, date, month, year)`

`printEuropean(day, date, month, year)`

Metotlarını yazın ve `main` içinde test edin.

**Teslim Dosyası:**

```
Exercise4_1.java
```

---

## 📘 Exercise 4.2 – Çalışma Sırası (Flow of Execution)

**Görev:**

* Verilen programdaki **her satırın çalışma sırasını** bulun.
* Her satırın sonuna:

  ```java
  // 1
  // 1, 7
  // 3, 9
  ```

  formatında yorum ekleyin.
* Programın **tam çıktısını** yazın.
* `baffle` metoduna ilk gönderilen `blimp` parametresinin değerini yazın.

**Teslim Dosyası:**

```
Exercise4_2.java
```

---

## 📘 Exercise 4.3 – Stack Diagram + Program Çıktısı

**Görev:**

* `ping` metodu **ilk çağrıldığında** programın stack diyagramını çizin.
* Programın ürettiği **tam çıktıyı** yazın.

**Not:** Stack diyagramı `.md` veya `.png` olarak ekleyebilirsiniz. 
Dilerseniz nanobananaya kağıda karaladığınız stack diagramını verin o size diyagram üretsin ve buraya png yükleyin. 
Stack diyagramı md yazım formatı ile çizdirilerek yazdırılabilir, bu da çok ilginç, değişik ve heyecanlı bir deneyim. 

**Teslim Dosyası:**

```
Exercise4_3.java
stack_diagram.md (veya .png)
```

---

## 📘 Exercise 4.4 – Derleyici Deneyleri

Aşağıdaki soruları **kendiniz derleyerek deneyin**:

1. Bir değer döndüren metodu çağırıp sonucunu kullanmazsanız ne olur?
2. Bir **void** metodu bir ifadenin içinde kullanırsanız (ör: `System.out.println("boo!") + 7`) ne olur?

**Teslim Dosyası:**

```
Exercise4_4.java içine yorum satırı (veya Exercise4_4_answers.md dosyası da ekleyebilirsin)
```

---

## 📘 Exercise 4.5 – Flow + Stack Diagram + Çıktı

**Görev:**

* `zoop` metodu **ikinci kez** çağrıldığında stack diyagramını çizin.
* Programın ürettiği **tam çıktıyı** hesaplayın.

**Teslim Dosyaları:**

```
Exercise4_5.java
stack_diagram_2.md ya da png
```
---

## 📘 Exercise 4.6 – Multadd ve expSum

**Görev:**

1. `multadd(a, b, c)` metodunu yazın → `a * b + c`
2. `expSum(x)` metodunu yazın:

   * `x * Math.exp(-x) + (1 - Math.exp(-x))`
3. `main` içinde şu ifadeleri test edin:

   * `multadd(1.0, 2.0, 3.0)`
   * `sin(pi/4) + cos(pi/4) / 2`
   * `log(10) + log(20)`

**Teslim Dosyası:**

```
Multadd.java
```

---

## 🧪 Derleme Komutları

Terminal kullananlar için tipik kullanım:

```
javac Exercise4_1.java
java Exercise4_1
```

---

## 📤 Teslim
* Commit mesajlarını düzenli ve açıklayıcı tutun.
* Deadline’dan önce push yapmayı unutmayın.

---

## 🏆 Başarılar!

Bu laboratuvar, Java metot yapısını ve program akışını derinlemesine anlamanız için tasarlanmıştır.
Her egzersiz bir sonrakinin temelini oluşturur. Takıldığınız yerlerde GitHub Discussions veya ders hocasına danışabilirsiniz.
