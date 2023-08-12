<template>
  <div>
    <!-- --------------------Herader Section--------------------------------- -->
    <section class="header" id="header">
      <nav>
        <a href="">
          <img
            class="clgLogo"
            src="https://pbs.twimg.com/profile_images/1450171770485583877/CA3SewH__400x400.jpg"
          />
          <label class="ms-3">Eduford</label>
        </a>
        <div class="nav-links" v-bind:style="{ right: isActive ? '0' : '-200px' }">
          <i class="fa fa-times" @click="hideMenu()"></i>
          <ul>
            <li><a href="#header">HOME</a></li>
            <li><a href="#about">ABOUT</a></li>
            <li><a href="#course">COURSES</a></li>
            <li><a href="#review">REVIEWS</a></li>
            <li><a href="#campus">CAMPUS</a></li>
            <li><a href="#facilities">FACILITIES</a></li>
            <li><a href="#contact">CONTACT</a></li>
          </ul>
        </div>
        <i class="fa fa-bars" @click="showMenu()"></i>
      </nav>
      <div class="text-box">
        <marquee behavior="scroll" direction="left" scrollamount="15"
          >World's Biggest University</marquee
        >
        <p>
          We’re a leading research university with a heart. Founded in the decade that the U.S.
          Constitution was signed, we’re the nation’s oldest Catholic and Jesuit university. Today
          we’re a forward-looking, diverse community devoted to social justice, restless inquiry and
          respect for each person’s individual needs and talents..
        </p>
        <a href="" class="super-btn">Visit Us To Know More</a>
      </div>
    </section>

    <!-- ----------------------------Courses section------------------------- -->

    <section class="course" id="course">
      <h1>Courses we Offer</h1>
      <p>
        Explore the intersection of technology and society. Learn about environmental justice. Take
        the famous Problem of God course. Our innovative courses inspire and invite you to help
        solve some of today’s most pressing local, national and global issues.
      </p>

      <div class="row-sec">
        <div class="course-col" style="background-color: #e6fff7">
          <h3>| UG Programs |</h3>
          <p>
            For decades, Eduford College has improved the health of our communities, one graduate at
            a time. The JoAnn McGrath School of Nursing and Health Professions, as one of the
            largest nursing schools in Wisconsin, offers a wide array of fully accredited nursing
            programs, guaranteed clinical placements and a technology-rich Center for Clinical
            Education.
          </p>
        </div>

        <div class="course-col" style="background-color: #ffe6ff">
          <h3>| Graduate Programs |</h3>
          <p>
            Building on our strong roots in leadership, health care and education, Eduford is proud
            to offer an array of coed graduate programs for women and men who are ready to advance
            their careers and grow as leaders. The Eduford College Community Psychology Master's
            program will help you to meet your goals of becoming a Licensed Professional Counselor.
          </p>
        </div>

        <div class="course-col" style="background-color: #e6e6ff">
          <h3>| Post Graduation |</h3>
          <p>
            The Eduford, as one of the largest nursing schools in Wisconsin, offers a wide array of
            fully accredited nursing programs, guaranteed clinical placements and a technology-rich
            Center for Clinical Education. The Eduford College Community Psychology Master's program
            will help you to meet your goals of becoming a Licensed Professional Counselor.
          </p>
        </div>
      </div>
    </section>

    <!-- -------------------------campus section--------------------------------->

    <section class="campus" id="campus">
      <h1>Our Global Campus</h1>
      <p>
        The University of Hartford's main campus is located on Bloomfield Avenue. Surrounded by
        green space, the main campus is divided into residential and academic buildings connected by
        a bridge that overlooks the north branch of the Park River, known to us as Hog River.
      </p>
      <div class="row-sec">
        <div class="campus-col">
          <img
            src="https://www.bangor.ac.uk/sites/default/files/styles/16x9_1100w/public/2020-05/CB%202018%20May%20%2837%29.jpg?h=41ef3158&itok=zGs3cG5Q"
          />
          <div class="layer">
            <h3 class="text-primary">LONDON</h3>
          </div>
        </div>

        <div class="campus-col">
          <img
            src="https://www.topuniversities.com/sites/default/files/styles/articles_inline/public/articles/lead-images/ludwig-university-of-munich.jpg.webp"
          />
          <div class="layer">
            <h3>NEW YORK</h3>
          </div>
        </div>

        <div class="campus-col">
          <img
            src="https://keystoneacademic-res.cloudinary.com/image/upload/element/16/166065_articlekeystoneimage.png"
          />
          <div class="layer">
            <h3 class="text-danger">WASHINGTON</h3>
          </div>
        </div>
      </div>
    </section>

    <!-- --------------------------Facilities---------------------- -->

    <section class="facilities" id="facilities">
      <h1>Our Facilities</h1>
      <p>
        We commit to meet the financial need of every admitted undergraduate student. We don’t
        consider your ability to pay when we review your application, and we don’t base our decision
        on whether you can cover the cost. If you’re accepted here, you belong here.
      </p>
      <div class="row-sec">
        <div class="facilities-col">
          <img src="https://eduford.mhjohn.com/image/library.png" />
          <h3>World Class Library</h3>
          <p>
            Pursue research at Eduford’s libraries, which include more than 3.5 million holdings.
            Whether your focus is on a specific discipline, interdisciplinary areas or emerging
            fields, our libraries offer academic resources, a maker hub, collaborative spaces and
            more.
          </p>
        </div>

        <div class="facilities-col">
          <img src="https://eduford.mhjohn.com/image/basketball.png" />
          <h3>Largest Play Ground</h3>
          <p>
            The College introduces students to philosophy and theology and challenges them to delve
            deeply into the arts, humanities, languages, social sciences and sciences.
          </p>
        </div>

        <div class="facilities-col">
          <img src="https://eduford.mhjohn.com/image/cafeteria.png" />
          <h3>Tasty and Healthy Food</h3>
          <p>
            Whether students pursue studies in Arabic, chemistry, government or one of hundreds of
            other opportunities, they are part of a rich legacy of academic excellence designed to
            serve them well in an ever-changing world.
          </p>
        </div>
      </div>
    </section>

    <!-- -----------------------Testimonials---------------------------- -->

    <section class="testimonials" id="review">
      <h1>What Our Student Says</h1>
      <p>
        We commit to meet the financial need of every admitted undergraduate student. We don’t
        consider your ability to pay when we review your application, and we don’t base our decision
        on whether you can cover the cost. If you’re accepted here, you belong here.
      </p>
      <div class="row-sec">
        <div class="testimonial-col">
          <img src="https://i.pinimg.com/236x/b2/df/7b/b2df7ba48acb476216361c611734703c.jpg" />
          <div>
            <p>
              “It’s likely that you will come to love some of the most amazing souls this campus has
              to offer. That love may come in the form of friendships that you know will last
              forever.”
            </p>
            <h3>Abhishek Roy</h3>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-o"></i>
          </div>
        </div>

        <div class="testimonial-col">
          <img src="https://cdn2.stylecraze.com/wp-content/uploads/2013/06/Lucy-Hale.jpg" />
          <div>
            <p>
              “Eduford is home to me not because of the fancy buildings like Healy Hall, or its
              prestigious reputation, care for the whole person as each of us attempts to live our
              lives for others.”
            </p>
            <h3>Anamika Saha</h3>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-half-o"></i>
          </div>
        </div>
      </div>
    </section>

    <!-- -----------------------------Call To Action-------------------- -->

    <section class="cta" id="contact">
      <h1>Enroll For Our Various Online Courses<br />Anywhere from the World</h1>
      <a href="" class="super-btn">CONTACT US</a>
    </section>

    <!-- ------------------------------Footer----------------------------- -->

    <section class="footer" id="about">
      <h4>About Us</h4>
      <p>
        We’re a leading research university with a heart. Founded in the decade that the U.S.
        Constitution was signed, we’re the nation’s oldest Catholic and Jesuit university. We’re a
        community of people who bridge our disparate experiences and identities. Meet the people and
        places that make Eduford home.
      </p>
      <div class="icons">
        <a href="https://www.facebook.com/login/" target="_blank"><i class="fa fa-facebook"></i></a>
        <a href="https://twitter.com/" target="_blank"><i class="fa fa-twitter"></i></a>
        <a href="https://www.instagram.com/" target="_blank"><i class="fa fa-instagram"></i></a>
        <a href="https://www.linkedin.com/" target="_blank"><i class="fa fa-linkedin"></i></a>
        <a href="https://web.whatsapp.com/" target="_blank"><i class="fa fa-whatsapp"></i></a>
        <a href="https://web.telegram.org/" target="_blank"><i class="fa fa-telegram"></i></a>
        <a href="https://www.youtube.com/" target="_blank"><i class="fa fa-youtube"></i></a>
      </div>
      <p>
        Made With <i class="fa fa-heart-o"></i> Gopikrishna Gurivisetti
        <i class="fa fa-copyright"></i>
      </p>
    </section>
  </div>
</template>

<script setup>
import { ref } from 'vue';
const isActive = ref(false)

function showMenu() {
  isActive.value = true
}

function hideMenu() {
  isActive.value = !isActive.value
}
</script>
<style scoped>

</style>
