# Github_Profile_Finder

getUser(searchValue): This function retrieves GitHub user data based on the searchValue, which is either a specific username or undefined. It constructs the API URL accordingly. If searchValue is undefined, it fetches data for all GitHub users and displays them as cards. If searchValue is defined, it fetches data for the specific user and displays their information in a card. The function handles cases where the user is not found.
Event Listeners:

searchButton.addEventListener "click": This event listener is triggered when the "Search" button is clicked. It gets the searchValue from the searchBar input and calls getUser(searchValue) to fetch and display the user's information.
getAllUsers.addEventListener "click" : This event listener is triggered when the "Get All Users" button is clicked. It clears the cardContainer and calls getUser() without any arguments to fetch and display information for all GitHub users.
Initial Call: The getUser() function is called initially without any arguments, so it fetches and displays information for all GitHub users by default when the page loads.
this code allows users to search for GitHub profiles by username and view the profiles as cards with their avatars, usernames, and links to their GitHub pages. It also provides a button to retrieve and display information for all GitHub users. The data is fetched from the GitHub API using the fetch() function and displayed dynamically in the web page's HTML.
