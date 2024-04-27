---
permalink: "/"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner.jpg
#excerpt: "Benvenuti sul nostro sito. Il centro Nascere e Rinascere pensato come un luogo"
#intro:
#  - excerpt: "Benvenuti sul nostro sito. Il centro Nascere e Rinascere pensato come un luogo"
feature_row:
  - image_path: /assets/images/gravidanza.jpg
    alt: "Gravidanza"
    title: "Gravidanza"
    excerpt: |-
      La gravidanza rappresenta un momento unico nella vita di una famiglia. È un periodo di grande trasformazione a 
      vari livelli. Per accompagnarvi in questo delicato cammino abbiamo pensato a diversi percorsi che vedono 
      coinvolte più figure professionali. 
    url: "/courses/parent_course_1/course_1_1"
    btn_label: "Per saperne di più clicca qui"
    btn_class: "btn--inverse"
feature_row-2:
    - image_path: /assets/images/postparto.jpg
      id: "row2"
      alt: "Post Parto"
      title: "Post Parto"
      excerpt: |-
        E’ il delicato momento in cui dobbiamo misurare la distanza che c’è tra il nostro immaginato e la realtà: il 
        bambino reale, il parto, il nuovo corpo.
        Molte dinamiche del passato possono riemergere.  Può rivelarsi un momento sereno, ma anche un momento faticoso 
        e difficile. Vi proponiamo quindi vari tipi di corsi di gruppo e percorsi individuali, che 
        vi forniranno strumenti utili  a vivere con serenità il vostro nuovo assetto personale e familiare.
      url: "/courses/parent_course_2/course_2_1"
      btn_label: "Per saperne di più clicca qui"
      btn_class: "btn--inverse"
feature_row-3:
  - image_path: /assets/images/luttoperinatale.jpg
    id: "row3"
    alt: "Lutto Perinatale"
    title: "Lutto Perinatale"
    excerpt: |-
      Perdere un figlio durante la gravidanza porta con sé una serie di emozioni e vissuti di grande dolore. 
      Con umiltà e consapevolezza che sia tra i momenti più difficili della vita di una persona, offriamo il nostro 
      aiuto con percorsi di sostegno e psicoterapia. 
    url: "/courses/parent_course_3/course_3_1"
    btn_label: "Per saperne di più clicca qui"
    btn_class: "btn--inverse"
feature_row-4:
  - image_path: /assets/images/pma.jpg
    alt: "Infertilità, Sterilità e PMA"
    title: "Infertilità, Sterilità e PMA"
    excerpt: |-
      Desiderare un figlio che non arriva può portare a un grosso sconvolgimento della nostra vita. Ci troveremo ad 
      affrontare momenti di difficoltà e a dover fare scelte spesso non facili. Sia che si tratti di un nodo da 
      sciogliere, sia che attivi dinamiche ataviche bisognose di cura e attenzione, potrebbe essere importante aprire 
      uno spazio di riflessione con un percorso intimo e accogliente. 
    url: "/courses/parent_course_4/course_4_1"
    btn_label: "Per saperne di più clicca qui"
    btn_class: "btn--inverse"
feature_row-5:
  - image_path: /assets/images/genitorialita.jpg
    id: "row2"
    alt: "Genitorialità"
    title: "Genitorialità"
    excerpt: |-
      Il cammino accanto ai propri figli è lungo una vita, si cambia e si cresce insieme attraversando momenti di gioia 
      e difficoltà. Quando avvertiamo ostacoli più grandi di noi possiamo intraprendere un percorso di sostegno che 
      tenga conto della situazione unica che noi e la nostra famiglia stiamo vivendo in quel preciso momento della vita.
    url: "/courses/parent_course_5/course_5_1"
    btn_label: "Per saperne di più clicca qui"
    btn_class: "btn--inverse"
feature_row-6:
  - image_path: /assets/images/psicoterapia.jpg
    id: "row3"
    alt: "Sostegno e Psicoretapia"
    title: "Sostegno e Psicoretapia"
    excerpt: |-
      Possono esserci nella vita momenti di particolare difficoltà, dove la sofferenza diventa troppo intensa e siamo 
      chiamati ad occuparcene. Altre volte ci troviamo ad affrontare momenti di grande cambiamento che richiedono una 
      riflessione più approfondita per comprendere quale sia la direzione da prendere. La psicoterapia a orientamento 
      psicoanalitico può essere d’aiuto in queste e molte altre situazioni, grazie a un lavoro introspettivo di analisi 
      e ricerca interiore, volto ad aumentare la consapevolezza e la conoscenza di sé. 
    url: "/courses/parent_course_6/course_6_1"
    btn_label: "Per saperne di più clicca qui"
    btn_class: "btn--inverse"
---

<div class="home-container">
    <p>
        Il centro Nascere e Rinascere è stato pensato come un luogo in cui poter trovare o ritrovare calma e serenità. 
        Uno spazio dedicato ad accogliere ogni storia, unica e straordinaria.
    </p>
    <p>
        Il nostro gruppo è formato da varie professioniste, tra cui: doula, psicologa psicoterapeuta, ostetrica, 
        consulente babywearing e IBCLC.
    </p>
    <p>Scopriamo insieme i nostri servizi. </p>
</div>
<div class="feature-row-container">
    {% include feature_row type="left" %}
    {% include feature_row id="feature_row-2" type="right" %}
    {% include feature_row id="feature_row-3" type="left" %}
    {% include feature_row id="feature_row-4" type="right" %}
    {% include feature_row id="feature_row-5" type="left" %}
    {% include feature_row id="feature_row-6" type="right" %}
</div>
