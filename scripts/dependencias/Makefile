install-symfony-demo: ## install the demo in your project
	docker exec -i project_geekhubs_php_1 symfony new --demo --dir=/var/www/symfony
install-orm: ## install dependencies for database connection
	docker exec -i project_geekhubs_php_1 composer require symfony/orm-pack
install-maker: ## install dependencies for database connection
	docker exec -i project_geekhubs_php_1  composer require --dev symfony/maker-bundle

install-database: ## install database
	docker exec -i project_geekhubs_php_1 bin/console doctrine:database:create 
install-schema: ## install schema
	docker exec -i project_geekhubs_php_1 bin/console doctrine:schema:create
install-fixtures: ## install fixtures
	docker exec -i project_geekhubs_php_1 bin/console doctrine:fixtures:load
