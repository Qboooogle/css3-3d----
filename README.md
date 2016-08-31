# css3-3d----
css3 3D实现旋转木马特效
<p><strong>基本原理：</strong></p>
<ul>
<li>1.首先我们需要让图片能旋转的效果，我们让所有图片绝对定位(position:absolute),共用一个中心点。</li>
<li>2.对于舞台我们加一个视距，比如下面的demo是 perspective: 800px;</li>
<li>3.对于容器 我们可以加一个3D视图 transform-style: preserve-3d;</li>
<li>4. 对于图片旋转，我们要使用在旋转 rotateY,但是一圈是360度，而图片共九张，因此每一张的图片旋转的角度是40度；</li>
<li>因此我们可以在css下这样写代码：</li>
</ul>
详细说明及实例请点击 <a href = "http://www.cnblogs.com/qbzmy/p/5826505.html">demo</a>
