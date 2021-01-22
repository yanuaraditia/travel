<template>
  <div>
    <section>
      <b-container class="py-5">
        <div class="text-center scopus mx-lg-auto py-lg-5">
          <h1 class="font-weight-bold trotesk">Video is the most powerful way to share information and connect with people</h1>
          <p class="mx-lg-5">Wibbitz gives teams the freedom to quickly and easily create short form video using automated video creation technology. From small marketing teams to multinational media companies, Wibbitz makes it easy for any business to grow with video.</p>
        </div>
      </b-container>
      <b-container fluid="">
        <img src="~/assets/about-hero.svg" class="img-fluid" alt="">
      </b-container>
      <b-container>
        <b-row class="py-5">
          <b-col lg="5">
            <h2 class="mr-lg-4">Empowering teams with video</h2>
          </b-col>
          <b-col class="pl-lg-4">
            <p>We live in a dynamic world where the way people communicate and share information is changing rapidly. Founded in 2011, Wibbitz is transforming the role that video plays in this change.</p>
            <p>With patented technology and a keen eye for media trends, Wibbitz has paved the way for businesses to harness the power of video with its online video editor built for any team and industry leading video production API.</p>
            <p>Our customers come from all industries and work with us to achieve a wide range of goals—because today, video is universal. We help the disruptive tech startup marketing team gain brand awareness, and the seasoned media conglomerate achieve efficiencies in their digital strategy.</p>
            <p>Our solutions are designed to empower teams to make more meaningful connections with customers, engage audiences, drive revenue, and build an impactful brand. To evoke emotion, inspire action, and advance change. That’s what video can do.</p>
          </b-col>
        </b-row>
      </b-container>
    </section>
    <section class="wb_about--people bg-gray">
      <b-container>
        <div class="row">
          <div class="col-md-7 order-md-2">
            <div class="wb_header">
              <h2 class="font-weight-bold">Our power is in our people</h2>
              <p>Success is a journey, and we travel in good company. We seek those who seek adventure, which is how we continuously raise the bar for ourselves, each other, and our industry. By building a team who truly care, we’re able to achieve change all while enjoying the ride.</p>
              <p>We’re just a group of people, trying to empower people, to better connect with people.</p>
              <p><a class="link-arrow" href="http://www.wibbitz.com/jobs/" target="_self">Learn more about our growing team <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/themes/wibbitz/assets/svg/arrow-right-blue.svg" alt="arrow-right"></a></p>
            </div>
            <div class="img-wrap about-image1">
              <img src="~/assets/TLV_2.png" alt="" data-rjs="2">
            </div>
          </div>
          <div class="about-images-group2 col-md-5 order-md-1">
            <div class="row">
              <div class="col-6 col-md-12">
                <div class="img-wrap about-image2 text-md-right">
                  <img src="~/assets/about-image1.jpg" alt="About Image" data-rjs="2">
                </div>
              </div>
              <div class="col-6 col-md-12">
                <div class="img-wrap about-image3 text-md-right">
                  <img src="~/assets/about-image2.jpg" alt="About Image" data-rjs="2">
                </div>
              </div>
            </div>
          </div>
        </div>
      </b-container>
    </section>
    <section class="wb_about--brands">
      <b-container>
        <div class="wb_header text-center">
          <h2>Leading brands trust Wibbitz for video</h2>
          <p><a class="link-arrow" href="https://www.wibbitz.com/customers/" target="_self">Customer Success Stories <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/themes/wibbitz/assets/svg/arrow-right-blue.svg" alt="arrow-right"></a></p>
        </div>
        <ul class="wb_trusted--brands">
          <li>
            <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-reuters.svg" alt="Reuters">
          </li>
          <li>
            <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-taboola.svg" alt="Taboola">
          </li>
          <li>
            <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-nbc.svg" alt="NBC">
          </li>
          <li>
            <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-bloomberg.svg" alt="Bloomberg">
          </li>
          <li>
            <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-tmz.svg" alt="TMZ">
          </li>
          <li>
            <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-forbes.svg" alt="Forbes">
          </li>
          <li>
            <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-hubspot.svg" alt="Hubspot">
          </li>
          <li>
            <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-birchbox.svg" alt="Birchbox">
          </li>
        </ul>
      </b-container>
    </section>
    <section class="wb_about--leadership">
      <b-container>
        <div class="wb_header text-center">
          <h2 class="font-weight-bold">Our leadership</h2>
          <p>Leadership at Wibbitz comes from all over. Here is the team at the helm of the ship.</p>
        </div>
        <div class="about-leaders">
          <div class="about-leaders--item" v-for="pengurus in penguruses" :key="pengurus.id">
            <div class="img-wrap">
              <img :src="pengurus.user.image_link" alt="" data-rjs="2" class="card-img-top">
            </div>
            <h4 v-html="pengurus.user.name"></h4>
            <p class="text-tiny" v-html="pengurus.name"></p>
          </div>
        </div>

        <div class="bottom-link">
          <p>Interested in becoming a part of our team?</p>
          <p><a class="link-arrow" href="http://www.wibbitz.com/jobs/" target="_self">View open positions<img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/themes/wibbitz/assets/svg/arrow-right-blue.svg" alt="arrow-right"></a></p>
        </div>
      </b-container>
    </section>
    <section class="wb_about--thrive">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <div class="wb_header">
              <h2 class="font-weight-bold">How we thrive</h2>
              <p>We want to thrive, both at work and in our personal lives. There is a shared understanding of the common threads that help us be our best, and as we continue to invest in them, we continue to grow.</p>
              <p>These are the values that drive our daily decisions, develop our relationships, and guide our strategy:</p>
            </div>
          </div>
          <div class="col-md-6">
            <ul>
              <li>
                <div class="img-wrap">
                  <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/thrive-icon1.svg" alt="heart">
                </div>
                <h3>Be sincere</h3>
              </li>
              <li>
                <div class="img-wrap">
                  <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/thrive-icon2.svg" alt="together">
                </div>
                <h3>Stronger together</h3>
              </li>
              <li>
                <div class="img-wrap">
                  <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/thrive-icon3.svg" alt="risks">
                </div>
                <h3>Take intelligent risks</h3>
              </li>
              <li>
                <div class="img-wrap">
                  <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/thrive-icon4.svg" alt="expect">
                </div>
                <h3>Expect extraordinary</h3>
              </li>
              <li>
                <div class="img-wrap">
                  <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/thrive-icon6.svg" alt="keep it simple">
                </div>
                <h3>Keep it simple</h3>
              </li>
              <li>
                <div class="img-wrap">
                  <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/thrive-icon5.svg" alt="pause and play">
                </div>
                <h3>Pause and play</h3>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <section class="wb_about--news bg-gray">
      <div class="container">
        <div class="wb_header">
          <h2 class="font-weight-bold">Wibbitz<br>
            in the news</h2>
          <p><a class="link-arrow" href="http://www.wibbitz.com/press/" target="_self">Read More<img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/themes/wibbitz/assets/svg/arrow-right-blue.svg" alt="Read More"></a></p>
        </div>
        <div class="about-news">
          <div class="about-news--item">
            <div class="card">
              <div class="card-body">
                <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-techcrunch.svg" alt="Techcrunch">
                <h3>Automated video creation startup Wibbitz raises $20M in series C</h3>
                <p><a href="https://techcrunch.com/2017/10/23/wibbitz-series-c/" target="_blank" rel="noopener">Read Story</a></p>
              </div>
            </div>
          </div>
          <div class="about-news--item">
            <div class="card">
              <div class="card-body">
                <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-adweek.svg" alt="adweek">
                <h3>This Startup Is Helping Speed Up How Publishers and Advertisers Create Social Videos</h3>
                <p><a href="https://www.adweek.com/digital/this-startup-is-helping-speed-up-how-publishers-and-advertisers-create-social-videos/" target="_blank" rel="noopener">Read Story</a></p>
              </div>
            </div>
          </div>
          <div class="about-news--item">
            <div class="card">
              <div class="card-body">
                <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2019/12/logo-thenewyorktimes.svg" alt="the new york times">
                <h3>As Online Video Surges, Publishers Turn to Automation</h3>
                <p><a href="https://www.nytimes.com/2016/07/11/business/media/as-online-video-surges-publishers-turn-to-automation.html" target="_blank" rel="noopener">Read Story</a></p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
import axios from 'axios'
export default {
  data() {
    return {
      isLoaded : false,
      penguruses : []
    }
  },
  head: {
    title: "Sesepuh",
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Dibalik batu ada udang, dibalik IMAKA ada mereka yang selalu siap meluangkan waktu untuk menjadikan imaka organisasi yang bermanfaat bagi siapapun'
      },
      {
        hid: 'og:description',
        name: 'og:description',
        content: 'Dibalik batu ada udang, dibalik IMAKA ada mereka yang selalu siap meluangkan waktu untuk menjadikan imaka organisasi yang bermanfaat bagi siapapun'
      },
    ]
  },
  methods: {
    loadPengurus() {
      if(localStorage.penguruses) {
        this.penguruses = JSON.parse(localStorage.penguruses)
        this.isLoaded = true
      }
      axios.get('https://api.imaka.or.id/v2/pengurus')
        .then(res => {
          this.penguruses = res.data.datas
          localStorage.penguruses = JSON.stringify(this.penguruses)
          this.isLoaded = true
        })
        .catch(err => {
          console.log(err)
        })
    }
  },
  mounted() {
    this.loadPengurus()
  }
}
</script>
