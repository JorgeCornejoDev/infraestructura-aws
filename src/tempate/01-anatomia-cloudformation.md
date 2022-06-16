### Anatomía de un template en CloudFormation

// Template 

AWSTemplateFormatVersion: '2010-0909'
Description: Mi primer lamda en Platzi

Parameters:
    NombreLamda:
    Description: Nombre de la función lambda
    Type: String

RuntimeLambda:
    Description: Ingrese el runtime de la función lambda
    Type: String
    Default: python3.7
    AllowedValues: 
        - python3.7
        - python2.7
        - ruby2.5
        - nodejs8.10
        - java8
        - dotnetcore2.1

