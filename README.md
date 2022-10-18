## Introduction

### Goal of the tutorial
This tutorial explains how to set up an instance of a Python web service on Render and deploy a flask app, using the flaskr Python package to create a minimal blogging platform with Auth, ___ and ___

### A blurb on Flask in the Python ecosystem and deploying Python to Render

## Bird's Eyy View of the Project
In addition to creating a web service, you will also see how to create an instance of FlasQLalchemy, deployed as a "private" ? service, where you will be able to store data as user records and blog posts are added. 

Alternatively (this might be too much too soon, but could point users in the direction of building a postgres database and recommend it as a more appropraite avenue for production ready app)

## Sample Deployment

Here is the example app deployed. (If we made one, could we make it wipe the database so people can't populate it with tomfoolery?)

Flask is ___link to official docs and github
Flaskr is ___ link to tutorial and github

Set up a monorepo for Flasqalchemy and flaskr? Or seperate repos with a blueprint?

Will flasqalchemy need disk space? WHat additional instruction or variables will need to be defined, if so?

Section on tests. Refer to pallets tutorial https://flask.palletsprojects.com/en/2.2.x/tutorial/layout/ test modules...maybe go over what tests are recommended

### Project Structure
Brief overview of gitignore?

### Setting Environment Variables
About environment variables
    FLASK_APP
    FLASK_ENV
    DATABASE_URL 

In development
(flask --app flaskr --debug run)

When deploying
(flask --app flaskr run)

Where does this happen? 
flask --app flaskr init-db (will this create an "instance" file and a flaskr.sqlite file or no? )

Disambiguate "Blueprint" https://flask.palletsprojects.com/en/2.2.x/api/#flask.Blueprint from Render's "Blueprints" https://render.com/docs/blueprint-spec
Also, someplace, I might need to disambiguate "render_template" https://flask.palletsprojects.com/en/2.2.x/api/?highlight=render#flask.render_template from our platform

### Managing Dependancies

Because this tutorial is meant to familiarize you with what elements you need to be familiar with in a flask app to deploy it to Render, may also want to take this as boilerplate to further experiment before creating a project from official Flask documentation. Some ideas to try: alter the layout, css, 

Where does the start command go in the flow of this setup?
