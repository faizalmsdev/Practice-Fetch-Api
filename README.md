# Practice-Fetch-Api
In this project it displays some datas teaken from api.<br>

<h2>Visit this to view the project <a href="https://faizalmsdev.github.io/Practice-Fetch-Api/">Click Here</a></h2>
<p>
  This code snippet sets up a web page with a table that displays coin data fetched from an API. Here's a breakdown of the code:

The coinTableBody, searchInput, sortMarketCapButton, and sortPercentageChangeButton variables are assigned references to DOM elements using getElementById.
An empty array coinData is declared to store the fetched data.
The code then fetches data from the Coingecko API using fetch and .then syntax. The response is converted to JSON format using response.json().
The fetched data is mapped to a new array format and assigned to coinData. Finally, the renderTable function is called with coinData as an argument.
The code also provides an alternative approach using async/await syntax. The fetchData function uses await to fetch the data and convert it to JSON. The data is then mapped and assigned to coinData, followed by calling renderTable.
An event listener is added to the searchInput element to filter the coinData based on the user's input. The filtered data is then passed to renderTable.
Event listeners are added to sortMarketCapButton and sortPercentageChangeButton to sort the coinData array based on the market cap and percentage change, respectively. The sorted data is then passed to renderTable.
The renderTable function clears the coinTableBody and populates it with table rows (tr) and cells (td) based on the provided data. Each cell is populated with corresponding data from the item object.
Overall, this code fetches coin data from an API, allows searching and sorting functionality, and dynamically renders the data in an HTML table on a web page.
</p>
