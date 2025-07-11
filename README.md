# javascript-projects
this repository contains javascript prpjects and challenges completed during my course
✅ DOM Manipulation Projects  
- ✅ JavaScript Basics: Variables, Functions, Loops  
- ✅ Event Handling  
- ✅ Form Validation Projects  
- ✅ Array Methods Practice  
- ✅ Final JavaScript Capstone Project

## 💡 Notes

- Code is pushed regularly to track progress.
- Feedback from my instructor is applied to each submission.
git clone https://github.com/sobhi777/javascript-projects.git
cd dom-events-challenge
https://github.com/sobhi777/javascript-projects
!-- Thumbnail Gallery -->
<div class="row">
  <div class="column">
    <img src="img1.jpg" onclick="openModal();currentSlide(1)" class="hover-shadow">
  </div>
  <!-- Repeat columns for each image -->
</div>

<!-- Modal Lightbox -->
<div id="myModal" class="modal">
  <span class="close cursor" onclick="closeModal()">&times;</span>
  <div class="modal-content">
    <div class="mySlides">
      <div class="numbertext">1 / 4</div>
      <img src="img1_wide.jpg" style="width:100%">
    </div>
    <!-- More slides here -->
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
    <div class="caption-container"><p id="caption"></p></div>
    <!-- Demo thumbnails here -->
  </div>
</div>
