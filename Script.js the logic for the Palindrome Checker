const button = document.getElementById("check-btn") ;
button.addEventListener('click' , function(){
  const input = document.getElementById("text-input").value;
  const result = document.getElementById("result");
  if(input === ""){
     alert("Please input a value")
  }

  const cleaned = input.replace(/[^A-Za-z0-9]/g, "").toLowerCase();
  const reversed = cleaned.split("").reverse().join("");

  if(cleaned === reversed){
   result.textContent = `${input} is a palindrome.`;
   result.style.color = "#00FFFF"
  } else {
    result.textContent = `${input} is not a palindrome.`;
    result.style.color = "#ff0055";
  }
  result.style.animation = "none";
  result.offsetHeight;
  result.style.animation = "fadeIn 0.5s ease-in-out";

}); 
