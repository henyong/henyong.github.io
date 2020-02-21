# 抽奖
<textarea width="200px" height="100px" id="txt"></textarea><br/>
<button onclick="a()">开始!</button>
<script>
  function a(){
  var notes=[
  '1、你有没有钟意的人?是谁?',
  '2、你的初恋是几岁?',
  '3、你的初恋对象是谁?',
  '4、你的初吻是几岁，被谁夺取的?',
  '5、你亲吻过多少人?'
  ];
  document.getElementById("txt").value=notes[Math.random()*notes.length];
  }
</script>
