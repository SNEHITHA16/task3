# task3
1)For the given JSON iterate over all for loops (for, for in, for of, forEach).
A)for
var obj = [ { person: "sneha", age: "2", company: "GUVI" }, { person: "pavan", age: "4", company: "Geek" }, { person: "sai", age: "6", company: "Network" }, ]; 
for(i=0;i<obj.length;i++){
    console.log(obj[i].person)
    console.log(obj[i].age)
    console.log(obj[i].company)
}

B)for in
for(i=0;i<obj.length;i++){
for(var property in obj[i]){
     console.log(`${property}: ${obj[i][property]}`);
}
}

C)for of
for(var elements of obj){
  console.log(elements.person)
    console.log(elements.age)
    console.log(elements.company)  
}

D)for each

obj.forEach(function(objects){
   console.log(objects.person)
    console.log(objects.age)
    console.log(objects.company)
})

2)RESUME IN JSON FORMAT
RESUME={
  "basics": {
    "name": "Snehitha Suram",
    "label": "Web Programmer",
    "email": "suramsnehitha16@gmail.com",
    "phone": 9346686123,
    "location": {
      "address": "7-57,Reddy colony",
      "postalCode": 50169,
      "city": "Jayashankar Bhupalpally",
      "countryCode": "India",
      "region": "Indian"
    }
},
"education": {
    "institution": "JNTUH",
    "url": "https://jntuh.com/",
    "area": "Software Development",
    "studyType": "Bachelor",
    "startDate": "2016-08-10",
    "endDate": "2020-09-22",
    "score": "6.8",
    "Course":’computer science engineering 
  },
"skills": {
    "name": "Web Development",
    "level": "Entry",
    "keywords": [
      "HTML",
      "CSS",
      "JavaScript",
“node”,
“Angular”,
“MangoDB”,
“express”,
“react”
    ]
  },
"interests": {
    "name": "Bussiness",
    "keywords": [
      "Stockmarket"
    ]
}
