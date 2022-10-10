# test
composer require --dev phpunit/phpunit
composer require --dev symfony/phpunit-bridge
./vendor/bin/phpunit tests
composer require symfony/maker-bundle --dev
composer require orm

# php bin/console make:entity
# make an entity and make a test for that entity (Movie, MovieTest)

# pre-commit file has to have: #!/bin/sh
<!-- Rename ./git/hooks/pre-commit.sample to pre-commit


#!/bin/sh
#
if ./vendor/bin/phpunit; then
	echo "Tests passed"
else
	echo "Tests failed"
    exit 1
fi 
-->