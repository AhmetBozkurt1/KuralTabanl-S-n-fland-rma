# Rule-Based-Customer-Classification

☞ Bu proje, bir tatil sitesinin sahip olduğu veri seti üzerinden çeşitli analizler,müşteri segmantasyonu ve en sonunda yapılan işlemler sonucunda gelecek olan müşteriden ortalama bir getiri tahmini hesaplaması yapar.

## İş Problemi
☞ Tatil sitesinin yaptığı satışların bazı özelliklerini kullanarak seviye tabanlı (level based) yeni satış tanımları oluşturmak ve bu yeni satış tanımlarına göre segmentler oluşturup bu segmentlere göre yeni gelebilecek müşterilerin şirkete ortalama ne kadar kazandırabileceğini tahmin etmek istemektedir.

**Örneğin**:
Antalya’dan Herşey Dahil bir otele yoğun bir dönemde gitmek isteyen bir müşterinin ortalama ne kadar kazandırabileceği belirlenmek isteniyor.

## Veri Seti Hikayesi
☞ Veri seti tatil sitesinin yaptığı satışların fiyatlarını ve bu satışlara ait bilgiler içermektedir. Veri seti her satış işleminde oluşan kayıtlardan meydana gelmektedir. Bunun anlamı tablo tekilleştirilmemiştir. Diğer bir ifade ile müşteri birden fazla alışveriş yapmış olabilir.

## Değişkenler
**SaleId**: Satış id <br/>
**SaleDate**: Satış Tarihi <br/>
**CheckInDate**: Müşterinin otele giriş tarihi <br/>
**Price**: Satış için ödenen fiyat <br/>
**ConceptName**: Otel konsept bilgisi <br/>
**SaleCityName**: Otelin bulunduğu şehir bilgisi <br/>
**CınDay**: Müşterinin otele giriş günü <br/>
**SaleCheckInDayDiff**: Check in ile giriş tarihi gün farkı <br/>
**Season**: Otele giriş tarihindeki sezon bilgisi

## Kurulum
Projeyi yerel makinenizde çalıştırmak için şu adımları izleyebilirsiniz:<br/>
  - GitHub'dan projeyi klonlayın.
  - Projeyi içeren dizine gidin ve terminalde `conda env create -f environment.yaml` komutunu çalıştırarak gerekli bağımlılıkları yükleyin.
  - Projeyi bir Python IDE'sinde veya Jupyter Notebook'ta açın.

