# Min viktresa – iPhone-webbapp

Appen fungerar offline efter första besöket på den publicerade adressen. Registreringar lagras **enbart i Safari på den aktuella enheten**. Ingen synkronisering eller inloggning. Exportera säkerhetskopia regelbundet.

## Publicera på GitHub Pages
1. Logga in på GitHub och skapa ett **nytt separat offentligt repository**, t.ex. `min-viktresa-app`. Lägg inte detta i PiNFO. GitHub Pages på gratis konto kräver normalt ett publikt repository. Publicerad kod och webbadress blir tillgängliga för andra; inga registreringar skickas till GitHub.
2. Ladda upp de sju filerna i den här mappen till repositoryts rot via **Add file → Upload files** och välj **Commit changes**.
3. Öppna **Settings → Pages → Build and deployment → Deploy from a branch**, välj `main` och `/(root)` och spara.
4. Besök adressen som visas där, normalt `https://DITT-NAMN.github.io/min-viktresa-app/`.
5. Öppna den adressen i **Safari på iPhone** → Dela → **Lägg till på hemskärmen** → Lägg till.

## Viktigt
- Sidan är **inte lösenordsskyddad**. Publicera inte känslig historik i kodfilerna. Dagliga registreringar förblir i telefonens lokala lagring, så länge Safari behåller den.
- Samma webbapp på dator och iPhone har **separata data**. Flytta via *Säkerhetskopia (JSON)* och *Importera säkerhetskopia*.
- Tidigare historik från HTML-filen förs **inte över automatiskt** till den nya webbdomänen. Exportera och importera den.
- Vid borttagning av Safari-webbplatsdata, ominstallation eller byte av domän kan informationen gå förlorad.
- Om du visar appen för andra på din telefon ser de de uppgifter du har registrerat, inklusive öl-fältet.
