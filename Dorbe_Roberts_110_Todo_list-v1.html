<!DOCTYPE html>
<html lang="lv">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<title>todo lists</title>
</head>
<body class="bg-light">
<div class="container d-flex justify-content-center mt-5">
<div class="card p-4 w-100" style="max-width:500px">
<h3 class="text-center mb-3">Saraksts kas jāizdara</h3>
<div class="input-group mb-3">
<input id="task-input" type="text" class="form-control" placeholder="Ieraksti darbu">
<button class="btn btn-primary" onclick="addTask()">Pievienot</button>
</div>
<ul id="task-list" class="list-group"></ul>
</div>
</div>

<script>
const list=document.getElementById("task-list")
const input=document.getElementById("task-input")
const data=JSON.parse(localStorage.getItem("tasks")||"[]")
data.forEach(t=>createTask(t))
function addTask(){
if(!input.value.trim())return
data.push(input.value)
localStorage.setItem("tasks",JSON.stringify(data))
createTask(input.value)
input.value=""
}
function createTask(text){
const li=document.createElement("li")
li.className="list-group-item d-flex justify-content-between align-items-center"
li.innerHTML=`${text}<button class="btn btn-danger btn-sm">Dzēst</button>`
li.querySelector("button").onclick=()=>{
data.splice(data.indexOf(text),1)
localStorage.setItem("tasks",JSON.stringify(data))
li.remove()
}
list.appendChild(li)
}
</script>
</body>
</html>
