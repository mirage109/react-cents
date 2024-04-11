# Avvio del progetto React-Cents

Questo progetto consiste in due parti: il backend e il frontend. Il backend è realizzato con Express.js, mentre il frontend utilizza React con TypeScript e Tailwind CSS.

## Avvio del backend

1. Assicurati di essere nella cartella `backend`:

   ```sh
   cd backend
   ```

2. Installa le dipendenze eseguendo il comando:

   ```sh
   npm install
   ```

3. Avvia il server eseguendo il comando:

   ```sh
   npm start
   ```

## Avvio del frontend

1.  Assicurati di avere il backend già avviato.

2.  Aggiungi il sottomodulo frontend eseguendo il seguente comando:

    ````sh
    git submodule add https://github.com/mirage109/cents-front frontend
     ```

3.  Passa alla cartella frontend.

    ```sh
    cd frontend
    ```

4.  Installa le dipendenze eseguendo il comando:

    ```sh
    npm install
    ```

5.  Avvia l'applicazione React eseguendo il comando:

        ```sh
        npm start
        ```

    L'applicazione verrà avviata in modalità sviluppo sulla porta 3000.

## Nota

Assicurati di avere Node.js e npm installati prima di avviare il progetto. Inoltre, assicurati che le porte 3300 e 3000 siano disponibili per l'utilizzo.

## Conclusione

Questo README.md fornisce tutte le istruzioni necessarie per avviare sia il backend che il frontend del progetto, inclusa l'aggiunta del sottomodulo frontend.
