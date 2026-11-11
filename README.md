<p align="center">
  <img src=".github/assets/nimbus-cover.png" alt="Nimbus: koyu zeminde kırmızı ışıkla aydınlanan saydam cam dalga" width="100%">
</p>

<h1 align="center">Müziğe yer aç.</h1>

<p align="center">
  Windows için Nimbus.<br>
  Yeni şarkılar keşfet, çevrimdışı dinle, arkadaşlarınla aynı parçaya eşlik et.
</p>

<p align="center">
  <a href="https://github.com/ensomg/nimbus-releases/releases/latest">
    <img src="https://img.shields.io/badge/Windows_i%C3%A7in_indir-ff4d4d?style=for-the-badge" alt="Windows için Nimbus indir" height="36">
  </a>
</p>

<p align="center">
  <a href="https://github.com/ensomg/nimbus-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/ensomg/nimbus-releases?style=flat-square&amp;label=son%20s%C3%BCr%C3%BCm&amp;labelColor=141414&amp;color=ff4d4d" alt="Nimbus'un son sürümü">
  </a>
  &nbsp; · &nbsp;
  <a href="https://github.com/ensomg/nimbus-releases/releases">Sürüm notları</a>
  &nbsp; · &nbsp;
  <a href="#kurulum">Kurulum</a>
</p>

<br>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Bağlantı gitse de müzik kalır.</h3>
      <p>Şarkıları üç nokta menüsünden indir. İnternetin olmadığında da dinlemeye devam et.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Aynı şarkı, aynı an.</h3>
      <p>Profil menüsünden bir dinleme partisi başlat, kodunu paylaş. 10 kişiye kadar aynı şarkıyı birlikte dinleyin.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Sözleri takip et.</h3>
      <p>Hareketli şarkı sözleriyle dinlediğin parçaya satır satır eşlik et.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Biraz cam, biraz ışık.</h3>
      <p>Açık ya da koyu tema seç. Ayarlar → Görünüm bölümünden Liquid Glass'ı açıp buzlu cam görünümünü dene.</p>
    </td>
  </tr>
</table>

<br>

## Kurulum

1. [Son sürümü aç](https://github.com/ensomg/nimbus-releases/releases/latest) ve **Assets** bölümündeki `Nimbus-Setup-…exe` dosyasını indir.
2. Kurulum dosyasını çalıştır ve Nimbus'u aç.
3. İlk açılıştaki hoş geldin turuyla uygulamayı tanı, dinlemeye başla.

Turu yeniden açmak istersen **Ayarlar → Görünüm** bölümüne uğra.

## Her yeni sürüm burada.

Windows kurulum dosyaları ve uygulama içi güncellemeler bu depodan dağıtılır. Nelerin değiştiğini [sürüm notlarından](https://github.com/ensomg/nimbus-releases/releases) takip edebilirsin.

<details>
  <summary>İndirdiğim dosyayı nasıl doğrularım?</summary>

İndirdiğin kurulum dosyasının SHA-256 özetini, aynı sürümün **Assets** bölümündeki `SHA256SUMS.txt` ile karşılaştırabilirsin.

Windows PowerShell'de dosyanın bulunduğu klasörü açıp çalıştır:

```powershell
Get-FileHash -Path .\Nimbus-Setup-*.exe -Algorithm SHA256
```

[Son sürümün SHA-256 listesi](https://github.com/ensomg/nimbus-releases/releases/latest/download/SHA256SUMS.txt)

</details>
