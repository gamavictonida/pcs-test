<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div v-if="$route.path == '/'">
    <div class="header-container">
      <div class="header-container-title">
        <div class="header-title">KerjaYuk!</div>
        <RouterLink to="/notif">
          <div class="header-title" style="display: flex; cursor: pointer">
            <img src="@/assets/icons/bell-alt-svgrepo-com.svg" height="25" width="25">
            <div style="width: 8px; height: 8px; background-color: red; border-radius: 50%; margin-top: 6px; margin-left: -10px"></div>
          </div>
        </RouterLink>
      </div>
      <div style="margin-top: 12px">
        <span style="font-size: 14px; font-weight: 500">Hi, Good Morning!</span>
      </div>
      <div class="header-card">
        <div style="display: flex">
          <div class="circle-image"></div>
          <div style="display: inline-grid; margin-left: 10px">
            <span class="font-header-bold">Tabay</span>
            <span class="font-header" style="margin-top: -5px">Ui/UX Designer</span>
          </div>
          <div style="display: inline-grid; position: absolute; right: 590px">
            <span class="font-header">Member Since</span>
            <span class="font-header-bold" style="font-size: 14px">01 Juni 2021</span>
          </div>
        </div>
        <div style="margin-left: 10px">
          <span class="font-header">Location</span>
        </div>
        <div style="margin-left: 10px; display: flex; justify-content: space-between; margin-bottom: 5px">
          <span class="font-header-bold" style="margin-top: -4px">Kantor Sahid</span>
          <span class="font-header" style="margin-right: 10px; margin-top: -4px">ICD</span>
        </div>
      </div>
      <div style="margin-top: 10px">
        <span style="font-size: 14px; font-weight: 700">Today's Activity</span>
      </div>
      <div style="display: flex; justify-content: space-between; margin-top: 5px">
        <div style="text-align: center; margin-left: 10px">
          <div><i class="bi bi-clock" style="color: red;"></i></div>
          <div class="font-header-bold" style="font-weight: 700">08:30</div>
          <div class="font-header" style="font-weight: 500">Check In</div>
        </div>
        <div style="text-align: center">
          <div><i class="bi bi-arrow-clockwise" style="color: red"></i></div>
          <div style="font-weight: 700; font-size: 14px; color: red">08:30:00</div>
          <div class="font-header" style="font-weight: 500">Working Hours</div>
        </div>
        <div style="text-align: center; margin-right: 10px">
          <div><i class="bi bi-clock-history" style="color: red;"></i></div>
          <div class="font-header-bold" style="font-weight: 700">--:--</div>
          <div class="font-header" style="font-weight: 500">Check Out</div>
        </div>
      </div>
      <div style="margin-top: 10px">
        <span style="font-size: 14px; font-weight: 700">PCS News</span>
      </div>

      <div class="slideshow-container">
        <div style="display: flex;">
          <div class="mySlides fade">
            <div class="card-news" style="margin-left: auto; margin-right: auto;">
              <div style="display: flex; justify-content: space-between">
                <div style="display: flex">
                  <div class="circle-image" style="background-color: red; height: 30px; width: 30px"></div>
                  <div style="display: inline-grid; margin-left: 10px">
                    <span class="font-header-bold" style="margin-top: 5px; color: red">Ana Riswati</span>
                  </div>
                </div>
                <div style="display: flex">
                  <div style="display: inline-grid; margin-right: 10px">
                    <span class="font-header-bold" style="text-align: right">Senin</span>
                    <span class="font-header-bold">30 Mei 2022</span>
                  </div>
                </div>
              </div>
              <div style="display: block; padding-left: 10px;">
                <div style="font-size: 12px; margin-top: 3px; height: 40px; overflow: hidden">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet blanditiis laborum numquam, rem sapiente vero? Consequatur, magnam maiores obcaecati quas quasi quis recusandae. Alias aut commodi excepturi facilis perspiciatis vero!</div>
              </div>
            </div>
          </div>

          <div class="mySlides fade" style="display: none">
            <div class="card-news" style="margin-left: auto; margin-right: auto;">
              <div style="display: flex; justify-content: space-between">
                <div style="display: flex">
                  <div class="circle-image" style="background-color: red; height: 30px; width: 30px"></div>
                  <div style="display: inline-grid; margin-left: 10px">
                    <span class="font-header-bold" style="margin-top: 5px; color: red">Deka</span>
                  </div>
                </div>
                <div style="display: flex">
                  <div style="display: inline-grid; margin-right: 10px">
                    <span class="font-header-bold" style="text-align: right">Senin</span>
                    <span class="font-header-bold">30 Mei 2022</span>
                  </div>
                </div>
              </div>
              <div style="display: block; padding-left: 10px;">
                <div style="font-size: 12px; margin-top: 3px; height: 40px; overflow: hidden">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet blanditiis laborum numquam, rem sapiente vero? Consequatur, magnam maiores obcaecati quas quasi quis recusandae. Alias aut commodi excepturi facilis perspiciatis vero!</div>
              </div>
            </div>
          </div>

          <div class="mySlides fade" style="display: none">
            <div class="card-news" style="margin-left: auto; margin-right: auto;">
              <div style="display: flex; justify-content: space-between">
                <div style="display: flex">
                  <div class="circle-image" style="background-color: red; height: 30px; width: 30px"></div>
                  <div style="display: inline-grid; margin-left: 10px">
                    <span class="font-header-bold" style="margin-top: 5px; color: red">Zaenal</span>
                  </div>
                </div>
                <div style="display: flex">
                  <div style="display: inline-grid; margin-right: 10px">
                    <span class="font-header-bold" style="text-align: right">Senin</span>
                    <span class="font-header-bold">30 Mei 2022</span>
                  </div>
                </div>
              </div>
              <div style="display: block; padding-left: 10px;">
                <div style="font-size: 12px; margin-top: 3px; height: 40px; overflow: hidden">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet blanditiis laborum numquam, rem sapiente vero? Consequatur, magnam maiores obcaecati quas quasi quis recusandae. Alias aut commodi excepturi facilis perspiciatis vero!</div>
              </div>
            </div>
          </div>
        </div>
        <br>

        <div style="text-align:center">
          <span class="dot active" @click="currentSlide(1)"></span>
          <span class="dot" @click="currentSlide(2)"></span>
          <span class="dot" @click="currentSlide(3)"></span>
        </div>
      </div>
      <div>
        <span style="font-size: 14px; font-weight: 700">Online</span>
      </div>
      <div class="card-news" style="margin-left: auto; margin-right: auto; height: 100px; padding-left: 10px">
        <div style="display: flex;">
          <div style="display: inline-grid; text-align: center">
            <div class="circle-image online-people"></div>
            <div class="font-header" style="font-weight: 600;">Jefril</div>
            <div class="font-header" style="font-weight: 300; margin-top: -5px">Sahid</div>
          </div>
          <div style="display: inline-grid; text-align: center">
            <div class="circle-image online-people" style="margin-left: -10px"></div>
            <div class="font-header" style="font-weight: 600;">Zasami</div>
            <div class="font-header" style="font-weight: 300; margin-top: -5px">BSD</div>
          </div>
          <div style="display: inline-grid; text-align: center">
            <div class="circle-image online-people" style="margin-left: -10px"></div>
            <div class="font-header" style="font-weight: 600;">Sam</div>
            <div class="font-header" style="font-weight: 300; margin-top: -5px">Sahid</div>
          </div>
          <div style="display: inline-grid; text-align: center">
            <div class="circle-image online-people" style="margin-left: -10px"></div>
            <div class="font-header" style="font-weight: 600;">Aldo</div>
            <div class="font-header" style="font-weight: 300; margin-top: -5px">Sahid</div>
          </div>
          <div style="display: inline-grid; text-align: center">
            <div class="circle-image online-people" style="margin-left: -10px"></div>
            <div class="font-header" style="font-weight: 600;">Erwin</div>
            <div class="font-header" style="font-weight: 300; margin-top: -5px">Sahid</div>
          </div>
          <div style="display: inline-grid; text-align: center">
            <div class="circle-image online-people" style="margin-left: -10px"></div>
            <div class="font-header" style="font-weight: 600;">Arye</div>
            <div class="font-header" style="font-weight: 300; margin-top: -5px">Sahid</div>
          </div>
          <div style="display: inline-grid; text-align: center">
            <div class="circle-image online-people" style="margin-left: -10px"></div>
            <div class="font-header" style="font-weight: 600;">Risya</div>
            <div class="font-header" style="font-weight: 300; margin-top: -5px">Sahid</div>
          </div>
          <div class="circle-image online-people" style="margin-left: -10px; text-align: center; display: inline-grid">
            <span class="font-more">10</span>
            <span class="font-more" style="margin-top: -10px">More</span>
          </div>
        </div>
      </div>
      <div class="circle-image" style="background-color: red; height: 50px; width: 50px; margin-left: 175px; margin-right: auto; margin-top: 25px; text-align: center; cursor: pointer">
        <img src="@/assets/icons/sign-out-2-svgrepo-com.svg" height="35" width="35" style="margin-top: 8px; color: white">
      </div>
    </div>
    <div class="footer-buuton" style="position: absolute; top: 690px; padding-left: 20px; padding-right: 20px; cursor: pointer">
      <div class="footer-buuton-group" style="cursor: pointer">
        <div><i class="bi bi-house-door-fill" style="cursor: pointer"></i></div>
        <span class="font-header" style="font-weight: 500">Home</span>
      </div>
      <div class="footer-buuton-group">
        <div><i class="bi bi-calendar-check"></i></div>
        <span class="font-header" style="font-weight: 500">Attendance</span>
      </div>
      <div class="footer-buuton-group" style="overflow: visible">
        <div class="circle-image" style="background-color: white; height: 40px; width: 40px; margin-top: -20px; z-index: -100"></div>
        <span class="font-header" style="font-weight: 500; margin-top: 5px">Check Out</span>
      </div>
      <div class="footer-buuton-group">
        <div><i class="bi bi-file-earmark-check"></i></div>
        <span class="font-header" style="font-weight: 500">Form</span>
      </div>
      <div class="footer-buuton-group">
        <div class="ceekk"><i class="bi bi-gear"></i></div>
        <span class="font-header" style="font-weight: 500; cursor: pointer">Setting</span>
      </div>
    </div>
  </div>
  <div class="h-full w-screen bg-red-50" v-else>
    <RouterView />
  </div>
</template>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  if (slides.length > 0 && dots.length > 0){
    slides[slideIndex-1].style.display = "block";
    dots[slideIndex-1].className += " active";
  }
}
</script>
