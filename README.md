# mongodb-queryPractice
# db.queryPractice.find() 
<img width="403" alt="dbquery1" src="https://user-images.githubusercontent.com/96439384/206911011-1a720c77-8715-4398-b396-6c6a596219df.png">

# db.queryPractice.find({gender:"Male"})
<img width="453" alt="dbquery2" src="https://user-images.githubusercontent.com/96439384/206911129-f8f58980-bbf1-413e-95d3-2a853dadf341.png">

#  db.queryPractice.find({gender:{$in:["Male","Female"]}})
<img width="429" alt="dbquery3" src="https://user-images.githubusercontent.com/96439384/206911164-ae7e56b9-7e65-42e8-9def-ac2158f0e04c.png">

# db.queryPractice.find({gender:"Male",id:{$lt:10}})
<img width="397" alt="dbquery4" src="https://user-images.githubusercontent.com/96439384/206911202-58ad361b-9f0a-4d5e-96cf-9cb4505a9c8c.png">

# db.queryPractice.find({$or:[{gender:"Male"},{id:{$lt:10}}]})
<img width="409" alt="dbquery5" src="https://user-images.githubusercontent.com/96439384/206911233-82377bb7-16cd-4df0-94bf-87af5b381780.png">

# db.queryPractice.find({gender:"Male",$or:[{id:{$lt:10}},{first_name: /^A/}]})
<img width="487" alt="dbquery6" src="https://user-images.githubusercontent.com/96439384/206911277-977be2c4-7634-4d8b-8d7a-58d42f8e037d.png">

# db.practice.find({size:{h:14,w:21,uom:"cm"}})
<img width="365" alt="dbquery7" src="https://user-images.githubusercontent.com/96439384/206911485-6b347710-412e-48ed-82c4-d1b6629b177d.png">

#  db.practice.find({"size.uom":"in"})
<img width="351" alt="dbquery8" src="https://user-images.githubusercontent.com/96439384/206911515-db64a085-a546-4b83-b25f-7ede87868c94.png">

# db.practice.find({"size.h":{$lt:15}})
<img width="415" alt="dbquery9" src="https://user-images.githubusercontent.com/96439384/206911553-612d7239-0f51-45f7-a88d-cf3d90caae0c.png">

# db.practice.find({"size.h":{$lt:15},"size.uom":"in",status:"D"})
<img width="414" alt="dbquery10" src="https://user-images.githubusercontent.com/96439384/206911604-ee3f00e1-89cb-499c-9ae7-9f0a986a8ca1.png">
