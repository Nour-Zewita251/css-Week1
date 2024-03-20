# css-Week1
1:4
task1
/* .title { any element with class title}
#nav { any element with id nav}
div { all div elements }
h2 { all h2 elements} 

task2
<!-- external -->
<link rel="stylesheet" href="css/file.css" />

<!-- color -->
<style>
p {
  color: red;
}
</style>

<!-- make the line blue but in the same element -->
<p style="color: blue;">This Is Our Paragraph</p>

task3
<link rel="stylesheet" href="assets.css/style.css"></link>


task4
<link rel="stylesheet" href="source.css/main.css" /></link>


task5
/* valid */
._user-name {
}   

/* valid */
.-user-name {
}

/* not valid */
.1user-name {
}

/* not valid */
.@user-name {
}

/* not valid */
.user@name {
}

/* valid */
._user10name {
}

/* valid */
.u {
}


task6
/* Bad */
.USERNAME {
}

/* Bad */
.UserName {
}

/* Good */
.user-name {
}

/* Bad */
.userName {
}

/* Bad */
.usernameprofile {
}

