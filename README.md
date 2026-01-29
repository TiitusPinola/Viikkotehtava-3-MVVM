# Viikkotehtava-3-MVVM

## Kuvaus
Yksinkertainen Android-sovellus, jossa voit:
- Lisätä uusia tehtäviä
- Poistaa tehtäviä
- Merkitä tehtäviä tehdyksi tai tekemättömäksi
- Avata modal-ikkunan klikkaamalla tehtävää, jossa kuvausta voi hallinnoida

## MVVM 
MVVM (Model–View–ViewModel) on arkkitehtuurimalli, jossa sovellus jaetaan kolmeen osaan:
Model sisältää datan ja logiikan, View on käyttöliittymä (Compose-näkymät) ja ViewModel hoitaa sovelluksen tilan sekä yhdistää View’n ja Modelin.
MVVM on hyödyllinen Compose-sovelluksissa, koska käyttöliittymä pysyy yksinkertaisena, sovelluksen tila on ViewModelissa ja Compose pystyy päivittämään näkymän automaattisesti, kun tila muuttuu. Lisäksi ViewModel säilyy esimerkiksi näytön käännössä.

## StateFlow 
StateFlow on tapa hallita ja seurata sovelluksen tilaa.
StateFlowssa on aina ajankohtainen arvo, ja kun tämä arvo muuttuu, kaikki sitä seuraavat osat (kuten Compose-käyttöliittymä) saavat muutoksesta tiedon.
ViewModelissa tilaa muutetaan MutableStateFlowlla ja käyttöliittymä lukee tilan StateFlown kautta, jolloin UI päivittyy automaattisesti tilan muuttuessa.

## Teknologiat
- Kotlin
- Android Studio
- Jetpack Compose
- StateFlow

## Asennus ja ajaminen
1. Kloonaa projekti

2. Avaa Android Studiossa

3. Rakenna ja aja sovellus emulaattorissa tai laitteessa
