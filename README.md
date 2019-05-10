<!DOCTYPE html>
<html lang="shizhiping">
	<head>
		<meta charset="UTF-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<title>shiyan2</title>
		<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
		<link rel="stylesheet" type="text/css" href="css.css">
		<script type="text/javascript" src="js/jquery-1.12.4.min.js"></script>
		<script type="text/javascript" src="js/bootstrap.min.js"></script>
		<link href="prettify/prettify.css" type="text/css" rel="stylesheet" />
		<script type="text/javascript" src="prettify/prettify.js"></script>
		<script type="text/javascript">
			$(document).ready(function() {
				prettyPrint();
			})
		</script>
		<style type="text/css">
			.indent {
				text-indent: 60px;
			}
			 .style1{
            width: 80px;
        }
		</style>
	</head>
	<body data-spy="scroll" data-target="#scroll-nav">
		<div class="jumbotron text-center">
			<span class="h4">这是一个示例网站，代码很简单，但是还是很美观的对不对？</span>
			<div class="navbar navbar-default navbar-inverse">
			<div class="navbar-header">
				<a class="navbar-brand" href="#">导航</a>
				<a class="navbar-toggle btn" data-toggle="collapse" data-target=".collapse-div1">
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
				</a>
			</div>
			<div class="collapse navbar-collapse collapse-div1">
				<ul class="nav navbar-nav">
					<li><a href="#xinwen" data-toggle="tab">新闻</a></li>
					<li><a href="#denglu" data-toggle="tab">登陆</a></li>
					<li><a href="#daima" data-toggle="tab">代码</a></li>
					<li><a href="#wenzhang" data-toggle="tab">文章</a></li>
				</ul>
			</div>
		</div>
		</div>
		<div id="scroll-nav" class="col-lg-1">
                <ul class="nav nav-pills nav-stacked" data-spy="affix">
                    <li><a href="#xinwen">新闻</a></li>
                    <li><a href="#denglu">登陆</a></li>
                    <li><a href="#daima">代码</a></li>
                    <li><a href="#wenzhang">文章</a></li>
                </ul>
            </div>
		<div class="container">
			
			<div class="row">
				 
				<div class="col-md-4 col-sm-6">
					<div class="panel panel-info">
						<div class="panel-heading" id="xinwen">
							每日要闻
						</div>
						<div class="panel-body">
							<ul>
								<li>两会于近期召开&nbsp;&nbsp;<small>19-3-6</small></li>
								<li>人大选举于近期进行&nbsp;&nbsp;<small>19-3-6</small></li>
								<li>台湾准备回归&nbsp;&nbsp;<small>19-3-6</small></li>
								<li>美国准备投降&nbsp;&nbsp;<small>19-3-6</small></li>
								<li>萨达姆平反昭雪&nbsp;&nbsp;<small>19-3-6</small></li>
								<li>网络安全有提升到新高度&nbsp;&nbsp;<small>19-3-6</small></li>
							</ul>
						</div>
					</div>
					<div class="panel panel-primary">
						<div class="panel-heading" id="denglu">
							请您登陆
						</div>
						<div class="panel-body">
							<div class="form-group">
								<label for="" class="control-label">用户名</label>
								<input type="text" name="username" class="form-control">
							</div>
							<div class="form-group">
								<label for="" class="control-label">密码</label>
								<input type="password" name="username" class="form-control">
							</div>
							<div class="form-group">
								<input type="button" name="submit" class="btn btn-default" value=" 登录 ">
							</div>
						</div>
					</div>

					<div class="panel panel-info">
						<div class="panel-heading" id="biaoge">
							这是一个表格啦
						</div>
						<div class="panel-body">
							<table class="table table-striped table-hover">
								<tr>
									<th>姓名</th>
									<th>科目</th>
									<th>分数</th>
								<tr>
									<td>张三</td>
									<td>语文</td>
									<td>80</td>
								</tr>
								<tr>
									<td>王麻子</td>
									<td>数学</td>
									<td>90</td>
								</tr>
								<tr>
									<td>李四</td>
									<td>英语</td>
									<td>100</td>
								</tr>
								</tr>
							</table>
						</div>
						<div class="panel-footer"></div>
					</div>
				</div>
				<div class="col-md-8 col-sm-6">
					<div class="panel panel-default">
						<div class="panel-heading" id="wenzhang">
							这是网络摘抄的一篇文章
						</div>
						<div class="panel-body">
							<h4>流年无恙，光阴留香</h4>
							<h4>不同的时间，不同的地点，不同的人群，相同的只有你和我；时间在变，空间在变，不变的只有对你无限的思念！</h4>
							<p class="indent">在一个人的世界里走走停停，看路边风景无数，人生，盼的就是流年无恙，光阴留香。沉浸在春天的花香里，不愿醒来。那些留在记忆深处的便是人生中最美的风景，最值得珍惜的东西。在这些风景里，我们陶醉，我们欢呼，我们细细品味。那年，那月，那一天，那个人，也许，每一天，我们都拥有最美的回忆。
							</p>
							<p class="indent"><u><b>青春</b></u>，将我们的记忆拉长，虽然短暂，但<u><b>青春</b></u>里那些最美好的风景，像长长的电影画面，在我们的脑海一遍遍放映。回忆，让我们一次次流泪，一次次哭着微笑。<u><b>青春</b></u>，是人生的春天，是人生的希望，是人生最美的花朵，散发着春天里最明媚的一缕幽香。<u><b>青春</b></u>，让我们的生活丰富多彩；<u><b>青春</b></u>，让我们的时光如骏马，奔腾不息；<u><b>青春</b></u>，让我们的生命融入最新鲜的血液。
							</p>
							<blockquote>
								<p class="indent">青春，是一次精彩的旅行。在青春里，我们走过春天的田野，淋过春雨，沐浴春光，迎着春风，闻阵阵花香。生机勃勃的春天，姹紫嫣红的春天，春意盎然的春天，春情绵绵的春天，一幅人生中最美的画卷，在我们的眼前、脑海里、心灵深处徐徐展开。春的暖，春的美，春的妩媚，春的萌动，春的意象，对我们来说，都是那样新鲜，那样深刻。
								</p>
								<footer>摘自文章阅读网，<cite>黄天健</cite></footer>
							</blockquote>
						</div>
						<div class="panel-footer"></div>
					</div>

					<div class="panel panel-default hidden-xs">
						<div class="panel-heading" id="daima">
							这是我写的代码
						</div>
						<div class="panel-body">
							<p>linux的重新关机命令可以用<code>shutdown</code>,但是需要带参数，还是没有<code>init 0</code>来的方便，init是特别好用的命令，切换单用户可以使用<code>init 1</code>，这里涉及到linux的运行级别，如果大家可以搜索<i>linux
									init</i>获得更多信息。</p>
							<pre class=”prettyprint Lang-java”>/*这是0416404石芝萍写的JAVA示例程序*/
package mypack;         //相当于一个目录

public class HelloWorld{
        public static void main(String[] args) {
                System.out.println("Hello World!");
        }
}
</pre>
							<p>
								程序需要打包成jar，然后使用命令<code>jar xxx.jar mypack.HelloWorld</code>运行，注意不可以使用<kbd>ctrl</kbd>+<kbd>r</kbd>运行哦，因为没有快捷键。
							</p>
						</div>
						<div class="panel-footer"></div>
					</div>
				</div>
			</div>
		</div>
	</body>
</html>
