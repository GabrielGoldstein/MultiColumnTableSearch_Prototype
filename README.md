# Prototype for Multi Column Table Search 

 

Author: Gabriel Goldstein  
Created: December 14, 2019  
Demo: [https://gabrielgoldstein.github.io/MultiColumnTableSearch_Prototype/Prototype_MultiColumnTableSearch.html](https://gabrielgoldstein.github.io/MultiColumnTableSearch_Prototype/Prototype_MultiColumnTableSearch.html)
 
 </br>
 
> ### Short Description: 
> - A prototype for a JavaScript search bar that looks thru all columns of a HTML table and we show all rows that match  

</br>

> ### Minimum Needed:
> - An input field with an "onekeyup" event handler
> - A table structure simple enough to easily pull a trArray and a tdArray
 
</br>

> ### Lengthy Explanation:
> - On each "onkeyup" event it calls the JavaScript function "myFunction()"
> - This function will pull all the tr tags into a trArray we then loop thru this array and pull all the td tags into a tdArray
> - We loop thru the tdArray and check if any td's match the users input using the JavaScript function ".indexOf()"
> - If a match is found we display that row and break out of the td loop since we only need to find one match to display a row
> - If a match is not found we display="hide" the tr 
 
