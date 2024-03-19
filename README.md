# PokéCalc

PokéCalc is an application that allows users to lookup information on a given Gen1 Pokémon. They can also calculate the stats of a desired Pokémon based on a variety of criteria that they are required to enter. This is a project I created for a Java class at my university.

<p align="center">
System Flow Diagram: <br/>
<img src="https://i.imgur.com/vFXedhK.png" height="80%" width="80%" alt="System Flow Diagram"/>
<br />
Pokédex: <br/>
<img src="https://i.imgur.com/lhhydKK.png" height="80%" width="80%" alt="Pokédex"/>
<br />
</p>

PokéCalc works using an input > process > output format by first reading from Pokemon.mdb when the program starts. All Pokémon data is stored in an object type Pokémon, which holds the necessary information of a Pokémon. Each Pokémon  is then held in an ArrayList which is the primary method of data access from that point. After the database is accessed, a menu is displayed for the user. They are prompted to press one of three buttons: Pokédex, Stat Calculator, or Quit. When Poké or Stat Calculator are selected, a window of Dex or StatCalc instance will be displayed to the user while the main menu is still active.
