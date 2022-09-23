db.books.insertMany([{title:"", description:"", authors:""},{title:"", description:"", authors:""}])
db.books.find( { title: "" } )
db.books.updateOne({id : "" }, {$set: {description: "", authors: ""}})
