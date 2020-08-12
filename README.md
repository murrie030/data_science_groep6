# Onderzoek films
Voor de casusopdracht van het vak Data Science moet er een pipeline worden gemaakt, waarbij een toegewezen dataset wordt geanalyseerd. Dit data onderzoek is gebaseerd op de dataset over films en is opgezet door groep 6 van klas V2C. 

De dataset is toegewezen door de Hogeschool Utrecht en bevat onder andere:
* filmgegevens, waaronder: duur, genres, taal, land van herkomst, budget en opbrengst;
* likes op facebook voor regisseur, hoofdrolspelers, totale cast en de film zelf;
* score op IMDB en aantal reviews.

# Installaties
Voordat het onderzoek gerund kan worden, moeten er eerst een paar installaties worden uitgevoerd om gebruik te kunnen maken van de tools en verschillende libraries.

Installeer Anaconda (dit is de data science toolkit):
* https://www.anaconda.com/products/individual

**Let op:** *Voor Windows moet het installatiebestand als **administator** worden uitgevoerd. Kies bij de installatie voor **All Users** en plaats Anaconda niet in diepe mappen (voorkeur C: of D: schijf).*

Nu volgen de installaties van de libraries. Hiervoor gebruik je de command prompt.

Voor het gebruik van Holoviews:

1. `conda install -c pyviz holoviews bokeh`

Voor het gebruik van pafy:

2. `pip install pafy`

Voor het gebruik van youtube_dl

3. `pip install youtube_dl`

Voor het gebruik van ipywidgets:

4. `conda install -c conda-forge ipywidgets`

Voor het gebruik van graphviz:

5. Voeg graphviz aan je environment (**systeem**) variabele PATH. 

**Let op:** *(Afhankelijk van de locatie moet er een **bin** folder met de **dot.exe** bestand toegevoegd worden aan de PATH.
Zie https://stackoverflow.com/questions/36869258/how-to-use-graphviz-with-anaconda-spyder/36869259).*

6. `pip install graphviz`.


Ga nu naar de desbetreffende locatie van het project.

Run het project met:

`jupyter notebook`
