
# [NAZWA TWOJEGO PROJEKTU]

Ten projekt zawiera zbiór skryptów PowerShell oraz dokumentację do zarządzania środowiskiem laboratoryjnym opartym o [Wymień technologie: np. Windows Server, GNS3, Proxmox, Azure/AWS]. Celem tego repozytorium jest udostępnienie praktycznych rozwiązań do automatyzacji typowych zadań administracyjnych i nauki.

---

## Spis Treści

* [Wprowadzenie](#wprowadzenie)
* [Wymagania Systemowe](#wymagania-systemowe)
    * [Oprogramowanie](#oprogramowanie)
    * [Licencje](#licencje)
* [Struktura Projektu](#struktura-projektu)
* [Jak Używać](#jak-uzywac)
    * [Przykład: Tworzenie Użytkownika AD](#przykład-tworzenie-uzytkownika-ad)
* [Wkład](#wkład)
* [Licencjonowanie](#licencjonowanie)
* [Kontakt](#kontakt)

---

## Wprowadzenie

W tym projekcie znajdziesz:
* Skrypty PowerShell do automatyzacji zadań na Windows Server.
* Instrukcje konfiguracji środowiska laboratoryjnego.
* [Dodaj inne kluczowe elementy projektu]

Celem jest usprawnienie pracy administratorów systemów oraz dostarczenie praktycznych scenariuszy do nauki i testowania.

---

## Wymagania Systemowe

Aby móc korzystać z tego projektu, potrzebne będą następujące elementy:

### Oprogramowanie

* **Windows Server [Wersja, np. 2022]:** System operacyjny dla maszyn wirtualnych.
* **Windows Client [Wersja, np. 10/11]:** System operacyjny dla stacji roboczych w labie.
* **Proxmox VE [Wersja, np. 8.1]:** Platforma wirtualizacji użyta do hostowania maszyn wirtualnych.
* **GNS3 [Wersja, np. 2.2.46]:** Emulator/symulator sieciowy dla urządzeń sieciowych.
* **PowerShell [Wersja, np. 5.1 / 7.x]:** Środowisko uruchomieniowe skryptów.
* **[Nazwa Dystrybucji Linux, np. Ubuntu Server 22.04 LTS]:** Używany jako maszyny wirtualne w labie.
* **[Wymień inne narzędzia, np. Visual Studio Code, Git]**

### Licencje

Pamiętaj, że niektóre komponenty użyte w tym labie mogą wymagać posiadania odpowiednich licencji.

* **Windows Server & Windows Client:**
    * Użyto **wersji ewaluacyjnych** (np. `Windows Server 2022 Evaluation`, `Windows 10 Pro Evaluation`).
    * Możesz pobrać swoje kopie ewaluacyjne z [Microsoft Evaluation Center](https://www.microsoft.com/en-us/evalcenter/).
    * **UWAGA:** Nie udostępniaj plików instalacyjnych ani kluczy licencyjnych systemów Windows w tym repozytorium.
* **Proxmox VE:**
    * Dostępny na licencji **GNU Affero General Public License (AGPLv3)**.
    * Oficjalna strona: [https://www.proxmox.com/](https://www.proxmox.com/)
* **GNS3:**
    * Dostępny na licencji **GNU General Public License (GPLv3)**.
    * Oficjalna strona: [https://www.gns3.com/](https://www.gns3.com/)
* **Obrazy z Marketplace (GNS3, Proxmox VE Templates):**
    * **[Nazwa Obrazu, np. Cisco IOSvL2]:** Obrazy komercyjne (np. urządzenia sieciowe Cisco, Juniper, FortiGate) wymagają odpowiedniej licencji od producenta. Zazwyczaj dostępne jako wersje ewaluacyjne lub po zakupie/posiadaniu kontraktu serwisowego.
        * **Źródło:** [Link do strony producenta/portalu, np. Cisco Software Download (wymaga konta)](https://software.cisco.com/)
        * **UWAGA:** Nie udostępniaj tych obrazów w tym repozytorium.
    * **[Nazwa Obrazu, np. Ubuntu Server]:** Obrazy systemów operacyjnych open source są zazwyczaj dostępne bezpłatnie.
        * **Źródło:** [Oficjalna strona pobierania, np. https://ubuntu.com/download/server](https://ubuntu.com/download/server)
* **Linux (ogólnie):**
    * Większość dystrybucji Linuksa (np. Ubuntu, Debian, CentOS) jest udostępniana na licencjach **open source** (np. GPL).
    * **Źródło:** [Link do oficjalnej strony dystrybucji]
* **Azure / AWS (Obrazy z Marketplace Chmury):**
    * Jeśli lab wykorzystuje maszyny wirtualne z Marketplace Azure lub AWS, koszty licencji (jeśli dotyczy) są zazwyczaj wliczone w cenę użycia instancji.
    * **UWAGA:** Korzystanie z zasobów chmurowych może wiązać się z kosztami. Upewnij się, że znasz cennik dostawcy (Azure/AWS).
    * **Źródło:** [Link do dokumentacji Azure/AWS dotyczącej konkretnego ob
