# Java Jacoco CI

Bu proje, GitHub Actions kullanarak Java Maven projesi için otomatik derleme, test çalıştırma ve JaCoCo ile test kapsamı raporu oluşturur.

## Özellikler
- Maven build
- JUnit 5 testleri
- JaCoCo ile test coverage
- GitHub Actions entegrasyonu

## Nasıl çalışır?
1. `pull_request` açıldığında otomatik olarak testler çalışır.
2. JaCoCo coverage raporu PR yorumlarına eklenir.
