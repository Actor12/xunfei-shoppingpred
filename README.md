#2021讯飞开放平台-基于用户画像的商品推荐挑战赛

竞赛网址：https://challenge.xfyun.cn/topic/info?type=user-portrait

最终成绩：初赛：21/1698  复赛：28/1698

本次比赛主要采用了lightGBM和用gru自建的深度学习网络两种模型训练，结果做投票融合；

提分点：特征衍生、nullimportance特征筛选法、调整gru网络参数和结构、word2vec调参、finetuning、交叉验证、伪标签、soft_vote融合和早停、学习率衰退等训练策略。
