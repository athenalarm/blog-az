---
title: "Zavod Təhlükəsizlik Sistemlərində Şin Topologiyası və IP Multipleksləşdirilmiş Arxitekturanın Qiymətləndirilməsi: Kommersiya Siqnalizasiya Distribütorları və Sistem İnteqratorları üçün Texniki Bələdçi"
date: 2026-05-20T09:00:00+08:00
draft: false
type: "posts"
description: "Böyük miqyaslı istehsal obyektlərində RS-485 şin topologiyası ilə IP multipleksləşdirilmiş arxitekturaları müqayisə edən hərtərəfli texniki mühəndislik bələdçisi. EMI-ni necə azaltmağı, məsafə hədlərini aşmağı, gərginlik düşümlərini aradan qaldırmağı və SCADA/BMS platformaları ilə inteqrasiyanı öyrənin."
keywords: [Factory Security Systems, Bus-Topology Alarm, IP-Multiplexing Architecture, Commercial Alarm Distributors, System Integrators, Industrial Intrusion Alarm, RS-485 Alarm Bus, SIA DC-09, Factory Alarm System Design]
---

40,000 m²-lik istehsal kompleksi üçün seçdiyiniz panel, pərakəndə mağazalar şəbəkəsi üçün seçdiyiniz panel ilə eyni mühəndislik sinfində deyil. Zavod mühitləri siqnalizasiya sisteminin əsas arxitekturasındakı hər bir zəifliyi üzə çıxaran elektrik, topoloji və əməliyyat məhdudiyyətləri yaradır — və bu zəifliklər birbaşa distribütor və inteqratorların zəmanət öhdəliklərinə, ödəniş edilməyən texniki xidmət müraciətlərinə və itirilmiş abunə müqavilələrinə çevrilir.

Bu bələdçi böyük miqyaslı sənaye və istehsal obyektləri üçün müdaxilə siqnalizasiya infrastrukturunun layihələndirilməsi və ya tədarükünə cavabdeh olan kommersiya siqnalizasiya distribütorları, təhlükəsizlik inteqratorları və satınalma menecerləri üçün hazırlanmışdır. O, ənənəvi analoq naqillər, [RS-485 şin topologiyası](https://athenalarm.com/athenalarm-technical-documents/burglar-alarm-knowledge/matters-485-wiring/) və müasir [IP multipleksləşdirilmiş arxitektura](https://athenalarm.com/network-alarm-system/network-alarm-monitoring-system-application/) arasında seçim zamanı yaranan real mühəndislik kompromislərini əhatə edir və bu hardware qərarlarının ümumi quraşdırma xərclərinə, monitorinq mərkəzinin uyğunluğuna və uzunmüddətli xidmət marjasına təsirini izah edir.

Geniş təhlilə keçməzdən əvvəl əsas mühəndislik yekununu qeyd edək: çoxsaylı istehsal zonalarına malik olan və 3,000 m²-dən böyük sahəni əhatə edən istənilən zavod layihəsində sadə xətti analoq sistem uğursuzluğa məhkumdur. Burada əsas sual şin və ya IP arxitekturasından istifadə edilib-edilməməsi deyil — əsas məsələ bu iki texnologiyanın düzgün layihələndirilməsidir.

---

## Sənaye EMI-nin Siqnalizasiya Şininin Etibarlılığına Təsiri

İstehsalat sahələri elektromaqnit və elektrik baxımından ən əlverişsiz mühitlərdən hesab olunur. Konveyer mühərriklərində və CNC şpindellərində istifadə olunan tezlik tənzimlənən intiqallar (VFD) geniş spektrdə (çox vaxt 10 kHz ilə 30 MHz arasında) güclü keçirici küy yaradır. Bu küy, güc magistrallarına paralel uzanan ekransız siqnal kabellərinə birbaşa təsir edir. Ağır sənaye kommutasiya aparatları kommutasiya prosesləri zamanı induktiv keçidlər yaradır və yaxınlıqdakı aşağı gərginlikli idarəetmə naqillərində 50–200 V həcmində gərginlik sıçrayışlarına səbəb ola bilər. Hətta böyük lüminesans işıqlandırma blokları 50/60 Hz harmoniklərində tutum əlaqəsi (capacitive coupling) yaradaraq siqnal xətlərinə müdaxilə edir.

Siqnalizasiya data şini mühitində bu müdaxilə mənbələri təhrif olunmuş məlumat paketlərinə, xəyali zona tətiklənmələrinə və panelin gözlənilmədən yenidən başlamasına səbəb olur. Real tətbiqlərdə VFD tərəfindən yaradılan keçirici küyün RS-485 siqnalizasiya data freymlərini təhrif etməsi mühəndislərin qarşılaşdığı ən kritik fiziki maneələrdən biridir. Ənənəvi analoq zona dövrəsi demək olar ki, sıfır küy toxunulmazlığına malikdir: panelin aşkarlama həddindən yuxarı olan istənilən induksiya gərginliyi sistem tərəfindən müdaxilə hadisəsi kimi qəbul edilir. Texniklər istehsalat sahələrində günlərlə xəyali həyəcan siqnallarının səbəbini axtarırlar və nəticədə bunun real müdaxilədən deyil, yaxınlıqdakı konveyer xəttinin işə düşməsindən qaynaqlandığını görürlər.

RS-485 diferensial siqnal ötürülməsi mexanizmi bu problemi qismən həll edir. Qəbuledici hər hansı bir naqilin mütləq gərginliyinə deyil, iki naqil arasındakı gərginlik fərqinə cavab verdiyi üçün hər iki naqilə bərabər şəkildə daxil olan ümumi rejim küyü (common-mode noise) ləğv edilir. Bu, tək-sonlu analoq dövrələrlə müqayisədə 20–40 dB ümumi rejim küyünün rədd edilməsini təmin edir ki, bu da yüngül sənaye mühitləri üçün kifayətdir. Lakin, ağır sənaye obyektlərində kabel marşrutu düzgün seçilmədikdə və ya kabel uzunluğu protokolun elektrik hüdudlarına yaxınlaşdıqda, yüksək tezlikli küy komponentləri məlumat freymlərini hələ də korlaya bilər. Bu səbəbdən layihələrdə [EMI müdaxilə azaldılması] strategiyalarının tətbiqi məcburidir.

![Athenalarm AS-9000 Ünvanlana Bilən Siqnalizasiya Paneli Quraşdırılma və Qoşulma Diaqramı](https://athenalarm.com/wp-content/uploads/2023/03/Athenalarm-burglar-alarm-manufacturer-scaled.jpg)

[IP multipleksləşdirilmiş arxitektura] üçün nəqliyyat təbəqəsi kimi istifadə olunan fiber-optik Ethernet mediası keçirici elektromaqnit müdaxiləsini tamamilə aradan qaldırır. Fiber kabellər metal ötürücülərə malik olmadığı üçün küy dalğalarını qəbul edən antenna rolunu oynamır. Məhz bu səbəbdən qaynaq sexləri, yüksək gərginlikli kommutasiya otaqları və kimyəvi emal zonalarında fiber əsaslı IP genişləndirmə modulları yalançı həyəcan filtrləmə alqoritmlərinə ehtiyac duymadan sabit işləyən yeganə memarlıq strukturudur.

---

## RS-485 Məsafə Hədləri və IP Aqreqasiya Strategiyası

EIA/TIA RS-485 standartı sonlandırılmış şəbəkədə 100 kbps sürətlə maksimum 1,200 m kabel uzunluğu müəyyən edir. Şin sürətinin adətən 9,600 ilə 38,400 baud arasında dəyişdiyi və kabel tutumunun əsas məhdudiyyət yaratdığı kommersiya siqnalizasiya paneli tətbiqlərində, [xətt təkrarlayıcısı] olmadan real iş mühiti limiti adətən 800–1,000 m təşkil edir. Kabel tutumunun yüksək olduğu və ya yanlış sonlandırma tətbiq edilən ərazilərdə bu məsafə hətta 400 m-dən aşağı düşə bilər.

Perimetr çəpərləri, xarici anbar sahələri və ya binalar arasında 300–500 m boşluqlar olan böyük zavod kompleksləri üçün bu məsafə məhdudiyyəti nəzəri bir məsələ deyil, real fiziki maneədir. Sahədə ən çox rast gəlinən imtina növü ən uzaq nodların dövri olaraq oflayn rejimə keçməsidir. Bu nasazlıqlar adətən ilkin quraşdırma və təhvil-təslim zamanı (kabel yeni çəkildikdə və temperatur sabit olduqda) aşkar edilmir; lakin sonrakı mövsümlərdə kabel izolyasiyasının rütubət udması və müqavimətin artması ilə özünü büruzə verir.

[Xətt təkrarlayıcısı] siqnalı yenidən generasiya edərək və məsafə sayğacını sıfırlayaraq fiziki RS-485 şinini uzadır. Məsələn, 900 m nöqtəsində quraşdırılmış repeater şinin daha 1,200 m uzadılmasına imkan verir. Lakin hər bir [xətt təkrarlayıcısı] siqnal keçidinə 1–3 ms sabit gecikmə (latency) əlavə edir və sistemin ümumi aparat zəifliyini artırır. Çoxsaylı binalardan ibarət zavodlarda mərkəzi mühafizə otağından çıxan və 3,500 m perimetr boyunca 3-4 repeater ilə ardıcıl (daisy-chain) qoşulan xətt texniki baxımdan mümkün görünsə də, əməliyyat cəhətdən olduqca kövrəkdir: tək bir kabel qırılması qırılma nöqtəsindən sonrakı bütün nodları sistemdən tamamilə təcrid edir.

Bu nöqtədə IP aqreqasiya arxitekturası struktur baxımından kəskin üstünlük qazanır. Hər bir binada və ya istehsalat sahəsində lokal şin nəzarətçisi (zona genişləndiricisi və ya IP modulu) yerləşdirməklə və məlumatları zavodun mövcud [fiber LAN magistralı] vasitəsilə mərkəzi [ünvanlana bilən siqnalizasiya paneli] sisteminə ötürməklə məsafə məhdudiyyətləri kökündən aradan qaldırılır. Beləliklə, fərdi RS-485 şinləri bina daxilində saxlanılaraq 200–400 m limitini keçmir, magistral aqreqasiya təbəqəsi isə fiber-optik TCP/IP üzərindən işləyir ki, bu da məsafə baxımından praktiki olaraq limitsizdir. Siqnalizasiya panelindən fiber çeviriciyə, oradan LAN kommutatoruna, IP moduluna və lokal şinə: miqyaslana bilən sənaye təhlükəsizliyinin əsas düsturu budur.

Lakin unutmamaq lazımdır ki, zavod LAN siyasətlərindən asılılığın quraşdırma və dəstək zamanı ziddiyyətlər yaratması bu sistemlərin tətbiqi zamanı əsas mühəndislik ziddiyyətlərindən birinə çevrilə bilər. İT departamentinin tətbiq etdiyi sərt daxili şəbəkə siyasətləri və port məhdudiyyətləri təhlükəsizlik avadanlıqlarının quraşdırılması mərhələsində ciddi gecikmələrə səbəb ola bilər.

---

## Uzun Siqnalizasiya Şin Dövrələri Üçün Gərginlik Düşümü Mühəndisliyi

Siqnalizasiya şin naqillərində [gərginlik düşümü] böyük zavod layihələrində ən çox nəzərdən qaçırılan mühəndislik problemidir. Bu problem ən kritik məqamda — bütün detektorların eyni vaxtda aktivləşdiyi və pik cərəyan çəkdiyi tam siqnalizasiya yükü (full alarm load) zamanı ortaya çıxır və uzaq nodların fasiləli sıradan çıxmasına səbəb olur.

Gərginlik düşümünü hesablayan əsas fiziki düstur:

$$V_{\text{drop}} = 2 \times I \times R \times L$$

Burada:
* $I$ = dövrədəki bütün nodların ümumi standby və ya aktiv siqnalizasiya cərəyanı (amperlə)
* $R$ = naqilin metrə düşən xüsusi müqaviməti ($\Omega/\text{m}$), naqil kəsiyindən asılı olaraq dəyişir
* $L$ = ən uzaq noda qədər olan birtərəfli fiziki məsafə (metrlə)
* 2 əmsalı cərəyanın gedən və qayıdan naqillər boyunca keçdiyi tam yolu ifadə edir

Siqnalizasiya sistemlərində geniş istifadə olunan 22 AWG çoxdamarlı naqil üçün keçirici müqaviməti təxminən $0.054\ \Omega/\text{m}$ təşkil edir. Daha qalın 18 AWG naqildə isə bu göstərici $0.021\ \Omega/\text{m}$ səviyyəsinə düşür.

### Praktiki Hesablama Nümunəsi:
Zavod daxilində uzanan və hər biri sükunət rejimində 8 mA, aktiv həyəcan rejimində isə 12 mA cərəyan çəkən 48 ədəd ünvanlı noda malik, ən uzaq nöqtəsi 650 m məsafədə yerləşən şin dövrəsini nəzərdən keçirək.
* Ümumi siqnalizasiya cərəyanı: $48 \text{ nod} \times 0.012\text{ A} = 0.576\text{ A}$
* 22 AWG standart naqil istifadə edildikdə gərginlik düşümü: $V_{\text{drop}} = 2 \times 0.576 \times 0.054 \times 650 = 40.435\text{ V}$

Bu hesablama mühəndislik reallığını dərhal ortaya qoyur: nominal 12 V DC ilə işləyən siqnalizasiya şini $40.435\text{ V}$ həcmində gərginlik düşümünü kompensasiya edə bilməz. Təcrübədə daxili RS-485 transiverlərinin minimum işləmə həddi adətən 10.5 V DC təşkil edir və gərginlik bu həddən aşağı düşdükdə nodlar panel ilə rabitəni tamamilə kəsir. Paneldə nominal qidalanma gərginliyinin 13.8 V DC olduğunu nəzərə alsaq, nodların dayanıqlı işləməsi üçün cəmi 3.3 V gərginlik marjası (headroom) qalır.

Bu problemin mühəndislik həlli sadəcə "daha qalın kabel çəkmək" deyil. Düzgün texniki yanaşma aşağıdakı addımlardan ibarətdir:
1. 200 metrdən uzun olan magistral xətlərdə mütləq 18 AWG və ya 16 AWG kabellərə keçid etmək (bu, gərginlik düşümünü 60–70% azaldır).
2. Paylanmış güc idarəetməsi tətbiq etmək — uzun dövrələrin orta və ya son nöqtələrində [yardımçı enerji təchizatı] blokları quraşdırmaq.
3. Tək bir uzun dövrəni bütün zavod boyu uzatmaq əvəzinə, yüksək sıxlıqlı detektor zonalarını şin genişləndiriciləri vasitəsilə daha qısa alt dövrələrə seqmentləşdirmək.

Layihələndirmə mərhələsində bu hesablamaların aparılmaması quraşdırma mərhələsində büdcənin kəskin şəkildə aşılmasına səbəb olur. Fəaliyyətdə olan bir sənaye müəssisəsində kabel kanallarından yenidən ağır kabellərin çəkilməsinin təkrar işçilik xərcləri olduqca yüksəkdir.

---

## Hibrid Zavod Siqnalizasiya Şəbəkə Arxitekturası

Böyük miqyaslı sənaye obyektlərində yüksək performans göstərən yeganə model hiyerarxik hibrid şəbəkə strukturudur: hər bir fərdi bina və ya istehsal sahəsi daxilində lokal [RS-485 şin topologiyası] dövrələri qurulur, bu dövrələr IP əsaslı genişləndirmə və aqreqasiya modullarında toplanır və zavodun daxili [fiber LAN magistralı] vasitəsilə mərkəzi [ünvanlana bilən siqnalizasiya paneli] infrastrukturuna ötürülür.

![Athenalarm Şəbəkə Siqnalizasiya Monitorinq Sisteminin Arxitektura Diaqramı](https://athenalarm.com/wp-content/uploads/2022/05/Athenalarm-network-alarm-monitoring-system-1-1024.jpg)

Bu hibrid yanaşma üç əsas mühəndislik problemini eyni vaxtda həll edir:
* **Məsafə:** Hər bir lokal RS-485 seqmenti bina daxilində 200–400 m hüdudlarında saxlanılır ki, bu da elektrik siqnallarının tam sabitliyini təmin edir. Şəbəkənin IP təbəqəsi isə məlumatları istənilən məsafəyə itkisiz çatdırır.
* **Zona Tutumu:** Standart daxili interfeyslər birbaşa məhdud sayda şin ünvanını dəstəkləyə bilər. Hər biri öz lokal RS-485 alt şinini idarə edən IP zona aqreqatorlarının tətbiqi sayəsində tək bir mərkəzi panel çoxbinalı kampus daxilində minlərlə paylanmış [zona bölməsi] strukturunu asanlıqla idarə edir.
* **Xətalardan Təcridolunma:** C binasındakı RS-485 seqmentində baş verən kabel qırılması və ya daxili qısa qapanma A, B və ya D binalarındakı zonaların işinə heç bir təsir göstərmir. Hər bir binanın IP genişləndirmə modulunun mərkəzi panel ilə əlaqəsi tam müstəqil qalır.

Praktiki quraşdırma ardıcıllığı belədir: texnik ilk növbədə hər bir binanın lokal RS-485 şinini işə salır, nod ünvanlarını və siqnal bütövlüyünü yoxlayır, daha sonra IP modulunu zavod daxili LAN şəbəkəsinə qoşur. Mərkəzi idarəetmə paneli hər bir binanı fiziki uzun naqil kimi deyil, yüksək ötürücülüyə malik daxili məntiqi genişlənmə modulu kimi qəbul edir. Monitorinq mərkəzinə hesabatlılıq isə birbaşa panel səviyyəsində [SIA DC-09] protokolu vasitəsilə IP üzərindən həyata keçirilir — beləliklə, detektorun paneldən 50 m və ya 2,000 m uzaqlıqda yerləşməsindən asılı olmayaraq, mərkəzi stansiya siqnalları eyni sürət və dəqiqliklə qəbul edir.

Əməliyyat xəbərdarlığı: Bu memarlıq quruluşu tamamilə zavod daxili şəbəkə infrastrukturunun dayanıqlılığından asılıdır. Şəbəkə idarəetməsinin tamamilə İT departamentində olduğu obyektlərdə daxili təhlükəsizlik qaydaları quraşdırma maneələri yarada bilər. Müqavilə imzalanmazdan əvvəl siqnalizasiya sisteminin zavodun ümumi istehsalat şəbəkəsindənmi, yoxsa tamamilə təcrid olunmuş daxili təhlükəsizlik VLAN xəttindənmi istifadə edəcəyi dəqiqləşdirilməlidir. Müştərək istehsalat şəbəkələri uzunmüddətli xidmət mərhələsində kənar daxili şəbəkə asılılıqları yaradır.

### Texniki Məlumat Matrisi: Kommunikasiya Arxitekturalarının Müqayisəsi

| Texniki Parametr | Ənənəvi Analoq Zonalar | Sənaye RS-485 Şini | IP Multipleksləşdirilmiş Arxitektura |
| :--- | :--- | :--- | :--- |
| **Maksimum Topoloji Məsafə** | ~300 m (dövrə müqavimət limiti) | Repeater olmadan seqment başı 1,200 m-ə qədər | LAN/Fiber magistralı ilə limitsiz məsafə |
| **Maksimum Nod / Zona Tutumu** | Hər naqil xəttinə 1 zona | Dövrə başına 128–256 nod (paneldən asılı olaraq) | IP aqreqatorları vasitəsilə minlərlə zona |
| **Küy Toxunulmazlığı (EMI/RFI)** | Zəif — induksiya gərginliyinə həssasdır | Yüksək — diferensial siqnal ümumi rejim küyünü rədd edir | Çox Yüksək — tam təcrid olunmuş Ethernet və ya fiber media |
| **Qəza Rejimində Redundantlıq** | Yoxdur — tək naqil qırılması zonanı sıradan çıxarır | Şin izolyasiya modulları — qısa qapanmanı seqmentdə məhdudlaşdırır | İki-kanallı kommunikasiya / Spanning Tree Protokolu (STP) |
| **Diaqnostika İmkanları** | Binaar: yalnız açıq dövrə və ya qısa qapanma | Nod səviyyəsində sorğulama: ünvan, status, sabotaj, qidalanma | Paket səviyyəsində telemetriya, real vaxt rejmində IP ping və heartbeat nəzarəti |
| **False Alarm Həssaslığı (EMI səbəbli)** | Çox Yüksək | Orta (ekranlama və düzgün torpaqlama tələb olunur) | Aşağı (fiber seqmentlər küyə tam dözümlüdür) |
| **10 İllik Ümumi Sahiblik Dəyəri (TCO)** | Yüksək — sistem genişləndikdə tamamilə yenilənmə tələb olunur | Orta — şin tutumu daxilində modulyar genişlənmə | Aşağı — proqram təminatı səviyyəsində genişlənmə, əlavə naqil tələb olunmur |

---

## SIA DC-09 və Sənaye Monitorinq Mərkəzi Hesabatlığı

1990-cı illərin əvvəllərində yaradılmış [Contact ID] protokolu siqnalizasiya hadisələrini standart telefon xətləri (PSTN) üzərindən dual-tone multi-frequency (DTMF) audio siqnalları şəklində ötürür. Hər bir hadisə daxili hesab nömrəsi, hadisə kodu, [zona bölməsi] və zona nömrəsini ifadə edən audio ton partlayışları şəklində kodlaşdırılır və adətən hər rəqəm üçün 103 ms sürətlə ötürülür. Tam bir həyəcan siqnalının sənaye mərkəzinə çatdırılması tək bir PSTN bağlantısı üzərindən 3–8 saniyə çəkir.

Perimetr müdaxiləsi zamanı onlarla zonadan (hərəkət sensorları, infraqırmızı baryerlər, daxili qapı sensorları) eyni vaxtda siqnal ötürən böyük bir sənaye obyekti üçün bu ötürmə qabiliyyəti tamamilə yetərsizdir. [Contact ID] protokolu daxili miqyası kiçik olan obyektlər üçün nəzərdən tutulmuşdur və eyni vaxtda 50 fərqli zona statusunu ötürən mürəkkəb sənaye obyektləri üçün yararlı deyil.

[SIA DC-09] protokolu isə birbaşa TCP və ya UDP bağlantıları vasitəsilə mərkəzi monitorinq stansiyasının qəbuledicisinə strukturlaşdırılmış məlumat paketləri göndərən yerli bir IP hesabat protokoludur. Hər bir paket daxili vaxt möhürü (milisaniyə dəqiqliyi ilə), hadisə növü, mətn tipli zona təsviri və genişləndirilmiş məlumat sahələrini ehtiva edən formatlaşdırılmış ASCII sətirlərindən ibarətdir. Tək bir TCP bağlantısı, köhnə [Contact ID] sistemindəki DTMF siqnal xəttinin yaratdığı növbə gözləmə problemi olmadan çox sayda həyəcan məlumatını eyni anda daşıya bilər.

### Sənaye Obyektləri üçün Əsas Protokol Fərqləri:
* **Şifrələmə:** [SIA DC-09] ötürülən hadisə paketlərinin AES-256 standartı ilə yerli olaraq şifrələnməsini dəstəkləyir. [Contact ID] isə analoq xətlər üzərindən tamamilə açıq şəkildə ötürülür.
* **Çatdırılma Təsdiqi:** DC-09 protokolu qəbul edilən hər bir paket üçün mərkəzi qəbuledicidən təsdiq siqnalı (acknowledgment) tələb edir, bu da panelə çatdırılmanı təsdiq etməyə və xəta baş verdikdə paketi yenidən göndərməyə imkan verir.
* **Mətn Tipli Zona Təsvirləri:** DC-09 protokolu monitorinq mərkəzinə sadəcə "Zona 047" kodu əvəzinə "Şimal Perimetri Qapı 3 İnfraqırmızı Baryer" kimi sərbəst daxil edilmiş mətn etiketlərini ötürür. 500 zonalı bir zavod idarəetməsində bu funksionallıq kritik əhəmiyyət kəsb edir.
* **İki-Kanallı Ötürmə:** DC-09 protokolu iki müstəqil IP yolu üzərindən (əsas korporativ WAN və ehtiyat mobil şəbəkə) eyni vaxtda işləyə bilər. [iki-kanallı kommunikasiya modulu] tətbiq edildikdə qəbuledici hər bir siqnalın hansı kanal vasitəsilə daxil olduğunu qeydiyyata alır.

İdxalçı və distribütorlar üçün keçid mərhələsindəki əsas maneə odur ki, mövcud monitorinq mərkəzlərində DC-09 paketlərini düzgün emal etmək üçün qəbuledici proqram təminatının yenilənməsi tələb oluna bilər. Layihə təklifini hazırlamazdan əvvəl mərkəzi stansiyanın bu protokolla tam uyğunluğunu yoxlayın.

---

## Zavod Təhlükəsizlik Sistemlərində SCADA və ONVIF İnteqrasiyası

Böyük istehsalat müəssisələri siqnalizasiya sistemlərinin mövcud əməliyyat texnologiyaları (OT) infrastrukturu ilə tam inteqrasiya olunmasını tələb edir: daxili prosesləri idarə edən SCADA platformaları, havalandırma və giriş-çıxışı tənzimləyən Bina İdarəetmə Sistemləri (BMS) və videomüşahidə platformaları (VMS).

![Zavod Şəbəkə Siqnalizasiya Monitorinq Sisteminin İnteqrasiya Diaqramı](https://athenalarm.com/wp-content/uploads/2022/05/Network-alarm-monitoring-system-diagram-01-1024.jpg)

### Modbus-TCP və SCADA İnteqrasiyası
[Modbus-TCP] interfeysini dəstəkləyən müasir siqnalizasiya panelləri SCADA sistemlərinə zona statuslarını, daxili sistem xətalarını və qidalanma vəziyyətlərini birbaşa registr dəyərləri (register values) şəklində oxumağa imkan verir. Strukturlaşdırılmış xəritələndirmə zamanı hər bir bit bir zonanın aktiv/normal vəziyyətini ifadə edir. SCADA sistemi paneli təyin olunmuş intervallarla (adətən 1–5 saniyə) sorğulayır və siqnal daxil olduqda daxili təhlükəsizlik ssenarilərini — konveyer xətlərinin dayandırılması, qəza işıqlarının işə salınması və ya daxili qapıların kilidlənməsi kimi prosesləri avtomatik icra edir. Kimyəvi emal və ya təhlükəli maddələrin saxlandığı sənaye müəssisələrində bu inteqrasiya əlavə funksiya deyil, obyektin əməliyyat təhlükəsizliyi tələbidir.

### Kamera İnteqrasiyası üçün ONVIF Profile S Standartı
Zavodun şərq perimetrində yerləşən infraqırmızı baryer aktivləşdikdə, sistem heç bir insan müdaxiləsi olmadan ən yaxın PTZ kameranı həmin nöqtəyə yönləndirməli və dərhal qeyd prosesini başlatmalıdır. Bu ssenari müxtəlif markalı avadanlıqlar arasında daxili IP əmrlərini standartlaşdıran [ONVIF Profile S] protokolu vasitəsilə həyata keçirilir. Ünvanlı siqnalizasiya paneli (və ya daxili IP modulu) kameranın daxili şəbəkə ünvanını, hədəf PTZ preset nömrəsini və video qeyd əmrini ehtiva edən daxili [ONVIF Profile S] paketlərini birbaşa şəbəkəyə göndərir. Bu, bahalı və mürəkkəb xarici inteqrasiya proqramlarına olan ehtiyacı aradan qaldırır.

### Yerli SDK və REST API Dəstəyi
Bəzi qabaqcıl istehsalçılar — o cümlədən [Athenalarm] platforması — standart Modbus registrləri və ya ONVIF əmrləri ilə məhdudlaşmayan, daha mürəkkəb və fərdiləşdirilmiş proqram inteqrasiyaları yaratmağa imkan verən daxili SDK kitabxanaları və REST API interfeysləri təqdim edir. Bu imkan, inteqratorların siqnalizasiya sistemini müştərinin vahid komanda mərkəzi proqram təminatına (PSIM) problemsiz daxil etməsinə şərait yaradır. Layihə xərclərini hesablayarkən daxili təhlükəsizlik divarlarının (firewall) port məhdudiyyətlərini və test mərhələləri üçün tələb olunan mühəndislik saatlarını mütləq nəzərə alın.

### İki-Kanallı Kommunikasiya (LTE + LAN) vasitəsilə Zavod Redundantlığının Təmini
Təhlükəsizlik sisteminin xarici monitorinq stansiyası ilə əlaqə qurmaq üçün yalnız tək bir rabitə kanalından (məsələn, daxili fiber xətt və ya korporativ LAN) istifadə etməsi daxili risk analizlərində qəbul edilməz tək nöqtəli uğursuzluq (single point of failure) riski yaradır.

Sənaye obyektlərində qəbul edilmiş mühəndislik standartı, daxili rabitə xətlərinin vəziyyətini avtomatik yoxlayan (heartbeat monitoring) və fasiləsiz keçid təmin edən [iki-kanallı kommunikasiya modulu] tətbiqidir:
* **Əsas Kanal:** Zavodun daxili LAN xətti və ya daxili internet kanalı vasitəsilə [SIA DC-09] protokolu üzərindən mərkəzi qəbulediciyə birbaşa TCP/IP bağlantısı.
* **Ehtiyat Kanal:** Şəbəkə təhlükəsizliyi siyasətinə uyğun olaraq daxili təcrid olunmuş xüsusi APN (Private APN) və ya standart operator daxili SIM kartı ilə işləyən daxili 4G LTE modulu.

Panel mərkəzi qəbulediciyə hər iki kanal vasitəsilə təyin olunmuş intervallarla (adətən hər 30–90 saniyədən bir) mütəmadi nəzarət siqnalları (heartbeat) göndərir. Qəbuledici daxili proqram təminatı vasitəsilə hər iki xətti nəzarətdə saxlayır. Əgər əsas kanal üzərindən gələn siqnal təyin olunmuş zaman pəncərəsi ərzində (məsələn, ardıcıl 3 sorğu müddətində, yəni 90–270 saniyə) kəsilərsə, sistem dərhal əsas xəttin sıradan çıxdığını qeyd edir və ehtiyat daxili mobil şəbəkə kanalı vasitəsilə məlumat qəbulunu fasiləsiz davam etdirir. Əsas rabitə xətti bərpa olunduqda, sistem heç bir insan müdaxiləsi olmadan avtomatik olaraq ilkin rejimə qayıdır.

Sənaye obyektlərində ən çox rast gəlinən real qəza ssenariləri bunlardır:
* Daxili tikinti və ya qazıntı işləri zamanı magistral fiber-optik kabelin qırılması.
* İT komandasının gecə saatlarında apardığı daxili profilaktik işlər zamanı korporativ şəbəkə şlüzünün (gateway) müvəqqəti dayanması.
* Zavod daxilində baş verən genişmiqyaslı enerji kəsintisi — bu zaman bəzi daxili şəbəkə kommutatorları UPS qidalanma qrupuna daxil edilmədiyi üçün şəbəkə rabitəsi tamamilə kəsilir.

Daxili 4G LTE mobil modulu bu kimi qəza ssenarilərində sistemin fasiləsiz işləməsini təmin edən mühüm sığortadır. Yeni layihələndirilən sənaye obyektlərində rabitə dayanıqlığını təmin etmək üçün minimum standart kimi daxili 4G LTE Cat-M1 və ya Cat-1 sinfində olan rabitə modullarının tətbiqini mütləq şərt kimi qoyun.

---

## Şin İzolyasiyası və Sənaye Xətalarının Məhdudlaşdırılması

Sənaye obyektlərində istehsal fəaliyyəti, daxili nəqliyyat vasitələrinin hərəkəti və ya kənar ekstrimal hava şəraiti səbəbindən kabellərin fiziki zədələnməsi və qısa qapanma halları tez-tez baş verir. [Şin izolyasiya modulu] (bus isolation module) daxili serial rabitə şininə ardıcıl şəkildə quraşdırılır və özündən sonrakı seqmentin gərginlik və empedans göstəricilərini mikrosaniyə dəqiqliyi ilə nəzarətdə saxlayır.

Xarici sahədə uzanan perimetr xətlərində və ya daxili ağır maşınların hərəkət etdiyi keçid zonalarında kabel əzilməsi və ya qısa qapanma baş verdikdə, [şin izolyasiya modulu] nasazlığı dərhal aşkarlayır və həmin zədələnmiş xətt seqmentini elektron şəkildə əsas magistraldan tamamilə təcrid edir. Bu proses digər sağlam seqmentlərin fəaliyyətini qorumaq üçün mikrosaniyələr daxilində baş verir. 

Şin izolyasiya modulları olmadıqda xarici kabel xətalarının bütün siqnalizasiya şin seqmentlərini sıradan çıxarması sənaye layihələrində ən böyük risklərdən biridir; tək bir nöqtədəki qısa qapanma bütün sistemi tamamilə iflic edə bilər. Bu modulların tətbiqi sayəsində xarici çəpər xəttində baş verən xəta zavodun daxili istehsalat binasındakı mühüm daxili detektorların fəaliyyətinə mane olmur. Texniki mühəndislik qaydalarına əsasən, hər bir bina keçid nöqtəsində və xarici sahəyə çıxan hər bir xəttin başlanğıcında ən azı bir ədəd [şin izolyasiya modulu] quraşdırılmalıdır.

---

## Uzaq Nodun Oflayn Olmasının Diaqnostik Sazlama İş Axımı

Sistem istismarı dövründə mərkəzi paneldə "Uzaq Nod Oflayn" (Distant Node Offline) xətası qeydə alındıqda, texnik mühəndislər nasazlığın elektrik gərginlik düşümündən, elektromaqnit müdaxilədən (EMI) və ya daxili ünvan ziddiyyətlərindən qaynaqlandığını müəyyən etmək üçün aşağıdakı ardıcıl diaqnostik iş axımını icra etməlidirlər:

* **Addım 1:** Rəqəmsal multimetri DC gərginlik ölçmə rejiminə keçirin və oflayn rejimə düşmüş uzaq nodun müsbət (+) və mənfi (-) qidalanma terminallarındakı mütləq gərginliyi ölçün. Ölçülən gərginlik dəyərinə uyğun olaraq növbəti diaqnostik şaxələrdən birini seçin:

### Şaxə A: Ölçülən Gərginlik < 10.5V DC (Ciddi Aşağı Gərginlik Həddi)
Nodun qidalanma gərginliyi daxili RS-485 transiverinin minimum işləmə limitindən aşağıdır. Bu, xətt boyu daxili gərginlik düşümünün normadan çox olduğunu göstərir. Aşağıdakı bərpa və təmir addımlarını icra edin:
* **Naqil Kəsiyini Yoxlayın:** Xətt boyunca standart qeyri-kafi naqillərin (məsələn, uzun məsafədə 18 AWG əvəzinə səhvən 22 AWG) istifadə edilib-edilmədiyini yoxlayın.
* **Dövrə cərəyanını ölçün:** Şinə bağlı olan bütün nodların ümumi cərəyan çəkiminin mövcud enerji mənbəyinin nominal gücündən çox olmadığını təsdiqləyin.
* **Xətt Gücləndiricisi Tətbiq Edin:** Siqnal bütövlüyünü bərpa etmək üçün xəttin müvafiq nöqtəsinə daxili [xətt təkrarlayıcısı] quraşdırın.
* **Torpaqlama Dövrələrini Audit Edin:** Çoxsaylı yanlış torpaqlama nöqtələrindən yaranan parazit daxili cərəyanları və gərginlik fərqlərini yoxlayın.
* **Paylanmış Güc İnnyeksiyası:** Terminal gərginliyini nominal səviyyəyə qaldırmaq üçün dövrənin orta hissəsində lokal bir [yardımçı enerji təchizatı] bloku yerləşdirin.

### Şaxə B: Ölçülən Gərginlik 10.5V ilə 11.5V DC Arasında (Kritik Keçid Zonası)
Nod elektrik baxımından qeyri-sabit bir boz zonada işləyir. Sistem sükunət rejimində normal fəaliyyət göstərə bilsə də, tam siqnalizasiya yükü zamanı fasiləli olaraq tamamilə oflayn ola bilər. Aşağıdakı profilaktik tədbirləri icra edin:
* **Tam Yük Altında Sınaq:** Dövrədəki bütün daxili releləri və indikatorları aktivləşdirərək tam siqnalizasiya yükü yaradın və bu zaman terminal gərginliyinin dəyişməsini qeydiyyata alın.
* **Kabel Yenilənməsi Siyahısı:** Növbəti planlı zavod profilaktik dayanması zamanı həmin xətt seqmentinin naqil kəsiyinin böyüdülməsini iş planına daxil edin.
* **Güc İnnyeksiyası Planı:** Gələcəkdə kabel müqavimətinin artması ilə yarana biləcək risklərin qarşısını almaq üçün xəttə əlavə [yardımçı enerji təchizatı] qoşulmasını layihələndirin.

### Şaxə C: Ölçülən Gərginlik ≥ 11.5V DC (Kifayət edən Gərginlik / Siqnal Problemi)
Noda daxil olan elektrik qidalanması tamamilə normaldır. Oflayn status elektrik çatışmazlığından deyil, birbaşa siqnal korlanması, hardware zamanlama xətaları və ya məntiqi data ziddiyyətlərindən qaynaqlanır. Aşağıdakı dərin diaqnostika addımlarını icra edin:
* **AC Dalğalanma Gərginliyini (AC Ripple) Ölçün:** Multimetri AC rejiminə keçirərək (və ya portativ osilloqraf vasitəsilə) yaxınlıqdakı tezlik tənzimlənən intiqallardan (VFD) xəttə daxil olan yüksək tezlikli common-mode küy dalğalarını yoxlayın.
* **Şin Sonlandırmasını Yoxlayın:** RS-485 serial şininin fiziki son nöqtəsində lazımi daxili sonlandırma rezistorunun ($120\ \Omega$) düzgün quraşdırıldığını və lazımi müqavimət dəyərini verdiyini yoxlayın.
* **Ünvan Ziddiyyətlərini Audit Edin:** Eyni şin dövrəsi üzərində səhvən eyni daxili ünvana proqramlaşdırılmış iki fərqli cihazın yarada biləcəyi səssiz məlumat toqquşmalarını (addressing conflicts) yoxlamaq üçün cihazların fiziki DIP-switch və ya daxili proqram ünvanlarını yoxlayın.
* **Ekran Kəsilməzliyinin Yoxlanılması:** Kabelin daxili ekran (shield) naqilinin bütün daxili qovşaqlarda kəsilmədən davam etdiyini və yalnız əsas idarəetmə paneli tərəfindən düzgün şəkildə torpaqlandığını yoxlayın (bu, iki tərəfli torpaqlamadan yaranan daxili ground-loop probleminin qarşısını alır).

---

## Kommersiya Distribütorları və B2B İdxalçıları üçün Kommersiya Dəyəri

### Anbar Optimizasiyası: Modulyar Siqnalizasiya Panellərinin Distribütorlar üçün SKU Sayını Azaltması
İndustrial və kommersiya bazarları üçün təhlükəsizlik avadanlıqlarının paylanması və satışı iqtisadiyyatı birbaşa daxili anbar saxlama strateji səmərəliliyindən asılıdır. Kiçik obyektlər üçün ayrı 16 zonalı panel, orta miqyaslı layihələr üçün 64 zonalı panel və böyük sənaye obyektləri üçün tamamilə fərqli 256 zonalı panel saxlayan distribütor faktiki olaraq üç fərqli məhsul xətti, üç fərqli texniki dəstək yükü və üç fərqli daxili periferiya qrupu daşımaq məcburiyyətində qalır.

Modulyar panel arxitekturası bu ticari problemi tamamilə həll edir. Vahid bir əsas idarəetmə ana platası platforması — daxili əsas zonaları ilə birlikdə — əlavə [RS-485 şin topologiyası] genişləndirmə kartları, IP zona aqreqatorları və mobil kommunikasiya modulları ilə birləşdirildikdə, distribütorun əlindəki eyni vahid master SKU həm 16 zonalı kiçik bir mağazanın quraşdırılmasında, həm də 400 zonalı mürəkkəb bir sənaye müəssisəsinin layihəsində istifadə edilə bilər. Distribütor fərqli tutumlu hazır panellər yerinə yalnız əsas panelləri və lazımi modulları anbarda saxlayır.

Bu yanaşmanın anbarda dondurulmuş maliyyə vəsaitlərinə birbaşa müsbət təsiri ölçülə biləndir: SKU sayının azaldılması fərdi məhsul sətirləri üzrə minimum sifariş miqdarını (MOQ) aşağı salır, anbar dövriyyəsini sürətləndirir və istehsalçı yeni model buraxdıqda əldə qalan köhnə fərdi panellərin yarada biləcəyi zərər riskini tamamilə aradan qaldırır. Fərqli coğrafi bazarlara və fərqli layihə miqyaslarına xidmət göstərən böyük regional distribütorlar üçün modulyar arxitektura eyni anbar ehtiyatı ilə bütün tələbləri qarşılamağa imkan verir.

[Athenalarm] məhsul platforması məhz bu ticari çeviklik prinsipi üzərində qurulmuşdur: eyni əsas panel arxitekturası sahədə aparılan modulyar genişləndirmələr vasitəsilə kiçik biznes obyektlərindən irimiqyaslı sənaye komplekslərinə qədər bütün layihə növlərini dəstəkləyir və inteqratorların hər layihə üçün tamamilə fərqli bir məhsul ailəsini öyrənmək məcburiyyətini ortadan qaldırır.

### Aşağı Sahiblik Dəyəri (TCO) vasitəsilə Layihə Rəqabətliliyinin Artırılması
Böyük sənaye və korporativ satınalma tenderlərində ən güclü arqument ilkin quraşdırma xərci deyil, sistemin 10 illik Ümumi Sahiblik Dəyəridir (TCO). Sənaye müəssisələrinin satınalma rəhbərləri yaxşı bilirlər ki, quraşdırılan sistem minimum 8–15 il istismar ediləcəkdir. Sürətli texnoloji köhnəlmə və ya daxili qapalı protokollar səbəbindən hər 5 ildən bir tamamilə dəyişdirilməsi tələb olunan sistem təhlükəsizlik investisiyası deyil, şirkət üçün təkrarlanan daxili kapital zərərdir.

Sənaye obyektləri üçün aparılan daxili TCO təhlili aşağıdakı amillərə əsaslanmalıdır:
* **Genişlənmə Çevikliyi:** Müəssisə dördüncü ildə yeni bir istehsalat binası tikdikdə, mövcud panel sadəcə bir şin modulu əlavə edilməklə genişləndirilə bilərmi, yoxsa mərkəzi idarəetmə sistemini tamamilə dəyişmək lazımdır? Standart və açıq layihələndirilmiş RS-485 şin sistemləri böyük infrastruktur dəyişikliyi etmədən mərhələli şəkildə böyüməyə imkan verir.
* **Protokol Uzunömürlülüyü:** Standartlaşdırılmış və sənayedə qəbul edilmiş açıq protokollardan (RS-485, [SIA DC-09], [Modbus-TCP]) istifadə edən sistemlər tək bir istehsalçının daxili qərarlarından və ya bazar fəaliyyətindən asılı qalmır. Əgər konkret bir şin genişləndirmə modulunun istehsalı dayandırılarsa, eyni RS-485 standartına və panel ünvanlama strukturuna uyğun gələn başqa bir markanın alternativi sistemə daxil edilə bilər. Tamamilə qapalı və xüsusi daxili protokollarla işləyən sistemlər isə müştərini 10 illik müddətdə tək bir tədarükçüdən asılı vəziyyətə salır ki, bu da ciddi kommersiya riskidir.
* **Monitorinq Çevikliyi:** Xarici monitorinq mərkəzinə hesabatları standart [SIA DC-09] protokolu vasitəsilə IP üzərindən ötürən bir müəssisə, gələcəkdə daxili hardware infrastrukturunu dəyişmədən istənilən digər lisenziyalı monitorinq mərkəzi ilə müqavilə imzalaya bilər. Bu, xidmət müqaviləsinin yenilənməsi mərhələsində daxili satınalma komandası üçün güclü bir kommersiya rıçaqıdır. Qapalı daxili protokollar isə müştərini yalnız konkret bir monitorinq mərkəzinə bağlayır və rəqabətli qiymət almaq imkanını məhdudlaşdırır.

Bu texniki amillərin cəmi, ilkin hardware satınalma qiyməti qapalı sistemlərlə müqayisədə bir qədər fərqli olsa belə, 10 illik daxili TCO modellərində açıq arxitekturalı modulyar sistemlərin kəskin şəkildə daha səmərəli olduğunu sübut edir.

---

## Sənaye Siqnalizasiya Sistemləri Üçün Texniki FAQ

#### S1: RS-485 şin topologiyalı siqnalizasiya sistemi video verifikasiya inteqrasiyasını dəstəkləyə bilərmi?
**Bəli, lakin yüksək həcmli video məlumat axını daxili şin təbəqəsi üzərindən deyil, birbaşa IP təbəqəsi vasitəsilə idarə olunur.** Lokal RS-485 şini yalnız zona aktivləşmə siqnallarını və rəqəmsal hadisə kodlarını minimal gecikmə ilə mərkəzi panelə çatdırır. İdarəetmə paneli isə öz növbəsində daxili IP rabitə modulu vasitəsilə TCP/IP şəbəkəsi üzərindən [ONVIF Profile S] əmrlərini göndərərək müvafiq kameraları hədəf preset nöqtələrinə yönləndirir və monitorinq mərkəzinə video axınını başladır. Hər iki təbəqə paralel işlədiyi üçün video məlumatları şin daxili rabitə sürətinə heç bir mənfi təsir göstərmir.

#### S2: Şin izolyasiya modulları böyük sənaye zavod şəbəkələrini necə qoruyur?
**[Şin izolyasiya modulu] serial RS-485 data xəttinə ardıcıl qoşulur və özündən sonrakı kabel seqmentinin daxili gərginlik və empedans göstəricilərini fasiləsiz yoxlayır.** Məsələn, xarici sahədə uzanan perimetr kabellərində qazıntı işləri və ya ildırım vurması səbəbindən qısa qapanma baş verdikdə, modul nasazlığı millisekundlar daxilində qeydə alır və daxili açar vasitəsilə zədələnmiş seqmenti əsas xətdən ayırır. Beləliklə, xatadan əvvəlki bütün daxili magistral problemsiz işləməyə davam edir. Bu modullar quraşdırılmadıqda, tək bir nöqtədəki kabel qısa qapanması bütün şini çökdürərək zavodun daxili detektorlarının da fəaliyyətini tamamilə dayandırır.

#### S3: Müasir zavod siqnalizasiya infrastructuresunda niyə SIA DC-09 protokolu Contact ID-dən daha üstün tutulur?
**[SIA DC-09] birbaşa IP (Ethernet və ya mobil rabitə) üzərindən işləmək üçün layihələndirilmiş, daxili AES-256 şifrələməsinə, milisaniyə dəqiqlikli daxili zaman möhürünə və tam çatdırılma təsdiqinə malik müasir sənaye protokoludur.** Köhnə [Contact ID] protokolu isə analoq telefon xətləri üzərindən DTMF audio tonları ilə işləyir və hər hadisə üçün 3–8 saniyə ötürmə müddəti tələb edir. Perimetr pozuntusu zamanı eyni anda onlarla fərqli zonadan siqnal göndərən sənaye müəssisələrində [Contact ID] daxili bufer növbəsi yaradır və məlumat gecikmələrinə səbəb olur. Bundan əlavə, DC-09 monitorinq mərkəzinə tam mətnli zona adlarını ötürməyə imkan verir.

#### S4: Zavod mühitində 300 metrdən çox olan RS-485 şin marşrutları üçün tövsiyə olunan minimum naqil kəsiyi hansıdır?
**Orta cərəyan yükünə malik 300 metrlə 800 metr arasında uzanan sənaye şin runs üçün praktiki minimum mühəndislik standartı 18 AWG ekranlı burulmuş cüt (shielded twisted-pair) kabeldir.** Məsafə 1,000 metrə yaxınlaşdıqda və ya tək bir dövrəyə bağlı olan ünvanlı cihazların sayı 40 ədədi keçdikdə, naqil daxili daxili müqavimətini azaltmaq və pik alarm yükü zamanı uzaq nöqtələrdə [gərginlik düşümü] riskinin qarşısını almaq üçün mütləq 16 AWG kabellərdən istifadə edilməlidir. Kabel növündən asılı olmayaraq, ən uzaq nodun terminalındakı gərginliyin 10.5 V DC-dən aşağı düşməyəcəyi hesablama ilə təsdiqlənməlidir.

#### S5: Tezlik tənzimlənən intiqallardan (VFD) gələn EMI istehsalat sahələrində detektor seçiminə necə təsir edir?
**Ağır mühərrikləri və VFD modullarını ehtiva edən istehsalat sahələrində standart hərəkət detektorları daxili sxemlərinə daxil olan yüksək daxili EMI küy dalğaları səbəbindən tez-tez yalançı həyəcan siqnalları (false alarms) verir.** Bu ərazilərdə yalnız daxili gücləndirilmiş RF və tezlik filtrlərinə (EMI-hardened) malik daxili sənaye sinfi detektorlar quraşdırılmalıdır. Mümkün olan yerlərdə daxili siqnal müddəti təhlili aparan ağıllı rəqəmsal detektorlara və həm infraqırmızı (PIR), həm də mikrodalğalı (microwave) aşkarlama texnologiyasını birləşdirən dual-tech sensorlara üstünlük verilməlidir. Bu, motor işə düşən zaman yaranan elektrik sıçrayışlarını real müdaxilə hadisələrindən tam ayırmağa imkan verir.

---

## Mühəndislik İstinad Cədvəli: Termin və Protokol Sorğu Kitabçası

| Termin / Abbreviatura | Kateqoriya | Sənaye Tərifi və Tətbiq Sahəsi |
| :--- | :--- | :--- |
| **RS-485** | Fiziki Şin Standartı | Diferensial iki-naqilli serial rabitə protokolu; 100 kbps sürətdə maks 1,200 m məsafəni dəstəkləyir; ünvanlı panellərdə əsas daxili sahə şini kimi tətbiq olunur. |
| **SIA DC-09** | Hesabat Protokolu | Şifrəli (AES-256) və çatdırılma təsdiqli yerli IP siqnal ötürmə standartı; sənaye monitorinq mərkəzləri ilə panel arasında əsas rabitəni təmin edir. |
| **Contact ID** | Köhnə Hesabat Standartı | DTMF tonlarına əsaslanan, analoq telefon xətləri üçün nəzərdən tutulmuş köhnə siqnal forması; sürəti aşağıdır, şifrələməsi və geniş mətn dəstəyi yoxdur. |
| **Şin İzolyasiya Modulu** | Aparat Mühafizəsi | RS-485 xəttinə ardıcıl qoşulan və qısa qapanma baş verdikdə nasaz xətt seqmentini avtomatik ayıran daxili qoruyucu modul. |
| **Xətt Təkrarlayıcısı** | Siqnal Gücləndirilməsi | Serial RS-485 elektrik siqnallarını gücləndirərək və zamanlamanı yeniləyərək şin məsafəsini növbəti 1,200 m-ə qədər uzadan cihaz (repeater). |
| **EOLR** | Dövrə Nəzarəti | End-of-Line Resistor (Xətt Sonu Rezistoru); zona naqillərinin bütövlüyünü (qırılma və ya sabotaj məqsədli qısa qapanma) fasiləsiz yoxlamaq üçün xəttin sonuna qoyulan rezistor. |
| **ONVIF Profile S** | Video İnteqrasiya Standartı | Şəbəkə kameralarının PTZ hərəkətlərini idarə etmək və siqnalizasiya panelindən gələn əmrlərlə video qeydi başlatmaq üçün istifadə olunan açıq qlobal IP standartı. |
| **Modbus-TCP** | Sənaye İnterfeys Protokolu | Ethernet təbəqəsi üzərində işləyən sənaye protokolu; təhlükəsizlik panelindəki zona və xəta məlumatlarının SCADA və BMS sistemləri tərəfindən oxunmasını təmin edir. |
| **İki-kanallı kommunikasiya modulu** | Rabitə Aparatı | Eyni vaxtda həm daxili şəbəkə (LAN), həm də daxili mobil (4G LTE) kanallarını nəzarətdə saxlayan və əsas xətt kəsildikdə avtomatik ehtiyata keçən rabitə modulu. |
| **VFD** | EMI Mənbəyi | Variable Frequency Drive (Tezlik Tənzimlənən İntiqal); sənaye mühərriklərinin sürətini tənzimləyən və ətrafa güclü keçirici elektromaqnit küy yayan cihaz. |
| **TCO** | Biznes Metriki | Total Cost of Ownership (Ümumi Sahiblik Dəyəri); sistemin 10 illik istismar müddətində satınalma, quraşdırma, genişləndirmə və texniki xidmət xərclərinin cəmini hesablayan ticari model. |
| **Xüsusi APN (Private APN)** | Şəbəkə Tənzimlənməsi | Mobil operator şəbəkəsi daxilində təhlükəsizlik panellərinin datalarını ümumi internetdən tam təcrid edərək birbaşa mərkəzə yönləndirən xüsusi daxili giriş nöqtəsi adı. |

---

Athenalarm, qlobal siqnalizasiya distribütorları, sistem inteqratorları və mərkəzi monitorinq stansiyası operatorları üçün ünvanlı siqnalizasiya panelləri, şəbəkə siqnalizasiya monitorinq infrastrukturu və OEM/ODM layihə inkişaf etdirmə xidmətləri təqdim edən peşəkar bir müdaxilə siqnalizasiya sistemləri istehsalçısı və sənaye təhlükəsizlik avadanlıqları tədarükçüsüdür. Geniş texniki sənədlər və quraşdırma bələdçiləri daxili mühəndislik qrupları üçün [Athenalarm texniki dəstək portalı](https://athenalarm.com/athenalarm-technical-documents/technical-support/) vasitəsilə təqdim olunur.
