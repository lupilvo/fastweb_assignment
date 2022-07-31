# Fastweb_Assignment

## Riproducibilità del notebook
Per la corretta esecuzione del notebook è consigliato utilizzare il kernel **fast_env** basato sull'omonimo ambiente virutale appositamente creato per questo assessment.

In alternativa basterà installare/avere a disposizione le librerie riportare nel file **requirements.txt**. (Non è garantita la compatibilità con versioni diverse di tali librerie, dunque è consigliato installare il kernel)

Per installare il kernel: 
1) Creare ed attivare l'ambiente virtuale **fast_env**:
   - Virtual Environment
     - Windows
       ```
	   virtualenv fast_env
       .\fast_env\Scripts\activate
	   pip install -r requirements.txt
       ```
      - Mac\Linux
       ```
	   virtualenv fast_env
       source /fast_env/bin/activate
	   pip install -r requirements.txt
       ```
   - Miniconda
     ```
	 conda create -n fast_env python=3.6
     conda activate env_to_create
	 conda install --file requirements.txt
     ```
2) Installare in locale il kernel per il notebook
  ```
  (fast_env) python -m ipykernel install --user --name=fast_env
  ```

A questo punto, dopo avere acceso il notebook sarà disponibile il kernel **fast_env**


PS: Per eliminare il kernel (una volta non più necessario) basta eseguire il comando `jupyter kernelspec uninstall fast_env`
