Käytetyt AI:t: Claude



**Alkupromt: I need you to help me make an app. It's a mobile app for personal use that is simply a recipe book. I want the recipes to mention the flavor profiles and i want to be able to search receipes based on these flavor profiles and their ingridients.**



Tästä syntyi ensimmäinen prototyyppi applikaatiolle. Ensimmäinen versio auttoi havainnollistamaan applikaation lopputulosta, ja kannattavaa formaattia. Claude teki ohjelman html kielellä. Tämä formaatti sopii hyvin käyttötarkoitukseeni, sillä applikaatio on tarkoitettu henkilökohtaiseen käyttöön. Applikaatiossa oli muutama asia minkä muutin vielä ennen kuin lähetin ensimmäisen version claudeen.



Ohjelma oli aluksi englanninkielinen. Halusin sen suomenkieliseksi. Halusin vielä, että kaikki reseptiin syötetyt ainesosat tallentuvat ja, että ohjelma "auto-suggestaa" aines osia kun alat kirjoittamaan niitä. Tämän muutoksen myötä reseptien haku ainesosilla onnistuu helpommin.



**Prompt: the language needs to be in finnish. And the ingredients need to be standardised, so If i add a new ingredient it should ask if i want to add a new ingredient to the app. I dont want it so that if i make a typo in a recipe it wont show up in the search, and i might use different names for some ingridients. Can you confirm you understand what i mean before you start building.**



Claude ymmärsi melko hyvin mitä tarkoitin, mutta korjasin muutaman ehdotuksen siltä. Ehdotukset olivat "Several names for one ingredient: Each ingredient has a main name and optional alternate names, for example "munakoisо" and "aubergiini". Typing either one finds the same ingredient, in recipes and in search." "Amounts: Should the amount stay free text (like "2 rkl" or "400 g"), or do you want separate amount and unit fields?".



**prompt: no need for several names for one ingredient. And yes the ingredients screen is a good idea. I also need the amounts to be scalable if i want to make more servings. To make this simpler we can just use grams, desiliters and float numbers for exmple 2 onions to 3.5 onions.**



Tämän jälkeen julkaisin ensimmäisen version git-hubiin.



Tällä hetkellä reseptit tallentuvat vain clauden, sekä selaimen muistiin. Tämä ei ole toivottua, sillä näissä on suuri riski, sille että reseptit poistuvat. Kysyin claudelta jos olisi mahdollista saada tallennettua reseptit omalle laitteelle. Se tarjosi muutaman vaihtoehdon joista varteenottavin oli "Backup to a file: I'd add an export button that saves all your recipes and ingredients as a file on your device, and an import button to load them back. You'd keep the synced version and still have a copy you control. The browser may ask you to confirm each save, and the file only updates when you export again". Claude lisäsi toiminnon.



Toiminto ei toiminut vielä toivotulla tavalla. Varmuuskopion vienti toimi ainoastaan clauden muistin kautta. Tämä muutettiin siten, että se toimii myös standalone versiossa.

