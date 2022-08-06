Customized GrphQL

Update composer.json and add a repository:
"repositories":[ { "type": "vcs", "url": "git@github.com:Akses-Digital-Indonesia/gql-api.git" } ]

Create an SSH Key on the machine (local and deployment server) on which you want to install the package.

Now just composer require or composer install the package as usual.
