

<script>
 // モーダルのVueインスタンス
var bus = new Vue({
     el: '#hello-world',
     data: {
       opened: false,
       isBlockChainActive: false
     },
     methods: {
       open: function() {
         this.opened = true;
       },
       close: function() {
         this.opened = false;
       },
       blockChainActive: function() {
         this.isBlockChainActive = this.isBlockChainActive == false
       },
     },
     created: function() {
       // 独自イベントclick.triggerを定義
       bus.$on('click.trigger', this.open);
     }
    });

</script>
