# cilt.ai

Mobil Telefon ile Çekilmiş Resimlerle Yapay Zeka Destekli Cilt
Analizi Uygulaması Geliştirme Makalesi
Kerem Karayız UID/120522 kerem.fyi
1. Giriş: Mobil Cilt Analizinde Yapay Zekanın Yükselişi
Mobil sağlık uygulamalarının artan yaygınlığı günümüzde dikkat çekmektedir. Özellikle
sağlık ve güzellik alanlarında yapay zeka (YZ) destekli tanı araçlarına olan ilgi giderek
artmaktadır. Mobil telefon kameralarıyla çekilen görüntüler kullanılarak YZ tabanlı cilt
analizi yapabilen bir uygulama geliştirmek, bu alanda umut vadeden bir yenilik olarak
ortaya çıkmaktadır.
1 Bu tür bir uygulama, kullanıcılara erken teşhis, kişiselleştirilmiş cilt
bakımı önerileri ve kolaylık gibi çeşitli avantajlar sunma potansiyeline sahiptir. Aynı
zamanda sağlık profesyonelleri için de ön değerlendirme ve hasta takibi gibi alanlarda
değer yaratabilir.
3 Bu rapor, söz konusu uygulamanın geliştirilmesi için izlenmesi
gereken adımları detaylı bir şekilde inceleyecektir.
Mobil cihazların yüksek kaliteli kameralarla donatılması ve YZ ile makine öğrenimi
alanlarındaki ilerlemeler, sostike mobil cilt analizi araçlarının geliştirilmesi için uygun
bir zemin oluşturmaktadır. Bu eğilim, tüketicilerin proaktif sağlık yönetimi ve
kişiselleştirilmiş güzellik çözümlerine olan artan ilgisiyle daha da güçlenmektedir.
Yüksek çözünürlüklü mobil kameralar, analiz için yeterli görüntü detayını yakalamayı
mümkün kılmaktadır. YZ algoritmaları, özellikle tıbbi görüntüleme alanında, görüntü
tanıma görevlerinde giderek daha doğru hale gelmektedir. Tüketiciler, sağlık ve zindelik
için mobil uygulamaları kullanma konusunda daha rahat hale gelmiştir. Bu nedenle, bu
faktörlerin birleşimi önemli bir fırsat sunmaktadır.
Ancak, bu potansiyel önemli olmakla birlikte, böyle bir uygulamanın geliştirilmesi, tıbbi
verilerle ilgili teknik zorlukların, düzenleyici gerekliliklerin ve etik sonuçların dikkatli bir
şekilde ele alınmasını gerektirmektedir. Cilt analizi, özellikle potansiyel tıbbi durumlar
için, sağlık alanına girmektedir. Sağlık uygulamaları katı düzenlemelere tabidir (örneğin,
GDPR, HIPAA). YZ modellerinin doğruluğunu ve güvenilirliğini sağlamak, yanlış teşhisi
önlemek ve kullanıcı güvenini korumak için hayati önem taşımaktadır.
2. Uygulama Gereksinimlerini Anlama: Kapsam ve İşlevselliği Tanımlama
Uygulamanın temel işlevleri arasında mobil telefon kamerası veya galeriden görüntü
yakalama ve işleme yer almalıdır. Ardından, YZ destekli analiz ile görüntüdeki cilt
durumları belirlenmeli ve akne, kırışıklıklar, lekeler, benler gibi belirli cilt sorunları
tanımlanmalıdır. Uygulama, belirli durumlar (örneğin, cilt kanseri) için potansiyel risk
değerlendirmesi sunabilir ve analiz sonuçlarına göre kişiselleştirilmiş cilt bakımı
önerilerinde bulunmalıdır. Ayrıca, görüntü geçmişi aracılığıyla cilt değişikliklerinin
zaman içinde takibi de mümkün olmalıdır.
3
Uygulamanın hedef kullanıcı grupları genel tüketiciler, cilt bakımı profesyonelleri ve tıp
uzmanları olabilir. Uygulamanın özellikleri ve tasarımı her grubun özel ihtiyaçlarına göre
şekillendirilebilir.
3 Cilt analizinde doğruluk, özellikle uygulama herhangi bir risk
değerlendirmesi sunmayı amaçlıyorsa, büyük önem taşımaktadır. YZ'nin sınırlamaları ve
profesyonel tıbbi tavsiye konusunda uyarıların gerekliliği de göz önünde
bulundurulmalıdır.
6 Mobil kullanıcılar için kullanıcı dostu ve sezgisel bir arayüz
gerekliliği vurgulanmalıdır. Görüntü yakalama kolaylığı, analiz sonuçlarının netliği ve
erişilebilirlik gibi hususlar dikkate alınmalıdır.
Uygulamanın işlevselliği farklı kullanıcı gruplarına göre kademelendirilebilir. Örneğin,
tüketiciler için temel analizler sunulurken, cilt bakımı uzmanları ve tıp pratisyenleri için
profesyonel iş akışlarına entegrasyon potansiyeli olan daha ayrıntılı özellikler
sunulabilir. Yüksek doğruluk hedeenirken, YZ'nin yetenekleri ve sınırlamaları hakkında
şeaık ve açık sorumluluk reddi beyanları, sorumlu dağıtım ve kullanıcı güveni için
esastır. YZ'nin sağlık alanında profesyonel tıbbi tavsiyenin yerini almadığı açıkça
belirtilmelidir. Uygulamanın ön değerlendirme ve bilgi aracı olarak rolünü net bir
şekilde iletmek, kullanıcı beklentilerini yönetmek ve potansiyel zararları önlemek için
hayati önem taşır.
3. Temel Teknik Bileşenler: Veri, YZ Modelleri ve Mobil Entegrasyon
3.1. Veri Toplama ve Ön İşleme
YZ modelini eğitmek için çeşitli cilt durumlarına ait karşılık gelen etiketlere sahip geniş
ve çeşitli bir görüntü veri kümesine ihtiyaç vardır. ISIC Archive, HAM10000 ve Dermnet
gibi kamuya açık veri kümeleri kullanılabilir. Farklı cilt tipleri, etnik kökenler ve durumlar
açısından veri çeşitliliğinin sağlanması, farklı kullanıcı demograleri arasında adil ve
doğru analiz için önemlidir.
1 Mobil telefon kameralarından kaynaklanan görüntü
kalitesindeki farklılıklar nedeniyle görüntü yeniden boyutlandırma, normalleştirme,
artırma gibi gerekli adımlar uygulanmalıdır.
19 Eğitim verilerindeki cilt durumlarının doğru
ve tutarlı bir şekilde etiketlenmesi, potansiyel olarak uzman dermatolojik girdisi
gerektirir.
1
Veri kümesi seçimi, uygulamanın doğruluğunu ve genellenebilirliğini önemli ölçüde
etkiler. Çeşitli, yüksek kaliteli veri kümelerinin bir kombinasyonunu kullanmak ve
potansiyel olarak yeni toplanan, anonimleştirilmiş kullanıcı verileriyle bunları artırmak,
daha sağlam bir model oluşturabilir. YZ modelleri, eğitildikleri verilerden öğrenir. Yanlı
veya sınırlı bir veri kümesi, yanlı veya sınırlı bir modelle sonuçlanır. Bu nedenle, eğitim
verilerinin dikkatli seçimi ve hazırlanması kritik öneme sahiptir. Ön işleme adımları, YZ
modelinin tutarlı ve standartlaştırılmış girdi almasını sağlayarak öğrenmesini ve
performansını iyileştirmesini iyileştirmek için çok önemlidir. Mobil telefon görüntü
kalitesindeki (aydınlatma, açı, odak) farklılıkların ele alınması gerekir. Ön işleme, bu
farklılıkların etkilerini azaltmaya ve modelin ilgili özelliklere odaklanmasını sağlamaya
yardımcı olur.
3.2. YZ Model Geliştirme
Görüntü sınıandırma görevleri için ResNet, Inception, EcientNet gibi Evrişimsel Sinir
Ağları (CNN'ler) gibi uygun derin öğrenme modelleri kullanılabilir. Vizyon
Dönüştürücüler (ViT'ler) alternatif bir mimari olarak düşünülebilir.
2 Hazırlanan veri
kümesi kullanılarak seçilen modelin eğitilmesi, transfer öğrenimi, hiperparametre
ayarlaması ve sınıf dengesizliğinin ele alınması gibi kavramları içerir.
2 Hızı ve gizliliği
artırmak için TensorFlow Lite veya Core ML gibi çerçeveler kullanılarak YZ modelinin
doğrudan mobil cihazda (uç YZ) çalıştırılması olasılığı değerlendirilebilir. Alternatif
olarak, görüntüler analiz için bir sunucuya gönderildiği bulut tabanlı bir yaklaşım da
düşünülebilir. Uç YZ kullanılıyorsa, sınırlı hesaplama kaynaklarına sahip mobil cihazlar
için modeli optimize etme teknikleri (örneğin, nicemleme, budama) açıklanmalıdır.
21
Uç YZ ve bulut tabanlı YZ arasındaki seçim, modelin karmaşıklığı, gerçek zamanlı analiz
ihtiyacı, kullanıcı gizliliği endişeleri ve hedef mobil cihazların hesaplama yetenekleri gibi
faktörlere bağlıdır. Uç YZ, verilerin cihazdan ayrılmaması nedeniyle daha hızlı işleme ve
gelişmiş gizlilik gibi avantajlar sunar. Ancak, optimize edilmiş ve potansiyel olarak daha
az karmaşık modeller gerektirir. Bulut tabanlı YZ, daha karmaşık modellere izin verir,
ancak gecikme ve veri aktarım gereksinimlerini beraberinde getirir. Geniş veri kümeleri
üzerinde önceden eğitilmiş modelleri (ImageNet gibi) kullanmak ve bunları cilt
görüntüsü verileri üzerinde ince ayar yapmak olan transfer öğrenimi, gereken veri
miktarını ve eğitim süresini önemli ölçüde azaltarak daha iyi performansa yol açabilir.
Derin öğrenme modellerini sıfırdan eğitmek büyük miktarda veri ve hesaplama kaynağı
gerektirir. Transfer öğrenimi, modellerin ilgili görevlerde öğrendiği özellikleri kullanarak
süreci daha verimli hale getirir.
3.3. Mobil Uygulama Entegrasyonu
Hedef mobil plaorm(lar)ı seçme konusunda dikkat edilmesi gerekenler tartışılmalıdır
(iOS ve/veya Android). Eğitilmiş YZ modelinin (uç veya bulut tabanlı) plaorma özgü
SDK'lar ve API'ler kullanılarak mobil uygulamaya nasıl entegre edileceği açıklanmalıdır.
Uç YZ için Core ML (iOS için) ve TensorFlow Lite (Android için) kullanımı tartışılmalıdır.
Bulut YZ için, YZ modelini barındıran bir arka uç sunucusuyla iletişim kurmak için REST
API'lerinin kullanımı tartışılmalıdır.
31 Görüntü analizi için mobil telefonun kamerasına
nasıl erişileceği açıklanmalıdır. iOS ve Android'de kamera işlevselliği için kütüphaneler
ve API'ler belirtilmelidir.
38 Görüntü yakalamaya, analiz sonuçlarını görüntülemeye ve
öneriler sunmaya olanak tanıyan kullanıcı arayüzünün geliştirilmesi tartışılmalıdır.
Fluer veya React Native gibi çapraz plaorm geliştirme çerçeveleri, uygulamanın hem
iOS hem de Android için eş zamanlı olarak geliştirilmesi için düşünülebilir, bu da
potansiyel olarak geliştirme süresinden ve kaynaklarından tasarruf sağlayabilir.
39 Bu
SDK'lar, makine öğrenimi modellerini mobil uygulamalara entegre etmenin bazı
karmaşıklıklarını soyutlayan üst düzey API'ler sağlar.
4. Detaylı Geliştirme Yol Haritası: Adım Adım Kılavuz
Geliştirme yol haritası, pazar araştırması ve rakip analizi
3
ile başlamalıdır. Ardından,
belirli uygulama özellikleri ve hedef kitle tanımlanmalıdır. UI/UX tasarımı için tel
çerçeveler ve taslaklar oluşturulmalıdır. Teknik zibilite çalışması ve plaorm seçimi
yapılmalıdır. YZ model geliştirme ve eğitimi aşamasında uygun cilt görüntü veri
kümeleri seçilmeli ve edinilmelidir.
1 Veri ön işleme, temizleme ve etiketleme adımları
gerçekleştirilmelidir. YZ model mimarisi seçilmeli ve uygulanmalıdır.
2 Model, uygun
teknikler kullanılarak eğitilmelidir.
2 Model performansı, ilgili metrikler kullanılarak
değerlendirilmelidir.
79 Model, hedef dağıtım (uç veya bulut) için optimize edilmeli ve
sıkıştırılmalıdır.
31 Mobil uygulama geliştirme aşamasında, seçilen plaorm(lar) için
geliştirme ortamı kurulmalıdır. Tasarımlara göre UI ve UX uygulanmalıdır. Kamera
işlevselliği entegre edilmelidir.
38 YZ modeli entegre edilmelidir.
31 Kullanıcı geçmişi ve
tercihleri için veri depolama uygulanmalıdır. Test ve doğrulama aşamasında, çeşitli
cihazlarda ve senaryolarda kapsamlı testler yapılmalıdır. YZ analizinin doğruluğu ve
güvenilirliği doğrulanmalıdır.
84 Kullanıcı kabul testi (UAT) gerçekleştirilmelidir. Dağıtım
ve bakım aşamasında, uygulama uygulama mağazalarında yayınlanmaya
hazırlanmalıdır. Performans ve hata takibi için izleme ve günlük kaydı uygulanmalıdır.
Yeni verilerle sürekli bakım, güncellemeler ve potansiyel model yeniden eğitimi
planlanmalıdır.
Aşamalı bir yaklaşım, yinelemeli geliştirmeye olanak tanır; her aşama bir önceki üzerine
inşa edilir ve potansiyel sorunların erken tanımlanmasını ve çözülmesini sağlar.
Karmaşık geliştirme sürecini her biri net hedeeri ve çıktıları olan yönetilebilir
aşamalara ayırmak, organizasyonu iyileştirir ve proje başarısızlığı riskini azaltır.
Geliştirme yaşam döngüsü boyunca sürekli test ve doğrulama, özellikle sağlıkla ilgili bir
uygulama için, uygulamanın gerekli doğruluk ve güvenilirlik standartlarını karşılamasını
sağlamak için çok önemlidir. Erken ve sık test, büyük sorunlar haline gelmeden hataları
ve performans sorunlarını belirlemeye yardımcı olur. Doğrulama, YZ modelinin gerçek
dünya senaryolarında beklendiği gibi performans gösterdiğini garanti eder.
5. Teknoloji Yığını ve Plaorm Seçimleri: Doğru Araçları ve Altyapıyı Seçme
Mobil geliştirme için native geliştirme (iOS için Swi, Android için Kotlin/Java) veya
çapraz plaorm çerçeveleri (Fluer, React Native) kullanılabilir.
39 YZ model geliştirme
ve eğitimi için Python, derin öğrenme çerçeveleri (TensorFlow, PyTorch) ve bulut
plaormları (Google Cloud AI Plaorm, Amazon SageMaker, Azure Machine Learning)
tercih edilebilir.
40 Uç YZ entegrasyonu için Core ML (iOS için)
28 ve TensorFlow Lite
(Android için)
21 kullanılabilir. Bulut YZ kullanılıyorsa, arka uç altyapısı için bulut
sağlayıcıları (AWS, Google Cloud, Azure), sunucusuz işlevler (AWS Lambda, Google
Cloud Functions, Azure Functions) ve API geliştirme çerçeveleri (Flask, Django,
Node.js) düşünülebilir.
Teknoloji yığını seçimi, geliştirme ekibinin uzmanlığı, proje gereksinimleri (performans,
ölçeklenebilirlik) ve bütçe ile uyumlu olmalıdır. Farklı teknolojilerin farklı güçlü ve zayıf
yönleri vardır. Doğru araçları seçmek, geliştirme sürecini ve nihai ürünü önemli ölçüde
etkileyebilir. Bulut sağlayıcılar üzerindeki yönetilen YZ plaormlarının kullanılması,
karmaşık YZ modellerinin eğitilmesi ve dağıtılması sürecini basitleştirerek
ölçeklenebilirlik ve maliyet etkinliği sunabilir. Bulut YZ plaormları, makine öğrenimi için
önceden yapılandırılmış ortamlar, araçlar ve altyapı sağlayarak bu kaynakları manuel
olarak yönetme yükünü azaltır.
6. Veri Gizliliği ve Uyumluluğu: Yasal ve Etik Standartları Sağlama
Avrupa Birliği kullanıcılarını hedeiyorsanız GDPR ve ABD'deki hastaların Korunan
Sağlık Bilgilerini (PHI) ele alıyorsanız HIPAA gibi veri gizliliği düzenlemelerine uyumun
önemi tartışılmalıdır.
55 Görüntüler dahil olmak üzere herhangi bir kişisel veya sağlıkla
ilgili verinin toplanması ve işlenmesi için açık kullanıcı onayı almanın gerekliliği
açıklanmalıdır. Veri minimizasyonu ve amaç sınırlaması ilkeleri vurgulanmalıdır.
61
Kullanıcı verilerini yetkisiz erişime, ihlallere ve kötüye kullanıma karşı korumak için güçlü
güvenlik önlemlerinin uygulanması, hem dinlenirken hem de aktarım sırasında
şifreleme dahil olmak üzere tartışılmalıdır.
55 Model iyileştirme veya araştırma için
kullanıcı tarafından sağlanan görüntüler kullanılıyorsa, kullanıcı gizliliğini korumak için
verileri anonimleştirme veya kimliksizleştirme teknikleri (örneğin, meta verileri kaldırma,
tanımlayıcı özellikleri maskeleme) açıklanmalıdır.
65 Kullanıcılara veri işleme uygulamaları
hakkında bilgi veren açık ve kapsamlı gizlilik politikaları ve hizmet şartlarının gerekliliği
vurgulanmalıdır.
69 Uygulama, bir kapsanan kuruluş adına PHI'yi ele alacaksa, bir İş
Ortağı Anlaşması (BAA) gereklilikleri tartışılmalıdır.
59
Veri gizliliği düzenlemelerine uyum yalnızca yasal bir gereklilik değil, aynı zamanda
kullanıcı güvenini oluşturmak ve uygulamanın etik kullanımını sağlamak için de çok
önemlidir. Kullanıcılar, özellikle sağlık verileri söz konusu olduğunda, gizlilikleri
konusunda giderek daha fazla endişe duymaktadır. Düzenlemelere uymak ve güçlü
gizlilik uygulamalarını uygulamak, uygulamanın itibarını ve kullanıcı benimsemesini
artırabilir. Geliştirmenin başından itibaren gizlilik tasarımı ilkelerini uygulamak, gizlilik
önlemlerini daha sonra eklemeye çalışmaktan daha etkilidir. Veri toplama, depolama ve
işleme dahil olmak üzere geliştirme sürecinin her aşamasında gizlilik sonuçlarını
dikkate almak, daha güvenli ve uyumlu bir uygulama oluşturmaya yardımcı olur.
7. Temel Zorluklar ve Azaltma Stratejileri: Geliştirmedeki Potansiyel Engelleri Ele
Alma
YZ modelini eğitmek için yeterince büyük ve çeşitli bir veri kümesi elde etmek zor
olabilir. Verilerdeki önyargı, belirli kullanıcı grupları için yanlış veya adaletsiz analizlere
yol açabilir. Azaltma stratejileri arasında kamuya açık veri kümelerinden yararlanmak,
veri artırma tekniklerini keşfetmek ve veri toplama için işbirliklerini düşünmek yer alır.
Cilt tipleri ve etnik kökenler açısından veri çeşitliliğine öncelik verilmelidir.
12 Mobil
telefon görüntülerinden cilt durumu analizinde yüksek doğruluk elde etmek, görüntü
kalitesindeki farklılıklar ve bazı cilt durumlarının ince yapısı nedeniyle teknik olarak
zorlayıcı olabilir. Azaltma stratejileri arasında son teknoloji derin öğrenme modellerini
kullanmak, transfer öğrenimini kullanmak, modelleri titizlikle ince ayarlamak ve sağlam
doğrulama stratejileri uygulamak yer alır. YZ analizinin sınırlamaları hakkında açık
sorumluluk reddi beyanları sunulmalıdır.
22 Sınırlı hesaplama kaynaklarına sahip mobil
cihazlarda karmaşık YZ modellerini çalıştırmak performansı (hız, pil ömrü) etkileyebilir.
Azaltma stratejileri arasında nicemleme ve budama gibi teknikler kullanarak modelleri
uç cihazlar için optimize etmek yer alır. Daha basit modelleri uç dağıtım için düşünmek
veya karmaşık analizleri buluta yüklemek de bir seçenektir.
31 Veri gizliliği ve sağlık
düzenlemelerinin (GDPR, HIPAA) karmaşık ortamında gezinmek zorlayıcı olabilir ve
ayrıntılara dikkat gerektirir. Azaltma stratejileri arasında hukuk danışmanlığı almak ve
veri gizliliği ve sağlık uyumluluğu konusunda uzmanlara danışmak yer alır. En başından
itibaren sağlam güvenlik ve gizlilik önlemleri uygulanmalıdır.
55 YZ destekli bir tanı
aracına kullanıcı güveni kazanmak ve benimsemeyi teşvik etmek zor olabilir, özellikle
sağlık alanında. Azaltma stratejileri arasında YZ'nin yetenekleri ve sınırlamaları
hakkında şeaık sağlamak yer alır. Kullanıcı dostu bir arayüz ve net, anlaşılır sonuçlar
sunulmalıdır. Uygulamanın profesyonel tıbbi tavsiyenin yerine geçmediği
vurgulanmalıdır.
73
Zorlukları proaktif bir şekilde ele almak, dikkatli planlama, sağlam teknik uygulama ve
etik ve düzenleyici hususlara güçlü bir odaklanma, uygulamanın başarılı bir şekilde
geliştirilmesi ve dağıtılması için çok önemlidir. Potansiyel engelleri geliştirme sürecinin
başlarında belirlemek, azaltma stratejilerinin uygulanmasına olanak tanır, gecikme
riskini azaltır ve daha sağlam bir nihai ürün sağlar.
8. Gelecek Eğilimler ve Potansiyel Geliştirmeler: Uygulamanın Evrimini Keşfetme
Sürekli cilt izleme ve veri toplama için giyilebilir cihazlarla entegrasyon olasılığı
keşfedilebilir.
74 Görüntü verilerini kullanıcı girdisi veya çevresel veriler gibi diğer
bilgilerle birleştiren çok modlu analiz gibi daha gelişmiş YZ tekniklerini dahil etmek
düşünülebilir. Veri gizliliğini korurken işbirlikçi model eğitimi için federatif öğrenme
kullanımı araştırılabilir.
75 Uygulamanın analizine dayalı olarak dermatologlarla uzaktan
konsültasyonları kolaylaştırmak için teletıp plaormlarıyla potansiyel entegrasyon
keşfedilebilir.
76 Bireysel cilt analizine ve kullanıcı tercihlerine göre cilt bakımı ürün
önerilerinin doğruluğu ve kişiselleştirilmesi daha da geliştirilebilir.
6 Uygulama, cilt
bakımı tedavilerinin zaman içindeki etkinliğini görüntü analizi yoluyla izlemeye yardımcı
olacak şekilde potansiyel olarak genişletilebilir.
Sağlık alanında YZ hızla gelişiyor ve uygulamanın alaka düzeyini ve değerini korumak
için sürekli yenilik ve adaptasyon anahtar olacaktır. YZ, mobil teknoloji ve dermatoloji
alanlarındaki en son gelişmeleri takip etmek, yeni özelliklerin ve iyileştirmelerin dahil
edilmesine olanak tanıyacak, kullanıcı deneyimini ve uygulamanın yeteneklerini
geliştirecektir.
9. Sonuç: YZ Destekli Mobil Cilt Analizi için İleriye Dönük Yolun Özeti
YZ destekli mobil cilt analizi uygulamalarının potansiyeli yinelenebilir. Geliştirme
sürecinde yer alan temel adımlar ve dikkat edilmesi gerekenler özetlenebilir. YZ, mobil
geliştirme, dermatoloji ve düzenleyici uyumluluk alanlarında uzmanlığı içeren çok
disiplinli bir yaklaşımın önemi vurgulanabilir. Bu teknolojinin geleceği ve sağlık ve
güzellik üzerindeki potansiyel etkisi hakkında ileriye dönük bir bakış açısıyla
sonuçlandırılabilir.
Ekler:
1. Tablo: Kamuya Açık Cilt Görüntüsü Veri Kümelerinin Karşılaştırılması (Bölüm
3.1)
Veri
Kümesi
Adı
Bağlantı Görüntü
Sayısı
Hastalık
Kategor
ileri
Açıklam
a
Detayla
rı
Erişilebi
lirlik
Temel
Güçlü
Yönler
Temel
Sınırlama
lar
ISIC
Arşivi
11 503.955
+
25 Uzman
açıklama
sı
Kamu
açık
Geniş ve
büyüyen
açık kaynak
arşivi
-
HAM100
00
13 10.015 7 Patolojik
doğrula
ma
(%53.3)
ISIC
arşivi
aracılığıy
la kamu
açık
Büyük, çok
kaynaklı
dermatosk
opik
görüntüler
Melanositi
k
lezyonlara
yönelik
önyargı
Dermnet
NZ
10 - - -
10 - -
DDI
14 656 570
benzersi
z hasta
Patolojik
olarak
onaylan
mış,
çeşitli
cilt
tonları
78
adresind
en
indirilebi
lir
Çeşitli cilt
tonlarına
sahip ilk
kamuya
açık,
uzman
küratörlüğü
nde veri
kümesi
Sınırlı
sayıda
görüntü
PAD-UF
ES-20
10 2.298 6 Klinik
görüntül
er, hasta
verileri
16
adresind
en
indirilebi
lir
Akıllı
telefonlard
an
toplanan
klinik
görüntüler
ve hasta
verileri
-
2. Tablo: Cilt Lezyonu Sınıandırması için Değerlendirme Metrikleri (Bölüm 3.2)
Metrik Adı Açıklama Formül Cilt Lezyonu
Analizindeki Önemi
Doğruluk (Accuracy) Toplam örnek sayısı
içinden doğru
sınıandırılan
örneklerin oranı
(Doğru Pozitif +
Doğru Negatif) /
Toplam Örnek Sayısı
Modelin genel
performansını ölçer
Kesinlik (Precision) Pozitif olarak tahmin
edilenlerin ne
kadarının gerçekten
pozitif olduğunu ölçer
Doğru Pozitif / (Doğru
Pozitif + Yanlış Pozitif)
Yanlış pozitieri en
aza indirmek
önemlidir
Duyarlılık
(Sensitivity/Recall)
Gerçek pozitierin ne
kadarının doğru bir
şekilde tanımlandığını
ölçer
Doğru Pozitif / (Doğru
Pozitif + Yanlış
Negatif)
Yanlış negatieri en
aza indirmek
önemlidir
F1-Skoru Kesinlik ve duyarlılığın
harmonik ortalaması
2 * (Kesinlik *
Duyarlılık) / (Kesinlik +
Duyarlılık)
Dengesiz veri
kümelerinde model
performansını
değerlendirmek için
kullanışlıdır
Özgüllük (Specicity) Gerçek negatierin
ne kadarının doğru
bir şekilde
tanımlandığını ölçer
Doğru Negatif /
(Doğru Negatif +
Yanlış Pozitif)
Yanlış pozitieri en
aza indirmek
önemlidir
3. Tablo: Sağlık Uygulamaları için Temel Veri Gizliliği Düzenlemeleri (Bölüm 6)
Düzenleme Adı Coğra Kapsam Uygulamayla İlgili Temel
Gereksinimler
GDPR Avrupa Birliği Açık onay, veri güvenliği, veri
anonimleştirme, veri sahibi
hakları
HIPAA Amerika Birleşik Devletleri Veri şifreleme, erişim
kontrolleri, denetim
mekanizmaları, iş ortağı
anlaşmaları (gerekirse)
Alıntılanan çalışmalar
1. ISIC Skin Image Analysis Workshop @ MICCAI 2023, erişim tarihi Mayıs 13, 2025,
hps://workshop.isic-archive.com/2023/
2. Deep Learning in Dermatology: A Systematic Review of Current Approaches,
Outcomes, and Limitations - PubMed Central, erişim tarihi Mayıs 13, 2025,
hps://pmc.ncbi.nlm.nih.gov/articles/PMC9841357/
3. 10 Best AI Skin Analysis Apps in 2025 - Perfect Corp., erişim tarihi Mayıs 13, 2025,
hps://www.makeupar.com/business/blog/ai-skincare/top-skin-care-analysis-app
4. AI Dermatologist: Skin Scanner on the App Store, erişim tarihi Mayıs 13, 2025,
hps://apps.apple.com/us/app/ai-dermatologist-skin-scanner/id1511472597
5. AI Skin Analysis Tool For Custom Skincare Routine | Cetaphil US, erişim tarihi Mayıs
13, 2025, hps://www.cetaphil.com/us/skin-analysis.html
6. Skin Analysis AI | Skin Analyzer | Free Demo Skin Checker Scan Age & Acne -
Perfect Corp., erişim tarihi Mayıs 13, 2025,
hps://www.perfectcorp.com/business/showcase/skincare/home
7. Skin Genius Personalized Skin Analysis Tool - L'Oréal Paris, erişim tarihi Mayıs 13,
2025, hps://www.lorealparisusa.com/skin-genius-landing-page
8. AI dermatologist: Skin scanner, erişim tarihi Mayıs 13, 2025, hps://ai-derm.com/
9. Dermatology image dataset - DermNet, erişim tarihi Mayıs 13, 2025,
hps://dermnetnz.org/dermatology-image-dataset
10. sfu-mial/awesome-skin-image-analysis-datasets - GitHub, erişim tarihi Mayıs 13,
2025, hps://github.com/sfu-mial/awesome-skin-image-analysis-datasets
11. International Skin Imaging Collaboration: ISIC, erişim tarihi Mayıs 13, 2025,
hps://www.isic-archive.com/
12. Review of 10 Skin Disease Datasets Available for Download - Online AI
Dermatologist, erişim tarihi Mayıs 13, 2025,
hps://skinive.com/skin-disease-datasets/
13. The HAM10000 dataset, a large collection of multi-source dermatoscopic images
of common pigmented skin lesions - PMC - PubMed Central, erişim tarihi Mayıs
13, 2025, hps://pmc.ncbi.nlm.nih.gov/articles/PMC6091241/
14. DDI - Diverse Dermatology Images | Center for Articial Intelligence in Medicine &
Imaging, erişim tarihi Mayıs 13, 2025,
hps://aimi.stanford.edu/datasets/ddi-diverse-dermatology-images
15. [2406.07426] DERM12345: A Large, Multisource Dermatoscopic Skin Lesion
Dataset with 38 Subclasses - arXiv, erişim tarihi Mayıs 13, 2025,
hps://arxiv.org/abs/2406.07426
16. PAD-UFES-20: a skin lesion dataset composed of patient data and clinical images
collected from smartphones, erişim tarihi Mayıs 13, 2025,
hps://data.mendeley.com/datasets/zr7vgbcyr2/1
17. The ISIC 2020 Challenge Dataset - International Skin Imaging Collaboration,
erişim tarihi Mayıs 13, 2025, hps://challenge2020.isic-archive.com/
18. HAM10000 Dataset - Papers With Code, erişim tarihi Mayıs 13, 2025,
hps://paperswithcode.com/dataset/ham10000-1
19. Intelligent skin lesion segmentation using deformable aention Transformer
U‐Net with bidirectional aention mechanism in skin cancer images, erişim tarihi
Mayıs 13, 2025, hps://pmc.ncbi.nlm.nih.gov/articles/PMC11306920/
20. High-Precision Skin Disease Diagnosis through Deep Learning on Dermoscopic
Images, erişim tarihi Mayıs 13, 2025,
hps://pmc.ncbi.nlm.nih.gov/articles/PMC11440112/
21. (PDF) A Skin Type Classication Method Using Mobile Device-Based Deep
Learning Model, erişim tarihi Mayıs 13, 2025,
hps://www.researchgate.net/publication/372504587_A_Skin_Type_Classication
_Method_Using_Mobile_Device-Based_Deep_Learning_Model
22. Recent Advancements and Perspectives in the Diagnosis of Skin Diseases Using
Machine Learning and Deep Learning: A Review - PMC, erişim tarihi Mayıs 13,
2025, hps://pmc.ncbi.nlm.nih.gov/articles/PMC10706240/
23. A review of psoriasis image analysis based on machine learning - Frontiers, erişim
tarihi Mayıs 13, 2025,
hps://www.frontiersin.org/journals/medicine/articles/10.3389/fmed.2024.1414582
/full
24. Skin Lesion Classication Using a Deep Ensemble Model - MDPI, erişim tarihi
Mayıs 13, 2025, hps://www.mdpi.com/2076-3417/14/13/5599
25. Skin Cancer Detection utilizing Deep Learning: Classication of Skin Lesion
Images using a Vision Transformer - arXiv, erişim tarihi Mayıs 13, 2025,
hps://arxiv.org/html/2407.18554v1
26. FairQuantize: Achieving Fairness Through Weight Quantization for Dermatological
Disease Diagnosis - MICCAI, erişim tarihi Mayıs 13, 2025,
hps://papers.miccai.org/miccai-2024/paper/3697_paper.pdf
27. (PDF) Classication of skin lesion using deep convolutional neural network by
applying transfer learning - ResearchGate, erişim tarihi Mayıs 13, 2025,
hps://www.researchgate.net/publication/374165418_Classication_of_skin_lesion
_using_deep_convolutional_neural_network_by_applying_transfer_learning
28. Integrating AI in Mobile Apps: CoreML, TensorFlow Lite, Create ML - Cactus,
erişim tarihi Mayıs 13, 2025,
hps://cactus-now.com/cactus-news/articial-intelligence-mobile-apps/
29. LiteRT overview | Google AI Edge - Gemini API, erişim tarihi Mayıs 13, 2025,
hps://ai.google.dev/edge/litert
30. TensorFlow Lite - Real-Time Computer Vision on Edge Devices - viso.ai, erişim
tarihi Mayıs 13, 2025, hps://viso.ai/edge-ai/tensorow-lite/
31. Guide to Integrate ML in iOS App Development with CoreML - Magicminds, erişim
tarihi Mayıs 13, 2025,
hps://magicminds.io/blogs/guide-to-integrate-ml-in-ios-app-development-with
-coreml/
32. TensorFlow Lite for Edge Devices - Tutorial - YouTube, erişim tarihi Mayıs 13, 2025,
hps://m.youtube.com/watch?v=OJnaBhCixng&pp=ygUII2xpZ2h0dGY%3D
33. Machine Learning - Apple Developer, erişim tarihi Mayıs 13, 2025,
hps://developer.apple.com/machine-learning/
34. Utilise TensorFlow Lite and Core ML for the best AI-powered mobile apps, erişim
tarihi Mayıs 13, 2025,
hps://www.chapter247.com/blog/building-ai-powered-mobile-apps-with-tensor
ow-lite-and-core-ml/
35. Implementing an ML model into an android app with tensorow lite - Stack
Overow, erişim tarihi Mayıs 13, 2025,
hps://stackoverow.com/questions/79415465/implementing-an-ml-model-intoan-android-app-with-tensorow-lite
36. How to Integrate Machine Learning in Android Apps? - LogicRays, erişim tarihi
Mayıs 13, 2025,
hps://www.logicrays.com/blog/how-to-integrate-machine-learning-in-androidapps/
37. Use a TensorFlow Lite model for inference with ML Kit on Android - Firebase,
erişim tarihi Mayıs 13, 2025,
hps://rebase.google.com/docs/ml-kit/android/use-custom-models
38. Image analysis | Android media - Android Developers, erişim tarihi Mayıs 13, 2025,
hps://developer.android.com/media/camera/camerax/analyze
39. Building iOS and Android ML app : r/iOSProgramming - Reddit, erişim tarihi Mayıs
13, 2025,
hps://www.reddit.com/r/iOSProgramming/comments/1d37q2u/building_ios_and_
android_ml_app/
40. App development with AI - Google for Developers, erişim tarihi Mayıs 13, 2025,
hps://developers.google.com/appdev
41. Firebase | Google's Mobile and Web App Development Plaorm, erişim tarihi
Mayıs 13, 2025, hps://rebase.google.com/
42. Google AI Studio, erişim tarihi Mayıs 13, 2025, hps://aistudio.google.com/
43. Experience AI in our products and experimental tools - Google AI, erişim tarihi
Mayıs 13, 2025, hps://ai.google/get-started/products/
44. What is Google Cloud and How is it Used in Mobile App Development? - Hyper
Pixel, erişim tarihi Mayıs 13, 2025,
hps://hyperpixel.co.uk/insights/what-is-google-cloud-and-how-is-it-used-in-m
obile-app-development/
45. Machine Learning Service – Amazon Sagemaker AI - AWS, erişim tarihi Mayıs 13,
2025, hps://aws.amazon.com/sagemaker-ai/
46. Building Generative AI and ML solutions faster with AI apps from AWS partners
using Amazon SageMaker | AWS Machine Learning Blog, erişim tarihi Mayıs 13,
2025,
hps://aws.amazon.com/blogs/machine-learning/building-generative-ai-and-mlsolutions-faster-with-ai-apps-from-aws-partners-using-amazon-sagemaker/
47. Build Generative AI with Amazon SageMaker - AWS, erişim tarihi Mayıs 13, 2025,
hps://aws.amazon.com/awstv/watch/24d20457c/
48. Get models on device using Core ML Converters - WWDC20 - Videos - Apple
Developer, erişim tarihi Mayıs 13, 2025,
hps://developer.apple.com/videos/play/wwdc2020/10153/
49. Core ML - Machine Learning - Apple Developer, erişim tarihi Mayıs 13, 2025,
hps://developer.apple.com/machine-learning/core-ml/
50. integrate ML into iOS Apps _ Day 2 - ingoampt, erişim tarihi Mayıs 13, 2025,
hps://ingoampt.com/whats-some-examples-of-machine-learning-ml-framewor
k-for-using-ml-in-ios-app-development-in-2024/
51. Core ML vs TensorowLite: ML Mobile Frameworks Comparison - Netguru, erişim
tarihi Mayıs 13, 2025,
hps://www.netguru.com/blog/coreml-vs-tensorow-lite-mobile
52. Using TensorFlow Lite and ML Kit to build custom machine learning models for
Android, erişim tarihi Mayıs 13, 2025,
hps://fritz.ai/build-custom-machine-learning-models-for-android/
53. Building a custom machine learning model on Android with Tensorow Lite -
devmio, erişim tarihi Mayıs 13, 2025,
hps://devm.io/machine-learning/android-ml-tensorow-lite-160971-001
54. An awesome list for TensorFlow Lite - Google Dev Library, erişim tarihi Mayıs 13,
2025,
hps://devlibrary.withgoogle.com/products/ml/repos/margaretmz-awesome-tens
orow-lite
55. Benets and Applications of GDPR Healthcare Compliance - Folio3 Digital Health,
erişim tarihi Mayıs 13, 2025,
hps://digitalhealth.folio3.com/blog/gdpr-healthcare-compliance/
56. GDPR in Healthcare: Compliance Guide, erişim tarihi Mayıs 13, 2025,
hps://www.gdprregister.eu/gdpr/healthcare-sector-gdpr/
57. HIPAA-Ready Apps: Navigating Compliance for Healthcare Solutions - NEKLO,
erişim tarihi Mayıs 13, 2025, hps://neklo.com/blog/hipaa-compliant-apps
58. 4 Steps to Make Your App HIPAA Compliant - Cprime, erişim tarihi Mayıs 13, 2025,
hps://www.cprime.com/resources/blog/4-steps-to-make-your-app-hipaa-com
pliant/
59. HIPAA Compliance for Medical Soware Applications, erişim tarihi Mayıs 13, 2025,
hps://www.hipaajournal.com/hipaa-compliance-for-medical-soware-applicati
ons/
60. HIPAA & Health Apps | HHS.gov, erişim tarihi Mayıs 13, 2025,
hps://www.hhs.gov/hipaa/for-professionals/special-topics/health-apps/index.ht
ml
61. GDPR Compliance for Apps - Privacy Policies, erişim tarihi Mayıs 13, 2025,
hps://www.privacypolicies.com/blog/gdpr-compliance-apps/
62. Understanding data privacy regulations for healthcare apps - Dogtown Media,
erişim tarihi Mayıs 13, 2025,
hps://www.dogtownmedia.com/understanding-data-privacy-regulations-for-he
althcare-apps/
63. GDPR and HIPAA compliance for health applications - Chino.io, erişim tarihi Mayıs
13, 2025,
hps://www.chino.io/compliance/gdpr-hipaa-health-application-compliance
64. HIPAA Compliant App Development: Best Practices & Checklist - Imaginovation,
erişim tarihi Mayıs 13, 2025,
hps://imaginovation.net/blog/hipaa-compliant-app-development/
65. Deidentifying and anonymizing healthcare data - Enlitic, erişim tarihi Mayıs 13,
2025, hps://enlitic.com/blogs/deidentifying-and-anonymizing-healthcare-data/
66. Data Masking and Data Anonymization for AI in Healthcare - iTech India, erişim
tarihi Mayıs 13, 2025,
hps://itechindia.co/us/blog/data-masking-and-data-anonymization-for-healthca
re-ai/
67. Use and Understanding of Anonymization and De-Identication in the Biomedical
Literature: Scoping Review - PMC - PubMed Central, erişim tarihi Mayıs 13, 2025,
hps://pmc.ncbi.nlm.nih.gov/articles/PMC6658290/
68. Algorithms to anonymize structured medical and healthcare data: A systematic
review - PMC, erişim tarihi Mayıs 13, 2025,
hps://pmc.ncbi.nlm.nih.gov/articles/PMC9815524/
69. GDPR Compliance for Digital Health Apps - Taylor Wessing, erişim tarihi Mayıs 13,
2025,
hps://www.taylorwessing.com/en/insights-and-events/insights/2021/04/dsgvo-c
ompliance-bei-digital-health-apps
70. HIPAA compliance when using mobile apps with your patients - Paubox, erişim
tarihi Mayıs 13, 2025,
hps://www.paubox.com/blog/hipaa-compliance-when-using-mobile-apps-with
-your-patients
71. Bias in articial intelligence for medical imaging: fundamentals, detection,
avoidance, mitigation, challenges, ethics, and prospects - Diagnostic and
Interventional Radiology, erişim tarihi Mayıs 13, 2025,
hps://www.dirjournal.org/articles/bias-in-articial-intelligence-for-medical-imagi
ng-fundamentals-detection-avoidance-mitigation-challenges-ethics-and-prosp
ects/doi/dir.2024.242854
72. GDPR compliance for Health-Tech and eHealth companies - TechGDPR, erişim
tarihi Mayıs 13, 2025,
hps://techgdpr.com/industries/gdpr-compliance-for-health-tech-and-ehealth-c
ompanies/
73. Assessment of Patient Perceptions of Articial Intelligence Use In Dermatology: A
Cross-Sectional Survey - DigitalCommons@TMC, erişim tarihi Mayıs 13, 2025,
hps://digitalcommons.library.tmc.edu/cgi/viewcontent.cgi?article=3395&context
=uthmed_docs
74. How does edge AI improve healthcare applications? - Milvus, erişim tarihi Mayıs
13, 2025,
hps://milvus.io/ai-quick-reference/how-does-edge-ai-improve-healthcare-appli
cations
75. Federated Learning for Medical Image Analysis: A Survey - arXiv, erişim tarihi
Mayıs 13, 2025, hps://arxiv.org/html/2306.05980v4
76. Articial intelligence in dermatology - DermNet, erişim tarihi Mayıs 13, 2025,
hps://dermnetnz.org/topics/articial-intelligence
77. Skin Cancer MNIST: HAM10000 | Kaggle, erişim tarihi Mayıs 13, 2025,
hps://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000
78. Diverse Dermatology Images, erişim tarihi Mayıs 13, 2025,
hps://ddi-dataset.github.io/
79. Skin Lesion Classication and Detection Using Machine Learning Techniques: A
Systematic Review - PMC, erişim tarihi Mayıs 13, 2025,
hps://pmc.ncbi.nlm.nih.gov/articles/PMC10572538/
80. Skin Lesion Classication and Detection Using Machine Learning Techniques: A
Systematic Review - PubMed, erişim tarihi Mayıs 13, 2025,
hps://pubmed.ncbi.nlm.nih.gov/37835889/
81. Accurate Skin Lesion Classication Using Multimodal Learning on the HAM10000
Dataset, erişim tarihi Mayıs 13, 2025,
hps://www.medrxiv.org/content/10.1101/2024.05.30.24308213v3.full-text
82. Accurate Skin Lesion Classication Using Multimodal Learning on the HAM10000
Dataset - medRxiv, erişim tarihi Mayıs 13, 2025,
hps://www.medrxiv.org/content/medrxiv/early/2024/05/31/2024.05.30.24308213.
full.pdf
83. Advanced Articial Intelligence Techniques for Comprehensive Dermatological
Image Analysis and Diagnosis - MDPI, erişim tarihi Mayıs 13, 2025,
hps://www.mdpi.com/2673-6179/4/4/15
84. Assessment of an Articial Intelligence Model's Capability of Responding to
Queries in the Realm of Integrative Dermatology, erişim tarihi Mayıs 13, 2025,
hps://www.jintegrativederm.org/article/125936-assessment-of-an-articial-intell
igence-model-s-capability-of-responding-to-queries-in-the-realm-of-integrativ
e-dermatology
85. Evaluation of the Diagnostic Accuracy of an Online Articial Intelligence
Application for Skin Disease Diagnosis - PMC, erişim tarihi Mayıs 13, 2025,
hps://pmc.ncbi.nlm.nih.gov/articles/PMC9234984/
86. DERM performance - Skin Analytics, erişim tarihi Mayıs 13, 2025,
hps://skin-analytics.com/ai-pathways/derm-performance/
87. Articial Intelligence and Its Eect on Dermatologists' Accuracy in Dermoscopic
Melanoma Image Classication: Web-Based Survey Study, erişim tarihi Mayıs 13,
2025, hps://pmc.ncbi.nlm.nih.gov/articles/PMC7519424/
88. New data shows DERM, our AI skin cancer diagnosis tool, could be as accurate as
clinical specialist, erişim tarihi Mayıs 13, 2025,
hps://skin-analytics.com/news/skin-cancer/prospective-study-shows-ai-as-acc
urate-as-clinical-specialist/
# cilt
