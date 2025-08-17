# This project is inspired by https://demian.wang/2023/12/30/%E7%AE%80%E5%8C%96B%E7%AB%99UI-%E8%8A%82%E7%BA%A6%E7%B2%BE%E5%8A%9B/
# Simply paste the code section below into the Stylish plugin to remove all distractions from your Bilibili home page.
<img width="868" height="605" alt="image" src="https://github.com/user-attachments/assets/57b9d7f3-11f5-4198-ba1a-b647542abc40" />


/* 屏蔽搜索热搜 */
.trending {
  display: none !important;
}

.nav-search-input::-webkit-input-placeholder {
    opacity: 0; /* Makes the placeholder invisible */
}

.nav-search-input::-moz-placeholder {
    opacity: 0; /* For Firefox */
}

.nav-search-input:-ms-input-placeholder {
    opacity: 0; /* For IE10-11 */
}

.nav-search-input::placeholder {
    opacity: 0; /* Standard syntax */
}

/* 屏蔽导航栏 */
#bili-header-container,
.bili-header,
.bili-header__bar,
#app #biliMainHeader {
  display: none !important;
}

/* 屏蔽底部 */
#biliMainFooter {
  display: none !important;
}

.nav-search-input::placeholder {
    color: transparent;
}
/* 工具栏可视 */
#i_cecream .bili-header,
#i_cecream .bili-header__bar {
  display: block !important;
}

/* 调整搜索栏样式 */
.bili-header__bar {
  background: var(--graph_bg_regular);
}

#nav-searchform {
  margin-top: 50vh;
  transform: translateY(-50%);
  background-color: white !important;
}

/* 屏蔽干扰项 */
.left-entry,
.trending,
.right-entry,
.bili-header__banner,
.bili-header__channel,
.header-channel,
.bili-feed4-layout,
.palette-button-wrap {
  display: none !important;
}

.recommend-list-v1 {
  display: none !important;
}

/* 屏蔽个人信息banner */
.h {
  display: none !important;
}

/* 屏蔽个人空间导航*/
 #navigator {
	display: none !important;
} 

/* 收藏页的左侧导航*/
 .fav-sidenav {
	display: none !important;
} 
/* Chrome, Safari, Edge, Opera */
.nav-search-input::-webkit-input-placeholder {
    color: transparent !important;
}

/* Firefox 19+ */
.nav-search-input::-moz-placeholder {
    color: transparent !important;
}

/* Internet Explorer 10-11 */
.nav-search-input:-ms-input-placeholder {
    color: transparent !important;
}

/* Standard syntax */
.nav-search-input::placeholder {
    color: transparent !important;
}
/* 屏蔽广告 */
.ad-report,
.video-page-special-card-small {
  display: none !important;
}
