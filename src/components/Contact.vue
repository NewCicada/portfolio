<script setup lang="ts">

import SocialItem from './common/SocialItem.vue'

const contacts = [
  { 
    icon: 'akar-icons:github-fill', 
    text: 'Github',
    link: 'https://github.com/NewCicada',
    color: 'hover:bg-[#39d353]',
    desc:'GitHub'
  },
  {
    icon: 'bx:book-bookmark',
    text: '小红书',
    link: 'https://www.xiaohongshu.com/user/profile/5c285f87000000000703c1cc?xhsshare=CopyLink&appuid=5c285f87000000000703c1cc&apptime=1674649386',
    color: 'hover:bg-[#ff2442]',
    desc: '小红书'
  },
  {
    icon: 'ri:bilibili-fill',
    text: 'Bili',
    link: 'https://space.bilibili.com/113248991',
    color: 'hover:bg-[#fb7299]',
  },
  {
    icon:'entypo-social:sina-weibo',
    text:'微博',
    link: 'https://weibo.com/u/7301418284',
    color:'hover:bg-[#df6160]',
  },
  {
    icon: 'akar-icons:twitter-fill',
    text: 'twitter',
    link: 'https://twitter.com/newcicada1',
    color: 'hover:bg-[#00acee]',
  },
]
</script>

<template>
  <SocialItem :items="contacts" />
</template>
