<template>
    <div>
        <AppHeader />
        <div class="banner"></div>
        <n-h3 style="text-align: center">
            五美金的礼品卡
        </n-h3>
        <n-divider />
        <div class="content">
            <n-tabs type="card" animated
                tab-style="min-width: 80px;white-space: nowrap;overflow:hidden;text-overflow:ellipsis">
                <n-tab-pane name="chap1" tab="2024/2025 年中国游">
                    我这辈子最疯狂的事，发生在我在 Amazon
                    当软件工程师的时候，故事是这样的：<br><br>
                    那时我和女朋友住在一起，正在家里远程工作。忽然同事给我发来了紧急消息：”我们的服务出现了
                    SEV 2 级别的故障！需要所有的人马上协助！“我们组的应用全挂掉了。<br><br>
                    当我还在费力的寻找修复方法的时候，忽然闻到隔壁房间的的焦味，防火报警器开始鸣叫。
                    <n-row gutter="12">
                        <n-col :span="6">
                            <n-card title="带封面的卡片" style="height: 480px">
                                <template #cover>
                                    <img height="240" src="~/assets/images/2.jpg">
                                </template>
                                卡片内容卡片内容卡片内容卡片内容卡片内容卡片内容卡片内容卡片内容卡片内容卡片内容卡片内容卡片内容卡片内容
                            </n-card>
                        </n-col>
                        <n-col :span="6">
                            <n-card title="带封面的卡片" style="height: 480px">
                                <template #cover>
                                    <img height="240" src="https://images.chinahighlights.com/allpicture/2021/04/747130ca20ad4192ab9e9f8b.webp">
                                </template>
                                卡片内容
                            </n-card>
                        </n-col>
                        <n-col :span="6">
                            <n-card title="带封面的卡片" style="height: 480px">
                                <template #cover>
                                    <img height="240" src="https://images.chinahighlights.com/allpicture/2018/08/f61a503b01654393a53c8f1a_cut_600x550_251.webp">
                                </template>
                                卡片内容
                            </n-card>
                        </n-col>
                        <n-col :span="6">
                            <n-card title="带封面的卡片" style="height: 480px">
                                <template #cover>
                                    <img height="240" src="https://images.chinahighlights.com/allpicture/2017/10/464ff429c1344fc982b0d6d9_cut_600x550_251.webp">
                                </template>
                                卡片内容
                            </n-card>
                        </n-col>
                    </n-row>

                </n-tab-pane>
                <n-tab-pane name="chap2" tab="中国外籍人士旅游">
                    “威尔！着火了！快来帮忙！”我听到女朋友大喊。现在一个难题在我面前——是恢复一个重要的
                    Amazon 服务，还是救公寓的火。<br><br>
                    我的脑海中忽然出现了 Amazon
                    著名的领导力准则”客户至上“，有很多的客户还依赖我们的服务，我不能让他们失望！所以着火也不管了，女朋友喊我也无所谓，我开始
                    debug 这个线上问题。
                </n-tab-pane>
                <n-tab-pane name="chap3" tab="中国冬季旅游">
                    但是忽然，公寓的烟味消失，火警也停了。我的女朋友走进了房间，让我震惊的是，她摘下了自己的假发，她是
                    Jeff Bezos（Amazon 老板）假扮的！<br><br>
                    “我对你坚持顾客至上的原则感到十分骄傲”，说完，他递给我一张五美金的亚马逊礼品卡，从我家窗户翻了出去，跳上了一辆
                    Amazon 会员服务的小货车，一溜烟离开了。<br><br>虽然现在我已不在 Amazon
                    工作，但我还是非常感激在哪里学的到的经验，这些经验我终身难忘。你们同意么？
                </n-tab-pane>
                <n-tab-pane name="chap4" tab="十大旅游线路">
                    但是忽然，公寓的烟味消失，火警也停了。我的女朋友走进了房间，让我震惊的是，她摘下了自己的假发，她是
                    Jeff Bezos（Amazon 老板）假扮的！<br><br>
                    “我对你坚持顾客至上的原则感到十分骄傲”，说完，他递给我一张五美金的亚马逊礼品卡，从我家窗户翻了出去，跳上了一辆
                    Amazon 会员服务的小货车，一溜烟离开了。<br><br>虽然现在我已不在 Amazon
                    工作，但我还是非常感激在哪里学的到的经验，这些经验我终身难忘。你们同意么？
                </n-tab-pane>
                <n-tab-pane name="chap5" tab="熊猫旅游">
                    但是忽然，公寓的烟味消失，火警也停了。我的女朋友走进了房间，让我震惊的是，她摘下了自己的假发，她是
                    Jeff Bezos（Amazon 老板）假扮的！<br><br>
                    “我对你坚持顾客至上的原则感到十分骄傲”，说完，他递给我一张五美金的亚马逊礼品卡，从我家窗户翻了出去，跳上了一辆
                    Amazon 会员服务的小货车，一溜烟离开了。<br><br>虽然现在我已不在 Amazon
                    工作，但我还是非常感激在哪里学的到的经验，这些经验我终身难忘。你们同意么？
                </n-tab-pane>
                <n-tab-pane name="chap6" tab="长城徒步">
                    但是忽然，公寓的烟味消失，火警也停了。我的女朋友走进了房间，让我震惊的是，她摘下了自己的假发，她是
                    Jeff Bezos（Amazon 老板）假扮的！<br><br>
                    “我对你坚持顾客至上的原则感到十分骄傲”，说完，他递给我一张五美金的亚马逊礼品卡，从我家窗户翻了出去，跳上了一辆
                    Amazon 会员服务的小货车，一溜烟离开了。<br><br>虽然现在我已不在 Amazon
                    工作，但我还是非常感激在哪里学的到的经验，这些经验我终身难忘。你们同意么？
                </n-tab-pane>
            </n-tabs>
        </div>

    </div>
</template>
<script>
import { defineComponent } from 'vue'
import { NButton, NDivider, NH3, NTabs, NTabPane, NCard } from 'naive-ui'

export default defineComponent({
    components: {
        NButton,
        NDivider,
        NH3,
        NTabs,
        NTabPane,
        NCard
    }
})
</script>
<style lang="scss" scoped>
.banner {
    width: 100%;
    background: url('@/assets/images/banner.jpg') no-repeat;
    background-size: cover;
    height: 634px;
}

.content {
    width: 80%;
    margin: 0 auto;
}
</style>