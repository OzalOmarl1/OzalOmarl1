<p align="center">
  <img src="banner.svg" alt="Ozal Omarlı — Bilgisayarlı Görü · Derin Öğrenme · Siber Güvenlik" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=500&amp;size=20&amp;duration=3200&amp;pause=900&amp;color=38BDF8&amp;center=true&amp;vCenter=true&amp;width=620&amp;lines=Bilgisayarl%C4%B1%20G%C3%B6r%C3%BC%20ve%20Nesne%20Tespiti;YOLOv8%20ile%20Erken%20Uyar%C4%B1%20Sistemleri;S%C4%B1zma%20Testi%20ve%20A%C4%9F%20G%C3%BCvenli%C4%9Fi;%C3%96n-Kay%C4%B1tl%C4%B1%2C%20Tekrarlanabilir%20Deneyler" alt="İlgi alanları"/>
</p>

<p align="center">
  <a href="mailto:ozalomerli011@gmail.com"><img src="https://img.shields.io/badge/ozalomerli011%40gmail.com-D14836?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="ozalomerli011@gmail.com" height="28"/></a>
  <img src="https://img.shields.io/badge/OST%C4%B0M%20Teknik%20%C3%9Cniversitesi%20%C2%B7%20Yaz%C4%B1l%C4%B1m%20M%C3%BChendisli%C4%9Fi%20YL-0A3D62?style=for-the-badge" alt="OSTİM Teknik Üniversitesi · Yazılım Mühendisliği YL" height="28"/>
  <img src="https://img.shields.io/badge/Siber%20Vatan%20%C2%B7%202%20sertifika-C8102E?style=for-the-badge" alt="Siber Vatan · 2 sertifika" height="28"/>
</p>

---

## 👋 Hakkımda

OSTİM Teknik Üniversitesi Fen Bilimleri Enstitüsü'nde **Yazılım Mühendisliği yüksek lisans** öğrencisiyim; **bilgisayarlı görü**, **derin öğrenme** ve **siber güvenlik** alanlarında çalışıyorum. Görüntü işleme tarafında nesne tespiti modellerinin gerçek koşullardaki (bulanıklık, eğiklik, uzak/yakın nesne, aydınlatma) dayanıklılığıyla ve bu dayanıklılığın **dürüst ölçülmesiyle** ilgileniyorum: deneylerimi önceden yazılmış protokollerle, eşit bütçe ve çoklu tohumla yürütüyor, kilitli test kümeleri kullanıyor ve tüm sonuçları raporluyorum. Güvenlik tarafında keşif, ağ trafiği analizi, web uygulama güvenliği ve sosyal mühendislik farkındalığı üzerine yetkili laboratuvar ortamlarında çalışıyorum.

- 🎓 **Eğitim:** Yazılım Mühendisliği Yüksek Lisans, OSTİM Teknik Üniversitesi Fen Bilimleri Enstitüsü
- 🏅 **Siber güvenlik eğitimleri:** Siber Vatan — *Beyaz Şapkalı Hacker ve Temel Linux* (56 saat) ve *Sızma Testi* (40 saat)
- 🧪 **Yöntem ilkem:** ön-kayıt · eşit bütçe · çoklu tohum · kilitli/harici test · her testi raporla
- 🛡️ **Güvenlik ilkem:** yalnız yetkili ve izole ortamlarda, etik çerçevede test
- 💬 **Konuşmaktan keyif aldığım konular:** nesne tespiti, veri artırımı, model değerlendirme, sızma testi, YZ etiği

---

## 📄 Yayınlar

> **Güvenli Dijitalleşme ve Yapay Zekâ Etiği Bağlamında Proaktif Risk Algılama: YOLOv8 Tabanlı Erken Uyarı Sistemi**<br/>
> *Dijital Dünyanın Kullanıcıları Üniversitelerarası Öğrenci Sempozyumu*, Erzincan Binali Yıldırım Üniversitesi · Bildiri Kitabı, s. 277–290<br/>
> 📄 [Sempozyum bildiri kitabı (PDF)](https://ogrencisempozyumu.ebyu.edu.tr/Sempozyum_Bildiri_Kitabi.pdf#page=280)

---

## 📌 Öne Çıkan Proje

<table>
  <tr>
    <td width="100%">
      <h3>🔥 <a href="https://ogrencisempozyumu.ebyu.edu.tr/Sempozyum_Bildiri_Kitabi.pdf#page=280">YOLOv8 Tabanlı Proaktif Erken Yangın Uyarı Sistemi</a></h3>
      <p>Dumanı yangının <b>erken habercisi (prekürsör)</b> olarak ele alan, gerçek zamanlı kamera görüntülerinde <b>duman</b> ve <b>alev</b> tespit eden bir erken uyarı sistemi. <b>İki düzeyli alarm politikası</b> (ön uyarı + kritik alarm) yanlış alarm yükünü ve kaçırılan tespit riskini birlikte yönetir; <b>etik kalibrasyon, insan denetimi ve açıklanabilirlik</b> tasarımın parçasıdır.</p>
      <table>
        <tr><th>Genel mAP50</th><th>Yangın (P / R)</th><th>Duman (P / R)</th></tr>
        <tr><td align="center"><b>0.86</b></td><td align="center">0.91 / 0.88</td><td align="center">0.79 / 0.83</td></tr>
      </table>
      <ul>
        <li><b>Veri:</b> Kaggle Fire-Smoke Dataset, Kaggle CVA_YOLO_S&amp;F ve Roboflow Fire Smoke Detection birleştirildi; depo, laboratuvar, ofis, tünel ve endüstriyel iç mekân sahneleri, gündüz/gece koşulları</li>
        <li><b>Eğitim:</b> COCO ön-eğitimli ağırlıklarla transfer öğrenme, AdamW, 50+ epoch; mozaik, rastgele ölçekleme, yatay çevirme, HSV ve kırpma/kaydırma artırımları</li>
        <li><b>Alarm:</b> düşük/orta güvenli duman → operatöre ön uyarı ve doğrulama; zamansal sürekliliği olan yüksek güvenli duman ve/veya alev → kritik alarm</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&amp;logo=ultralytics&amp;logoColor=white" alt="YOLOv8" height="28"/>
        <img src="https://img.shields.io/badge/Transfer%20%C3%B6%C4%9Frenme%20%C2%B7%20COCO-0E7490?style=for-the-badge" alt="Transfer öğrenme · COCO" height="28"/>
        <img src="https://img.shields.io/badge/mAP50%200.86-15803D?style=for-the-badge" alt="mAP50 0.86" height="28"/>
        <a href="https://ogrencisempozyumu.ebyu.edu.tr/Sempozyum_Bildiri_Kitabi.pdf#page=280"><img src="https://img.shields.io/badge/Bildiri%20%C2%B7%20s.%20277%E2%80%93290-B45309?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxlbGxpcHNlIGN4PScxMicgY3k9JzUnIHJ4PSc4JyByeT0nMycvPjxwYXRoIGQ9J000IDV2MTRjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtM1Y1Jy8%2BPHBhdGggZD0nTTQgMTJjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtMycvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="Bildiri · s. 277–290" height="28"/></a>
      </p>
    </td>
  </tr>
</table>

---

## 🏅 Siber Güvenlik Sertifikaları

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="sertifika-beyaz-sapkali-hacker.jpg"><img src="sertifika-beyaz-sapkali-hacker.jpg" alt="Beyaz Şapkalı Hacker ve Temel Linux sertifikası" width="100%"/></a>
      <h4>🎩 Beyaz Şapkalı Hacker ve Temel Linux</h4>
      <p><b>56 saat</b> · 13–19 Aralık 2023<br/>
      Kalkınma Ajansları <b>Siber Vatan Programı</b> (T.C. Sanayi ve Teknoloji Bakanlığı)<br/>
      T.C. Batı Akdeniz Kalkınma Ajansı ve Burdur Mehmet Akif Ersoy Üniversitesi işbirliği<br/>
      Eğitim: Cyrops Siber Güvenlik A.Ş.</p>
    </td>
    <td width="50%" valign="top">
      <a href="sertifika-sizma-testi.jpg"><img src="sertifika-sizma-testi.jpg" alt="Sızma Testi sertifikası" width="100%"/></a>
      <h4>🎯 Sızma Testi</h4>
      <p><b>40 saat</b> · 19–23 Şubat 2024<br/>
      Kalkınma Ajansları <b>Siber Vatan Programı</b> (T.C. Sanayi ve Teknoloji Bakanlığı)<br/>
      T.C. Batı Akdeniz Kalkınma Ajansı ve Burdur Mehmet Akif Ersoy Üniversitesi işbirliği<br/>
      Eğitim: BG-TEK Bilgi Güvenliği Teknolojileri<br/>
      Doğrulama: <a href="https://www.bg-tek.net/verify">bg-tek.net/verify</a> · Kimlik <code>3E8B970CBB26B88</code></p>
    </td>
  </tr>
</table>

---

## 🛡️ Siber Güvenlik

| Alan | Araçlar |
|:--|:--|
| **Keşif ve tarama** | <img src="https://img.shields.io/badge/Nmap-0E5A8A?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxjaXJjbGUgY3g9JzEyJyBjeT0nMTInIHI9JzknLz48Y2lyY2xlIGN4PScxMicgY3k9JzEyJyByPSc1Jy8%2BPHBhdGggZD0nTTEyIDEybDYtNicvPjxjaXJjbGUgY3g9JzEyJyBjeT0nMTInIHI9JzEnIGZpbGw9J3doaXRlJy8%2BPC9zdmc%2B&amp;logoColor=white" alt="Nmap" height="28"/> <img src="https://img.shields.io/badge/Amass-2E7D32?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxjaXJjbGUgY3g9JzEyJyBjeT0nMTInIHI9JzknLz48cGF0aCBkPSdNMyAxMmgxOE0xMiAzYzMgMyAzIDE1IDAgMThNMTIgM2MtMyAzLTMgMTUgMCAxOCcvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="Amass" height="28"/> |
| **OSINT** | <img src="https://img.shields.io/badge/Maltego-1565C0?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxjaXJjbGUgY3g9JzUnIGN5PSc2JyByPScyLjUnLz48Y2lyY2xlIGN4PScxOScgY3k9JzYnIHI9JzIuNScvPjxjaXJjbGUgY3g9JzEyJyBjeT0nMTgnIHI9JzIuNScvPjxjaXJjbGUgY3g9JzEyJyBjeT0nMTAnIHI9JzInLz48cGF0aCBkPSdNNyA3bDMuNSAyTTE3IDdsLTMuNSAyTTEyIDEydjMuNScvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="Maltego" height="28"/> |
| **Ağ trafiği analizi** | <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&amp;logo=wireshark&amp;logoColor=white" alt="Wireshark" height="28"/> |
| **Web uygulama güvenliği** | <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&amp;logo=burpsuite&amp;logoColor=white" alt="Burp Suite" height="28"/> |
| **Kimlik doğrulama testleri** | <img src="https://img.shields.io/badge/Hydra-7F1D1D?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxjaXJjbGUgY3g9JzgnIGN5PScxNScgcj0nNCcvPjxwYXRoIGQ9J00xMSAxMmw5LTlNMTcgNmwzIDNNMTQgOWwyIDInLz48L3N2Zz4%3D&amp;logoColor=white" alt="Hydra" height="28"/> |
| **Sosyal mühendislik ve oltalama farkındalığı** | <img src="https://img.shields.io/badge/GoPhish-37474F?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxwYXRoIGQ9J00xMiAzdjExYTQgNCAwIDEgMS04IDAnLz48cGF0aCBkPSdNNCAxNGwyLTInLz48Y2lyY2xlIGN4PScxMicgY3k9JzMnIHI9JzEnLz48cGF0aCBkPSdNMTQgMTljMiAwIDYtMiA3LTUtMS0xLTMtMi01LTInLz48L3N2Zz4%3D&amp;logoColor=white" alt="GoPhish" height="28"/> <img src="https://img.shields.io/badge/SET-5B21B6?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxjaXJjbGUgY3g9JzEyJyBjeT0nNycgcj0nNCcvPjxwYXRoIGQ9J000IDIxYzAtNCAzLjUtNyA4LTdzOCAzIDggNycvPjxwYXRoIGQ9J005IDdoNicvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="SET" height="28"/> |
| **Active Directory analizi** | <img src="https://img.shields.io/badge/BloodHound-B71C1C?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxjaXJjbGUgY3g9JzYnIGN5PScxOCcgcj0nMicvPjxjaXJjbGUgY3g9JzE4JyBjeT0nMTgnIHI9JzInLz48Y2lyY2xlIGN4PScxMicgY3k9JzUnIHI9JzInLz48Y2lyY2xlIGN4PScxMicgY3k9JzEyJyByPScyJy8%2BPHBhdGggZD0nTTEyIDd2M00xMC41IDEzLjVsLTMgM00xMy41IDEzLjVsMyAzTTggMThoOCcvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="BloodHound" height="28"/> |
| **Platform ve betik** | <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&amp;logo=kalilinux&amp;logoColor=white" alt="Kali Linux" height="28"/> <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&amp;logo=gnubash&amp;logoColor=white" alt="Bash" height="28"/> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python" height="28"/> |

---

## 👁️ Görüntü İşleme ve Derin Öğrenme

| Alan | Araçlar |
|:--|:--|
| **Görüntü işleme** | <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&amp;logo=opencv&amp;logoColor=white" alt="OpenCV" height="28"/> |
| **Nesne tespiti** | <img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&amp;logo=ultralytics&amp;logoColor=white" alt="YOLOv8" height="28"/> <img src="https://img.shields.io/badge/Ultralytics-0B23A9?style=for-the-badge&amp;logo=ultralytics&amp;logoColor=white" alt="Ultralytics" height="28"/> |
| **Sınıflandırma omurgaları** | <img src="https://img.shields.io/badge/ResNet-6D28D9?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxyZWN0IHg9JzUnIHk9JzMnIHdpZHRoPSc4JyBoZWlnaHQ9JzQnIHJ4PScxJy8%2BPHJlY3QgeD0nNScgeT0nMTAnIHdpZHRoPSc4JyBoZWlnaHQ9JzQnIHJ4PScxJy8%2BPHJlY3QgeD0nNScgeT0nMTcnIHdpZHRoPSc4JyBoZWlnaHQ9JzQnIHJ4PScxJy8%2BPHBhdGggZD0nTTEzIDVoNXYxNGgtNScvPjxwYXRoIGQ9J00xNiAxNmwtMyAzIDMgMycgdHJhbnNmb3JtPSd0cmFuc2xhdGUoMCwtMyknLz48L3N2Zz4%3D&amp;logoColor=white" alt="ResNet" height="28"/> |
| **Derin öğrenme çatıları** | <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch" height="28"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&amp;logo=tensorflow&amp;logoColor=white" alt="TensorFlow" height="28"/> <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&amp;logo=keras&amp;logoColor=white" alt="Keras" height="28"/> |
| **Bilimsel Python** | <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&amp;logo=numpy&amp;logoColor=white" alt="NumPy" height="28"/> <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&amp;logo=pandas&amp;logoColor=white" alt="pandas" height="28"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&amp;logo=scikitlearn&amp;logoColor=white" alt="scikit-learn" height="28"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&amp;logo=jupyter&amp;logoColor=white" alt="Jupyter" height="28"/> |
| **GPU ve araştırma altyapısı** | <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&amp;logo=nvidia&amp;logoColor=white" alt="CUDA" height="28"/> <img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&amp;logo=latex&amp;logoColor=white" alt="LaTeX" height="28"/> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git" height="28"/> |
| **Veri kümeleri** | <img src="https://img.shields.io/badge/Fire--Smoke%20Dataset-20BEFF?style=for-the-badge&amp;logo=kaggle&amp;logoColor=white" alt="Fire-Smoke Dataset" height="28"/> <img src="https://img.shields.io/badge/CVA__YOLO__S%26F-20BEFF?style=for-the-badge&amp;logo=kaggle&amp;logoColor=white" alt="CVA_YOLO_S&F" height="28"/> <img src="https://img.shields.io/badge/Fire%20Smoke%20Detection-6706CE?style=for-the-badge&amp;logo=roboflow&amp;logoColor=white" alt="Fire Smoke Detection" height="28"/> <a href="https://github.com/detectRecog/CCPD"><img src="https://img.shields.io/badge/CCPD2019-334155?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxlbGxpcHNlIGN4PScxMicgY3k9JzUnIHJ4PSc4JyByeT0nMycvPjxwYXRoIGQ9J000IDV2MTRjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtM1Y1Jy8%2BPHBhdGggZD0nTTQgMTJjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtMycvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="CCPD2019" height="28"/></a> <a href="https://github.com/detectRecog/CCPD"><img src="https://img.shields.io/badge/CCPD2020-334155?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxlbGxpcHNlIGN4PScxMicgY3k9JzUnIHJ4PSc4JyByeT0nMycvPjxwYXRoIGQ9J000IDV2MTRjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtM1Y1Jy8%2BPHBhdGggZD0nTTQgMTJjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtMycvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="CCPD2020" height="28"/></a> <a href="https://github.com/yxgong0/CRPD"><img src="https://img.shields.io/badge/CRPD-334155?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCcgZmlsbD0nbm9uZScgc3Ryb2tlPSd3aGl0ZScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1saW5lam9pbj0ncm91bmQnPjxlbGxpcHNlIGN4PScxMicgY3k9JzUnIHJ4PSc4JyByeT0nMycvPjxwYXRoIGQ9J000IDV2MTRjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtM1Y1Jy8%2BPHBhdGggZD0nTTQgMTJjMCAxLjcgMy42IDMgOCAzczgtMS4zIDgtMycvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="CRPD" height="28"/></a> |

---

<p align="center">
  <i>“Önce ölç, sonra iddia et.”</i><br/>
  <sub>Tüm güvenlik çalışmaları yalnız yetkili ve izole ortamlarda, etik kurallar çerçevesinde yürütülür.</sub>
</p>
