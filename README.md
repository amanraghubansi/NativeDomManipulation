####################################################
Create element using string literals 

function fragmentFromString(strHTML) {
    var temp = document.createElement('template');   
    temp.innerHTML = strHTML;
    return temp.content;
}

####################################################
