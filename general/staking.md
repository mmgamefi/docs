# 质押

自成立以来，Tornado Cash用户使用TORN代币进行治理。它的主要用途是允许在链上（通过锁定的TORN来治理提案）和链下（在快照上）提出提案和投票。

自 [Tornado Cash 的治理提案#10](https://tornadocash.eth.link/governance/10)执行以来，TORN代币获得了另一个有用的效用。**随着去中心化中继器注册表的引入，TORN的持有者只要将TORN锁入到治理合约中，就能获得了质押奖励。**

[TORN](torn.md)的持有者仍然可以将他们的代币锁入到治理合约中，就像他们过去用于投票治理一样。显著的区别在于，他们现在能够从中继者那里获得奖励（协议收取的费用）。显然，奖励的比例将同他们锁入的TORN数量成正比。

#### 这些收取的费用从哪里来？

这些费用的收取是通过实施去中心化的中继器注册表来实现的。为了在协议UI上列出中继器，中继器需要质押一定数量的TORN（目前由治理设置`300个TORN`）。此中继器注册表的功能[在此论坛帖子](https://torn.community/t/proposal-relayer-registry-setting-parameters-after-audit/2134) 和 [中继器注册表文档页面](how-to-become-a-relayer.md)上有详细的解释。

简而言之，用户通过中继器进行提款，所选中继器必须从质押余额中向协议支付费用（且需保持在 `300个TORN` 阈值以上）。目前，该费用为提款金额的 `0.3%` （已由治理确定），可以通过链上提案和投票随时更改。

### 如何质押TORN代币？

如上所述，锁入TORN代币的流程保持不变。

* 在这里➡️[https://tornadocash.eth.link/governance](https://tornadocash.eth.link/governance)⬅️，点击 **`管理`**，然后在 **`锁入`** 标签
* 治理合约需要获得批准才能将您的代币转移到智能合约。为此，您需要单击 **`批准`** 按钮
* 确认批准后，您可以输入要锁入的代币数量，然后点击 **`锁入`**
* 之后您要做的就是确认钱包中的交易并等待确认通过

![](../.gitbook/assets/c05e5a1813edad280544b627b24002dc8d5adcf2.png)

### 如何领取您的质押奖励？

既然您的TORN代币已经成功锁入在治理合约中，您就能领取您的质押奖励。怎么做呢？都在这里操作➡️ [https://tornadocash.eth.link/governance](https://tornadocash.eth.link/governance) ⬅️

在这页面的顶部就能看到你的质押奖励，等你来领取💰

![](../.gitbook/assets/head.png)

* 点击 **`管理`** -> **`Claim`** 标签 -> **`Claim`** _按钮。_

![](<../.gitbook/assets/claim (1).png>)

_这是这样，我们完成了。小事一桩_ :wink:



_编写_ [_**@bt11ba**_](https://torn.community/u/bt11ba/) _和_ [_**@ayefda**_](https://torn.community/u/ayefda)
