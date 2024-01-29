JS - 9
Theme: DOM MONUPULATION 

let parent = document.querySelector('.parent'),
child = document.querySelector('.child'),
littleChild = document.querySekector('.little-child');
3 ta variable ochmasdan turip  variable bita ochib 3 ta nom berish usuli

console.log(parent.parentElement);
parentElement - bu otasini olib beradi

console.log(parent.nextElementSibling);
nextElementSibling - ozidan keyingi elementi tanlab beradi

console.log(parent.previousElementSibling);
previousElementSibling - ozidan oldingi elementi oladi

console.log(parent.children);
children - bola elementi olib beradi

console.log(parent.childNotes);
childNotes - nima bosa hammasini qaytarib beradi 

console.log(parent.firstChild);
firstChild - birinchi bolani tanlidi

console.log(parent.lastChild);
lastChild - ohirgi elementi oladi 

console.log(parent.firstElementChild);
firstElementChild - birinchi elementi olib beradi 

console.log(parent.lastElementChild);
lastElementChild - ohirgisini olib beradi

console.log(parent.children[1]);
Har kando elementi select qisa boladi 


JS - dan turip still berish

parent.style.backgroundColor = "red";

child.style.borderRadious = "1px solid grey";


Dark mode

// HTML

<button onclick="darkMode()">Dark mode</button>

// JS

let isDark = false;

function darkMode() {
    
    isDark =! isDark;    

    if (isDark) {
        parent.style.backgroundColor = "black";
        parent.style.color = "white";
    } else {
          parent.style.backgroundColor = "white";
          parent.style.color = "black";
      }
}
