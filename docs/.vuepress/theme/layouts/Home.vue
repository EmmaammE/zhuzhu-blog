<template>
  <div class="container">
    <div class="divider divider-top"></div>

    <main class="main">
      <div class="box">
        <h1 class="title">Zhuzhu's <br> Blog</h1>
        <!-- <img class="title-append-icon"
          :src="$withBase('/piggy.png')" alt="piggy"> -->

        <svg class="icon" viewBox="0 0 1024 1024" 
          version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="1419" width="45" height="45">
          <path d="M173.056 696.32m-32.768 0a32.768 32.768 0 1 0 65.536 0 32.768 32.768 0 1 0-65.536 0Z" p-id="1420"></path>
          <path d="M961.536 530.432l-4.096-44.032-11.264 4.096-24.576 10.24c-2.048 0-7.168 1.024-17.408 2.048h-1.024c-2.048-5.12-4.096-11.264-5.12-15.36-2.048-7.168-5.12-15.36-8.192-25.6-13.312-39.936-28.672-70.656-39.936-94.208l-8.192-16.384c0-2.048 1.024-4.096 3.072-9.216 5.12-12.288 12.288-29.696 4.096-48.128-9.216-22.528-30.72-35.84-58.368-35.84-3.072 0-6.144 0-10.24 1.024-7.168 1.024-18.432 2.048-27.648 4.096-10.24-6.144-29.696-18.432-46.08-26.624-6.144-3.072-20.48-10.24-41.984-17.408-14.336-70.656-76.8-121.856-149.504-121.856-69.632 0-131.072 48.128-147.456 114.688h-2.048C226.304 243.712 160.768 337.92 131.072 409.6c-2.048-4.096-5.12-8.192-12.288-10.24-2.048-1.024-4.096-1.024-6.144-1.024-12.288 0-27.648 9.216-31.744 55.296-1.024 11.264-2.048 17.408-2.048 22.528h-1.024v9.216c0 8.192-2.048 78.848 39.936 99.328V614.4c1.024 17.408 15.36 30.72 32.768 30.72 18.432 0 32.768-14.336 32.768-32.768 0-6.144 0-11.264-1.024-16.384 0-22.528-1.024-54.272-25.6-66.56 7.168-7.168 14.336-18.432 16.384-37.888 0-2.048 26.624-164.864 192.512-210.944 1.024 6.144 3.072 13.312 5.12 19.456-14.336 9.216-24.576 19.456-32.768 29.696l-8.192 11.264c-4.096 5.12-7.168 12.288-7.168 19.456 0 18.432 14.336 32.768 32.768 32.768 10.24 0 20.48-5.12 25.6-13.312L389.12 368.64c19.456-24.576 70.656-43.008 123.904-43.008 54.272 0 105.472 17.408 123.904 43.008l8.192 11.264c6.144 7.168 15.36 12.288 25.6 12.288 18.432 0 32.768-14.336 32.768-32.768 0-7.168-2.048-13.312-6.144-18.432l-8.192-11.264c-8.192-10.24-19.456-20.48-32.768-29.696 1.024-4.096 2.048-7.168 3.072-11.264 6.144 3.072 11.264 5.12 15.36 7.168 17.408 8.192 41.984 24.576 50.176 29.696l10.24 7.168 12.288-2.048s15.36-2.048 29.696-4.096c-5.12 12.288-9.216 29.696-2.048 47.104 3.072 7.168 7.168 15.36 12.288 26.624 10.24 20.48 23.552 48.128 35.84 83.968 3.072 9.216 6.144 17.408 8.192 24.576 10.24 31.744 19.456 61.44 62.464 61.44 0 26.624-2.048 47.104-7.168 58.368-8.192 19.456-25.6 24.576-26.624 24.576l-59.392 14.336 25.6 23.552c-10.24 7.168-17.408 16.384-24.576 24.576-9.216 10.24-18.432 22.528-36.864 34.816-32.768 22.528-46.08 41.984-49.152 47.104l-4.096 11.264 4.096 13.312c3.072 9.216 5.12 19.456 7.168 28.672-14.336 1.024-32.768 2.048-52.224 2.048h-8.192c-11.264-14.336-20.48-23.552-30.72-27.648-6.144-2.048-11.264-4.096-18.432-4.096-5.12 0-11.264 1.024-18.432 2.048-14.336 2.048-41.984 5.12-94.208 5.12h-7.168c-51.2 0-82.944-4.096-101.376-6.144-10.24-1.024-17.408-2.048-23.552-2.048-10.24 0-18.432 2.048-25.6 7.168-5.12 4.096-10.24 8.192-17.408 14.336-2.048 2.048-4.096 4.096-6.144 5.12-6.144 1.024-15.36 1.024-25.6 1.024-15.36 0-30.72-1.024-40.96-2.048 0-6.144 1.024-12.288 2.048-17.408 1.024-13.312 3.072-26.624 2.048-37.888-1.024-10.24-5.12-20.48-11.264-32.768-5.12-10.24-16.384-17.408-28.672-17.408-18.432 0-32.768 14.336-32.768 32.768 0 5.12 2.048 11.264 4.096 15.36 2.048 3.072 3.072 5.12 3.072 6.144 0 6.144-1.024 17.408-2.048 27.648-2.048 19.456-4.096 37.888 0 52.224 2.048 8.192 8.192 20.48 24.576 28.672 20.48 10.24 61.44 11.264 77.824 11.264 13.312 0 44.032-1.024 56.32-6.144 8.192-4.096 16.384-11.264 24.576-19.456l2.048-2.048c3.072 0 8.192 1.024 12.288 1.024 20.48 2.048 54.272 6.144 108.544 6.144h8.192c56.32 0 86.016-4.096 103.424-6.144h2.048c3.072 4.096 7.168 9.216 10.24 14.336l9.216 15.36h51.2c91.136 0 108.544-10.24 113.664-35.84 3.072-11.264 0-31.744-8.192-62.464 5.12-5.12 11.264-10.24 21.504-17.408 24.576-17.408 38.912-33.792 50.176-46.08 11.264-13.312 13.312-14.336 16.384-14.336 28.672-4.096 37.888-22.528 39.936-29.696 1.024-4.096 2.048-9.216 2.048-13.312 12.288-9.216 27.648-23.552 36.864-46.08 15.36-39.936 10.24-108.544 9.216-121.856zM600.064 272.384c-26.624-8.192-55.296-11.264-83.968-11.264-28.672 0-57.344 4.096-82.944 11.264-2.048-8.192-3.072-15.36-3.072-23.552 0-48.128 38.912-87.04 87.04-87.04s87.04 38.912 87.04 87.04c-1.024 8.192-2.048 16.384-4.096 23.552z" p-id="1421"></path>
          <path d="M732.16 496.64m-47.104 0a47.104 47.104 0 1 0 94.208 0 47.104 47.104 0 1 0-94.208 0Z" p-id="1422"></path>
        </svg>

        <barnsley-fern />
      </div>

      <div class="menu">
        <nav class="level-1">
          <ul class="inner">
            <li
              v-for="(menu, i) in menus"
              :key="i"
              :class="`menu-tab ${(i===activeIndex)?'active':''}`"
              @click="changeMenu(i)"
            >
              {{menu}}
            </li>
          </ul>
        </nav>
        <div class="level-2">
            <div class="inner">
            <!-- <div class="post-card" v-for="n of 5" :key="n">
              <div class="page-detail">
                <div class="page-title">XXXX</div>
                <div class="page-description"> tttttttttttttttttttttttttttttttttttttt</div>
              </div>
            </div> -->
            <router-link v-for="page in pages" :to="page.path">
              <div class="post-card">
                <ul class="page-detail">
                  <li>{{ page.title }}
                    
                    <div>{{ page.frontmatter.description }}</div>
                  </li>
                </ul>
              </div>
            </router-link>
          </div>
        </div>
      </div>
    </main>

    <div class="divider divider-down"></div>
  </div>
</template>

<script>
import BarnsleyFern from '../components/barnsleyFern/BarnsleyFern.vue'

export default {

  components: {
    BarnsleyFern,
  },

  mounted() {
    console.log(this.$frontmatter)
    console.log(this.$site)
  },

  data() {
    return {
      activeIndex: 0,
    }
  },

  computed: {
    menus() {
      // get "menus" from frontmatter
      return this.$frontmatter.menus;
    },

    pages() {
      const currentTab = this.menus[this.activeIndex];
      console.log(currentTab)

      return this.$site.pages.filter(page => page.frontmatter.type === currentTab)
    }
  },

  methods: {
    changeMenu(index) {
      console.log(index);
      this.activeIndex = index;
    }
  }

}
</script>

<style scoped lang="scss">
  body {
    overflow: hidden;
  }
  
  h1, h2, h3, h4, h5, h6 {
    font-family: 'Sacramento', cursive;
  }
  
  .container {
    display: flex;
    flex-direction: column;
    padding: 40px;
    justify-content: space-between;
    height: 85vh;

    // box-shadow: 0 -5px 0 #fff, 0 1px 6px rgba(0,0,0, .35);
    box-shadow: 0 -5px 0 #fff, 0 1px 6px rgba(0, 0, 0, 0.2),
      inset 0 0 50px rgba(#b09174, 0.2);

    .divider {
      width: 100%;
      height: 5px;
     
      &.divider-down {
        border-top: 1px solid #000;
        border-bottom: 2px solid #000;
      }

      &.divider-top {
        border-top: 2px solid #000;
        border-bottom: 1px solid #000;
      }
    }

    // title
    .title {
      font-size: 100px;
      font-weight: 200;
      text-indent: 80px;
      line-height: 90px;
    }
    .title-append-icon {
      height: 30px;
    }

    .icon {
      // path {
      //   stroke-dasharray: 3000 0;
      //   stroke-dashoffset: 3000;
      // }
    }

    .main {
      display: flex;
      flex-grow: 1;

      .box {
        flex: 0 0 55%;
        display: flex;
        justify-content: center;
        align-items: center;
        position: relative;
      }

      .menu {
        display: flex;
        height: 85vh;
        flex: 0 0 45%;

        .level-1 {
          flex: 0 0 35%;
          padding: 20% 5%;
          border-width: 2px;
          border-style: solid;
          border-image: linear-gradient(
            to bottom,
            #fff 10%,
            rgba(0,0,0,1) 45%,
            rgba(0,0,0,1) 55%,
            #fff 90%
          ) 1;

          .inner {
            list-style: none;
            padding: 0;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            align-items: center;
            mask-image: linear-gradient(90deg, rgba(83, 79, 79, 0) 0%, #ffffff 25%, #ffffff 75%, rgba(255, 255, 255, 0) 100%);
          
            // menu tab
            .menu-tab {
              font-size: 24px;
              text-align: center;
              line-height: 45px;
              width: 100%;
              border-bottom: 1px solid #000;
              box-shadow:  0 5px 5px -3px rgba($color: #b09174, $alpha: 0.3), 
                0 20px 20px -10px rgba($color: #b09174, $alpha: 0.3);
              cursor: pointer;
              transition: all cubic-bezier(0.175, 0.885, 0.32, 1.275) 300ms;

              &:hover {
                transform: translateY(-10px);
              }

              &.active {
                color: #b09174;
              }
            }
          }
        }

        .level-2 {
          flex: 1 0 35%;
          padding: 10% 10px;
          background: #f8f5f2;
          mask-image: linear-gradient(90deg, rgba(83, 79, 79, 0) 0%, #ffffff 25%, #ffffff 75%, rgba(255, 255, 255, 0) 100%);

          .inner {
            max-height: 85vh;
            height: 85vh;
            overflow: auto;
            border-image: linear-gradient(
              to bottom,
              #fff 0%,
              rgba(0,0,0,1) 45%,
              rgba(0,0,0,1) 55%,
              #fff 100%
            ) 1;
            border-width: 0 2px 0 0;
            border-style: solid;

            .post-card {
              margin: 10px 0;
              padding: 20px;
              cursor: pointer;
              color: #000;

              // post-list
              ul {
                counter-reset: index;  
                padding: 0;
                max-width: 300px;
              }

              /* List element */
              li {
                counter-increment: index; 
                display: -webkit-box; 
                display: flex;
                -webkit-box-align: center;
                        align-items: center;
                padding: 12px 0;
                box-sizing: border-box;
                border-bottom: 1px solid;
              }


              /* Element counter */
              li::before {
                content: counters(index, ".", decimal-leading-zero);
                font-size: 1.5rem;
                text-align: right;
                font-weight: bold;
                min-width: 50px;
                padding-right: 12px;
                align-self: flex-start;
                background-image: linear-gradient(to bottom, #b09174, orangered);
                background-attachment: fixed;
                -webkit-background-clip: text;
                -webkit-text-fill-color: transparent;
              }


              /* Element separation */
              li + li {
                border-top: 1px solid rgba(255,255,255,0.2);
              }

            }
          }

          a {
            text-decoration: none;
          }
        }
      }
    }
  }
</style>