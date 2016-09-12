# MAL-REST-API

<h2>MyAnimeList REST micro-API </h2>

It allows you to get information about an anime that the orginal <a href="https://myanimelist.net/modules.php?go=api">MAL-API </a> doesn't provide. </br>
This provide a very basic information: name ,score ,scoredby ,genre ,status ,pic ,id .  You can navigate the MAL page to get an extra information that you want. 

Set-up: </br>
1- Get Spring Framework: </br>
https://spring.io/tools </br>
2-Clone or downlowd this repository </br>
3- Go to File>Import>Gradle_Gradle Project>Browse to the repository > Bulid Model > Finish </br>
4- Go to MALAPIController Class and add the authorization header in sendGet method.</br>
5- Right click at class Application > Run As > Java Application 
    </br> </br>
    
    
    
    
Open this URL: </br>
http://localhost:8080/getMAL/Name_of_the_anime </br>

When you request for "Naruto" You will get : </br>
 <p>
{</br>
  "name": "Naruto",</br>
  "score": 7.8,</br>
  "scoredby": "434,766",</br>
  "genre": "Action,Comedy,Martial Arts,Shounen,Super Power",</br>
  "status": "Finished Airing",</br>
  "pic": "https://myanimelist.cdn-dena.com/images/anime/13/17405.jpg",</br>
  "id": "20"</br>
}  </p>