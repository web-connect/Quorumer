# Quorumer
Originally by Justin Turner

Quorumer is a question and answer framework to the style of Stack Overflow.
It's goals are to be massive scalable, massively usable, and massively extendable.

## Requirements
* Rails 3.1.1
* ruby >= 1.8.7
* Java JRE 1.6 (If running Cassandra Locally)

## Installation
* Clone Project
* run `bundle install`
* run `cassandra_helper cassandra`. This will take a while. Eventually it will run cassandra. control+c to get out of it when it is done.
* run `cassandra_helper cassandra:start` to daemonize
* run `thin start`
* Visit http://localhost:3000

## License
Quorumer is released under the MIT license.
