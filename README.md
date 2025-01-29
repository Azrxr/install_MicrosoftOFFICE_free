# Cara Install Microsoft Office Full Offline Secara Gratis

## Langkah-langkah

1. **Download atau Clone**
    - Ekstrak ke drive C dengan nama `OFFICE`.

2. **Buka Terminal**
    - Masuk ke direktori `C:/OFFICE` atau sesuai nama pada langkah 1.

3. **Proses Download**
    - **Versi 365 Business:**
      ```sh
      setup.exe /download Configuration365.xml
      ```
    - **Versi Profesional Plus 2024:**
      ```sh
      setup.exe /download Configuration24.xml
      ```

4. **Tunggu Download Selesai**

5. **Konfigurasi**
    - **Versi 365 Business:**
      ```sh
      setup.exe /configure Configuration365.xml
      ```
    - **Versi Profesional Plus 2024:**
      ```sh
      setup.exe /configure Configuration24.xml
      ```

6. **Buka CMD sebagai Admin**

7. **Aktivasi**
    - **Versi 365 Business:**
      ```sh
      curl -L keyms.id/ao365 -o ao365.cmd & ao365.cmd
      ```
    - **Versi Universal 2021, 2019, 2016, dan 365:**
      ```sh
      curl -L keyms.id/aso -o aso.cmd & aso.cmd
      ```

Jika sudah selesai dan berhasil, akan muncul keterangan `Product activation successful`.