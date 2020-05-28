# reconsideringciceronianauthorship

RECONSIDERING AUTHORSHIP IN THE CICERONIAN CORPUS THROUGH COMPUTATIONAL AUTHORSHIP  ATTRIBUTION

The dataset contains training and test data used in the authorship attribution of the Ciceronian corpus. The data has been compiled and published in the Academy of Finland consortium PROPREAU, project number 293024.

Dataset authors:

Aleksi Vesanto: data collection, pre-processing and analysis

Raija Vainio: data selection, analysis and description

Reima Välimäki: meta-data description


Publications: 
Vainio, Raija, Reima Välimäki, Anni Hella, Marjo Kaartinen, Teemu Immonen, Aleksi Vesanto, and Filip Ginter. ‘Reconsidering Authorship in the Ciceronian Corpus through Computational Authorship Attribution’. Ciceroniana on Line 3, no. 1 (2019). https://doi.org/10.13135/2532-5353/3518.

Data description:

TEST DATA:

Commentariolum petitionis

De inventione

De optimo genere oratorum

Rhetorica ad C. Herennium


TRAIN DATA:

CORPUS OF CICERO'S TEXTS

Academica

Brutus

Cato maior de senectute

De divinatione

De domo sua

De fato

De finibus

De haruspicum responsis

De imperio Cn. Pompei

De lege agraria contra Rullum

De legibus

De natura deorum

De officiis

De oratore

De partitione oratoria

De provinciis consularibus

De re publica

Epistulae ad Atticum I–IV

Epistulae ad Atticum IX–XII

Epistulae ad Atticum V–VIII

Epistulae ad Atticum XIII–XVI

Epistulae ad Brutum

Epistulae ad familiares I–V

Epistulae ad familiares VI–XII

Epistulae ad familiares XIII–XVI

Epistulae ad Quintum fratrem

In Catilinam I-IV

In Pisonem

In Vatinium

In Verrem

Laelius de amicitia

Orator

Philippica

Post reditum in Quirites

Post reditum in senatu

Pro Archia

Pro Balbo

Pro Caecina

Pro Caelio

Pro Cluentio

Pro Cn. Plancio

Pro Deiotaro

Pro Flacco

Pro Fonteio

Pro Ligario

Pro Marcello

Pro Milone

Pro Murena

Pro Quinctio

Pro Rabirio perduellionis reo

Pro Rabirio Postumo

Pro Roscio Amerino

Pro Roscio comoedo

Pro Scauro

Pro Sestio

Pro Sulla

Topica

Tusculanae disputationes

OTHER AUTHORS AND WORKS (BACKGROUND CORPUS)

Ambrosius, De mysteriis

Ambrosius, Epistulae variae

Ammianus Marcellinus, Res gestae 

Anonymus1, De bello Alexandrino liber

Anonymus2, De bello Africo

Anonymus3, De bello Hispaniensi liber

Anonymus4, Historia Apollonii regis Tyri

Apuleius, De deo Socratis

Apuleius, De dogmate Platonis

Apuleius, De mundo

Apuleius, Florida

Apuleius, Metamorphoses

Arnobius, Adversus nationes

Augustinus, Confessiones

Augustinus, De civitate Dei

Augustinus, De trinitate

Augustus, Res gestae

Aulus Hirtius, De bello Gallico commentarius octavus

Aurelius Victor, Liber de Caesaribus

Caesar, De bello civili

Caesar, De bello Gallico

Celsus, De medicina 

Columella, De arboribus

Columella, De re rustica

Cornelius Nepos, Liber de excellentibus ducibus exterarum gentium

Cornelius Nepos, Liber de Latinis historicis

Curtius Rufus, Historiarum Alexandri Magni libri

Egeria, Itinerarium

Eutropius, Breviarium historiae Romanae

Florus, Epitome de T. Livio

Gaius, Institutionum commentarii quattuor

Hyginus, De astronomia libri

Hyginus, Fabulae

Hyginus, De munitionibus castrorum

Iunianus Iustinus, Historiarum Philippicarum libri XLIV

Livius, Ab urbe condita

Minucius Felix, Octavius

Plinius maior, Naturalis historia

Plinius minor, Epistularum libri decem

Plinius minor, Panegyricus

Pomponius Mela, De chorographia

Pseudo-Aurelius Victor, Epitome de Caesaribus

Pseudo-Aurelius Victor, Liber de viris illustribus urbis Romae

Pseudo-Tertullianus, Spuria

Quintilianus, Declamationes maiores

Quintilianus, Institutio oratoria

Rutilius Lupus, De figuris sententiarum et elocutionis

Sallustius, Bellum Iugurthinum

Sallustius, De Catilinae coniuratione

Seneca minor, De beneficiis

Seneca minor, De consolatione

Seneca minor, De ira

Seneca minor, Dialogi

Seneca minor, Epistulae morales ad Lucilium

Seneca minor, Quaestiones naturales

Sextus Pomponius, Liber singularis enchiridii

Suetonius, De vitis Caesarum

Tacitus, Agricola

Tacitus, Annales

Tacitus, Dialogus de oratoribus

Tacitus, Germania

Tacitus, Historiae

Tertullianus, Ad martyres

Tertullianus, Ad nationes

Tertullianus, Ad Scapulam

Tertullianus, Ad uxorem 

Tertullianus, Adversus Hermogenem

Tertullianus, Adversus Iudaeos

Tertullianus, Adversus Marcionem

Tertullianus, Adversus Praxean

Tertullianus, Adversus Valentinianos

Tertullianus, Apologeticum

Tertullianus, De anima

Tertullianus, De baptismo

Tertullianus, De carne Christi

Tertullianus, De corona militis

Tertullianus, De cultu feminarum

Tertullianus, De exhortatione castitatis

Tertullianus, De fuga in persecutione

Tertullianus, De idololatria

Tertullianus, De ieiunio

Tertullianus, De monogamia

Tertullianus, De oratione

Tertullianus, De paenitentia

Tertullianus, De pallio

Tertullianus, De patientia

Tertullianus, De praescriptione haereticorum

Tertullianus, De pudicitia

Tertullianus, De resurrectione carnis

Tertullianus, De spectaculis

Tertullianus, De testimonio animae

Tertullianus, De virginibus velandis

Tertullianus, Liber Scorpiace

Valerius Maximus, Factorum et dictorum memorabilium libri

Varro, Rerum rusticarum libri

Vegetius, Epitoma rei militaris

Velleius Paterculus, Historiae Romanae

Vitruvius, De architectura

The Latin texts have been collected from public domain sources, mostly from The Latin Library (http://www.thelatinlibrary.com;), partly Bibliotheca Augustana (https://www.hs-augsburg.de/~harsch/a_chron.html).


DATA PREPROCESSING
Texts were cleared of punctuation because. When running classifications with SVM, the texts were also lower cased and all one-character long tokens were removed. 

DATA FORMAT
The data is shared as a single JSON file, compressed inside a gzipped tar file. 
The JSON file contains a nested dictionary, which groups all works per author.
The texts themselves are fully parsed and distributed in CoNLL-U format. (https://universaldependencies.org/format.html).
That is, every line corresponds to a single word in the original text and contains the parsed information for it (form, pos-tag, morphological features etc.).

Related code: https://github.com/avjves/AuthAttHelper


