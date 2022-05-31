# iris-biblio-tools
Tools to handle bibliography in IRIS


Da cambiare sono i dati di login IRIS in line 137

https://github.com/bortigno/iris-biblio-tools/blob/c2e802d3b01d1335f7e618be4605a7044ea01b4b/login-iris.py#L137


Un altra cosa da cambiare e' l'autore da cercare nell'author list in questa riga:

https://github.com/bortigno/iris-biblio-tools/blob/c2e802d3b01d1335f7e618be4605a7044ea01b4b/login-iris.py#L291

e qui
https://github.com/bortigno/iris-biblio-tools/blob/c2e802d3b01d1335f7e618be4605a7044ea01b4b/login-iris.py#L319

Se la stringa degli autori e' vuota (dipende da come lo importate) lo script la prende dal database DOI, pero' se anch'esso dovesse fallire potete decidere cosa scrivere in questa riga: 

https://github.com/bortigno/iris-biblio-tools/blob/c2e802d3b01d1335f7e618be4605a7044ea01b4b/login-iris.py#L257
