<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
/*每个页面公共css uParse为优化版本*/
@import './common/app.css';
@import './common/app-extend.css';
@import './common/custom.css';
@import './static/style/thorui-extend.css';
/* #ifndef APP-NVUE */
@import './components/uni/uParse/src/wxParse.css';
/* #endif */
</style>
