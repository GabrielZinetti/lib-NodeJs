# lib-NodeJs
Library that grabs links from an .md file in the directory and verifies if the links are validated
# 🛠️ Open and run the project
- Import "Chalk" lib to display in color in Terminal
- Import lib "fs" to manage the files

# :hammer: Project Features

- `$npm run cli`: Lists all links and titles in the desired file
- `$npm run cli:valida`: Lists the validated Links with their STATUS. If the link does not exist, "link not found" will be displayed.
- `STATUS da validação`: `100-199`: information answers | `200-299`: successful answers | `300-399`: redirects |`400-499`: customer errors | `500-599`: server errors
