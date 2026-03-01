# Bankomat Proqramı

### Layihə Haqqında
Sadə Bankomat proqramı. İstifadəçilər hesab yarada, depozit/withdraw edə, balansı görə, pin dəyişdirə və hesabı silə bilərlər. Java dilində yazılıb.

### Class/Enum izahı
- **Main.java** – istifadəçi interfeysi, seçimləri oxuyur və `NewAccount` metodlarını çağırır.  
- **NewAccount.java** – istifadəçi hesabını idarə edir: qeydiyyat, depozit, pul çıxarma, pin dəyişdirmə, balans göstərmə və hesab silmə.  
- **ValyutaType.java** – valyuta tipini təyin edən enum. Hər valyuta üçün tam ad saxlanılır.

## QA Portfolio
Layihə ilə birlikdə QA təcrübəsini göstərmək üçün aşağıdakı fayllar əlavə olunub:
- `QA/TestCases.xlsx` – test case-lər
- `QA/BugReports.pdf` – tapılan buglar və onların həlli yolları

## İstifadə Qaydası
1. Layihəni klonlayın və ya yükləyin.
2. Java Development Kit (JDK) quraşdırın.
3. Terminalda layihə qovluğuna keçin və aşağıdakı əmrlə proqramı işə salın:

```bash
javac bankomat/*.java
java bankomat.Main
