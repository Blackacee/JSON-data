# JSON-data

// get some data from stackoverflow
fetch("https://api.stackexchange.com/2.2/questions/featured?order=desc&sort=activity&site=stackover
flow")
 .then(resp => resp.json())
 .then(json => console.log(json))
 .catch(err => console.log(err));
