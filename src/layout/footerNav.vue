<template>
	 <div class='footer'>
        <p class="intro rflex">
            <span>{{ $t('commons.author') }}Admin</span>
        </p>
        <p class="beian" hidden>xxxxxxxxxx号</p>
    </div>
</template>


<script>


export default {
    name: "footerNav",
	data(){
		return {
		}
	},
	methods:{

	}
}
</script>

<style lang="less">
	.footer{
        width: 100%;
        padding: 10px 0;
        font-size:12px;
        text-align: center;
        background: #fff;
        p{
            line-height: 30px;
        }
        .intro{
            width: 240px;
            margin: 0 auto;
            justify-content: space-between;
            align-items: center;
        }
    }
</style>


