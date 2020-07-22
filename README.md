# Nokta Bulutu İşleme
## 1. Giriş
Projenin kapsamı, nokta bulutları (Point Cloud) ve nokta bulutları üzerinde işlemleri kapsamaktadır. Şekil 1’de resmi verilen derinlik kamerası, görüş alanı içerisinde renkli piksel değerleri yanına derinlik bilgisi de sunmaktadır. Elde edilen 3B derinlik bilgisi kameraya göre tanımlı 3B noktalarla ifade edilmektedir. Bu noktaların oluşturduğu noktalar kümesine nokta bulutu adı verilir. Şekil 1’de bir tavşan yüzeyinden elde edilen nokta bulutunun gösterimi verilmektedir.

![sekil-1](https://user-images.githubusercontent.com/53192718/88223363-03c70700-cc70-11ea-9e04-2f1e611a42fb.png)

Bir kameradan alınan nokta bulutundaki her bir nokta, o kamera üzerinde tanımlı koordinat sistemine göre tanımlıdır. Örneğin, Şekil 2’de mavi renkli elips içinde gösterilen nokta bulutu 𝑂c1 koordinat sistemine göre tanımlıdır. Yeşil renkli elips içinde gösterilen nokta bulutu 𝑂c2 koordinat sistemine göre tanımlıdır. Bu iki nokta bulutunu birleştirip tek bir nokta bulutu olarak elde etmek için, her iki buluttaki noktaları ortak bir koordinat sistemine (𝑂B) göre tanımlı olacak şekilde dönüştürmek gerekir.

![sekil-2](https://user-images.githubusercontent.com/53192718/88223919-ee061180-cc70-11ea-9cb1-a36a871959b1.png)

P noktasının, {A} koordinat eksenine göre gösterimi aşağıda verilmektedir.

![A-koordinat-ekseni](https://user-images.githubusercontent.com/53192718/88223750-a3849500-cc70-11ea-98ea-4b28d99a0b49.png)

Bir P noktasının, {A} ve {B} koordinat eksenlerine göre, gösterimi sırasıyla ^A𝑃  ve ^B𝑃  ile gösterilmektedir. 

![A-B-koordinat-ekseni](https://user-images.githubusercontent.com/53192718/88223847-ce6ee900-cc70-11ea-9e5d-5dbbcdaa8253.png)

![donusum-matrisleri](https://user-images.githubusercontent.com/53192718/88224132-36253400-cc71-11ea-8e5b-ad2f03bfa9c4.png)
