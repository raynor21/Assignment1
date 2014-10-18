Assignment1
===========

Cash register and Address book
var bob = {
    firstName: "Bob",
    lastName: "Jones",
    phoneNumber: "(650) 777-7777",
    email: "bob.jones@example.com"
};

var mary = {
    firstName: "Mary",
    lastName: "Johnson",
    phoneNumber: "(650) 888-8888",
    email: "mary.johnson@example.com"
};

var contacts = [bob, mary];

function printPerson(person) {
    console.log(person.firstName + " " + person.lastName);
}

function list() {
	var contactsLength = contacts.length;
	for (var i = 0; i < contactsLength; i++) {
		printPerson(contacts[i]);
	}
}

/*Create a search function
then call it passing "Jones"*/
function search(lastName){
contactslength = contacts.length;
for (var a = 0 ; a < contacts.length ; a++){
if(contacts[a].lastName = lastName){
printPerson(contacts[a])}
}
}
search("Jones")
var bob = {
firstName: "Bob",
lastName: "Jones",
phoneNumber: "(650) 777-7777",
email: "bob.jones@example.com"
};

var mary = {
firstName: "Mary",
lastName: "Johnson",
phoneNumber: "(650) 888-8888",
email: "mary.johnson@example.com"
};
var tasnim={
firstName: "example",
lastName: "example",
phoneNumber: "example",
email: "example"
};
var add=function(firstName,lastName, phoneNumber,email){
tasnim={
firstName:firstName ,
lastName:lastName ,
phoneNumber:phoneNumber ,
email:email 
};
};

add("Tasnim","Rahman","(870) 768768","tasnim.bd10@gmail.com");

var contacts = [bob, mary,tasnim];

function printPerson(person) {
console.log(person.firstName + " " + person.lastName);
}

function list() {
var contactsLength = contacts.length;
for (var i = 0; i < contactsLength; i++) {
printPerson(contacts[i]);
}
}
list();
var search=function(lastName){
contactsLength=contacts.length;
for (var i = 0; i < contactsLength; i++) {
if(contacts[i].lastName===lastName){
printPerson(contacts[i]);
}
}
};
