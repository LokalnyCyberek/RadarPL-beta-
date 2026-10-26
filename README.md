# 🛡️ RadarPL — Air Threat & Military Aircraft Monitor

**RadarPL** to zaawansowana aplikacja mobilna dla systemu Android, stworzona w technologii **Jetpack Compose**. Służy do monitorowania w czasie rzeczywistym zagrożeń powietrznych (drony kamikadze, rakiety manewrujące i balistyczne, bomby kierowane) oraz śledzenia na żywo lotów wojskowych państw NATO i sojuszniczych na wschodniej flance.

---

## 🌟 Główne Funkcje

- **📡 Monitorowanie Zagrożeń w Czasie Rzeczywistym:** 
  - Integracja z protokołem WebSocket oraz REST API (Neptun).
  - Śledzenie dronów (Shahed / BpLA, FPV, rozpoznawcze), rakiet manewrujących i balistycznych, bomb KAB oraz nosicieli MiG-31K / Kinżał.
- **✈️ Śledzenie Lotów Wojskowych Live:** 
  - Integracja z otwartymi sieciami transponderów (OpenSky Network oraz ADSB.fi).
  - Precyzyjne filtrowanie wyłącznie maszyn wojskowych (AWACS, tankowce KC-135, drony strategiczne RQ-4 Global Hawk, zwiadowcze RC-135, myśliwce F-16).
- **🗺️ Interaktywna Mapa Taktyczna (OsmDroid):** 
  - Darmowe kafelki mapy z polskojęzycznymi etykietami.
  - Autorskie wektorowe znaczniki taktyczne bez zbędnych obwódek, skalowane optymalnie przy przybliżaniu i oddalaniu.
- **📖 Encyklopedia Wikipedia w Czasie Rzeczywistym:** 
  - Automatyczne pobieranie zdjęć, opisów i specyfikacji technicznych z polskiej Wikipedii dla każdego samolotu lub zagrożenia po kliknięciu.
- **🎨 Nowoczesny Interfejs Material 3 (Dark Tactical Theme):** 
  - Ciemny motyw operacyjny zaprojektowany z myślą o czytelności w dzień i w nocy, z obsługą trybu Edge-to-Edge.

---

## 🛠️ Stos Technologiczny

- **Język:** Kotlin
- **UI:** Jetpack Compose, Material 3, Material Icons Extended
- **Architektura:** MVVM (ViewModel, StateFlow, Coroutines)
- **Sieć:** OkHttp 4, Kotlinx Serialization JSON
- **Mapa:** OsmDroid (OpenStreetMap Android SDK)
- **Ładowanie Obrazów:** Coil 2.7 (z obsługą nagłówków User-Agent dla Wikipedi)

⚠️ Zastrzeżenie Prawne (Disclaimer)
Aplikacja ma charakter wyłącznie informacyjno-edukacyjny i korzysta z ogólnodostępnych agregatorów danych OSINT oraz otwartych sieci transponderów. 
Nie zastępuje oficjalnych systemów ostrzegania państwowego (syren alarmowych, alertów RCB czy RSO).
W sytuacji realnego zagrożenia należy kierować się wyłącznie komunikatami odpowiednich służb państwowych.
