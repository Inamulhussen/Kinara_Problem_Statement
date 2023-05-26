# Kinara_Problem_Statement
 Load Student Details API
_________________________________________________________________
 const express = require('express')
const app = express();
const PORT = 3000;
//Following lines are to make sure our app can parse the json data
app.use(express.json());
app.use(express.urlencoded({
  extended: false
}));

app.listen(PORT, () => {
  console.log('Server started on port 3000');
})
