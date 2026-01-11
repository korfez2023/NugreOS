# NugreOS
Güncel Program

# NugreOS

## 📦 Resmi Yayın – 11 Ocak 2026

NugreOS, her zaman **son sistem, son sürüm** felsefesiyle geliştirilen bir platformdur.  
Bu sürüm, .NET 9.0.308 SDK ve MAUI 9.0.100 paketleriyle uyumlu olarak tasarlanmıştır.  
Amaç: **ileriye dönük, sürdürülebilir ve açık** bir yazılım mimarisi.

---

## 🔧 Teknik Özellikler
- .NET 9.0.308 SDK desteği  
- MAUI 9.0.100 paketleri (Controls, Essentials, WebView, Compatibility)  
- CommunityToolkit.Maui 9.0.0 entegrasyonu  
- Newtonsoft.Json 13.0.3 ile veri işleme  
- install-shell.ps1, hata-gider.ps1 ve setup.ps1 scriptleri ile tam otomasyon  
- Windows build → sadeleştirilmiş, MSIX paketleme ileride eklenecek  
- Android build → Linux makinede ayrı olarak çalıştırılacak  

---

## 📖 Kurulum

NugreOS’i kurmak ve derlemek için tek yapmanız gereken `setup.ps1` scriptini çalıştırmaktır.  
Bu script, gerekli workload ve NuGet paketlerini yükler, MSIX uyarılarını bastırır ve projeyi derlemeye hazır hale getirir.  

### Adımlar
1. Projeyi klonlayın:
   ```
   git clone https://github.com/korfez2023/NugreOS.git
   cd NugreOS
   ```

2. `setup.ps1` scriptini çalıştırın:
   ```
   .\setup.ps1
   ```

3. Script otomatik olarak şunları yapar:
   - .NET MAUI workload’u günceller  
   - Gerekli NuGet paketlerini yükler  
   - MSIX uyarısını bastırır  
   - `dotnet restore` ve `dotnet build` ile projeyi derler  

4. Derleme tamamlandığında NugreOS çalışmaya hazırdır 🚀  

---

## 🎯 Vizyon
- NugreOS, geçmişi onurlandırarak geleceği inşa eder.  
- Her 18 ayda bir yeni major sürüm yayınlanır.  
- LTS sürümleri ayrı branch’te tutulur.  
- Ana branch (`main`) → her zaman en güncel sürüm.  
- Açık kaynak topluluk katkısına açık, sürdürülebilir ve paylaşım odaklı.  

---

📂 GitHub: [korfez2023/NugreOS](https://github.com/korfez2023/NugreOS)

---


