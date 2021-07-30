<template>
	<view class="account-total">
		<!-- 选择转账方式 -->
		<view class="account">
			<view class="style">
				选择转账方式
			</view>
		</view>
		<!-- 转账方式 -->
		<view class="transfer-style clearfix">
			<view class="style-left fl">
				转账方式
			</view>
			<view class="style-right-first fl">
				<view  class="private">
					对私转账	
				</view>
			</view>
			<view class="style-right-second fl">
				<view  class="public">
					对公转账
				</view>
			</view>
		</view>
		<!-- 收款账户 -->
		<view class="get-account">
			<text class="get-title">收款账户</text>
		</view>
		<!-- 收款账户内容 -->
		  <!-- 开户行 -->
		  <view class="open-account clearfix">
			<!-- 开户 -->
			  <view class="open-account-left fl">
				  开户行
			  </view>
		  	<!-- 属于什么银行 -->
			<view class="bank-style fl">
				建行银行
			</view>
			<!-- 内容的复制 -->
			<view class="content-copy fr">
				复制	
			</view>
		  </view>
		  <!-- 虚线 -->
		  <view class="line">
		  </view>
		  <!-- 银行卡号 -->
		  <view class="open-account clearfix">
		  			<!-- 银行卡号-->
		  			  <view class="open-account-left fl">
		  				  银行卡号
		  			  </view>
		  	<!-- 银行卡号数字 -->
		  			<view class="bank-style fl">
		  				8291 8391 7381 891
		  			</view>
		  			<!-- 内容的复制 -->
		  			<view class="content-copy fr">
		  				复制	
		  			</view>	
		  </view>
		  <view class="line">
		  </view>
		  <!-- 账户信息 -->
		  <view class="open-account clearfix">
		  			<!-- 信息栏目-->
		  			  <view class="open-account-left fl">
		  				  姓名
		  			  </view>
		  	<!-- 名字 -->
		  			<view class="bank-style fl">
		  				橘子不是子
		  			</view>
		  			<!-- 内容的复制 -->
		  			<view class="content-copy fr">
		  				复制	
		  			</view>		  			
		  </view>
		  <!-- 转账凭证 -->
		  <view class="send-account">
		  	 <text class="send-account-title">转账凭证</text>
		  </view>
		  <!-- 添加转账凭证 -->
		  <view class="add-account">
		  	<image src="../../static/添加.png" mode="" class="add"></image>
		    <view class="add-title">
		    	添加转账凭证
		    </view>
		  </view>
		  <!-- 提交按钮 -->
		  <view class="submit clearfix">
		  	 <view class="submit-title fl">
				 提交	
		  	 </view>
		  </view>
	</view>
</template>

<script>
	export default {
		data() {

		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="less">
	.account-total {
		background: #F3F3F3;
		.fl {
			float: left;
		}

		.fr {
			float: right;
		}

		.clearfix:after {
			clear: both;
			content: '';
			display: block;
			font-size: 0;
			line-height: 0;
			visibility: hidden;
			width: 0;
			height: 0;
		}

		.account {
			background: #F3F3F3;

			.style {
				width: 156rpx;
				height: 36rpx;
				font-size: 26rpx;
				font-family: PingFangSC-Regular, PingFang SC;
				font-weight: 400;
				color: rgba(31, 31, 31, 0.4);
				line-height: 36rpx;
				margin-left: 32rpx;
				padding: 18rpx 0;
			}
		}

		.transfer-style {
			width: 750rpx;
			height: 112rpx;
			background: #FFFFFF;

			.style-left {
				float: left;
				width: 136rpx;
				height: 48rpx;
				font-size: 28rpx;
				font-family: PingFangSC-Regular, PingFang SC;
				font-weight: 400;
				color: #1F1F1F;
				line-height: 48rpx;
				margin-top: 32rpx;
				margin-left: 32rpx;
			}

			.style-right-first {
				float: left;
				width: 120rpx;
				height: 40rpx;
				background: #F3F3F3;
				border-radius: 4rpx;
				margin-left: 272rpx;
				margin-top: 36rpx;

				.private {
					width: 96rpx;
					height: 24rpx;
					font-size: 24rpx;
					font-family: PingFangSC-Regular, PingFang SC;
					font-weight: 400;
					color: #9F9F9F;
					line-height: 24rpx;
					margin: 8rpx 12rpx;
				}

			}

			.style-right-second {
				float: right;
				width: 146rpx;
				height: 40rpx;
				background: #087CB2;
				border-radius: 4rpx;
				margin-right: 20rpx;
				margin-top: 36rpx;

				.public {
					width: 96rpx;
					height: 24rpx;
					font-size: 24rpx;
					font-family: PingFangSC-Semibold, PingFang SC;
					font-weight: 600;
					color: #FFFFFF;
					line-height: 24rpx;
					margin-left: 12rpx;
					margin-top: 8rpx;


				}
			}
		}

		.get-account ,.send-account{
			padding: 18rpx 0;
			.get-title , .send-account-title{
				margin-left: 32rpx;
				width: 104rpx;
				height: 36rpx;
				font-size: 26rpx;
				font-family: PingFangSC-Regular, PingFang SC;
				font-weight: 400;
				color: rgba(31, 31, 31, 0.4);
				line-height: 36rpx;
			}

		}
		.open-account {
			width: 750rpx;
			height: 112rpx;
			background: #FFFFFF;
			.open-account-left {
				width: 136rpx;
				float: left;
				height: 48rpx;
				font-size: 28rpx;
				font-family: PingFangSC-Regular, PingFang SC;
				font-weight: 400;
				color: #1F1F1F;
				line-height: 48rpx;
				margin-top: 32rpx;
				margin-left: 32rpx;
			}
			.bank-style {
				float: left;	
				height: 28rpx;
				font-size: 28rpx;
				font-family: PingFangSC-Regular, PingFang SC;
				font-weight: 400;
				color: #1F1F1F;
				line-height: 28rpx;
				margin-top: 42rpx;
				margin-left: 16rpx;
				
			}
			.content-copy {
				float: right;
				width: 56rpx;
				font-size: 28rpx;
				font-family: PingFangSC-Regular, PingFang SC;
				font-weight: 400;
				color: #3296FA;
				line-height: 112rpx;
				margin-right: 32rpx;
			}
		}
        .line {
			width: 718rpx;
			height: 2rpx;
			background: rgba(31, 31, 31, 0.09);
			margin-left: 32rpx;
		}
		.add-account {
			height: 374rpx;
			background: #FFFFFF;
			.add {
				width: 44rpx;
				height: 44rpx;
				margin-top: 134rpx;
				margin-left: 352rpx;
			
			}
			.add-title {
				width: 192rpx;
				height: 44rpx;
				font-size: 32rpx;
				font-family: PingFangSC-Regular, PingFang SC;
				font-weight: 400;
				color: #087CB2;
				line-height: 44rpx;
				margin-top: 28rpx;
				margin-left: 280rpx;
			}
		}
		.submit {
			width: 690rpx;
			height: 72rpx;
			background: linear-gradient(180deg, #3AC0FF 0%, rgba(58, 192, 255, 0) 100%) #087CB2;
			border-radius: 16rpx;
			margin-left: 30rpx;
			margin-top: 262rpx;
			.submit-title {
				float: left;
				width: 64rpx;
				height: 44rpx;
				font-size: 32rpx;
				font-family: PingFangSC-Medium, PingFang SC;
				font-weight: 500;
				color: #FFFFFF;
				line-height: 44rpx;
				margin-top: 14rpx;
				margin-left: 314rpx;
			}
		}
	}
</style>
