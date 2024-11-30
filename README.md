To start your mongo shell type the following command :

mongosh

To verified or  see exists database use the following command on CMD :

show dbs 

To create database type :

use Coderibe

To Create collections named Facilitators, Trainees and Projects use the following commands : 

db.createCollection("Facilitators")
db.createCollection("Trainees")
db.createCollection("Projects")

To see collections type the following command :

show collections

To use or see data from a specific collection type the following command :

db.Facilitators.Find()

db.Trainees.Find()

db.Projects.Find()

To insert a document INTO Facilitators collection type the following command :

db.Facilitators.insertOne({name:"KB", location:"kimberley", course:"backed development"})

To insert a document INTO Trainees collection type the following command :

db.Trainees.insertOne({name:"Rethabile", location:"kimberley",facilitator:"KB"})

To insert a document INTO Projects collection type the following command :

db.Projects.insertOne({name:"Rethabile", course:"backend development", lesson:"mongodb commands"})