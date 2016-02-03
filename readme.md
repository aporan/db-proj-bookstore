## Overview

## Workflow
There are 3 main branches and all other branches should be a child of these

    development (branch to check functionality as per required, then merge to master)
    feature
    fixes

## Quick Start
Clone the repo and bundle

    git clone https://github.com/remmihsorp/sample-ordinary-bookstore.git
    cd sample-ordinary-bookstore
    bundle install

Setting up `database.yml` based on your needs. (Use the default settings if you're not sure what to change)

    cp config/database.yml.sample config/database.yml

    ** CHANGE THE DETAILS BEFORE PROCEEDING 

Set up database with postgres:

    rake db:create

    run the schema.sql in postgres

    rake db:schema:dump
    
    rake db:migrate

    rake db:seed

## Testing the app
No test is written right now. Work for the unforeseen future...
