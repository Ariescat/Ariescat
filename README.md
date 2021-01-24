### Hi there 👋


> 浊以静之徐清  
> 安以动之徐生



#### 关于 我

九〇后，性别男，直男，爱好女。  
有时文艺，有时严肃，有时逗比，怕生。  
有时候看书，喜欢折腾一些东西。  
现在是一个普通人。



#### ⬇️开通了一个小站

[<img src="https://raw.githubusercontent.com/Ariescat/ariescat.github.io/master/img/apple-touch-icon.png" alt="icon" style="max-width:100%;" height="18" width="18">  **Ariescat‘s Blog**](https://github.ariescat.top) （ 如果在国内访问速度较慢，可以访问这个国内的节点：[**Ariescat‘s Blog**](http://ariescat.top) ）

小破站自 <a href="http://ariescat.top/2019/01/19/Hello-2019/" target="_blank" rel="noopener"><strong>2019.01.19</strong></a> 在各种灾难中苟活了<span id="htmer_time" style="font-weight: bold; color: rgb(0,124,183)"></span>


#### 欢迎来叨扰

你可以通过邮箱或Github找到我，欢迎Star，有Follow就更好了(☆ω☆)  
网站内有评论，希望大佬们多提意见 😄


<script type="text/javascript">
    function diff(second) {
        if (!second) {
            return 0;
        }
        var time = new Array(0, 0, 0, 0, 0);
        if (second >= 365 * 24 * 3600) {
            time[0] = parseInt(second / (365 * 24 * 3600));
            second %= 365 * 24 * 3600;
        }
        if (second >= 24 * 3600) {
            time[1] = parseInt(second / (24 * 3600));
            second %= 24 * 3600;
        }
        if (second >= 3600) {
            time[2] = parseInt(second / 3600);
            second %= 3600;
        }
        if (second >= 60) {
            time[3] = parseInt(second / 60);
            second %= 60;
        }
        if (second > 0) {
            time[4] = second;
        }
        return time;
    }
    function setTime() {
        // 博客创建时间秒数，时间格式中，月比较特殊，是从0开始的，所以想要显示5月，得写4才行，如下
        var create_time = Math.round(new Date(Date.UTC(2019, 0, 19, 0, 0, 0)).getTime() / 1000);
        var cur = Math.round((new Date().getTime() + 8 * 60 * 60 * 1000) / 1000);// 当前时间秒数,增加时区的差异
        diffTime = diff((cur - create_time));
        if (diffTime[0] == 0) {
            currentTimeHtml = diffTime[1] + '天' + diffTime[2] + '时' + diffTime[3] + '分' + diffTime[4] + '秒';
        } else {
            currentTimeHtml = diffTime[0] + '年' + diffTime[1] + '天' + diffTime[2] + '时' + diffTime[3] + '分' + diffTime[4] + '秒';
        }
        // 兼容pjax，当htmer_time存在时输出，否则清空计时器
        if (document.getElementById("htmer_time")) {
            document.getElementById("htmer_time").innerHTML = currentTimeHtml;
        } else {
            clearInterval(timer);
        }
    }
    var timer = setInterval(setTime, 1000);
</script>


<!--
**Ariescat/Ariescat** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
  -->
