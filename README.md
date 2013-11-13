# Practica9

TODO: 

Considere el desarrollo de una aplicación que contemple la creación de Matrices. Se ha de utilizar una representación para matrices densas y otra diferente para matrices dispersas. Una matriz se considerará dispersa si tiene más de un 60% de ceros. Se ha de establecer una relación de herencia entre las clases que se utilicen para su representación. Las operaciones básicas con matrices son diferentes en cada caso.


## Installation

Add this line to your application's Gemfile:

    gem 'Practica9'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install Practica9

## Usage

TODO: Write usage instructions here

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Implementación


Existe una clase Matriz:

Esta clase base contendrá las funciones basicas de operaciones y la funcion de mostrar_Matriz como cargar_Matriz

La clases MDensa y MDispersa:

Cada una contendrán todas las operaciones básicas implementadas, ya que son diferentes, salvo mostrar matriz, que sera la misma para ambas, la cual está en la clase base.
