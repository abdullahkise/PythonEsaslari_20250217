# Python ile Esasları

## Python Ortamının Hazırlanması
**Python** ortamını hazırlamak için:
1. Öncelikle [python.org](https://www.python.org/) sitesinden engine indirmek gerekli.
2. Sonrasında `Terminal` üzerinde veya bir IDE ile çalışabiliriiz.
    * `Jupyter Notebook`, `Jupyter Lab`
    * `Visual Studio Code`, `Spyder`, `PyCharm`
3. Dilerseniz **Anaconda** dağıtımını kurarak her şeyi derli toplu şekilde `Anaconda Navigator` ile yönetebiliriz.
4. ~Python 2~ yerine *Python 3* kullanmaya özen gösterelim. Büyük Syntax farklılıkları var.


**Not:**
* Yukarıdaki yatık tırnakları (`) <kbd>AltGr</kbd> + <kbd>;</kbd> + <kbd>Space</kbd> ile oluşturduk.
* Markdown dili html kodlarını da destekler <font color='red'> Bu metin html ile yazıldı.</font>

## Çalışma Modları:
1. Interactive Mode
2. Script Mode
3. Setup Mode

## Kullanılacak Bazı Komutlar
### Shell Komutları:

```shell
python --version
py --version
py -3.11
py3
python3
    help()
    help(print)
    exit()
cls
```

### Python Komutları:
```python
print("merhaba","Dünyalı", sep='-')
```

### SQL  Komutları:
```sql
SELECT
    Kolon1,
    Kolon2
FROM Tablo
WHERE filtre
```

### Bazı Kısayollar:
* Hücrelerdeki kodları çalıştırmak için:
    * <kbd>Shift</kbd> + <kbd>Enter</kbd> ile hücre çalışır, alt hücreye geçer yoksa yeni ekler.
    * <kbd>Ctrl</kbd> + <kbd>Enter</kbd> ile aynı hücre tekrar tekrar çalıştırılabilir.
    * <kbd>Alt</kbd> + <kbd>Enter</kbd> ile hücre çalışır alta kesin bir boş hücre ekler.
* Commanda Mode seçili iken kullanılacak bazı kısayollar
    * üste hücre eklemek için <kbd>A</kbd>
    * Alta hücre eklemek için <kbd>B</kbd>
    * Hücre silmek için <kbd>D</kbd>, <kbd>D</kbd>
    * Silinen hücreyi geri almak <kbd>Z</kbd> ileri almak Y</kbd>
    * Tüm kısayollar için <kbd>H</kbd>
    
### Matematiksel Semboller Gösterilebilir
* https://rmd4sci.njtierney.com/math
* $x^2$
* $\int$
* $\infty$
* $\int_0^\infty x^{-a}$
* $\frac{1-x}{3+y}$
* $\sum_{i=1}^n$
* $\sqrt{1-p}$

## Tablo Oluşturma
|Ad|Soyad|
|---|----|
|Ali|Uçan|
|Veli|Kaçan|
