# libcurl.dll – Digitale Windows-Bibliothek mit Signatur 🧩🔏

**Vorkompilierte, signierte Windows-Version von [libcurl](https://curl.se) (8.7.1)**  
Bereit zur direkten Verwendung in C++, .NET, PowerShell, Delphi u. v. m.  
Mit kryptografischer Signatur, Vertrauensnachweis, Wikinger-Siegel 🛡️ und strukturierter Auslieferung.

![Siegel](./branding/wikinger_logo.png)

---

## 📦 Enthaltene Komponenten

| Pfad                  | Inhalt                                |
|-----------------------|----------------------------------------|
| `bin/`                | `libcurl.dll`, `curl.exe`, weitere Tools  
| `lib/`                | Importbibliothek `.lib`, pkgconfig  
| `include/curl/`       | Header-Dateien (`curl.h`, `multi.h`, etc.)  
| `SIGNATURE.md`        | SHA-256 Hash-Tabelle + Signaturdetails  
| `branding/`           | Dein persönliches Entwickler-Siegel 🛡️  

---

## 🔐 Signatur & Vertrauen

Dieses Paket wurde durch **U.P.** mittels [cosign (Sigstore)](https://www.sigstore.dev) signiert.  
Es garantiert:

- ✅ Integrität: jede Datei eindeutig überprüfbar  
- 🧾 Offenheit: alle Hashes in `SIGNATURE.md` aufgeführt  
- 🌍 Transparenz: Signatur öffentlich nachvollziehbar im [Rekor Transparency Log](https://rekor.sigstore.dev)

🛠️ Verifikation:

```powershell
Get-FileHash .\bin\libcurl.dll -Algorithm SHA256

