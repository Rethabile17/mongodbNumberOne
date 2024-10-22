To start your mongo shell type the following command :

mongosh

To create database type :

use Coderibe

To Create collections named Facilitators, Trainees and Projects use the following commands : 

db.createCollecttion(" Facilitators")
db.createCollecttion("  Trainees")
db.createCollecttion(" Projects")

To insert a document INTO Facilitators collection type the following command :

db.Facilitators.insertOne(Name:"KB", Location:"kimberley", Course:"backed development")

To insert a document INTO Trainees collection type the following command :

db.Trainees.insertOne(Name:"Rethabile", Location:"kimberley",Facilitator:"KB")

To insert a document INTO Projects collection type the following command :

db.Projects.insertOne(Name:"Rethabile", Course:backend development, Lesson:"mongodb commands")