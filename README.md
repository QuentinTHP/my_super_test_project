# my_super_test_project



installer Gem:
$ gem install rspec

Quand tu utilises rspec, tous tes fichiers de test devront finir par _spec.rb. C'est une convention.

$ rspec --init


faire test :
$ rspec



Les lignes de base d'un programme de test en Rspec sont :

require_relative '***' pour faire appel au programme testé (sinon ses méthodes ne sont pas accessibles par le programme de test

describe "***" do (...) end pour introduire un groupe de test, généralement axé sur une méthode donnée

it "***" do (...) end pour introduire un test précis au sein de ce groupe, généralement axé sur une fonctionnalité donnée

expect(lmethode_ou_variable_ou_autre).to eq(resultat_attendu) pour faire le test qu'une méthode ou variable ou autre donne le résultat attendu