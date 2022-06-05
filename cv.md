# Serebrennikova Irina
### *Junior Frontend Developer*  

---

### About myself:  
Hard worker with a good work-and-life balance  

---

### Contacts: 
**Telegram:** [@irksova](t-do.ru/irksova)  
**E-mail:** dancespenguin@gmail.com  

**LinkedIn:** [Irina Serebrennikova](https://www.linkedin.com/in/irina-serebrennikova-80160a231/)  
**GitHub:** [irksova](https://github.com/irksova)  
**Discord** murrrka(@irksova)  

**Location:** Russia, St.Petersburg (ready to distant work)  

---

### Skills:
**Hard Skills:**
* HTML, CSS, JavaScript  
* Figma, Adobe Photoshop, Adobe Illustrator, Adobe InDesign, Tilda  

**Languages:**  
* Russian — Native proficiency  
* English — Pre-Intermediate proficiency  

---

### Work experience:

* **Content Moderator**  
VK (Mail.ru Group until 12 October 2021), St Petersburg City, Russia    
*May, 2017 - May, 2022*  

* **Freelance Web Designer**  
*2018 - Present*  

---

### Education and Courses:  
* **Master's degree**, Information Technology  
ITMO University  
*Sep 2016 - Jun 2018*  

* **Bachelor's degree**, Information Technology  
Tomsk State University of Control Systems and Radioelectronics  
*Sep 2012 - Jun 2016*  

---

### Code example:
**Script for showing random block on Tilda**
```
<script>
$(document).ready(
function(){
    $('#rec375605562, #rec376123622, #rec376123663, #rec376123687, #rec376123698,').addClass('chooseblk').hide();

function getRandomInt(max) { 
    return Math.floor(Math.random() * Math.floor(max)); 
};

function showRandomBlock(){
    let blkSts = getRandomInt($('.chooseblk').length);
    $('.chooseblk').hide();
    $('.chooseblk:eq('+blkSts+')').slideToggle(0); t_lazyload_update(); 
};

$("[href='#prediction']").click(function(e) {
    e.preventDefault();
    showRandomBlock()});
});
</script>
```
---
### Thank you for watching!  
