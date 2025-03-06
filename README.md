# BigData

I file contenuti nella repository sono 2 notebook e 3 file binari.
Per far funzionare i notebook senza ricreare i samples da zero, basta creare una cartella chiamata "audiozzi" come sottocartella di MyDrive (/content/drive/MyDrive/audiozzi) e inserirci i 3 file binari da cui poi estrarre i samples già assemblati.

Come già spiegano un po' i nomi dei file:

- FullSamplesTest.ipynb -> Notebook in cui sono stati creati e testati i samples completi (Librosa + Parselmouth + TF-IDF)
- LibrosaParselmouthVStf_idf.ipynb -> Notebook in cui sono stati creati e confrontati i samples "Librosa + Parselmouth" e quelli TF-IDF
- samplesCompleti.pkl -> File binario che contiene i samples completi di tutte le feature (Librosa + Parselmouth + TF-IDF)
- samplesSoloLibrosaParselmouth.pkl -> File binario che contiene i samples con solo le feature estratte dagli audio (Librosa + Parselmouth)
- samplesSoloTFIDF.pkl -> File binario che contiene i samples con solo le feature estratte dalle trascrizioni (TF-IDF)

Se si vuole testare anche il processo di creazione samples, è necessario avere nella cartella audiozzi anche:

- I file audio .mp3, assicurandosi che quelli urgenti terminino con u.mp3
- Il file Trascrizioni.txt, così formattato:
  nomeFile1.mp3
  trascrizione1

  nomeFile2.mp3
  trascrizione2
