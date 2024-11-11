# CI/CD Nedir?
CI/CD, Sürekli Entegrasyon (Continuous Integration) ve Sürekli Dağıtım (Continuous Delivery) veya Sürekli Yayınlama (Continuous Deployment) anlamına gelir. Bu, yazılım geliştirmede daha hızlı teslimat süreleri ve daha yüksek kaliteli yazılım sağlamak amacıyla geliştirme iş akışını iyileştirmeye yönelik bir dizi uygulama ve ilkedir.

### Sürekli Entegrasyon (CI):
CI, birden fazla katkıcının yaptığı kod değişikliklerinin otomatik olarak paylaşılan bir depoya entegre edilmesidir ve bu işlem günde birden fazla kez yapılır. Her değişiklik otomatik olarak derlenir, test edilir ve doğrulanır, bu da gelişim döngüsünün erken aşamalarında sorunları tanımlamaya yardımcı olur.

### Sürekli Dağıtım (CD):
CD, kodun dağıtıma hazırlanmasını sağlayan otomatikleştirilmiş bir süreçtir. Kodun her zaman dağıtıma hazır bir durumda olmasını ve her an üretime aktarılabilmesini garanti eder. Bu süreç, kaliteyi ve kararlılığı sağlamak için otomatik testler ve aşamalar içerir.

### Sürekli Yayınlama (CD):
CI/CD'nin daha ileri bir aşamasıdır. Burada, otomatik testlerden başarıyla geçen herhangi bir değişiklik, manuel müdahale olmadan üretime aktarılır. Bu yaklaşım, özelliklerin ve düzeltmelerin daha hızlı ve daha sık yayınlandığı çevik ve DevOps ortamlarında sıklıkla kullanılır.

[img1]: cicd.webp (CI/CD)
![img1]

----

# Neden CI/CD Kullanılır?
### Daha Hızlı Geliştirme Döngüsü:
Test ve dağıtım gibi tekrarlayan işlemleri otomatikleştirerek, CI/CD, geliştiricilerin kod yazmaya daha fazla odaklanmalarını ve manuel işlemlere daha az zaman harcamalarını sağlar. Bu da daha hızlı düzeltmeler ve daha hızlı özellik yayınları ile sonuçlanır.

### Geliştirilmiş Kod Kalitesi:
Otomatik testler, sorunların süreç boyunca erken aşamalarda tespit edilmesini sağlar. Geliştiriciler kodu sürekli entegre ettikçe, kodlarının performansına dair anında geri bildirim alırlar. Bu, daha kaliteli ve daha az sorunlu bir kodun üretime gitmesini sağlar.

### Azaltılmış İnsan Hatası:
Manuel işlemler, özellikle test ve dağıtımda, insan hatalarına yatkındır. Bu işlemleri otomatikleştirerek, CI/CD hataları azaltır ve daha stabil ve güvenilir bir iş akışı sağlar.

### Daha İyi İşbirliği:
CI ile geliştiriciler daha küçük ve sık değişiklikler yaparak işbirliğini kolaylaştırır ve entegrasyon çatışmalarını azaltır. Sürekli geri bildirim döngüsü, ekipteki herkesin değişikliklerden haberdar olmasını sağlar ve bu değişiklikler hızla entegre edilir.

### Daha Hızlı Pazara Çıkış:
Yayınlar daha sık ve otomatik olduğundan, CI/CD ekiplerin özellikleri ve iyileştirmeleri müşterilere daha hızlı sunmalarına yardımcı olur.

----

# CI/CD ve GitOps
GitOps, CI/CD ilkelerini altyapı yönetimine uygulayan bir operasyonel modeldir. GitOps'ta, yapılandırma ve altyapı bir Git deposunda saklanır ve depoda yapılan her değişiklik otomatik olarak altyapıya uygulanır. İşte CI/CD ile GitOps arasındaki farklar:

### CI/CD:
Yazılım yaşam döngüsüne odaklanır ve kod entegrasyonu, test ve dağıtım süreçlerini otomatikleştirir. Jenkins, GitLab CI ve CircleCI gibi CI/CD araçları, uygulamalar için derleme, test ve dağıtım süreçlerini otomatikleştirir.

### GitOps:
Operasyonel yaşam döngüsüne odaklanır. GitOps'ta, Git depoları altyapı yapılandırmasının doğruluğu için kaynak olarak kullanılır. GitOps ile operasyon ekipleri, Git kullanarak altyapı güncellemelerini otomatik olarak gerçekleştirebilir ve depodaki sistem durumunun canlı sistemle eşleşmesini sağlar.

### Ana Farklar:
CI/CD, yazılım dağıtımına odaklanır ve kodun hızla ve güvenilir bir şekilde üretime aktarılmasını sağlar.
GitOps, altyapı ve yapılandırma yönetimi ile ilgilidir ve Git, pipeline'lar ve sistem durumu yönetimi için merkezi nokta olarak kullanılır.

Özetle, CI/CD yazılım teslimi ile ilgili DevOps sürecinin temel bir parçasıdır, GitOps ise bu uygulamaları altyapı yönetimine genişletir ve Git'i operasyonlar ve uygulamalar için merkezi bir nokta haline getirir.

[img2]: cicd-gitops.webp (CI/CD)
![img2]

----

# CI/CD İçin Popüler Araçlar
CI/CD pipeline'larını uygulamak için birçok araç vardır. İşte en popüler olanlardan bazıları:

### Jenkins
Çeşitli teknolojilerle entegrasyon için eklentiler desteği sunan, kodun derlenmesi, test edilmesi ve dağıtılması için açık kaynaklı bir otomasyon sunucusudur.

### GitLab CI/CD
Bu araç, doğrudan GitLab depolarına entegre edilmiştir ve test, derleme ve dağıtım pipeline'larını otomatikleştirmek için kolay bir platform sağlar.

### CircleCI
Hız ve ölçeklenebilirliğe odaklanarak test ve dağıtımı otomatikleştiren bulut tabanlı bir CI/CD aracıdır. CircleCI, GitHub ve Bitbucket gibi sürüm kontrol sistemleriyle entegre olur.

### Travis CI
GitHub depolarında otomatik olarak kodu derleyip test eden, açık kaynak ve özel projeler için kolay kurulum sağlayan bulut tabanlı bir CI aracıdır.

### Azure DevOps
Microsoft'un, sürüm kontrolü, test ve sürüm yönetimi dahil olmak üzere kapsamlı bir CI/CD araç seti sunduğu bir üründür ve IDE'ler ve popüler servislerle entegrasyon desteği sağlar.

### GitHub Actions
GitHub'ın kendi CI/CD aracıdır, geliştiricilerin GitHub depoları içinde doğrudan pipeline'ları otomatikleştirmesine olanak tanır, pull request'ler ve birleştirmelerle entegre bir deneyim sunar.

### Bamboo
Atlassian tarafından geliştirilen ve Jira ve Bitbucket gibi diğer Atlassian ürünleriyle entegre olan bir otomasyon aracıdır.

### TeamCity
JetBrains'in güçlü bir CI/CD aracıdır, birden fazla sürüm kontrol sistemi, derleme aracı ve programlama dili ile entegrasyonu destekler.

### Argo CD
Kubernetes'te sürekli dağıtım için bir araçtır, GitOps ilkelerini takip eder ve kullanıcıların Git deposundan Kubernetes'e uygulama dağıtmasına olanak tanır.

### Spinnaker
Birden fazla bulut sağlayıcısında yazılım dağıtımını otomatikleştirmeye yardımcı olan açık kaynaklı bir sürekli dağıtım platformudur, Kubernetes, AWS ve diğer servisleri destekler.

Bu araçlar, derleme, test ve dağıtım süreçlerini otomatikleştirerek, sorunsuz ve hatasız yazılım teslimat iş akışlarını sağlar. Doğru CI/CD araçlarını kullanmak, yazılım kalitesini ve operasyonları önemli ölçüde iyileştirebilir, böylece organizasyonların müşterilerine daha hızlı değer sunmasına yardımcı olur.

----

[z01]: README.md
[z02]: README-az.md
[z03]: README-tr.md
[z04]: README-fa.md

[1.z01]: https://raw.githubusercontent.com/samadelmakchi/samadelmakchi/main/flag/en.svg (English)
[1.z02]: https://raw.githubusercontent.com/samadelmakchi/samadelmakchi/main/flag/az.svg (Azərbaycani)
[1.z03]: https://raw.githubusercontent.com/samadelmakchi/samadelmakchi/main/flag/tr.svg (Türkisch)
[1.z04]: https://raw.githubusercontent.com/samadelmakchi/samadelmakchi/main/flag/fa.svg (فارسی)

### Translate
[![1.z01]][z01] [![1.z04]][z04] [![1.z02]][z02] 
