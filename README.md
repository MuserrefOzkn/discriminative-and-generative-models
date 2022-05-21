# discriminative-and-generative-models
Generative model: Yeni veri örnekleri üreten bir istatistiksel modeller sınıfıdır. Bu modeller denetimsiz makine öğreniminde olasılık ve olasılık tahmini, veri noktalarını modelleme ve bu olasılıkları kullanarak sınıflar arasında ayrım yapma gibi görevleri gerçekleştirmek için kullanılır. Generative modeller, ortak olasılığı bulmak için Bayes teoremine dayanır. Aykırı değerlerin varlığı bu modelleri büyük ölçüde etkiler. Generative model türleri: Latent Dirichlet Allocation (LDA), Bayesian Network, Hidden Markov model, Autoregressive model, Generative adversarial network

Discriminative model: Gözetimli öğrenme modellerinde kullanılır. Bir veri setindeki sınıflar ya da etiketler arasındaki sınırları öğrenir. Asıl amacı bir sınıfı diğerinden ayırmaktır. Discriminative modeller koşullu olasılığa dayalı tahmin yapar ve sınıflandırma ya da regresyon için kullanılır. Discriminative model türleri : Random forest, lojistik regresyon, support vector machine, decision tree 

Discriminative edici bir makine öğrenimi, koşullu olasılık P'yi (Y | X) en üst düzeye çıkaran parametreleri öğrenerek bir modeli eğitir, ancak Generative bir model, ortak olasılık P'yi (X, Y) en üst düzeye çıkararak parametreleri öğrenir.

Generative bir model, veri noktalarının ortak olasılığını modelleme eğiliminde olacak ve olasılık tahminlerini ve maksimum olasılığı kullanarak yeni örnekler oluşturabilecek olsa da, Discriminative modeller koşullu olasılığı modelleyerek sınıfları ayırır ve veri noktası hakkında herhangi bir varsayımda bulunmaz.
Generative bir modelin verilerin nasıl üretildiğini açıklamaya odaklanırken, Discriminative bir modelin verilerin etiketlerini tahmin etmeye odaklanır.
