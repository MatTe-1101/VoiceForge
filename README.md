# VoiceLink

App Android in Kotlin/Jetpack Compose che trasforma il telefono in un microfono con monitoraggio sugli altoparlanti, effetti vocali e correzione di intonazione sperimentale.

## Apertura

1. Apri questa cartella con **Android Studio** (JDK 17).
2. Lascia completare la sincronizzazione Gradle e installa su un telefono fisico con Android 8 o successivo.
3. Concedi il permesso **Microfono**, poi premi `Inizia a parlare`.

## Funzioni incluse

- Catena microfono → altoparlante a bassa latenza (48 kHz quando supportato), con instradamento preferenziale a cuffie/casse Bluetooth.
- Volume casse, guadagno microfono, indicatore di livello e latenza stimata.
- Quattro profili rapidi: Pulito, Podcast, Palco e Pop.
- Gate anti-rumore, cancellazione eco, riduzione rumore, AGC e limiter tramite gli effetti disponibili sul dispositivo.
- Autotune in tempo reale con tonalità, scala, intensità e velocità di correzione.
- Mixer voce a tre bande (bassi, medi, alti), riverbero e delay.
- Streaming Wi-Fi locale in UDP PCM-16 mono, 48 kHz: inserisci IP del ricevitore e porta (predefinita 5004), oppure usa il broadcast `255.255.255.255` se la rete lo consente.
- Tema Sistema, Chiaro e Scuro; i temi Sistema usano Material You su Android 12+.
- Console professionale a quattro aree: Live, Mixer, Voice Studio e Routing, con meter d'ingresso e scene rapide.
- Interfaccia Jetpack Compose Material 3: su Android 12+ usa automaticamente i colori Material You del telefono.

## Nota importante su sicurezza e resa

Il monitoraggio da microfono ad altoparlante può innescare feedback. Inizia sempre a volume basso, tieni il microfono lontano dalle casse e usa cuffie per risultati migliori. La cancellazione eco e l'autotune dipendono dal supporto audio del dispositivo: l'app li abilita quando Android li rende disponibili, ma non tutti i telefoni hanno la stessa qualità o la stessa latenza.

L'autotune qui è un processore leggero, pensato per monitoraggio in tempo reale; una correzione vocale da studio richiederebbe un motore DSP più pesante e introdurrebbe più latenza.
