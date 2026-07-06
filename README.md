# UI Automation Framework

Framework pengujian UI Website menggunakan Java, Selenium WebDriver, Cucumber, Gradle, dan JUnit.

## Technologies
- Java
- Gradle
- Selenium WebDriver
- Cucumber
- JUnit 4
- WebDriverManager

## Project Structure
![projek struktur 1.png](../../../projek%20struktur%201.png)
![projek struktur 2.png](../../../projek%20struktur%202.png)

## Test Scenarios
- ✅ Positive Test – Login menggunakan username dan password yang valid.
- ✅ Negative Test – Login menggunakan password yang salah.
- ✅ Boundary Test – Login menggunakan username kosong.

## Cucumber Report
![cucumber report.png](../../../cucumber%20report.png)

## Cara Menjalankan
1. Clone repository.
2. Open project menggunakan IntelliJ IDEA.
3. Jalankan `TestRunner.java`.
4. Laporan akan tersedia di:
```text
target/cucumber-report.html
```