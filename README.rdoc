## Valeriu Olariu 

# Rails Crypto Portofolio-Project

https://api.coinmarketcap.com/v1/ticker/

https://rubygems.org/gems/devise

https://rubygems.org/gems/bootstrap-sass

https://guides.rubyonrails.org/association_basics.html

Adding:

belongs_to
has_one
has_many


The difference between rake db:migrate and rake db:reset is pretty clear in my head. The thing which I don't understand is how rake db:schema:load different from the former two.

Just to be sure that I am on the same page:

rake db:migrate - Runs the migrations which haven't been run yet.
rake db:reset - Clears the database (presumably does a rake db:drop + rake db:create + rake db:migrate) and runs migration on a fresh database.

https://stackoverflow.com/questions/10301794/difference-between-rake-dbmigrate-dbreset-and-dbschemaload

rails g scaffold cryptos symbol:string user_id:integer:index cost_per:decimal amount_owner:decimal

https://stackoverflow.com/questions/7832770/how-to-get-certain-commit-from-github-project