

<script>
 // モーダルのVueインスタンス
var bus = new Vue({
     el: '#bussiness',
     data: {
       opened: false,
       isBlockChainActive: false,
       isHowToVrActive: false,
       isNotification: false,
       isBusinessAbout: false,
       isTechnicalAbout: false,
       show: false,
       hide: false,
     },
     methods: {
       open: function() {
         this.opened = true;
       },
       close: function() {
         this.opened = false;
       },
       blockChainActive: function() {
         this.isBlockChainActive = !this.isBlockChainActive;
       },
       howToVrActive: function() {
         this.isHowToVrActive = !this.isHowToVrActive;
       },
       notification: function() {
         this.isNotification = !this.isNotification;
       },
       businessAbout: function() {
         this.isBusinessAbout = !this.isBusinessAbout;
       },
       technicalAbout: function() {
         this.isTechnicalAbout = !this.isTechnicalAbout;
       },
     },
     created: function() {
       // 独自イベントclick.triggerを定義
       bus.$on('click.trigger', this.open);
     }
    });

</script>
