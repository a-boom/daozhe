<template>

  	<header class="header">
		<a class="header-left ><</a>
		<div class="header-title">
			<span class="single-line"><span class="iconfont"></span>输入城市/景点/游玩主题</span>
		</div>
		<div class="header-right">
			<span class="nav-city">北京
				<i class="downarrow"></i>
			</span>
		</div>
	</header>

</template>

<script>

export default {
	data () {
	    return {

	    }
	}
}
</script>

<style scoped>
	
	.header {
		position: relative;
	    overflow: hidden;
	    width: 100%;
	    height: 2rem;
	    background: #00bcd4;
	    text-align: center;
	    color: #fff;
	}
	.header-left {
		float: left;
	    display: block;
	    width: .4rem;
	    line-height: 2rem;
	    padding: 0 .2rem;
	    color: #fff;
	    font-size: .66rem;
	    text-align: left;
	}
	.header-title {
	    position: relative;
	    height: 1.6rem;
	    margin: .14rem 1.6rem .14rem .6rem;
	    background: #fff;
	    line-height: 1.6rem;
	    border-radius: .6rem;
	}
	.header-right{
		position: absolute;
		top: 0;
		right: 0;
		line-height: 2rem;
		width: 1.5rem;
		text-align: center;
	}
	.single-line {
		color: #ccc;
	}
</style>
