# CASTOR..functionx..82

![CASTOR Logo](https://raw.githubusercontent.com/universish/CASTOR..functionx..82/refs/heads/main/CASTOR-LOGO.png)

# DİKKAT: BU PROJENİN CASTOR MOTORU'NUN ORİJİNAL GELİŞTİRİCİSİ İLE HİÇBİR BAĞI YOKTUR.
Bu uygulama, Universish Labs bünyesinde Saffet Yavuz (universish) tarafından geliştirilen CASTOR Scientific Calculator Motor altyapısı kullanılarak inşa edilmiştir. Ancak bu türev uygulamanın tasarımı, işleyişi, kod kalitesi, eksiklikleri (kantitesizlik) ve hatalarından tamamen bu projeyi yayınlayan kişi/kurum sorumludur. Universish Labs ve Saffet Yavuz, bu türev projenin kullanımıyla ilgili hiçbir yasal veya teknik sorumluluk kabul etmez.

# ATTENTION: THIS PROJECT HAS NO AFFILIATION WITH THE ORIGINAL DEVELOPER OF THE CASTOR ENGINE.
This application was built using the CASTOR Scientific Calculator Engine infrastructure developed by Saffet Yavuz (universish) at Universish Labs. However, the developer/publisher of the derivative project is solely responsible for the design, operation, code quality, errors, and deficiencies (shortcomings). Universish Labs and Saffet Yavuz assume no legal or technical liability regarding the use of this derivative project.

---

----

## CASTOR functionx 82

This project is a digital clone built on the open-source and extensible [CASTOR Scientific Calculator Engine](original_engine_repo_link_here), which simulates the operational logic of the Casio fx-82MS-2 model (S-V.P.A.M., 9-variable memory, STAT mode, etc.). It is developed using the Rust programming language with a high-performance, modular architecture.

### Features
* **Engine Infrastructure:** An extensible architecture based on CASTOR’s `calc-core`.
* **S-V.P.A.M. Parser:** Exact integration of the physical calculator’s operation priorities and implied multiplication rules.
* **Visual Front End:** Optimized dot-matrix and 7-segment display simulation using Slint.

### Installation and Usage
*(This section should include instructions on how to compile the project, Cargo commands, and requirements)*
```bash
cargo run --release
```

### Licensing and Usage Rights (Dual License)

This project (the Casio fx-82 engine and interface) is offered under a **Dual License** model, depending on the developer’s intended use. Users who copy or fork the code must choose one of the following two licenses:

1. **Universish Labs Libre General Protective License v1.0 (ULLGPL):**
If you wish to use the “CASTOR” brand, name (e.g., `CASTOR-calculator`), and logo while developing your project, **you must select this license.** This license legally requires you to include the above disclaimer in your project’s README file and to transfer project rights to the Original Developer in cases where the “CASTOR” brand reputation is harmed. For details, see the `LICENSE-ULLGPL.txt` file.
2. **PolyForm Noncommercial License 1.0.0:**
If you wish to use this engine in your personal, academic, or non-commercial hobby projects, you must select this license. If you select this license, you may not generate any commercial revenue from your project, and you **MAY NOT USE the name or logo “CASTOR” anywhere in your application or repository.** For details, see the `LICENSE-POLYFORM.txt` file.

*(For commercial usage rights, please contact Universish Labs directly.)*

----

## CASTOR functionx 82

Bu proje, açık kaynaklı ve genişletilebilir [CASTOR Scientific Calculator Engine](orijinal_motor_repo_linki_buraya) çekirdeği üzerine inşa edilmiş, Casio fx-82MS-2 modelinin çalışma mantığını (S-V.P.A.M., 9 değişkenli bellek, STAT modu vb.) simüle eden dijital bir klondur. Rust programlama dili kullanılarak yüksek performanslı ve modüler bir mimariyle geliştirilmektedir.

### Özellikler
* **Motor Altyapısı:** CASTOR `calc-core` üzerine kurulu genişletilebilir yapı.
* **S-V.P.A.M. Ayrıştırıcı:** Fiziksel hesap makinesindeki işlem öncelikleri ve örtük çarpma (implied multiplication) kurallarının birebir entegrasyonu.
* **Görsel Ön Yüz:** Slint kullanılarak optimize edilmiş nokta matris (dot-matrix) ve 7-segment ekran simülasyonu.

### Kurulum ve Kullanım
*(Bu bölüme projenin nasıl derleneceği, Cargo komutları ve gereksinimleri eklenmelidir)*
```bash
cargo run --release
```

### Lisanslama ve Kullanım Hakları (Dual License)

Bu proje (Casio fx-82 motoru ve arayüzü), geliştiricilerin kullanım amaçlarına göre **Çifte Lisans (Dual License)** modeliyle sunulmaktadır. Kodu kopyalayan veya çatallayan (fork) kullanıcılar aşağıdaki iki lisanstan birini seçmek zorundadır:

1. **Universish Labs Libre General Protective License v1.0 (ULLGPL):**
Eğer projenizi geliştirirken "CASTOR" markasını, ismini (örneğin: `CASTOR-hesap-makinesi`) ve logosunu kullanmak istiyorsanız **bu lisansı seçmek zorundasınız.** Bu lisans, projenizin README dosyasında yukarıdaki sorumluluk reddi metnini bulundurmanızı ve "CASTOR" marka itibarını zedeleyici durumlarda proje haklarını Orijinal Geliştirici'ye devretmenizi yasal olarak şart koşar. Ayrıntılar için `LICENSE-ULLGPL.txt` dosyasına bakınız.
2. **PolyForm Noncommercial License 1.0.0:**
Eğer bu motoru kişisel, akademik veya kâr amacı gütmeyen hobi projelerinizde kullanmak istiyorsanız bu lisansı seçmelisiniz. Bu lisansı seçtiğiniz takdirde projenizden hiçbir şekilde ticari gelir elde edemezsiniz ve uygulamanızın/deponuzun hiçbir yerinde **"CASTOR" ismini veya logosunu KULLANAMAZSINIZ.** Ayrıntılar için `LICENSE-POLYFORM.txt` dosyasına bakınız.

*(Ticari kullanım hakları için doğrudan Universish Labs ile iletişime geçilmelidir.)*


## Licensing (fx82-engine)
This Casio simulation engine (fx82-engine) is provided under a **Dual License**.

1. **PolyForm Noncommercial License 1.0.0:** Select this license to use this engine for personal, academic, or non-commercial hobby projects. *Condition:* You may not engage in any commercial activity, and you **may not** use the “CASTOR” name or logo in your project.
2. **ULLGPL v1.0:** Select this license if you wish to develop an official CASTOR derivative using this engine. This choice legally binds you to the rules outlined in the `TRADEMARK.md` file (Extensive Disclaimer, Quality Control, and, when necessary, repository/rights transfer).

*(Note: If you wish to use this engine in a commercial product and also wish to be exempt from PolyForm’s restrictions, you must enter into a separate Commercial License agreement with Universish Labs.)*


## Lisanslama (fx82-engine)
Bu Casio simülasyon motoru (fx82-engine), **Çifte Lisans (Dual License)** ile sunulmaktadır. 

1. **PolyForm Noncommercial License 1.0.0:** Bu motoru kişisel, akademik veya kâr amacı gütmeyen hobi projelerinizde kullanmak için bu lisansı seçin. *Şart:* Hiçbir şekilde ticari faaliyette bulunamazsınız ve "CASTOR" ismini/logosunu projenizde **kullanamazsınız.**
2. **ULLGPL v1.0:** Bu motor ile resmi bir CASTOR türevi geliştirmek istiyorsanız bu lisansı seçmelisiniz. Bu seçim, sizi `TRADEMARK.md` dosyasındaki kurallara (Büyük Sorumluluk Reddi metni, Kalite kontrolü ve gerektiğinde depo/hak devri) yasal olarak mecbur kılar.

*(Not: Bu motoru hem ticari bir üründe kullanmak hem de PolyForm'un kısıtlamalarından kurtulmak istiyorsanız, Universish Labs ile özel bir Ticari Lisans (Commercial License) anlaşması yapmanız gerekmektedir.)*
