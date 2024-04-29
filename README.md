Clone the repo ```git@github.com:Denes-cilwal/atlas-gorm-migration-versioning.git``` <br>
Install dependencies ```go mod download``` <br>
Populate the .env file using the .env.sample file <br>
Run server: ```go run main.go``` <br>

Install atlas: ```curl -sSf https://atlasgo.sh | sh ``` <br>
Generate migration file ```atlas migrate diff --env gorm``` <br>
Check migration status ```atlas migrate status --url "mysql://username:password@:port/dbname"``` <br>
Apply migration ```atlas migrate apply --url "mysql://username:password@:port/dbname"``` <br>
