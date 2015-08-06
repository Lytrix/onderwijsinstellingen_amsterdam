onderwijsinstellingen_amsterdam
=============================

Dutch schools provided by Dienst Uitvoering Onderwijs (DUO), www.duo.nl<br>

This python script retrieves the latest education locations from the Netherlands from a ZIP file and cleans the list with adding missing website and email addresses. This script only keeps the Amsterdam based locations. The zip file is from this website:<br> http://data.duo.nl/organisatie/open_onderwijsdata/gegevens_voor_gemeenten/Basisgegevens_instellingen/default.asp
<br>
<br>
<b>usage:</b> <br>
Deploy this repo to heroku by using this tutorial:<br>
https://devcenter.heroku.com/articles/getting-started-with-python#introduction
<br>
or deploy locally by using: <br>
pip install -r requirements.txt --allow-all-external
<br> <br>
This script uses an Amazon S3 storage solution to save the created csv file.
<br>

