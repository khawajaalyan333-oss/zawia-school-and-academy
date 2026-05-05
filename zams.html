<!DOCTYPE html>
<html>
<head>
<title>School Management System</title>

<style>
body {
  font-family: Arial;
  background: #0f172a;
  color: white;
}

.container {
  display: flex;
}

.sidebar {
  width: 200px;
  background: #1e293b;
  padding: 20px;
}

.sidebar button {
  display: block;
  width: 100%;
  margin: 10px 0;
  padding: 10px;
  background: #3b82f6;
  border: none;
  color: white;
  border-radius: 8px;
}

.content {
  flex: 1;
  padding: 20px;
}

.card {
  background: #1e293b;
  padding: 20px;
  margin: 10px 0;
  border-radius: 10px;
}

input {
  padding: 8px;
  margin: 5px;
}

button.add {
  background: green;
}
</style>
</head>

<body>

<h1>🎓 School System</h1>

<div class="container">

<div class="sidebar">
  <button onclick="show('students')">Students</button>
  <button onclick="show('teachers')">Teachers</button>
  <button onclick="show('attendance')">Attendance</button>
</div>

<div class="content">

<div id="students" class="section">
  <h2>Students</h2>

  <input id="sname" placeholder="Name">
  <input id="sclass" placeholder="Class">

  <button class="add" onclick="addStudent()">Add</button>

  <ul id="studentList"></ul>
</div>

<div id="teachers" class="section" style="display:none">
  <h2>Teachers</h2>

  <input id="tname" placeholder="Name">
  <button class="add" onclick="addTeacher()">Add</button>

  <ul id="teacherList"></ul>
</div>

<div id="attendance" class="section" style="display:none">
  <h2>Attendance</h2>
  <p>Mark Present / Absent</p>
  <ul id="attendanceList"></ul>
</div>

</div>

</div>

<script>

// NAVIGATION
function show(section){
  document.querySelectorAll(".section").forEach(s=>s.style.display="none");
  document.getElementById(section).style.display="block";
}

// STORAGE
let students = JSON.parse(localStorage.getItem("students")) || [];
let teachers = JSON.parse(localStorage.getItem("teachers")) || [];

// STUDENTS
function addStudent(){
  let name = document.getElementById("sname").value;
  let cls = document.getElementById("sclass").value;

  students.push({name, cls});
  localStorage.setItem("students", JSON.stringify(students));

  loadStudents();
}

function loadStudents(){
  let list = document.getElementById("studentList");
  list.innerHTML = "";

  students.forEach((s,i)=>{
    let li = document.createElement("li");
    li.innerHTML = s.name + " ("+s.cls+")";

    let del = document.createElement("button");
    del.innerText="X";
    del.onclick=()=>{
      students.splice(i,1);
      localStorage.setItem("students", JSON.stringify(students));
      loadStudents();
    }

    li.appendChild(del);
    list.appendChild(li);
  });

  loadAttendance();
}

// TEACHERS
function addTeacher(){
  let name = document.getElementById("tname").value;

  teachers.push({name});
  localStorage.setItem("teachers", JSON.stringify(teachers));

  loadTeachers();
}

function loadTeachers(){
  let list = document.getElementById("teacherList");
  list.innerHTML="";

  teachers.forEach((t,i)=>{
    let li = document.createElement("li");
    li.innerHTML = t.name;

    let del = document.createElement("button");
    del.innerText="X";
    del.onclick=()=>{
      teachers.splice(i,1);
      localStorage.setItem("teachers", JSON.stringify(teachers));
      loadTeachers();
    }

    li.appendChild(del);
    list.appendChild(li);
  });
}

// ATTENDANCE
function loadAttendance(){
  let list = document.getElementById("attendanceList");
  list.innerHTML="";

  students.forEach(s=>{
    let li = document.createElement("li");

    let present = document.createElement("button");
    present.innerText="Present";

    let absent = document.createElement("button");
    absent.innerText="Absent";

    li.innerHTML = s.name + " ";

    li.appendChild(present);
    li.appendChild(absent);

    list.appendChild(li);
  });
}

// INIT
loadStudents();
loadTeachers();

</script>

</body>
</html>
