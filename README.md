
# **LockByte**

**Komunikator tekstowy stawiający prywatność na 1. miejscu!**

LockByte to nowoczesny, bezpieczny komunikator tekstowy, zaprojektowany z myślą o maksymalnej ochronie prywatności użytkowników. W dobie rosnących zagrożeń dla prywatności, LockByte oferuje niezawodne technologie zabezpieczeń, które zapewniają pełną anonimowość i ochronę danych.

## **Kluczowe funkcje**

### **1. End-to-End Encryption (E2EE)**  
LockByte wykorzystuje szyfrowanie typu end-to-end. Wiadomości są szyfrowane na urządzeniu nadawcy i deszyfrowane dopiero na urządzeniu odbiorcy. Ani LockByte, ani żaden pośrednik nie ma dostępu do treści wiadomości. Używamy sprawdzonych algorytmów, takich jak:
- **AES-256**: Szyfrowanie symetryczne z kluczem 256-bitowym.
- **RSA-4096**: Wymiana kluczy oparta na algorytmie asymetrycznym.
- **ECDH (Elliptic Curve Diffie-Hellman)**: Protokół wymiany kluczy, który umożliwia szybkie i bezpieczne ustalenie wspólnego klucza sesji.

### **2. Forward Secrecy**  
LockByte implementuje mechanizm **Perfect Forward Secrecy (PFS)**, co oznacza, że w przypadku naruszenia klucza sesji, wcześniejsze wiadomości pozostają bezpieczne. Każda sesja ma unikalny klucz, który nie jest ponownie wykorzystywany.

### **3. Brak centralnych serwerów**  
Komunikator korzysta z **architektury zdecentralizowanej** lub **peer-to-peer (P2P)**, co minimalizuje ryzyko ataków na centralne serwery. W LockByte wiadomości są przesyłane bezpośrednio między użytkownikami, co dodatkowo zmniejsza możliwość śledzenia i analizy ruchu sieciowego.

### **4. Zero Knowledge Proof**  
LockByte stosuje zasadę **Zero-Knowledge Proof (ZKP)**, co oznacza, że nawet serwery zarządzające komunikacją nie mają wiedzy o zawartości przesyłanych danych ani o tożsamości użytkowników.

### **5. Samoniszczące wiadomości**  
Użytkownicy mogą ustawić automatyczne usuwanie wiadomości po określonym czasie. Wiadomości są usuwane zarówno z urządzenia nadawcy, jak i odbiorcy.

### **6. Anonimowość użytkowników**  
LockByte nie wymaga numerów telefonów ani adresów e-mail do rejestracji. Użytkownicy tworzą anonimowe identyfikatory (pseudonimy), co eliminuje możliwość powiązania ich tożsamości z kontem. **Założenie konta kosztuje jedynie 1$, a płatność można dokonać przy pomocy kryptowalut, co dodatkowo zwiększa anonimowość.**

### **7. Ochrona przed atakami typu Man-in-the-Middle (MitM)**  
Dzięki zaawansowanym mechanizmom autoryzacji kluczy, LockByte chroni użytkowników przed atakami typu MitM. Zastosowanie technik takich jak **Certyfikaty Kluczy Publicznych (PKI)** i **TOFU (Trust On First Use)** pozwala na bezpieczne nawiązywanie nowych połączeń.

### **8. Brak zbierania metadanych**  
LockByte nie gromadzi żadnych metadanych na temat użytkowników, takich jak logi połączeń, informacje o lokalizacji czy czas przesyłania wiadomości.

### **9. Wsparcie dla sieci TOR**  
Dla dodatkowego poziomu prywatności, LockByte jest kompatybilny z siecią **TOR (The Onion Router)**, co pozwala na ukrycie adresu IP użytkownika i zapewnia anonimowość na poziomie sieciowym.

## **Technologie i standardy zabezpieczeń**

- **Szyfrowanie AES-256**: Oferuje najwyższy poziom bezpieczeństwa dla przesyłanych danych.
- **RSA-4096 wraz z ECDH**: Algorytmy te zapewniają bezpieczną wymianę kluczy.
- **HMAC-SHA256**: Używany do zapewnienia integralności danych, chroniąc wiadomości przed manipulacją.
- **TLS 1.3**: Najnowsza wersja protokołu TLS, zapewniająca bezpieczne połączenia podczas komunikacji z serwerami.

## **Ochrona prywatności i bezpieczeństwa użytkowników**

### **1. Brak śledzenia aktywności**  
LockByte nie monitoruje ani nie zapisuje aktywności użytkowników. Wszelkie interakcje są całkowicie prywatne, bez zbierania danych w celach marketingowych lub analitycznych.

### **2. Niepowtarzalne tożsamości użytkowników**  
Każdy użytkownik ma unikalne ID, generowane lokalnie na urządzeniu, bez potrzeby podawania danych osobowych.

### **3. Funkcja "Safe Room"**  
LockByte oferuje możliwość tworzenia „bezpiecznych pokoi” do rozmów grupowych. Wiadomości w tych pokojach są dodatkowo szyfrowane za pomocą unikalnych kluczy.

### **4. Uwierzytelnianie dwuskładnikowe (2FA)**  
Użytkownicy LockByte mogą dodatkowo zabezpieczyć swoje konta poprzez włączenie uwierzytelniania dwuskładnikowego (2FA), np. za pomocą aplikacji generujących jednorazowe kody lub fizycznych kluczy bezpieczeństwa zgodnych z FIDO2.

### **5. Blokada biometryczna i PIN**  
Aplikacja wspiera zabezpieczenia takie jak blokada biometryczna oraz kod PIN, aby uniemożliwić nieautoryzowany dostęp do aplikacji i wiadomości.

### **6. Szyfrowanie lokalne**  
LockByte szyfruje wszystkie dane przechowywane lokalnie na urządzeniu użytkownika za pomocą AES-256, co zapewnia, że nawet w przypadku fizycznego dostępu do urządzenia, dane pozostają bezpieczne.

## **Przejrzysta polityka prywatności**

LockByte stosuje zasadę **Zero Trust**, co oznacza, że nawet zespół deweloperów nie ma dostępu do danych użytkowników. Wszystkie interakcje są szyfrowane, a firma nie przechowuje żadnych danych, które mogłyby zostać wykorzystane do identyfikacji lub monitorowania użytkowników. LockByte działa zgodnie z przepisami **GDPR** oraz innymi międzynarodowymi regulacjami dotyczącymi ochrony prywatności.

## **Open Source i audyty bezpieczeństwa**

LockByte jest projektowany jako **open source**, co oznacza, że cały kod aplikacji jest dostępny na GitHubie do wglądu i audytowania przez społeczność oraz niezależnych ekspertów ds. bezpieczeństwa. Regularne audyty bezpieczeństwa prowadzone przez zewnętrzne firmy zapewniają, że LockByte jest zgodny z najnowszymi standardami ochrony prywatności i bezpieczeństwa.

## **Wieloplatformowość i synchronizacja**

LockByte to komunikator dostępny na wielu platformach, co pozwala na wygodne korzystanie z aplikacji na różnych urządzeniach bez utraty bezpieczeństwa. Wiadomości są synchronizowane między urządzeniami z pełnym zachowaniem prywatności.

### **1. Dostępność na różnych platformach:**
- **Desktop**: Windows, macOS, Linux.
- **Mobile**: iOS i Android.
- **Web**: Zabezpieczona wersja przeglądarkowa.

### **2. Lokalne szyfrowanie kluczy:**
Klucze szyfrujące są przechowywane lokalnie na urządzeniu użytkownika i nigdy nie są wysyłane na serwery.

## **Tryb „Stealth Mode”**

LockByte oferuje **tryb ukrycia (Stealth Mode)**, który wzmacnia ochronę prywatności użytkowników w sytuacjach zagrożenia:

- **Ukrywanie aplikacji**: Aplikacja może być ukryta przed nieautoryzowanymi użytkownikami.
- **Szybkie usuwanie danych**: W sytuacjach awaryjnych użytkownik może usunąć wszystkie dane lokalne za pomocą jednego przycisku.

