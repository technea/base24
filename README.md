# base24
every function
function truthCheck(collection, arr) {
  return collection.every(item=>item["isBot"])
}

truthCheck([{name: "Quincy", role: "Founder", isBot: false}, {name: "Naomi", role: "", isBot: true}, {name: "Camperbot", role: "Bot", isBot: true}], "isBot");
