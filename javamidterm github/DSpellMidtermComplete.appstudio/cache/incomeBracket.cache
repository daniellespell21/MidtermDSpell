
submit.onclick=function(){
  let income=Number(enterIncome.value)
  
  if (income<30000){
    Label1.textContent=`With your income of $${income}, you are in a tax bracket of 8%`
} else if (income >= 30000 && income<=99999){
    Label1.textContent=`With your income of $${income}, you are in a tax bracket of 15%`
} else if (income > 99999) {
    Label1.textContent=`With your income of $${income}, you are in a tax bracket of 25%`
} else {
    Label1.textContent=`Enter a Number`
  }
}
goAgain.onclick=function(){
  enterIncome.value=''
  
  Label1.textContent=``
}

