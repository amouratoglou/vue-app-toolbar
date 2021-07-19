<template>
  <v-app>
    <v-app-bar
      class="Header"
      absolute
      color="#fff"
      light
      dense
      shrink-on-scroll
      fade-img-on-scroll
    >
      <div class="logo">
        <a href="https://simplycodes.com/">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="173"
            height="32"
            viewBox="0 0 130 24"
            alt="Simply Codes"
            class="hidden sm:block"
            data-v-21c9f610=""
          >
            <g fill="none">
              <path
                fill="#10F24C"
                d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm0 6a6 6 0 110 12 6 6 0 010-12z"
              ></path>
              <path
                fill="#222"
                d="M39.994 13.856v-.52c0-1.63-.538-2.504-2.117-3.142l-3.41-1.36c-.891-.37-1.126-.79-1.126-1.496v-.269c0-.89.621-1.293 1.881-1.293h3.881c.168 0 .252-.101.252-.286V4.448c0-.15-.067-.235-.269-.268-1.327-.202-1.982-.286-3.376-.286-2.672 0-4.536.52-4.536 3.04v.387c0 1.613.42 2.621 1.78 3.125l3.63 1.428c.957.386 1.242.84 1.242 1.613v.285c0 .89-.621 1.26-1.864 1.26h-4.688c-.184 0-.268.084-.268.27v1.007c0 .185.067.269.235.303 1.495.218 2.822.302 4.133.302 2.637 0 4.62-.538 4.62-3.058zm2.571-7.812c.79 0 1.21-.42 1.21-1.159 0-.739-.42-1.159-1.21-1.159s-1.226.42-1.226 1.16c0 .738.437 1.158 1.226 1.158zm.756 10.786c.168 0 .252-.084.252-.252V7.792c0-.168-.084-.252-.252-.252h-1.529c-.168 0-.252.084-.252.252v8.786c0 .168.084.252.252.252h1.53zm4.05 0c.168 0 .252-.084.252-.252V9.22h1.428c1.428 0 1.848.084 1.848 2.25v5.108c0 .168.084.252.252.252h1.546c.151 0 .218-.067.218-.252l.034-5.14c0-.925-.084-1.597-.252-2.1a10.317 10.317 0 011.68-.135c1.461 0 1.848.117 1.848 2.604v4.771c0 .168.067.252.235.252h1.529c.168 0 .235-.084.235-.252l.034-5.41c.016-3.175-.941-3.73-3.713-3.73-.807 0-1.915.202-2.823.522-.604-.286-1.713-.504-2.89-.504-.806 0-2.1.084-2.99.268-.168.034-.252.068-.252.27v8.584c.017.168.084.252.252.252h1.53zm14.634 3.36c.168 0 .252-.084.252-.269v-3.108c.723.084 1.361.101 2.134.101 3.108 0 3.864-.991 3.864-4.805 0-3.679-.756-4.653-4.15-4.653-1.21 0-2.15.067-3.578.302-.202.034-.32.134-.32.336v11.827c0 .185.085.269.253.269h1.545zm2.067-5.057c-.538 0-1.244-.033-1.815-.1V9.22h1.915c1.865 0 2.05.655 2.05 2.956 0 2.403-.252 2.957-2.15 2.957zm7.695 1.697c.168 0 .252-.084.252-.252V4.23c0-.168-.084-.252-.252-.252h-1.529c-.168 0-.252.084-.252.252v12.348c0 .168.084.252.252.252h1.53zm6.285 3.444c3.41 0 3.981-1.058 3.998-3.982v-8.5c0-.168-.084-.252-.252-.252h-1.529c-.168 0-.252.084-.252.252v7.24c-.588.084-1.277.101-1.831.101-1.854 0-2.175-.538-2.184-2.853V7.792c0-.168-.084-.252-.252-.252h-1.529c-.168 0-.252.084-.252.252v4.67c0 3.394.79 4.452 3.898 4.452.79 0 1.428-.034 2.15-.151v.084c0 1.327-.403 1.73-2.083 1.73h-2.705c-.168 0-.235.067-.235.252v.991c0 .152.067.236.218.27.924.134 1.714.184 2.84.184zm11.072-3.36c1.277 0 2.386-.067 3.209-.202.201-.033.319-.15.319-.37v-1.058c0-.168-.084-.252-.252-.252h-3.276c-2.592 0-3.064-1.035-3.074-4.52v-.116c0-3.579.453-4.62 3.074-4.62H92.4c.168 0 .252-.084.252-.27V4.449c0-.218-.118-.319-.32-.352-.822-.152-1.931-.202-3.208-.202-4.183 0-5.258 1.462-5.258 6.502 0 5.023 1.075 6.518 5.258 6.518zm12.803-4.72c0-3.798-.74-4.738-4.1-4.738-3.326 0-4.067.922-4.082 4.624v.113c0 3.742.708 4.702 3.982 4.72l.1.001c3.36 0 4.1-.94 4.1-4.72zm-4.1 2.956c-1.77 0-2.041-.57-2.049-2.853v-.104c0-2.385.252-2.973 2.05-2.973 1.797 0 2.05.588 2.05 2.973 0 2.369-.253 2.957-2.05 2.957zm9.662 1.764c1.21 0 2.167-.067 3.595-.302.202-.034.302-.118.302-.353V4.247c0-.185-.067-.252-.252-.252h-1.528c-.168 0-.252.067-.252.252v3.31c-.555-.068-1.277-.101-2.15-.101-3.076 0-3.832.987-3.848 4.622v.115c0 3.763.74 4.721 4.133 4.721zm-.017-1.764c-1.87 0-2.077-.652-2.083-2.857v-.1c0-2.419.252-2.973 2.133-2.973h1.832v5.796c-.588.084-1.361.134-1.882.134zm9.644 1.764c1.076 0 2.117-.05 3.008-.185.15-.033.235-.1.235-.285v-1.042c0-.168-.084-.252-.252-.252h-2.873c-1.63 0-2.033-.403-2.083-2.184h5.325c.47 0 .572-.134.572-.454v-.504c-.034-3.645-.773-4.552-3.932-4.552-3.243 0-4 .921-4.015 4.623v.114c0 3.78.74 4.721 4.015 4.721zm1.882-5.41h-3.847c.017-1.814.403-2.284 1.965-2.284 1.496 0 1.865.47 1.882 2.284zm6.738 5.41c2.2 0 3.478-.437 3.478-2.352v-.218c0-1.042-.236-1.899-1.714-2.453l-2.2-.807c-.706-.268-.925-.588-.925-.99v-.202c0-.521.403-.74 1.109-.74h3.091c.185 0 .269-.084.269-.252v-.99c0-.152-.084-.236-.252-.27a17.216 17.216 0 00-2.62-.184c-2.1 0-3.613.42-3.613 2.25v.337c0 .991.37 1.999 1.68 2.47l2.218.84c.756.285.957.554.957.957v.168c0 .573-.335.715-1.393.722h-3.344c-.202 0-.269.084-.269.27v1.04c0 .152.05.236.252.253.554.05 1.814.151 3.276.151z"
              ></path>
            </g>
          </svg>
        </a>
      </div>
      <div class="Search" :class="{ closed: searchClosed }">
        <v-autocomplete
          class="expanding-search"
          fullWidth
          color="white"
          background-color="white"
          append-icon="mdi-magnify"
          rounded
          :placeholder="getPlaceHolder()"
          @focus="searchClosed = false"
          @blur="searchClosed = true"
          :dense="searchClosed ? true : false"
          :loading="isLoading"
          clearable
          solo-inverted
          item-text="name"
          item-value="id"
          :items="search ? merchants : initialMerchants"
          :search-input.sync="search"
          transition="scale-transition"
          flat
          filled
          hide-no-data
          hide-details
          return-object
          :menu-props="{
            contentClass: !search ? 'initialLayout' : '',
            minWidth: '760',
          }"
        >
          <template slot="prepend-item" v-if="isLoading && search">
            <v-sheet class="skeleton">
              <v-skeleton-loader
                v-bind="merchants"
                type="avatar, text, avatar, text, avatar, text, avatar, text, avatar, text"
              ></v-skeleton-loader>
            </v-sheet>
          </template>

          <div class="v-menu-footer" v-if="!search" slot="append-item">
            <a href="#">Explore by category</a>
          </div>

          <template v-slot:item="merchant">
            <v-list-item-avatar
              v-if="!isLoading"
              v-bind:style="{
                backgroundImage: 'url(' + merchant.item.logo + ')',
              }"
              :class="{ smallAvatar: search }"
            >
            </v-list-item-avatar>

            <v-list-item-content v-if="!isLoading">
              <v-list-item-title
                v-html="merchant.item.name"
              ></v-list-item-title>
              <div
                class="discount"
                v-if="merchant.item.bestCode && !search"
                v-html="
                  'Up to <strong>' +
                    merchant.item.bestCode.amountOff +
                    '% off</strong>'
                "
              ></div>
            </v-list-item-content>
          </template>
        </v-autocomplete>
      </div>
      <div class="menu-spacer"></div>
      <v-menu
        v-model="menu"
        :close-on-content-click="false"
        :nudge-width="200"
        class="nav-menu"
        offset-y
        rounded-pill
      >
        <template v-slot:activator="{ on, attrs }">
          <v-btn
            color="white"
            small
            rounded
            depressed
            light
            v-bind="attrs"
            v-on="on"
          >
            <div class="menu-container">
              <div class="Menu__hamburger mr-4" :class="{ menu_open: menu }">
                <div></div>
              </div>
            </div>
            <v-avatar size="30">
              <img
                src="https://lh3.googleusercontent.com/ogw/ADea4I4g8hbXwhXnDUi2IXfPKDvEa1NjaAXy4ZHT6uWhy5c=s83-c-mo"
                alt="Agu"
              />
            </v-avatar>
          </v-btn>
        </template>

        <v-card class="nav">
          <v-list>
            <v-list-item>
              <v-list-item-title
                ><p class="font-weight-bold">Settings</p></v-list-item-title
              >
            </v-list-item>
            <v-list-item>
              <v-list-item-title
                ><p class="font-weight-bold">Profile</p></v-list-item-title
              >
            </v-list-item>
            <v-list-item>
              <v-list-item-title
                ><p class="font-weight-bold">
                  Submit Coupons
                </p></v-list-item-title
              >
            </v-list-item>

            <v-divider></v-divider>

            <v-list-item>
              <v-list-item-title>Help</v-list-item-title>
            </v-list-item>
            <v-list-item>
              <v-list-item-title>Log out</v-list-item-title>
            </v-list-item>
          </v-list>
        </v-card>
      </v-menu>
    </v-app-bar>
  </v-app>
</template>

<script>
import _ from 'lodash';
import Axios from 'axios';

export default {
  name: 'App',
  data: function() {
    return {
      searchClosed: true,
      initialMerchants: [],
      merchants: [],
      isLoading: false,
      search: null,
      menu: false,
    };
  },
  methods: {
    getMerchants(params = '') {
      const requestData = params.length
        ? 'https://api.simplycodes.com/v1/merchants/search' + params
        : 'https://api.simplycodes.com/v1/merchants?limit=9';
      if (params.length) this.isLoading = true;
      Axios.get(requestData)
        .then((resp) => {
          if (!params.length) {
            this.initialMerchants = [...resp.data.merchants];
          } else {
            let tempMerchants = [
              ...this.merchants.slice(0),
              ...resp.data.merchants,
            ];
            this.merchants = _.uniqBy(tempMerchants, 'id');
            setTimeout(() => {
              this.isLoading = false;
            }, 900);
          }
        })
        .catch((e) => {
          console.error(e);
        });
    },
    resultsLayoutHandler() {
      if (!this.search) {
        return 'initialLayout';
      }
    },
    getPlaceHolder() {
      if (this.searchClosed) return 'Search stores';
      if (!this.searchClosed) return 'Try "StoreName"';
    },
    searchMerchants(query, queryType) {
      // query / limit
      let searchQuery = encodeURI('?' + queryType + '=' + query);
      this.getMerchants(searchQuery);
    },
  },
  watch: {
    search: _.debounce(function(query) {
      this.searchMerchants(query, 'query');
    }, 250),
  },
  created() {
    this.getMerchants();
  },
  mounted() {
    const inputField = document.querySelector('.v-input__icon--append');
    inputField.classList.remove('v-input__icon--append');
  },
};
</script>

<style>
.theme--light.v-application {
  background: #f7f7f7 !important;
}
body .v-application {
  font-family: 'Proxima Nova', sans-serif;
}
.Header {
  box-shadow: 0 1px 12px rgb(0 0 0 / 8%) !important;
}
.Search {
  width: 600px;
  margin: auto;
  transition: all 0.3s ease;
}
.v-toolbar__content .Search .v-input {
  box-shadow: 0 1px 2px rgb(0 0 0 / 8%), 0 4px 12px rgb(0 0 0 / 5%);
  transition: all 0.3s ease;
  border: 1px solid rgba(235, 235, 235);
}
.v-toolbar__content .Search .v-input:hover {
  box-shadow: 0 2px 4px rgb(0 0 0 / 18%);
  transition: all 0.3s ease;
}
body .v-toolbar--prominent .v-toolbar__content {
  align-items: center;
}
.v-toolbar__content .Search.closed {
  width: 365px !important;
  margin: auto;
  transition: all 0.3s ease;
}
.v-input__append-inner .v-input__icon {
  background: #635bff;
  border-radius: 100%;
}
.Menu__hamburger div {
  overflow: hidden;
  white-space: nowrap;
}
.menu-spacer {
  width: 85px;
}
.Search input::placeholder {
  opacity: 1;
  font-weight: normal;
  font-size: 15px;
  color: #979797 !important;
}
.Search.closed input::placeholder {
  font-weight: 600;
  font-size: 15px;
  color: #343434 !important;
}
body button.v-btn.v-btn--has-bg.theme--light.v-size--default.white {
  padding: 0 0 0 12px;
}
body .nav.v-card.v-sheet.theme--light .v-list-item:hover {
  background: #f1f1f1;
  transition: all 0.2s ease;
  cursor: pointer;
}
.nav .v-list-item__title {
  font-size: 15px;
  line-height: 20px !important;
  font-weight: 500;
}
.nav-menu.v-menu__content.theme--light.menuable__content__active {
  margin-top: 33px !important;
}
.closed .v-input__append-inner .v-input__icon {
  height: 34px !important;
  width: 34px !important;
  color: #fff;
  transition: all 0.5s ease;
}
.v-input__append-inner .v-input__icon {
  height: 48px !important;
  width: 48px !important;
  transition: all 0.5s ease;
}
.closed .v-input__icon i {
  font-size: 18px;
  transition: all 0.5s ease;
}
.v-input__icon i {
  font-size: 22px;
  transition: all 0.5s ease;
}
.mdi-close::before {
  content: '\F0156';
  font-size: 10px;
  background: rgba(235, 235, 235, 235);
  border-radius: 100px;
  padding: 5px;
  margin-right: 18 px;
}
.v-text-field--filled.v-input--dense > .v-input__control > .v-input__slot,
.v-text-field--full-width.v-input--dense > .v-input__control > .v-input__slot,
.v-text-field--outlined.v-input--dense > .v-input__control > .v-input__slot {
  min-height: 48px !important;
}
i.v-icon.notranslate.mdi.mdi-magnify.theme--light {
  color: #fff;
}
.v-list {
  padding: 34px;
}
.v-list-item__title p {
  margin-bottom: 0 !important;
}
.v-application a {
  color: #343434 !important;
  font-weight: 600;
  font-size: 18px;
}
.skeleton {
  width: 160px;
  margin-left: 15px;
}
.skeleton > div {
  margin-bottom: 15px;
  margin-left: 18px;
  margin-top: 18px;
}
.v-skeleton-loader__bone {
  margin-bottom: 11px;
}
.v-skeleton-loader--is-loading {
  overflow: hidden;
  display: grid !important;
  grid-template-columns: 50% 50%;
}
.v-skeleton-loader__text.v-skeleton-loader__bone {
  margin-top: 15px;
}
button.v-icon.notranslate.v-icon--link.mdi.mdi-close.theme--light.white--text {
  color: #111 !important;
}
.v-input__icon.v-input__icon--clear {
  background: #fff !important;
}
.v-menu__content.theme--light.menuable__content__active {
  width: 240px;
  box-shadow: 0 10px 35px 0 rgb(0 0 0 / 15%);
  margin-top: 25px !important;
}
.Search .v-menu__content.theme--light.menuable__content__active {
  top: 71px;
}
.v-toolbar__content,
.v-toolbar__extension {
  padding: 0 !important;
}
.v-autocomplete__content.initialLayout > div {
  display: flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 0;
}
.v-menu-footer {
  width: 100%;
}
.v-menu__content.theme--light.menuable__content__active.v-autocomplete__content {
  max-height: 500px !important;
  height: 500px !important;
}
.v-menu__content.theme--light.menuable__content__active.v-autocomplete__content.initialLayout {
  max-height: 600px !important;
  height: auto !important;
}
.v-menu__content.theme--light.menuable__content__active.v-autocomplete__content.initialLayout {
  padding-top: 20px !important;
}
.v-menu__content.theme--light.menuable__content__active.v-autocomplete__content {
  padding-top: 0 !important;
}
.v-autocomplete__content
  .theme--light.v-list-item:not(.v-list-item--active):not(.v-list-item--disabled) {
  border-radius: 6px !important;
  overflow: hidden;
  margin-bottom: 20px;
  margin-top: 20px;
}
.initialLayout .v-list .v-list-item {
  max-width: 30%;
  flex-grow: 1;
  box-sizing: border-box;
  justify-content: space-between;
  align-items: center;
  display: flex;
  flex: 1 1 100%;
  letter-spacing: normal;
  min-height: 48px;
  outline: none;
  padding-top: 0 !important;
  padding-bottom: 0 !important;
  padding-left: 11px !important;
  padding-right: 11px !important;
  position: relative;
  text-decoration: none;
  margin-left: 7px !important;
  margin-right: 7px !important;
}
.v-autocomplete__content .v-list-item__title {
  font-size: 21px !important;
  font-weight: 400 !important;
  margin-left: 16px;
  line-height: auto !important;
}
.v-autocomplete__content.initialLayout .v-list-item__title {
  font-size: 18px !important;
  margin-bottom: 10px !important;
  font-weight: normal !important;
  letter-spacing: -0.25px;
  line-height: 20px;
  margin-left: 0;
}
#app .v-autocomplete__content .v-list-item {
  min-height: auto;
  margin-left: 0;
  margin-right: 0;
  padding-left: 35px;
  margin-bottom: 0;
}
#app .v-autocomplete__content .v-avatar.v-list-item__avatar {
  display: inline-block;
  background-size: 100%;
  background-position: center;
  cursor: pointer;
  border: 1px solid #ebebeb;
  border-radius: 9999px;
  border-width: 1px;
  width: 48px !important;
  height: 48px !important;
  min-width: auto !important;
}
#app .v-btn:not(.v-btn--round).v-size--default {
  height: 58px;
  min-width: 64px;
  border-radius: 41px;
  padding: 5px 5px 5px 12px;
  position: relative;
  transition: box-shadow 0.2s ease;
  border: 1px solid #ebebeb;
}
.v-btn:not(.v-btn--round).v-size--small::before,
.v-btn:not(.v-btn--round).v-size--small:hover,
.v-btn:not(.v-btn--round).v-size--small:focus {
  color: transparent;
}
.v-btn:not(.v-btn--round).v-size--small {
  height: 40px !important;
  min-width: 50px;
  padding: 17px 8.444444px !important;
  border: 1px solid #ebebeb !important;
}
.v-btn:hover {
  box-shadow: 0 2px 4px rgb(0 0 0 / 18%);
  transition: box-shadow 0.2s ease;
}
.v-menu__content.theme--light.menuable__content__active.v-autocomplete__content.initialLayout:before {
  content: 'Popular Stores';
  font-weight: bold;
  text-transform: uppercase;
  padding-left: 18px;
  font-size: 13px;
  display: inline-block;
}
.v-btn__content .v-avatar {
  width: 36px;
  height: 36px;
}
.v-toolbar__content {
  margin: auto;
  box-sizing: inherit;
  border: 0 solid #ebebeb;
  margin-left: auto;
  margin-right: auto;
  padding-left: 80px;
  padding-right: 80px;
  align-items: center;
  justify-content: space-between;
  display: flex;
  height: 80px;
  max-width: 1120px;
}
.v-btn:hover {
  box-shadow: 0 2px 4px rgb(0 0 0 / 18%);
  transition: box-shadow 0.2s ease;
  background: #fff;
}
.v-icon.v-icon {
  font-size: 18px;
}
.v-menu-footer {
  background: #f7f7f7;
  padding: 20px;
  margin-top: 30px;
  text-align: center;
}
.v-input__slot.white {
  padding-right: 7px !important;
}
.v-select__selection,
.v-select__selection--comma,
.v-select.v-text-field input {
  color: #111 !important;
}
.notranslate {
  transform: none !important;
}
.expanding-search {
  color: #111;
}
h4 {
  margin-bottom: 19px;
}
.Search input {
  cursor: pointer;
}
.v-menu__content.theme--light.menuable__content__active.v-autocomplete__content {
  padding: 30px 0 0 0;
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 1px 12px rgb(0 0 0 / 8%);
  left: 0 !important;
  right: 0;
  margin: 24px auto;
}
#app .Menu {
  border-radius: 24px;
  padding: 0;
  position: relative;
  display: flex;
  transition: box-shadow 0.2s ease;
}
.Menu__hamburger {
  display: flex;
  position: relative;
  width: 18px;
  height: 18px;
  cursor: pointer;
  pointer-events: all;
  background: transparent;
  outline: none;
}
.Menu__hamburger.menu_open:before {
  transform: translateY(2px) rotate(135deg);
}
.Menu__hamburger.menu_open:after {
  transform: translateY(-2px) rotate(45deg);
}
.Menu__hamburger:after,
.Menu__hamburger:before {
  content: '';
  position: absolute;
  top: 6px;
  left: 0;
  width: 18px;
  height: 2px;
  background: #000;
  transition: transform 0.3s ease-out;
}
.Menu__hamburger:after {
  top: auto !important;
  bottom: 6px !important;
}
#app .v-avatar.v-list-item__avatar.smallAvatar {
  width: 40px;
  height: 40px;
  min-width: auto;
}
</style>
