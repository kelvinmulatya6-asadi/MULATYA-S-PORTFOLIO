//View My Work button
document.getElementById("workBtn").onclick=function(){

    document.getElementById("projects").scrollIntoView({
        behavior:"smooth"
    });
};

//Dark Mode
document.getElementById("themeBtn").onclick=function(){
    document.body.classList.toggle("dark");
};

//Contact Form
document.getElementById("contactForm").onsubmit=function(event){
    event.preventDefault();

    let name=
    document.getElementById("name").value;

    if(name===""){
        alert("please enter your name.");
    }else{
        alert("Thank you," + name + "! Your message has been received.");
    }
};
//mobile menu
document.getElementById("menuBtn").onclick=function(){
    document.getElementById("navMenu").classList.toggle("show");
};