# Papery, które przeczytałem

## A Mathematical Framework for Transformer Circuits (Elhage et al.)

Tutaj pokazany jest proces reverse-engineeringu sieci z zerową ilosć warstw atencji i pokazane jest że to jest tak naprawdę matrix factorization bigramu przewidywania kolejnego tokenu po danym tokenie, jedną warstwą atencji (pokazane że ta jedna warstwa atencji implementuje tzw. skip-tri-gram) i dwie warstwy atencji gdzie poprzez K-kompozycję działają tzw. głowy indukcyjne, które są w stanie odtwarzać sekwencję które pojawiły się wczesniej w sekwencji

## In-context Learning and Induction Heads

Tutaj jest przedstawione sześć argumentów, które uzasadniają to że w modelach o dowolnej wielkości i ilości warstw atencji, to głowy indukcyjnie odpowiadają za jak nie całość to większość in-context learningu

## [An informal note on some intuitions related to Mechanistic Interpretability by Chris Olah.](https://transformer-circuits.pub/2022/mech-interp-essay/index.html)

Tutaj była fajna analogia, która porównywała to jak bez uprzywilejowanej bazy feature'y są rozpraszane przez wszystkie elementy wektorów aktywacji, to jest tak jakby zamiast grupować zmienne w programie rozpraszać je poprzez wszystkie bity w pamięci utrudniałoby reverse-engineering programów binarnych

# Papery, które w przyłości warto byłoby przeczytać 

* **Language Models are Few-Shot Learners**
* **Grokking: Generalization beyond overfitting on small algorithmic datasets**
* **Reconciling modern machine-learning practice and the classical bias--variance trade-off**
* **Exact solutions to the nonlinear dynamics of learning in deep linear neural networks**
Convergent learning: Do different neural networks learn the same representations?
