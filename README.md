#Kesirli Sayı Sınıfı

```java
public class Main {
    public static void main(String[] args) {
        // KesirliSayi nesneleri oluşturma ve başlangıç değerlerini atama
        KesirliSayi kesirliSayi1 = new KesirliSayi(3, 4);
        KesirliSayi kesirliSayi2 = new KesirliSayi(5, 6);

        // Toplama işlemi
        KesirliSayi toplam = kesirliSayi1.topla(kesirliSayi2);
        System.out.println("Toplam: " + toplam);

        // Çarpma işlemi
        KesirliSayi carpim = kesirliSayi1.carp(kesirliSayi2);
        System.out.println("Çarpım: " + carpim);
    }
}
```

Bu kod parçası, `KesirliSayi` sınıfını kullanarak kesirli sayıların toplamını ve çarpımını hesaplar ve ekrana yazdırır. Bu örnek, sınıfın nasıl kullanılabileceğini daha iyi anlamanıza yardımcı olabilir.
