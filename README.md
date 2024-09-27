# Trello-API-Manual-Testing
This repository contains manual API testing for the Trello API, performed using Postman. The goal of this project is to validate various API endpoints for managing boards, lists, and cards within the Trello platform.

## Project Overview
The Trello API allows users to manage boards, lists, and cards, enabling functionality such as creating boards, moving cards between lists, and deleting items. Below are the APIs tested in this project:

https://api.trello.com/

- Get All Boards: Fetches all existing boards.
- Create a Board: Creates a new board.
- Get Single Board: Retrieves information about a specific board.
- Create TO DO List: Creates a new list within a board.
- Create Unique Name List: Creates a list with a unique name.
- Get All Lists from a Board: Retrieves all lists within a specific board.
- Create Card in TO DO List: Adds a new card to a TO DO list.
- Move Card to Unique Name List: Moves a card to a list with a unique name.
- Delete Card: Deletes a card.
- Delete Board: Deletes a board.
  
## Tested API Endpoints
The following endpoints were tested:

- GET /api/Boards: Get all boards.
- POST /api/Board: Create a new board.
- GET /api/Board/{id}: Get details of a specific board.
- POST /api/Board/{id}/List/ToDo: Create a TO DO list on a board.
- POST /api/Board/{id}/List/UniqueName: Create a list with a unique name.
- GET /api/Board/{id}/Lists: Get all lists from a board.
- POST /api/List/{listId}/Card: Create a new card in the TO DO list.
- PUT /api/List/{uniqueListId}/Card: Move a card to a list with a unique name.
- DELETE /api/Card/{id}: Delete a card.
- DELETE /api/Board/{id}: Delete a board.
  
## Tools Used
- Postman: For creating and running API test cases.
- GitHub: For version control and repository management.
  
## How to Use
1. Clone the repository:
  
git clone https://github.com/yourusername/Trello-API-Testing.git

2. Navigate to the project directory:

cd Trello-API-Testing

3. Run the test cases by following the test collection within the Postman workspace.

## License
This project is licensed under the MIT License.
