# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
crear tablas
user (con devise)
    nombre
    apellido
    foto
    email
    telefono
    curriculo


oferta (scaffold)
    titulo
    detalles
    postulaciones 

postulaciones
    user:references
    oferta:references

rails devise user



