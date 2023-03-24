--login with specific email address--

function validate () {
    var field=document.getElementById("field").value;

    if(field=="admin@gmail.com") {
        alert("get started free successfully");
        return false;
    }
    else{
        alert("get started free failed");
    }
}
