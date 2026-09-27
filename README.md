# Schemer — Mobile Android

Dit project maakt van de bestaande `Schemer.html` game een mobiele Android-game.

## GitHub compile

Het project bevat:

- `SchemerMobile.code-workspace` — VS Code workspace-bestand.
- `.github/workflows/android-build.yml` — compileert automatisch op GitHub Actions.
- Android target API 36.
- Touch-besturing en liggende schermstand.

### GitHub gebruiken

1. Upload deze volledige map naar een GitHub-repository.
2. Push naar `main` of `master`.
3. Open in GitHub het tabblad **Actions**.
4. De workflow **Build Schemer Mobile** compileert automatisch.
5. Na afloop staan de bestanden bij de workflow-run onder **Artifacts**:
   - `schemer-mobile-apk`
   - `schemer-mobile-aab`

Je kunt de workflow ook handmatig starten met **Run workflow**.

## Android Studio / VS Code

Open `SchemerMobile.code-workspace` in VS Code, of open de projectmap in Android Studio.

Voor Google Play moet een release-build uiteindelijk met jouw eigen signing key worden ondertekend.
