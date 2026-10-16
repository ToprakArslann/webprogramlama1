# MDN Web Geliştirme — HTML Öğrenme Rehberi (Türkçe)

> Bu belge, MDN Web Docs'un HTML eğitim serisi içeriklerinin Türkçe çevirisidir.

---


---

# Structuring content with HTML

HTML, herhangi bir web sitesinin içeriğini ve yapısını tanımlayan teknolojidir. Doğru yazıldığında, içeriğin semantik anlamını da makine tarafından okunabilir bir biçimde tanımlamalıdır; bu da erişilebilirlik, arama motoru optimizasyonu ve tarayıcıların içerik için sunduğu yerleşik özelliklerden en iyi şekilde yararlanmak açısından hayati önem taşır. Bu modül, dilin temellerini kapsar; ardından belge yapısı, bağlantılar, listeler, görseller, formlar ve daha fazlası gibi temel alanlara bakar.

## Önkoşullar

Bu modüle başlamadan önce herhangi bir HTML bilgisine ihtiyacınız yoktur; ancak bilgisayar kullanımı ve web'i pasif olarak kullanma konusunda en azından temel bir aşinalığınız olmalıdır. Temel bir çalışma ortamı kurmuş olmalısınız (bkz. Temel yazılım yükleme) ve dosyaları oluşturup yönetmeyi bilmelisiniz (bkz. Dosyalarla çalışma). Bunların ikisi de Web ile başlama tam başlangıç modülümüzün parçalarıdır.

> Not: Bir bilgisayar, tablet veya dosya oluşturamadığınız başka bir cihaz kullanıyorsanız, kodu CodePen veya JSFiddle gibi çevrimiçi bir editörde çalıştırmayı deneyebilirsiniz.

## Eğitimler ve alıştırmalar

### Basic HTML syntax

HTML'in mutlak temellerini kapsar; başlamak için gereken her şeyi sağlar — öğeleri, öznitelikleri ve diğer önemli terimleri tanımlar, bunların dil içinde nerede yer aldığını gösterir. Ayrıca tipik bir HTML sayfasının nasıl yapılandırıldığını ve bir HTML öğesinin nasıl yapılandırıldığını gösterir, dilin diğer önemli temel özelliklerini açıklar. Bu arada, sizi HTML ile biraz oynatarak merakınızı da artırır!

### What's in the head? Web page metadata

Bir HTML belgesinin head bölümü, sayfa tarayıcıda yüklendiğinde görüntülenmeyen kısımdır. Sayfanın `<title>` öğesi, CSS bağlantıları (HTML içeriğinizi CSS ile biçimlendirmek istiyorsanız), özel favicon bağlantıları ve başka metadata (HTML hakkında veri; örneğin yazarı ve belgeyi tanımlayan önemli anahtar kelimeler) gibi bilgiler içerir.

### Headings and paragraphs

HTML'in temel görevlerinden biri, bir tarayıcının bir HTML belgesini geliştiricinin amaçladığı şekilde gösterebilmesi için metne yapı kazandırmaktır. Bu makale, başlıkları ve paragrafları tanımlayarak temel sayfa yapısının nasıl sağlanabileceğini açıklar.

### Emphasis and importance

Önceki makale, HTML'de semantiğin neden önemli olduğuna baktı ve başlıklar ile paragraflara odaklandı. Bu makale, semantik temasını sürdürerek metne vurgu ve önem uygulayan HTML öğelerini inceler (basılı medyadaki italik ve kalın metinle paralel olarak).

### Lists

Listeler hayatın her yerindedir — alışveriş listenizden, her gün evinize gitmek için bilinçaltınızda takip ettiğiniz yön tarifleri listesine, bu eğitimlerde izlediğiniz talimat listelerine kadar! HTML'in farklı liste türlerini tanımlamamıza olanak sağlayan kullanışlı bir öğe kümesine sahip olması sizi şaşırtmayabilir. Web'de üç liste türü vardır: sırasız, sıralı ve açıklama listeleri. Bu ders, farklı türleri nasıl kullanacağınızı gösterir.

### Advanced text features

HTML'de, Emphasis and importance makalesinde yer vermediğimiz metin semantiğini tanımlayan daha birçok öğe vardır. Bu makalede açıklanan öğeler daha az bilinir, ancak yine de bilinmeleri yararlıdır (ve bu, hiçbir şekilde tam bir liste değildir). Burada alıntıları, bilgisayar kodunu ve diğer ilgili metni, alt simge ve üst simgeyi, iletişim bilgilerini ve daha fazlasını işaretlemeyi öğreneceksiniz.

### Marking up a letter Challenge

Hepimiz er ya da geç bir mektup yazmayı öğreniriz; bu, metin biçimlendirme becerilerinizi sınamak için de yararlı bir örnektir. Bu alıştırmada, HTML metin biçimlendirme becerilerinizin yanı sıra bağlantıları ve HTML `<head>` öğesinin doğru kullanımını test etmek için işaretlemeniz gereken bir mektup olacak.

### Structuring documents

Sayfanızın tek tek parçalarını tanımlamanın yanı sıra (örneğin “bir paragraf” ya da “bir görsel”), HTML web sitenizin alanlarını tanımlamak için kullanılan bir dizi blok düzeyi öğeye de sahiptir (örneğin “başlık”, “gezinti menüsü”, “ana içerik sütunu”). Bu makale, temel bir web sitesi yapısının nasıl planlanacağını ve bu yapıyı temsil etmek için HTML'in nasıl yazılacağını inceler.

### Creating links

Bağlantılar (hiper bağlantılar olarak da bilinir) gerçekten önemlidir — Web'i web yapan şey onlardır. Bu makale, bir bağlantı oluşturmak için gereken sözdizimini gösterir ve bağlantı için en iyi uygulamaları tartışır.

### Structuring a page of content Challenge

CSS kullanarak düzenlemeye hazır bir içerik sayfasını yapılandırmak ustalaşılması gereken çok önemli bir beceridir; bu nedenle bu alıştırmada, bir sayfanın sonunda nasıl görünebileceğini düşünme ve bir yerleşim oluşturmak için uygun yapısal semantik öğeleri seçme yeteneğiniz sınanır.

### HTML images

Başlangıçta web sadece metinden ibaretti ve gerçekten oldukça sıkıcıydı. Neyse ki, web sayfalarının içine görselleri (ve diğer daha ilginç içerik türlerini) gömme yeteneği çok geçmeden eklendi. Bu makalede, `<img>` öğesinin temelleri, onu `<figure>` kullanarak altyazılarla açıklama ve CSS background images ile ilişkisi dahil olmak üzere ayrıntılı olarak nasıl kullanılacağına bakacağız.

### HTML video and audio

Artık bir web sayfasına basit görseller eklemeye alıştığımıza göre, bir sonraki adım HTML belgelerinize video ve audio oynatıcıları eklemeye başlamaktır! Bu makalede bunu `<video>` ve `<audio>` öğeleriyle nasıl yapacağımızı inceleyeceğiz; ardından videolarınıza captions/subtitles eklemeye bakarak bitireceğiz.

### Creepy-crawly splash page Challenge

Bu alıştırmada, son birkaç derste tartışılan tekniklerden bazıları konusundaki bilginizi test edeceğiz; böcekler ve diğer sürüngen yaratıklar hakkında bir splash page'e bazı görseller ve video eklemeniz istenecek.

### HTML table basics

Bu makale, HTML tablolarına başlamanızı sağlar; satırlar, hücreler, başlıklar, hücreleri birden çok sütun ve satır boyunca genişletme ve biçimlendirme amacıyla bir sütundaki tüm hücreleri birlikte gruplandırma gibi temel konuları kapsar.

### HTML table accessibility

Bu makalede, captions/summaries, satırları table head, body ve footer bölümlerine gruplandırma ve sütunlar ile satırlar için scope ayarlama gibi daha fazla HTML tablo erişilebilirlik özelliğine bakıyoruz.

### Structuring a planet data table Challenge

Bu alıştırmada, size Güneş Sistemi'mizdeki gezegenler hakkında bazı veriler sunuyoruz. Göreviniz bunları erişilebilir bir HTML tablo halinde yapılandırmaktır.

### Forms and buttons in HTML

HTML formları ve düğmeleri, kullanıcılarla etkileşim kurmak için güçlü araçlardır — çoğunlukla kullanıcılarдан veri toplamak veya onların bir kullanıcı arabirimini kontrol etmesine izin vermek için kullanılırlar. Bu makalede formlar ve düğmelerin temellerine giriş yapıyoruz.

### Debugging HTML

HTML yazmak iyidir, peki bir şey ters giderse ve koddaki hatanın nerede olduğunu bulamazsanız ne olur? Bu makale, HTML'deki hataları bulmanıza ve düzeltmenize yardımcı olabilecek bazı araçları tanıtacaktır.

### Test your skills

Yeterince ilerlediğinizden emin olmak için, en önemli bilgileri koruyup korumadığınızı denetleyen “Test your skills” makalelerini öğretici makalelerin arasına yerleştirilmiş halde bulacaksınız. Hepsini birlikte keşfetmek isterseniz, bunları Test your skills: HTML altında listelenmiş olarak bulabilirsiniz.

## Ek eğitimler

Bu eğitimler öğrenme yolunun bir parçası değildir, ancak yine de ilginçtir — ana Core makalelerini bitirdiğinizde bunları isteğe bağlı olarak çalışılacak genişleme hedefleri olarak düşünebilirsiniz.

### Including vector graphics in HTML

Vektör grafikleri birçok durumda çok kullanışlıdır — dosya boyutları küçüktür ve son derece ölçeklenebilirdir, bu yüzden yakınlaştırıldıklarında veya büyük boyuta büyütüldüklerinde pikselleşmezler. Bu makalede, bunlardan birini web sayfanıza nasıl ekleyeceğinizi göstereceğiz.

### From object to iframe — general embedding technologies

Geliştiriciler genellikle görüntü, video ve audio gibi medyayı web sayfalarına gömme konusunu düşünür. Bu makalede biraz yan bir adım atarak, web sayfalarınıza çok çeşitli içerik türlerini gömmeye olanak tanıyan bazı öğelere bakıyoruz: `<iframe>`, `<embed>` ve `<object>` öğeleri. Bu öğeler, diğer web sayfaları ve PDF dosyaları gibi harici kaynakları gömmeye olanak tanır.

## Ayrıca bkz.

### Learn HTML and CSS, Scrimba MDN learning partner

Scrimba'nın Learn HTML and CSS kursu, beş harika proje oluşturarak ve dağıtarak HTML ve CSS öğretir; dersler ve alıştırmalar etkileşimlidir ve bilgili eğitmenler tarafından sunulur.

### Learn HTML, Codecademy

HTML temellerini öğrenmek için başka yararlı bir kaynak.

### The basics of semantic HTML, Scrimba MDN learning partner

Bu etkileşimli ders, HTML'in yararlı bir açıklamasını sunar ve özellikle semantik yönünün neden önemli olduğuna odaklanır.

## Genel bakış: Temel öğrenme modülleri

Next

Daha iyi bir internet için planınız.


---

# Basic HTML syntax

Bu makalede HTML'in temel taşlarını, terminolojiyi, sözdizimini ve yapıyı ele alıyoruz. Yol boyunca, temel HTML yazmaya aşina olmanız için bazı etkileşimli alıştırmaları tamamlayacaksınız.

## Önkoşullar

Temel yazılımın yüklü olması ve dosyalarla çalışma hakkında temel bilgi.

## Öğrenme çıktıları

- HTML öğesinin anatomisi: öğe, açılış etiketi, içerik, kapanış etiketi, öznitelikler.
- HTML body öğesi ve sayfa içeriği için bir kapsayıcı olarak amacı.
- Void elements nedir ve diğer öğelerden nasıl farklı oldukları.
- HTML belgelerinin en üstünde bir doctype olmasının gerekliliği; bunun özgün amacı ve günümüzde bir tür tarihî kalıntı oluşu.
- HTML'in doğru şekilde iç içe yerleştirilmesi gerektiğini anlamak.

## HTML nedir?

HTML (HyperText Markup Language), web tarayıcılarına ziyaret ettiğiniz web sayfalarını nasıl yapılandıracaklarını söyleyen bir markup language'dir. HTML, içeriğin farklı parçalarını kapsamak, sarmalamak veya işaretlemek için kullandığınız bir dizi öğeden oluşur; böylece onların belirli bir biçimde görünmesini veya davranmasını sağlar. Saran etiketler, içeriği başka bir sayfaya bağlanan bir hyperlink'e dönüştürebilir, kelimeleri italik yapabilir ve benzeri şeyler yapabilir. Örneğin şu metin satırını düşünün:

My cat is very grumpy

Bu metnin bir paragraph olduğunu, onu paragraph ( `<p>` ) etiketleri içine alarak belirtebiliriz:

```html
<p>My cat is very grumpy</p>
```

Ya da bu metnin üst düzey bir heading olduğunu, onu `<h1>` etiketleri içine alarak belirtebiliriz:

```html
<h1>My cat is very grumpy</h1>
```

HTML, `.html` dosya uzantısına sahip HTML documents ya da kısaca documents denen text files içinde yer alır. Daha önce web pages'den söz ederken, bir HTML document web page'in içeriğini barındırır ve yapısını belirtir.

Karşılaşacağınız en yaygın HTML dosyası `index.html`'dir; bu dosya genellikle bir web sitesinin home page içeriğini barındırmak için kullanılır. Bir web sitesinin farklı yerlerinde kendi `index.html` dosyalarına sahip alt klasörler görmek de yaygındır; böylece bir web sitesinin farklı konumlarda birden fazla index file'ı olabilir.

> Not: HTML'de tags büyük/küçük harfe duyarlı değildir. Yani büyük harf veya küçük harf ile yazılabilirler. Örneğin, bir `<title>` tag'i `<title>`, `<TITLE>`, `<Title>`, `<TiTlE>` vb. biçimlerde yazılabilir ve çalışır. Ancak tutarlılık ve okunabilirlik için tüm tag'leri küçük harfle yazmak iyi uygulamadır.

## Bir HTML öğesinin anatomisi

Önceki bölümdeki paragraph öğemizi daha ayrıntılı inceleyelim:

Tam öğemiz şunlardan oluşur:

- Açılış etiketi: Öğenin adından oluşur (bu örnekte paragraph için `p`), açılı ve kapanış parantezleri içine alınır. Bu açılış etiketi, öğenin nerede başladığını veya etkisini göstermeye başladığını işaret eder. Bu örnekte paragraph metninin başlangıcından önce gelir.
- İçerik: Öğenin içeriğidir. Bu örnekte paragraph metni olan "My cat is very grumpy"'dir.
- Kapanış etiketi: Bu, açılış etiketiyle aynıdır; ancak öğe adından önce bir ileri eğik çizgi içerir. Bu, öğenin nerede bittiğini işaret eder. Kapanış etiketini eklememek, başlangıç seviyesindeki kullanıcıların sık yaptığı ve tuhaf sonuçlar doğurabilen bir hatadır.

> Not: HTML tags hakkında etkileşimli bir açıklama için öğrenme ortağımız Scrimba'nın HTML tags MDN learning partner scrim'ine göz atın.

## İlk HTML öğenizi oluşturma

Kendi HTML öğelerinizi yazma konusunda biraz pratik yapalım:

1. Aşağıdaki code block'ta bulunan example'ı düzenlemek için "Play"e tıklayın.
2. Metin satırını `<em>` ve `</em>` etiketleriyle sarın. Öğeyi açmak için açılış etiketini (`<em>`) satırın başına koyun. Öğeyi kapatmak için kapanış etiketini (`</em>`) satırın sonuna koyun. Bunu yapmak, rendered text'i italik text olarak biçimlendirmelidir.
3. İsterseniz daha fazlasını araştırıp text example'a başka HTML öğeleri de uygulamayı deneyin.

Hata yaparsanız, MDN Playground'daki Reset düğmesini kullanarak çalışmanızı temizleyebilirsiniz. Çok takılırsanız, code block'un altındaki solution'a bakabilirsiniz.

```html
This is my text.
```

Click here to show the solution

## Öğelerin iç içe yerleştirilmesi

Öğeler başka öğelerin içine yerleştirilebilir. Buna nesting denir. Eğer kedimizin çok suratsız olduğunu belirtmek isteseydik, `very` kelimesini bir `<strong>` öğesi içine alabilirdik; bu da kelimeye güçlü metin biçimlendirmesi verir:

```html
<p>My cat is <strong>very</strong> grumpy.</p>
```

Bu code block'ta "My cat is very grumpy." metninin tamamı bir paragraph olarak tanımlanır. `very` kelimesi ayrıca güçlü önem taşıyan bir şey olarak tanımlanır.

İç içe yerleştirmenin doğru ve yanlış yolları vardır. Yukarıdaki code block'ta önce `<p>` öğesini açarız, sonra `<strong>` öğesini açarız. Doğru nesting için önce `<strong>` öğesini kapatır, sonra `<p>` öğesini kapatırız.

Aşağıda yanlış nesting örneği vardır:

```html
<p>My cat is <strong>very grumpy.</p></strong>
```

Etiketlerin, birbirlerinin içinde ya da dışında kalacak şekilde açılıp kapanması gerekir. Önceki code block'ta öğeler üst üste bindiği için tarayıcı niyetinizi tahmin etmek zorunda kalır. Bu tür tahminler beklenmedik sonuçlara yol açabilir.

## Void elements

Her öğe açılış etiketi + içerik + kapanış etiketi kalıbını izlemez. Bazı öğeler tek bir etiketten oluşur; bu genellikle belgeye bir şey eklemek/gömmelemek için kullanılır. Bu tür öğelere void elements denir; yani "başka HTML içeriği barındıramayan öğeler".

Örneğin, `<br>` öğesi bir satır metne line break ekler ve bunun birden fazla satıra bölünmesine neden olur:

```html
<p>
This is a single paragraph, but we are going to <br />break it onto two lines.
</p>
```

Bu şu şekilde gösterilir:

This is a single paragraph, but we are going to
break it onto two lines.

> Not: Bazı HTML örneklerinde, void element etiketinin sonunda bir `/` görürsünüz; örneğin `<br />`. Bu farklı bir markup syntax stilidir; yanlış değildir, ancak bu "closing slash" gerekli değildir.

## Öznitelikler

Öğelerin öznitelikleri de olabilir. Öznitelikler şu şekilde görünür:

Öznitelikler, öğenin içeriğinin parçası olmayan ek bilgiler içerir. `class` özniteliği, öğeyi stiller (CSS) veya scripting information (JavaScript) ile hedeflemek için kullanılabilecek tanımlayıcı bir ad sağlar.

Bir özniteliğin şunlara sahip olması gerekir:

- Öğenin adıyla arasında bir boşluk. Bir öğenin birden fazla özniteliği olduğunda, öznitelikler de aralarında boşluk olacak şekilde ayrılmalıdır.
- Eşittir işareti (`=`) ile takip edilen öznitelik adı.
- Açılış ve kapanış tırnak işaretleri içine alınmış bir öznitelik değeri.

## Bir öğeye öznitelik ekleme

Şimdi tekrar sıra sizde. Bu bölümde, sayfada bir image görüntülemek için kullanılan `<img>` öğesini inceleyeceksiniz. `<img>` öğesi şu öznitelikleri alabilir:

- `src`: image'in URL (web address)'ini belirten gerekli bir öznitelik. Örneğin:

  `src="https://mdn.github.io/shared-assets/images/examples/fx-nightly-512.png"`.

- `alt`: image'i göremeyen kişilere açıklamak için bir text description belirtir. Örneğin: `alt="The Firefox Nightly icon"`. Bu öznitelik teknik olarak gerekli değildir, ancak anlam taşıyan tüm images için bir text description sağlamanız gerçekten gerekir (saf dekoratif olanlar hariç).
- `width`: image'in pixel cinsinden genişliğini belirtir. Örneğin: `width="300"`.
- `height`: image'in pixel cinsinden yüksekliğini belirtir. Örneğin: `height="300"`.

Görevi tamamlamak için aşağıdaki adımları izleyin:

1. Aşağıdaki code block'ta bulunan example'ı düzenlemek için "Play"e tıklayın.
2. Çevrimiçi favori bir image bulun, üzerine sağ tıklayın ve Copy Image Link/Address'e basın. Alternatif olarak yukarıdaki image URL'sini kopyalayın.
3. MDN Playground'a geri dönün, `<img>` öğesine `src` özniteliğini ekleyin ve değerini 2. adımdaki URL yapın.
4. `alt` özniteliğini image için uygun bir açıklama olacak şekilde ayarlayın.
5. `width` özniteliğini örneğin `300` gibi bir değere ayarlayın; böylece image'i output panelinde biraz daha iyi görebilirsiniz. Gerekirse değeri ayarlayın.

Hata yaparsanız, MDN Playground'daki Reset düğmesini kullanarak çalışmanızı temizleyebilirsiniz. Çok takılırsanız, code block'un altındaki solution'a bakabilirsiniz.

```html
<img />
```

Click here to show the solution

## Boolean attributes

Bazen HTML özniteliklerinin values olmadan yazıldığını görürsünüz. Bunlara Boolean attributes denir. Bir boolean attribute eklendiğinde, ona atanmış değer ne olursa olsun (hatta hiç değer verilmemiş olsa bile) değeri `true` olur. Bir öznitelik HTML tag'inde yer almıyorsa, değeri `false` olur.

Örneğin, kullanıcıların veri girmesini engellemek için form `<input>` öğelerine atayabileceğiniz `disabled` özniteliğini düşünün. Mesela:

```html
<label for="first-input">This input is disabled</label>

<input id="first-input" type="text" disabled="disabled" />

<br />
```

Kısaltma olarak, `disabled` özniteliğini değer vermeden yazmak da kabul edilebilir:


---

# What's in the head? Web page metadata

Bir HTML belgesinin head bölümü, sayfa tarayıcıda yüklendiğinde görüntülenmeyen kısımdır. Sayfanın `<title>` öğesi, CSS bağlantıları (HTML içeriğinizi CSS ile biçimlendirmeyi seçerseniz), özel favicons bağlantıları ve diğer metadata (HTML hakkında veri; örneğin yazar ve belgeyi tanımlayan önemli anahtar kelimeler) gibi metadata bilgileri içerir.

Web tarayıcıları, HTML belgesini doğru şekilde işlemek için head içinde bulunan bilgileri kullanır. Bu makalede, yukarıdakilerin tümünü ve daha fazlasını ele alacağız; böylece markup ile çalışmak için iyi bir temel kazanmış olacaksınız.

## Önkoşullar

Önceki derste ele alındığı gibi temel HTML aşinalığı.

## Öğrenme çıktıları

- Document character encoding ve title ayarlama.
- Arama motorları için metadata sağlama.
- Tarayıcılar ve mobil platformlarda kullanılacak icons ile bağlama.
- Stylesheets ve script files ile bağlama.
- `<html>` açılış tag'inde `lang` özniteliğini kullanarak belgenin dilini ayarlama gerekliliği.

## HTML head nedir?

Önceki makalede ele aldığımız basit HTML belgesine dönelim:

```html
<!doctype html>

<html lang="en-US">

<head>

<meta charset="utf-8" />

<title>My test page</title>

</head>

<body>

<p>This is my page</p>

</body>

</html>
```

HTML head, `<head>` öğesinin içeriğidir. `<body>` öğesinin içeriğinin aksine (bunlar tarayıcıda yüklendiğinde sayfada görüntülenir), head içeriği sayfada görüntülenmez. Bunun yerine head'in görevi, belge hakkında metadata taşımaktır. Yukarıdaki örnekte head oldukça küçüktür:

```html
<head>

<meta charset="utf-8" />

<title>My test page</title>

</head>
```

Ancak daha büyük sayfalarda head oldukça büyüyebilir. Sevdiğiniz bazı web sitelerine gidip developer tools ile head içeriklerini incelemeyi deneyin. Buradaki amacımız, head içine konabilecek her şeyi göstermek değil; bunun yerine head'e eklemek isteyeceğiniz ana öğeleri kullanmayı öğretmek ve size aşinalık kazandırmaktır. Hadi başlayalım.

## Bir title ekleme

`<title>` öğesini zaten kullandık — bu, belgeye bir title eklemek için kullanılabilir. Ancak bu, body içeriğinize üst düzey bir heading eklemek için kullanılan h1 öğesiyle karıştırılabilir — bu da bazen page title olarak anılır. Fakat bunlar farklı şeylerdir!

h1 öğesi, tarayıcıda yüklendiğinde sayfada görünür — genellikle page content'in title'ını (hikâye başlığı, haber manşeti veya kullanımınıza uygun başka bir şey) işaretlemek için sayfa başına bir kez kullanılmalıdır.

`<title>` öğesi ise tüm HTML document'in title'ını temsil eden metadata'dır (belgenin içeriğini değil).

## Bir example inceleme

1. Bu alıştırmada, GitHub repo'muza gidip `title-example.html` sayfamızın bir kopyasını indirmeniz gerekecek. Bunu yapmak için, ya:
   1. Sayfadaki kodu kopyalayıp kod editörünüzde yeni bir text file içine yapıştırın, sonra uygun bir yere kaydedin.
   2. GitHub sayfasındaki "Raw" düğmesine basın; bu, ham kodun görünmesini sağlar (muhtemelen yeni bir browser tab'da). Ardından tarayıcınızın Save Page As… menüsünü seçin ve dosyayı kaydetmek için uygun bir yer belirleyin.
2. Şimdi dosyayı tarayıcınızda açın. Şuna benzer bir şey görmelisiniz:
3. Artık `<h1>` içeriğinin nerede göründüğü ve `<title>` içeriğinin nerede göründüğü tamamen açık olmalıdır!
4. Ayrıca kodu kod editörünüzde açıp bu öğelerin içeriğini düzenlemeyi, sonra sayfayı tarayıcınızda yenilemeyi de denemelisiniz. Bununla biraz eğlenin.

`<title>` öğesinin içeriği başka şekillerde de kullanılır. Örneğin, sayfayı yer imlerine eklemeyi denerseniz (Bookmarks > Bookmark This Page veya Firefox'ta URL çubuğundaki yıldız simgesi), `<title>` içeriğinin önerilen bookmark name olarak doldurulduğunu görürsünüz.

`<title>` içeriği search results içinde de kullanılır; aşağıda göreceksiniz.

## Metadata: `<meta>` öğesi

Metadata, veriyi tanımlayan veridir ve HTML'nin bir belgeye metadata eklemek için "resmî" bir yolu vardır — `<meta>` öğesi. Elbette bu makalede sözünü ettiğimiz diğer şeyler de metadata olarak düşünülebilir. Sayfanızın `<head>` bölümüne eklenebilecek çok çeşitli `<meta>` öğeleri vardır; ancak bu aşamada hepsini açıklamaya çalışmayacağız, çünkü bu sadece fazla karışık olurdu. Bunun yerine, sıkça görebileceğiniz birkaç şeyi açıklayacağız; böylece fikir edinmiş olacaksınız.

### Belgenizin character encoding'ini belirtme

Yukarıda gördüğümüz örnekte şu satır yer alıyordu:

```html
<meta charset="utf-8" />
```

Bu öğe, belgenin character encoding'ini — yani belgenin kullanmasına izin verilen character set'i — belirtir.

utf-8, hemen her insan dilinden neredeyse her karakteri içeren evrensel bir character set'tir. Bu, web sayfanızın herhangi bir dili gösterebileceği anlamına gelir; bu yüzden oluşturduğunuz her web sayfasında bunu ayarlamak iyi bir fikirdir! Örneğin, sayfanız İngilizce ve Japonca'yı rahatça destekleyebilir:

Eğer character encoding'inizi örneğin ISO-8859-1'e ayarlarsanız (Latin alfabesi için character set), sayfanızın render edilmesi çok bozulmuş görünebilir:

> Not: Bazı tarayıcılar (Chrome gibi) yanlış encoding'leri otomatik olarak düzeltir; bu yüzden hangi tarayıcıyı kullandığınıza bağlı olarak bu sorunu görmeyebilirsiniz. Yine de diğer tarayıcılarda olası sorunları önlemek için sayfanızda yine de `utf-8` encoding'i ayarlamalısınız.

### Character encoding ile deneme yapma

Bunu denemek için, `<title>` bölümünde elde ettiğiniz basit HTML template'e (title-example.html sayfası) geri dönün, meta charset değerini ISO-8859-1 olarak değiştirmeyi ve sayfanıza Japonca eklemeyi deneyin. Kullandığımız kod şu idi:

```html
<p>Japanese example: ご飯が熱い。</p>
```

### Bir yazar ve açıklama ekleme

Birçok `<meta>` öğesi `name` ve `content` özniteliklerini içerir:

- `name`, meta öğesinin türünü; ne tür bilgi içerdiğini belirtir.
- `content`, gerçek meta içeriğini belirtir.

Sayfanıza eklemesi yararlı olan bu tür iki meta öğe, sayfanın yazarını tanımlar ve sayfanın kısa bir açıklamasını sağlar. Bir örneğe bakalım:


---

# Türkçe çeviri

HTML
Başlıklar ve paragraflar
Başlıklar ve paragraflar
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
One of HTML's main jobs is to give text structure so that a tarayıcı can display an HTML document the way its developer
intends. This article explains how HTML can be used to provide fundamental page structure by defining başlıks and
paragrafs.
Önkoşullar:
Basic HTML familiarity, as covered in Basic HTML Syntax.
Learning
outcomes:
How to create a good document structure with başlıks and content beneath those
başlıks.
Using semantic HTML rather than presentational HTML, and why this is important.
The need for başlık levels to be used logically, i.e., no skipping levels or using them
arbitrarily because you want to achieve a certain font size (that's a job for CSS).
SEO benefits: for example, keywords are boosted in başlıks.
Accessibility benefits: Assistive technology (AT) such as ekran okuyucus use başlıks
(and other landmarks) as signposts to navigate content. HTML documents are very
difficult for AT users to use without başlıks.
Başlıklar ve paragraflar
Most structured text consists of başlıks and paragrafs, whether you are reading a story, a newspaper, a college
textbook, a magazine, etc.
İngilizce (ABD)
15.10.2026 20:22
Başlıklar ve paragraflar - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragrafs
1/6

Structured content makes the reading experience easier and more enjoyable.
In HTML, each paragraf has to be wrapped in a <p>  element, like so:
HTML
<p>I am a paragraf, oh yes I am.</p>
Each başlık has to be wrapped in a başlık element:
HTML
<h1>I am the title of the story.</h1>
There are six başlık elements: h1, h2, h3, h4, h5, and h6. Each element represents a different level of content in the
document; <h1>  represents the main başlık, <h2>  represents subbaşlıks, <h3>  represents sub-subbaşlıks, and
so on.
Implementing structural hierarchy
For example, in this story, the <h1>  element represents the title of the story, the <h2>  elements represent the title of
each chapter, and the <h3>  elements represent subsections of each chapter:
HTML
15.10.2026 20:22
Başlıklar ve paragraflar - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragrafs
2/6

<h1>The Crushing Bore</h1>
<p>By Chris Mills</p>
<h2>Chapter 1: The dark night</h2>
<p>
It was a dark night. Somewhere, an owl hooted. The rain lashed down on the…
</p>
<h2>Chapter 2: The eternal silence</h2>
<p>Our protagonist could not so much as a whisper out of the shadowy figure…</p>
<h3>The specter speaks</h3>
<p>
Several more hours had passed, when all of a sudden the specter sat bolt
upright and exclaimed, "Please have mercy on my soul!"
</p>
It's really up to you what the elements involved represent, as long as the hierarchy makes sense. You just need to bear in
mind a few best practices as you create such structures:
Preferably, you should use a single <h1>  per page—this is the top level başlık, and all others sit below this in
the hierarchy.
Make sure you use the başlıks in the correct order in the hierarchy. Don't use <h3>  elements to represent
subbaşlıks, followed by <h2>  elements to represent sub-subbaşlıks—that doesn't make sense and will lead
to weird results.
Of the six başlık levels available, you should aim to use no more than three per page, unless you feel it is
necessary. Documents with many levels (for example, a deep başlık hierarchy) become unwieldy and difficult to
navigate. On such occasions, it is advisable to spread the content over multiple pages if possible.
Why do we need structure?
To answer this question, let's take a look at 
—a nice hummus recipe. This document's body currently
contains multiple pieces of content. They aren't marked up in any way, but they are separated with line breaks
(Enter/Return pressed to go onto the next line).
However, when you 
, you'll see that the text appears as a big chunk!
text-start.html
open the document in your tarayıcı
15.10.2026 20:22
Başlıklar ve paragraflar - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragrafs
3/6

This is because there are no elements to give the content structure, so the tarayıcı does not know what is a başlık and
what is a paragraf. Furthermore:
Users looking at a web sayfası tend to scan quickly to find relevant content, often just reading the başlıks, to
begin with. (We usually 
.) If they can't see anything useful within a few
seconds, they'll likely get frustrated and go somewhere else.
Search engines indexing your page consider the contents of başlıks as important keywords for influencing the
page's search rankings. Without başlıks, your page will perform poorly in terms of SEO (Search Engine
Optimization).
Severely visually impaired people often don't read web sayfasıs; they listen to them instead. This is done with
software called a 
. This software provides ways to get fast access to given text content. Among
the various techniques used, they provide an outline of the document by reading out the başlıks, allowing their
users to find the information they need quickly. If başlıks are not available, they will be forced to listen to the
whole document read out loud.
To style content with CSS, or make it do interesting things with JavaScript, you need to have elements wrapping
the relevant content, so CSS/JavaScript can effectively target it.
Therefore, we need to give our content structural markup.
Giving content structure
Let's jump straight in and get you to solve a small code challenge to gain practice with HTML başlıks and paragrafs:
1. Click "Play" in the code block below to edit the example in the MDN Playground.
2. Wrap the appropriate text at the start of the content inside an <h1>  element to turn it into a main başlık.
3. There are two pairs of words that should be wrapped inside <h2>  elements to turn them into second level
başlıks.
4. Wrap the remaining sentences in <p>  elements to turn them into paragrafs. One <p>  element should sit below
each <h2>  element.
spend a very short time on a web sayfası
ekran okuyucu
15.10.2026 20:22
Başlıklar ve paragraflar - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragrafs
4/6

If you make a mistake, you can clear your work using the Reset button in the MDN Playground. If you get really stuck,
you can view the solution below the code block.
HTML
Favorite body parts The brain Lovely shape and color. Also does thinkin' stuff.
The feet Knobbly and ugly, but useful for getting about.
Favorite body parts The brain Lovely shape and color. Also does thinkin' stuff. The feet Knobbly and
ugly, but useful for getting about.
Click here to show the solution
Why do we need semantics?
Semantics are relied on everywhere around us—we rely on previous experience to tell us what the function of an
everyday object is; when we see something, we know what its function will be. So, for example, we expect a red traffic
light to mean "stop," and a green traffic light to mean "go." Things can get tricky very quickly if the wrong semantics are
applied. (Do any countries use red to mean "go"? We hope not.)
In a similar way, we need to make sure we are using the correct elements, giving our content the correct meaning,
function, or appearance. In this context, the <h1>  element is also a semantic element, which gives the text it wraps
around the role (or meaning) of "a top level başlık on your page."
HTML
<h1>This is a top level başlık</h1>
By default, the tarayıcı will give it a large font size to make it look like a başlık (although you could style it to look like
anything you wanted using CSS). More importantly, its semantic value will be used in multiple ways, for example by
search engines and ekran okuyucus (as mentioned above).
On the other hand, you could make any element look like a top level başlık. Consider the following:
HTML
<span style="font-size: 32px; margin: 21px 0; display: block;">
Is this a top level başlık?
</span>
This is a <span>  element. It has no semantics. You use it to wrap content when you want to apply CSS to it (or do
something to it with JavaScript) without giving it any extra meaning. (You'll find out more about these later on in the
15.10.2026 20:22
Başlıklar ve paragraflar - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragrafs
5/6

course.) We've applied some CSS to it to make it look like a top level başlık, but since it has no semantic value, it will
not get any of the extra benefits described above. It is a good idea to use the relevant HTML element for the job.
Summary
This concludes our study of HTML başlıks and paragrafs. Sonraki, we will look at more aspects of semantic HTML:
giving words emphasis.
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
15.10.2026 20:22
Başlıklar ve paragraflar - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragrafs
6/6


---

# Vurgu ve önem

## HTML

# Vurgu ve önem

## İngilizce (ABD)

# Vurgu ve önem

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

Önceki makale, HTML'de semantiğin neden önemli olduğuna baktı ve başlıklar ile paragraflara odaklandı. Bu makale, semantik temasını sürdürerek metne vurgu ve önem uygulayan HTML öğelerine bakar (basılı medyadaki italik ve kalın metne paralel olarak).

### Ön koşullar:

Temel HTML bilgisi; Basic HTML Syntax bölümünde ele alındığı gibi.

### Öğrenme çıktıları:

HTML'de vurguyu ve önemi ifade eden anlam ve bunları uygulayan temel öğeler, örneğin `<em>` ve `<strong>`.

Artık hiç kullanılmaması gereken sunumsal işaretlemeyi tanımlama (ör. `<big>` ve `<font>`); bunlar kullanımdan kaldırılmıştır.

Yeni semantik anlam kazanacak şekilde yeniden amaçlandırılmış sunumsal işaretlemeyi tanımlama (ör. `<i>` ve `<b>`).

## Vurgu ve önem nedir?

İnsan dilinde, bir cümlenin anlamını değiştirmek için belirli kelimeleri sık sık vurgularız ve çoğu zaman belirli kelimeleri önemli ya da bir bakıma farklı olarak işaretlemek isteriz. HTML, metin içeriğini bu tür etkilerle işaretlememize olanak tanıyan çeşitli semantik öğeler sağlar ve bu bölümde en yaygın olanlardan birkaçına bakacağız.

## Vurgu

Sözlü dilde vurgu eklemek istediğimizde, belirli kelimeleri vurgulayarak söylediklerimizin anlamını ince biçimde değiştiririz. Benzer şekilde, yazılı dilde de kelimeleri italik yaparak vurgulama eğilimindeyiz. Örneğin, aşağıdaki iki cümle farklı anlamlara sahiptir.

Ben geç kalmadığın için memnunum.

Ben geç kalmadığın için memnunum.

İlk cümle, kişinin geç kalmamış olmasından gerçekten rahatlama duyulduğunu ifade eder. Buna karşılık, hem "memnun" hem de "geç" kelimeleri italik yazılmış ikinci cümle, kişinin biraz geç gelmesinden duyulan rahatsızlığı ifade eden alaycı ya da pasif-agresif bir ton taşır.

HTML'de bu tür durumları işaretlemek için `<em>` (vurgu) öğesini kullanırız. Belgeyi okumayı daha ilginç hale getirmenin yanı sıra, bunlar ekran okuyucular tarafından da tanınır; ekran okuyucular bunları farklı bir ses tonuyla okuyacak şekilde yapılandırılabilir. Tarayıcılar bunu varsayılan olarak italik biçimde gösterir, ancak sadece italik görünüm elde etmek için bu etiketi kullanmamalısınız. Bunun için bir `<span>` öğesi ve biraz CSS ya da belki bir `<i>` öğesi kullanırsınız (aşağıya bakın).

```html
<p>Ben <em>memnun</em> oldum çünkü geç <em>kalmadın</em>.</p>
```

## Güçlü önem

Önemli kelimeleri vurgulamak için, konuşurken genellikle onları daha belirgin söyler ve yazıda kalın yaparız. Örneğin:

Bu sıvı son derece zehirlidir.

Sana güveniyorum. Geç kalma!

HTML'de bu tür durumları işaretlemek için `<strong>` (güçlü önem) öğesini kullanırız. Belgeyi daha kullanışlı hale getirmenin yanı sıra, bunlar da ekran okuyucular tarafından tanınır; ekran okuyucular bunları farklı bir ses tonuyla okuyacak şekilde yapılandırılabilir. Tarayıcılar bunu varsayılan olarak kalın metin biçiminde gösterir, ancak sadece kalın görünüm elde etmek için bu etiketi kullanmamalısınız. Bunun için bir `<span>` öğesi ve biraz CSS ya da belki bir `<b>` öğesi kullanırsınız (aşağıya bakın).

```html
<p>Bu sıvı <strong>son derece zehirlidir</strong>.</p>

<p>Sana güveniyorum. <strong>Geç</strong> kalma!</p>
```

İsterseniz güçlü önem ve vurguyu birbirinin içine yuvalayabilirsiniz:

```html
<p>Bu sıvı <strong>son derece zehirlidir</strong> — eğer onu içerseniz, <strong><em>ölebilirsiniz</em></strong>.</p>
```

Bu sıvı son derece zehirlidir.

Sana güveniyorum. Geç kalma!

Bu sıvı son derece zehirlidir — eğer onu içerseniz, ölebilirsiniz.

## Vurgu ve önemle oynayalım

Bu bölümde vurgu ve önem ile oynamanızı istiyoruz:

1. Aşağıdaki kod bloğunda örneği MDN Playground'da düzenlemek için "Play" düğmesine tıklayın.
2. Ana başlıkta "Emphasis" kelimesine vurgu, "importance" kelimesine güçlü önem verin.
3. İlk paragrafta kahve makinesi adına güçlü önem verin ve kahveyi tanımlamak için kullanılan sıfatları vurgulayın.
4. İkinci paragrafta sıcaklık açıklamasına (`"cold"`) ve yapmanız gereken eyleme (`"wrap up warm to avoid falling ill"`) güçlü önem verin. `"falling ill"` ifadesine hem vurgulanmış hem de önemli olacak şekilde ek işaretleme verin.

Hata yaparsanız, MDN Playground'daki Reset düğmesini kullanarak çalışmanızı temizleyebilirsiniz. Gerçekten takılırsanız, çözümü kod bloğunun altında görebilirsiniz.

```html
<h1>Vurgu ve önem</h1>

<p>

Yeni kahve makinemin adı The Percolator 2000. En

sublime ve wonderful kahveyi üretir.

</p>

<p>

Kışın en soğuk günlerinde, hava cold olacaktır. Hasta olmamak için sıcak giyinmelisiniz.

</p>
```

Vurgu ve önem

Yeni kahve makinemin adı The Percolator 2000. En sublime ve wonderful kahveyi üretir.

Kışın en soğuk günlerinde, hava cold olacaktır. Hasta olmamak için sıcak giyinmelisiniz.

Çözümü göstermek için buraya tıklayın

## İtalik, kalın, altı çizili…

Şimdiye kadar tartıştığımız öğelerin ilişkili semantik anlamları nettir. `<b>`, `<i>` ve `<u>` ile durum biraz daha karmaşıktır. Bunlar, CSS'in hâlâ zayıf desteklendiği ya da hiç desteklenmediği bir dönemde insanların kalın, italik veya altı çizili metin yazabilmesi için ortaya çıktı. Yalnızca görünümü etkileyen, semantiği etkilemeyen bu tür öğeler sunumsal öğeler olarak bilinir ve artık kullanılmamalıdır; çünkü daha önce gördüğümüz gibi semantik, erişilebilirlik, SEO vb. için çok önemlidir.

HTML5, `<b>`, `<i>` ve `<u>` öğelerini yeni ve bir miktar kafa karıştırıcı semantik rollerle yeniden tanımladı.

Unutabileceğiniz en iyi kural şudur: Geleneksel olarak kalın, italik ya da altı çizili ile aktarılan bir anlamı vermek için `<b>`, `<i>` veya `<u>` kullanmak ancak daha uygun bir öğe yoksa uygundur; ve genellikle vardır. `<strong>`, `<em>`, `<mark>` veya `<span>` daha uygun olabilir mi diye düşünün.

Her zaman erişilebilirlik odaklı düşünün. İtalik kavramı, ekran okuyucu kullanan kişiler ya da Latin alfabesi dışındaki bir yazı sistemi kullanan kişiler için pek yararlı değildir.

`<i>`, geleneksel olarak italikle aktarılan bir anlamı vermek için kullanılır: yabancı kelimeler, taksonomik adlandırmalar, teknik terimler, bir düşünce…

`<b>`, geleneksel olarak kalın ile aktarılan bir anlamı vermek için kullanılır: anahtar kelimeler, ürün adları, giriş cümlesi…

`<u>`, geleneksel olarak altı çizili ile aktarılan bir anlamı vermek için kullanılır: özel ad, yanlış yazım…

Not: İnsanlar altı çiziliyi güçlü biçimde bağlantılarla ilişkilendirir. Bu nedenle web'de yalnızca bağlantıların altını çizmek en iyisidir. Anlamsal olarak uygun olduğunda `<u>` öğesini kullanın, ancak web'de varsayılan altı çizgiyi daha uygun bir şeyle değiştirmek için CSS kullanmayı düşünün. Aşağıdaki örnek bunun nasıl yapılabileceğini gösterir.

```html
<!-- bilimsel adlar -->

<p>

Kızıl boğazlı sinekkuşu (<i>Archilochus colubris</i>) Doğu Kuzey Amerika'daki en yaygın

sinekkuşudur.

</p>

<!-- yabancı kelimeler -->

<p>

Menü, <i lang="uk-latn">vatrushka</i>,

<i lang="id">nasi goreng</i> ve <i lang="fr">soupe à l'oignon</i> gibi egzotik kelimeler deniziydi.

</p>

<!-- bilinen bir yanlış yazım -->

<p>Bir gün nasıl daha iyi <u class="spelling-error">spel</u> yazılacağını öğreneceğim.</p>

<!-- tanım verilirken tanımlanan terim -->

<dl>

<dt>Anlamsal HTML</dt>

<dd>

Öğeleri görünüşlerine göre değil, anlamsal anlamlarına göre kullanın.

</dd>

</dl>
```

Kızıl boğazlı sinekkuşu (Archilochus colubris) Doğu Kuzey Amerika'daki en yaygın sinekkuşudur.

Menü, vatrushka, nasi goreng ve soupe à l'oignon gibi egzotik kelimeler deniziydi.

Bir gün nasıl daha iyi spel yazılacağını öğreneceğim.

Anlamsal HTML

Öğeleri görünüşlerine göre değil, anlamsal anlamlarına göre kullanın.

## Özet

Şimdilik vurgu ve önem konusunu burada bitiriyoruz. Şimdi HTML'de listeleri nasıl temsil edeceğimize bakalım.

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

Daha iyi bir internet için planınız.

---

# Listeler

## HTML

# Listeler

## İngilizce (ABD)

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

Şimdi dikkatimizi listelere çevirelim. Listeler hayatın her yerindedir — alışveriş listenizden, her gün farkında olmadan evinize giderken takip ettiğiniz yönler listesine, bu eğitimlerde izlediğiniz yönergeler listesine kadar! HTML'nin farklı türde listeler tanımlamamıza olanak sağlayan kullanışlı bir öğe kümesine sahip olması şaşırtıcı olmayabilir. Web'de üç tür liste vardır: sırasız, sıralı ve açıklama listeleri. Bu ders, bunları nasıl kullanacağınızı gösterir.

### Ön koşullar:

Temel HTML bilgisi; Basic HTML Syntax bölümünde ele alındığı gibi.

### Öğrenme çıktıları:

Üç liste türü için HTML yapısı — sırasız, sıralı ve açıklama.

Her liste türü için doğru kullanım.

Gezinme menüleri gibi listelerin daha geniş kullanım alanları.

## Sırasız listeler

Sırasız listeler, öğelerin sırasının önemli olmadığı öğe listelerini işaretlemek için kullanılır. Bir market alışveriş listesini örnek alalım:

- süt
- yumurta
- ekmek
- humus

Bu örnekte öğeler herhangi bir sırada olabilir. Bu listeyi HTML'de oluşturmak için önce tüm listeyi bir `<ul>` (unordered list) öğesi içine alırız. Sonra her öğeyi bir `<li>` (list item) öğesi içine alırız:

```html
<ul>
<li>süt</li>
<li>yumurta</li>
<li>ekmek</li>
<li>humus</li>
</ul>
```

## Sırasız bir listeyi işaretleme

Size biraz pratik yaptırmak için, önceki listeyi kendiniz işaretlemeyi denemenizi istiyoruz:

1. Aşağıdaki oluşturulmuş kod çıktısında örneği düzenlemek için "Play" düğmesine tıklayın.
2. Tek tek metin öğelerini sırasız bir listeye dönüştürün.

Hata yaparsanız, MDN Playground'daki Reset düğmesini kullanarak çalışmanızı temizleyebilirsiniz. Takılırsanız, önceki kod parçasına geri dönün.

süt yumurta ekmek humus

## Sıralı

Sıralı listeler, öğelerin sırasının önemli olduğu listelerdir. Bir yol tarifi kümesini örnek alalım:

- Yolun sonuna kadar sürün
- Sağa dönün
- İlk iki kavşaktan dümdüz geçin
- Üçüncü kavşakta sola dönün
- Okul, yolun sağında, 300 metre ileridedir

İşaretleme yapısı sırasız listelerle aynıdır; tek fark, liste öğelerini `<ul>` yerine bir `<ol>` öğesi içine almanız gerektiğidir:

```html
<ol>
<li>Yolun sonuna kadar sürün</li>
<li>Sağa dönün</li>
<li>İlk iki kavşaktan dümdüz geçin</li>
<li>Üçüncü kavşakta sola dönün</li>
<li>Okul, yolun sağında, 300 metre ileridedir</li>
</ol>
```

## Sıralı bir listeyi işaretleme

Yine pratik zamanı! Bir önceki görevdeki gibi, önceki sıralı listeyi kendiniz işaretlemeyi denemenizi istiyoruz.

1. Aşağıdaki oluşturulmuş kod çıktısında örneği düzenlemek için "Play" düğmesine tıklayın.
2. Tek tek metin öğelerini sıralı bir listeye dönüştürün.

Hata yaparsanız, MDN Playground'daki Reset düğmesini kullanarak çalışmanızı temizleyebilirsiniz. Takılırsanız, önceki kod parçasına geri dönün.

Yolun sonuna kadar sürün Sağa dönün İlk iki kavşaktan dümdüz geçin Üçüncü kavşakta sola dönün Okul, yolun sağında, 300 metre ileridedir

## Tarif sayfamızı işaretleme

Şimdi gerçek bir meydan okumaya! Bu noktada, daha karmaşık bir içerik bölümünü işaretlemek için ihtiyacınız olan tüm bilgiye sahipsiniz. En sevdiğimiz humus tarifinin yönergelerini işaretlemenizi istiyoruz.

İsterseniz şunlardan birini yapabilirsiniz:

Yerel bir kopyasını kaydedin: `text-start.html` başlangıç dosyası ve işi kod düzenleyicinizde yapın.

Aşağıdaki oluşturulmuş kod çıktısında örneği düzenlemek için "Play" düğmesine tıklayın.

İzlemeniz gereken yönergeler:

1. Ana sayfa başlığını bir `<h1>` öğesiyle ve üç alt başlığı `<h2>` öğeleriyle işaretleyin.
2. `<p>` öğeleriyle işaretlenmesi anlamlı olan beş metin satırı vardır. Bunu şimdi yapın.
3. Malzeme listesini sırasız liste olarak işaretleyin.
4. Talimat listesini sıralı liste olarak işaretleyin.

Hata yaparsanız, MDN Playground'daki Reset düğmesini kullanarak çalışmanızı temizleyebilirsiniz. Gerçekten takılırsanız, çözümü kod çıktısının altında görebilirsiniz.

```html
Quick hummus recipe

Bu tarif, hızlı ve lezzetli humus yapar; hiçbir zahmeti yoktur. Yıllar içinde okuduğum birçok farklı tariften uyarlanmıştır.

Humus, Yunan ve Orta Doğu yemeklerinde yoğun biçimde kullanılan lezzetli, koyu bir ezmedir. Salata, ızgara etler ve pita ekmekleriyle çok lezzetlidir.

Ingredients

1 can (400g) of chick peas (garbanzo beans)

175g of tahini

6 sundried tomatoes

Half a red pepper

A pinch of cayenne pepper

1 clove of garlic

A dash of olive oil

Instructions

Garlic'in kabuğunu çıkarın ve kabaca doğrayın

Biberin tüm çekirdeklerini ve sapını çıkarın ve kabaca doğrayın

Tüm malzemeleri bir food processor içine ekleyin
```

```text
Tüm malzemeleri bir ezmeye dönüştürün

Kaba "chunky" humus istiyorsanız, kısa süre işleyin

Pürüzsüz humus istiyorsanız, daha uzun süre işleyin

Farklı bir lezzet için, az miktarda limon ve kişniş, chili pepper, lime ve chipotle, harissa ve mint ya da spinach ve feta cheese eklemeyi deneyebilirsiniz. Deneyin ve sizin için neyin işe yaradığını görün.

Storage

Hazırladığınız humusu kapalı bir kapta buzdolabında saklayın. Yapıldıktan sonra yaklaşık bir hafta boyunca kullanabilmelisiniz. Eğer köpürmeye başlarsa, mutlaka atmalısınız.

Humus dondurmak için uygundur; çözdürüp birkaç ay içinde kullanmalısınız.
```

Quick hummus recipe Bu tarif, hızlı ve lezzetli humus yapar; hiçbir zahmeti yoktur. Yıllar içinde okuduğum birçok farklı tariften uyarlanmıştır. Humus, Yunan ve Orta Doğu yemeklerinde yoğun biçimde kullanılan lezzetli, koyu bir ezmedir. Salata, ızgara etler ve pita ekmekleriyle çok lezzetlidir. Ingredients 1 can (400g) of chick peas (garbanzo beans) 175g of tahini 6 sundried tomatoes Half a red pepper A pinch of cayenne pepper 1 clove of garlic A dash of olive oil Instructions Garlic'in kabuğunu çıkarın ve kabaca doğrayın Biberin tüm çekirdeklerini ve sapını çıkarın ve kabaca doğrayın Tüm malzemeleri bir food processor içine ekleyin Tüm malzemeleri bir ezmeye dönüştürün Kaba "chunky" humus istiyorsanız, kısa süre işleyin Pürüzsüz humus istiyorsanız, daha uzun süre işleyin Farklı bir lezzet için, az miktarda limon ve kişniş, chili pepper, lime ve chipotle, harissa ve mint ya da spinach ve feta cheese eklemeyi deneyebilirsiniz. Deneyin ve sizin için neyin işe yaradığını görün. Storage Hazırladığınız humusu kapalı bir kapta buzdolabında saklayın. Yapıldıktan sonra yaklaşık bir hafta boyunca kullanabilmelisiniz. Eğer köpürmeye başlarsa, mutlaka atmalısınız. Humus dondurmak için uygundur; çözdürüp birkaç ay içinde kullanmalısınız.

Çözümü göstermek için buraya tıklayın

## İç içe listeler

Bir listenin içine başka bir liste yerleştirmek tamamen uygundur. Üst düzey bir madde altında yer alacak bazı alt maddeler isteyebilirsiniz. Tarif örneğimizden ikinci listeyi ele alalım:

```html
<ol>
<li>Garlic'in kabuğunu çıkarın ve kabaca doğrayın.</li>
<li>Biberin tüm çekirdeklerini ve sapını çıkarın ve kabaca doğrayın.</li>
<li>Tüm malzemeleri bir food processor içine ekleyin.</li>
<li>Tüm malzemeleri bir ezmeye dönüştürün.</li>
<li>Eğer kaba "chunky" humus istiyorsanız, kısa süre işleyin.</li>
<li>Eğer pürüzsüz humus istiyorsanız, daha uzun süre işleyin.</li>
</ol>
```

Son iki madde, kendilerinden bir önceki maddeyle çok yakından ilişkili olduğundan (o maddenin alt talimatları ya da seçenekleri gibi okunurlar), bunları kendi sırasız listelerinin içine yerleştirip o listeyi mevcut dördüncü maddenin içine koymak mantıklı olabilir. Bu şu şekilde görünür:

```html
<ol>
<li>Garlic'in kabuğunu çıkarın ve kabaca doğrayın.</li>
<li>Biberin tüm çekirdeklerini ve sapını çıkarın ve kabaca doğrayın.</li>
<li>Tüm malzemeleri bir food processor içine ekleyin.</li>
<li>
Tüm malzemeleri bir ezmeye dönüştürün.
<ul>
<li>
Eğer kaba "chunky" humus istiyorsanız, kısa süre işleyin.
</li>
<li>Eğer pürüzsüz humus istiyorsanız, daha uzun süre işleyin.</li>
</ul>
</li>
</ol>
```

Bir önceki göreve geri dönmeyi ve ikinci listeyi böyle güncellemeyi deneyin.

## Açıklama listeleri

Açıklama listelerinin amacı, terimler ve tanımlar ya da sorular ve cevaplar gibi öğe kümelerini ve bunlara ilişkin açıklamaları işaretlemektir. Terimler ve tanımlardan oluşan bir kümeye örnek bakalım:

- soliloquy
- monologue
- aside

Dramada, bir karakterin kendi kendine konuşarak iç düşüncelerini ya da duygularını temsil ettiği ve bunu yaparken de izleyiciye aktardığı durum.

Dramada, bir karakterin düşüncelerini izleyicilerle ve mevcut diğer karakterlerle paylaşmak için yüksek sesle konuştuğu durum.

Dramada, bir karakterin yalnızca izleyiciyle mizahi ya da dramatik etki için bir yorum paylaştığı durum. Bu genellikle bir duygu, düşünce ya da ek arka plan bilgisidir.

Açıklama listeleri diğer liste türlerinden farklı bir kapsayıcı kullanır — `<dl>`; ayrıca her terim bir `<dt>` (description term) öğesi içine alınır ve her açıklama bir `<dd>` (description definition) öğesi içine alınır.

## Açıklama listesi örneği

Örneğimizi işaretlemeyi bitirelim:

---

# Becerilerinizi test edin: HTML metin temelleri

## Test: HTML tests index

# Becerilerinizi test edin: HTML metin temelleri

## İngilizce (ABD)

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

Bu beceri testinin amacı, HTML'de metni yapı ve anlam verecek şekilde nasıl işaretleyeceğinizi anlayıp anlamadığınızı ölçmenize yardımcı olmaktır.

Not: Yardım almak için Test your skills kullanım kılavuzunu okuyun. Ayrıca iletişim kanallarımızdan biri aracılığıyla bize ulaşabilirsiniz.

## Metin temelleri 1

Bu görevde, sağlanan HTML'yi anlamsal başlık ve paragraf öğelerini kullanarak işaretlemenizi istiyoruz.

Görevin başlangıç noktası şu şekildedir:

Temel HTML Hayvanları Bu, sayfamızdaki ilk paragraftır. Hayvanlarımızı tanıtır. Lama Lamamız, liste öğelerinin büyük bir hayranıdır. Bir web sayfasında onlardan bir parça görürse, sanki şekerlermiş gibi onları yer ve bunu yaparken dudaklarını yalar. Anakonda Kurnaz anakonda sayfa boyunca süzülmeyi, avının üzerine sinsice yaklaşmak için bağlantılar aracılığıyla hızla ilerlemeyi sever.

İşte bu başlangıç noktasının temel kodu:

```html
Temel HTML Hayvanları

Bu, sayfamızdaki ilk paragraftır. Hayvanlarımızı tanıtır.

Lama

Llamamız, liste öğelerinin büyük bir hayranıdır. Bir web sayfasında onlardan bir parça görürse,

onları sanki şekerlermiş gibi yer ve bunu yaparken dudaklarını yalar.

Anakonda

Kurnaz anakonda sayfa boyunca süzülmeyi, bağlantılar aracılığıyla hızla ilerlemeyi

ve avının üzerine sinsice yaklaşmayı sever.
```

Güncellenmiş içerik şöyle görünmelidir:

Temel HTML Hayvanları

Bu, sayfamızdaki ilk paragraftır. Hayvanlarımızı tanıtır.

Lama

Llamamız, liste öğelerinin büyük bir hayranıdır. Bir web sayfasında onlardan bir parça görünce,

onları sanki şekerlermiş gibi yer ve bunu yaparken dudaklarını yalar.

Anakonda

Kurnaz anakonda sayfa boyunca süzülmeyi, bağlantılar aracılığıyla hızla ilerlemeyi

ve avının üzerine sinsice yaklaşmayı sever.

Çözümü göstermek için buraya tıklayın

## Metin temelleri 2

Bu görevde, ilk işaretlenmemiş listeyi sırasız bir listeye ve ikincisini sıralı bir listeye dönüştürmenizi istiyoruz.

Görevin başlangıç noktası şu şekildedir:

Listelere bakarken

Aşağıdaki favori sebzeler listemi sırasız bir listeye dönüştürün.

Salatalık Brokoli Kuşkonmaz Biber

Aşağıdaki yönergeleri sıralı bir listeye dönüştürün.

Kapıyı önce çalın Uyarıldığınızda sihirli sözü söyleyin En az 5 saniye bekleyin Kolu çevirin ve itin

İşte bu başlangıç noktasının temel kodu:

```html
<h1>Listelere bakarken</h1>

<p>Aşağıdaki favori sebzeler listemi sırasız bir listeye dönüştürün.</p>

Salatalık

Brokoli

Kuşkonmaz

Biber

<p>Aşağıdaki yönergeleri sıralı bir listeye dönüştürün.</p>

Kapıyı önce çalın

Uyarıldığınızda sihirli sözü söyleyin

En az 5 saniye bekleyin

Kolu çevirin ve itin
```

Güncellenmiş içerik şöyle görünmelidir:

Listelere bakarken

Aşağıdaki favori sebzeler listemi sırasız bir listeye dönüştürün.

Salatalık
Brokoli
Kuşkonmaz
Biber

Aşağıdaki yönergeleri sıralı bir listeye dönüştürün.

1. Kapıyı önce çalın
2. Uyarıldığınızda sihirli sözü söyleyin
3. En az 5 saniye bekleyin
4. Kolu çevirin ve itin

Çözümü göstermek için buraya tıklayın

## Metin temelleri 3

Bu görevde, verilen hayvanları ve tanımlarını bir açıklama listesine dönüştürmenizi istiyoruz.

Görevin başlangıç noktası şu şekildedir:

```html
# Şimdiye ait olmayan HTML Hayvanları

Lama Uzun, yünlü dört ayaklı, sivri kulaklı. Bazen binilebilir, ama huysuzdur ve çok tükürür. Liste öğelerinin büyük hayranı.

Anakonda Bağlantılar aracılığıyla hızla ilerleyerek avının üzerine sinsice yaklaşan çok büyük bir boğucu yılan.

Su aygırı Onun tanımı dipsizdir.
```

İşte bu başlangıç noktasının temel kodu:

```html
<h1>İleri düzey HTML hayvanları</h1>

Lama

Uzun, yünlü dört ayaklı, sivri kulaklı. Bazen binilebilir, ama huysuzdur ve çok tükürür. Liste öğelerinin büyük hayranı.

Anakonda

Bağlantılar aracılığıyla hızla ilerleyerek avının üzerine sinsice yaklaşan çok büyük bir boğucu yılan.

Su aygırı

Onun tanımı dipsizdir.
```

Güncellenmiş içerik şöyle görünmelidir:

İleri düzey HTML hayvanları

Lama

Uzun, yünlü dört ayaklı, sivri kulaklı. Bazen binilebilir, ama huysuzdur ve çok tükürür. Liste öğelerinin büyük hayranı.

Anakonda

Bağlantılar aracılığıyla hızla ilerleyerek avının üzerine sinsice yaklaşan çok büyük bir boğucu yılan.

Su aygırı

Onun tanımı dipsizdir.

Çözümü göstermek için buraya tıklayın

## Metin temelleri 4

Bu görevde size bir paragraf verilir ve amacınız, birkaç uygun kelimeyi güçlü önemle ve birkaçını vurguyla işaretlemek için bazı satır içi öğeler kullanmaktır.

Görevin başlangıç noktası şu şekildedir:

```html
<h1>Vurgu ve önem</h1>

<p>

Benim için önemli iki şey var — müzik ve arkadaşlar. Bir gün arkadaşlarımın birbirleriyle ve müziğimle ilgilenmesini sağlayabilirim!

</p>
```

Güncellenmiş içerik yaklaşık olarak şöyle görünmelidir:

Vurgu ve önem

Benim için önemli iki şey var — müzik ve arkadaşlar. Bir gün arkadaşlarımın birbirleriyle ve müziğimle ilgilenmesini sağlayabilirim!

Çözümü göstermek için buraya tıklayın

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

Daha iyi bir internet için planınız.

---

# Gelişmiş metin özellikleri

## HTML

# Gelişmiş metin özellikleri

## İngilizce (ABD)

Gelişmiş metin özellikleri

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

HTML'de, Vurgu ve önem makalesinde ele almaya fırsat bulamadığımız metin semantiğini tanımlamak için başka birçok öğe vardır. Bu makalede anlatılan öğeler daha az bilinir, ancak yine de bilinmesi yararlıdır (ve bu da hiçbir şekilde tam bir liste değildir). Burada alıntıların, bilgisayar kodunun ve diğer ilgili metinlerin, alt ve üst simgelerin, iletişim bilgilerinin ve daha fazlasının nasıl işaretleneceğini öğreneceksiniz.

### Ön koşullar:

Basic HTML Syntax bölümünde ele alındığı gibi temel HTML bilgisi. Başlıklar, paragraflar ve listeler gibi metin düzeyi semantiği.

### Öğrenme çıktıları:

Alıntılar.

Kısaltmalar ve akronimler.

Adresler.

Saatler ve tarihler.

Üst simge ve alt simge.

## Alıntılar

HTML, alıntıları işaretlemek için kullanılabilen özellikler içerir; hangi öğeyi kullanacağınız, blok düzeyinde mi yoksa satır içi bir alıntı mı işaretlediğinize bağlıdır.

### Blok alıntılar

Bir blok düzeyindeki içerik bölümü (ister bir paragraf, ister birden fazla paragraf, ister bir liste vb.) başka bir yerden alıntılanmışsa, bunu belirtmek için onu bir `<blockquote>` öğesinin içine sarmalısınız ve alıntı kaynağını gösteren bir URL'yi `cite` özniteliği içinde eklemelisiniz. Örneğin, aşağıdaki işaretleme MDN `<blockquote>` öğesi sayfasından alınmıştır:

```html
<p>

<strong>HTML <code>&lt;blockquote&gt;</code> Element</strong> (veya

<em>HTML Block Quotation Element</em>) çevrelenmiş metnin genişletilmiş bir alıntı olduğunu belirtir.

</p>
```

Bunu bir blok alıntıya dönüştürmek için yalnızca şunu yaparız:

```html
<p>İşte bir blockquote:</p>

<blockquote

cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/blockquote">

<p>

<strong>HTML <code>&lt;blockquote&gt;</code> Element</strong> (veya

<em>HTML Block Quotation Element</em>) çevrelenmiş metnin genişletilmiş bir alıntı olduğunu belirtir.

</p>

</blockquote>
```

Tarayıcının varsayılan stili bunu, alıntı olduğuna dair bir gösterge olarak girintili bir paragraf şeklinde görüntüler; alıntının üzerindeki paragraf da bunu göstermek içindir.

HTML <blockquote> Element (veya HTML Block Quotation Element), çevrelenmiş metnin genişletilmiş bir alıntı olduğunu belirtir.

İşte bir blockquote:

HTML <blockquote> Element (veya HTML Block Quotation Element), çevrelenmiş metnin genişletilmiş bir alıntı olduğunu belirtir.

### Satır içi alıntılar

Satır içi alıntılar tam olarak aynı şekilde çalışır, ancak bunun için `<q>` öğesini kullanırız. Örneğin, aşağıdaki işaretleme MDN `<q>` sayfasından bir alıntı içerir:

```html
<p>

Alıntı öğesi — <code>&lt;q&gt;</code> —

<q

cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/q">

paragraf sonları gerektirmeyen kısa alıntılar için tasarlanmıştır.

</q>

</p>
```

Tarayıcının varsayılan stili bunu, alıntıyı belirtmek için tırnak içine alınmış normal metin olarak gösterir; şöyle:

```text
Alıntı öğesi — <q> — “ paragraf sonları gerektirmeyen kısa alıntılar için tasarlanmıştır. ”
```

### Atıflar

`cite` özniteliğinin içeriği kullanışlı görünür, ancak ne yazık ki tarayıcılar, ekran okuyucular vb. bununla pek bir şey yapmaz. `cite` içeriğini tarayıcıya göstertmenin, JavaScript veya CSS ile kendi çözümünüzü yazmadan bir yolu yoktur. Alıntının kaynağını sayfada görünür kılmak istiyorsanız, bunu metin içinde bir bağlantı ya da başka uygun bir yolla sağlamanız gerekir.

Ayrıca bir `<cite>` öğesi vardır; ancak bu, alıntılanan kaynağın başlığını, örneğin kitabın adını içermek için kullanılır. Bununla birlikte, `<cite>` içindeki metni bir şekilde alıntı kaynağına bağlamanıza engel yoktur:

```html
<p>

Şuna göre:

<a href="/en-US/docs/Web/HTML/Reference/Elements/blockquote">

<cite>MDN blockquote sayfası</cite></a>:

</p>

<blockquote

cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/blockquote">

<p>

<strong>HTML <code>&lt;blockquote&gt;</code> Element</strong> (veya

<em>HTML Block Quotation Element</em>) çevrelenmiş metnin genişletilmiş bir alıntı olduğunu belirtir.

</p>

</blockquote>

<p>

Alıntı öğesi — <code>&lt;q&gt;</code> —

<q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/q">

paragraf sonları gerektirmeyen kısa alıntılar için tasarlanmıştır.

</q>

— <a href="/en-US/docs/Web/HTML/Reference/Elements/q"><cite>MDN q sayfası</cite></a>.

</p>
```

Atıflar varsayılan olarak italik yazı tipiyle biçimlendirilir.

Şuna göre:

HTML <blockquote> Element (veya HTML Block Quotation Element), çevrelenmiş metnin genişletilmiş bir alıntı olduğunu belirtir.

Alıntı öğesi — <q> — “ paragraf sonları gerektirmeyen kısa alıntılar için tasarlanmıştır. ” — MDN q sayfası.

## Kim söyledi? Blockquote pratiği

Bir başka görev zamanı! Bu örnekte sizden şunları istiyoruz:

1. Aşağıdaki kod bloğunda örneği düzenlemek için MDN Playground'da "Play" düğmesine tıklayın.
2. Ortadaki paragrafı bir blockquote'a dönüştürün ve bir `cite` özniteliği ekleyin.
3. Üçüncü paragraftaki "The Need To Eliminate Negative Self Talk" ifadesini satır içi bir alıntıya dönüştürün ve bir `cite` özniteliği ekleyin.
4. Her kaynağın başlığını `<cite>` etiketleri içine sarın ve her birini o kaynağa giden bir bağlantıya dönüştürün.

Bilmeniz gereken alıntı kaynakları şunlardır:

`http://www.brainyquote.com/quotes/authors/c/confucius.html` — Confucius alıntısı için

`http://example.com/affirmationsforpositivethinking` — "The Need To Eliminate Negative Self Talk" için.

Hata yaparsanız, MDN Playground'daki Reset düğmesini kullanarak çalışmanızı temizleyebilirsiniz. Gerçekten takılırsanız, çözümü kod bloğunun altında görebilirsiniz.

```html
<p>Merhaba ve motivasyon sayfama hoş geldiniz. Confucius'un alıntılar sitesi şöyle diyor:</p>

<p>Yavaş gitmeniz önemli değil, yeter ki durmayın.</p>

<p>

Pozitif düşünce kavramını da çok seviyorum ve The Need To Eliminate

Negative Self Talk (Affirmations for Positive Thinking'de belirtildiği gibi.)

</p>
```

Merhaba ve motivasyon sayfama hoş geldiniz. Confucius'un alıntılar sitesi şöyle diyor:

Yavaş gitmeniz önemli değil, yeter ki durmayın.

Pozitif düşünce kavramını da çok seviyorum ve The Need To Eliminate Negative Self Talk (Affirmations for Positive Thinking'de belirtildiği gibi.)

Çözümü göstermek için buraya tıklayın

## Kısaltmalar

Web'de bakarken karşınıza çıkacak bir diğer oldukça yaygın öğe `<abbr>`'dır — bu, bir kısaltma ya da akronimi sarmalamak için kullanılır. Bunlardan herhangi birini dahil ederken, ilk kullanımda düz metin olarak terimin tam açılımını sağlayın ve kısaltmayı işaretlemek için `<abbr>` kullanın. Bu, içerik hakkında tüm kullanıcılara ne anlama geldiğini bildirirken kullanıcı aracılarının içeriği nasıl duyurup/göstereceğine dair bir ipucu sağlar.

Açılımın kısaltmayla birlikte verilmesi pek anlamlı değilse ve kısaltma ya da akronim oldukça kısa bir terimse, `title` özniteliğinin değeri olarak tam açılımı verin:

### Kısaltma örneği

Bir örneğe bakalım.

```html
<p>

HTML kullanıyoruz, Hypertext Markup Language, web

dokümanlarımızı yapılandırmak için.

</p>

<p>

Bence <abbr title="Reverend">Rev.</abbr> Green işi mutfakta testereyle yaptı.

</p>
```

Bunlar şu şekilde görüntülenir:

HTML kullanıyoruz, Hypertext Markup Language, web dokümanlarımızı yapılandırmak için.

Bence Rev. Green işi mutfakta testereyle yaptı.

Not: html'in önceki sürümlerinde `<acronym>` öğesi için de destek vardı, ancak bu öğe, hem kısaltmaları hem de akronimleri temsil etmek için `<abbr>` kullanımını tercih ederek HTML spesifikasyonundan kaldırıldı. `<acronym>` kullanılmamalıdır.

## Bir kısaltmayı işaretleyelim

Bu öğrenme görevi için bir kısaltmayı işaretlemenizi istiyoruz.

1. Aşağıdaki kod bloğunda örneği düzenlemek için MDN Playground'da "Play" düğmesine tıklayın.
2. Dahil edilen kısaltmaları uygun HTML ile işaretleyin. İsterseniz bunu kendi seçtiğiniz bir örnekle değiştirebilir ve onu işaretlemeyi de deneyebilirsiniz.

Hata yaparsanız, MDN Playground'daki Reset düğmesini kullanarak çalışmanızı temizleyebilirsiniz. Gerçekten takılırsanız, çözümü kod bloğunun altında görebilirsiniz.

```html
<p>NASA kesinlikle heyecan verici işler yapıyor.</p>

<p>Yeni kullanıcı arayüzü tasarımı LGTM!</p>
```

NASA kesinlikle heyecan verici işler yapıyor.

Yeni kullanıcı arayüzü tasarımı LGTM!

Çözümü göstermek için buraya tıklayın

## İletişim bilgilerini işaretleme

HTML, iletişim bilgilerini işaretlemek için bir öğe sağlar — `<address>`. Bu, örneğin iletişim bilgilerinizi sarmalar:

```html
<address>Chris Mills, Manchester, The Grim North, UK</address>
```

Daha karmaşık işaretleme ve diğer iletişim bilgileri biçimlerini de içerebilir; örneğin:

```html
<address>

<p>

Chris Mills<br />

Manchester<br />

The Grim North<br />

UK

</p>

<ul>

<li>Tel: 01234 567 890</li>

<li>Email: me@grim-north.co.uk</li>

</ul>

</address>
```

Not: Bağlantılı sayfa iletişim bilgilerini içeriyorsa, aşağıdaki gibi bir şey de uygun olur:

```html
<address>

Page written by <a href="../authors/chris-mills/">Chris Mills</a>.

</address>
```

Not: `<address>` öğesi yalnızca en yakın `<article>` ya da `<body>` öğesinin içerdiği belge için iletişim bilgileri sağlamak amacıyla kullanılmalıdır. Bir sitenin tüm sitesi için iletişim bilgilerini eklemek üzere sitenin alt bilgisinde ya da bir makale içinde yazarın iletişim bilgileri için kullanmak doğrudur, ancak o sayfanın içeriğiyle ilgisiz adres listesini işaretlemek için doğru değildir.

## Üst simge ve alt simge

Tarihler, kimyasal formüller ve matematiksel denklemler gibi öğeleri doğru anlamlarıyla işaretlemek için zaman zaman üst simge ve alt simge kullanmanız gerekir. `<sup>` ve `<sub>` öğeleri bu işi yapar. Örneğin:

```html
<p>Doğum günüm 25<sup>th</sup> Mayıs 2001'dir.</p>

<p>

Kafeinin kimyasal formülü

C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>'dir.

</p>

<p>Eğer x<sup>2</sup> 9 ise, x 3 ya da -3 olmalıdır.</p>
```

Bu kodun çıktısı şöyle görünür:

Doğum günüm 25th Mayıs 2001'dir.

Kafeinin kimyasal formülü C8H10N4O2'dir.

Eğer x2 9 ise, x 3 ya da -3 olmalıdır.

## Bilgisayar kodunu temsil etme

HTML kullanarak bilgisayar kodunu işaretlemek için kullanılabilecek bir dizi öğe vardır:

`<code>`: Genel bilgisayar kodu parçalarını işaretlemek için.

`<pre>`: Boşlukları korumak için (genellikle kod blokları) — metninizin içine girinti veya fazla boşluk koyarsanız, tarayıcılar bunu yok sayar ve oluşturulan sayfada görmezsiniz. Ancak metni `<pre>` etiketlerine sararsanız, boşluklar metin düzenleyicinizde gördüğünüzle aynı şekilde gösterilir.

`<var>`: Değişken adlarını özellikle işaretlemek için.

`<kbd>`: Bilgisayara girilen klavye (ve diğer türden) girdileri işaretlemek için.

`<samp>`: Bir bilgisayar programının çıktısını işaretlemek için.

Bu öğelerin nasıl kullanıldığını gösteren örneklere bakalım:

```html
<pre><code>const para = document.querySelector('p');

para.onclick = function() {

alert('Owww, stop poking me!');

}</code></pre>

<p>

`<font>` ve `<center>` gibi sunumsal öğeleri kullanmamalısınız.

</p>

<p>

Yukarıdaki JavaScript örneğinde, `<var>para</var>` bir paragraf öğesini temsil eder.

</p>

<p>Metnin tamamını `<kbd>Ctrl</kbd>/<kbd>Cmd</kbd> + <kbd>A</kbd>` ile seçin.</p>

<pre>$ <kbd>ping mozilla.org</kbd>

<samp>PING mozilla.org (63.245.215.20): 56 data bytes

64 bytes from 63.245.215.20: icmp_seq=0 ttl=40 time=158.233 ms</samp></pre>
```

Yukarıdaki kod şöyle görünür:

```text
const para = document.querySelector('p');

para.onclick = function() {
  alert('Owww, stop poking me!');
}

`<font>` ve `<center>` gibi sunumsal öğeleri kullanmamalısınız.

Yukarıdaki JavaScript örneğinde, para bir paragraf öğesini temsil eder.

Metnin tamamını Ctrl/Cmd + A ile seçin.

$ ping mozilla.org
PING mozilla.org (63.245.215.20): 56 data bytes
64 bytes from 63.245.215.20: icmp_seq=0 ttl=40 time=158.233 ms
```

## Saatleri ve tarihleri işaretleme

HTML ayrıca, saatleri ve tarihleri makine tarafından okunabilir bir biçimde işaretlemek için `<time>` öğesini sağlar. Örneğin:

```html
<time datetime="2016-01-20">20 Ocak 2016</time>
```

Bu neden yararlıdır? Çünkü insanların tarihleri yazmasının birçok farklı yolu vardır. Yukarıdaki tarih şu şekillerde yazılabilir:

20 Ocak 2016

20 Ocak 2016

Jan 20 2016

20/01/16

01/20/16

Gelecek ayın 20'si

20e Janvier 2016

2016 年 1 ⽉ 20 ⽇

Ve benzeri.

Ancak bu farklı biçimler bilgisayarlar tarafından kolayca tanınamaz — bir sayfadaki tüm etkinliklerin tarihlerini otomatik olarak alıp bir takvime eklemek isteseydiniz ne olurdu? `<time>` öğesi, bu amaç için belirsiz olmayan, makine tarafından okunabilir bir tarih/saat eklemenize olanak tanır.

Yukarıdaki temel örnek yalnızca basit, makine tarafından okunabilir bir tarih sağlar; ancak mümkün olan başka seçenekler de vardır, örneğin:

```html
<!-- Standart basit tarih -->

<time datetime="2016-01-20">20 Ocak 2016</time>

<!-- Yalnızca yıl ve ay -->

<time datetime="2016-01">Ocak 2016</time>

<!-- Yalnızca ay ve gün -->

<time datetime="01-20">20 Ocak</time>

<!-- Yalnızca saat ve dakika -->

<time datetime="19:30">19:30</time>

<!-- Saniye ve milisaniye de verebilirsiniz! -->

<time datetime="19:30:01.856">19:30:01.856</time>

<!-- Tarih ve saat -->

<time datetime="2016-01-20T19:30">20 Ocak 2016, akşam 7.30</time>

<!-- Saat dilimi farkıyla tarih ve saat -->

<time datetime="2016-01-20T19:30+01:00">

20 Ocak 2016 akşam 7.30, Fransa'da akşam 8.30'dur

</time>

<!-- Belirli bir hafta numarasını belirtme -->

<time datetime="2016-W04">2016'nın dördüncü haftası</time>
```

## Özet

Bu, daha az yaygın HTML metin semantiklerini incelememizin sonunu işaret ediyor. Bu kurs boyunca gördükleriniz, HTML metin öğelerinin eksiksiz bir listesi değildir — temel unsurları ve sahada daha sık göreceğiniz daha yaygın olanlardan bazılarını ele almaya çalıştık.

Sırada, daha az yaygın HTML metin özelliklerini ne kadar iyi anladığınızı ve aklınızda tuttuğunuzu kontrol etmek için kullanabileceğiniz bazı testler var.

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

Daha iyi bir internet için planınız.

---

# Türkçe çeviri

Test: HTML tests index
Test: Advanced HTML text
Yeteneklerinizi test edin: Gelişmiş HTML metni
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
The aim of this skill test is to help you assess whether you understand how to use lesser-known HTML elements to mark
up advanced semantic features.
Advanced text 1
In this task, we want you to add some semantics to the provided HTML.
To complete this task:
1. Turn the second paragraf into a block-level quote, and semantically indicate that the quote is taken from
Accessibility.
2. Semantically mark up "HTML" and "CSS" as acronyms, providing expansions as tooltips.
3. Use subscript and superscript to provide correct semantics for the chemical formulae and dates, and make them
display correctly.
4. Semantically associate machine-readable dates with the dates in the text.
The starting point of the task looks like this:
Advanced text semantics
Let's start with a quote:
HTML, Hypertext Markup Language is by default accessible, if used correctly.
CSS can also be used to make web sayfasıs more, or less, accessible.
Chemical Formulae: H2O (Water), C2H6O (Ethanol).
Dates: December 25th 2019 (Christmas Day), November 2nd 2019 (Día de los
Muertos).
Here's the underlying code for this starting point:
HTML
İngilizce (ABD)
Note: To get help, read our Test your skills usage guide. You can also reach out to us using one of our
communication channels.
15.10.2026 20:23
Yeteneklerinizi test edin: Gelişmiş HTML metni - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Advanced_HTML_text
1/2

<h1>Advanced text semantics</h1>
<p>Let's start with a quote:</p>
<p>
HTML, Hypertext Markup Language is by default accessible, if used correctly.
</p>
<p>CSS can also be used to make web sayfasıs more, or less, accessible.</p>
<p>Chemical Formulae: H2O (Water), C2H6O (Ethanol).</p>
<p>
Dates: December 25th 2019 (Christmas Day), November 2nd 2019 (Día de los
Muertos).
</p>
The updated content should look like this:
Advanced text semantics
Let's start with a quote:
HTML, Hypertext Markup Language is by default accessible, if used
correctly.
CSS, Cascading Style Sheets, can also be used to make web sayfasıs more, or less,
accessible.
Chemical Formulae: H2O (Water), C2H6O (Ethanol).
th
d
Click here to show the solution
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
15.10.2026 20:23
Yeteneklerinizi test edin: Gelişmiş HTML metni - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Advanced_HTML_text
2/2


---

# Türkçe çeviri

HTML
Challenge: Letter markup
Meydan okuma: Bir mektubu işaretleme
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
We all learn to write a letter sooner or later; it is also a useful example to test our text formatting skills. In this challenge,
we give you a letter to mark up as a test for your HTML text formatting skills and knowledge of the HTML <head>
contents.
Starting point
To begin, click the Play button in the code sample panel below to open the provided body text in the MDN Playground.
You'll follow the instructions in the sections that follow to mark up the text appropriately.
HTML
Dr. Eleanor Gaye
Awesome Science faculty
University of Awesome
Bobtown, CA 99999,
USA
Tel: 123-456-7890
Email: no_reply@example.com
20 January 2016
Miss Eileen Dover
4321 Cliff Top Edge
Dover, CT9 XXX
UK
Re: Eileen Dover university application
Dear Eileen,
Thank you for your recent application to join us at the University of
Awesome's science faculty to study as part of your
PhD (Doctor of Philosophy) next year. I will answer your
questions one by one, in the following sections.
Starting dates
We are happy to accommodate you starting your study with us at any time,
İngilizce (ABD)
15.10.2026 20:23
Meydan okuma: Bir mektubu işaretleme - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Marking_up_a_letter
1/5

however it would suit us better if you could start at the beginning of a
semester; the start dates for each one are as follows:
First semester: 9 September 2016
Second semester: 15 January 2017
Third semester: 2 May 2017
Please let me know if this is ok, and if so which start date you would
prefer.
Subjects of study
At the Awesome Science Faculty, we have a pretty open-minded research
facility — as long as the subjects fall somewhere in the realm of science
and technology. You seem like an intelligent, dedicated researcher, and
just the kind of person we'd like to have on our team. Saying that, of the
ideas you submitted we were most intrigued by are as follows, in order of
priority:
Turning H2O into wine, and the health benefits of Resveratrol
(C14H12O3).
Measuring the effect on performance of funk bass players at temperatures
exceeding 30°C (86°F), when the audience size exponentially increases
(effect of 3 × 103 increasing to 3 × 104).
HTML, Hypertext Markup Language, and CSS,
Cascading Style Sheets, constructs for representing musical scores.
So please can you provide more information on each of these subjects,
including how long you'd expect the research to take, required staff and
other resources, and anything else you think we'd need to know? Thanks.
Exotic dance moves
Yes, you are right! As part of my post-doctorate work, I
did study exotic tribal dances. To answer your question, my
favorite dances are as follows, with definitions:
Polynesian chicken dance
A little known but very influential dance dating back as far as
300 BCE, a whole village would
dance around in a circle like chickens, to encourage their livestock to
be "fruitful".
Icelandic brownian shuffle
Before the Icelanders developed fire as a means of getting warm, they
used to practice this dance, which involved huddling close together in a
circle on the floor, and shuffling their bodies around in imperceptibly
tiny, very rapid movements. One of my fellow students used to say that
he thought this dance inspired modern styles such as Twerking.
Arctic robot dance
15.10.2026 20:23
Meydan okuma: Bir mektubu işaretleme - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Marking_up_a_letter
2/5

An interesting example of historic misinformation, English explorers in
the 1960s believed to have discovered a new dance style characterized by
"robotic", stilted movements, being practiced by inhabitants of Northern
Alaska and Canada. Later on however it was discovered that they were
just moving like this because they were really cold.
Yours sincerely,
Dr Eleanor Gaye
University of Awesome motto: Be awesome to each other. --
The memoirs of Bill S Preston, Esq.
Dr. Eleanor Gaye Awesome Science faculty University of Awesome Bobtown, CA 99999, USA Tel:
123-456-7890 Email: no_reply@example.com 20 January 2016 Miss Eileen Dover 4321 Cliff Top
Edge Dover, CT9 XXX UK Re: Eileen Dover university application Dear Eileen, Thank you for your
recent application to join us at the University of Awesome's science faculty to study as part of your
PhD (Doctor of Philosophy) next year. I will answer your questions one by one, in the following
sections. Starting dates We are happy to accommodate you starting your study with us at any time,
however it would suit us better if you could start at the beginning of a semester; the start dates for
each one are as follows: First semester: 9 September 2016 Second semester: 15 January 2017 Third
semester: 2 May 2017 Please let me know if this is ok, and if so which start date you would prefer.
Subjects of study At the Awesome Science Faculty, we have a pretty open-minded research facility —
as long as the subjects fall somewhere in the realm of science and technology. You seem like an
Project brief
For this project, your task is to mark up a letter that needs to be hosted on a university intranet. The letter is a response
from a research fellow to a prospective PhD student concerning their application to the university.
Block/structural semantics
Add an appropriate HTML structure including doctype, and <html> , <head>  and <body>  elements.
In general, the letter should be marked up as an organization of başlıks and paragrafs, except for the
addresses mentioned in the next bullet. There is one top level başlık (the "Re:" line) and three second level
başlıks.
Put the two addresses inside <address>  elements. Each line of the address should sit on a new line, but not be
in a new paragraf.
Use an appropriate list type to mark up the semester start dates, study subjects, and exotic dances.
Inline semantics
The names of the sender and receiver (and Tel and Email) should be marked up with strong importance.
The four dates in the document should be wrapped in appropriate elements containing machine-readable dates.
The first address and first date in the letter should have a class  attribute value of sender-column  set on them.
The CSS you'll add later will cause these to be right aligned, as it should be in the case in a classic letter layout.
Mark up the following five acronyms/abbreviations in the main text of the letter — "PhD," "HTML," "CSS," "BCE,"
and "Esq." — to provide expansions of each one.
15.10.2026 20:23
Meydan okuma: Bir mektubu işaretleme - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Marking_up_a_letter
3/5

The six sub/superscripts should be marked up appropriately — in the chemical formulae, and the numbers 103
and 104 (they should be 10 to the power of 3 and 4, respectively).
Mark up at least two other appropriate words in the text with strong importance/emphasis.
Mark up the university motto quote and citation with appropriate elements.
The head of the document
The character set of the document should be set as utf-8  using the appropriate <meta>  tag.
The author of the letter should be specified in an appropriate <meta>  tag.
You should set the language of the document as en-US .
Include the following text inside a document title element: "Awesome science application correspondence".
The following CSS should be included inside an appropriate element inside the head:
CSS
body {
font: 1.2em / 1.5 system-ui;
}
.sender-column {
text-align: right;
}
h1 {
font-size: 1.5em;
}
h2 {
font-size: 1.3em;
}
Hints and tips
Use the 
 to validate your HTML. Award yourself bonus points if it validates.
You don't need to know any CSS to do this assignment. You just need to put the provided CSS inside an HTML
element.
Example
The following live example shows what the letter should look like after being marked up. If you are getting stuck on how
to achieve some of this, see the solution below the live example.
W3C HTML validator
15.10.2026 20:23
Meydan okuma: Bir mektubu işaretleme - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Marking_up_a_letter
4/5

Dr. Eleanor Gaye
Awesome Science faculty
University of Awesome
Bobtown, CA 99999,
USA
Tel: 123-456-7890
Email: no_reply@example.com
20 January 2016
Miss Eileen Dover
4321 Cliff Top Edge
Dover, CT9 XXX
UK
Re: Eileen Dover university application
Dear Eileen,
Click here to show the solution
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
15.10.2026 20:23
Meydan okuma: Bir mektubu işaretleme - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Marking_up_a_letter
5/5


---

# Türkçe çeviri

HTML
Belgeleri yapılandırma
Belgeleri yapılandırma
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
In addition to defining individual parts of your page (such as "a paragraf" or "an image"), HTML also boasts a number
of block level elements used to define areas of your website such as "the header", "the navigation menu", or "the main
content column". This article looks into how to plan a basic website structure, and write the HTML to represent this
structure.
Önkoşullar:
Basic HTML familiarity, as covered in Basic HTML Syntax. Text-level semantics such as
başlıks and paragrafs and lists.
Learning
outcomes:
The common HTML semantic structural elements, for example <main> , <section> ,
<article> , <header> , <nav> , and <footer> , and how to use them correctly.
The need to use semantic elements in appropriate places, rather than just using <div>
elements wherever a block-level container is required, and the benefits of this (such as
improved accessibility).
Basic sections of a document
Webpages can and will look pretty different from one another, but they all tend to share similar standard components,
unless the page is displaying a fullscreen video or game, is part of some kind of art project, or is just badly structured:
header:
Usually a big strip across the top with a big başlık, logo, and perhaps a tagline. This usually stays the same from
one page of a website to another.
navigation bar:
Links to the site's main sections; usually represented by menu buttons, links, or tabs. Like the header, this content
usually remains consistent from one webpage to another — having inconsistent navigation on your website will just
lead to confused, frustrated users. Many web designers consider the navigation bar to be part of the header rather
than an individual component, but that's not a requirement; in fact, some also argue that having the two separate is
better for accessibility, as ekran okuyucus can read the two features better if they are separate.
main content:
A big area in the center that contains most of the unique content of a given webpage, for example, the video you want
to watch, or the main story you're reading, or the map you want to view, or the news headlines, etc. This is the one
part of the website that definitely will vary from page to page!
sidebar:
Some peripheral info, links, quotes, ads, etc. Usually, this is contextual to what is contained in the main content (for
example on a news article page, the sidebar might contain the author's bio, or links to related articles) but there are
İngilizce (ABD)
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
1/11

also cases where you'll find some recurring elements like a secondary navigation system.
footer:
A strip across the bottom of the page that generally contains fine print, copyright notices, or contact info. It's a place
to put common information (like the header) but usually, that information is not critical or secondary to the website
itself. The footer is also sometimes used for SEO purposes, by providing links for quick access to popular content.
A "typical website" could be structured something like this:
HTML for structuring content
The example shown above isn't pretty, but it is perfectly fine for illustrating a typical website layout example. Some
websites have more columns, some are a lot more complex, but you get the idea. With the right CSS, you could use
pretty much any elements to wrap around the different sections and get it looking how you wanted, but as discussed
before, we need to respect semantics and use the right element for the right job.
This is because visuals don't tell the whole story. We use color and font size to draw sighted users' attention to the most
useful parts of the content, like the navigation menu and related links, but what about visually impaired people for
example, who might not find concepts like "pink" and "large font" very useful?
Note: The image above illustrates the main sections of a document, which you can define with HTML. However,
the appearance of the page shown here — including the layout, colors, and fonts — is achieved by applying
CSS to the HTML.
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
2/11

In your HTML code, you can mark up sections of content based on their functionality — you can use elements that
represent the sections of content described above unambiguously, and assistive technologies like ekran okuyucus can
recognize those elements and help with tasks like "find the main navigation", or "find the main content." As we
mentioned earlier in the course, there are a number of consequences of not using the right element structure and
semantics for the right job.
To implement such semantic mark up, HTML provides dedicated tags that you can use to represent such sections, for
example:
header: <header> .
navigation bar: <nav> .
main content: <main> , with various content subsections represented by <article> , <section> , and <div>
elements.
sidebar: <aside> ; often placed inside <main> .
footer: <footer> .
Exploring the code for our example
The example seen above is represented by the following code (you can also 
,
and 
). We'd like you to look at the listing below to see what parts make up each section of the
visual output.
HTML
<!doctype html>
<html lang="en-US">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width" />
<title>My page title</title>
<link
href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300|Sonsie+One"
rel="stylesheet" />
<link rel="stylesheet" href="style.css" />
</head>
<body>
<!-- The main header used across all the pages of our website -->
<header>
<h1>Header</h1>
</header>
Note:
 are colorblind; or, to put it another way, approximately 1 in
every 12 men and 1 in every 200 women. Blind and visually impaired people represent roughly 4-5% of the
world population (in 2015 there were 
, while the total
population was 
).
Roughly 8% of men and 0.5% of women
940 million people with some degree of vision loss
around 7.5 billion
find the code in our GitHub repository
view the example live
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
3/11

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Our team</a></li>
<li><a href="#">Projects</a></li>
<li><a href="#">Contact</a></li>
</ul>
<!-- A Search form: another common non-linear
way to navigate through a site. -->
<form>
<input type="search" name="q" placeholder="Search query" />
<input type="submit" value="Go!" />
</form>
</nav>
<!-- Our page's main content -->
<main>
<!-- An article -->
<article>
<h2>Article başlık</h2>
<p>
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Donec a diam
lectus. Set sit amet ipsum mauris. Maecenas congue ligula as quam
viverra nec consectetur ant hendrerit. Donec et mollis dolor. Praesent
et diam eget libero egestas mattis sit amet vitae augue. Nam tincidunt
congue enim, ut porta lorem lacinia consectetur.
</p>
<section>
<h3>Subsection</h3>
<p>
Donec ut librero sed accu vehicula ultricies a non tortor. Lorem
ipsum dolor sit amet, consectetur adipisicing elit. Aenean ut
gravida lorem. Ut turpis felis, pulvinar a semper sed, adipiscing id
dolor.
</p>
<p>
Pelientesque auctor nisi id magna consequat sagittis. Curabitur
dapibus, enim sit amet elit pharetra tincidunt feugiat nist
imperdiet. Ut convallis libero in urna ultrices accumsan. Donec sed
odio eros.
</p>
</section>
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
4/11

<section>
<h3>Another subsection</h3>
<p>
Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus. Cum
soclis natoque penatibus et manis dis parturient montes, nascetur
ridiculus mus. In rutrum accumsan ultricies. Mauris vitae nisi at
sem facilisis semper ac in est.
</p>
<p>
Vivamus fermentum semper porta. Nunc diam velit, adipscing ut
tristique vitae sagittis vel odio. Maecenas convallis ullamcorper
ultricied. Curabitur ornare, ligula semper consectetur sagittis,
nisi diam iaculis velit, is fringille sem nunc vet mi.
</p>
</section>
</article>
<!-- the aside content can also be nested within the main content -->
<aside>
<h2>Related</h2>
<ul>
<li><a href="#">Oh I do like to be beside the seaside</a></li>
<li><a href="#">Oh I do like to be beside the sea</a></li>
<li><a href="#">Although in the North of England</a></li>
<li><a href="#">It never stops raining</a></li>
<li><a href="#">Oh well…</a></li>
</ul>
</aside>
</main>
<!-- The footer that is used across all the pages of our website -->
<footer>
<p>©Copyright 2050 by nobody. All rights reversed.</p>
</footer>
</body>
</html>
Take some time to look over the code and understand it — the comments inside the code should also help you to
understand it. We aren't asking you to do much else in this article, because the key to understanding document layout is
writing a sound HTML structure, and then laying it out with CSS. We'll wait for this until you start to study CSS layout as
part of the CSS topic.
HTML layout elements in more detail
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
5/11

It's good to understand the overall meaning of all the HTML sectioning elements in detail — this is something you'll work
on gradually as you start to get more experience with web development. You can find a lot of detail by reading our HTML
element reference. For now, these are the main definitions that you should try to understand:
<main>  is for content unique to this page. Use <main>  only once per page, and put it directly inside <body> .
Ideally this shouldn't be nested within other elements.
<article>  encloses a block of related content that makes sense on its own without the rest of the page (for
example, a single blog post).
<section>  is similar to <article> , but it is more for grouping together a single part of the page that constitutes
one single piece of functionality (like a mini map, or a set of article headlines and summaries), or a theme. It's
considered best practice to begin each section with a başlık; also note that you can break <article> s up into
different <section> s, or <section> s up into different <article> s, depending on the context.
<aside>  contains content that is not directly related to the main content but can provide additional information
indirectly related to it (glossary entries, author biography, related links, etc.).
<header>  represents a group of introductory content. If it is a child of <body>  it defines the global header of a
webpage, but if it's a child of an <article>  or <section>  it defines a specific header for that section (try not to
confuse this with titles and başlıks).
<nav>  contains the main navigation functionality for the page. Secondary links, etc., would not go in the
navigation.
<footer>  represents a group of end content for a page.
Each of the aforementioned elements can be clicked on to read the corresponding article in the "HTML element
reference" section, providing more detail about each one.
Non-semantic wrappers
Sometimes you'll come across a situation where you can't find an ideal semantic element to group some items together
or wrap some content. Sometimes you might want to just group a set of elements together to affect them all as a single
entity with some CSS or JavaScript. For cases like these, HTML provides the <div>  and <span>  elements. You should
use these preferably with a suitable class  attribute, to provide some kind of label for them so they can be easily
targeted.
<span>  is an inline non-semantic element, which you should only use if you can't think of a better semantic text element
to wrap your content, or don't want to add any specific meaning. For example:
HTML
<p>
The King walked drunkenly back to his room at 01:00, the beer doing nothing to
aid him as he staggered through the door.
<span class="editor-note">
[Editor's note: At this point in the play, the lights should be down low].
</span>
</p>
In this case, the editor's note is supposed to merely provide extra direction for the director of the play; it is not supposed
to have extra semantic meaning. For sighted users, CSS would perhaps be used to distance the note slightly from the
main text.
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
6/11

<div>  is a block level non-semantic element, which you should only use if you can't think of a better semantic block
element to use, or don't want to add any specific meaning. For example, imagine a shopping cart widget that you could
choose to pull up at any point during your time on an e-commerce site:
HTML
<div class="shopping-cart">
<h2>Shopping cart</h2>
<ul>
<li>
<p>
<a href=""><strong>Silver earrings</strong></a>: $99.95.
</p>
<img src="../products/3333-0985/thumb.png" alt="Silver earrings" />
</li>
<li>…</li>
</ul>
<p>Total cost: $237.89</p>
</div>
This isn't really an <aside> , as it doesn't necessarily relate to the main content of the page (you want it viewable from
anywhere). It doesn't even particularly warrant using a <section> , as it isn't part of the main content of the page. So a
<div>  is fine in this case. We've included a başlık as a signpost to aid ekran okuyucu users in finding it.
Line breaks and horizontal rules
Two elements that you'll use occasionally and will want to know about are <br>  and <hr> .
<br>: the line break element
<br>  creates a line break in a paragraf; it is the only way to force a rigid structure in a situation where you want a
series of fixed short lines, such as in a postal address or a poem. For example:
HTML
<p>
There once was a man named O'Dell<br />
Warning: Divs are so convenient to use that it's easy to use them too much. As they carry no semantic value,
they just clutter your HTML code. Take care to use them only when there is no better semantic solution and try
to reduce their usage to the minimum otherwise you'll have a hard time updating and maintaining your
documents.
Note: Scrimba's 
MDN learning partner interactive tutorial provides a useful recap of semantic
markup and why you should use it, plus a challenge that tests your ability to improve an HTML codebase with
semantic elements.
Semantic HTML
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
7/11

Who loved to write HTML<br />
But his structure was bad, his semantics were sad<br />
and his markup didn't read very well.
</p>
Without the <br>  elements, the paragraf would just be rendered in one long line (as we said earlier in the course,
HTML ignores most whitespace); with <br>  elements in the code, the markup renders like this:
There once was a man named O'Dell
Who loved to write HTML
But his structure was bad, his semantics were sad
and his markup didn't read very well.
<hr>: the thematic break element
<hr>  elements create a horizontal rule in the document that denotes a thematic change in the text (such as a change in
topic or scene). Visually it just looks like a horizontal line. As an example:
HTML
<p>
Ron was backed into a corner by the marauding netherbeasts. Scared, but
determined to protect his friends, he raised his wand and prepared to do
battle, hoping that his distress call had made it through.
</p>
<hr />
<p>
Meanwhile, Harry was sitting at home, staring at his royalty statement and
pondering when the next spin off series would come out, when an enchanted
distress letter flew through his window and landed in his lap. He read it
hazily and sighed; "better get back to work then", he mused.
</p>
Would render like this:
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
8/11

Ron was backed into a corner by the marauding netherbeasts. Scared, but determined to protect his
friends, he raised his wand and prepared to do battle, hoping that his distress call had made it through.
Meanwhile, Harry was sitting at home, staring at his royalty statement and pondering when the next
spin off series would come out, when an enchanted distress letter flew through his window and
landed in his lap. He read it hazily and sighed; "better get back to work then", he mused.
Structuring a basic website
The next stage after planning out the structure of a single webpage is to plan out the structure of a whole multi-page
website, including how they should be arranged and link to one another for the best possible user experience. This is
called Information architecture.
In a large, complex website, a lot of planning can go into this process, but for a basic website with a few pages, it can be
a quick and fun exercise.
The process might look like this:
1. You'll have a few elements common to most (if not all) pages — such as the navigation menu, and the footer
content. If your site is for a business, for example, it's a good idea to have your contact information available in
the footer on each page. Note down what you want to have common to every page. For example:
Header:
Title and logo
Site language chooser
Navigation menu
Footer:
Copyright notice
Link to terms and conditions, contact details, and accessibility policy
2. Sonraki, draw a rough sketch of what you might want the structure of each page to look like (it might look like our
simple website above). Note what each block is going to be.
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
9/11

Header
Footer
Main
content
1 or 2
sidebars,
depending on
page
3. Now, brainstorm all the other (not common to every page) content you want to have on your website. For
example:
Flights
Accommodation
Transport
Things to do
Special offers
Popular holiday packages, for example winter sun, skiing
Search results
Reviews
Visa/entry requirements
Currency
Languages and culture
Buy holidays
4. Sonraki, try to sort all these content items into groups, to give you an idea of what parts might live together on
different pages. This is very similar to a technique called Card sorting.
Search
Flights
Accommodation
Transport
Things to do
Special offers
Popular holidays
Winter sun
Skiing
Search results
Reviews
Country-specific info
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
10/11

Visa/entry requirements
Currency
Languages and culture
Buy holidays
5. Now try to sketch a rough sitemap — have a box for each page on your site, and draw lines to show the typical
workflow between pages. The homepage will probably be in the top or at the center, and link to most if not all of
the others. Most of the pages in a small site should be available from the main navigation, although there are
exceptions. You might also want to include notes about how things might be presented.
Homepage
Link to more special offers, country-
specific pages, shopping cart
Search menu
Show specials on front page
Search
results
Country
info
Special
offers
Holiday
purchase flow
Shopping cart, enter address, pay, etc.
Try carrying out the above exercise for a website of your own creation. What would you like to make a site about? As a
stretch goal, use the HTML knowledge you've gained so far to create a few of the pages on the site. You could use our
 as a starting point.
Summary
At this point, you should have a better idea about how to structure a web sayfası/site. In the next article of this module,
we'll look at how to create hyperlinks, one of the fundamental features of the web.
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
basic HTML template
15.10.2026 20:23
Belgeleri yapılandırma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
11/11


---

# Türkçe çeviri

HTML
Bağlantılar oluşturma
Bağlantılar oluşturma
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
Links (also known as hyperlinks) are really important — they are what makes the Web a web. This article shows the
syntax required to make a link, and discusses link best practices.
Önkoşullar:
Basic HTML familiarity, as covered in Basic HTML Syntax. Text-level semantics such as
başlıks and paragrafs and lists.
Learning
outcomes:
Understand why links are the fundamental feature of the web. There is no web without
links.
The href  attribute.
Absolute and relative paths, and when to use them.
Path syntax in detail — slashes, single dot, and double dot.
Link states and why they are important — :hover , :focus , :visited , and
:active .
Inline and block-level links.
Understanding the benefits of writing good link text, such as better accessibility for
ekran okuyucu users, and potential positive SEO effects.
What is a hyperlink?
Hyperlinks are features of an HTML document that, when clicked or otherwise activated, cause the tarayıcı to navigate
to other documents or resources, sometimes specific parts of documents. Hyperlinks are one of the most exciting
innovations the Web has to offer. They've been a feature of the Web since the beginning, and are what makes the Web a
web. Each resource on the web has an address, known as a URL (Uniform Resource Locator), which hyperlinks point to.
For example, the BBC homepage contains many links that point not only to multiple news stories, but also different areas
of the site (navigation functionality), login/registration pages (user tools), and more.
İngilizce (ABD)
Note: A URL can point to HTML files, text files, images, text documents, video and audio files, or anything else
that lives on the Web. If the web tarayıcı doesn't know how to display or handle the file, it will ask you if you
want to open the file (in which case the duty of opening or handling the file is passed to a suitable native app on
the device) or download the file (in which case you can try to deal with it later on).
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
1/15

Anatomy of a link
A basic link is created by wrapping the text or other content inside an <a>  element and using the href  attribute, also
known as a Hypertext Reference, or target, that contains the web address.
HTML
<p>
I'm creating a link to
<a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>.
</p>
This gives us the following result:
I'm creating a link to 
.
Block level links
As mentioned before, almost any content can be made into a link, even block-level elements. If you want to make a
başlık element a link then wrap it in an anchor ( <a> ) element as shown in the following code snippet:
the Mozilla homepage
Note: Scrimba's 
MDN learning partner scrim provides an interactive demonstration of how to create
links using HTML, plus a challenge to get you creating your own links.
Anchor tags
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
2/15

HTML
<a href="https://developer.mozilla.org/en-US/">
<h1>MDN Web Docs</h1>
</a>
<p>
Documenting web technologies, including CSS, HTML, and JavaScript, since 2005.
</p>
This turns the başlık into a link:
MDN Web Docs
Documenting web technologies, including CSS, HTML, and JavaScript, since 2005.
Image links
To turn an image into a link, wrap the <img>  element with an <a>  element. The example below uses a relative path to
reference a locally stored SVG image file.
HTML
<a href="https://developer.mozilla.org/en-US/">
<img src="mdn_logo.svg" alt="MDN Web Docs" />
</a>
This makes the MDN logo a link:
Adding supporting information with the title attribute
Note: You'll find out more about using images on the Web in a future article.
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
3/15

You may also want to add a title  attribute to your links. The title contains additional information about the link, such as
which kind of information the page contains, or things to be aware of on the website.
HTML
<p>
I'm creating a link to
<a
href="https://www.mozilla.org/en-US/"
title="The best place to find more information about Mozilla's mission and how to
contribute">
the Mozilla homepage</a
>.
</p>
This gives us the following result and hovering over the link displays the title as a tooltip:
I'm creating a link to the Mozilla homepage.
Creating your own example links
OK, now it's your turn!
1. Click "Play" in the code block below to edit the example in the MDN Playground, or make a copy of our 
 and copy the below code into there.
2. Link the "Red squirrel" and "Eastern gray squirrel" text to Wikipedia pages that describe the relevant species.
Give each link a title  attribute equal to the species' scientific name.
3. Link the "Wikipedia Squirrel page" text to the main Wikipedia page for squirrels.
If you make a mistake, you can clear your work using the Reset button in the MDN Playground. If you get really stuck,
you can view the solution below the code block.
HTML
Note: A link title is only revealed on mouse hover, which means that people relying on keyboard controls or
touchscreens to navigate web sayfasıs will have difficulty accessing title information. If a title's information is
truly important to the usability of the page, then you should present it in a manner that will be accessible to all
users, for example by putting it in the regular text.
getting
started template
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
4/15

<h1>Squirrels</h1>
<p>
Squirrels are commonly thought of as tree-dwelling mammals, but the squirrel
family extends far beyond that to include ground-dwelling rodents such as
chipmunks and prairie dogs, and flying squirrels.
</p>
<p>Two of the most common and best-known squirrel species are the:</p>
<ul>
<li>Red squirrel</li>
<li>Eastern gray squirrel</li>
</ul>
<p>
For a good starting point on squirrel information, see the Wikipedia Squirrel
page.
</p>
Squirrels
Squirrels are commonly thought of as tree-dwelling mammals, but the squirrel family extends far
beyond that to include ground-dwelling rodents such as chipmunks and prairie dogs, and flying
squirrels.
Two of the most common and best-known squirrel species are the:
Red squirrel
Eastern gray squirrel
For a good starting point on squirrel information, see the Wikipedia Squirrel page.
Click here to show the solution
A quick primer on URLs and paths
Link targets are URLs. A URL, or Uniform Resource Locator, is a string of text that defines where something is located on
the Web. For example, Mozilla's English homepage is located at https://www.mozilla.org/en-US/ .
A web server receives requests for URLs and responds with the appropriate resource. Most resources are stored as files
on the server's file system, so the URLs for these resources often resemble file paths.
Note: File paths and URLs are not the same thing, but for now, we'll talk about them like they are to facilitate
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
5/15

Let's look at an example server directory structure:
The root of this directory structure is called creating-hyperlinks . When working locally with a website, you'll have
one directory that contains the entire site. Inside the root, we have an index.html  file and a contacts.html . In a real
website, index.html  would be our home page or landing page (a web sayfası that serves as the entry point for a website
or a particular section of a website).
There are also two directories inside our root — pdfs  and projects . These each have a single file inside them — a
PDF ( project-brief.pdf ) and an index.html  file, respectively. Note that you can have multiple index.html  files in
one project, as long as they're in different filesystem locations. The second index.html  would perhaps be the main
landing page for project-related information.
Let's look at some examples of links between some different files in this directory structure to demonstrate different path
types.
Same directory
If you want to include a hyperlink inside the top level index.html  pointing to contacts.html , you can specify the path
as just the filename that you want to link to, because it's in the same directory as the current file. The URL you would use
is contacts.html :
HTML
<p>
Want to contact a specific staff member? Find details on our
understanding. We'll discuss more about the differences in the how do URLs translate into file paths? section.
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
6/15

<a href="contacts.html">contacts page</a>.
</p>
You can also start a path to a file inside the same directory using a single dot followed by a slash: ./ . The following
example is equivalent to the previous one, but some people like to include the ./  anyway because they feel it provides
more clarity:
HTML
<p>
Want to contact a specific staff member? Find details on our
<a href="./contacts.html">contacts page</a>.
</p>
Moving down into subdirectories
If you want to include a hyperlink inside the top level index.html  pointing to projects/index.html , you need to go
down into the projects  directory before indicating the file you want to link to. This is done by specifying the directory's
name, then a forward slash, then the name of the file. The URL you can use is projects/index.html :
HTML
<p>Visit my <a href="projects/index.html">project homepage</a>.</p>
Moving back up into parent directories
If you want to include a hyperlink inside projects/index.html  pointing to pdfs/project-brief.pdf , you have to go
up a directory level, then back down into the pdfs  directory. To go up a directory, you use two dots — ..  — so the URL
is ../pdfs/project-brief.pdf :
HTML
<p>A link to my <a href="../pdfs/project-brief.pdf">project brief</a>.</p>
Linking relative to the root directory
Note: There are some instances in which including ./  in your path will make a difference, for example when
specifying paths for JavaScript module imports, but you don't need to worry about this for static HTML and CSS
links.
Note: You can combine multiple instances of these features into complex paths, if needed, for example:
../../../complex/path/to/my/file.html .
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
7/15

The above URLs work, but bear in mind that if you move either the linking file or the linked file to a different location, you
will break the link.
If you want to create a link to a specific location that won't break if you move the linking file, you can do so by putting a
single slash at the start of the path — this indicates that the path starts in the root directory of the site. For example, the
previous link inside projects/index.html  could be rewritten as:
HTML
<p>A link to my <a href="/pdfs/project-brief.pdf">project brief</a>.</p>
Now the path will always start from the root directory ( creating-hyperlinks ), travel to the pdfs  directory, and find
the project-brief.pdf  file. This will still work if you move the linking file to a different location, for example
a/b/c/d/e/index.html .
If you move the linked project-brief.pdf  file to a different location, you will still break the link.
Two terms you'll come across on the web are absolute path and relative path.
Absolute path: Points to a location defined by its absolute location in your site (or elsewhere on the web). For
example, you can create an absolute link that always points to the same location relative to the site root directory
using the single slash at the start of the path, as we saw earlier: /pdfs/project-brief.pdf .
Relative path: Points to a location that is relative to the file you are linking from. In our earlier example, we used
projects/index.html  to create a relative link between the current file and a file called index.html  that is
inside a projects  subdirectory. If you were to move the current file to a different location, the path would still be
relative to that file, but it would point to a different absolute location.
These terms are not always used consistently. For example, /pdfs/project-brief.pdf  is absolute with respect to the
current file's location, but relative to the domain name. A URL that includes the full domain name, such as
https://example.com/pdfs/project-brief.pdf , is absolute with respect to the entire web.
Linking with full URLs
You can specify a full URL as your path, which will always point to the same location on the web, no matter where it's
used. For example:
HTML
<a href="https://www.example.com/projects/">projects</a>
This link will always link to https://www.example.com/projects/ , even if your site is moved to a different domain.
Internal and external links
When a link points to a resource on your site, it is referred to as an internal link. When a link points to a resource on a
different site, it is called an external link.
When specifying an external link, you always have to include the full URL as the path, for example:
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
8/15

HTML
<a href="https://www.some-other-site.com">projects</a>
You can't reference a location on a different site with a path like /pdfs/project-brief.pdf  or projects/index.html ,
as they are both relative to a location on your own site, and the tarayıcı needs the website's domain name to be able to
find it.
When specifying an internal link, you can use a relative or absolute path, or a full URL. In our example, these links are
equivalent:
HTML
<a href="https://www.example.com/projects/">projects</a>
<a href="projects">projects</a>
We recommend the latter without the full domain name, because of portability. As we said earlier, if you specify
https://www.example.com/projects/ , it will always link to https://www.example.com/projects/ . If you then
move your website to a different domain, for example another-example.com , your full URL links will all need to be
changed. If you specify paths such as /projects , they will still work, as they are still relative to the directory structure.
Document fragments
It's possible to link to a specific part of an HTML document, known as a document fragment, rather than just to the top
of the document. Elements with an id  attribute in the document automatically create a document fragment that can be
linked to.
The most typical use case is linking to a specific başlık, which looks like this:
HTML
<h2 id="mailing_address">Mailing address</h2>
To link to that specific id , you include it at the end of the path, preceded by a hash/pound symbol ( # ), for example:
HTML
<p>
Want to write us a letter? Use our
<a href="contacts.html#mailing_address">mailing address</a>.
</p>
You can even use the document fragment reference on its own to link to another part of the current document:
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
9/15

HTML
<p>
The <a href="#mailing_address">company mailing address</a> can be found at the
bottom of this page.
</p>
How do URLs translate into file paths?
All the link targets we've seen so far are URLs, which get processed by a web server to find the relevant resource. No
web content can directly see the server's file system.
The server example we've looked at so far creates a static website. The server just takes the pathname part of the URL
and directly looks for the corresponding file in its file system.
If we start a web server (see How do you set up a local testing server?) using our sample site directory as the root, and
the website domain name is set to example.com , our pdfs/project-brief.pdf  file would be available at
https://www.example.com/pdfs/project-brief.pdf .
All links are resolved relative to the current document's URL, so:
For all pages on the https://example.com  domain, a link to /pdfs/project-brief.pdf  always creates a link
to https://www.example.com/pdfs/project-brief.pdf , whose pathname is /pdfs/project-brief.pdf .
The server looks for the pdfs  directory in the root directory, then looks for the project-brief.pdf  file inside
that directory.
A link to projects/index.html  would create a link to https://www.example.com/projects/index.html , but
only when included in a file inside the root directory, such as the top-level index.html  file, or contacts.html .
If you included it, for example, inside an HTML file at pdfs/index.html , it would link to
https://www.example.com/pdfs/projects/index.html , whose path name is /pdfs/projects/index.html ,
which doesn't exist, so you'd end up with a broken link.
The default index.html page
When referencing an index.html  file, you generally don't need to include the index.html  in the URL/path, because
web servers look for a default landing page called index.html  when a filename isn't specified.
Looking again at our projects/index.html  path example, we could just write the path as projects , and this would
create a link to https://www.example.com/projects/index.html . When navigating to the page, we could write the
URL as https://www.example.com/projects/  and it would still get us to the right place.
Note: Many servers generate content for a URL on-the-fly rather than retrieving it from a static file. If you use a
web framework, your source code directory may also be very different from what gets deployed to the server.
When working with your own website, you need to understand your build tools and server setup to know how
URLs get mapped to your source files.
Note: The trailing slash ( / ) at the end of the URL is important. With it, a relative link to contacts.html  inside
projects/index.html  would resolve to https://www.example.com/projects/contacts.html  (which is in
the same directory). Without it, the URL would be treated as a file, and the relative link would resolve to
https://www.example.com/contacts.html  (which is one directory up).
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
10/15

Link best practices
There are some best practices to follow when writing links. Let's look at these now.
Use clear link wording
It's easy to throw links up on your page. That's not enough. We need to make our links accessible to all readers,
regardless of their current context and which tools they prefer. For example:
Screen reader users like jumping around from link to link on the page, and reading links out of context.
Search engines use link text to index target files, so it is a good idea to include keywords in your link text to
effectively describe what is being linked to.
Visual readers skim over the page rather than reading every word, and their eyes will be drawn to page features
that stand out, like links. They will find descriptive link text useful.
Let's look at a specific example:
Good link text: 
HTML
<p><a href="https://www.firefox.com/en-US/">Download Firefox</a></p>
Bad link text: 
 to download Firefox
HTML
<p>
<a href="https://www.firefox.com/en-US/">Click here</a> to download Firefox
</p>
Other tips:
Don't repeat the URL as part of the link text — URLs look ugly, and sound even uglier when a ekran okuyucu reads
them out letter by letter.
Don't say "link" or "links to" in the link text — it's just noise. Screen readers tell people there's a link. Visual users
will also know there's a link, because links are generally styled in a different color and underlined (this convention
generally shouldn't be broken, as users are used to it).
Keep your link text as short as possible — this is helpful because ekran okuyucus need to interpret the entire link
text.
Minimize instances where multiple copies of the same text are linked to different places. This can cause problems
for ekran okuyucu users, if there's a list of links out of context that are labeled "click here", "click here", "click
here".
 — some
automatically redirect to the URL with a trailing slash, while some serve the same index.html  without
redirecting. The latter behavior can break relative links.
Different web servers handle a URL like https://www.example.com/projects  differently
Download Firefox
Click here
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
11/15

Linking to non-HTML resources — leave clear signposts
When linking to a resource that will not be opened in the current page as a "normal navigation", you should add clear
wording to the link text about what is going to happen. For example, if you're downloading or streaming a resource, or if
the link is going to open a popup or perform some other potentially unexpected effect, this should be stated in the text.
This is important for users on low bandwidth connections, who might want to avoid downloading assets of multiple
megabytes. It also helps to set up expectations for ekran okuyucu users, who may not be aware of what's happening
otherwise.
Let's look at some examples, to see what kind of text can be used here:
HTML
<p>
<a href="/large-report.pdf" download>
Download the sales report (PDF, 10MB)
</a>
</p>
<p>
<a href="https://www.example.com/video-stream/" target="_blank">
Watch the video (stream opens in separate tab, HD quality)
</a>
</p>
Use the download attribute when linking to a download
When you are linking to a resource that's to be downloaded rather than opened in the tarayıcı, you can use the
download  attribute to provide a default save filename. Here's an example with a download link to the latest Windows
version of Firefox:
HTML
<a
href="https://download.mozilla.org/?product=firefox-latest-ssl&os=win64&lang=en-US"
download="firefox-latest-64bit-installer.exe">
Download Latest Firefox for Windows (64-bit) (English, US)
</a>
When to open links in a new tab
Links by default open in the same tab as the page they are on, which allows the user to navigate back to the previous
page using the tarayıcı's back button. However, many sites (including MDN) choose to open certain links, especially
external links, in a new tab. This is done by setting the target  attribute to "_blank" .
HTML
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
12/15

Firefox is developed by the
<a href="https://www.mozilla.org/en-US/" target="_blank">Mozilla Foundation</a>.
Whether or not to open links in a new tab should be a conscious decision, based on user experience design
considerations. Here are some things to think about:
Opening links in a new tab presents the two documents simultaneously, which is useful for a "parallel" navigation
experience. On the other hand, links that open in the same tab are more like a continuation of the current page.
Opening links in a new tab can be disorienting for users who are accustomed to using the back button.
Even when links are opened in the same tab by default, users can still choose to open them in a new tab, using
keyboard shortcuts or context menu options. On the other hand, links that open in a new tab are hard to open in
the same tab.
Screen reader users may be confused by links that open in a new tab, as they may not realize that the new tab
has opened, and they may lose context about their location on the page.
A common approach is to open external links in new tabs and internal links in the same tab. Some designers prefer to
open all links in the same tab. If you do open links in new tabs, then it is recommended that you provide cues for these
links, such as an icon next to the link text.
Creating a navigation menu
For this exercise, we'd like you to link some pages together with a navigation menu to create a multipage website. This is
one common way in which a website is created — the same page structure is used on every page, including the same
navigation menu, so when links are clicked it gives the impression that you are staying in the same place, and different
content is being brought up.
You'll need to make local copies of the following four pages, all in the same directory. For a complete file list, see the
 directory:
You should:
1. Add an unordered list in the indicated place on one page that includes the names of the pages to link to. A
navigation menu is usually just a list of links, so this is semantically OK.
2. Change each page name into a link to that page.
3. Copy the navigation menu across to each page.
4. On each page, remove just the link to that same page — it's confusing and unnecessary for a page to include a
link to itself. And, the lack of a link acts a good visual reminder of which page you are currently on.
The finished example should look similar to the following page:
navigation-menu-start
index.html
projects.html
pictures.html
social.html
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
13/15

Email links
It's possible to create links or buttons that, when clicked, open a new outgoing email message rather than linking to a
resource or page. This is done using the <a>  element and the mailto:  URL scheme.
In its most basic and commonly used form, a mailto:  link indicates the email address of the intended recipient. For
example:
HTML
<a href="mailto:nowhere@mozilla.org">Send email to nowhere</a>
This results in a link that looks like this: Send email to nowhere.
In fact, the email address is optional. If you omit it and your href  is "mailto:", a new outgoing email window will be
opened by the user's email client with no destination address. This is often useful as "Share" links that users can click to
send an email to an address of their choosing.
Specifying details
In addition to the email address, you can provide other information. In fact, any standard mail header fields can be
added to the mailto  URL you provide. The most commonly used of these are "subject", "cc", and "body" (which is not a
Note: If you get stuck, or aren't sure if you have got it right, you can check the 
directory to see the correct answer.
navigation-menu-marked-up
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
14/15

true header field, but allows you to specify a short content message for the new email). Each field and its value is
specified as a query term.
Here's an example that includes a cc, bcc, subject and body:
HTML
<a
href="mailto:nowhere@mozilla.org?
cc=name2@rapidtables.com&bcc=name3@rapidtables.com&subject=The%20subject%20of%20the%20email&bod
y=The%20body%20of%20the%20email">
Send mail with cc, bcc, subject and body
</a>
Here are a few other sample mailto  URLs:
mailto:
mailto:nowhere@mozilla.org
mailto:nowhere@mozilla.org,nobody@mozilla.org
mailto:nowhere@mozilla.org?cc=nobody@mozilla.org
mailto:nowhere@mozilla.org?cc=nobody@mozilla.org&subject=This%20is%20the%20subject
Summary
That's it for links, for now anyway! You'll return to links later on in the course when you start to look at styling them. Sonraki
up, we'll give you some tests that you can use to check how well you've understood and retained the information we've
provided on links.
Önceki
Genel Bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
Note: The values of each field must be URL-encoded with non-printing characters (invisible characters like
tabs, carriage returns, and page breaks) and spaces percent-escaped. Also, note the use of the question mark
( ? ) to separate the main URL from the field values, and ampersands (&) to separate each field in the mailto:
URL. This is standard URL query notation. Read The GET method to understand what URL query notation is
more commonly used for.
15.10.2026 20:23
Bağlantılar oluşturma - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links
15/15


---

# Bilgini sınayın: Bağlantılar

Bilgini sınayın: Bağlantılar - Web geliştirmeyi öğren | MDN

Test: HTML testleri dizini

Test: Bağlantılar

English (US)

Bilgini sınayın: Bağlantılar

Önceki

Genel Bakış: HTML ile içeriği yapılandırma

Sonraki

Bu beceri testinin amacı, HTML içinde bağlantıları nasıl uyguladığınızı değerlendirmenize yardımcı olmaktır.

Not: Yardım almak için, Bilgini sınayın kullanım kılavuzumuzu okuyun. Ayrıca iletişim kanallarımızdan biriyle bize ulaşabilirsiniz.

Not: Bu görevlerdeki başlangıç kodundaki bazı bağlantılarda  target="_blank"  niteliği ayarlanmıştır; böylece onlara tıkladığınızda, aynı sekme yerine yeni bir sekmede bağlı sayfayı açmayı denerler. Bu kesinlikle en iyi uygulama değildir; ancak bunu burada, sayfaların MDN Playground çıktısındaki <iframe> içinde açılmaması ve bu süreçte örnek kodunuzun silinmemesi için yaptık!

Bağlantılar 1

Bu görevde, Balinalar bilgi sayfamızdaki bağlantıları doldurmanıza yardımcı olmanızı istiyoruz.

Görevi tamamlamak için bağlantıları aşağıdaki gibi güncelleyin:

1. İlk bağlantı, geçerli sayfa ile aynı dizinde bulunan whales.html adlı bir sayfaya bağlanmalıdır.

2. Üzerine gelindiğinde, sayfanın Mavi Balinalar ve İspermeçet Balinaları hakkında bilgi içerdiğini söyleyen bir araç ipucu ekleyin.

3. İkinci bağlantı, kullanıcının varsayılan posta uygulamasında bir e-posta açacak bir bağlantıya dönüştürülmelidir; alıcı whales@example.com olarak ayarlanmalıdır.

4. Bonus puan, e-postanın konu satırının otomatik olarak Question about Whales olarak doldurulmasını da ayarlarsanız verilir.

Görevin başlangıç noktası şöyle görünür:

Balinalar Hakkında Bilgi

Koruma faaliyetlerimiz ve hangi Balinaları incelediğimiz hakkında daha fazla bilgi için Balinalar sayfamıza bakın.

Ekibimize daha fazla soru sormak isterseniz, bize e-posta göndermekten çekinmeyin.

Bu başlangıç noktası için alttaki kod şöyledir:

HTML

<h1>Balinalar Hakkında Bilgi</h1>

<p>

Koruma faaliyetlerimiz ve hangi Balinaları incelediğimiz hakkında daha fazla bilgi için

<a target="_blank">Balinalar sayfamıza</a> bakın.

</p>

<p>

Ekibimize daha fazla soru sormak isterseniz, bize

<a target="_blank">e-posta göndermekten</a> çekinmeyin.

</p>

Görevin güncellenmiş içeriği şöyle görünmelidir:

Balinalar Hakkında Bilgi

Koruma faaliyetlerimiz ve hangi Balinaları incelediğimiz hakkında daha fazla bilgi için Balinalar sayfamıza bakın.

Ekibimize daha fazla soru sormak isterseniz, bize e-posta göndermekten çekinmeyin.

Çözümü göstermek için buraya tıklayın

Bağlantılar 2

Bu görevde, dört bağlantıyı uygun yerlere götürecek şekilde doldurmanızı istiyoruz.

Görevi tamamlamak için bağlantıları aşağıdaki gibi güncelleyin:

1. İlk bağlantı, geçerli dizin içinde blue adlı bir dizinde bulunan blue-whale.jpg adlı bir görüntüye bağlanmalıdır.

2. İkinci bağlantı, geçerli dizinin bir üst dizin seviyesinde bulunan narwhal adlı bir dizinde yer alan narwhal.jpg adlı bir görüntüye bağlanmalıdır.

3. Üçüncü bağlantı, Birleşik Krallık Google Görsel Arama'ya bağlanmalıdır. Temel URL https://www.google.co.uk olup görsel arama imghp adlı bir alt dizinde yer alır.

4. Dördüncü bağlantı, geçerli sayfanın en altındaki paragrafa bağlanmalıdır. Bu paragrafin kimliği bottom’dur.

Görevin başlangıç noktası şöyle görünür:

List path tests

Mavi balina görüntüsüne beni bağla

Narval görüntüsüne beni bağla

Google görsel aramasına beni bağla

Sayfanın altındaki paragrafa beni bağla

Bu başlangıç noktası için alttaki kod şöyledir:

HTML

<h1>List path tests</h1>

<ul>

<li><a target="_blank">Mavi balina görüntüsüne beni bağla</a></li>

<li><a target="_blank">Narval görüntüsüne beni bağla</a></li>

<li><a target="_blank">Google görsel aramasına beni bağla</a></li>

<li><a>Sayfanın altındaki paragrafa beni bağla</a></li>

</ul>

<div></div>

<p id="bottom">Sayfanın alt kısmı!</p>

Görevin güncellenmiş içeriği şöyle görünmelidir:

List path tests

Mavi balina görüntüsüne beni bağla

Narval görüntüsüne beni bağla

Google görsel aramasına beni bağla

Sayfanın altındaki paragrafa beni bağla

Çözümü göstermek için buraya tıklayın

Bağlantılar 3

Aşağıdaki bağlantılar, Narwhals hakkında bilgi sayfasına, bir destek e-posta adresine ve 4 MB boyutunda bir PDF bilgi dosyasına götürür.

Görevi tamamlamak için:

1. Mevcut, kötü yazılmış bağlantı metinlerini alın ve iyi bağlantı metni olacak şekilde yeniden yazın.

2. Uyarı gerektiren bağlantılara gerekli uyarıyı ekleyin.

Görevin başlangıç noktası şöyle görünür:

Biz Narwhals ile çok çalışıyoruz. Bu çalışma hakkında daha fazla bilgi edinmek için buraya tıklayın.

Daha fazla sorunuz varsa destek ekibimize e-posta gönderebilirsiniz — bunu yapmak için buraya tıklayın.

Ayrıca bilgi dosyamızı indirmek için buraya tıklayabilirsiniz; bu dosya, SSS dahil çok daha fazla bilgi içerir.

Bu başlangıç noktası için alttaki kod şöyledir:

HTML

<p>

Biz Narwhals ile çok çalışıyoruz. Bu çalışma hakkında daha fazla bilgi edinmek için

<a href="narwhals.html" target="_blank">buraya tıklayın</a>.

</p>

<p>

Daha fazla sorunuz varsa destek ekibimize e-posta gönderebilirsiniz —

<a href="mailto:whales@example.com">buraya tıklayın</a> bunu yapmak için.

</p>

<p>

Ayrıca bilgi dosyamızı indirmek için <a href="factfile.pdf" target="_blank">buraya tıklayabilirsiniz</a>; bu dosya, SSS dahil çok daha fazla bilgi içerir.

</p>

Bu görev için bitirilmiş içerik sağlamadık; aksi halde çözümü ele vermiş olurduk.

Çözümü göstermek için buraya tıklayın

Önceki

Genel Bakış: HTML ile içeriği yapılandırma

Sonraki

Kendiniz için daha iyi bir internet taslağı.


---

# İçerik sayfasını yapılandırma meydan okuması

İçerik sayfasını yapılandırma meydan okuması - Web geliştirmeyi öğren | MDN

HTML

Bird watching site meydan okuması

English (US)

İçerik sayfasını yapılandırma meydan okuması

Önceki

Genel Bakış: HTML ile içeriği yapılandırma

Sonraki

CSS kullanılarak düzenlenmek üzere bir sayfayı yapılandırmak, ustalaşılması gereken çok önemli bir beceridir. Bu meydan okumada, bir sayfanın sonunda nasıl görünebileceğini düşünme ve bunun üzerine bir düzen oluşturmak için uygun yapısal semantik seçme yeteneğiniz sınanacaktır.

Başlangıç noktası

Bu meydan okumayı çözmek için, bilgisayarınızın sabit diskinde uygun bir klasörün içinde ya da CodePen veya JSFiddle gibi bir çevrimiçi düzenleyici kullanarak basit bir web sitesi projesi oluşturmanız beklenmektedir. İhtiyacınız olan kodun çoğu zaten sağlanmıştır.

1. Bilgisayarınızda uygun bir konumda structuring-html-challenge adlı yeni bir klasör oluşturun (veya çevrimiçi bir düzenleyici açıp yeni bir proje oluşturmak için gerekli adımları izleyin).

2. Aşağıdaki HTML listesini klasörünüzün içinde index.html adlı bir dosyaya kaydedin (veya çevrimiçi düzenleyicinizin HTML bölmesine yapıştırın).

HTML

<!doctype html>

<html lang="en">

<head>

<meta charset="utf-8" />

<title>Birdwatching</title>

<link

href="https://fonts.googleapis.com/css?

family=Roboto+Condensed:300%7CCinzel+Decorative:700"

rel="stylesheet" />

</head>

<body>

<h1>Birdwatching</h1>

Home Get started Photos Gear Forum

<h2>Welcome</h2>

<p>

Welcome to our fake birdwatching site. If this were a real site, it

olacaktı:


would be the ideal place to come to learn more about birdwatching,

whether you are a beginner looking to learn how to get into birding, or

an expert wanting to share ideas, tips, and photos with other

like-minded people.

</p>

<p>

So don't waste time! Get what you need, then turn off that computer and

get out into the great outdoors!

</p>

<h2>Favorite photos</h2>

<!-- Link images here. -->

<p>

This fake website example is CC0 — any part of this code may be reused

in any way you wish. Original example written by Chris Mills, 2016.

</p>

<p>

<a href="http://game-icons.net/lorc/originals/dove.html">Dove icon</a>

by Lorc.

</p>

</body>

</html>

3. Aşağıdaki CSS listesini klasörünüzün içinde style.css adlı bir dosyaya kaydedin (veya çevrimiçi düzenleyicinizin CSS bölmesine yapıştırın).

CSS

/* || General setup */

body {

margin: 0;

}

html {

font-size: 10px;

background-color: darkgrey;

}

body {

width: 70%;

min-width: 800px;

margin: 0 auto;

}

/* || typography */

h1,

h2 {

font-family: "Cinzel Decorative", cursive;

color: #2a2a2a;

}

p,

li {

font-family: "Roboto Condensed", sans-serif;

color: #2a2a2a;

}

h1 {

font-size: 4rem;

text-align: center;

text-shadow: 2px 2px 10px black;

}

h2 {

font-size: 3rem;

text-align: center;

}

p,

li {

font-size: 1.6rem;

line-height: 1.5;

}

/* || header layout */

header {

margin-bottom: 10px;

}

main,

header,

nav,

article,

aside,

footer,

section {

background-color: #00ff0080;

padding: 1%;

}

h1 {

text-transform: uppercase;

display: flex;

align-items: center;

justify-content: center;

gap: 20px;

}

header img {

height: 60px;

}

nav ul {

padding: 0;

list-style-type: none;

display: flex;

}

nav li {

text-align: center;

flex: 1;

}

nav a {

font-size: 2rem;

text-transform: uppercase;

text-decoration: none;

color: black;

}

nav a:hover,

nav a:focus {

color: red;

}

/* || main layout */

main {

display: flex;

gap: 10px;

}

article {

flex: 4;

}

aside {

flex: 1;

}

aside a {

display: block;

float: left;

width: 50%;

}

aside img {

max-width: 100%;

}

footer {

margin-top: 10px;

}

Daha sonra, sayfanızda aşağıdaki URL’leri kullanmanız gerekecek.

dove.png :

Site logosu

favorite-bird-1.jpg :

İlk kenar çubuğu görselinin tam boy sürümü

favorite-bird-1_th.jpg :

İlk kenar çubuğu görselinin küçük resmi

favorite-bird-2.jpg :

İkinci kenar çubuğu görselinin tam boy sürümü

favorite-bird-2_th.jpg :

İkinci kenar çubuğu görselinin küçük resmi

favorite-bird-3.jpg :

Üçüncü kenar çubuğu görselinin tam boy sürümü

favorite-bird-3_th.jpg :

Üçüncü kenar çubuğu görselinin küçük resmi

favorite-bird-4.jpg :

Dördüncü kenar çubuğu görselinin tam boy sürümü

favorite-bird-4_th.jpg :

Dördüncü kenar çubuğu görselinin küçük resmi

Proje özeti

Bu proje için göreviniz, bir kuş gözlem sitesi ana sayfasının içeriğini alıp ona yapısal öğeler eklemek, böylece üzerine bir sayfa düzeni uygulanabilmesini sağlamaktır. Ayrıca içeriğe birkaç ekleme de yapmanız gerekir.

İçerik eklemeleri

1. <h1> öğesinin içinde, sayfadaki dove logosunu içeren bir <img> öğesi ekleyin. Ona boş alternatif metin ("") verin.

2. "Home", "Get started", "Photos", "Gear" ve "Forum" metin öğeleri bir gezinme menüsüne dönüştürülmelidir.

1. Bunları sırasız bir liste olarak işaretleyin.

2. Her liste öğesinin içinde metni # değerine (sahte bağlantı oluşturan) işaret eden bir <a> öğesi içine sarın.

3. <!-- Link images here. --> yorumunu kaldırın. Yerine, "favorite birds" için dört küçük resim görüntüsü kümesi koyun. Her birinde resmi tanımlamak için uygun alternatif metin bulunmalı ve tam boy eşdeğerine bağlanan bir <a> öğesi içine sarılmalıdır.

Yapısal gereksinimler

Site yapısı şu öğelerden oluşmalıdır:

1. Üst düzey sayfa başlığını ve gezinme menüsü listesini saran bir başlık bölümü.

2. Gezinme menüsü listesi için ek bir sarmalayıcı.

3. Bir ana içerik alanı; bir ana makale karşılama metnini içermeli, bir de küçük görselleri içeren bir kenar çubuğu (aside) bulunmalıdır.

4. Telif hakkı bilgilerini ve atıfları içeren bir alt bilgi bölümü.

Başka bir deyişle, şunlar için uygun bir sarmalayıcı eklemeniz gerekir:

Başlık bölümü

Gezi̇nme menüsü

Ana içerik

Karşılama makalesi

Görsel kenar çubuğu

Alt bilgi

Sayfayı stillendirme

Gerekirse, başlangıç HTML’inde sağlanan mevcut öğenin hemen altına başka bir <link> öğesi ekleyerek sağlanan CSS’yi sayfaya uygulayın (bazı çevrimiçi kod düzenleyiciler CSS’yi otomatik olarak uygular).

İpuçları ve öneriler

HTML’nizde istenmeyen hataları yakalamak için W3C HTML doğrulayıcısını kullanın; böylece bunları düzeltebilirsiniz.

Bu meydan okumayı yapmak için herhangi bir CSS bilmeniz gerekmiyor; yalnızca verilen CSS’yi HTML’nize uygulamanız gerekiyor.

Takılıp sayfada hangi öğeleri nereye yerleştireceğinizi hayal edemiyorsanız, sayfa düzeninin basit bir blok diyagramını çizin ve hangi öğelerin her bloğu sarması gerektiğini yazın. Bu çok faydalıdır.

Örnek

Aşağıdaki ekran görüntüsü, ana sayfanın işaretlendikten sonra nasıl görünebileceğine dair bir örnektir. Bunun bir kısmını nasıl başaracağınız konusunda takılırsanız, aşağıdaki canlı örneğe bakın.

Çözümü göstermek için buraya tıklayın

| Önceki | Genel Bakış: HTML ile içeriği yapılandırma | Sonraki |
| -------- | --------------------------------------- | ---- |

Kendiniz için daha iyi bir internet taslağı.


---

# HTML görüntüleri

HTML görüntüleri - Web geliştirmeyi öğren | MDN

HTML

Görüntüler

English (US)

HTML görüntüleri

Önceki

Genel Bakış: HTML ile içeriği yapılandırma

Sonraki

Başlangıçta web yalnızca metinden ibaretti ve gerçekten oldukça sıkıcıydı. Neyse ki, kısa süre sonra web sayfalarının içine görüntüleri (ve diğer daha ilgi çekici içerik türlerini) gömme yeteneği eklendi. Bu makalede, <img> öğesinin nasıl kullanılacağını ayrıntılı olarak inceleyeceğiz; temel bilgileri, <figure> ile altyazı eklemeyi ve CSS arka plan görüntüleriyle ilişkisini ele alacağız.

Önkoşullar:

Basic HTML Syntax’ta ele alındığı gibi temel HTML bilgisi. Başlıklar, paragraflar ve listeler gibi metin düzeyi semantiği.

Yeniden kullanılan öğe (replaced element) terimi — ne anlama gelir?

Temel <img> etiket sözdizimi

Bir kaynağı işaret etmek için src kullanımı.

Öğrenme kazanımları:

width ve height kullanımı; örneğin, bir görüntü yüklenip gösterildikten sonra arayüzde istenmeyen sarsıntılı güncellemeleri önlemek için.

Web için medya varlıklarını optimize etme — dosya boyutlarını küçük tutun.

Medya varlığı lisanslamasını anlama — farklı lisans türleri, bunlara nasıl uyulacağı ve projelerde kullanılacak uygun lisanslı medya dosyalarının nasıl aranacağı.

Bir görüntüyü web sayfasına nasıl koyarız?

Bir web sayfasına bir görüntü koymak için <img> öğesini kullanırız. Bu, yararlı olabilmesi için iki niteliğe ihtiyaç duyan boş bir öğedir (yani, çocuk içeriği olamaz ve bir bitiş etiketi olamaz): src ve alt. src niteliği, sayfaya gömmek istediğiniz görüntüyü işaret eden bir URL içerir. <a> öğeleri için href niteliğinde olduğu gibi, src niteliği de göreli bir URL veya mutlak bir URL olabilir. src niteliği olmadan, bir img öğesinin yükleyecek bir görüntüsü yoktur.

alt niteliği aşağıda açıklanmaktadır.

Not: Devam etmeden önce göreli ve mutlak URL’ler hakkındaki bilginizi tazelemek için URLs and paths üzerine kısa giriş bölümünü okumalısınız.

Örneğin, görüntünüzün adı dinosaur.jpg ise ve HTML sayfanızla aynı dizinde yer alıyorsa, resmi şöyle gömebilirdiniz:

HTML

<img src="dinosaur.jpg" alt="Dinosaur" />

Eğer görüntü, HTML sayfasıyla aynı dizinin içinde bulunan images alt dizinindeyse, bunu şöyle gömerdiniz:

HTML

<img src="images/dinosaur.jpg" alt="Dinosaur" />

Ve benzeri.

Not: Arama motorları ayrıca görüntü dosyası adlarını okur ve bunları SEO’ya katkı olarak sayar. Bu nedenle, görüntünüze açıklayıcı bir dosya adı vermelisiniz; dinosaur.jpg, img835.png’den daha iyidir.

Ayrıca görüntüyü mutlak URL’siyle de gömebilirsiniz; örneğin:

HTML

<img src="https://www.sourcecodester.com/sites/default/files/images/rems/cdg1.jpg" alt="Dinosaur" />

Ancak mutlak URL’lerle bağlantı vermek önerilmez. Kullanmak istediğiniz görüntüleri kendi sitenizde barındırmalısınız; basit kurulumlarda bu, web sitenizin görüntülerini HTML ile aynı sunucuda tutmak anlamına gelir. Ayrıca, farklı bir etki alanına taşındığınızda yeni etki alanını içerecek şekilde tüm URL’lerinizi güncellemeniz gerekmez; bakım açısından göreli URL’ler mutlak URL’lerden daha verimlidir. Daha gelişmiş kurulumlarda, görüntülerinizi sunmak için bir CDN (Content Delivery Network) kullanabilirsiniz.

Eğer görüntüleri siz oluşturmadıysanız, onların yayımlandığı lisansın koşullarına göre bunları kullanma izniniz olduğundan emin olmalısınız (daha fazla bilgi için aşağıdaki Medya varlıkları ve lisanslama bölümüne bakın).

Uyarı: src niteliğini, izinsiz olarak başkasının web sitesinde barındırılan bir görüntüye asla yönlendirmeyin. Buna "hotlinking" denir. Başka biri, biri sayfanızı ziyaret ettiğinde görüntünün bant genişliği maliyetini ödeyeceği için etik dışı kabul edilir. Ayrıca, görüntü kaldırıldığında veya utanç verici bir şeyle değiştirildiğinde sizin hiçbir kontrolünüz olmaz.

Yukarıdaki kod parçacığı, mutlak veya göreli URL ile, bize aşağıdaki sonucu verir:

Not: <img> ve <video> gibi öğelere bazen yeniden kullanılan öğeler denir. Bunun nedeni, öğenin içeriğinin ve boyutunun, öğenin kendi içeriği tarafından değil, harici bir kaynak (bir görüntü veya video dosyası gibi) tarafından tanımlanmasıdır. Bunlar hakkında daha fazlasını replaced elements sayfasında okuyabilirsiniz.

Alternatif metin

Bakacağımız bir sonraki nitelik alt’tır. Değeri, görüntünün görülemediği/gösterilemediği ya da yavaş bir internet bağlantısı nedeniyle oluşturulmasının uzun sürdüğü durumlarda kullanılmak üzere, görüntünün metinsel bir açıklaması olmalıdır. Örneğin, yukarıdaki kodumuz şöyle değiştirilebilir:

HTML

<img
src="images/dinosaur.jpg"
alt="The head and torso of a dinosaur skeleton;
it has a large head with long sharp teeth" />

alt metnini test etmenin en kolay yolu, dosya adınızı bilerek yanlış yazmaktır. Örneğin görüntü adımız dinosooooor.jpg olsaydı, tarayıcı görüntüyü göstermez ve bunun yerine alt metnini gösterirdi:

Peki, alt metnini neden veya ne zaman görürsünüz? Bu, birkaç nedenle işe yarayabilir:

Kullanıcı görme engellidir ve web’i kendisine okumak için bir ekran okuyucu kullanıyordur. Hatta görüntüyü tanımlamak için alt metninin bulunması çoğu kullanıcı için faydalıdır.

Yukarıda açıklandığı gibi, dosya veya yol adının yazımı yanlış olabilir.

Tarayıcı görüntü türünü desteklemeyebilir. Hâlâ Lynx gibi yalnızca metin tabanlı tarayıcılar kullanan bazı kişiler vardır; bunlar görüntülerin alt metnini gösterir.

Arama motorlarının kullanabileceği metin sağlamak isteyebilirsiniz; örneğin arama motorları alt metnini arama sorgularıyla eşleştirebilir.

Kullanıcılar veri aktarım hacmini ve dikkat dağıtıcı unsurları azaltmak için görüntüleri kapatmış olabilir. Bu durum, özellikle mobil telefonlarda ve bant genişliğinin sınırlı ya da pahalı olduğu ülkelerde yaygındır.

alt niteliğinizin içine tam olarak ne yazmalısınız? Bu, görüntünün ilk etapta orada olma nedenine bağlıdır; başka bir deyişle, görüntünüz görünmezse neyi kaybedeceğinize bağlıdır:

Dekorasyon. Dekoratif görüntüler için CSS arka plan görüntüleri kullanmalısınız; ancak HTML kullanmak zorundaysanız, boş bir alt="" ekleyin. Görüntü içeriğin bir parçası değilse, ekran okuyucunun bunu okumak için zaman harcamaması gerekir.

İçerik. Görüntünüz önemli bilgi sağlıyorsa, aynı bilgiyi kısa bir alt metninde verin — hatta daha iyisi, herkesin görebileceği ana metinde verin. Gereksiz alt metni yazmayın. Bir görsel kullanıcı için ana içerikte tüm paragraflar iki kez yazılsaydı ne kadar can sıkıcı olurdu? Görüntü ana metin tarafından yeterince açıklanıyorsa, alt="" kullanabilirsiniz.

Bağlantı. Bir görüntüyü <a> etiketlerinin içine koyup bir görüntüyü bağlantıya dönüştürürseniz, yine de erişilebilir bağlantı metni sağlamalısınız. Bu durumlarda, bunu ya aynı <a> öğesinin içine, ya da görüntünün alt niteliği içine yazabilirsiniz — hangisi sizin durumunuzda daha iyi çalışıyorsa.

Metin. Metninizi görüntülerin içine koymamalısınız. Örneğin ana başlığınız bir gölge istiyorsa, bunu bir görüntüye metin koymak yerine CSS ile yapın. Bununla birlikte, bunu gerçekten önleyemiyorsanız, metni alt niteliği içinde sağlamalısınız.

Özünde, amaç, görüntüler görülemediğinde bile kullanılabilir bir deneyim sunmaktır. Bu, tüm kullanıcıların içeriğin hiçbirini kaçırmamasını sağlar. Tarayıcınızda görüntüleri kapatmayı deneyin ve görünümün nasıl olduğunu görün. Görüntü görülemediğinde alt metninin ne kadar yararlı olduğunu kısa sürede anlayacaksınız.

Not: Görüntüler için çeşitli durumlarda alt niteliğini nasıl kullanacağınızı öğrenmek için Metin Alternatifleri kılavuzumuza ve bir alt Karar Ağacı’na bakın.

Not:

HTML etiketleri

MDN öğrenme ortağı Scrimba, görüntüler ve mini meydan okumalar hakkında bilgi veren etkileşimli bir derstir.

Genişlik ve yükseklik

Görüntünüzün genişliğini ve yüksekliğini belirtmek için width ve height niteliklerini kullanabilirsiniz. Bunlar birim içermeyen tam sayılar olarak verilir ve görüntünün piksel cinsinden genişliğini ve yüksekliğini temsil eder.

Görüntünüzün genişliğini ve yüksekliğini çeşitli yollarla öğrenebilirsiniz. Örneğin Mac’te, görüntü dosyasının görüntüleme bilgilerini almak için Cmd + I kullanabilirsiniz. Örneğimize dönerek, bunu yapabiliriz:

HTML

<img
src="images/dinosaur.jpg"
alt="The head and torso of a dinosaur skeleton;
it has a large head with long sharp teeth"


---

# Bilgini sınayın: HTML görüntüleri

Bilgini sınayın: HTML görüntüleri - Web geliştirmeyi öğren | MDN

Test: HTML testleri dizini

Test: Görüntüler

English (US)

Bilgini sınayın: HTML görüntüleri

Önceki

Genel Bakış: HTML ile içeriği yapılandırma

Sonraki

Bu beceri testinin amacı, görüntüleri anlayıp HTML içinde nasıl gömdüğünüzü değerlendirmenize yardımcı olmaktır.

Not: Yardım almak için, Bilgini sınayın kullanım kılavuzumuzu okuyun. Ayrıca iletişim kanallarımızdan biriyle bize ulaşabilirsiniz.

Görüntüler 1

Bu görevde, sayfaya bazı Yaban Mersinleri görüntüsü yerleştirmenizi istiyoruz.

Görevi tamamlamak için:

1. Görüntüyü sayfaya gömmek için uygun bir niteliğe görüntünün yolunu ekleyin. Görüntünün adı blueberries.jpg’dir ve şu yolda bulunur: https://github.com/mdn/learning-area/blob/main/html/multimedia-and-embedding/tasks/images/blueberries.jpg?raw=true .

2. Görüntüyü göremeyen kişiler için resmi açıklamak üzere uygun bir niteliğe biraz alternatif metin ekleyin.

3. <img> öğesine 400 genişlik değeri ve uygun bir yükseklik değeri verin; böylece doğru en-boy oranında görüntülenir ve yüklendiğinde yeniden oluşturma (re-render) yapmaz. Görüntünün doğal boyutu 615 x 419 pikseldir.

Görevin başlangıç noktası şöyle görünür:

Temel görüntü gömme

Üstte bazı yaban mersinlerinin resmini görmelisiniz.

Bu başlangıç noktası için alttaki kod şöyledir:

HTML

<h1>Temel görüntü gömme</h1>

<img />

<p>Üstte bazı yaban mersinlerinin resmini görmelisiniz.</p>

Görevin güncellenmiş içeriği şöyle görünmelidir:

Temel görüntü gömme

Üstte bazı yaban mersinlerinin resmini görmelisiniz.

Çözümü göstermek için buraya tıklayın

Görüntüler 2

Bu görevde, zaten tam özellikli bir görüntünüz var; ancak üzerine gelindiğinde görünen bir araç ipucu eklemenizi istiyoruz. Araç ipucuna uygun bazı bilgiler koymalısınız.

Görevin başlangıç noktası şöyle görünür:

Temel görüntü başlığı

Bu başlangıç noktası için alttaki kod şöyledir:

HTML

<h1>Temel görüntü başlığı</h1>

<img

src="https://flatheadbeacon.com/wp-content/uploads/2024/10/20231020_LARCH_ELK_MTN_0056-copy.jpg"

alt="Several tall evergreen trees called larches" />

Bu görev için bitirilmiş içerik sağlamadık; çünkü başlangıç noktasıyla aynı görünür.

Çözümü göstermek için buraya tıklayın

Görüntüler 3

Bu görevde, hem tam özellikli bir görüntü hem de bazı açıklama metinleri verilmiştir. Burada yapmanız gereken, görüntüyü açıklama ile ilişkilendirecek öğeler eklemektir.

Görevin başlangıç noktası şöyle görünür:

Görüntü ve açıklama

 2019 Firefox logosu

Bu başlangıç noktası için alttaki kod şöyledir:

HTML

<h1>Görüntü ve açıklama</h1>

<img

src="https://github.com/mdn/learning-area/blob/main/html/multimedia-and-embedding/tasks/images/firefox.png?raw=true"

alt="An abstract flaming fox wrapping around a blue sphere"

width="446"

height="460" />

2019 Firefox logosu

Görevin güncellenmiş içeriği şöyle görünmelidir:

Görüntü ve açıklama

2019 Firefox logosu

Çözümü göstermek için buraya tıklayın

Önceki

Genel Bakış: HTML ile içeriği yapılandırma

Sonraki

Kendiniz için daha iyi bir internet taslağı.


---

HTML
Video ve audio
HTML video ve audio
Önceki
Genel bakış: HTML ile içeriği yapılandırma
Sonraki
Now that we are comfortable with adding simple images to a webpage, the next step is to start adding video and audio
players to your HTML documents! In this article we'll look at doing just that with the <video>  and <audio>  elements;
we'll then finish off by looking at how to add captions/subtitles to your videos.
Önkoşullar:
Basic HTML familiarity, as covered in Basic HTML Syntax. Text-level semantics such as
headings and paragraphs and lists.
Learning
outcomes:
Basic <video>  and <audio>  tag syntax
Video ve audio-specific attributes such as controls and muted.
Using <source>  elements to provide different video or audio sources.
The basics of using text tracks such as captions and subtitles.
Video ve audio on the web
The first influx of online videos and audio were made possible by proprietary plugin-based technologies like 
 and
. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML
solutions <video>  and <audio>  elements and the availability of JavaScript APIs for controlling them. We'll not be
looking at JavaScript here — just the basic foundations that can be achieved with HTML.
We won't be teaching you how to produce audio and video files — that requires a completely different skill set. We have
provided you with 
 for your own experimentation, in case you are
unable to get hold of your own.
<video> öğesi
The <video>  element allows you to embed a video very easily. A really simple example looks like this:
HTML
English (US)
Flash
Silverlight
sample audio and video files and example code
Note: Before you begin here, you should also know that there are quite a few OVPs (online video providers) like
, 
, and 
, and online audio providers like 
. Such companies offer
a convenient, easy way to host and consume videos, so you don't have to worry about the enormous bandwidth
consumption. OVPs even usually offer ready-made code for embedding video/audio in your webpages; if you
use that route, you can avoid some of the difficulties we discuss in this article. We'll be discussing this kind of
service a bit more in the next article.
YouTube
Dailymotion
Vimeo
Soundcloud
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
1/11

<video src="rabbit320.webm" controls>
<p>
Your browser doesn't support HTML video. Here is a
<a href="rabbit320.webm">link to the video</a> instead.
</p>
</video>
The features to note are:
src
In the same way as for the <img>  element, the src  (source) attribute contains a path to the video you want to
embed. It works in exactly the same way.
controls
Users must be able to control video and audio playback (it's especially critical for people who have 
.) You
must either use the controls  attribute to include the browser's own control interface, or build your interface using
the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to
adjust the volume.
The paragraph inside the <video>  tags
This is called fallback content — this will be displayed if the browser accessing the page doesn't support the
<video>  element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case,
we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser
they are using.
The embedded video will look something like this:
epilepsy
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
2/11

You can 
 here (see also the 
.)
Using multiple source formats to improve
compatibility
There's a problem with the above example. It is possible that the video might not play for you, because different
browsers support different video (and audio) formats. Fortunately, there are things you can do to help prevent this from
being an issue.
Bir medya dosyasının içeriği
First, let's go through the terminology quickly. Formats like OGG, WAV, MP4 and WebM are called container formats.
They define a structure in which the audio and/or video tracks that make up the media are stored, along with metadata
describing the media, what codecs are used to encode its channels, and so forth.
A WebM file containing a movie which has a main video track and one alternate angle track, plus audio for both English
and Spanish, in addition to audio for an English commentary track can be conceptualized as shown in the diagram below.
Also included are text tracks containing closed captions for the feature film, Spanish subtitles for the film, and English
captions for the commentary.
try the example live
source code
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
3/11

The audio and video tracks within the container hold data in the appropriate format for the codec used to encode that
media. Different formats are used for audio tracks versus video tracks. Each audio track is encoded using an audio
codec, while video tracks are encoded using (as you probably have guessed) a video codec. As we talked about before,
different browsers support different video and audio formats, and different container formats (like OGG, MP4, and WebM,
which in turn can contain different types of video and audio).
For example:
A WebM container typically packages Vorbis or Opus audio with VP8/VP9 video. This is supported in all modern
browsers, though older versions may not work.
An MP4 container often packages AAC or MP3 audio with H.264 video. This is also supported in all modern
browsers.
The Ogg container tends to use Vorbis audio and Theora video. This is best supported in Firefox and Chrome, but
has basically been superseded by the better quality WebM format.
There are some special cases. For example, for some types of audio, a codec's data is often stored without a container,
or with a simplified container. One such instance is the FLAC codec, which is stored most commonly in FLAC files, which
are just raw FLAC tracks.
Another example is the ever-popular "MP3 file". An "MP3 file" is an audio file encoded using MPEG-1 Audio Layer III
compression. While it can include metadata, it is not encapsulated within a separate MPEG or MPEG-2 container. Its
widespread support in the <audio>  and <video>  elements is largely a testament to its enduring popularity.
An audio player will tend to play an audio track directly, e.g., an MP3 or Ogg file. These don't need containers.
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
4/11

Tarayıcılarda medya dosyası desteği
The codecs described in the previous section exist to compress video and audio into manageable files, since raw audio
and video are both exceedingly large. Each web browser supports an assortment of codecs, like Vorbis or H.264, which
are used to convert the compressed audio and video into binary data and back. Each codec offers its own advantages
and drawbacks, and each container may also offer its own positive and negative features affecting your decisions about
which to use.
Things become slightly more complicated because not only does each browser support a different set of container file
formats, they also each support a different selection of codecs. In order to maximize the likelihood that your website or
app will work on a user's browser, you may need to provide each media file you use in multiple formats. If your site and
the user's browser don't share a media format in common, your media won't play.
Due to the intricacies of ensuring your app's media is viewable across every combination of browsers, platforms, and
devices you wish to reach, choosing the best combination of codecs and container can be a complicated task. See
Choosing the right container for help selecting the container file format best suited for your needs; similarly, see
Choosing a video codec and Choosing an audio codec for help selecting the first media codecs to use for your content
and your target audience.
One additional thing to keep in mind: mobile browsers may support additional formats not supported by their desktop
equivalents, just like they may not support all the same formats the desktop version does. On top of that, both desktop
and mobile browsers may be designed to offload handling of media playback (either for all media or only for specific
types it can't handle internally). This means media support is partly dependent on what software the user has installed.
So how do we do this? Take a look at the following 
 (
, also):
HTML
<video controls>
<source src="rabbit320.mp4" type="video/mp4" />
<source src="rabbit320.webm" type="video/webm" />
<p>
Your browser doesn't support this video. Here is a
<a href="rabbit320.mp4">link to the video</a> instead.
</p>
</video>
Here we've taken the src  attribute out of the actual <video>  tag, and instead included separate <source>  elements
that point to their own sources. In this case the browser will go through the <source>  elements and play the first one
Note: Several popular formats, such as MP3 and MP4/H.264, are excellent but are encumbered by patents; that
is, there are patents covering some or all of the technology that they're based upon. In the United States,
patents covered MP3 until 2017, and H.264 is encumbered by patents through at least 2027.
Because of those patents, browsers that wish to implement support for those codecs must pay typically
enormous license fees. In addition, some people prefer to avoid restricted software and prefer to use only open
formats. Due to these legal and preferential reasons, web developers find themselves having to support multiple
formats to provide a video experience to their entire audience.
updated example
try it live here
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
5/11

that it has the codec to support. Including WebM and MP4 sources should be enough to play your video on most
platforms and browsers these days.
Each <source>  element also has a type  attribute. This is optional, but it is advised that you include it. The type
attribute contains the MIME type of the file specified by the <source> , and browsers can use the type  to immediately
skip videos they don't understand. If type  isn't included, browsers will load and try to play each file until they find one
that works, which obviously takes time and is an unnecessary use of resources.
Refer to our guide to media types and formats for help selecting the best containers and codecs for your needs, as well
as to look up the right MIME types to specify for each.
Diğer <video> özellikleri
There are a number of other features you can include when displaying an HTML video. Take a look at our next example:
HTML
<video
controls
width="400"
height="400"
autoplay
loop
muted
preload="auto"
poster="poster.png">
<source src="rabbit320.mp4" type="video/mp4" />
<source src="rabbit320.webm" type="video/webm" />
<p>
Your browser doesn't support this video. Here is a
<a href="rabbit320.mp4">link to the video</a> instead.
</p>
</video>
The resulting UI looks something like this:
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
6/11

Features include:
width  and height
You can control the video size either with these attributes or with CSS. In both cases, videos maintain their native
width-height ratio — known as the aspect ratio. If the aspect ratio is not maintained by the sizes you set, the video
will grow to fill the space horizontally, and the unfilled space will just be given a solid background color by default.
autoplay
Makes the audio or video start playing right away, while the rest of the page is loading. You are advised not to use
autoplaying video (or audio) on your sites, because users can find it really annoying.
loop
Makes the video (or audio) start playing again whenever it finishes. This can also be annoying, so only use if really
necessary.
muted
Causes the media to play with the sound turned off by default.
poster
The URL of an image which will be displayed before the video is played. It is intended to be used for a splash screen
or advertising screen.
preload
Used for buffering large files; it can take one of three values:
"none"  does not buffer the file
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
7/11

"auto"  buffers the media file
"metadata"  buffers only the metadata for the file
You can find the above example available to 
 (also 
.) Note that we haven't
included the autoplay  attribute in the live version — if the video starts to play as soon as the page loads, you don't get
to see the poster!
<audio> öğesi
The <audio>  element works just like the <video>  element, with a few small differences as outlined below. A typical
example might look like so:
HTML
<audio controls>
<source src="viper.mp3" type="audio/mp3" />
<source src="viper.ogg" type="audio/ogg" />
<p>
Your browser doesn't support this audio file. Here is a
<a href="viper.mp3">link to the audio</a> instead.
</p>
</audio>
This produces something like the following in a browser:
play live on GitHub
see the source code
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
8/11

This takes up less space than a video player, as there is no visual component — you just need to display controls to play
the audio. Other differences from HTML video are as follows:
The <audio>  element doesn't support the width / height  attributes — again, there is no visual component, so
there is nothing to assign a width or height to.
It also doesn't support the poster  attribute — again, no visual component.
Other than this, <audio>  supports all the same features as <video>  — review the above sections for more information
about them.
Video metin izlerini görüntüleme
Now we'll discuss a slightly more advanced concept that is really useful to know about. Many people can't or don't want
to hear the audio/video content they find on the Web, at least at certain times. For example:
Many people have auditory impairments (such as being hard of hearing or deaf) so can't hear the audio clearly if
at all.
Others may not be able to hear the audio because they are in noisy environments (like a crowded bar when a
sports game is being shown).
Similarly, in environments where having the audio playing would be a distraction or disruption (such as in a library
or when a partner is trying to sleep), having captions can be very useful.
People who don't speak the language of the video might want a text transcript or even translation to help them
understand the media content.
Wouldn't it be nice to be able to provide these people with a transcript of the words being spoken in the audio/video?
Well, thanks to HTML video, you can. To do so we use the WebVTT file format and the <track>  element.
WebVTT is a format for writing text files containing multiple strings of text along with metadata such as the time in the
video at which each text string should be displayed, and even limited styling/positioning information. These text strings
are called cues, and there are several kinds of cues which are used for different purposes. The most common cues are:
subtitles
Translations of foreign material, for people who don't understand the words spoken in the audio.
captions
Synchronized transcriptions of dialog or descriptions of significant sounds, to let people who can't hear the audio
understand what is going on.
timed descriptions
Text which should be spoken by the media player in order to describe important visuals to blind or otherwise visually
impaired users.
A typical WebVTT file will look something like this:
WEBVTT
Note: You can 
 on GitHub (also see the 
.)
run the audio demo live
audio player source code
Note: "Transcribe" means "to write down spoken words as text." The resulting text is a "transcript."
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
9/11

1
00:00:22.230 --> 00:00:24.606
This is the first subtitle.
2
00:00:30.739 --> 00:00:34.074
This is the second.
…
To get this displayed along with the HTML media playback, you need to:
1. Save it as a .vtt  file somewhere the server can serve (see below), such as in the same directory as the HTML
file.
2. Link to the .vtt  file with the <track>  element. <track>  should be placed within <audio>  or <video> , but
after all <source>  elements. Use the kind  attribute to specify whether the cues are subtitles , captions , or
descriptions . Further, use srclang  to tell the browser what language you have written the subtitles in. Finally,
add label  to help readers identify the language they are searching for.
Here's an example:
HTML
<video controls>
<source src="example.mp4" type="video/mp4" />
<source src="example.webm" type="video/webm" />
<track kind="subtitles" src="subtitles_es.vtt" srclang="es" label="Spanish" />
</video>
In order to try this you need to host the files on a local HTTP server. In the output in browser, you'll see a video that has
subtitles displayed. For a full-fledged application and its source code, see Adding captions and subtitles to HTML video.
This example uses JavaScript to allow users to choose between different subtitles. Note that to turn the subtitles on, you
need to press the "CC" button and select an option — English, Deutsch, or Español.
Kendi audio ve videonuzu yerleştirme
For this task, why not go out into the world and record some of your own video and audio? If you have a phone, use that
to record audio and video, transfer it to your computer, and try it out. You may have to do some conversion to end up
with a WebM and MP4 in the case of video, and an MP3 and Ogg in the case of audio, but there are enough programs
and tools out there to allow you to do this without too much trouble, such as 
 (online) and 
(desktop application). We'd like you to have a go!
Note: Text tracks also help you with SEO, since search engines especially thrive on text. Text tracks even allow
search engines to link directly to a spot partway through the video.
CloudConvert
Audacity
Note: If you are unable to source any video or audio, then you can feel free to use our 
 to carry out this exercise.
sample audio and video
files
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
10/11

We would like you to:
1. Save your audio and video files in a new directory on your computer.
2. Create a new HTML file in the same directory, called index.html , based on our 
.
3. Add <audio>  and <video>  elements to the page; make them display the default browser controls.
4. Give both of them <source>  elements so that browsers will find the audio format they support best and load it.
These should include type  attributes.
5. Give both of them a fallback <p>  element inside the tags that provides a direct link to the media for non-
supporting browsers.
6. Give the <video>  element a poster that will be displayed before the video starts to be played. Have fun creating
your own poster graphic.
Click here to show the solution
Summary
And that's a wrap — we hope you had fun playing with video and audio in web pages! Sonraki up, we'll give you some tests
that you can use to check how well you've understood and retained the information we've provided on HTML video and
audio.
Önceki
Genel bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
getting started template
15.10.2026 20:24
HTML video ve audio - Web geliştirmeyi öğrenin | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio
11/11


---

Test: HTML tests index
Test: Audio and video
Test your skills: Audio and video
Önceki
Genel bakış: HTML ile içeriği yapılandırma
Sonraki
The aim of this skill test is to help you assess whether you understand how to embed video and audio content in HTML.
Audio and video 1
In this task, we want you to embed an audio file onto the page.
To complete this task:
1. Add the path to the audio file to an appropriate attribute to embed it on the page. The audio is called audio.mp3 ,
and it is available at the path https://github.com/mdn/learning-
area/raw/refs/heads/main/html/multimedia-and-embedding/tasks/audio-video/audio.mp3 .
2. Add an attribute to make browsers display some default controls.
The starting point of the task looks like this:
Basic audio embed
Here's the underlying code for this starting point:
HTML
<h1>Basic audio embed</h1>
<audio></audio>
The updated content should look like this:
English (US)
Note: To get help, read our Test your skills usage guide. You can also reach out to us using one of our
communication channels.
15.10.2026 20:24
Test your skills: Audio and video - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Audio_and_video
1/4

Basic audio embed
Click here to show the solution
Audio and video 2
In this task, we want you to mark up a slightly more complex video player, with multiple sources, subtitles, and other
features besides.
To complete this task:
1. Add an attribute to make browsers display some default controls.
2. Add multiple sources, containing the paths to the video files. The files are called video.mp4  and video.webm ,
and are available at the following paths:
1. https://github.com/mdn/learning-area/raw/refs/heads/main/html/multimedia-and-
embedding/tasks/audio-video/video.mp4
2. https://github.com/mdn/learning-area/raw/refs/heads/main/html/multimedia-and-
embedding/tasks/audio-video/video.webm
3. Let the browser know in advance what video formats the sources point to, so it can make an informed choice of
which one to download ahead of time.
4. Give the <video>  a width and height equal to its intrinsic size (320 by 240 pixels).
5. Make the video muted by default.
6. Display the text tracks contained in the subtitles_en.vtt  file when the video is playing. You must explicitly set
the type as subtitles, and the subtitle language to English. Also set the default  attribute so that the track is
displayed by default.
7. Make sure the readers can identify the subtitle language when they use the default controls.
The starting point of the task looks like this:
Note: A copy of the subtitles file is located in the same directory as this page to avoid crossorigin
problems: if you are completing the task live on MDN via the MDN Playground, the path you need is just
subtitles_en.vtt . If you decide to recreate the example on your local file system, you can find a copy
at the path https://github.com/mdn/learning-area/raw/refs/heads/main/html/multimedia-and-
embedding/tasks/audio-video/subtitles_en.vtt .
15.10.2026 20:24
Test your skills: Audio and video - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Audio_and_video
2/4

Video embed
Here's the underlying code for this starting point:
HTML
<h1>Video embed</h1>
<video></video>
The updated content should look like this:
Video embed
0:00 / 0:07
Click here to show the solution
15.10.2026 20:24
Test your skills: Audio and video - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Audio_and_video
3/4

Önceki
Genel bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
15.10.2026 20:24
Test your skills: Audio and video - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Audio_and_video
4/4


---

HTML
Challenge: Splash page
Challenge: Creepy-crawly splash page
Önceki
Genel bakış: HTML ile içeriği yapılandırma
Sonraki
In this challenge, we'll test your knowledge of some of the techniques discussed in the last couple of lessons, getting
you to add some images and a video to a splash page all about bugs and other creepy crawlies.
Starting point
To solve this challenge we are expecting you to create a simple website project, either inside a folder on your computer's
hard drive, or using an online editor such as 
 or 
. Much of the code you need is already provided.
1. Create a new folder in an appropriate location on your computer called splash-page-challenge  (or open an
online editor and take the required steps to create a new project).
2. Save the following HTML listing inside a file inside your folder called index.html  (or paste it into your online
editor's HTML pane).
HTML
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<title>Creepy crawlies!</title>
<link href="style.css" rel="stylesheet" />
</head>
<body>
<header>
<nav>
<ul>
<li><a href="#beetles">Beetles</a></li>
<li><a href="#true_bugs">True bugs</a></li>
<li><a href="#butterflies_moths">Butterflies and moths</a></li>
<li><a href="#flies_mosquitos">Flies and mosquitos</a></li>
<li><a href="#bees_wasps_ants">Bees, wasps, and ants</a></li>
<li><a href="#spiders">Spiders</a></li>
</ul>
</nav>
<section>
<h1>Creepy-crawlies splash page!</h1>
<p>
English (US)
CodePen
JSFiddle
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
1/11

In casual language, people use "bugs" to mean all sorts of small
creepy-crawlies: insects, spiders, etc. However, "Bugs" (true bugs)
are actually just one order of insects (Hemiptera). This page
provides a summary of the main classes or groups of
creepy-crawlies.
</p>
</section>
</header>
<main>
<section id="beetles">
<h2>Beetles (Coleoptera)</h2>
<p>
Beetles make up the largest order of insects, with more than
350,000 known species. They are recognized by their hardened
forewings (elytra) that cover and protect the delicate hindwings
and abdomen. This feature gives them a tough, armored look and
helps them survive in many environments, from forests to deserts.
Beetles can vary greatly in size, color, and habits, ranging from
tiny grain beetles to massive stag beetles with impressive jaws.
</p>
<p>
Many beetles play important ecological roles. Some, like ladybugs,
are beneficial predators that feed on crop pests such as aphids.
Others, such as dung beetles, recycle nutrients by breaking down
animal waste. However, certain species like the Colorado potato
beetle or Japanese beetle are major agricultural pests. Their
diversity and adaptability make beetles one of the most successful
groups of insects on Earth.
</p>
<p class="copyright">
Image by URSchmidt - Own work, CC BY-SA 4.0,
<a href="https://commons.wikimedia.org/w/index.php?curid=70137401"
>https://commons.wikimedia.org/w/index.php?curid=70137401</a
>.
</p>
</section>
<section id="true_bugs">
<h2>True Bugs (Hemiptera)</h2>
<p>
True bugs include a wide range of insects such as stink bugs,
cicadas, aphids, and water striders. Unlike beetles, their
forewings are partly hardened and partly membranous, and they
possess distinctive piercing-sucking mouthparts. These mouthparts
are adapted for feeding on plant sap, blood, or other insects. Many
true bugs have scent glands that produce strong odors as a defense
mechanism, which is why some are called "stink bugs."
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
2/11

</p>
<p>
True bugs are found worldwide and occupy a variety of habitats,
including plants, soil, and water. While some species are harmless
or even beneficial predators, others are destructive agricultural
pests that weaken plants by draining their sap. Certain bugs, like
bed bugs and kissing bugs, can also affect humans directly by
biting or transmitting diseases.
</p>
<p class="copyright">
Image created by user B. Schoenmakers at Waarneming.nl, a source of
nature observations in the Netherlands. - This image is uploaded as
image number 29046158 at Waarneming.nl, a source of nature
observations in the Netherlands.This tag does not indicate the
copyright status of the attached work. A normal copyright tag is
still required. See Commons:Licensing for more information. This
site now requires authentication, however, the same image and
copyright information is also available via
<a href="https://world.observation.org/foto/view/29046158"
>https://world.observation.org/foto/view/29046158</a
>
since it uses the same data, CC BY 3.0,
<a href="https://commons.wikimedia.org/w/index.php?curid=92410673"
>https://commons.wikimedia.org/w/index.php?curid=92410673</a
>.
</p>
</section>
<section id="butterflies_moths">
<h2>Butterflies & Moths (Lepidoptera)</h2>
<p>
Butterflies and moths are some of the most recognizable insects
thanks to their large, often colorful wings covered in tiny scales.
These scales give their wings shimmering, patterned appearances and
are one of the defining traits of this group. Butterflies are
usually active by day, while moths are mostly nocturnal, though
there are exceptions. Both undergo complete metamorphosis, with a
dramatic transformation from caterpillar to winged adult.
</p>
<p>
As caterpillars, they primarily feed on leaves, sometimes causing
damage to crops and plants. As adults, butterflies and many moths
are important pollinators, transferring pollen as they sip nectar
from flowers. They are also ecologically vital as food sources for
birds, bats, and other animals. Their beauty and ecological
importance make them a favorite group for nature enthusiasts and
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
3/11

scientists alike.
</p>
<p class="copyright">
Image by Didier Descouens - Own work, CC BY-SA 4.0,
<a href="https://commons.wikimedia.org/w/index.php?curid=19303857"
>https://commons.wikimedia.org/w/index.php?curid=19303857</a
>.
</p>
</section>
<section id="flies_mosquitos">
<h2>Flies & Mosquitoes (Diptera)</h2>
<p>
Flies and mosquitoes belong to the order Diptera, meaning "two
wings." Unlike most other insects, they have only one functional
pair of wings; the hind pair has evolved into tiny balancing organs
called halteres. This adaptation gives them incredible agility in
flight. Their mouthparts vary widely: some species have sponging
mouthparts (like houseflies), while others have piercing-sucking
ones (like mosquitoes).
</p>
<p>
These insects are among the most ecologically and medically
significant. Many flies are decomposers, helping break down waste
and recycle nutrients. Mosquitoes, however, are infamous as disease
vectors, spreading malaria, dengue, and other illnesses. Despite
their negative reputation, flies and mosquitoes are essential in
ecosystems, serving as pollinators and as a major food source for
many animals.
</p>
<p class="copyright">
Image created by user Dick Belgers at Waarneming.nl, a source of
nature observations in the Netherlands. - This image is uploaded as
image number 5105758 at Waarneming.nl, a source of nature
observations in the Netherlands.This tag does not indicate the
copyright status of the attached work. A normal copyright tag is
still required. See Commons:Licensing for more information. CC BY
3.0,
<a href="https://commons.wikimedia.org/w/index.php?curid=27659589"
>https://commons.wikimedia.org/w/index.php?curid=27659589</a
>.
</p>
</section>
<section id="bees_wasps_ants">
<h2>Bees, Wasps, Ants (Hymenoptera)</h2>
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
4/11

<p>
Bees, wasps, and ants are a diverse group known for their complex
behaviors and social structures. Many species live in colonies with
distinct roles for workers, queens, and males. Bees are especially
famous for pollination, producing honey, and communicating with
each other through dances. Wasps are often predators or
parasitoids, while ants are skilled builders and cooperative
foragers.
</p>
<p>
This group has a huge ecological impact. Bees and wasps contribute
to pollination, supporting food crops and wild plants. Some wasps
help control pest populations by preying on or parasitizing other
insects. Ants are critical soil engineers, aerating the ground and
recycling nutrients. While stings and aggressive behaviors make
some species feared, they are vital players in natural and
agricultural systems.
</p>
<p class="copyright">
Image by Trounce - Own work, CC BY-SA 2.5,
<a href="https://commons.wikimedia.org/w/index.php?curid=1997709"
>https://commons.wikimedia.org/w/index.php?curid=1997709</a
>.
</p>
</section>
<section id="spiders">
<h2>Spiders (Araneae)</h2>
<p>
Spiders are arachnids, not insects, and are easily distinguished by
their eight legs and lack of antennae. Almost all spiders are
predators, using venom and silk to capture prey. Many build
intricate webs to trap insects, while others are active hunters
that chase or ambush their food. Their silk is an incredibly strong
and versatile material, used for webs, egg sacs, or safety lines.
</p>
<p>
Spiders are found in nearly every habitat on Earth, from deserts to
caves to homes. While some people fear them, very few species pose
a danger to humans. In fact, spiders are highly beneficial because
they help control insect populations, including pests. They play a
crucial role in balancing ecosystems, making them one of the most
important non-insect "bugs" people commonly encounter.
</p>
<p class="copyright">
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
5/11

Image by AJC ajcann.wordpress.com from UK, CC BY-SA 2.0
<a href="https://creativecommons.org/licenses/by-sa/2.0"
>https://creativecommons.org/licenses/by-sa/2.0</a
>, via Wikimedia Commons.
</p>
</section>
</main>
</body>
</html>
3. Save the following CSS listing inside a file inside your folder called style.css  (or paste it into your online
editor's CSS pane).
CSS
/* type */
body {
font: 1.2em / 1.5 system-ui;
margin: 0 auto;
width: 90%;
min-width: 800px;
max-width: 1200px;
}
h1 {
text-align: center;
}
.copyright {
font-size: 0.8em;
}
/* nav menu */
ul {
padding: 0;
list-style-type: none;
text-align: center;
display: flex;
flex-flow: row wrap;
justify-content: center;
align-items: center;
}
li {
flex: auto;
}
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
6/11

nav a {
font-size: 1.2em;
padding: 0 20px;
}
/* General link styles */
a {
text-decoration: none;
color: red;
}
a:hover,
a:focus {
text-decoration: underline;
}
/* header section layout */
header section {
display: grid;
grid-template-areas:
"heading heading"
"text video"
"text video";
grid-template-columns: 1fr 2fr;
gap: 20px;
}
h1 {
grid-area: heading;
}
header p {
grid-area: text;
margin: 0;
}
video {
grid-area: video;
width: 100%;
border: 1px solid black;
}
/* image floats */
figure {
float: right;
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
7/11

margin-left: 20px;
padding: 20px;
background: orange;
border: 1px solid black;
}
figcaption {
font-size: 0.6em;
}
Later on, you will need to include the following URLs in your page.
bee.jpg : 
.
beetle.png : 
.
butterfly.jpg : 
.
fly.jpg : 
.
spider.jpg : 
.
true_bug.jpg : 
.
bug_video_640.mp4 : 
.
Project brief
In this assessment we are presenting you with a mostly-finished splash page about different creepy-crawlies.
Unfortunately, no images or video have been added yet — this is your job! You need to add some media to make the
page look more interesting. The following subsections detail what you need to do.
Adding a video to the header
Just below the <h1> , add a <video>  element that embeds our header video into the page. We'd like it to do the
following:
Autoplay the video on load (for this to work in at least some browsers, you'll also need to specify that the video
should be muted).
Loop endlessly rather than playing once.
Preload the video content.
Not show any controls.
Adding section images
In the expanded information sections on each type of bug, below each <h2> , we'd like you to add an image element
that embeds the appropriate image for each section. Give each image some appropriate alternative text for the benefit of
screen reader users (and in case the image doesn't load), and constrain each image to dimensions of 250 x 180.
In addition, we'd like you to include a caption for each image; think about what container element is needed to
semantically associate the two together. Don't just make the caption repeat the alternative text; it should work alongside
the alternative text and the image.
Add bug emojis or icons to the nav menu and <h2>s
For a bit of fun, we'd like you to add icons to the start of each nav list item, and the same icon to the start of each
corresponding <h2> . You could do this using embedded images, but it's easier to just find appropriate emojis and add
Image for the "Bees, Wasps, Ants (Hymenoptera)" section
Image for the "Beetles (Coleoptera)" section
Image for the "Butterflies & Moths (Lepidoptera)" section
Image for the "Flies & Mosquitoes (Diptera)" section
Image for the "Spiders (Araneae)" section
Image for the "True Bugs (Hemiptera)" section
header video
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
8/11

them to the HTML text itself.
Hints and tips
You can use the 
 to catch mistakes in your HTML.
You don't need to know any CSS to do this assessment; you just need to edit the provided HTML file. The CSS
part is already done for you.
Example
The following screenshot shows what the splash page should look like. If you are getting stuck on how to achieve some
of this, see the solution below the live example.
W3C HTML validator
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
9/11

15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
10/11

Click here to show the solution
Önceki
Genel bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
15.10.2026 20:24
Challenge: Creepy-crawly splash page - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Splash_page
11/11


---

HTML
Table basics
HTML table basics
Önceki
Genel bakış: HTML ile içeriği yapılandırma
Sonraki
This article gets you started with HTML tables, covering the basics such as rows, cells, headings, making cells span
multiple columns and rows, and styling all cells in a column as a single item.
Önkoşullar:
Basic HTML familiarity, as covered in Basic HTML Syntax.
Öğrenme çıktıları:
What tables are for — structuring tabular data.
What tables are not for — layout, or anything else.
Basic table syntax — <table> , <tr> , and <td> .
Defining table headers with <th> .
Spanning multiple columns and rows with colspan  and rowspan .
Grouping columns with <colgroup>  and <col> .
What is a table?
A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily
look up values that indicate a connection between different types of data, for example, a person and their age, a day of
the week, or the timetable for a local swimming pool.
English (US)
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
1/15

Tables are very commonly used in human society and have been for a long time, as evidenced by this US Census
document from 1800:
It is therefore no wonder that the creators of HTML provided a way to structure and present tabular data on the web.
How does a table work?
Tables are rigid. Information is interpreted by making visual associations between row and column headers. Look at the
table below, for example, and find a Jovian gas giant with 62 moons. You can find the answer by associating the relevant
row and column headers.
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
2/15

Data about the planets of our solar system (Source: Nasa's Planetary Fact Sheet -
Name
Mass
(1024kg)
Diameter
(km)
Density
(kg/m3)
Gravity
(m/s2)
Length
of day
(hours)
Distance
from
Sun
(106km)
Mean
temperatu
(°C)
Terrestrial
planets
Mercury 0.330
4,879
5427
3.7
4222.6
57.9
167
Venus
4.87
12,104
5243
8.9
2802.0
108.2
464
Earth
5.97
12,756
5514
9.8
24.0
149.6
15
Mars
0.642
6,792
3933
3.7
24.7
227.9
-65
Jovian
planets
Gas
giants
Jupiter
1898
142,984
1326
23.1
9.9
778.6
-110
Saturn
568
120,536
687
9.0
10.7
1433.5
-140
Ice
giants
Uranus
86.8
51,118
1271
8.7
17.2
2872.5
-195
Neptune 102
49,528
1638
11.0
16.1
4495.1
-200
Dwarf planets
Pluto
0.0146
2,370
2095
0.7
153.3
5906.4
-225
When implemented correctly, accessibility tools such as screen readers handle tables well, so a successful HTML table
should enhance the experience of sighted and visually impaired users alike.
Table styling
You can also have a 
 on GitHub! One thing you'll notice is that the table is more
readable there — the table earlier on this page has minimal styling, whereas the GitHub version has more significant CSS
applied.
Be under no illusion; for tables to be effective on the web, you need to provide some styling information with CSS, as
well as good, solid structure with HTML. In this lesson, we focus on the HTML part; you'll learn about styling tables later,
in our Styling tables lesson.
We won't focus on CSS in this module, but we have provided a minimal CSS stylesheet that will make your tables more
readable than the default you get without any styling. You can find the 
, and you can also find an 
 that applies the stylesheet — these together will give you a good starting point for experimenting with HTML
tables.
When should you avoid HTML tables?
HTML tables are only for tabular data (information that's easy to work with in rows and columns) — this is what they are
designed for. Unfortunately, people used to use HTML tables to lay out web pages; for example, one row to contain a
look at the live planets data example
stylesheet here
HTML
template
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
3/15

page header, another row to contain each content column, one row to contain the footer, etc. This technique was used in
the past because CSS support across browsers used to be a lot more limited. Modern browsers have solid CSS support,
so table-based layouts are no longer needed. Table layouts are now extremely rare, but you might still see them in some
corners of the web.
In short, using tables for layout rather than CSS layout techniques is a bad idea. The main reasons are as follows:
1. Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret
the tags that exist in an HTML page and read out the contents to the user. Because tables are not designed for
layout and result in more complex markup, the resulting screen reader output will be confusing.
2. Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures
than proper layout techniques, resulting in the code being harder to write, maintain, and debug.
3. Tables are not automatically responsive: When you use proper layout containers (such as <header> ,
<section> , <article> , or <div> ), their width defaults to 100% of their parent element. Tables are sized to
their content by default, so they need extra work to display effectively across a variety of devices.
Creating your first table
We've talked table theory enough, so let's dive into a practical example. Here, you'll build a simple table.
1. First of all, make a copy of 
 and 
 in a new directory on your local
machine. The HTML template already contains a <link>  element to apply the CSS, so you don't need to worry
about that.
2. Every table is enclosed by <table></table>  tags. Add these inside the body of your HTML.
3. The smallest container inside a table is a table cell, which is created with a <td>  element ("td" stands for "table
data"). Add the following inside your table tags:
HTML
<td>Hi, I'm your first cell.</td>
4. If we want a row of four cells, we need to copy these tags three times. Update the contents of your table to look
like this:
HTML
<td>Hi, I'm your first cell.</td>
<td>I'm your second cell.</td>
<td>I'm your third cell.</td>
<td>I'm your fourth cell.</td>
The cells are not placed underneath each other; rather, they are automatically aligned on the same row. Each <td>
element creates a single cell, and together they make up the first row. Every cell we add makes the row grow longer.
To start placing subsequent cells on a second row, we need to use the <tr>  element ('tr' stands for 'table row'). Let's
investigate this now.
blank-template.html
minimal-table.css
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
4/15

1. Place the four cells you've already created inside <tr>  tags, like so:
HTML
<tr>
<td>Hi, I'm your first cell.</td>
<td>I'm your second cell.</td>
<td>I'm your third cell.</td>
<td>I'm your fourth cell.</td>
</tr>
2. Now you've made one row, have a go at making one or two more — each row needs to be wrapped in an
additional <tr>  element, with each cell contained in a <td> .
Click here to show the solution
Adding headers with <th> elements
Now let's turn our attention to table headers — special cells that go at the start of a row or column and define the type of
data that row or column contains (for example, see the "Person" and "Age" cells in the first example shown in this
article). To see why they are useful, have a look at the following table example. First the source code:
HTML
<table>
<tr>
<td>&nbsp;</td>
<td>Knocky</td>
<td>Flor</td>
<td>Ella</td>
<td>Juan</td>
</tr>
<tr>
<td>Breed</td>
<td>Jack Russell</td>
<td>Poodle</td>
<td>Streetdog</td>
<td>Cocker Spaniel</td>
</tr>
<tr>
<td>Age</td>
<td>16</td>
<td>9</td>
<td>10</td>
<td>5</td>
</tr>
<tr>
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
5/15

<td>Owner</td>
<td>Mother-in-law</td>
<td>Me</td>
<td>Me</td>
<td>Sister-in-law</td>
</tr>
<tr>
<td>Eating Habits</td>
<td>Eats everyone's leftovers</td>
<td>Nibbles at food</td>
<td>Hearty eater</td>
<td>Will eat till he explodes</td>
</tr>
</table>
Now the actual rendered table:
 
Knocky
Flor
Ella
Juan
Breed
Jack Russell
Poodle
Streetdog
Cocker Spaniel
Age
16
9
10
5
Owner
Mother-in-law
Me
Me
Sister-in-law
Eating
Habits
Eats everyone's
leftovers
Nibbles at
food
Hearty
eater
Will eat till he
explodes
The problem here is that, while you can make out what's going on, it is not as easy to cross-reference data as it could
be. If the column and row headings stood out, it would be easier.
Adding headers to the dogs table
Let's improve the dogs table example by adding some headers.
1. First, make another copy of our 
 and 
 files in a new directory on your
local machine.
2. Add the following code inside the <body>  of your HTML:
HTML
<h1>Dogs Table</h1>
<table>
<tr>
<td>&nbsp;</td>
<td>Knocky</td>
blank-template.html
minimal-table.css
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
6/15

<td>Flor</td>
<td>Ella</td>
<td>Juan</td>
</tr>
<tr>
<td>Breed</td>
<td>Jack Russell</td>
<td>Poodle</td>
<td>Streetdog</td>
<td>Cocker Spaniel</td>
</tr>
<tr>
<td>Age</td>
<td>16</td>
<td>9</td>
<td>10</td>
<td>5</td>
</tr>
<tr>
<td>Owner</td>
<td>Mother-in-law</td>
<td>Me</td>
<td>Me</td>
<td>Sister-in-law</td>
</tr>
<tr>
<td>Eating Habits</td>
<td>Eats everyone's leftovers</td>
<td>Nibbles at food</td>
<td>Hearty eater</td>
<td>Will eat till he explodes</td>
</tr>
</table>
3. To recognize the table headers as headers, both visually and semantically, you can use the <th>  element ("th"
stands for "table header"). This works the same as a <td> , except that it denotes a header, not a normal cell. Go
into your HTML, and change all the <td>  elements surrounding the table headers into <th>  elements.
4. Save your HTML and load it in a browser, and you should see that the headers now look like headers.
Click here to show the solution
Why are headers useful?
We have already partially answered this question — it is easier to find the data you are looking for when the headers
clearly stand out, and the design just generally looks better.
Note: Table headings come with some default styling — they are bold and centered even if you don't add your
own styling to the table, to help them stand out.
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
7/15

Table headers have another benefit — along with the scope  attribute (which we'll learn about in the next article), they
make tables more accessible by associating each header with all the data in the same row or column. Screen readers
can then read out a whole row or column of data at once, which is pretty useful.
Allowing cells to span multiple rows and columns
Sometimes we want cells to span multiple rows or columns. Take the following simple example, which shows the names
of common animals. In some cases, we want to show the names of the males and females next to the animal name.
Sometimes we don't, and in such cases we just want the animal name to span the whole table.
The initial markup looks like this:
HTML
<table>
<tr>
<th>Animals</th>
</tr>
<tr>
<th>Hippopotamus</th>
</tr>
<tr>
<th>Horse</th>
<td>Mare</td>
</tr>
<tr>
<td>Stallion</td>
</tr>
<tr>
<th>Crocodile</th>
</tr>
<tr>
<th>Chicken</th>
<td>Hen</td>
</tr>
<tr>
<td>Rooster</td>
</tr>
</table>
But the output doesn't give us quite what we want:
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
8/15

Animals
Hippopotamus
Horse
Mare
Stallion
Crocodile
Chicken
Hen
Rooster
Fixing the layout with rowspan and colspan
We need a way to get "Animals", "Hippopotamus", and "Crocodile" to span across two columns, and "Horse" and
"Chicken" to span over two rows. Fortunately, HTML tables provide the colspan  and rowspan  attributes to achieve
this. Both accept a unitless number value equal to the number of rows or columns to span. For example, colspan="2"
makes a cell span two columns.
Let's use colspan  and rowspan  to improve this table.
1. Make another local copy of our 
 and 
 files in a new directory on your
local machine.
2. Add the following into your HTML <body> :
HTML
<table>
<tr>
<th>Animals</th>
</tr>
<tr>
<th>Hippopotamus</th>
</tr>
<tr>
<th>Horse</th>
<td>Mare</td>
</tr>
<tr>
<td>Stallion</td>
</tr>
<tr>
blank-template.html
minimal-table.css
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
9/15

<th>Crocodile</th>
</tr>
<tr>
<th>Chicken</th>
<td>Hen</td>
</tr>
<tr>
<td>Rooster</td>
</tr>
</table>
3. Sonraki, use colspan  to make "Animals", "Hippopotamus", and "Crocodile" span across two columns.
4. Finally, use rowspan  to make "Horse" and "Chicken" span across two rows.
5. Save and open your code in a browser to see the improvement.
Click here to show the solution
Grouping columns with <colgroup> and
<col>
There is a way to target entire table columns as a single entity, for example, when applying styles to a table (which you'll
learn about later in Styling tables). As you get more experience with creating HTML tables, you'll find that applying a
background color, for example, to every cell in a single column is harder than you might think. The <colgroup>  and
<col>  elements provide a solution to this problem.
The <colgroup>  element is included as a child of the table, just after the opening <table>  element. Inside the
<colgroup>  element, you can include one or more <col>  elements, which represent groups of columns. The <col>
element can include a span  attribute that indicates the number of columns in that group. It can also include global
attributes such as style  (to target the group with inline styles) or class  (to target the group with CSS or JavaScript
using a class name). The <col>  elements represent the table columns from the start of the columns, for example from
the left-hand side of a table written in a left-to-right language such as English.
Let's have a look at an example to show what we mean. The following table shows a school timetable:
HTML
<h1>School language timetable</h1>
<table>
<colgroup>
<col span="2" />
<col class="column-background" />
<col class="column-fixed-width" />
<col class="column-background" />
<col class="column-background-border" />
<col span="2" class="column-fixed-width" />
</colgroup>
<tr>
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
10/15

<td>&nbsp;</td>
<th>Mon</th>
<th>Tues</th>
<th>Wed</th>
<th>Thurs</th>
<th>Fri</th>
<th>Sat</th>
<th>Sun</th>
</tr>
<tr>
<th>1st period</th>
<td>English</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>German</td>
<td>Dutch</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<th>2nd period</th>
<td>English</td>
<td>English</td>
<td>&nbsp;</td>
<td>German</td>
<td>Dutch</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<th>3rd period</th>
<td>&nbsp;</td>
<td>German</td>
<td>&nbsp;</td>
<td>German</td>
<td>Dutch</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<th>4th period</th>
<td>&nbsp;</td>
<td>English</td>
<td>&nbsp;</td>
<td>English</td>
<td>Dutch</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
11/15

</tr>
</table>
This table has eight columns. Let's look at the <colgroup>  and <col>  structure more closely to show how it affects
them:
HTML
<colgroup>
<col span="2" />
<col class="column-background" />
<col class="column-fixed-width" />
<col class="column-background" />
<col class="column-background-border" />
<col span="2" class="column-fixed-width" />
</colgroup>
Looking at the <col>  elements:
The first one has span="2"  set on it, so it represents the first and second columns from the left of the table. We
are not targeting these columns with any styles; it allows us to target subsequent columns.
The second and fourth ones don't have a span  attribute set, so they will represent a single column — the third
and fifth columns in these cases. They have a class  of column-background  applied.
The third one doesn't have a span  attribute set and has a class  of column-fixed-width  applied. It represents
the fourth column.
The fifth one doesn't have a span  attribute set, and has a class  of column-background-border  applied. It
represents the sixth column.
The sixth one has span="2"  set on it, and has a class  of column-fixed-width  applied. It represents the
seventh and eighth columns.
We have hidden most of the CSS for this example, but we are showing you the rules that apply styles to the <col>
elements with the column-background , column-fixed-width , and column-background-border  classes set on them:
CSS
.column-background {
background-color: #97db9a;
}
.column-fixed-width {
width: 40px;
}
.column-background-border {
background-color: #dcc48e;
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
12/15

border: 4px solid #c1437a;
}
The <col>  elements with a column-background  class have a solid background color set on them.
The <col>  elements with a column-fixed-width  class have a narrow fixed width set on them.
The <col>  element with a column-background-border  class has a solid background color and a thick border
set on it.
You don't need to worry about how the CSS works for now; you'll learn about it in detail later on in our CSS styling
basics module.
Let's look at how the above code renders:
School language timetable
 
Mon
Tues
Wed
Thurs
Fri
Sat
Sun
1st
period
English
 
 
German
Dutch
 
 
2nd
period
English
English
 
German
Dutch
 
 
3rd
period
 
German
 
German
Dutch
 
 
4th
period
 
English
 
English
Dutch
 
 
Notice how the different columns receive the styles specified in the classes.
Do <col> styles clash with other table styles?
The answer is "yes". Styles set on tables are painted in the order of styles set on <table> , then <col> , then <tr> ,
then <th>  and <td> . This means that styles set on table rows, headings, and cells will overwrite column styles.
Try this out by adding column styles to the template example you worked on earlier in the article. If you add the
following to the HTML above the first <tr>  tag:
Note: Even though <colgroup>  and <col>  mainly facilitate styling, they are an HTML feature, so we've
covered them here rather than in our CSS modules. They are a limited feature — as shown on the <colgroup>
reference page, only a limited subset of styles can be applied to a <col>  element. Most other styles that were
historically available have been deprecated (removed, or flagged for removal).
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
13/15

HTML
<colgroup>
<col span="2" style="border: 2px solid black; background-color: red" />
</colgroup>
You'll see that the first two columns of the table get a 2px
black  border, but they don't get a red  background color.
This is because the table headings and rows have the following styles set on them inside minimal-table.css , which
override the column styles:
CSS
th {
background-color: rgb(235 235 235);
}
tr:nth-child(even) td {
background-color: rgb(250 250 250);
}
tr:nth-child(odd) td {
background-color: rgb(220 220 220);
}
Remove these background-color  styles to see the red  background color.
Interactive recap of table concepts
The following embedded content from ScrimbaMDN learning partner provides an interactive lesson summarizing most of
the techniques covered in this article. Check it out for a recap of the key points and some extra practice.
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
14/15

Clicking will load content from scrimba.com
Summary
That wraps up the basics of HTML tables. In the next article, we'll look at some further features that can be used to
make HTML tables more accessible to visually impaired people.
Önceki
Genel bakış: HTML ile içeriği yapılandırma
Sonraki
Your blueprint for a better internet.
HTML TABLES
15.10.2026 20:24
HTML table basics - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics
15/15


---

HTML
Table accessibility
HTML table accessibility
Previous
Overview: Structuring content with HTML
Next
In the previous article, we looked at one of the most important features for making HTML tables accessible to visually
impaired users — the <th>  element. In this article, we continue down this path, looking at more HTML table
accessibility features such as captions/summaries, grouping your rows into table head, body and footer sections, and
scoping columns and rows.
Prerequisites:
The basics of HTML (see Basic HTML Syntax).
Learning
outcomes:
An understanding of the accessibility issues associated with tables.
Adding captions to tables.
Better table structuring with head, body, and footer.
Creating further association between headers and cells with the scope , id , and
headers  attributes.
Recap: Tables for visually impaired users
Let's recap briefly on how we use data tables. A table can be a handy tool, for giving us quick access to data and
allowing us to look up different values. For example, it takes only a short glance at the table below to find out how many
rings were sold in Ghent during August 2016. To understand its information, we make visual associations between the
data in this table and its column and/or row headers.
Items Sold August 2016
Clothes
Accessories
Trousers
Skirts
Dresses
Bracelets
Rings
Belgium
Antwerp
56
22
43
72
23
Ghent
46
18
50
61
15
Brussels
51
27
38
69
28
The Netherlands
Amsterdam
89
34
69
85
38
Utrecht
80
12
43
36
19
But what if you cannot make those visual associations? How then can you read a table like the above? Visually impaired
people often use a screen reader that reads out information on web pages to them. This is no problem when you're
English (US)
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
1/10


reading plain text but interpreting a table can be quite a challenge for a blind person. Nevertheless, with the proper
markup we can replace visual associations by programmatic ones.
Using column and row headers
Screen readers will identify all headers and use them to make programmatic associations between those headers and
the cells they relate to. The combination of column and row headers will identify and interpret the data in each cell so
that screen reader users can interpret the table similarly to how a sighted user does.
We already covered headers in our previous article — see Adding headers with <th> elements.
Adding a caption to your table with <caption>
You can give your table a caption by putting it inside a <caption>  element and nesting that inside the <table>
element. You should put it just below the opening <table>  tag.
HTML
<table>
<caption>
Dinosaurs in the Jurassic period
</caption>
<!-- … -->
</table>
As you can infer from the brief example above, the caption is meant to contain a description of the table contents. This is
useful for all readers wishing to get a quick idea of whether the table is useful to them as they scan the page, but
particularly for blind users. Rather than have a screen reader read out the contents of many cells just to find out what the
table is about, the user can rely on a caption and then decide whether or not to read the table in greater detail.
A caption is placed directly beneath the <table>  tag.
Table caption practice
At this point we'll get you to try out adding a caption to an HTML table, using the school timetable you met in the
previous article.
1. Copy the first HTML block in the Grouping columns with <colgroup>  and <col>  into an HTML file on your
computer, or an online editor such as 
 or 
.
2. Add a suitable caption to the table.
3. Save your code and see what it looks like.
Note: There are around 253 Million people living with Visual Impairment according to 
.
WHO data in 2017
Note: The summary  attribute can also be used on the <table>  element to provide a description — this is also
read out by screen readers. We'd recommend using the <caption>  element instead, however, as summary  is
deprecated and can't be read by sighted users (it doesn't appear on the page).
CodePen
JSBin
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
2/10


Click here to show the solution
Adding structure with <thead>, <tbody>, and
<tfoot>
As your tables get a bit more complex in structure, it is useful to give them more structural definition. One clear way to
do this is by using <thead> , <tbody> , and <tfoot> , which allow you to mark up a header, body, and footer section for
the table.
These elements don't necessarily make the table any more accessible to screen reader users. They don't result in any
visual enhancement on their own, however they are very useful for applying styling and layout enhancements via CSS,
which can improve accessibility. To give you some interesting examples, in the case of a long table you could make the
table header and footer repeat on every printed page, and you could make the table body display on a single page and
have the contents available by scrolling up and down.
To use them, they should be included in the following order:
The <thead>  element must wrap the part of the table that is the header — this is usually the first row containing
the column headings, but this is not necessarily always the case. If you are using <col> / <colgroup>  elements,
the table header should come just below those.
The <tbody>  element needs to wrap the main part of the table content that isn't the table header or footer, and
should come after the <thead> .
The <tfoot>  element needs to wrap the part of the table that is the footer — this might be a final row with items
in the previous rows summed, for example. The <tfoot>  should come after the <tbody> .
Adding structure to a spending record table
Let's get you to put these new elements into action.
1. First of all, create a new HTML file called spending-record.html  and put the following HTML inside the
<body> :
HTML
<h1>My spending record</h1>
<table>
<caption>
How I chose to spend my money
</caption>
<tr>
<th>Purchase</th>
Note: <tbody>  is always implicitly included in every table if you don't specify it in your code. To check this,
open up one of your previous examples that doesn't include <tbody>  and look at the HTML code in your
browser developer tools — you will see that the browser has added this tag for you. You might wonder why you
ought to bother including it at all — you should, because it gives you more control over your table structure and
styling.
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
3/10


<th>Location</th>
<th>Date</th>
<th>Evaluation</th>
<th>Cost (€)</th>
</tr>
<tr>
<td>Haircut</td>
<td>Hairdresser</td>
<td>12/09</td>
<td>Great idea</td>
<td>30</td>
</tr>
<tr>
<td>Lasagna</td>
<td>Restaurant</td>
<td>12/09</td>
<td>Regrets</td>
<td>18</td>
</tr>
<tr>
<td>Shoes</td>
<td>Shoe shop</td>
<td>13/09</td>
<td>Big regrets</td>
<td>65</td>
</tr>
<tr>
<td>Toothpaste</td>
<td>Supermarket</td>
<td>13/09</td>
<td>Good</td>
<td>5</td>
</tr>
<tr>
<td>SUM</td>
<td>118</td>
</tr>
</table>
2. Next, create a CSS file called minimal-table.css  in the same directory as your HTML file and fill it with the
following content:
CSS
html {
font-family: sans-serif;
}
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
4/10


table {
border-collapse: collapse;
border: 2px solid rgb(200 200 200);
letter-spacing: 1px;
font-size: 0.8rem;
}
td,
th {
border: 1px solid rgb(190 190 190);
padding: 10px 20px;
}
th {
background-color: rgb(235 235 235);
}
td {
text-align: center;
}
tr:nth-child(even) td {
background-color: rgb(250 250 250);
}
tr:nth-child(odd) td {
background-color: rgb(245 245 245);
}
caption {
padding: 10px;
}
3. Add a <link>  element into your HTML <head>  to apply the CSS to the HTML (see Applying CSS and JavaScript
to HTML for help with this).
4. Try putting the obvious headers row inside a <thead>  element, the "SUM" row inside a <tfoot>  element, and
the rest of the content inside a <tbody>  element.
5. Next, add a colspan  attribute to make the "SUM" cell span across the first four columns, so the actual number
appears at the bottom of the "Cost" column.
6. Let's add some simple extra styling to the table, to give you an idea of how useful these elements are for applying
CSS. Add the following to your CSS file:
CSS
tbody {
font-size: 95%;
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
5/10


font-style: italic;
}
tfoot {
font-weight: bold;
}
7. Save and refresh, and have a look at the result. If the <tbody>  and <tfoot>  elements weren't in place, you'd
have to write much more complicated selectors/rules to apply the same styling.
The finished example should look like this:
Click here to show the solution
The scope attribute
The scope  attribute can be added to the <th>  element to tell screen readers exactly what cells the header is a header
for — is it a header for the row it is in, or the column, for example? Looking back to our spending record example from
earlier on, you could unambiguously define the column headers as column headers like this:
HTML
<thead>
<tr>
<th scope="col">Purchase</th>
<th scope="col">Location</th>
<th scope="col">Date</th>
Note: We don't expect you to fully understand the CSS right now. You'll learn more about this when you
go through our CSS modules (starting with CSS Styling basics, which includes an article specifically on
styling tables).
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
6/10


<th scope="col">Evaluation</th>
<th scope="col">Cost (€)</th>
</tr>
</thead>
And each row could have a header defined like this (if we added row headers as well as column headers):
HTML
<tr>
<th scope="row">Haircut</th>
<td>Hairdresser</td>
<td>12/09</td>
<td>Great idea</td>
<td>30</td>
</tr>
Screen readers will recognize markup structured like this, and allow their users to read out the entire column or row at
once, for example.
scope  has two more possible values — colgroup  and rowgroup . These are used for headings that sit over the top of
multiple columns or rows. If you look back at the "Items Sold August 2016" table at the start of this section of the article,
you'll see that the "Clothes" cell sits above the "Trousers", "Skirts", and "Dresses" cells. All of these cells should be
marked up as headers ( <th> ), but "Clothes" is a heading that sits over the top and defines the other three subheadings.
"Clothes" therefore should get an attribute of scope="colgroup" , whereas the others would get an attribute of
scope="col" :
HTML
<thead>
<tr>
<th colspan="3" scope="colgroup">Clothes</th>
</tr>
<tr>
<th scope="col">Trousers</th>
<th scope="col">Skirts</th>
<th scope="col">Dresses</th>
</tr>
</thead>
The same applies to headers for multiple grouped rows. Take another look at the "Items Sold August 2016" table, this
time focusing on the rows with the "Amsterdam" and "Utrecht" headers ( <th> ). You'll notice that the "The Netherlands"
header, also marked up as a <th>  element, spans both rows, being the heading for the other two subheadings.
Therefore, scope="rowgroup"  should be specified on this header cell to help screen readers create the correct
associations:
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
7/10


HTML
<tr>
<th rowspan="2" scope="rowgroup">The Netherlands</th>
<th scope="row">Amsterdam</th>
<td>89</td>
<td>34</td>
<td>69</td>
</tr>
<tr>
<th scope="row">Utrecht</th>
<td>80</td>
<td>12</td>
<td>43</td>
</tr>
The id and headers attributes
An alternative to using the scope  attribute is to use id  and headers  attributes to create associations between data
cells and header cells.
A <th>  element can provide a heading for either a data cell ( <td> ) or, in more complex tables, for another header cell
( <th> ). This allows you to create layered or grouped headers, where one header describes several others.
The headers  attribute is used to link a cell, <td>  or <th> , to one or more header cells. It takes a space-separated list
of strings; the order of strings does not matter. Each string must match the unique id  of a <th>  element that the cell is
associated with.
This method gives your HTML table a more explicit definition of the position of each cell, based on the headers for the
column and the row it belongs to, kind of like a spreadsheet. For this to work well, your table should include both column
and row headers.
Let's look at a portion of the "Items Sold August 2016" example to see how to use the id  and headers  attributes:
1. Add a unique id  to each <th>  element in the table.
2. For the header cells: Add a headers  attribute to each <th>  element that acts as a subheading, that is, a header
cell with another header above it. The value is the id  of the high-level heading. In our example, that's
"clothes"  for the column headers and "belgium"  for the row header.
3. For the data cells: Add a headers  attribute to each <td>  element, and add the id s of the associated <th>
element(s) as a space-separated list. You can proceed as you would in a spreadsheet: Find the data cell, then
locate the row and column headers that describe it. The order of the specified id s doesn't matter, but keeping it
consistent helps to keep it organized and improves readability of the code.
HTML
<thead>
<tr>
<th></th>
<th></th>
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
8/10


<th id="clothes" colspan="3">Clothes</th>
</tr>
<tr>
<th></th>
<th></th>
<th id="trousers" headers="clothes">Trousers</th>
<th id="skirts" headers="clothes">Skirts</th>
<th id="dresses" headers="clothes">Dresses</th>
</tr>
</thead>
<tbody>
<tr>
<th id="belgium" rowspan="2">Belgium</th>
<th id="antwerp" headers="belgium">Antwerp</th>
<td headers="belgium antwerp clothes trousers">56</td>
<td headers="belgium antwerp clothes skirts">22</td>
<td headers="belgium antwerp clothes dresses">43</td>
</tr>
<tr>
<th id="ghent" headers="belgium">Ghent</th>
<td headers="belgium ghent clothes trousers">41</td>
<td headers="belgium ghent clothes skirts">17</td>
<td headers="belgium ghent clothes dresses">35</td>
</tr>
</tbody>
In this example:
The <th>  for "Belgium"  uses rowspan="2"  to span both "Antwerp"  and "Ghent" .
The city header cells ( "Antwerp"  and "Ghent" ) use the headers  attribute to reference "belgium"  to show
they belong to the Belgium group.
Each <td>  includes a headers  attribute for country ( belgium ), city ( antwerp  or ghent ), group ( clothes ),
and the specific clothing item ( trousers , skirts , or dresses ).
Playing with scope and headers
For this final exercise, we will get you to try using scope and headers on the sample table we introduced above.
1. First make local copies of 
 and 
, in a new directory.
2. Try adding in the appropriate scope  attributes to make this table more accessible.
3. Making another copy of the starter files in another local directory
4. This time make the table more accessible by creating precise and explicit associations using id  and headers
attributes.
Click here to show the solution
Note: This method creates very precise associations between headers and data cells but it uses a lot more
markup and does not leave any room for errors. The scope  approach is usually sufficient for most tables.
items-sold.html
minimal-table.css
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
9/10


Summary
There are a few other things you could learn about tables in HTML, but this is all you need to know for now. Next, you
can test yourself with our HTML tables challenge. Have fun!
Previous
Overview: Structuring content with HTML
Next
Your blueprint for a better internet.
15.10.2026 20:24
HTML table accessibility - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Table_accessibility
10/10


---

HTML
Challenge: Planet data table
Challenge: Structuring a planet data
table
Previous
Overview: Structuring content with HTML
Next
In this challenge, we provide data on the planets in our solar system. Your job is to structure it into an accessible HTML
table.
Starting point
1. Create a new folder in an appropriate location on your computer called planet-data-table  (or open an online
editor and take the required steps to create a new project).
2. Save the following HTML listing inside a file inside your folder called index.html  (or paste it into your online
editor's HTML pane).
HTML
<!doctype html>
<html lang="en-US">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width" />
<title>Planet data table</title>
<link href="style.css" rel="stylesheet" type="text/css" />
</head>
<body>
<h1>Planet data table</h1>
</body>
</html>
3. Save the following CSS listing inside a file inside your folder called style.css  (or paste it into your online
editor's CSS pane).
CSS
html {
font-family: sans-serif;
}
English (US)
15.10.2026 20:24
Challenge: Structuring a planet data table - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Planet_data_table
1/5


table {
border-collapse: collapse;
border: 2px solid rgb(200 200 200);
letter-spacing: 1px;
font-size: 0.8rem;
}
td,
th {
border: 1px solid rgb(190 190 190);
padding: 10px 20px;
}
th {
background-color: rgb(235 235 235);
}
td {
text-align: center;
}
tr:nth-child(even) td {
background-color: rgb(250 250 250);
}
tr:nth-child(odd) td {
background-color: rgb(245 245 245);
}
caption {
padding: 10px;
}
.column-border {
border: 2px solid black;
}
4. Keep the following data handy; you'll need to turn this into an HTML data table inside your HTML.
Rows
Terrestrial planets
Mercury 0.330 4,879 5427 3.7 4222.6 57.9 167 0 Closest to the Sun
Venus 4.87 12,104 5243 8.9 2802.0 108.2 464 0
Earth 5.97 12,756 5514 9.8 24.0 149.6 15 1 Our world
Mars 0.642 6,792 3933 3.7 24.7 227.9 -65 2 The red planet
15.10.2026 20:24
Challenge: Structuring a planet data table - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Planet_data_table
2/5


Jovian planets
Gas giants
Jupiter 1898 142,984 1326 23.1 9.9 778.6 -110 67 The largest planet
Saturn 568 120,536 687 9.0 10.7 1433.5 -140 62
Ice giants
Uranus 86.8 51,118 1271 8.7 17.2 2872.5 -195 27
Neptune 102 49,528 1638 11.0 16.1 4495.1 -200 14
Dwarf planets*
Pluto 0.0146 2,370 2095 0.7 153.3 5906.4 -225 5 Declassified as a planet in 2006, but
this <a href="http://www.usatoday.com/story/tech/2014/10/02/pluto-planet-solar-
system/16578959/">remains controversial</a>.
Columns
Name
Mass (10<sup>24</sup>kg)
Diameter (km)
Density (kg/m<sup>3</sup>)
Gravity (m/s<sup>2</sup>)
Length of day (hours)
Distance from Sun (10<sup>6</sup>km)
Mean temperature (°C)
Number of moons
Notes
Caption
Data about the planets of our solar system (Planetary facts taken from <a
href="http://nssdc.gsfc.nasa.gov/planetary/factsheet/">Nasa's Planetary Fact Sheet -
Metric</a>).
Project brief
You are working at a school; currently, your students are studying the planets of our solar system, and you want to
provide them with an easy-to-follow set of data to look up facts and figures about the planets. An HTML data table would
be ideal — you need to take the raw data you have available and turn it into a table, following the steps below.
All the data you need is contained in the data listing provided above. If you have trouble visualizing the data, take a look
at the live example below, or try drawing a diagram.
1. Start the table off by giving it an outer container, a table header, and a table body. You don't need a table footer
for this example.
2. Add the provided caption to your table.
15.10.2026 20:24
Challenge: Structuring a planet data table - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Planet_data_table
3/5


3. Add a row to the table header containing all the column headers.
4. Create all the content rows inside the table body, remembering to make all the row headings into headings
semantically.
5. Ensure all the content is placed into the right cells — in the raw data, each row of planet data is shown next to its
associated planet.
6. Add attributes to make the row and column headers unambiguously associated with the rows, columns, or row
groups that they act as headings for.
7. Add a black border just around the column that contains all the planet name row headers. Do this using a suitable
<colgroup> / <col>  structure and the .column-border  class style provided in the CSS.
Hints and tips
The first cell of the header row needs to be blank, and span two columns.
The group row headings (e.g., Jovian planets) that sit to the left of the planet name row headings (e.g., Saturn)
are a little tricky to sort out — you need to make sure each one spans the correct number of rows and columns.
One way of associating headers with their rows/columns is a lot easier than the other way.
Example
The table should look like the following after being marked up correctly. If you get stuck, check out the solution below
the live example.
15.10.2026 20:24
Challenge: Structuring a planet data table - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Planet_data_table
4/5


Click here to show the solution
Previous
Overview: Structuring content with HTML
Next
Your blueprint for a better internet.
15.10.2026 20:24
Challenge: Structuring a planet data table - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Planet_data_table
5/5


---

HTML
Forms and buttons
Forms and buttons in HTML
Previous
Overview: Structuring content with HTML
Next
HTML forms and buttons are powerful tools for interacting with a website's users. Most commonly, they provide users
with controls to manipulate a user interface (UI) or input data when required.
In this article, we provide an introduction to the basics of forms and buttons. There is a lot more to know — a lot of input
types and form features are not mentioned — but this article will give you a solid foundation for most cases. You can
learn the advanced or specialized uses on a need-to-know basis as part of the constant learning you'll do throughout
your career.
Prerequisites:
Basic HTML familiarity, as covered in Basic HTML Syntax. Text-level semantics such as
headings and paragraphs and lists. Structural HTML.
Learning
outcomes:
An appreciation that forms and buttons are the main tools for users to interact with a
website, along with links.
Different button types.
Common <input>  types.
Common attributes such as name  and value .
The <form>  element, and the basics of form submission.
Making forms accessible with labels and correct semantics.
Other control types: <textarea> , <select> , and <option> .
Client-side validation basics.
Interacting with users
So far in the course, you have seen a couple of ways in which users can interact with the web:
Links can be used to navigate to different sections of content, either on the same page or a different page.
<video>  and <audio>  elements generally feature controls such as play/pause, fast forward, rewind, etc., which
allow users to consume media content as they wish.
However, these features tend to facilitate one-way interactions, with users passively consuming content. This is fine, but
the web is a two-way experience. Website users set preferences for how they want to experience content and services.
They order taxis and request call backs. They provide feedback and make complaints. They buy products and get them
delivered to their homes.
To provide this two-way experience, you need to use buttons and forms.
Buttons are usually created using HTML <button>  elements (they are also sometimes created using <input>  elements
with their type  attributes set to a value like button  or submit ). These push buttons are general-purpose — you can
wire them up to trigger any functionality you want, limited only by your imagination and coding skills.
English (US)
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
1/14


Forms are created using elements such as <form> , <label> , <input> , and <select> . Form elements can be used to
create more complex controls than simple buttons allow — for example, a drop-down menu containing multiple options
that allow you to choose between different themes for a user interface element.
However, crucially, they can also be used to create forms for users to fill in when they need to submit information to a
website server. Think about e-commerce sites — when you want to search for a product to buy, you use a form to enter
search terms. When you want to pay for some items and finalize delivery, you use a form to enter your postal address,
and another form to enter your credit card details.
We'll be concentrating mainly on this — more traditional — use of form elements in this article. Note that buttons are also
commonly used inside forms to submit the entered data to the server.
With this important theory out of the way, let's move on to explore the code and see how buttons and forms are
implemented.
Buttons
As hinted at above, buttons have a couple of main uses on the web. First of all, they are used to trigger functionality,
which is useful when creating UI controls. The simplest button is implemented using the following code:
HTML
<button>Press me</button>
This is rendered as follows:
Press me
The text appearing in-between the <button></button>  tags is rendered inside the button, and it is given some basic
styling by the browser so it will look and behave like a button by default. So far, so good. However, there is an issue here
— our lonesome button won't do anything useful on its own. To make it do something useful, you'll need to put it inside a
form (which we'll cover later on), or add some JavaScript.
For example, if you applied the following JavaScript to the above button:
JS
const btn = document.querySelector("button");
btn.addEventListener("click", () => {
btn.textContent = "YOU CLICKED ME!! ❤️";
setTimeout(() => {
btn.textContent = "Press me";
}, 1000);
});
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
2/14


It would give you the following output — try clicking it:
Press me
You are not expected to understand how the JavaScript works for now. You'll learn more about it later on in the course.
In the next section, you'll see a demonstration of the second main use of buttons — submitting forms.
The anatomy of a form
A basic form contains three things:
A <form>  element, which wraps all of the other form content. Any form controls inside the <form></form>  tags
are part of the same form, and their data is included when the form is submitted.
One or more pairs each consisting of a <label>  element and a form control element (usually an <input>
element, but there are other types as well, for example <select> ):
The form control element allows the user to choose or enter some data, which will be sent to the server
when the form is submitted.
The <label>  element provides an identifying label associated with the form control describing the data
that should be entered into it.
A <button>  element, used to submit the form.
Let's look at a basic example that includes the above three items. This form could be used to ask for a user's name and
email, to sign them up for a newsletter (don't worry — it isn't connected to any server, so currently won't do anything).
HTML
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<title>First form</title>
</head>
<body>
<form action="./submit_page" method="get">
<h2>Subscribe to our newsletter</h2>
<p>
<label for="name">Name (required):</label>
<input type="text" name="name" id="name" required />
</p>
<p>
<label for="email">Email (required):</label>
<input type="email" name="email" id="email" required />
</p>
<p>
<button>Sign me up!</button>
</p>
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
3/14


</form>
</body>
</html>
This is rendered as follows:
Subscribe to our newsletter
Name (required): 
Email (required): 
Sign me up!
If you click "Sign me up!" right away, you'll see a validation error because you didn't enter any data. If you fill out the
fields with a name and email address, and then click "Sign me up!", nothing happens—this is because we prevent the
form from submitting, which would navigate you away from this page.
Before moving on, copy the previous HTML code listing into a new HTML file using your code editor and open it in a new
browser tab.
The <form> element
As we said earlier, the <form>  element acts as the outer wrapper for the form, grouping all the form controls inside it.
When the <button>  is pressed, all the data represented by the form controls will be submitted to the server. The
<form>  element can take many attributes, but the two most important ones, which we've included in our example, are
as follows:
action : Contains a path to the page that we want to send the submitted form data to, to be processed. Later on,
after you submit the form, you'll see /submit_page  included in the URL. You'll also get a 404  error response
because the page doesn't actually exist, but that's fine for now.
method : Specifies the data transmission method you want to use for sending the form data to the server. Don't
worry about this too much for now; the get  value causes the data to be sent as parameters attached to the end
of the URL.
Checking out the submitted data
1. Go to the example in the separate tab, try entering a name of "Bob" and an email address of "bob@bob.com".
2. Press the <button> .
The action  and method  attributes cause the form data to be submitted in a URL along the following lines:
/some/url/submit_page?name=Bob&email=bob%40bob.com
Structuring forms
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
4/14


You can include any HTML elements you like inside a <form>  element to structure the form elements themselves and
provide containers to target with CSS for styling, etc.
In our example, we've included a heading element ( <h2> ) to describe the purpose of the form.
We've also put each input/label pair and the submit button inside a separate <p> , so that each will appear on a separate
line. These elements are all inline by default, meaning that if we didn't do this, they would all sit on the same line.
This is a common pattern for form structuring. Some people use <p>  elements to separate out their form elements,
some use <div> , <section> , or even <li>  elements. It doesn't matter a great deal, as long as the elements used
make semantic sense. For example, it makes sense to divide form element groups up into separate paragraphs or
sections of content, or even items in a list. It would make less sense to represent them as blockquotes, asides, or
addresses.
There is a specialized element for grouping form elements together called <fieldset> . This is useful in certain
circumstances, such as in complex forms and when grouping multiple checkboxes and radio buttons. We'll look at a
couple of <fieldset>  examples later on.
<input> elements
The <input>  elements represent the different data items entered into the form. Let's study one of the examples from
our basic form:
HTML
<input type="text" name="name" id="name" required />
The attributes are as follows:
type : Specifies the type of form control to create. There are many different types of form controls, from simple
text fields of different types to radio buttons, checkboxes, and more. Type text  renders a basic text field that
can accept any value.
name : Specifies a name for the data item. When the form is submitted, the data is sent in name/value pairs. In
each case, the name is equal to this name  attribute value, and the value is equal to the text entered in the text
field.
id : Specifies an ID that can be used to identify the element. In this case, it is used to associate the form control
with its <label> .
required : Specifies that a value has to be entered into the form element before the form can be submitted. This
should only be set on inputs that you require, not on optional fields.
You should be aware that some input types usually don't get their values from text entered into a field. For example,
<input type="color">  renders a color picker widget that you choose a color from, whereas <input type="radio">
renders a radio button control that can be selected, or not.
In the case of radio buttons, you generally need to provide the value that would be submitted if it is selected inside a
specific value  attribute. Note that you can specify a value  attribute on input types like text  and color  — the effect
is that the value is pre-filled into the form field when it is first rendered.
required and value attributes in action
1. Again, go to the example you loaded in a separate tab, and try submitting the form with no value entered in either
field. You'll see an error message pop up next to the "Name" field saying something like "Please fill in this field"
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
5/14


(it will vary across different browsers). This is the required  attribute — and the browser's default client-side
form validation — in action.
2. Now try submitting the form with a valid name entered in the first field, but a value that is not a valid email
address in the second field (something like "aaaa" will do). This time you'll see an error message pop up next to
the "Email" field saying something like "Please enter an email address".
3. Try editing the form to include value="Bob"  on the first input. When you reload the code, you'll see that the first
field has a value of "Bob" entered into it by default.
Specialized text field inputs
The second exercise above raises an interesting point. The second input field specifically expects an email address and
validates entered values as such. If you look at the form code again, you'll see why — the second <input>  has a type
of email .
There are several specialized text field input types designed to handle specific types of data such as <input
type="number"> , <input type="password"> , <input type="tel"> , <input type="url"> , and so on.
Follow some of the links above to find out what these input types are used for. Have a look around our <input>
reference and see if you can find any more specialized text field input types.
<label> elements
As we said above, <label>  elements provide identifying labels associated with form controls that describe the data that
should be entered into them. You can put whatever text content you like in <label>  elements, but they should
accurately describe what data the associated form control expects. The association is created by giving the form control
an id  attribute, then giving the <label>  element a for  attribute with the same value as the control's id .
For example:
HTML
<label for="name">Name (required):</label>
<input type="text" name="name" id="name" required />
<label>  elements are important for several reasons, most notably that:
When visually impaired users use a screen reader to help them read and interact with web page content, the
screen reader will read out the associated label text when each control is encountered. This makes it easier for
the users to understand what content should be entered into each control.
They enable you to focus the form elements by clicking on their label text as well as the controls. This is
especially useful for mobile phone users, where it can be difficult to accurately select a form element with your
finger on a touch screen. Making the hit area larger is useful in such circumstances.
Explicit and implicit form labels
The form label style you saw above is called an explicit form label — the association between control and label is
explicitly made via the id  and for  attributes. You can also implement an implicit form label by nesting the control
inside the label, like this:
HTML
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
6/14


<label>
Name (required):
<input type="text" name="name" required />
</label>
The nesting makes an implicit association between control and label, and you no longer need the id  and for
attributes.
Either approach is OK, but we'd recommend using the explicit labeling approach. This is because the explicit association
is usually easier to identify and understand, especially as your HTML code gets more complex. In addition, screen
readers (and other assistive technologies) don't always handle implicit labels correctly.
You can read more about form labeling best practices in 
, csstricks.com (2021).
The <button> element
When a <button>  element is included inside a <form>  element, its default behavior is that it will submit the form,
provided there is no invalid data present, causing submission to be blocked by client-side form validation. You've already
seen this behavior when playing with our basic form example above.
Other button behaviors can be specified via the <button>  element's type  attribute:
<button type="submit">  explicitly declares that a button should behave like a submit button. You don't ever
really need to declare this, unless for some reason you are including other buttons inside your <form> , and you
want to make it clear which one the submit button is. This will be very rare.
<button type="reset">  creates a reset button — this immediately deletes all data out of the form, resetting it to
its initial state. Don't use reset buttons — they used to be popular in the early days of the web, but they are
usually more annoying than they are helpful. Most people have experienced filling out a long form only to click
the reset button by accident instead of the submit button, meaning they have to start again.
<button type="button">  creates a button with the same behavior as buttons specified outside of <form>
elements. As we saw earlier, they do absolutely nothing by default, and JavaScript is needed to give them
functionality.
Although you can create these button types by using an <input>  element with the same type  values – such as <input
type="submit"> , <input type="reset"> , and <input type="button">  – they have many disadvantages compared
to their <button>  counterparts. So you should use <button>  instead.
An aside on accessibility
We've already talked about the importance of form labels for accessibility, but we also wanted to include some
commentary on the general importance of using the correct semantic elements to create forms (for example, use a
<button>  to submit your form, and not a <div>  programmed to behave like a <button> .) It is perfectly possible to
use a combination of CSS and JavaScript to make pretty much any HTML element look and behave like a form element.
Developers usually do this for design reasons — some form controls are hard to style.
However, when you do this, you are making life harder for yourself and your users. The browser provides several
<button>  and form control features by default, with no JavaScript or other extra code required, to make forms more
HTML Inputs and Labels: A Love Story
Note: ScrimbaMDN learning partner has a free lesson — 
 — which provides a useful
interactive recap of the form basics we covered previously in this article.
The very basics of forms
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
7/14


usable for all users.
For example:
Semantic elements are understood by assistive technology such as screen readers, which communicate their
meaning to users who cannot see them.
Form controls and buttons are keyboard-accessible by default. In the previous example, try moving forward and
backward between the form elements using Tab  and Shift  + Tab  (called "tabbing").
Notice also how tabbing between the form elements causes the focused element to be highlighted using a blue
outline (called the focus outline). This is an important feature for keyboard users to know where they currently
are in the form.
If you don't use the correct semantic elements to implement your forms, your form elements will not behave as users
expect and will seem broken. You'll have to re-implement all of this functionality yourself, which all adds up.
Other control types
There are many other control types you can use to collect data in a form. Let's look at a slightly more complex example,
and then we'll explore and explain it.
HTML
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<title>Second form</title>
</head>
<body>
<form action="./payment_page" method="get">
<h2>Register for the meetup</h2>
<fieldset>
<legend>Choose hotel room type:</legend>
<div>
<input
type="radio"
id="hotelChoice1"
name="hotel"
value="economy"
checked />
<label for="hotelChoice1">Economy (+$0)</label>
<input type="radio" id="hotelChoice2" name="hotel" value="superior" />
<label for="hotelChoice2">Superior (+$50)</label>
<input
Note: In this example, we are assuming the user is already registered and signed in, hence not needing to
collect details such as name and email.
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
8/14


type="radio"
id="hotelChoice3"
name="hotel"
value="penthouse"
disabled />
<label for="hotelChoice3">Penthouse (+$150)</label>
</div>
</fieldset>
<fieldset>
<legend>Choose classes to attend:</legend>
<div>
<input type="checkbox" id="yoga" name="yoga" />
<label for="yoga">Yoga (+$10)</label>
<input type="checkbox" id="coffee" name="coffee" />
<label for="coffee">Coffee roasting (+$20)</label>
<input type="checkbox" id="balloon" name="balloon" />
<label for="balloon">Balloon animal art (+$5)</label>
</div>
</fieldset>
<p>
<label for="transport">How are you getting here:</label>
<select name="transport" id="transport">
<option value="">--Please choose an option--</option>
<option value="plane">Plane</option>
<option value="bike">Bike</option>
<option value="walk">Walk</option>
<option value="bus">Bus</option>
<option value="train">Train</option>
<option value="jetPack">Jet pack</option>
</select>
</p>
<p>
<label for="comments">Any other comments:</label>
<textarea id="comments" name="comments" rows="5" cols="33"></textarea>
</p>
<p>
<button>Continue to payment</button>
</p>
</form>
</body>
</html>
This is rendered as follows:
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
9/14


We'd recommend that you open this example in a separate browser tab as you work through the next few sections, in
which we look at each control type in turn. To achieve this, copy the code into an HTML file using your code editor, and
open it in a browser tab.
Before moving on, play with the different form controls in your local copy and select some values. Try submitting the
form and see what the data submitted in the URL looks like.
Radio buttons
The "Choose hotel room type" buttons are implemented using <input type="radio">  controls. These render as a set
of push button controls where only one of the set can be selected at any one time — you can't select more than one at
once. They are named after the buttons found on old-fashioned radios, where you press one button and the previously-
selected one pops out again.
Our example code looks like this:
HTML
<fieldset>
<legend>Choose hotel room type:</legend>
<div>
<input
type="radio"
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
10/14


id="hotelChoice1"
name="hotel"
value="economy"
checked />
<label for="hotelChoice1">Economy (+$0)</label>
<input type="radio" id="hotelChoice2" name="hotel" value="superior" />
<label for="hotelChoice2">Superior (+$50)</label>
<input
type="radio"
id="hotelChoice3"
name="hotel"
value="penthouse"
disabled />
<label for="hotelChoice3">Penthouse (+$150)</label>
</div>
</fieldset>
radio  input types mostly work the same as text  input types, but with a few differences:
The name  attributes for each set of radio buttons have to contain the same value, to associate them together as
one set. If they contain different values, they will effectively be separate sets, with different values on
submission.
You have to include a value  attribute containing the value to submit for each radio button. The submitted value
will be a name/value pair, but the name will always be the same, for example, hotel=economy  or
hotel=superior .
The <label>  for each radio button should describe that particular value choice, rather than the overall value you
are selecting. The preferred way to describe the overall value choice is to wrap them in a <fieldset> , which
takes a <legend>  element as a child that contains the description.
It's also worth noting that we've applied the checked  attribute to the first radio button — this causes it to be selected
when the page first loads. This means one option will always be selected, and you can't deselect a radio button without
selecting another one.
Try removing the checked  attribute from the first radio button, save, then reload, to see the effect it has. Put it back
before you move on.
Disabling form controls
In the radio button example, you'll notice that the third radio button has the disabled  attribute set on it. This causes the
rendered control to be grayed out and unselectable. This is useful in many situations where an option is normally
available, just not right now. For example, a product might be out of stock, or as in our example's case, penthouse suites
are all booked up!
You can set the disabled  attribute on any form control, including <button>  elements. <fieldset>  elements can also
accept the disabled  attribute — this causes every form control inside the fieldset to be disabled.
Note: Besides structuring and labeling forms, fieldsets have other uses, such as disabling an entire set of
controls as a single unit.
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
11/14


Try setting the disabled  attribute on the two <fieldset>  elements, save, then reload, to see the effect it has. Remove
them again before moving on.
Checkboxes
Our "classes to attend" selectors are implemented using <input type="checkbox">  controls. These render as a set of
on/off state checkboxes. Unlike radio buttons, you can select more than one at once.
HTML
<fieldset>
<legend>Choose classes to attend:</legend>
<div>
<input type="checkbox" id="yoga" name="yoga" />
<label for="yoga">Yoga (+$10)</label>
<input type="checkbox" id="coffee" name="coffee" />
<label for="coffee">Coffee roasting (+$20)</label>
<input type="checkbox" id="balloon" name="balloon" />
<label for="balloon">Balloon animal art (+$5)</label>
</div>
</fieldset>
As you can see from the code snippets, radio buttons and checkboxes are implemented in a very similar way (they can
also take checked  attributes to render them pre-selected when the page loads). They also behave in a fairly similar
fashion, except that radio buttons allow you to choose zero or one items out of many, and checkboxes allow you to
choose zero or more items out of many.
The main difference (apart from the type  value!) is that each checkbox has a different name  value, and they generally
aren't given value  attributes. Behavior-wise, this means they represent different data values, whereas a radio button set
only represents one. On submission, each value is submitted with a value of on  if the checkbox was checked —
yoga=on , balloon=on , etc.
Drop-down menus
Drop-down menus, for example, the "How are you getting here" selection control in our example, are implemented not
with an <input>  type, but with the <select>  and <option>  elements:
HTML
<label for="transport">How are you getting here:</label>
<select name="transport" id="transport">
Note: It is possible to change the value submitted for a checkbox by giving it a value  attribute, for example:
<input type="checkbox" id="yoga" name="yoga" value="yes" />  would result in yoga=yes  being
submitted if checked.
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
12/14


<option value="">--Please choose an option--</option>
<option value="plane">Plane</option>
<option value="bike">Bike</option>
<option value="walk">Walk</option>
<option value="bus">Bus</option>
<option value="train">Train</option>
<option value="jetPack">Jet pack</option>
</select>
The <select>  element wraps all the different value choices. It is where you set the id  attribute that associates the
control with its label, and the name  attribute that sets the name of the data item to be submitted.
Each possible value for the data item is represented by an <option>  element, nested inside the <select>  element.
Each <option>  element can take a value  attribute, which specifies the value to be submitted if that option is chosen
from the drop-down list. If you don't specify a value , the text inside the <option></option>  tags is used as the value.
You can also split the options inside a <select>  drop-down menu into multiple subgroups using the <optgroup>
element. Take a look at this element's reference page to find out how.
Multi-line text input fields
Multi-line text input fields are created using <textarea>  elements:
HTML
<label for="comments">Any other comments:</label>
<textarea id="comments" name="comments" rows="5" cols="33"></textarea>
They behave in the same way as <input type="text">  elements, except that they allow multiple lines of text to be
entered. The rows  attribute specifies the number of rows tall the text area will be by default, while the cols  attribute
specifies the number of columns wide the text area will be by default. If they are not specified, the values used are
cols="20"  and rows="2" .
Most browsers render text areas with a drag handle in one corner, which can be used to resize it. Try using this to resize
the text area in our demo.
Form validation
Earlier on, we looked at some of the basic client-side form validation provided by the browser. The required  attribute is
used to specify that a field must be filled out before the form can be submitted; it also checks the correct value type is
entered for specific value types like email addresses, URLs, numbers, etc. Validation is important for two main reasons:
Making sure that data is submitted in the correct format so that it doesn't cause errors in your application.
Making sure data does not cause security problems. Bad people know how to submit data formatted specifically
so that, on insecure applications, it can execute commands to delete databases or take control of a system.
Note: If you want to have a specific option selected on page load, you can add a selected  attribute to the
relevant <option>  element.
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
13/14


Form validation is a huge topic that is beyond the scope of this article, so we will leave it here for now. Just bear in mind
that there are two types of form validation:
Client-side validation, which happens in the browser, is implemented using a combination of form validation
attributes (like required ) and JavaScript. Client-side validation is useful for giving users instant hints when they
have entered the wrong data, but is not so effective at stopping malicious data from getting through. It is too easy
to turn off JavaScript or alter client-side code so that the validation no longer works.
Server-side validation, which happens on the server, is implemented using whatever language the server is using.
Badly-formed messages can be sent to a server by accident or on purpose. Conventional wisdom is to make sure
that your server doesn't trust anything a client is sending to avoid bugs or security issues caused by malformed
messages. Server-side validation is great for stopping malicious messages, as it's harder to tamper with the code
running on the server. Server-side validation is not so good at giving users hints about incorrect data because the
data has to go to the server to get validated, then the result has to be sent back to the client before the user can
be notified.
In short, don't decide between using either client-side or server-side validation - you will need both. You need client-
side validation to give users feedback on their input and server-side validation to make sure messages are in a format
your server can safely handle. If you want to start learning more about validation, a good place to start is Client-side
form validation.
Summary
That's all for now. There's a lot more to know about forms, but for now, we've given you enough of an understanding to
move forward in your studies.
Next up, we'll give you some tests that you can use to check how well you've understood and retained the information
we've provided on HTML forms.
See also
Web forms — Working with user data
Previous
Overview: Structuring content with HTML
Next
Your blueprint for a better internet.
15.10.2026 20:25
Forms and buttons in HTML - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms
14/14


---

Test: HTML tests index
Test: Forms and buttons
Test your skills: Forms and buttons
Previous
Overview: Structuring content with HTML
Next
The aim of this skill test is to help you assess whether you understand how HTML forms and buttons work.
Forms and buttons 1
This task starts you off nice and gently by asking you to create two <input>  elements, for a user's ID and password,
along with a submit button.
To complete the task:
1. Create appropriate inputs for user ID and password.
2. You should also associate them with their text labels semantically.
3. Create a submit button inside the remaining list item, with button text of "Log in".
The starting point of the task looks like this:
User ID
Password
Here's the underlying code for this starting point:
HTML
<form>
<ul>
<li>User ID</li>
<li>Password</li>
<li></li>
</ul>
</form>
English (US)
Note: To get help, read our Test your skills usage guide. You can also reach out to us using one of our
communication channels.
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
1/9


The updated form should look like this:
User ID 
Password 
Log in
Click here to show the solution
Forms and buttons 2
The next task requires you to create working sets of checkboxes and radio buttons, from the provided text labels.
To complete the task:
1. Turn the first <fieldset> 's contents into a set of radio buttons — you should only be able to select one pony
character at once.
2. Make it so that the first radio button is selected upon page load.
3. Turn the second <fieldset> 's content into a set of checkboxes.
4. Add a couple more hotdog choices of your own.
The starting point of the task looks like this:
Who is your favorite pony?
Pinkie Pie
Rainbow Dash
Twilight Sparkle
Hotdog preferences
Vegan
Onions
Here's the underlying code for this starting point:
HTML
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
2/9


<fieldset>
<legend>Who is your favorite pony?</legend>
<ul>
<li>
<label for="pinkie">Pinkie Pie</label>
</li>
<li>
<label for="rainbow">Rainbow Dash</label>
</li>
<li>
<label for="twilight">Twilight Sparkle</label>
</li>
</ul>
</fieldset>
<fieldset>
<legend>Hotdog preferences</legend>
<ul>
<li>
<label for="vegan">Vegan</label>
</li>
<li>
<label for="onions">Onions</label>
</li>
</ul>
</fieldset>
The updated controls should look like this:
Who is your favorite pony?
Pinkie Pie 
Rainbow Dash 
Twilight Sparkle 
Hotdog preferences
Vegan 
Onions 
Mustard 
Ketchup 
Click here to show the solution
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
3/9


Forms and buttons 3
In this task, you'll explore some more specific input types. We want you to create appropriate inputs for a user to update
their details:
1. Email
2. Website
3. Phone number
4. Favorite color
The starting point of the task looks like this:
Edit your preferences
Email
Website
Phone number
Favorite color
Here's the underlying code for this starting point:
HTML
<h2>Edit your preferences</h2>
<ul>
<li>
<label for="email">Email</label>
</li>
<li>
<label for="website">Website</label>
</li>
<li>
<label for="phone">Phone number</label>
</li>
<li>
<label for="fave-color">Favorite color</label>
</li>
</ul>
The updated controls should look like this:
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
4/9


Edit your preferences
Email 
Website 
Phone number 
Favorite color 
Click here to show the solution
Forms and buttons 4
Now it's time to have a go at implementing a drop-down select menu, to allow a user to pick their favorite food from the
choices provided.
To complete the task:
1. Create a basic select box structure.
2. Associate it semantically with the provided "food" label.
3. Inside the list, split the choices up into 2 subgroups — "mains" and "snacks".
The starting point of the task looks like this:
Pick your favorite food: Salad Curry Pizza Fajitas Biscuits Crisps Fruit Breadsticks
Here's the underlying code for this starting point:
HTML
<ul>
<li>
<label for="food">Pick your favorite food:</label>
Salad Curry Pizza Fajitas Biscuits Crisps Fruit Breadsticks
</li>
</ul>
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
5/9


The updated controls should look like this:
Pick your favorite food: Salad
Click here to show the solution
Forms and buttons 5
In this task we want you to structure the provided form features.
To complete the task:
1. Separate out the first two and second two form fields into two distinct containers, each with a descriptive legend
(use "Personal details" for the first two, and "Comment information" for the second two).
2. Mark up each text label with an appropriate element so that it is semantically associated with its respective form
field.
3. Add a suitable set of structural elements around the label/field pairs to separate them out.
The starting point of the task looks like this:
Name: 
 Age: 
 Comment:
 Email: 
Here's the underlying code for this starting point:
HTML
Name:
<input type="text" id="name" name="name" />
Age:
<input type="number" id="age" name="age" />
Comment:
<input type="text" id="comment" name="comment" />
Email:
<input type="email" id="email" name="email" />
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
6/9


The updated controls should look like this:
Personal details
Name: 
Age: 
Comment information
Comment: 
Email (include if you want a reply): 
Click here to show the solution
Forms and buttons 6
In this task, we are providing you with a simple support query form, and we want you to add some validation features to
it. This task requires some knowledge that we don't teach in the "Forms and buttons in HTML" article, so you may need
to do some research elsewhere.
To complete the task:
1. Make all of the input fields mandatory to complete before the form can be submitted.
2. Change the type of the "Email address" and "Phone number" fields to make the browser apply some more
specific validation suitable for the data being asked for.
3. Give the "User name" field a required length of between 5 and 20 characters, the "Phone number" field a
maximum length of 15 characters, and the "Comment" field a maximum length of 200 characters.
Try submitting your form — it should refuse to submit until the above constraints are followed, and give suitable error
messages.
The starting point of the task looks like this:
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
7/9


Enter your support query
User name: 
Email address: 
Phone number: 
Comment: 
 
Submit comment
Here's the underlying code for this starting point:
HTML
<form>
<h2>Enter your support query</h2>
<ul>
<li>
<label for="uname">User name:</label>
<input type="text" name="uname" id="uname" />
</li>
<li>
<label for="email">Email address:</label>
<input type="text" name="email" id="email" />
</li>
<li>
<label for="phone">Phone number:</label>
<input type="text" name="phone" id="phone" />
</li>
<li>
<label for="comment">Comment:</label>
<textarea name="comment" id="comment"> </textarea>
</li>
<li>
<button>Submit comment</button>
</li>
</ul>
</form>
We've not provided finished content for this task, as it looks the same as the starting point.
Click here to show the solution
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
8/9


Previous
Overview: Structuring content with HTML
Next
Your blueprint for a better internet.
15.10.2026 20:25
Test your skills: Forms and buttons - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Test_your_skills/Forms_and_buttons
9/9


---

HTML
Challenge: Feedback form
Challenge: Structuring a feedback form
Previous
Overview: Structuring content with HTML
Next
In this challenge, we are going to test your ability to create and structure a form, as well as add some other HTML
features to it.
Starting point
To solve this challenge, we are expecting you to create a basic website project, either inside a folder on your computer's
hard drive, or using an online editor such as 
 or 
. Much of the code you need is already provided
on this page.
1. Create a new folder in an appropriate location on your computer called forms-challenge  (or open an online
editor and take the required steps to create a new project).
2. Save the following HTML listing inside a file inside your folder called index.html  (or paste it into your online
editor's HTML pane).
HTML
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<title>Forms challenge</title>
<link href="style.css" rel="stylesheet" />
<script defer src="index.js"></script>
</head>
<body>
We want your feedback!
We're very excited that you visited the little house in the woods,
and we want to hear what you thought of it! Please fill in the below
sections. You don't need to provide your name or contact details, but
if you do, we'll enter you into a prize draw where you'll have a chance
to win prizes.
--
Facilities
Was the porridge
English (US)
CodePen
JSFiddle
15.10.2026 20:25
Challenge: Structuring a feedback form - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Forms_challenge
1/7


Too hot?
Too cold?
Just right?
Were the beds
Too hard?
Too soft?
Just right?
Describe the chairs (select all you agree with)
Comfy
Luxurious
Hi-tech
Pretty
Majestic
--
About your hosts
Who's your favorite bear?
Papa bear
Mama bear
Junior
Dozer
Which greeting did you prefer?
Wave
Friendly greeting
Growl
Claw marks in the door
--
Any other feedback?
Give us your comments
--
Your details
Name
Email
Phone
--
Submit
15.10.2026 20:25
Challenge: Structuring a feedback form - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Forms_challenge
2/7


--
</body>
</html>
3. Save the following CSS listing inside a file inside your folder called style.css  (or paste it into your online
editor's CSS pane).
CSS
/* Basic font styles */
body {
background-color: white;
color: #333333;
font: 1em / 1.4 system-ui;
padding: 1em;
max-width: 800px;
margin: 0 auto;
}
h1 {
font-size: 2rem;
}
h2 {
font-size: 1.6rem;
}
h1,
h2 {
margin: 0 0 20px;
color: purple;
}
* {
box-sizing: border-box;
}
p {
color: gray;
margin: 0.5em 0;
}
/* Form structure */
fieldset {
border: 0;
15.10.2026 20:25
Challenge: Structuring a feedback form - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Forms_challenge
3/7


padding: 0;
}
legend {
padding-bottom: 10px;
font-weight: bold;
}
fieldset,
.separator {
margin-bottom: 20px;
}
.form-section {
margin-bottom: 20px;
padding: 20px;
}
img {
max-width: 100%;
height: 50px;
margin: 20px 0;
}
/* Individual form items */
fieldset input {
margin: 0 10px 0 0;
}
label {
margin-right: 40px;
}
textarea {
margin-top: 10px;
padding: 5px;
width: 100%;
height: 200px;
}
.separator {
display: flex;
}
.separator label {
flex: 2;
}
15.10.2026 20:25
Challenge: Structuring a feedback form - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Forms_challenge
4/7


.separator input,
.separator select {
flex: 3;
padding: 5px;
}
button {
padding: 10px 20px;
border-radius: 10px;
border: 1px solid grey;
background-color: #dddddd;
width: 50%;
margin: 0 auto;
display: block;
}
button:hover,
button:focus {
background-color: #eeeeee;
cursor: pointer;
}
Project brief
We'd like you to imagine that you have just been to stay at a hotel called the little house in the woods (well, at least you
thought it was a hotel). We want you to help us create a fictional feedback form for the hotel. As well as marking up the
required features and structuring the form, there are a few additional HTML features we want you to implement.
Implementing form controls
1. In the "Facilities" section, we want you to turn the first two sets of lines into sets of radio buttons plus a label to
describe each one and a legend describing the whole group. Add an attribute to make the first radio button in
each case selected by default.
2. In the "Facilities" section, turn the third set of lines into a set of checkboxes, with a label to describe each one
and a legend describing the whole group.
3. In the "About your hosts" section, turn both sets of lines into a drop-down menu of options, with a label to
describe each one.
4. In the "Any other feedback?" section, add a multi-line text entry box and turn the existing line into its descriptive
label.
5. In the "Your details" section, add a suitable type of text input to collect each of the three listed values. Turn the
existing lines into their labels.
6. Turn "Submit" into a submit button for the form.
Structuring the form
1. Wrap the form in a suitable wrapper element to specify the whole thing as a form.
2. Add repeating structural elements inside the form, to wrap each form section. Give each form section element a
class  of form-section . To make things easier, each form section is surrounded by two sets of double-
hyphens ( -- ). You can remove the double-hyphens when you've added your structural elements.
15.10.2026 20:25
Challenge: Structuring a feedback form - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Forms_challenge
5/7


3. You'll need to include additional structural elements around some of the control/label pairs to make them sit on
their own separate lines. Add these now, giving each one a class  of separator .
4. Add a line break element between the multi-line text entry box and its label to make the two sit on separate lines.
Additional HTML features
1. There are several headings in the text that need marking up with suitable elements:
1. The top level-heading: "We want your feedback!".
2. Second level headings: "Facilities", "About your hosts", "Any other feedback?", and "Your details".
2. The opening paragraph below the top-level heading needs to be marked up appropriately.
3. Also in the opening paragraph, turn the text "little house in the woods" and "prize draw" into links. We don't have
pages to link to yet, so for now, just set the target URL as #  for a placeholder.
4. We want you to place a wide, flat image below the opening paragraph as a decoration. The image path is
https://mdn.github.io/shared-assets/images/examples/learn/woodland-strip.jpg , and we'd like you to
set the alternative text for it to an empty value, given that it is decorative only.
5. Following on from the previous point, as a stretch goal, research a better way to include the decorative image on
the page, and have a go at doing so (this involves a different technology to HTML, which we haven't touched on
in this module).
Hints and tips
Use the 
 to catch unintended mistakes in your HTML — so that you can fix them.
If you are getting stuck and can't envisage what elements to put where, draw out a simple block diagram of the
page layout, and write on the elements you think should wrap each block. This is extremely helpful.
Example
The following live example shows what the form might look like after being marked up. If you are getting stuck on how to
achieve some of this, see the solution below.
W3C HTML validator
15.10.2026 20:25
Challenge: Structuring a feedback form - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Forms_challenge
6/7


We want your feedback!
We're very excited that you visited the little house in the woods, and we want to hear
what you thought of it! Please fill in the below sections. You don't need to provide your
name or contact details, but if you do, we'll enter you into a prize draw where you'll
have a chance to win prizes.
Facilities
Was the porridge
 Too hot?
 
 Too cold?
 
 Just right?
Were the beds
 Too hard?
 
 Too soft?
 
 Just right?
Click here to show the solution
Previous
Overview: Structuring content with HTML
Next
Your blueprint for a better internet.
15.10.2026 20:25
Challenge: Structuring a feedback form - Learn web development | MDN
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Forms_challenge
7/7


---

# Debugging HTML

HTML ile hata ayıklama

## HTML

## Debugging HTML

## English (US)

## HTML'de Hata Ayıklama

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

HTML yazmak gayet iyidir; peki ya bir şeyler ters giderse ve koddaki hatanın nerede olduğunu anlayamazsanız? Bu makale, HTML'deki hataları bulup düzeltmenize yardımcı olacak bazı araçları tanıtacaktır.

Önkoşullar:

Basic HTML Syntax’ta ele alındığı şekliyle temel HTML aşinalığı. Başlıklar, paragraflar ve listeler gibi metin düzeyi anlambilim. Yapısal HTML.

Öğrenme çıktıları:

HTML hata ayıklamasının arkasındaki temel arka plan

HTML kodunuzun daha derinine inmek için tarayıcı DevTools içindeki DOM inspector kullanımını

Yaygın HTML hata türlerini keşfetme.

HTML hatalarını tespit etmek için HTML validator kullanma.

## Hata ayıklama korkutucu değildir

Bir tür kod yazarken her şey yolundadır; ta ki o korkunç ana kadar: bir hata oluşur — yanlış bir şey yapmışsınızdır, bu yüzden kodunuz çalışmaz — ya hiç çalışmaz ya da tam istediğiniz gibi davranmaz. Örneğin, aşağıdaki örnek Rust dilinde yazılmış basit bir programı derlemeye çalışırken bildirilen bir hatayı gösterir.

Buradaki hata mesajı görece anlaşılırdır — "unterminated double quote string". Listeye bakarsanız, println!(Hello, world!); ifadesinin mantıksal olarak bir çift tırnak eksikmiş gibi göründüğünü muhtemelen fark edebilirsiniz. Ancak programlar büyüdükçe hata mesajları hızla daha karmaşık ve yorumlanması daha zor hale gelebilir; hatta Rust hakkında hiçbir şey bilmeyen biri için basit durumlar bile biraz göz korkutucu görünebilir.

Yine de hata ayıklamanın korkutucu olmak zorunda olmadığını unutmayın — herhangi bir kodu yazarken ve hata ayıklarken rahat olmanın anahtarı, hem dile hem de ilgili araçlara aşinalıktır.

## HTML ve hata ayıklama

HTML, Rust kadar karmaşık değildir. HTML, ayrıştırılmadan önce başka bir biçime derlenmez (compiled değil, interpreted’dır). Ayrıca HTML’nin öğe sözdizimi, Rust, JavaScript veya Python gibi "gerçek bir programlama dili"ne kıyasla tartışmasız çok daha anlaşılırdır.

Tarayıcıların HTML ayrıştırma biçimi, çoğu programlama dilinin ayrıştırılmasına göre çok daha hoşgörülüdür; bu hem iyi hem de kötü bir şeydir.

Peki hoşgörülü derken neyi kastediyoruz? Genelde kodda bir şeyi yanlış yaptığınızda karşınıza çıkacak iki ana hata türü vardır:

Syntax errors: Kodunuzdaki, programın çalışmamasına neden olan yazım hatalarıdır; az önce gösterilen Rust hatası gibi. Bunlar, dilin sözdizimine aşina olduğunuz ve hata mesajlarının ne anlama geldiğini bildiğiniz sürece genellikle düzeltmesi kolaydır.

Logic errors: Sözdiziminin aslında doğru olduğu, fakat kodun amaçladığınız şeyi yapmadığı, yani programın yanlış çalıştığı hatalardır. Bunları düzeltmek çoğu zaman syntax errors’tan daha zordur; çünkü hatanın kaynağına işaret eden bir hata mesajı yoktur.

HTML’nin kendisi syntax errors’tan muzdarip değildir; çünkü tarayıcılar onu hoşgörülü şekilde ayrıştırır, yani kaynak kodda sözdizimsel hatalar olsa bile sayfa yine de görüntülenir. Tarayıcıların, yanlış yazılmış HTML markup’ı (çoğu zaman invalid veya badly-formed markup olarak adlandırılır) nasıl yorumlayacağını belirleyen yerleşik kuralları vardır ve bunu otomatik olarak geçerli markup’a dönüştürürler.

Örneğin, aşağıdaki HTML parçası yanlış iç içe geçmiş öğeler içerir:

```html
<p>I didn't expect to find the <em>next-door neighbor's <strong>cat</em></strong> here!
</p>
```

Kapanış `</strong>` etiketi, kapanış `</em>` etiketinden önce gelmeliydi; ancak gelmiyor — ondan sonra geliyor.

Bu HTML’i bir tarayıcıya yükleyip işlenen DOM’a bakarsanız, iç içe yerleştirmenin tarayıcı tarafından düzeltildiğini görürsünüz:

```html
<p>
I didn't expect to find the
<em>next-door neighbor's <strong>cat</strong></em> here!
</p>
```

Peki bu neden hem iyi hem kötü? Bu örnekte tarayıcı amaçlanan sonucu üretmiştir; ancak biraz sonra göreceğiniz gibi, durum her zaman böyle olmaz. Her durumda bir şey çalışır halde elde edersiniz, fakat tarayıcı her zaman doğru olanı yapmaz; bu da sorunlara yol açabilir. Başta doğru markup yazmak daha iyidir.

Not: HTML’nin hoşgörülü ayrıştırılmasının nedeni, web ilk oluşturulduğunda içeriğin yayımlanabilmesinin, sözdiziminin kesinlikle doğru olmasından daha önemli sayılmasıydı. Eğer en başından daha katı olsaydı, web muhtemelen bugün olduğu kadar popüler olmazdı.

Peki markup hatalarını nasıl bulursunuz? Birazdan HTML validator kullanarak HTML’deki hataları nasıl bulacağınızı göstereceğiz; ancak önce DOM inspector ile HTML’nizi elle nasıl inceleyeceğinizi, ardından ne tür markup hataları arayabileceğinizi ve tarayıcının bunları nasıl yorumlayabileceğini göstereceğiz.

## DOM inspector kullanımı

Tüm modern tarayıcıların içinde, geçerli sekmede yüklenen web sayfasını incelemek için kullanılan bir dizi developer tools (devtools) bulunur. Bunlar size sayfada hangi HTML’nin işlendiğini, hangi CSS’nin her DOM düğümüne uygulandığını, hangi JavaScript’in sayfada çalıştığını ve daha fazlasını gösterebilir. Ayrıca şu anda çalışan kodu düzenlemenize ve etkinin sayfada canlı olarak nasıl değiştiğini görmenize olanak tanırlar.

Tarayıcıdan tarayıcıya benzer şekilde devtools açabilirsiniz — bunu öğrenmek için tarayıcınızda devtools nasıl açılır sayfasına bakın.

Bu makale için ilgili tek devtools işlevi DOM inspector’dır; bu araç, şu anda işlenen HTML DOM’unu gösterir ve onu düzenlemenize izin verir. Şimdi buna bakalım:

1. Tarayıcınızda devtools’u açın.
2. DOM inspector’ı açın. Her tarayıcıda aynı yerde bulunur — devtools içinde, satırın en başındaki ilk sekme. Firefox’ta Inspector, Safari, Edge ve Chrome’da ise Elements olarak etiketlenmiştir. Devtools’u ilk açtığınızda varsayılan olarak seçili olmalıdır; değilse seçin.
3. Sekmede gösterilen DOM ağacının yapısını inceleyin ve her DOM düğümünün başındaki küçük genişletme oklarına tıklayarak çocuk düğümleri nasıl açıp kapatabildiğinize dikkat edin. Ayrıca yukarı ve aşağı ok tuşlarıyla düğümler arasında yukarı-aşağı hareket edebilir, sağ ve sol ok tuşlarıyla düğümleri genişletip daraltabilirsiniz.
4. Düğümlerin üzerine gelmeyi (veya ok tuşlarıyla seçmeyi) de deneyin ve şu anda üzerine gelinen (veya seçilen) öğenin viewport içinde nasıl vurgulandığını fark edin.
5. Render edilmiş DOM’u düzenleyebilirsiniz de. Bu makalede düzenleme özelliğini kullanmayacağız; ancak merak ediyorsanız bunun nasıl yapıldığını araştırmak için biraz zaman ayırın.

## Sıra sizde: DOM inspector ile HTML inceleme

Bu bölümde, DOM inspector kullanarak bazı kodları inceleyecek ve tarayıcının yaygın markup hatalarını nasıl ele aldığını göreceksiniz.

1. Öncelikle aşağıdaki HTML dosyası listesini yerel makinenizde bir yere `debug-example.html` olarak kaydedin. Bu demo, keşfetmemiz için kasıtlı olarak bazı yerleşik hatalarla yazılmıştır.

```html
<!doctype html>

<html lang="en-US">

<head>

<meta charset="utf-8">

<title>HTML debugging examples</title>

</head>

<body>

<h1>HTML debugging examples</h1>

<p>What causes errors in HTML?

<ul>

<li>Unclosed elements: If an element is <strong>not closed properly,then its effect

can spread to areas you didn't intend

<li>Badly nested elements: Nesting elements properly is also very important for

code behaving correctly. <strong>strong <em>strong emphasized?</strong> what is this?

</em>

<li>Unclosed attributes: Another common source of HTML problems. Let's look at an

example: <a href="https://www.mozilla.org/>link to Mozilla homepage</a>

</ul>

</body>

</html>
```

2. Ardından bunu tarayıcıda açın. Bunun gibi bir şey görürsünüz:
3. Bu görünüm hemen çok iyi görünmüyor; nedenini anlamak için kaynak kodu inceleyelim (yalnızca body içeriği gösteriliyor):

```html
<h1>HTML debugging examples</h1>

<p>What causes errors in HTML?

<ul>

<li>Unclosed elements: If an element is <strong>not closed properly,

then its effect can spread to areas you didn't intend

<li>Badly nested elements: Nesting elements properly is also very important

for code behaving correctly. <strong>strong <em>strong emphasized?</strong>

what is this?</em>
```

4. Sorunları gözden geçirelim:

Paragraf ve liste öğelerinde kapanış etiketleri yok. Yukarıdaki görüntüye bakınca bunun markup’ın sunumunu çok kötü etkilemediği görülüyor; bir öğenin nerede bitip diğerinin nerede başlaması gerektiğini çıkarmak kolaydır.

İlk `strong` öğesinin kapanış etiketi yok. Bu biraz daha sorunludur; çünkü öğenin nerede bitmesi gerektiğini anlamak kolay değildir. Aslında metnin geri kalanının tamamı kalın biçimde gösterilmiştir.

Bu bölüm kötü iç içe geçmiştir: `strong <em>strong emphasized?</strong> what is this?</em>`. Önceki problem nedeniyle bunun nasıl yorumlandığını anlamak kolay değildir.

`href` öznitelik değeri kapanış çift tırnak işaretini eksik bırakmıştır. Görünüşe göre bu en büyük soruna yol açmıştır — bağlantı hiç render edilmemiştir.

5. Şimdi kaynak kod yerine render edilmiş DOM’u inceleyelim. Bunun için tarayıcınızın DOM inspector’ını açın. Render edilmiş markup’ın bir gösterimini göreceksiniz:
6. Tarayıcının HTML hatalarımızı nasıl düzeltmeye çalıştığına bakın (incelemeyi Firefox’ta yaptık; diğer modern tarayıcılar da aynı sonucu vermelidir):

Tarayıcı paragraf ve liste öğelerine kapanış etiketleri eklemiştir.

İlk `strong` öğesinin nerede kapanması gerektiği net olmadığından, tarayıcı metnin her ayrı bloğunu kendi `strong` öğesine sarmalamış ve bunu belgenin en altına kadar sürdürmüştür!

Yanlış iç içe geçme, tarayıcı tarafından aşağıdaki gibi düzeltilmiştir:

```html
<strong>
strong
<em>strong emphasized?</em>
</strong>
<em> what is this?</em>
```

Eksik çift tırnaklı bağlantı tamamen silinmiştir. Son liste öğesi şöyle görünür:

```html
<li>
<strong>
Unclosed attributes: Another common source of HTML problems. Let's look
at an example:
</strong>
</li>
```

## HTML doğrulama

Yukarıdaki örnekten, HTML’nizin iyi biçimlenmiş olduğundan gerçekten emin olmanız gerektiği anlaşılır! Peki nasıl? Yukarıda görülen gibi küçük bir örnekte satırları tarayıp hataları bulmak kolaydır; fakat ya devasa, karmaşık bir HTML belgesinde?

Bu iş için kullanılan araç Markup Validation Service’tir (veya HTML validator); W3C tarafından oluşturulmuş ve sürdürülmektedir (bunu The web standards model bölümünde öğrenmiştiniz). Validator bir HTML belgesini girdi olarak alır, onu işler ve HTML’nizde neyin yanlış olduğunu söyleyen bir rapor verir.

Bir HTML belgesini doğrulamak için bir web adresi verebilir, bir HTML dosyası yükleyebilir veya doğrudan bazı HTML kodu girebilirsiniz.

## Bir HTML belgesini doğrulama

Bu görevde, HTML validator’ı denemeniz istenecek. Daha önce DOM inspector ile incelediğiniz HTML’nin aynısını doğrulayacaksınız.

1. Önce, henüz açık değilse Markup Validation Service’i yeni bir tarayıcı sekmesinde açın.
2. Validate by Direct Input sekmesine geçin.
3. Örnek belgeyi kopyalayın ve Markup Validation Service içinde gösterilen büyük metin alanına yapıştırın. Yalnızca `body` içeriğini değil, tüm belge yapısını yapıştırın.
4. Check düğmesine basın.

Bu, size bir hata ve başka bilgiler listesi vermelidir.

## Hata mesajlarını yorumlama

Hata mesajları genellikle faydalıdır, ancak bazen o kadar kolay anlaşılmazlar. Biraz pratikle, kodunuzu düzeltmek için bunları nasıl yorumlayacağınızı anlayabilirsiniz. Hata mesajlarını ve ne anlama geldiklerini birlikte inceleyelim.

Her mesajın, hatayı kolayca bulmanıza yardımcı olmak için bir satır ve sütun numarasıyla geldiğini göreceksiniz.

`"End tag li implied, but there were open elements"` (2 örnek): Bu mesajlar, kapatılması gereken bir öğenin açık olduğunu gösterir. Bitiş etiketi varsayılmıştır, fakat gerçekte yoktur. Satır/sütun bilgisi, kapanış etiketinin gerçekten olması gereken satırdan sonraki ilk satıra işaret eder; ancak bu, neyin yanlış olduğunu görmek için yeterli bir ipucudur.

`"Unclosed element strong"`: Bunu anlamak daha kolaydır — bir `strong` öğesi kapatılmamıştır ve satır/sütun bilgisi tam olarak ilgili yere işaret eder.

`"End tag strong violates nesting rules"`: Bu, yanlış iç içe geçmiş öğeleri işaret eder; satır/sütun bilgisi de bunların bulunduğu yeri gösterir.

`"End of file reached when inside an attribute value. Ignoring tag"`: Bu biraz şifreli görünür; dosyanın sonunun öznitelik değeri içinde görünmesi nedeniyle, bir yerde düzgün biçimlendirilmemiş bir öznitelik değeri olduğunu ifade eder. Tarayıcının bağlantıyı render etmemesi, hangi öğenin hatalı olduğuna dair iyi bir ipucu vermelidir.

`"End of file seen and there were open elements"`: Bu biraz belirsizdir; ancak temelde düzgün şekilde kapatılması gereken açık öğeler bulunduğunu ifade eder. Satır numaraları dosyanın son birkaç satırını işaret eder ve bu hata mesajı, açık bir öğe örneğini işaret eden bir satır kodla birlikte gelir:

```html
example: <a href="https://www.mozilla.org/>link to Mozilla homepage</a> ↩ </ul>↩
</body>↩</html>
```

Not: Kapanış tırnağı eksik bir öznitelik, belgenin geri kalanının özniteliğin içeriği olarak yorumlanmasına neden olduğundan açık bir öğeyle sonuçlanabilir.

`"Unclosed element ul"`: Bu çok yararlı değildir; çünkü `ul` öğesi doğru şekilde kapatılmıştır. Bu hata, eksik kapanış tırnak işareti nedeniyle `a` öğesi kapatılamadığı için oluşur.

Tüm hata mesajlarının ne anlama geldiğini çözemezseniz endişelenmeyin. İyi bir strateji, birkaç hatayı bir seferde düzeltmek ve ardından HTML’nizi her düzeltme grubundan sonra yeniden doğrulamaktır; böylece geriye hangi hataların kaldığını görürsünüz. Bazen daha önceki bir hatayı düzeltmek, diğer hata mesajlarını da ortadan kaldırır — birden fazla hata tek bir sorundan, domino etkisiyle kaynaklanabilir.

Tüm hatalarınız düzeldiğinde, rapor edilecek hata olmadığını söyleyen hoş bir yeşil bant gördüğünüzü anlayacaksınız. Yazım anında şu ifade yer alıyordu: "Document checking completed. No errors or warnings to show."

## Özet

Böylece HTML hata ayıklamaya giriş yapmış olduk; bu size yalnızca HTML’yi değil, kursun ilerleyen bölümlerinde CSS ve JavaScript kodunu hata ayıklarken de kullanabileceğiniz faydalı beceriler kazandırmalıdır. Bu aynı zamanda Structuring content with HTML modülünün de sonunu işaret eder.

Sonraki adımınız, CSS styling basics modülümüzde web’i stillendirmeyi öğrenmeye başlamak olacak.

Önceki

Genel bakış: HTML ile içeriği yapılandırma

Sonraki

Your blueprint for a better internet.


---

# Test your skills: Structuring content with HTML

HTML ile içeriği yapılandırma becerilerinizi test edin

## HTML

## Test: HTML tests index

## English (US)

## Becerilerinizi test edin: HTML ile içeriği yapılandırma

Bu sayfa, bu modülde öğrendiklerinizi doğrulayabilmeniz için deneyebileceğiniz HTML testlerini listeler.

## HTML becerilerinizi konuya göre test edin

### Becerilerinizi test edin: Gelişmiş HTML metni

Bu beceri testinin amacı, gelişmiş anlamsal özellikleri işaretlemek için daha az bilinen HTML öğelerini nasıl kullanacağınızı anlayıp anlamadığınızı değerlendirmenize yardımcı olmaktır.

### Becerilerinizi test edin: Ses ve video

Bu beceri testinin amacı, HTML’de video ve ses içeriğini nasıl gömeceğinizi anlayıp anlamadığınızı değerlendirmenize yardımcı olmaktır.

### Becerilerinizi test edin: Formlar ve düğmeler

Bu beceri testinin amacı, HTML formlarının ve düğmelerinin nasıl çalıştığını anlayıp anlamadığınızı değerlendirmenize yardımcı olmaktır.

### Becerilerinizi test edin: HTML görüntüleri

Bu beceri testinin amacı, görüntüleri ve bunları HTML’ye nasıl gömeceğinizi anlayıp anlamadığınızı değerlendirmenize yardımcı olmaktır.

### Becerilerinizi test edin: HTML metin temelleri

Bu beceri testinin amacı, metni yapı ve anlam kazandıracak şekilde HTML’de nasıl işaretleyeceğinizi anlayıp anlamadığınızı değerlendirmenize yardımcı olmaktır.

### Becerilerinizi test edin: Bağlantılar

Bu beceri testinin amacı, bağlantıları HTML’de nasıl uygulayacağınızı anlayıp anlamadığınızı değerlendirmenize yardımcı olmaktır.

## Ayrıca bakın

Structuring content with HTML

Your blueprint for a better internet.


---

# Including vector graphics in HTML

HTML’de vektör grafikleri dahil etme

## HTML

## Vektör grafikleri

## English (US)

## HTML’de vektör grafikleri dahil etme

Vektör grafikleri birçok durumda çok kullanışlıdır — küçük dosya boyutlarına sahiptirler ve son derece ölçeklenebilirdirler; bu yüzden yakınlaştırıldıklarında veya büyük boyuta çıkarıldıklarında piksellenmezler. Bu makalede, bunlardan birini web sayfanıza nasıl ekleyeceğinizi göstereceğiz.

Önkoşullar:

HTML’nin temellerini ve belgenize nasıl resim ekleyeceğinizi bilmelisiniz.

Hedef:

Bir web sayfasına SVG (vektör) görüntüsünün nasıl gömüleceğini öğrenin.

Not: Bu makale size SVG öğretmeyi amaçlamaz; yalnızca ne olduğunu ve web sayfalarına nasıl ekleneceğini anlatır.

## Vektör grafikleri nedir?

Web’de iki tür görüntüyle çalışırsınız — raster görüntüler ve vektör görüntüler:

Raster görüntüler piksel ızgarası kullanılarak tanımlanır — bir raster görüntü dosyası, her pikselin tam olarak nereye yerleştirileceği ve tam olarak hangi renkte olması gerektiği hakkında bilgi içerir. Popüler web raster formatları arasında Bitmap (`.bmp`), PNG (`.png`), JPEG (`.jpg`) ve GIF (`.gif`) bulunur.

Vektör görüntüler algoritmalar kullanılarak tanımlanır — bir vektör görüntü dosyası, bilgisayarın ekranda görüntü render edildiğinde nasıl görünmesi gerektiğini hesaplamak için kullanabileceği şekil ve yol tanımlarını içerir. SVG formatı, Web’de kullanılmak üzere güçlü vektör grafikleri oluşturmamıza olanak tanır.

İkisi arasındaki fark hakkında bir fikir vermek için bir örneğe bakalım:

```html
<img src="star.png" alt="A raster star" />

<img src="star.svg" role="img" alt="A vector star" />
```

Bu, yan yana duran, siyah gölgeli iki görünüşte aynı kırmızı yıldızı gösterir. Fark şudur: soldaki raster (PNG), sağdaki ise vektör (SVG) görüntüdür.

Sayfayı yakınlaştırdığınızda veya görüntülerin boyutunu artırdığınızda fark belirgin hale gelir. Aşağıdaki örnek, iki yıldızın 300px genişlikte nasıl render edildiğini gösterir:

PNG görüntü piksellenir; çünkü her pikselin nerede olması gerektiği (ve hangi renkte olması gerektiği) hakkında bilgi içerir. Yakınlaştırıldığında, her piksel ekrandaki birden fazla pikseli dolduracak şekilde boyutlandırılır; bu yüzden görüntü bloklu görünmeye başlar. Ancak SVG görüntü, boyutu ne olursa olsun güzel ve net görünmeye devam eder; çünkü şekiller, büyüdükçe ölçeklenen değerlerle algoritmalar kullanılarak hesaplanır.

Ayrıca vektör görüntü dosyaları raster muadillerinden çok daha hafiftir; çünkü görüntüdeki her bir piksele ilişkin bilgi yerine yalnızca birkaç algoritma saklamaları gerekir.

## SVG nedir?

SVG, vektör görüntüleri tanımlamak için XML tabanlı bir dildir. Temelde HTML gibi işaretlemedir; ancak görüntünüzde görünmesini istediğiniz şekilleri ve bu şekillere uygulamak istediğiniz efektleri tanımlamak için birçok farklı öğeniz vardır. SVG, içerik değil grafik işaretlemek içindir. SVG; `<circle>` ve `<rect>` gibi temel şekiller oluşturmak için öğeler, ayrıca `<path>` ve `<polygon>` gibi daha karmaşık şekiller oluşturmak için öğeler tanımlar. Daha gelişmiş SVG özellikleri arasında `<feColorMatrix>` (bir dönüştürme matrisi kullanarak renkleri dönüştürür), `<animate>` (vektör grafiğinizin bölümlerini canlandırır) ve `<mask>` (görselinizin üzerine bir maske uygular) bulunur.

Basit bir örnek olarak, aşağıdaki kod bir daire ve bir dikdörtgen oluşturur:

```html
<svg
version="1.1"
baseProfile="full"
width="300"
height="200"
xmlns="http://www.w3.org/2000/svg">

<rect width="100%" height="100%" fill="black" />

<circle cx="150" cy="100" r="90" fill="blue" />

</svg>
```

Bu aşağıdaki çıktıyı oluşturur:

Yukarıdaki örnekten, SVG’yi elle kodlamanın kolay olduğu izlenimine kapılabilirsiniz. Evet, basit SVG’leri bir metin düzenleyicide elle kodlayabilirsiniz; ancak karmaşık bir görüntü için bu çok hızlı bir şekilde zorlaşır. SVG görüntüleri oluşturmak için çoğu kişi Inkscape veya Illustrator gibi bir vektör grafik düzenleyicisi kullanır. Bu paketler, çeşitli grafik araçlarını kullanarak bir dizi illüstrasyon oluşturmanıza ve fotoğrafların yaklaşık karşılıklarını oluşturmanıza (örneğin Inkscape’in Trace Bitmap özelliği gibi) olanak tanır.

SVG, şimdiye kadar anlatılanlara ek olarak bazı avantajlara sahiptir:

Vektör görüntülerdeki metin erişilebilir kalır (bu aynı zamanda SEO’nuzu da iyileştirir).

SVG’ler stil verme ve betik çalıştırmaya çok uygundur; çünkü görüntünün her bileşeni CSS ile stillendirilebilen veya JavaScript ile betiklenebilen bir öğedir.

Peki neden biri raster grafikleri SVG’ye tercih etsin? SVG’nin bazı dezavantajları da vardır:

SVG çok hızlı biçimde karmaşıklaşabilir; bu da dosya boyutlarının büyümesine neden olabilir. Karmaşık SVG’ler tarayıcıda önemli işleme süresi de gerektirebilir.

Oluşturmak istediğiniz görüntü türüne bağlı olarak SVG, raster görüntülere göre oluşturulması daha zor olabilir.

Yukarıda açıklanan nedenlerden dolayı, raster grafikler fotoğraflar gibi karmaşık ve hassas görüntüler için tartışmalı olarak daha iyidir.

Inkscape gibi düzenleyicilerden dışa aktarılan SVG grafiklerinde boyut optimizasyonu için büyük alan vardır. Bunları web’e dağıtmadan önce, muhtemelen bunları bir SVG optimizer’dan, örneğin SVGO’dan geçirmeniz gerekir.

## Sayfalarınıza SVG ekleme

Bu bölümde SVG vektör grafiklerini web sayfalarınıza eklemenin farklı yollarını ele alacağız.

### Hızlı yol: `img` öğesi

Bir SVG’yi `<img>` öğesi aracılığıyla gömmek için, beklediğiniz gibi `src` özniteliğinde ona başvurmanız yeterlidir. SVG’nizin yerleşik bir en-boy oranı yoksa `height` veya `width` özniteliğine (veya ikisine birden) ihtiyacınız olacaktır. Bunu henüz yapmadıysanız lütfen HTML images bölümünü okuyun.

```html
<img
src="equilateral.svg"
alt="triangle with all three sides equal"
height="87"
width="100" />
```

Artılar

`alt` özniteliğinde yerleşik metin eşdeğeri bulunduğundan, hızlı ve tanıdık bir görüntü sözdizimi.

`<img>` öğesini bir `<a>` öğesi içine iç içe yerleştirerek görüntüyü kolayca bir köprüye dönüştürebilirsiniz.

SVG dosyası tarayıcı tarafından önbelleğe alınabilir; bu da gelecekte bu görüntüyü kullanan herhangi bir sayfa için daha hızlı yükleme süreleri sağlar.

Eksiler

Görüntüyü JavaScript ile değiştiremezsiniz.

SVG içeriğini CSS ile denetlemek istiyorsanız, SVG kodunuza satır içi CSS stilleri eklemelisiniz. (SVG dosyasından çağrılan harici stil sayfaları hiçbir etki göstermez.)

Görüntüyü CSS sözde sınıflarıyla (örneğin `:focus`) yeniden stillendiremezsiniz.

### Sorun giderme ve tarayıcılar arası destek

SVG desteklemeyen tarayıcılarda (IE 8 ve altı, Android 2.3 ve altı), `src` özniteliğinizde bir PNG veya JPG’ye başvurup SVG’ye atıfta bulunmak için bir `srcset` özniteliği kullanabilirsiniz (bu özniteliği yalnızca yeni tarayıcılar tanır). Böylece, yalnızca destekleyen tarayıcılar SVG’yi yükler — eski tarayıcılar bunun yerine PNG’yi yükler:

```html
<img
src="equilateral.png"
alt="triangle with equal sides"
srcset="equilateral.svg" />
```

SVG’leri aşağıda gösterildiği gibi CSS background images olarak da kullanabilirsiniz. Aşağıdaki kodda eski tarayıcılar anladıkları PNG ile devam ederken, yenileri SVG’yi yükler:

```css
background: url("fallback.png") no-repeat center;
background-image: url("image.svg");
background-size: contain;
```

Yukarıda açıklanan `<img>` yöntemi gibi, SVG’leri CSS background images kullanarak eklemek de SVG’nin JavaScript ile değiştirilemeyeceği anlamına gelir ve aynı CSS sınırlamalarına tabidir.

SVG’leriniz hiç görünmüyorsa bunun nedeni sunucunuzun doğru yapılandırılmamış olması olabilir. Sorun buysa, bu makale sizi doğru yöne yönlendirecektir.

## SVG kodunu HTML’nizin içine ekleme

SVG dosyasını bir metin düzenleyicide açıp SVG kodunu kopyalayabilir ve HTML belgenize yapıştırabilirsiniz — buna bazen SVG’yi inline eklemek veya SVG’yi satır içine almak denir. SVG kod parçanızın `<svg>` başlangıç etiketiyle başladığından ve `</svg>` bitiş etiketiyle sona erdiğinden emin olun. İşte belgenize yapıştırabileceğiniz çok basit bir örnek:

```html
<svg width="300" height="200">

<rect width="100%" height="100%" fill="green" />

</svg>
```

Artılar

SVG’yi satır içine yerleştirmek bir HTTP isteğini azaltır ve bu nedenle yükleme sürenizi biraz düşürebilir.

SVG öğelerine `class` ve `id` atayabilir, bunları CSS ile stillendirebilirsiniz; bunu SVG’nin içinde veya HTML belgeniz için CSS stil kurallarını nereye koyarsanız orada yapabilirsiniz. Aslında, herhangi bir SVG presentation attribute’u bir CSS property olarak kullanabilirsiniz.

SVG’yi satır içine almak, CSS etkileşimlerini (`:focus` gibi) ve CSS animasyonlarını SVG görüntünüzde kullanmanıza izin veren tek yaklaşımdır (normal stil sayfanızda bile).

SVG markup’ını bir `<a>` öğesi içine sararak onu bir köprüye dönüştürebilirsiniz.

Eksiler

Bu yöntem yalnızca SVG’yi tek bir yerde kullanıyorsanız uygundur. Yinelenme, kaynak açısından maliyetli bakım demektir.

Ek SVG kodu HTML dosyanızın boyutunu artırır.

Tarayıcı inline SVG’yi, sıradan görüntü varlıklarını önbelleğe aldığı gibi önbelleğe alamaz; bu yüzden görüntüyü içeren sayfalar, görüntüyü içeren ilk sayfa yüklendikten sonra daha hızlı yüklenmez.

`<foreignObject>` öğesinde yedek içerik ekleyebilirsiniz; ancak SVG’yi destekleyen tarayıcılar bile yine de yedek görüntüleri indirir. Yalnızca eski tarayıcıları desteklemek için ekstra yükün gerçekten buna değip değmediğini tartmanız gerekir.

### SVG’yi `iframe` ile gömme

SVG görüntülerini web sayfaları gibi tarayıcınızda açabilirsiniz. Bu yüzden bir SVG belgesini `<iframe>` ile gömmek, From `<object>` to `<iframe>` — general embedding technologies bölümünde öğrendiğimiz gibi yapılır.

Kısa bir hatırlatma:

```html
<iframe src="triangle.svg" width="500" height="500" sandbox></iframe>
```

Bu kesinlikle seçilecek en iyi yöntem değildir:

## Eksiler

`<iframe>` öğeleri, açılış ve kapanış etiketleri arasına yedek içerik ekleyebilir; ancak bu, yalnızca `<iframe>` desteklemeyen tarayıcılarda gösterilir, görüntü yüklenemediğinde değil.

Ayrıca, SVG ile mevcut web sayfanız aynı origin’e sahip değilse, ana web sayfanızda JavaScript kullanarak SVG’yi değiştiremezsiniz.

## SVG ile deneme yapma

Bu alıştırmada biraz SVG ile uğraşmanızı istiyoruz. Play düğmesine basarak bir sonraki örneği MDN Playground’da açın ve orada düzenleyin.

SVG Element Reference sayfasına giderek, size yerleşik birçok işlevsellik sağlayan başka hangi öğeleri kullanabileceğinizi görün. Elips gibi başka şekilleri deneyebilir veya desenlerle ya da hatta filtre efektleriyle denemeler yapabilirsiniz. Bu bölüm, araştırma becerileriniz, yeni bir şey denemeniz ve biraz eğlenmeniz hakkındadır.

Kodu çalıştırmakta takılırsanız, Playground’daki Reset düğmesini kullanarak sıfırlayabilirsiniz.

```html
<svg width="100%" height="100%">

<rect width="100%" height="100%" fill="red" />

<circle cx="100%" cy="100%" r="150" fill="blue" stroke="black" />

<polygon points="120,0 240,225 0,225" fill="green" />

<text
x="50"
y="100"
font-family="Verdana"
font-size="55"
fill="white"
stroke="black"
stroke-width="2">
Hello!

</text>

</svg>
```

Hello!
Hello!

## Özet

Bu makale size vektör grafikleri ve SVG’nin ne olduğuna, neden bilinmeye değer olduklarına ve SVG’yi web sayfalarınıza nasıl ekleyebileceğinize dair hızlı bir tur sundu. Hiçbir zaman SVG öğrenmek için tam bir kılavuz olmayı amaçlamadı; yalnızca Web’deki yolculuklarınız sırasında SVG ile karşılaşırsanız onun ne olduğunu bilmeniz için bir ipucu olarak hazırlandı. Bu yüzden henüz kendinizi bir SVG uzmanı gibi hissetmiyorsanız endişelenmeyin. Nasıl çalıştığı hakkında daha fazla bilgi edinmek isterseniz size yardımcı olabilecek bazı bağlantıları aşağıya ekledik.

## Ayrıca bakın

SVG tutorial on MDN

Sara Soueidan's tutorial on responsive SVG images

SVG Properties and CSS

How to scale SVGs

(it's not as simple as raster graphics!)

Your blueprint for a better internet.


---

# From object to iframe — general embedding technologies

`<object>` öğesinden `<iframe>` öğesine — genel gömme teknolojileri

## HTML

## Gömme teknolojileri

## English (US)

## `<object>` öğesinden `<iframe>` öğesine — genel gömme teknolojileri

Geliştiriciler genellikle resimler, video ve ses gibi ortamları web sayfalarına gömmeyi düşünür. Bu makalede biraz yan bir adım atıyor ve web sayfalarınıza çok çeşitli içerik türlerini gömenize olanak tanıyan bazı öğelere bakıyoruz: `<iframe>`, `<embed>` ve `<object>` öğeleri. Bu öğeler, diğer web sayfaları ve PDF dosyaları gibi harici kaynakları gömmenize olanak tanır.

Önkoşullar:

Hedef:

Temel yazılımın yüklü olması, dosyalarla çalışma hakkında temel bilgi, HTML temellerine aşinalık.

PDF belgeleri ve diğer web sayfaları gibi öğeleri `<object>`, `<embed>` ve `<iframe>` kullanarak web sayfalarına nasıl gömeceğinizi öğrenmek.

## Gömmenin kısa tarihi

Web’in çok eski zamanlarında, web siteleri oluşturmak için frames kullanmak popülerdi — bir web sitesinin küçük bölümleri ayrı HTML sayfalarında saklanırdı. Bunlar, frameset adı verilen ana bir belgeye gömülürdü; bu belge, her frame’in ekranda kaplayacağı alanı belirtmenize izin verirdi; bu, bir tablonun sütun ve satırlarını boyutlandırmaya benzerdi. Bunlar 90’ların ortasından sonuna kadar havalılığın zirvesi sayılıyordu ve bir web sayfasının bu şekilde daha küçük parçalara bölünmesinin indirme hızları açısından daha iyi olduğuna dair kanıtlar vardı — özellikle de ağ bağlantıları o zamanlar çok yavaş olduğu için bu daha belirgindi.

Bununla birlikte pek çok sorunları vardı ve ağ hızları arttıkça olumlu yönlerini fazlasıyla geride bıraktılar; bu nedenle artık kullanılmadıklarını görürsünüz.

Biraz sonra (90’ların sonu, 2000’lerin başı), Java Applets ve Flash gibi plugin teknolojileri çok popüler hale geldi — bunlar web geliştiricilerinin videolar ve animasyonlar gibi, yalnızca HTML ile sağlanamayan zengin içerikleri web sayfalarına gömmesine olanak tanıyordu. Bunların gömülmesi `<object>` gibi öğeler ve daha az kullanılan `<embed>` aracılığıyla yapılıyordu ve o zamanlar çok faydalıydılar. Ancak erişilebilirlik, güvenlik, dosya boyutu ve daha fazlası dahil birçok sorun nedeniyle zamanla gözden düştüler. Bugün büyük tarayıcılar Flash gibi plugin’leri desteklemeyi bıraktı.

Son olarak `<iframe>` öğesi ortaya çıktı (ayrıca `<canvas>`, `<video>` gibi içerik gömme yolları da belirdi). Bu, tüm bir web belgesini başka bir belgenin içine, sanki bir `<img>` ya da benzeri bir öğeymiş gibi gömmeye yarayan bir yol sağlar ve günümüzde düzenli olarak kullanılır.

Bu tarih dersini geride bıraktığımıza göre, şimdi bunlardan bazılarının nasıl kullanılacağına bakalım.

## Klasik gömme kullanımlarıyla oynama

Bu makalede, gömme teknolojilerinin ne işe yaradığını hemen hissetmeniz için doğrudan bir alıştırmaya geçeceğiz. Çevrim içi dünya YouTube’a çok aşinadır; ancak birçok kişi onun sunduğu bazı paylaşım özelliklerini bilmez.

1. Öncelikle MDN Playground’u açın.
2. Şimdi YouTube’un, `<iframe>` kullanarak herhangi bir sayfaya nasıl video gömmemize izin verdiğine bakalım.
3. YouTube’a gidin ve beğendiğiniz bir video bulun.
4. Videonun altında bir Share düğmesi bulacaksınız — paylaşım seçeneklerini görmek için bunu seçin.
5. Embed düğmesini seçin; size bazı `<iframe>` kodları verilecektir — bunu kopyalayın.
6. Playground’daki HTML paneline yapıştırın ve çıktıda ne olduğuna bakın.

3. Bonus puan için, Playground’da bir Google Map gömmeyi de deneyebilirsiniz:

1. Google Maps’e gidin ve beğendiğiniz bir harita bulun.
2. UI’nin sol üstündeki "hamburger menü"ye (üç yatay çizgi) tıklayın.
3. Share or embed map seçeneğini seçin.
4. Embed a map seçeneğini seçin; size bazı `<iframe>` kodları verilecektir — bunu kopyalayın.
5. Playground’daki HTML paneline yapıştırın ve çıktıda ne olduğuna bakın.

Hata yaparsanız Playground’daki Reset düğmesini kullanarak her zaman sıfırlayabilirsiniz.

## Web sayfalarını gömmek için iframes kullanma

Evet, bu kolay ve eğlenceli değil mi? `<iframe>` öğeleri, başka web belgelerini mevcut belgenin içine gömenize izin verecek şekilde tasarlanmıştır. Bu, üzerinde doğrudan kontrolünüz olmayabilecek ve kendi sürümünüzü uygulamak istemeyeceğiniz üçüncü taraf içeriğini web sitenize dahil etmek için harikadır — örneğin çevrim içi video sağlayıcılarından video, Disqus gibi yorum sistemleri, çevrim içi harita sağlayıcılarından haritalar, reklam banner’ları vb. Bu kurs boyunca kullandığınız canlı düzenlenebilir örnekler bile `<iframe>`’ler kullanılarak uygulanmıştır.

`<iframe>` öğelerini kullanmaya dalmadan önce dikkat etmeniz gereken bazı güvenlik endişeleri vardır. MDN glossary’yi web sayfalarınızdan birine `<iframe>` ile eklemek istediğinizi varsayalım; aşağıdaki kod örneğine benzer bir şey deneyebilirsiniz. Aşağıdaki kodu sayfalarınızdan birine eklerseniz, glossary sayfası yerine bir hata mesajı görmek sizi şaşırtabilir:

```html
<iframe
src="https://developer.mozilla.org/en-US/docs/Glossary"
width="100%"
height="500"
allowfullscreen
sandbox>
</iframe>
```

```css
iframe {
border: none;
}
```

Tarayıcınızın Console’una bakarsanız, aşağıdaki gibi bir hata mesajı görürsünüz:

`Refused to display 'https://developer.mozilla.org/' in a frame because it set 'X-Frame-Options' to 'deny'.`

Aşağıdaki Security bölümü bu hatayı neden gördüğünüzü daha ayrıntılı açıklar; ancak önce kodumuzun ne yaptığını inceleyelim.

Örnek, bir `<iframe>` kullanmak için gereken temel unsurları içerir:

`border: none`

Kullanılırsa, `<iframe>` etrafında bir sınır olmadan gösterilir. Aksi halde varsayılan olarak tarayıcılar `<iframe>`’i çevresinde bir sınırla gösterir (bu genellikle istenmez).

`allowfullscreen`

Ayarlanırsa, `<iframe>` Fullscreen API kullanılarak tam ekran moduna alınabilir (bu makalenin kapsamının biraz dışındadır).

`src`

Bu öznitelik, `<video>` / `<img>` için olduğu gibi, gömülecek belgenin URL’sine işaret eden bir yol içerir.

`width` ve `height`

Bu öznitelikler, iframe’in olmasını istediğiniz genişlik ve yüksekliği belirtir.

`sandbox`

Diğer `<iframe>` özelliklerinin geri kalanından biraz daha modern tarayıcılarda çalışan bu öznitelik (örneğin IE 10 ve üzeri) daha yüksek güvenlik ayarları ister; bundan sonraki bölümde bunu daha fazla ele alacağız.

Not: Hızı artırmak için, ana içerik yüklemeyi bitirdikten sonra JavaScript ile iframe’in `src` özniteliğini ayarlamak iyi bir fikirdir. Bu, sayfanızı daha erken kullanılabilir hale getirir ve resmi sayfa yüklenme sürenizi azaltır (önemli bir SEO metriği.)

## Güvenlik endişeleri

Yukarıda güvenlik endişelerinden bahsettik — şimdi bunu biraz daha ayrıntılı ele alalım. Bu içeriğin tamamını ilk seferde mükemmel biçimde anlamanızı beklemiyoruz; amacımız sizi bu konunun farkına vardırmak ve `<iframe>`’leri deneylerinizde ve çalışmalarınızda kullanmayı düşünmeye başladığınızda geri dönebileceğiniz bir referans sunmaktır. Ayrıca, `<iframe>` kullanmaktan korkmanıza da gerek yok — sadece dikkatli olmanız gerekir. Devam edin…

Tarayıcı üreticileri ve Web geliştiricileri, iframe’lerin Web’de kötü insanlar için yaygın bir hedef olduğunu (resmi terim: attack vector) zor yoldan öğrendi; bu kişiler web sayfanızı kötü niyetli şekilde değiştirmeye ya da kullanıcıları kullanıcı adları ve parolalar gibi hassas bilgileri ifşa etmeye kandırmaya çalışabilir. Bu nedenle, standart geliştiricileri ve tarayıcı geliştiricileri `<iframe>`’leri daha güvenli hale getirmek için çeşitli güvenlik mekanizmaları geliştirdi; ayrıca dikkate alınması gereken iyi uygulamalar da vardır — aşağıda bunlardan bazılarını ele alacağız.

Not: Clickjacking, hacker’ların belgenize görünmez bir iframe yerleştirdiği (veya belgenizi kendi kötü amaçlı web sitelerine gömdüğü) ve bunu kullanıcı etkileşimlerini yakalamak için kullandığı yaygın bir iframe saldırısı türüdür. Bu, kullanıcıları yanıltmanın veya hassas verileri çalmanın yaygın bir yoludur.

Önce hızlı bir örnek: daha önce gösterdiğimiz örneği tarayıcınızda açmayı deneyin — bunu GitHub üzerinde canlı bulabilirsiniz (kaynak kodunu da görün). Beklediğiniz sayfa yerine büyük olasılıkla "I can't open this page" benzeri bir mesaj görürsünüz ve tarayıcı geliştirici araçlarındaki Console’a bakarsanız nedenini belirten bir mesaj göreceksiniz. Firefox’ta, `"https://developer.mozilla.org/en-US/docs/Glossary" in a frame is denied by "X-Frame-Options" directive set to "DENY".` gibi bir mesaj alırsınız.

Bunun nedeni, MDN’i oluşturan geliştiricilerin, web sitesi sayfalarını sunan sunucuya bunların `<iframe>` içinde gömülmesini engelleyen bir ayar eklemiş olmalarıdır (aşağıdaki Configure CSP directives bölümüne bakın.) Bu mantıklıdır — tüm bir MDN sayfasının, onları kendi sitenize gömüp kendinize aitmiş gibi göstermeyi istemediğiniz sürece başka sayfalara gömülmesinin bir anlamı yoktur; ya da clickjacking yoluyla veri çalmaya çalışmak gibi, ikisi de çok kötü şeylerdir. Ayrıca herkes bunu yapmaya başlarsa, ek bant genişliği Mozilla’ya çok para ödetmeye başlar.

### Yalnızca gerektiğinde gömün

Bazen üçüncü taraf içeriği gömmek mantıklıdır — YouTube videoları ve haritalar gibi — ancak yalnızca tamamen gerekli olduğunda üçüncü taraf içerik gömerseniz kendinizi birçok baş ağrısından kurtarabilirsiniz. Web güvenliği için iyi bir kural şudur: "Asla fazla temkinli olamazsınız. Siz yaptıysanız yine de iki kez kontrol edin. Başkası yaptıysa, zararsız olduğu kanıtlanana kadar tehlikeli olduğunu varsayın."

Güvenliğin ötesinde, fikrî mülkiyet konularının da farkında olmalısınız. Çoğu içerik, beklemediğiniz içerikler bile dahil olmak üzere, çevrim dışı ve çevrim içi olarak telif hakkıyla korunur (örneğin Wikimedia Commons üzerindeki çoğu görsel). Bir web sayfasında, siz ona sahip olmadıkça ya da sahipleri size yazılı ve tartışmasız izin vermedikçe içerik göstermeyin. Telif hakkı ihlalinin cezaları ağırdır. Yine, asla fazla temkinli olamazsınız.

İçerik lisanslıysa, lisans şartlarına uymanız gerekir. Örneğin MDN’deki içerik CC-BY-SA altında lisanslıdır. Bu, içeriğimizi önemli ölçüde değiştirmiş olsanız bile alıntıladığınızda bize düzgün biçimde atıf yapmanız gerektiği anlamına gelir.

### HTTPS kullanın

HTTPS, HTTP’nin şifrelenmiş sürümüdür. Web sitelerinizi mümkün olduğunda HTTPS ile sunmalısınız:

1. HTTPS, uzak içeriğin aktarım sırasında kurcalanma olasılığını azaltır.
2. HTTPS, gömülü içeriğin ana belgenizdeki içeriğe erişmesini ve bunun tersini önler.

Siteniz için HTTPS etkinleştirmek, özel bir güvenlik sertifikasının yüklenmesini gerektirir. Birçok hosting sağlayıcısı, bir sertifika kurmak için kendi başınıza hiçbir şey yapmanıza gerek kalmadan HTTPS etkin hosting sunar. Ancak siteniz için HTTPS desteğini kendiniz kurmanız gerekiyorsa, Let's Encrypt bunu otomatik olarak gerekli sertifikayı oluşturmak ve yüklemek için kullanabileceğiniz araçlar ve yönergeler sağlar; Apache web sunucusu, Nginx ve diğerleri dahil en yaygın kullanılan web sunucuları için yerleşik destekle birlikte. Let's Encrypt araçları, süreci olabildiğince kolay hale getirmek için tasarlanmıştır; bu yüzden bunu veya HTTPS sağlamak için mevcut diğer yöntemleri kullanmaktan kaçınmak için gerçekten iyi bir neden yoktur.

Not: GitHub Pages, içeriğin varsayılan olarak HTTPS üzerinden sunulmasına izin verir. Farklı bir hosting sağlayıcısı kullanıyorsanız, HTTPS üzerinden içerik sunmak için ne tür bir destek sağladıklarını kontrol etmelisiniz.

### Her zaman `sandbox` özniteliğini kullanın

Saldırganlara web sitenizde kötü şeyler yapmaları için olabildiğince az yetki vermek istersiniz; bu nedenle gömülü içeriğe yalnızca işini yapmak için gerekli izinleri vermelisiniz. Elbette bu kendi içeriğiniz için de geçerlidir. Uygun şekilde — ya da test için — kullanılabilecek fakat kod tabanının geri kalanına (ister kazara ister kötü niyetle) zarar veremeyen bir kod kapsayıcısına sandbox denir.

Sandbox edilmemiş içerik JavaScript çalıştırabilir, formlar gönderebilir, açılır pencere tetikleyebilir vb. Varsayılan olarak, önceki örneğimizde gösterildiği gibi `sandbox` özniteliğini parametresiz kullanarak mevcut tüm kısıtlamaları uygulamalısınız.

Zorunlu olarak gerekirse, izinleri tek tek geri ekleyebilirsiniz (`sandbox=""` öznitelik değeri içinde) — mevcut tüm seçenekler için sandbox başvuru kaydına bakın. Önemli bir not: Gömülü içerik gömülme sayfasıyla aynı origin’e sahipse, `allow-scripts` ve `allow-same-origin` seçeneklerinin ikisini birden `sandbox` özniteliğinize asla eklememelisiniz — bu durumda gömülü içerik JavaScript kullanarak özniteliği kaldırıp kendini yeniden yükleyebilir ve sandboxing’i tamamen kapatabilir.

Not: Saldırganlar insanları kötü niyetli içeriği doğrudan ziyaret etmeye kandırabiliyorsa sandboxing hiçbir koruma sağlamaz (bir iframe dışında). Belirli içeriğin kötü niyetli olma ihtimali varsa (örneğin kullanıcı tarafından oluşturulan içerik), lütfen onu ana sitenizden farklı bir etki alanında sunun.

### CSP yönergelerini yapılandırın

CSP, content security policy anlamına gelir ve HTML belgenizin güvenliğini artırmak için tasarlanmış bir dizi HTTP Headers sağlar (web sunucusundan sunulduklarında web sayfalarınızla birlikte gönderilen meta veriler). `<iframe>`’leri güvence altına alma söz konusu olduğunda, sunucunuzun uygun bir `X-Frame-Options` başlığı göndermesini yapılandırabilirsiniz. Bu, diğer web sitelerinin içeriğinizi kendi sayfalarına gömmesini engelleyebilir (bu da clickjacking ve diğer birçok saldırıyı mümkün kılar); tam da MDN geliştiricilerinin daha önce gördüğümüz gibi yaptığı şey budur.

Not: Daha fazla arka plan bilgisi için Frederik Braun’un On the X-Frame-Options Security Header yazısını okuyabilirsiniz. Açıkçası, bu makalede tam bir açıklama için kapsamın biraz dışındadır.

## `<embed>` ve `<object>` öğeleri

Tıpkı `<iframe>` gibi, `<embed>` ve `<object>` öğeleri de harici içeriği gömebilir. Gömülen içeriğe bağlı olarak bu, daha hafif bir seçenek olabilir; çünkü tarayıcının gömülü içerik için tam bir browsing context oluşturması gerekmez.

Tarihsel olarak bu öğeler Adobe Flash gibi tarayıcı eklentileri tarafından işlenen içerikleri gömmek için de kullanılmıştır; ancak bu teknoloji artık eskimiştir ve modern tarayıcılar tarafından desteklenmez. Bugün kullanımlarının neredeyse tamamı, daha fazla güvenlik özelliği sağlayan `<iframe>` ile karşılanabilir.

Bu öğeleri kullanarak harici içerik gömmek zorunda kalırsanız, en azından bilmeniz gereken bilgiler şunlardır:

`<embed>`

`<object>`

Gömülü içeriğin URL’si

Gömülü içeriğin doğru medya türü

Gömülü içeriğin kutusunun yüksekliği ve genişliği (CSS pikseli cinsinden)

`src`

'type'

`height`

`width`

`data`

'type'

`height`

`width`

Bağımsız HTML içeriği, kullanılamayan bir kaynak için yedek olarak

Desteklenmez

Açılış ve kapanış `<object>` etiketleri içinde yer alır

## PDF’leri gömme

Web’de çoğu ortamın zaten kendine ayrılmış öğeleri vardır: `<audio>`, `<img>`, `<video>`, `<svg>` vb. Web sayfaları dışında, `<iframe>`, `<object>` ve `<embed>` öğelerinin diğer ana kullanım alanı PDF belgelerini gömmektir.

Günümüzde tüm tarayıcılar yerel PDF görüntüleyiciler sağlar. Bu görüntüleyiciler çalıştırılabilir içeriği zaten sandbox eder, bu nedenle PDF’leri gömmek varsayılan olarak genellikle güvenlidir. Eğer `<iframe>` kullanıyorsanız, `sandbox` özniteliğini sağlamanıza gerek yoktur; hatta `sandbox` eklemek PDF görüntüleyicinin çalışmasını engelleyebilir.

Sayfanızın bir PDF önizlemesine ihtiyacı varsa, ihtiyaç duyduğunuz özelliklere göre bir öğe seçin:

`<iframe>` öğesi ilk tercih olmalıdır: `loading="lazy"` ve `referrerpolicy` gibi denetimler sunar.

Kaynak render edilmeyebilir ve yedek içerik gerekebilir ise yalnızca `<object>` kullanın.

`<embed>` öğesi, PDF önizlemesi için hiçbir avantaj sunmaz.

Tarayıcının PDF görüntüleyicisi zaten kendi sandboxing’ini sağladığından, öğe üzerinde ayrıca sandboxing gerekli değildir. Hatta `sandbox` eklemek PDF görüntüleyicinin çalışmasını engelleyebilir. Content Security Policy kullanıyorsanız, `<iframe>` kaynakları `frame-src` ile, `<object>` ve `<embed>` kaynakları ise `object-src` ile denetlenir. object-src başvuru sayfasının belirttiği gibi, genellikle `object-src 'none'` tutmalısınız; bu durumda `<iframe>` tek uygulanabilir seçenek olur.

Bir PDF’yi sayfaya gömən bir `<object>` örneğine bakalım:

```html
<object data="my-pdf.pdf" type="application/pdf" width="800" height="1200">

<p>
The PDF preview is unavailable.

<a href="my-pdf.pdf">Open the PDF file.</a>
</p>

</object>
```

PDF’ler kağıt ile dijital arasında gerekli bir basamak taşını temsil ediyordu, ancak erişilebilirlik açısından birçok zorluk oluştururlar ve küçük ekranlarda okunmaları zor olabilir. Hâlâ bazı çevrelerde popüler olsalar da, bunları bir web sayfasına gömmek yerine indirilip ayrı bir sayfada okunabilmeleri için onlara bağlantı vermek çok daha iyidir.

## Özet

Web belgelerine başka içerik gömme konusu hızla çok karmaşık hale gelebilir; bu makalede, konuyu hemen ilgili görünecek kadar basit ve tanıdık bir şekilde tanıtmaya çalıştık; aynı zamanda ilgili teknolojilerin daha gelişmiş özelliklerinden bazılarına da işaret ettik. Başlangıçta, gömmeyi büyük olasılıkla sayfalarınıza haritalar ve videolar gibi üçüncü taraf içerikler eklemekten öte çok fazla kullanmayacaksınız. Ancak deneyiminiz arttıkça, onlar için daha fazla kullanım alanı bulmaya başlayabilirsiniz.

Burada tartıştıklarımızın dışında harici içerik gömmeyi içeren başka birçok teknoloji de vardır. Önceki makalelerde `<video>`, `<audio>` ve `<img>` gibi bazılarını gördük; ancak keşfedilecek başka şeyler de vardır: JavaScript tarafından üretilen 2D ve 3D grafikler için `<canvas>` ve vektör grafikleri gömmek için `<svg>` gibi.

Your blueprint for a better internet.

