# Istruzioni

## Autori
* Gabriele Carrara: 814720;
* Paolo Crotti: 820933;
* Simone Tufano: 816984.

## Cartelle:
* Image_Classification: 
	+ Cartella Notebook con file Score_blur.ipynb in cui viene effettuato lo score di nuove immagini, 
	Image_classification.ipynb con codice principale (parte di ML e Feature Engineering), Image_Classification_CNN.ipynb in cui si affronta il 
	problema con Convolutional Neural Network ed infine image_blurring.ipynb dove viene effettato 'Data Enrichment' del dataset e si prova nuovamente
	un'architettura convoluzionale;
	+ Demo con il modello migliore;
	+ map_classes.pkl, dizionario per contestualizzare le label della previsione;
	+ final_model_image_classification.zip, in cui è presente il modello che ottiene le performance migliori.

* Audio_Classification:
	+ Cartella Notebook con Audio_classification.ipynb, con il codice principale e Score_audio.ipynb in cui vengono effettuate le previsioni sui nuovi file;
	+ Demo con il modello migliore;
	+ Cartella nnet, in cui è presente il modello che ottiene le performance migliori.

* Image_Retrieval:
	+ Cartella notebook con il file Score_Retrieval.ipynb in cui viene effettuato lo score per le varie architetture provate, Image_Retrieval.ipynb con codice principale;
	+ Demo per i 4 modelli


* Dataset :
	[Image_Classification](  https://www.kaggle.com/toponowicz/spoken-language-identification).
	[Audio_Classification](https://www.kaggle.com/kwentar/blur-dataset).
	[Image_Retrieval](http://skydrive.live.com/?cid=1e04f731c1dd71bc&id=1E04F731C1DD71BC!105).