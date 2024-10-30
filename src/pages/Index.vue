<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<template>
  <Layout>
    <section class="home-section" id="home">
      <div class="container-fluid">
        <div class="bg-box">
          <div class="opener-text-box">
            <div class="wording-wrapper">
              <div class="opener-headline">👋 Hi! I'm Guntur & I'm a</div>
                <div class="words">
                      <span class='text-color'>UI UX Designer</span>
                      <span class='text-color'>Product Designer</span>
                      <span class='text-color'>UX Researcher</span>
                      <span class='text-color'>Frontend Developer</span>
                      <span class='text-color'>Graphic Designer</span>
                </div>
                <p class="paragraph">
                  That creates empathy with users, design solutions, and helping <br>to focus the business goals on users.
                  I love to bring simplicity and<br>ease to complex interfaces.
                </p>
                <a href="https://drive.google.com/file/d/1YeecJkS0jQOFDDF9CXYPew0IrWCZ2vH5/view?usp=sharing" target="_blank" rel="noopener noreferrer" class="btn download"><g-image src="/images/download.png" class="download-btn"/>Download CV</a>
                <a href="https://www.linkedin.com/in/gunturalll/" target="_blank" rel="noopener noreferrer" class="btn linkedin">Check My Linkedin<g-image src="/images/chevrons-right.svg" class="icon-btn"/></a>
              </div>
              <g-image src="/images/foto-profil.png" class="img-profil"/>
          </div>
        </div>
      </div>
    </section>

    <section class="about-section" id="about">
      <div class="container-fluid">
        <div class="wrapper-1">
          <div class="chip-section">About me</div>
        </div>
          <div class="navigation-container">
            <div role="tablist" class="tabbed-navigation">
              <a role="tab" id="tab-1" class="tab-btn active" tabindex="0" href="#content-1" aria-label="Info" aria-selected="true">Personal Info</a>
              <a role="tab" id="tab-2" class="tab-btn" tabindex="-1" href="#content-2" aria-label="Qualifications" aria-selected="false">Qualifications</a>
              <a role="tab" id="tab-3" class="tab-btn" tabindex="-1" href="#content-3" aria-label="Skills" aria-selected="false">Skills</a>
            </div>
          </div>
          <div class="container">
            <div id="content-1" class="tab-content tab-content-1 active" aria-hidden="false">
                  <div class="img">
                    <img src="images/personal-info-pict.png" alt="">
                  </div>
                  <div class="personal-info">
                    <h2 class="heading">Unmatched service quality for over 2 years</h2>
                    <div class="sub-heading">
                      <p>
                        I specialize in crafting intuitive websites and apps with cutting edge technology,
                        delivering<br>dynamic, and engaging user experiences.
                      </p>
                    </div>
                    <div class="detail-info">
                      <div class="row-1">
                        <div class="name">
                          <p><g-image src="/images/person.svg" class="icon-person-name"/>&nbsp;Maulana Guntur Alharits (25 y.o)</p>
                        </div>
                        <div class="phone-number">
                          <p><g-image src="/images/call.svg" class="phone-call"/>&nbsp;+62 82121697108</p>
                        </div>
                      </div>
                      <div class="row-2">
                        <div class="gmail">
                          <p><g-image src="/images/mail.svg" class="email"/>&nbsp;gunturalharits28@gmail.com</p>
                        </div>
                        <div class="domicile">
                          <p><g-image src="/images/distance.svg" class="dom-icon"/>&nbsp;Jakarta, Indonesia</p>
                        </div>
                      </div>
                      <div class="row-3">
                        <div class="education">
                          <p><g-image src="/images/school.svg" class="edu-icon"/>&nbsp;Bachelor’s Degree on Computer Science</p>
                        </div>
                      </div>
                      <div class="language-skills">
                        <h2 class="heading-language">Language skills</h2>
                        <hr>
                        <p>Bahasa Indonesia (Advanced), English (Intermediate)</p>
                      </div>
                    </div>
                  </div>
            </div>
            <div id="content-2" class="tab-content tab-content-2" aria-hidden="true">
                <div class="wrapper-right">
                  <div class="my-journey">
                    <h2 class="heading">My Journey</h2>
                  </div>
                  <div class="wrap-exp-edu">
                    <div class="experience">
                      <div class="tittle">
                        <h3 class="heading"><g-image src="/images/work.svg" class="icon-work"/>&nbsp;Experience</h3>
                      </div>
                      <div class="contents">
                        <div class="box">
                          <h2>Rekrutee.com</h2>
                          <h3>UI/UX Designer</h3>
                          <p>Sep 2021 - Present</p>
                        </div>
                        <div class="box">
                          <h2>Dhana Jasa Konsultan</h2>
                          <h3>UI/UX Designer</h3>
                          <p>Sep 2017 - Present</p>
                        </div>
                        <div class="box">
                          <h2>Majujaya Karya Indonesia</h2>
                          <h3>UI/UX Design Lead</h3>
                          <p>Mar 2021 - Sep 2022</p>
                        </div>
                        <div class="box">
                          <h2>Gunadarma University</h2>
                          <h3>IT Support Specialist in Tax Laboratory</h3>
                          <p>Sep 2019 - Aug 2021</p>
                        </div>
                      </div>
                    </div>
                    <div class="education">
                      <div class="tittle">
                        <h3 class="heading"><g-image src="/images/school.svg" class="icon-edu"/>&nbsp;Education</h3>
                      </div>
                      <div class="contents">
                        <div class="box">
                          <h2>Gunadarma University</h2>
                          <h3>Bachelor's Degree of IT</h3>
                          <p>Aug 2017 - Aug 2021</p>
                        </div>
                        <div class="box">
                          <h2>SMK Taman Harapan</h2>
                          <h3>Highschool Diploma of Network Engineer</h3>
                          <p>July 2015 - July 2017</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
            </div>
            <div id="content-3" class="tab-content tab-content-3" aria-hidden="true">
                <div class="container">
                  <div class="my-skills-part">
                    <div class="my-skills">
                      <h2 class="heading">Tools I use everyday</h2>
                      <hr>
                    </div>
                    <div class="logo">
                      <div class="logo-container">
                        <img src="images/skills/logo-html-css-javascript.png" class="logo-item" alt="Logo 1">
                        <img src="images/skills/logo-figma.png" class="logo-item" alt="Logo 2">
                        <img src="images/skills/logo-ai.png" class="logo-item" alt="Logo 3">
                        <img src="images/skills/logo-miro.png" class="logo-item" alt="Logo 4">
                        <img src="images/skills/logo-balsamiq.png" class="logo-item" alt="Logo 5">
                        <img src="images/skills/logo-maze.png" class="logo-item" alt="Logo 6">
                        <img src="images/skills/logo-framer.png" class="logo-item" alt="Logo 7">
                        <img src="images/skills/logo-vue.png" class="logo-item" alt="Logo 8">
                        <img src="images/skills/logo-trello.png" class="logo-item" alt="Logo 9">
                        <img src="images/skills/logo-gitlab.png" class="logo-item" alt="Logo 10">
                      </div>
                    </div>
                  </div>
                  <div class="certificate-container">
                    <div class="my-certificate">
                        <h2 class="heading">My competencies</h2>
                        <hr>
                    </div>
                    <div class="container">
                      <div class="certificate-1">
                        <div class="certif-wrapper">
                          <img src="images/google-certif.png" alt="Certificate-1" class="certif-1">
                        </div>
                        <h5 class="tittle">Foundations of User Experience (UX) Design</h5>
                      </div>
                      <div class="certificate-2">
                        <div class="certif-wrapper">
                          <img src="images/udemy-certif.jpg" alt="Certificate-2" class="certif-2">
                        </div>
                        <h5 class="tittle">Motion Design with Figma: Animations, Motion Graphics</h5>
                      </div>
                      <div class="certificate-3">
                        <div class="certif-wrapper">
                          <img src="images/myskill-certif.png" alt="Certificate-3" class="certif-3">
                        </div>
                        <h5 class="tittle">UI-UX Research and Design: Fullstack Intensive Bootcamp</h5>
                      </div>
                      <div class="certificate-4">
                        <div class="certif-wrapper">
                          <img src="images/design-gestalt-certif.png" alt="Certificate-4" class="certif-4">
                        </div>
                        <h5 class="tittle">UX Design Gestalt</h5>
                      </div>
                      <div class="certificate-5">
                        <div class="certif-wrapper">
                          <img src="images/skill-academy-certif.jpg" alt="Certificate-5" class="certif-5">
                        </div>
                        <h5 class="tittle">Designing Applications and Software For Users</h5>
                      </div>
                    </div>
                </div>
                </div>
        </div>
      </div>
      </div>
    </section>

    <section class="service-section" id="service">
      <div class="container-fluid">
        <div class="wrapper">
          <div class="chip-section">My services</div>
        </div>
        <div class="container">
          <h1 class="tittle">Build your infinite experience with me</h1>
          <p class="sub-tittle">Your website looks so boring? Want to create an eye-catching User Experience for your website? I am here for you!</p>
          <div class="item-list">
            <div class="item">
              <img src="/images/icon-uiux-card.png" class="symbol">
              <p class="label">UI/UX Design</p>
              <p class="description">I specialize in crafting seamless and intuitive user experiences.</p>
            </div>
            <div class="item">
              <img src="/images/icon-webdev-card.png" class="symbol">
              <p class="label">Web Development</p>
              <p class="description">I deliver solutions that elevate your online presence and drive results.</p>
            </div>
            <div class="item">
              <img src="/images/icon-graphic-card.png" class="symbol">
              <p class="label">Graphic Design</p>
              <p class="description">I specialize in creating visual identities that leave a lasting impression.</p>
            </div>
          </div>
          <a href=" https://wa.me/082121697108" class="btn btn-contact">Digitalize your business</a>
        </div>
      </div>
    </section>

    <section class="project-section" id="project">
      <div class="container-fluid">
        <div class="wrapper">
          <div class="chip-section">My portfolio</div>
        </div>
        <div class="container">
          <h1 class="tittle">Elevate your project: collaborative sessions for success</h1>
          <p class="sub-tittle">Unlock Innovation and Drive Results Together</p>
          <div class="navigation-container">
            <div role="tablist" class="navigation">
              <a role="tab" id="tab-project-1" class="tab-btn-project active" tabindex="0" href="#content-project-1" aria-label="Mobile" aria-selected="true">Mobile Apps</a>
              <a role="tab" id="tab-project-2" class="tab-btn-project" tabindex="-1" href="#content-project-2" aria-label="Web" aria-selected="false">Website</a>
              <a role="tab" id="tab-project-3" class="tab-btn-project" tabindex="-1" href="#content-project-3" aria-label="Graphic" aria-selected="false">Graphic Design</a>
            </div>
          </div>
          <div id="content-project-1" class="tab-content-project tab-content-project-1 active" aria-hidden="false">
            <div class="row-1">
              <div class="mobile-1">
                <p class="category">Mobile Apps</p>
                <p class="tittle">Rekrutee</p>
                <p class="desc">Job Portal Application</p>
                <a href="#" class="see-detail">See details</a>
                <img src="/images/mobile-design/pict-project-1.png" class="pict-project-split">
              </div>
              <div class="mobile-2">
                  <p class="category">Mobile Apps</p>
                  <p class="tittle">Duit Instant</p>
                  <p class="desc">Finance Technology</p>
                  <a href="#" class="see-detail">See details</a>
                  <img src="/images/mobile-design/pict-project-2.png" class="pict-project-split">
              </div>
            </div>
              <div class="row-2">
                <div class="mobile-3">
                  <p class="category">Mobile Apps</p>
                  <p class="tittle">Bandor (Bandar Motor)</p>
                  <p class="desc">Motorcycle Market Place</p>
                  <a href="#" class="see-detail">See details</a>
                  <img src="/images/mobile-design/pict-project-3.png" class="pict-project-split">
                </div>
                <div class="mobile-4">
                  <p class="category">Mobile Apps</p>
                  <p class="tittle">Media Tanam</p>
                  <p class="desc">Agriculture Monitoring</p>
                  <a href="#" class="see-detail">See details</a>
                  <img src="/images/mobile-design/pict-project-4.png" class="pict-project-split">
                </div>
              </div>
              <div class="row-3">
                <div class="mobile-5">
                  <p class="category">Mobile Apps</p>
                  <p class="tittle">Ewija (Explore Wisata Jateng)</p>
                  <p class="desc">Tourism Guidance</p>
                  <a href="#" class="see-detail">See details</a>
                  <img src="/images/mobile-design/pict-project-5.png" class="pict-project-split">
                </div>
                <div class="mobile-6">
                  <p class="category">Mobile Apps</p>
                  <p class="tittle">Momify</p>
                  <p class="desc">Pregnancy Tracker</p>
                  <a href="#" class="see-detail">See details</a>
                  <img src="/images/mobile-design/pict-project-6.png" class="pict-project-split">
                </div>
              </div>
              <div class="row-4">
                <div class="mobile-7">
                  <p class="category">Mobile Apps</p>
                  <p class="tittle">Salutary</p>
                  <p class="desc">Exercise & Food Tracker</p>
                  <a href="#" class="see-detail">See details</a>
                  <img src="/images/mobile-design/pict-project-7.png" class="pict-project-split">
                </div>
                <div class="mobile-8">
                  <p class="category">Mobile Apps</p>
                  <p class="tittle">Starbucks Redesign</p>
                  <p class="desc">Food E-Commerce</p>
                  <a href="#" class="see-detail">See details</a>
                  <img src="/images/mobile-design/pict-project-8.png" class="pict-project-split">
                </div>
              </div>
          </div>
          <div id="content-project-2" class="tab-content-project tab-content-project-2" aria-hidden="true">
            <div class="row-1">
              <div class="web-design-1">
                <p class="category">Web Design</p>
                <p class="tittle">Rekrutee</p>
                <p class="desc">Job Portal Platform</p>
                <a href="#" class="see-detail">See details</a>
                <img src="/images/web-design/web-design-1.png" class="pict-project-split">
              </div>
              <div class="web-design-2">
                  <p class="category">Web Design</p>
                  <p class="tittle">Daily Golf</p>
                  <p class="desc">E-commerce Golf Web Design</p>
                  <a href="#" class="see-detail">See details</a>
                  <img src="/images/web-design/web-design-2.png" class="pict-project-split">
              </div>
            </div>
          </div>
          <div id="content-project-3" class="tab-content-project tab-content-project-3" aria-hidden="true">

          </div>
          </div>
        </div>
    </section>

    <section class="testimonials-section" id="testi">
      <div class="container-fluid">
        <div class="wrapper">
          <div class="chip-section">Reviews</div>
        </div>
        <div class="container">
          <h1 class="tittle">People love working with me</h1>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
import $ from 'jquery'

export default {
  metaInfo: {
    title: 'Portfolio'
  },
};
$(document).ready(function(){
    $('.tab-btn').click(function(e){
        e.preventDefault();
        var tabId = $(this).attr('href');
        $('.tab-btn').removeClass('active');
        $(this).addClass('active');
        $('.tab-content').removeClass('active').hide();
        $(tabId).addClass('active').show();
    });
});

$(document).ready(function(){
    $('.tab-btn-project').click(function(e){
        e.preventDefault();
        var tabId = $(this).attr('href');
        $('.tab-btn-project').removeClass('active');
        $(this).addClass('active');
        $('.tab-content-project').removeClass('active').hide();
        $(tabId).addClass('active').show();
    });
});
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
