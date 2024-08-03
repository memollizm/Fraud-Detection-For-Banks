# <p align="center">SOM ile Kredi Kartı Dolandırıcılığının Tespiti</p>

<br>

<h3>1. Hakkında</h3> <hr>
<b> Bu depo, Kendiliğinden Örgütlenen Haritalar (SOM) kullanarak kredi kartı dolandırıcılığının tespit edilmesini gösteren bir projeyi içermektedir. 
  Proje, veri kümesindeki desenleri belirlemek ve potansiyel dolandırıcılık faaliyetlerini vurgulamak için denetimsiz öğrenmeyi içermektedir.</b> 

<br>
<br>
<br>

<h3>2. Veri Seti</h3> <hr>
<b>Bu projede Credit_Card_Applications.csv adlı veri kümesi kullanılmıştır. Veri kümesi, kredi kartı başvurularının çeşitli özelliklerini içermektedir. 
  Her satır farklı bir başvuruyu temsil eder ve sütunlar başvuruların farklı özelliklerini temsil eder. Son sütun, başvurunun onaylanıp onaylanmadığını (1) veya reddedildiğini (0) belirtir.</b>

<br>
<br>
<br>

<h3>3. Gereksinimler</h3> <hr>
<b>
  
  * Python 3.x
  * NumPy
  * Matplotlib
  * Pandas
  * MiniSom
   
</b>

<br>

<h3>4. Projeye Genel Bakış</h3> <hr>
<b>
  a. Veri Ön İşleme: <br>
  
   * Veri kümesini yükleyin ve özellikleri (X) hedef değişkenden (y) ayırın. <br>
   * Özellikleri MinMaxScaler kullanarak normalleştirin.

  <br>
  b. SOM'un İnşası ve Eğitilmesi: <br>
   
   * 10x10 boyutunda bir SOM ağı başlatın. <br>
   * SOM'u normalleştirilmiş verilerle eğitin.

  <br>
  c. Sonuçların Görselleştirilmesi: <br>

   * SOM mesafe haritasını görselleştirin. <br>
   * Her bir veri noktasını SOM haritasında belirli işaretler ve renklerle gösterin.

 <br>
 d. Dolandırıcılık Tespiti: <br>

  * Kazanan harita hücrelerine göre dolandırıcılıkları belirleyin. <br>
  * Tespit edilen dolandırıcılıkları ters normalleştirin.
  
</b>

<br>
<br>


<h3>5. Katkıda Bulunma</h3> <hr>
<b>Bu projeye katkıda bulunmak istiyorsanız, bir çekme isteği (pull request) açabilirsiniz. </b>













