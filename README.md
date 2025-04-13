Për të krijuar një skedar `.env` në folderin kryesor të programit tuaj (ku ndodhet `manage.py`), mund të ndiqni këto hapa:

1. **Krijoni skedarin**: Në terminalin tuaj, navigoni në folderin e projektit dhe krijoni skedarin `.env` me komandën:

   ```bash
   touch .env
   ```

2. **Hapni skedarin**: Përdorni një editor teksti për të hapur skedarin `.env`. Mund të përdorni `nano`, `vim`, ose ndonjë editor tjetër sipas preferencës suaj:

   ```bash
   nano .env
   ```

3. **Shtoni informacionin në skedar**: Kopjoni dhe shkruani informacionin e nevojshëm për lidhjen me databazën, duke e zëvendësuar vlerat përkatëse me ato të sakta për projektin tuaj.

   ```plaintext
   DEBUG=True
   HOST=hostin ku ndodhet databaza
   PORT=porta
   USER=username
   PASSWORD=passrwordin per databazen
   NAME=emrin e databazes
   ```

   P.sh., nëse po përdorni një databazë MySQL me host `localhost`, port `3306`, dhe emrin e databazës `mydatabase`, do të dukej kështu:

   ```plaintext
   DEBUG=True
   HOST=localhost
   PORT=3306
   USER=myuser
   PASSWORD=mypassword
   NAME=mydatabase
   ```

4. **Ruani dhe mbyllni skedarin**: Nëse po përdorni `nano`, mund ta ruani dhe mbyllni duke shtypur `CTRL + X`, pastaj `Y` për të konfirmuar ruajtjen dhe `Enter` për të dalë.

Tani keni krijuar një skedar `.env` të gatshëm për t'u përdorur në projekte tuaj me Django ose frameworke të tjera. Sigurohuni që të mos e publikoni këtë skedar në versionet tuaj ekzistuese për të mbrojtur informacionin e ndjeshëm.
