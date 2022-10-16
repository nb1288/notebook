<div id="primary" class="site-content">
		<div id="content" role="main">

			
				
	<article id="post-2300" class="post-2300 post type-post status-publish format-standard hentry category-tools tag-gfw tag-shadowrocket tag-shadowsocks tag-surge tag-540">
				<header class="entry-header">
			
						<h1 class="entry-title">iOS利器“小火箭”（Shadowrocket）最全使用教程</h1>
										<div class="comments-link">
					<a href="https://laob.me/2300/#comments">81条回复</a>				</div><!-- .comments-link -->
					</header><!-- .entry-header -->

				<div class="entry-content">
			<p>最近得知Surge2可以向surge3迁移或赠送Mac版，我使用授权迁移时提示我已经被其他邮箱迁移走，官推不回，邮件不回，想想买个新版吧？258元？于是到美区买了Shadowrocket，我们俗称的小火箭，因为其图标是一个小火箭的LOGO，所以大家爱称之为小火箭。大家到App Store下载的时候别认错了，App Store好几款挂羊头卖狗肉的冒充货。配置下来发现，经过3年的发展，对得起这个价格。</p>
<p></p>
<p>　　Shadowrocket是一款基于规则的网络调试工具，具有性能高和稳定好、使用流畅，功能多样的特点，只占用最少的系统资源，全盘接管所有的连接，根据规则来进行处理，让你无忧无虑。独有的场景模式，方便根据不同需求自动切换配置及节点。不过这个指是软件教程，另外还需要一个好用的服务器或机场服务。</p>


<div class="wp-block-image is-style-default"><figure class="aligncenter size-large is-resized"><a href="https://www.amysecure.com/aff.php?aff=12" target="view_window" rel="noopener noreferrer"><img loading="lazy" src="https://laob.me/wp-content/uploads/2020/09/shadowsocks.jpg" alt="" class="wp-image-2372" width="256" height="256"></a></figure></div>


<p>主界面</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2301" src="https://laob.me/wp-content/uploads/2018/11/1.jpg" alt="" width="500" height="889"></a></p>
<p>一，节点相关</p>
<p>1，添加节点</p>
<p>小火箭支持多种方法添加节点。</p>
<p>（1）链接导入</p>
<p>小火箭可以直接打开ss://开头的节点链接，自动导入节点；使用这个导入方式，部分网站可以一键导入所有节点。这个也是“小火箭免费节点获取”等Workflow流程可以直接导入节点的原理。假如你已经复制了一个ss://开头的节点链接，打开小火箭，会询问是否添加。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828701-8729-acd4uwfft.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2302" src="https://laob.me/wp-content/uploads/2018/11/1496828701-8729-acd4uwfft.jpg" alt="" width="500" height="234"></a></p>
<p>（2）扫描二维码添加</p>
<p>点击右上角扫描符号，可以打开相机扫描，也可以从相册提取二维码扫描；这个方式最为方便了，一键完成。<span id="more-2300"></span></p>
<p>（3）手动输入</p>
<p>点击右上角+号，手动输入节点信息添加。适合只知道节点信息的情况下使用。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828700-5548-qon6kmtrd.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2303" src="https://laob.me/wp-content/uploads/2018/11/1496828700-5548-qon6kmtrd.jpg" alt="" width="500" height="117"></a></p>
<blockquote>
<p>Tips：<br>一个完整节点必须具备四个要素：服务器，端口，密码，加密方式，缺一不可。在添加节点界面，可以逐一输入。节点示例：<br>服务器：125.195.246.110（一般为IP地址或者网址）<br>端口：12345（一般为1—65535）<br>密码：12345（最长128位）<br>算法：rc4-md5（即加密方式）<br>混淆：auth_sha1_v4 tls1.2_ticket_auth(选填)</p>
</blockquote>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828701-4299-olcrcytyh.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2304" src="https://laob.me/wp-content/uploads/2018/11/1496828701-4299-olcrcytyh.jpg" alt="" width="800" height="349" srcset="https://laob.me/wp-content/uploads/2018/11/1496828701-4299-olcrcytyh.jpg 800w, https://laob.me/wp-content/uploads/2018/11/1496828701-4299-olcrcytyh-530x231.jpg 530w, https://laob.me/wp-content/uploads/2018/11/1496828701-4299-olcrcytyh-768x335.jpg 768w, https://laob.me/wp-content/uploads/2018/11/1496828701-4299-olcrcytyh-624x272.jpg 624w" sizes="(max-width: 800px) 100vw, 800px"></a></p>
<p>小火箭支持多种类型节点，例如SS、SSR，GFW等等。多类型的节点方式，是根据不同的协议、不同的加密混淆及一些不同的特性而开发的，目前比较主流的是SS、SSR，我们使用扫码添加或者链接导入节点的时候会自动判断节点类型，手动添加要注意节点类型。</p>
<p>小火箭支持多种加密方法，例如rc4-md5、chacha20等等。内置丰富的旗帜，方便区分所用节点的国家。扫码或者导入的节点，会自动识别位置显示国旗标识。</p>
<p>2，节点编辑及删除</p>
<p>在小火箭首页，节点列表，点击节点右边的叹号，可以编辑节点信息，例如修改密码，修改旗帜等等。</p>
<p>节点前面有黄色小圆点，表示当前选择该节点。按住节点向左滑，可以复制节点，显示节点二维码，或者删除该节点。注意：正在使用的节点是无法删除的。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828701-1103-tla7kwzl5.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2305" src="https://laob.me/wp-content/uploads/2018/11/1496828701-1103-tla7kwzl5.jpg" alt="" width="500" height="292"></a></p>
<p>小火箭支持删除多个节点。点击节点列表上方的三横杠按钮，进入节点删除排序界面，拖动节点右边的三横杠按钮，可以对节点进行排序。勾选节点，可以批量删除。适合多节点失效的情况下快速删除节点。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828704-6201-v1lq322i1.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2306" src="https://laob.me/wp-content/uploads/2018/11/1496828704-6201-v1lq322i1.jpg" alt="" width="500" height="857"></a></p>
<p>3，节点的延迟测试</p>
<p>在主界面，点击延迟测试，可以对已添加的节点进行速度测试，并显示具体数字，数字越低的节点，速度越快。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828704-6754-81f2qq4o9.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2307" src="https://laob.me/wp-content/uploads/2018/11/1496828704-6754-81f2qq4o9.jpg" alt="" width="500" height="254"></a></p>
<p>在设置——延迟测试方法——可以对测试方式进行更改，有TCP和ICMP可选。建议选择TCP。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828704-3616-sa2gcg3zd.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2308" src="https://laob.me/wp-content/uploads/2018/11/1496828704-3616-sa2gcg3zd.jpg" alt="" width="500" height="198"></a></p>
<p>这两种都是网络传输协议，承载数据传输。简单来说，TCP是可靠传输，有3次握手机制保证数据传输的可靠性。如果有丢包，则重新传数据。像FTP文件传送，远程登录，POP3电子邮件等等这些都是基于TCP协议的。ICMP是TCP/IP协议簇的一个子协议。不承载数据，不是用来传输用户数据，是用来传递控制消息的，即：网络通不通、主机是否可达。ping命令就是基于ICMP的。具体不同，不赘述。</p>
<p>填写好节点，打开开关，就会开导状态栏出现VPN的标志，小火箭就可以初步使用啦。</p>
<p>二，全局路由的策略</p>
<p>小火箭拥有四种全局路由策略：配置、代理、直连、场景。下面一一介绍。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828704-9165-bathx6srt.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2309" src="https://laob.me/wp-content/uploads/2018/11/1496828704-9165-bathx6srt.jpg" alt="" width="500" height="454"></a></p>
<p>1，配置</p>
<p>选用配置（规则）方法来进行连接。可以根据不同的规则，使网络连接在自己定制的“规则”范围内进行。例如可以分流（例如国内IP直连，国外网站自动走代理），例如可以去除广告。小火箭的配置和节点是分开的，这一点很方便。</p>
<p>（1）添加配置<br>小火箭支持从URL或者.conf文件方式，还有云端导入。</p>
<p>A. 从URL添加配置</p>
<p>小火箭——配置——点击右上角的“+”号，弹出对话框输入（粘贴）配置地址，然后可以在远程文件处，看到刚刚下载的远程文件，点击，弹出选项中选择使用配置，该配置就会添加到“远程文件”列表上方的“本地文件”列表当中，选择就可以使用了。</p>
<p>注意：在配置的“本地文件”中，前面的黄色小圆点表示默认配置，后面的打钩符号，表示正在使用。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828705-7898-eixza8f1l.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2310" src="https://laob.me/wp-content/uploads/2018/11/1496828705-7898-eixza8f1l.jpg" alt="" width="800" height="597" srcset="https://laob.me/wp-content/uploads/2018/11/1496828705-7898-eixza8f1l.jpg 800w, https://laob.me/wp-content/uploads/2018/11/1496828705-7898-eixza8f1l-530x396.jpg 530w, https://laob.me/wp-content/uploads/2018/11/1496828705-7898-eixza8f1l-768x573.jpg 768w, https://laob.me/wp-content/uploads/2018/11/1496828705-7898-eixza8f1l-624x466.jpg 624w" sizes="(max-width: 800px) 100vw, 800px"></a></p>
<p>在远程文件点击该配置，可以对配置进行预览，使用和复制网址。在本地文件中，点击配置文件，可以编辑配置，改名，导出等操作。</p>
<blockquote>
<p>推荐的配置<br>lhie1的Shadowrocket规则：<br>https://raw.githubusercontent.com/lhie1/Surge/master/Shadowrocket.conf<br>说明：目前比较主流小火箭规则，长期维护更新，所有国内网站直线连接，国外常用网站加速，解决本地 DNS 可能带来的干扰，屏蔽部分应用程序的广告，屏蔽部分运营商劫持网页，屏蔽常用网站广告、其他流媒体网站广告。<br>逗比极客surge规则：<br>精简规则<br>https://raw.githubusercontent.com/tudi1909/Surge_rules/master/iOS_S.conf<br>全能规则<br>https://raw.githubusercontent.com/tudi1909/Surge_rules/master/iOS.conf<br>说明：小火箭兼容Surge规则，逗比极客规则并没有小火箭专版，所以在使用上，导入规则后，需要手动去除添加进来的节点信息。</p>
</blockquote>
<p>B. conf文件方式导入</p>
<p>小火箭也支持从conf文件为后缀名的配置文件导入，如下图所示，打开conf文件，选择拷贝至小火箭。小火箭兼容Surge规则。如果导入的是Surge配置文件，会提示是否保存配置文件当中的节点，建议选择否。导入后在配置中“本地文件”可以看到。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828705-2348-3xipbyy3t.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2311" src="https://laob.me/wp-content/uploads/2018/11/1496828705-2348-3xipbyy3t.jpg" alt="" width="800" height="680" srcset="https://laob.me/wp-content/uploads/2018/11/1496828705-2348-3xipbyy3t.jpg 800w, https://laob.me/wp-content/uploads/2018/11/1496828705-2348-3xipbyy3t-530x451.jpg 530w, https://laob.me/wp-content/uploads/2018/11/1496828705-2348-3xipbyy3t-768x653.jpg 768w, https://laob.me/wp-content/uploads/2018/11/1496828705-2348-3xipbyy3t-624x530.jpg 624w" sizes="(max-width: 800px) 100vw, 800px"></a></p>
<p>C. 从云端导入</p>
<p>小火箭支持从云端导入配置，在配置界面可以看到，支持从 iCloud或者其他网盘方式导入。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828707-8752-9zqc2gmjt.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2312" src="https://laob.me/wp-content/uploads/2018/11/1496828707-8752-9zqc2gmjt.jpg" alt="" width="800" height="337" srcset="https://laob.me/wp-content/uploads/2018/11/1496828707-8752-9zqc2gmjt.jpg 800w, https://laob.me/wp-content/uploads/2018/11/1496828707-8752-9zqc2gmjt-530x223.jpg 530w, https://laob.me/wp-content/uploads/2018/11/1496828707-8752-9zqc2gmjt-768x324.jpg 768w, https://laob.me/wp-content/uploads/2018/11/1496828707-8752-9zqc2gmjt-624x263.jpg 624w" sizes="(max-width: 800px) 100vw, 800px"></a></p>
<p>在配置界面，也可以对配置进行上传，编辑等等。</p>
<p>（2）编辑配置</p>
<p>点击已经导入本地文件的配置，可以对配置进行编辑。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828707-8357-adro226nd.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2313" src="https://laob.me/wp-content/uploads/2018/11/1496828707-8357-adro226nd.jpg" alt="" width="500" height="586"></a></p>
<p>（3）更新配置</p>
<p>配置的更新，适合以URL方式导入的规则。可以在配置——远程文件处，点击所选远程文件网址，弹出菜单选择使用配置，重新导入配置，就是该远程文件最新的配置了。无需理会节点问题。</p>
<p>2，代理</p>
<p>即为全部网络连接使用代理进行，Proxy，就是我们所说的全局代理。</p>
<p>3，直连</p>
<p>直接访问网络，Direct，并不使用科学上网连接。</p>
<p>4，场景</p>
<p>根据不同使用场合自动切换相关配置，支持使用不同的Urltest测速分组和Conf配置文件。这个是小火箭特有的厉害之处。根据设置的场景，可以切自动切换节点或者配置。例如，我可以设置一个场景，网络切换到公司WIFI，可以使小火箭自动切换到直连状态。</p>
<p>位置在首页——全局路由——场景。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828708-9756-ty674u78p.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2314" src="https://laob.me/wp-content/uploads/2018/11/1496828708-9756-ty674u78p.jpg" alt="" width="800" height="215" srcset="https://laob.me/wp-content/uploads/2018/11/1496828708-9756-ty674u78p.jpg 800w, https://laob.me/wp-content/uploads/2018/11/1496828708-9756-ty674u78p-530x142.jpg 530w, https://laob.me/wp-content/uploads/2018/11/1496828708-9756-ty674u78p-768x206.jpg 768w, https://laob.me/wp-content/uploads/2018/11/1496828708-9756-ty674u78p-624x168.jpg 624w" sizes="(max-width: 800px) 100vw, 800px"></a></p>
<p>在添加场景里，可以自行设置</p>
<p>场景：选择触发模式的具体场景，例如数据状态，某个WIFI下。SSID即为选择WIFI时候的具体WIFI名称；</p>
<p>路由：使用该场景时候的全局路由方式，有配置、代理、直连可选；</p>
<p>类型：使用该场景时候节点的类型，可以选择单个节点，也可以选择分组。分组在下节速度测试结束。类型下方的节点选项，要类型里选择为单节点才会显示；</p>
<p>配置：使用场景时候的配置文件；</p>
<p>备注：给场景备注一个方便辨别的名词。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828708-5399-nyig16mg9.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2315" src="https://laob.me/wp-content/uploads/2018/11/1496828708-5399-nyig16mg9.jpg" alt="" width="800" height="608" srcset="https://laob.me/wp-content/uploads/2018/11/1496828708-5399-nyig16mg9.jpg 800w, https://laob.me/wp-content/uploads/2018/11/1496828708-5399-nyig16mg9-530x403.jpg 530w, https://laob.me/wp-content/uploads/2018/11/1496828708-5399-nyig16mg9-768x584.jpg 768w, https://laob.me/wp-content/uploads/2018/11/1496828708-5399-nyig16mg9-624x474.jpg 624w" sizes="(max-width: 800px) 100vw, 800px"></a></p>
<p>当全局路由选择场景模式，只有场景触发，才会启用场景里面的设置。否则还是使用当前设置。</p>
<p>例如，我设置了一个场景：网络4G时候，使用He日本这个节点。如下图所示，当网络切换为4G情况下，小火箭会自动重新连接VPN，尽管我默认的节点是“Tu新加坡”，但是连接使用的是我场景预设的节点。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828708-5701-r6mxe88q1.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2316" src="https://laob.me/wp-content/uploads/2018/11/1496828708-5701-r6mxe88q1.jpg" alt="" width="500" height="502"></a></p>
<p>5，节点分组测速</p>
<p>小火箭有节点也有节点分组测试，作用是自动测试分组内的节点，并选择速度最快节点来使用。这个就类似于Surge的Auto Gruop功能。这个就方便我们可以自动选择最优节点来使用，假如某个节点挂了，就自动切换可用的延迟最低的节点，省去手动选择的没法。</p>
<p>使用方法：首页——点击全局路由——找到下面的设置——点击速度测试进入速度测试设置界面。</p>
<p>点击下面的添加分组，选择常用的节点，目前每个分组只能选择10个节点，备注好节点名称后，完成。启动URL测试，节点速度测试就开启了。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828710-3691-icw0x4lrd.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2317" src="https://laob.me/wp-content/uploads/2018/11/1496828710-3691-icw0x4lrd.jpg" alt="" width="800" height="307" srcset="https://laob.me/wp-content/uploads/2018/11/1496828710-3691-icw0x4lrd.jpg 800w, https://laob.me/wp-content/uploads/2018/11/1496828710-3691-icw0x4lrd-530x203.jpg 530w, https://laob.me/wp-content/uploads/2018/11/1496828710-3691-icw0x4lrd-768x295.jpg 768w, https://laob.me/wp-content/uploads/2018/11/1496828710-3691-icw0x4lrd-624x239.jpg 624w" sizes="(max-width: 800px) 100vw, 800px"></a></p>
<p>如下图所示，我默认选择的是“Tu新加坡”这个节点，但是我启用了节点速度测试功能后，会自动选取延迟最低的最优节点来使用。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828710-7669-jt7jf9oo9.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2318" src="https://laob.me/wp-content/uploads/2018/11/1496828710-7669-jt7jf9oo9.jpg" alt="" width="500" height="530"></a></p>
<p>三，安装证书及开启HTTPS</p>
<p>小火箭更新至2.1.6版本后，增加了MITM功能。</p>
<p>MITM是什么呢？就是Man-in-the-MiddleAttack的缩写，翻译过来就是中间人攻击，简而言之，MITM攻击是通过拦截加密的通信数据例如HTTPS，并进行数据篡改和嗅探，在通信的双方却毫不知情的情况下完成。小火箭（Shadowrocket）使用中间人攻击的方式用来解密HTTPS流量，从而对广告行为进行分析并拦截，达到去除HTTPS广告的作用。如何开启MITM呢？</p>
<p>1，生成及安装证书</p>
<p>点击小火箭下方菜单的设置——高级——证书<br><a href="https://laob.me/wp-content/uploads/2018/11/1496828711-3038-6qgyt44rt.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2319" src="https://laob.me/wp-content/uploads/2018/11/1496828711-3038-6qgyt44rt.jpg" alt="" width="500" height="852"></a></p>
<p>2，开启HTTPS解密</p>
<p>配置——本地文件一栏——点击正在使用的配置——弹出菜单选择编辑配置：</p>
<p>四，数据统计</p>
<p>在小火箭底部的数据菜单，点击统计，可以查看小火箭数据情况。这里，可以看到节点，链接时间，流量详情等等。<br><a href="https://laob.me/wp-content/uploads/2018/11/1496828717-3488-u252i7j1l.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2320" src="https://laob.me/wp-content/uploads/2018/11/1496828717-3488-u252i7j1l.jpg" alt="" width="500" height="1192" srcset="https://laob.me/wp-content/uploads/2018/11/1496828717-3488-u252i7j1l.jpg 500w, https://laob.me/wp-content/uploads/2018/11/1496828717-3488-u252i7j1l-430x1024.jpg 430w" sizes="(max-width: 500px) 100vw, 500px"></a></p>
<p>五，节点及配置的备份</p>
<p>小火箭拥有丰富的备份功能。位置在数据——备份——iCloud。</p>
<p>使用备份功能，可以将节点，配置文件，场景，分组信息全部备份到iCloud。即使更换手机，可以轻松将所有信息转移至新设置，相当方便。建议打开小火箭的iCloud备份自动同步的开关。<br><a href="https://laob.me/wp-content/uploads/2018/11/1496828717-1552-h0nz63k15.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2321" src="https://laob.me/wp-content/uploads/2018/11/1496828717-1552-h0nz63k15.jpg" alt="" width="800" height="607" srcset="https://laob.me/wp-content/uploads/2018/11/1496828717-1552-h0nz63k15.jpg 800w, https://laob.me/wp-content/uploads/2018/11/1496828717-1552-h0nz63k15-530x402.jpg 530w, https://laob.me/wp-content/uploads/2018/11/1496828717-1552-h0nz63k15-768x583.jpg 768w, https://laob.me/wp-content/uploads/2018/11/1496828717-1552-h0nz63k15-624x473.jpg 624w" sizes="(max-width: 800px) 100vw, 800px"></a></p>
<p>六，按需求连接</p>
<p>按需求连接，意思你的网络试图连接按需求规则内的域名时候，小火箭会自动打开VPN模式，进行连接。</p>
<p>例如，当你开启按需求连接，Facebook这个域名是默认在按需求规则内的，打开Facebook网站时候，你会看到状态栏出现VPN标志，小火箭自动连接VPN了。是不是很方便呢？</p>
<p>睡眠时断开，则是当手机进入睡眠状态，VPN会自动断开，至于系统睡眠，是根据系统判断的。注意：按需求规则只能添加域名，添加IP地址的形式是不起作用的。</p>
<p>设置——高级——按需求连接。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828721-4445-k3op9gyzt.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2322" src="https://laob.me/wp-content/uploads/2018/11/1496828721-4445-k3op9gyzt.jpg" alt="" width="500" height="890"></a></p>
<p>七，如何同一局域网下实现代理共享？</p>
<p>首先小火箭开启代理共享，设置——代理——代理共享——启用共享。</p>
<p>其他iOS设备，去无线局域网下点击当前所处的同一WIFI右边的感叹号，最下面HTTP代理——选择手动，填写服务器和端口，例如，火箭代理共享处的地址为192.168.123.16:1082，则服务器填写192.168.123.16，端口填写1082即可，这样就可以实现代理共享啦。如果无法共享，请将其他设备的IP地址填入小火箭代理共享内允许的IP地址中。</p>
<p><a href="https://laob.me/wp-content/uploads/2018/11/1496828723-6948-m0q0rsf1l.jpg"><img loading="lazy" class="aligncenter size-full wp-image-2323" src="https://laob.me/wp-content/uploads/2018/11/1496828723-6948-m0q0rsf1l.jpg" alt="" width="500" height="545"></a></p>
<p>电脑及安卓也可以使用该方法实现代理共享。注意：2台设备必须在同一WIFI下才可以。</p>
<p>8，巧用场景</p>
<p>有时候会遇到这样的情况，如果路由器挂载了ss我如何指定该路由下的连接走直连？而其他路由器下继续走代理呢？使用场景功能，可以轻松解决。</p>
<p>首页——点击全局路由——设置——场景——可以新建一个场景，其中SSID设置为已经挂了SS的路由器WIFI名称，路由选择直连即可。</p>


<div class="wp-block-image is-style-default"><figure class="aligncenter size-large is-resized"><a href="https://www.amysecure.com/aff.php?aff=12" target="view_window" rel="noopener noreferrer"><img loading="lazy" src="https://laob.me/wp-content/uploads/2020/09/shadowsocks.jpg" alt="" class="wp-image-2372" width="256" height="256"></a></figure></div>
					</div><!-- .entry-content -->
		
		<footer class="entry-meta">
			本条目发布于<a href="https://laob.me/2300/" title="12:09 下午" rel="bookmark"><time class="entry-date" datetime="2018-11-03T12:09:32+08:00">2018年11月3日</time></a>。属于<a href="https://laob.me/category/tools/" rel="category tag">Tools</a>分类，被贴了 <a href="https://laob.me/tag/gfw/" rel="tag">GFW</a>、<a href="https://laob.me/tag/shadowrocket/" rel="tag">shadowrocket</a>、<a href="https://laob.me/tag/shadowsocks/" rel="tag">shadowsocks</a>、<a href="https://laob.me/tag/surge/" rel="tag">surge</a>、<a href="https://laob.me/tag/%e7%a7%91%e5%ad%a6%e4%b8%8a%e7%bd%91/" rel="tag">科学上网</a> 标签。<span class="by-author">作者是<span class="author vcard"><a class="url fn n" href="https://laob.me/author/soolby/" title="查看所有由毕扬发布的文章" rel="author">毕扬</a></span>。</span>								</footer><!-- .entry-meta -->
	</article><!-- #post -->

				<nav class="nav-single">
					<h3 class="assistive-text">文章导航</h3>
					<span class="nav-previous"><a href="https://laob.me/2290/" rel="prev"><span class="meta-nav">←</span> 已经一年没有更新了。</a></span>
					<span class="nav-next"><a href="https://laob.me/2329/" rel="next">LastPass 密码库导入迁移至 1Password <span class="meta-nav">→</span></a></span>
				</nav><!-- .nav-single -->

				
<div id="comments" class="comments-area">

	
			<h2 class="comments-title">
			《<span>iOS利器“小火箭”（Shadowrocket）最全使用教程</span>》有81个想法		</h2>

		<ol class="commentlist">
					<li class="comment even thread-even depth-1" id="li-comment-30488">
		<article id="comment-30488" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/e2094f9b24c64f381085c45275e0ffe4?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/e2094f9b24c64f381085c45275e0ffe4?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="https://www.sunnyfly.com" rel="external nofollow ugc" class="url">孙威</a></b> </cite><a href="https://laob.me/2300/#comment-30488"><time datetime="2018-11-29T16:20:17+08:00">2018年11月29日 4:20 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>IOS翻墙神器，最爱的app~</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30488#respond" data-commentid="30488" data-postid="2300" data-belowelement="comment-30488" data-respondelement="respond" data-replyto="回复给孙威" aria-label="回复给孙威">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor odd alt depth-2" id="li-comment-30489">
		<article id="comment-30489" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-30489"><time datetime="2018-11-30T13:34:50+08:00">2018年11月30日 1:34 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>以前我最爱surge 现在我发现，小火箭更新了几个版本，真的好用。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30489#respond" data-commentid="30489" data-postid="2300" data-belowelement="comment-30489" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment even depth-3" id="li-comment-30490">
		<article id="comment-30490" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/7eccc984b0feea176dc6544d000e1c3d?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/7eccc984b0feea176dc6544d000e1c3d?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">YY</b> </cite><a href="https://laob.me/2300/#comment-30490"><time datetime="2018-11-30T19:10:49+08:00">2018年11月30日 7:10 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>请问哪里找节点？感觉有了教程没资源添加？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30490#respond" data-commentid="30490" data-postid="2300" data-belowelement="comment-30490" data-respondelement="respond" data-replyto="回复给YY" aria-label="回复给YY">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor odd alt depth-4" id="li-comment-30491">
		<article id="comment-30491" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-30491"><time datetime="2018-12-03T21:58:28+08:00">2018年12月3日 9:58 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>找个机场，买一个</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30491#respond" data-commentid="30491" data-postid="2300" data-belowelement="comment-30491" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment even depth-5" id="li-comment-30641">
		<article id="comment-30641" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/546403b056b32cb015f400875701dde6?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/546403b056b32cb015f400875701dde6?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="https://share.earnrmb.us" rel="external nofollow ugc" class="url">yamakuchi</a></b> </cite><a href="https://laob.me/2300/#comment-30641"><time datetime="2019-03-14T21:35:31+08:00">2019年03月14日 9:35 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>去rixcloud买~节点</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30641#respond" data-commentid="30641" data-postid="2300" data-belowelement="comment-30641" data-respondelement="respond" data-replyto="回复给yamakuchi" aria-label="回复给yamakuchi">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment odd alt depth-6" id="li-comment-32140">
		<article id="comment-32140" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/20130e5d66872a5f8de647768324afc7?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/20130e5d66872a5f8de647768324afc7?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">1</b> </cite><a href="https://laob.me/2300/#comment-32140"><time datetime="2021-06-20T22:38:19+08:00">2021年06月20日 10:38 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>lj广告</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32140#respond" data-commentid="32140" data-postid="2300" data-belowelement="comment-32140" data-respondelement="respond" data-replyto="回复给1" aria-label="回复给1">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even depth-5" id="li-comment-30754">
		<article id="comment-30754" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/a8343722f6dcabe1b9efd32a363df734?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/a8343722f6dcabe1b9efd32a363df734?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://china" rel="external nofollow ugc" class="url">陈小姐</a></b> </cite><a href="https://laob.me/2300/#comment-30754"><time datetime="2019-08-27T10:48:06+08:00">2019年08月27日 10:48 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>怎么买小火箭？我要</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30754#respond" data-commentid="30754" data-postid="2300" data-belowelement="comment-30754" data-respondelement="respond" data-replyto="回复给陈小姐" aria-label="回复给陈小姐">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment odd alt depth-2" id="li-comment-30755">
		<article id="comment-30755" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/8dd1a1d6269fb8561649a76569417d4a?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/8dd1a1d6269fb8561649a76569417d4a?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">刘油</b> </cite><a href="https://laob.me/2300/#comment-30755"><time datetime="2019-09-27T14:40:30+08:00">2019年09月27日 2:40 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>求节点分享</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30755#respond" data-commentid="30755" data-postid="2300" data-belowelement="comment-30755" data-respondelement="respond" data-replyto="回复给刘油" aria-label="回复给刘油">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment even depth-3" id="li-comment-30801">
		<article id="comment-30801" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/18a9ebe2e28af201c1d053adc7bec7b1?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/18a9ebe2e28af201c1d053adc7bec7b1?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">wegwe</b> </cite><a href="https://laob.me/2300/#comment-30801"><time datetime="2020-01-22T21:58:23+08:00">2020年01月22日 9:58 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>贪得无厌，自己去买啊</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30801#respond" data-commentid="30801" data-postid="2300" data-belowelement="comment-30801" data-respondelement="respond" data-replyto="回复给wegwe" aria-label="回复给wegwe">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment odd alt depth-4" id="li-comment-33723">
		<article id="comment-33723" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/08d8d348782916871e82fc6663afb15e?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/08d8d348782916871e82fc6663afb15e?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">冕</b> </cite><a href="https://laob.me/2300/#comment-33723"><time datetime="2021-11-23T22:17:57+08:00">2021年11月23日 10:17 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>怎么续费啊，我的到期了，续费那个界面在哪？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=33723#respond" data-commentid="33723" data-postid="2300" data-belowelement="comment-33723" data-respondelement="respond" data-replyto="回复给冕" aria-label="回复给冕">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even depth-2" id="li-comment-30833">
		<article id="comment-30833" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/77adc59477002d748f0c2e92361f09fb?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/77adc59477002d748f0c2e92361f09fb?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">风</b> </cite><a href="https://laob.me/2300/#comment-30833"><time datetime="2020-04-08T00:49:43+08:00">2020年04月8日 12:49 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>还不错</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30833#respond" data-commentid="30833" data-postid="2300" data-belowelement="comment-30833" data-respondelement="respond" data-replyto="回复给风" aria-label="回复给风">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt depth-2" id="li-comment-32380">
		<article id="comment-32380" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/17e34e901a4fd40e4fcd5a8a2240e2a9?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/17e34e901a4fd40e4fcd5a8a2240e2a9?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">小胖子的时候</b> </cite><a href="https://laob.me/2300/#comment-32380"><time datetime="2021-07-17T13:32:28+08:00">2021年07月17日 1:32 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>好</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32380#respond" data-commentid="32380" data-postid="2300" data-belowelement="comment-32380" data-respondelement="respond" data-replyto="回复给小胖子的时候" aria-label="回复给小胖子的时候">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-odd thread-alt depth-1" id="li-comment-30570">
		<article id="comment-30570" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/b09d564660034a771f272bdba387b6af?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/b09d564660034a771f272bdba387b6af?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="https://thornbird.org" rel="external nofollow ugc" class="url">鸟叔</a></b> </cite><a href="https://laob.me/2300/#comment-30570"><time datetime="2019-01-24T21:59:43+08:00">2019年01月24日 9:59 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>这东西不敢瞎玩了。居然有人被拘留罚款了</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30570#respond" data-commentid="30570" data-postid="2300" data-belowelement="comment-30570" data-respondelement="respond" data-replyto="回复给鸟叔" aria-label="回复给鸟叔">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment odd alt depth-2" id="li-comment-30640">
		<article id="comment-30640" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/546403b056b32cb015f400875701dde6?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/546403b056b32cb015f400875701dde6?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="https://share.earnrmb.us" rel="external nofollow ugc" class="url">yamakuchi</a></b> </cite><a href="https://laob.me/2300/#comment-30640"><time datetime="2019-03-14T21:34:49+08:00">2019年03月14日 9:34 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>是不是上次那个广东的？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30640#respond" data-commentid="30640" data-postid="2300" data-belowelement="comment-30640" data-respondelement="respond" data-replyto="回复给yamakuchi" aria-label="回复给yamakuchi">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-30572">
		<article id="comment-30572" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/0b703b23d742188b837826035e3aba39?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/0b703b23d742188b837826035e3aba39?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="https://www.mzihen.com/" rel="external nofollow ugc" class="url">子痕</a></b> </cite><a href="https://laob.me/2300/#comment-30572"><time datetime="2019-01-29T13:01:11+08:00">2019年01月29日 1:01 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>教程很详细</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30572#respond" data-commentid="30572" data-postid="2300" data-belowelement="comment-30572" data-respondelement="respond" data-replyto="回复给子痕" aria-label="回复给子痕">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30678">
		<article id="comment-30678" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/f3d1e4bc14ef38b7f2e0a7d8538ee83f?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/f3d1e4bc14ef38b7f2e0a7d8538ee83f?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">公众号：宁宁数码</b> </cite><a href="https://laob.me/2300/#comment-30678"><time datetime="2019-04-21T20:09:57+08:00">2019年04月21日 8:09 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>看昵称，我有方法直接安装小火箭</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30678#respond" data-commentid="30678" data-postid="2300" data-belowelement="comment-30678" data-respondelement="respond" data-replyto="回复给公众号：宁宁数码" aria-label="回复给公众号：宁宁数码">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment even depth-2" id="li-comment-30751">
		<article id="comment-30751" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/01dfcebf8b1d1630f600a673f72e3a8c?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/01dfcebf8b1d1630f600a673f72e3a8c?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">小霸王</b> </cite><a href="https://laob.me/2300/#comment-30751"><time datetime="2019-08-24T15:04:22+08:00">2019年08月24日 3:04 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>怎么联系</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30751#respond" data-commentid="30751" data-postid="2300" data-belowelement="comment-30751" data-respondelement="respond" data-replyto="回复给小霸王" aria-label="回复给小霸王">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment odd alt thread-even depth-1" id="li-comment-30693">
		<article id="comment-30693" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/12182e18247c3646a2d370db8ac19f36?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/12182e18247c3646a2d370db8ac19f36?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">owen</b> </cite><a href="https://laob.me/2300/#comment-30693"><time datetime="2019-05-23T19:26:10+08:00">2019年05月23日 7:26 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>想和大佬谈一下商业合作</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30693#respond" data-commentid="30693" data-postid="2300" data-belowelement="comment-30693" data-respondelement="respond" data-replyto="回复给owen" aria-label="回复给owen">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor even depth-2" id="li-comment-30723">
		<article id="comment-30723" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-30723"><time datetime="2019-07-02T15:35:08+08:00">2019年07月2日 3:35 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>什么合作</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30723#respond" data-commentid="30723" data-postid="2300" data-belowelement="comment-30723" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30700">
		<article id="comment-30700" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/b642b4217b34b1e8d3bd915fc65c4452?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/b642b4217b34b1e8d3bd915fc65c4452?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">test</b> </cite><a href="https://laob.me/2300/#comment-30700"><time datetime="2019-05-31T21:44:58+08:00">2019年05月31日 9:44 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>请问修复分组节点作用是？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30700#respond" data-commentid="30700" data-postid="2300" data-belowelement="comment-30700" data-respondelement="respond" data-replyto="回复给test" aria-label="回复给test">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-30716">
		<article id="comment-30716" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/fb3f2c62da7f648f2681f53c2f76b72f?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/fb3f2c62da7f648f2681f53c2f76b72f?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me/2300/#more-2300" rel="external nofollow ugc" class="url">南风</a></b> </cite><a href="https://laob.me/2300/#comment-30716"><time datetime="2019-06-22T22:30:30+08:00">2019年06月22日 10:30 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>我的iOS配置完还是无法连接，怎么解决啊</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30716#respond" data-commentid="30716" data-postid="2300" data-belowelement="comment-30716" data-respondelement="respond" data-replyto="回复给南风" aria-label="回复给南风">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30727">
		<article id="comment-30727" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/12182e18247c3646a2d370db8ac19f36?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/12182e18247c3646a2d370db8ac19f36?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">owen</b> </cite><a href="https://laob.me/2300/#comment-30727"><time datetime="2019-07-13T19:09:00+08:00">2019年07月13日 7:09 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>想和您商谈一下合作事宜，谢谢。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30727#respond" data-commentid="30727" data-postid="2300" data-belowelement="comment-30727" data-respondelement="respond" data-replyto="回复给owen" aria-label="回复给owen">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor even depth-2" id="li-comment-30765">
		<article id="comment-30765" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-30765"><time datetime="2019-10-17T10:06:27+08:00">2019年10月17日 10:06 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>合作什么？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30765#respond" data-commentid="30765" data-postid="2300" data-belowelement="comment-30765" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment odd alt depth-3" id="li-comment-34256">
		<article id="comment-34256" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/5d27b05c043adaf7c9f628a3a5334a12?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/5d27b05c043adaf7c9f628a3a5334a12?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">ds</b> </cite><a href="https://laob.me/2300/#comment-34256"><time datetime="2022-01-24T18:20:48+08:00">2022年01月24日 6:20 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>IPC failled 怎么解决？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=34256#respond" data-commentid="34256" data-postid="2300" data-belowelement="comment-34256" data-respondelement="respond" data-replyto="回复给ds" aria-label="回复给ds">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-30728">
		<article id="comment-30728" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/14ff74f17b52c4c4e1e874618bd62ff3?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/14ff74f17b52c4c4e1e874618bd62ff3?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://none" rel="external nofollow ugc" class="url">hei zai</a></b> </cite><a href="https://laob.me/2300/#comment-30728"><time datetime="2019-07-23T13:39:33+08:00">2019年07月23日 1:39 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>感觉还行， 不过我一直用免费的，Potatso 和 BaseVPN， BaseVPN 更好些，还有免费线路。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30728#respond" data-commentid="30728" data-postid="2300" data-belowelement="comment-30728" data-respondelement="respond" data-replyto="回复给hei zai" aria-label="回复给hei zai">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30750">
		<article id="comment-30750" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/ae451cc91ec1cc806867935fe040310c?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/ae451cc91ec1cc806867935fe040310c?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">吴先生</b> </cite><a href="https://laob.me/2300/#comment-30750"><time datetime="2019-08-23T12:58:19+08:00">2019年08月23日 12:58 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>你好，为什么我的小火箭每次都是下载的时候能用一下，后面一直显示超时、不管哪个节点都是显示超时！请问是什么原因，我同事的手机是别人帮她弄的，现在用的还是正常的，我下载了几个版本都是一样，用了一下子就显示超时。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30750#respond" data-commentid="30750" data-postid="2300" data-belowelement="comment-30750" data-respondelement="respond" data-replyto="回复给吴先生" aria-label="回复给吴先生">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment even depth-2" id="li-comment-30759">
		<article id="comment-30759" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6db1e873fced2cce79c367bdc22270c5?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6db1e873fced2cce79c367bdc22270c5?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">USA</b> </cite><a href="https://laob.me/2300/#comment-30759"><time datetime="2019-10-09T23:35:45+08:00">2019年10月9日 11:35 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>节点不能用了呗</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30759#respond" data-commentid="30759" data-postid="2300" data-belowelement="comment-30759" data-respondelement="respond" data-replyto="回复给USA" aria-label="回复给USA">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment odd alt thread-even depth-1" id="li-comment-30775">
		<article id="comment-30775" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/7b5e95f66a2214ce10123ed2949d16b5?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/7b5e95f66a2214ce10123ed2949d16b5?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">UK</b> </cite><a href="https://laob.me/2300/#comment-30775"><time datetime="2019-11-04T10:55:49+08:00">2019年11月4日 10:55 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>三，安装证书及开启HTTPS  新版本已经找不到这个证书功能了。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30775#respond" data-commentid="30775" data-postid="2300" data-belowelement="comment-30775" data-respondelement="respond" data-replyto="回复给UK" aria-label="回复给UK">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even thread-odd thread-alt depth-1" id="li-comment-30781">
		<article id="comment-30781" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/f904a32e98607e3ad1b25fbcdd395a7e?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/f904a32e98607e3ad1b25fbcdd395a7e?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">Tanky</b> </cite><a href="https://laob.me/2300/#comment-30781"><time datetime="2019-11-29T21:52:41+08:00">2019年11月29日 9:52 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>请问一下，如果我分享节点给朋友用，我可以控制节点的使用时长吗？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30781#respond" data-commentid="30781" data-postid="2300" data-belowelement="comment-30781" data-respondelement="respond" data-replyto="回复给Tanky" aria-label="回复给Tanky">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor odd alt depth-2" id="li-comment-30795">
		<article id="comment-30795" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-30795"><time datetime="2020-01-07T17:40:44+08:00">2020年01月7日 5:40 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>不可以</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30795#respond" data-commentid="30795" data-postid="2300" data-belowelement="comment-30795" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="pingback even thread-even depth-1" id="comment-30807">
		<p>Pingback引用通告： <a href="http://www.quanzi.de/1162.html" rel="external nofollow ugc" class="url">“小火箭”使用教程 - 权子的 QUANZI.DE</a> </p>
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30808">
		<article id="comment-30808" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/9795ceaa1b38c311e7924ef5d7cf383a?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/9795ceaa1b38c311e7924ef5d7cf383a?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">Jack L</b> </cite><a href="https://laob.me/2300/#comment-30808"><time datetime="2020-02-10T13:37:57+08:00">2020年02月10日 1:37 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>为什么我用小火箭加载带用户名密码那种socks5代理，可以PING通，但是浏览器打不开网址呢。我直接用的全局代理模式。求指导。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30808#respond" data-commentid="30808" data-postid="2300" data-belowelement="comment-30808" data-respondelement="respond" data-replyto="回复给Jack L" aria-label="回复给Jack L">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-30830">
		<article id="comment-30830" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/123c7d40d692f8310d7ae85ce64365dd?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/123c7d40d692f8310d7ae85ce64365dd?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">frank</b> </cite><a href="https://laob.me/2300/#comment-30830"><time datetime="2020-04-02T13:37:35+08:00">2020年04月2日 1:37 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>有人告诉我怎么在mac上用小火箭吗</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30830#respond" data-commentid="30830" data-postid="2300" data-belowelement="comment-30830" data-respondelement="respond" data-replyto="回复给frank" aria-label="回复给frank">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30840">
		<article id="comment-30840" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/2424eef43cf470e6c00041d8080f8524?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/2424eef43cf470e6c00041d8080f8524?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">chen</b> </cite><a href="https://laob.me/2300/#comment-30840"><time datetime="2020-04-15T10:32:27+08:00">2020年04月15日 10:32 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>博主接广告吗</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30840#respond" data-commentid="30840" data-postid="2300" data-belowelement="comment-30840" data-respondelement="respond" data-replyto="回复给chen" aria-label="回复给chen">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor even depth-2" id="li-comment-30859">
		<article id="comment-30859" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-30859"><time datetime="2020-06-29T10:20:43+08:00">2020年06月29日 10:20 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>邮箱联系</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30859#respond" data-commentid="30859" data-postid="2300" data-belowelement="comment-30859" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment odd alt depth-3" id="li-comment-32346">
		<article id="comment-32346" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/1630d5558b5258aecb96eb9dbbf1b16a?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/1630d5558b5258aecb96eb9dbbf1b16a?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">Max</b> </cite><a href="https://laob.me/2300/#comment-32346"><time datetime="2021-07-10T11:41:48+08:00">2021年07月10日 11:41 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>您邮箱是多少？我的url的配置链接说无法获取订阅我想发您问下</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32346#respond" data-commentid="32346" data-postid="2300" data-belowelement="comment-32346" data-respondelement="respond" data-replyto="回复给Max" aria-label="回复给Max">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-30853">
		<article id="comment-30853" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/cbbe656c7bb46772f589c9b18a7c747e?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/cbbe656c7bb46772f589c9b18a7c747e?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="https://www.shephe.com" rel="external nofollow ugc" class="url">牧羊人</a></b> </cite><a href="https://laob.me/2300/#comment-30853"><time datetime="2020-06-17T09:13:50+08:00">2020年06月17日 9:13 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>我在用最新版本的这个软件，我觉得它的 代理配置文件有些问题，我想问问啊：如何修改配置，只让部分域名（比如g）代理，其他的域名、IP都采用直连方式呢？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30853#respond" data-commentid="30853" data-postid="2300" data-belowelement="comment-30853" data-respondelement="respond" data-replyto="回复给牧羊人" aria-label="回复给牧羊人">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="pingback odd alt thread-odd thread-alt depth-1" id="comment-30858">
		<p>Pingback引用通告： <a href="https://yunsw.cc/ssshadowsocks-ssrshadowsocksr%ef%bc%89%e5%ae%a2%e6%88%b7%e7%ab%af%e4%b8%80%e8%a7%88/251.html" rel="external nofollow ugc" class="url">SS(Shadowsocks)/SSR(ShadowsocksR）客户端一览 - 云上网</a> </p>
				</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-30883">
		<article id="comment-30883" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/8a23a4ceabfc5cdc7177f010abec596f?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/8a23a4ceabfc5cdc7177f010abec596f?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">冯嘉俊</b> </cite><a href="https://laob.me/2300/#comment-30883"><time datetime="2020-07-15T14:01:17+08:00">2020年07月15日 2:01 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>打不开   还有吗？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30883#respond" data-commentid="30883" data-postid="2300" data-belowelement="comment-30883" data-respondelement="respond" data-replyto="回复给冯嘉俊" aria-label="回复给冯嘉俊">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30901">
		<article id="comment-30901" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/364bdd2107eff62d09503c4531563d82?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/364bdd2107eff62d09503c4531563d82?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">Cheney</b> </cite><a href="https://laob.me/2300/#comment-30901"><time datetime="2020-09-27T22:37:27+08:00">2020年09月27日 10:37 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>同一个URL可以在不同设备使用吗</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30901#respond" data-commentid="30901" data-postid="2300" data-belowelement="comment-30901" data-respondelement="respond" data-replyto="回复给Cheney" aria-label="回复给Cheney">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor even depth-2" id="li-comment-30903">
		<article id="comment-30903" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-30903"><time datetime="2020-09-29T15:01:32+08:00">2020年09月29日 3:01 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>上面有说明，同时在线ＩＰ限制。有写限制的数量</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30903#respond" data-commentid="30903" data-postid="2300" data-belowelement="comment-30903" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment odd alt thread-even depth-1" id="li-comment-30921">
		<article id="comment-30921" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/849a63820e35563d197010754fb35db2?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/849a63820e35563d197010754fb35db2?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">Jingfei Wang</b> </cite><a href="https://laob.me/2300/#comment-30921"><time datetime="2020-11-01T17:52:03+08:00">2020年11月1日 5:52 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>hello, 请问我在vultr上买了节点, 但是不会搭建到小火箭上….. 我是白痴… 不知道端口怎么输入….</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30921#respond" data-commentid="30921" data-postid="2300" data-belowelement="comment-30921" data-respondelement="respond" data-replyto="回复给Jingfei Wang" aria-label="回复给Jingfei Wang">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor even depth-2" id="li-comment-30926">
		<article id="comment-30926" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-30926"><time datetime="2020-11-12T10:15:36+08:00">2020年11月12日 10:15 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>买个现成的机场不香吗？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30926#respond" data-commentid="30926" data-postid="2300" data-belowelement="comment-30926" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment odd alt depth-3" id="li-comment-30932">
		<article id="comment-30932" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/38defc2440fe7cdc750c1f34b732def3?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/38defc2440fe7cdc750c1f34b732def3?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">毕金超</b> </cite><a href="https://laob.me/2300/#comment-30932"><time datetime="2020-11-24T16:06:51+08:00">2020年11月24日 4:06 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>我叫毕金超，加个微信呗</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30932#respond" data-commentid="30932" data-postid="2300" data-belowelement="comment-30932" data-respondelement="respond" data-replyto="回复给毕金超" aria-label="回复给毕金超">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even depth-3" id="li-comment-31584">
		<article id="comment-31584" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/ae2a5a0ea9de71b41e128b12a73795f8?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/ae2a5a0ea9de71b41e128b12a73795f8?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">bbccxx</b> </cite><a href="https://laob.me/2300/#comment-31584"><time datetime="2021-03-19T17:16:41+08:00">2021年03月19日 5:16 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>现成的机场在哪里买？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31584#respond" data-commentid="31584" data-postid="2300" data-belowelement="comment-31584" data-respondelement="respond" data-replyto="回复给bbccxx" aria-label="回复给bbccxx">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor odd alt depth-4" id="li-comment-31673">
		<article id="comment-31673" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-31673"><time datetime="2021-03-26T09:52:00+08:00">2021年03月26日 9:52 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>侧边或者底部广告位</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31673#respond" data-commentid="31673" data-postid="2300" data-belowelement="comment-31673" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-odd thread-alt depth-1" id="li-comment-30927">
		<article id="comment-30927" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/e82e2e28ac7fcfeec547a72f4c587c52?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/e82e2e28ac7fcfeec547a72f4c587c52?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">擎鳯</b> </cite><a href="https://laob.me/2300/#comment-30927"><time datetime="2020-11-12T16:44:39+08:00">2020年11月12日 4:44 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>牛逼的博客都在境外论坛，作者写的非常详细。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30927#respond" data-commentid="30927" data-postid="2300" data-belowelement="comment-30927" data-respondelement="respond" data-replyto="回复给擎鳯" aria-label="回复给擎鳯">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-even depth-1" id="li-comment-30937">
		<article id="comment-30937" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/aa6d66bd7872a4cda14a646256192fb7?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/aa6d66bd7872a4cda14a646256192fb7?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">htx</b> </cite><a href="https://laob.me/2300/#comment-30937"><time datetime="2020-12-03T12:28:22+08:00">2020年12月3日 12:28 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>mac可用么</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=30937#respond" data-commentid="30937" data-postid="2300" data-belowelement="comment-30937" data-respondelement="respond" data-replyto="回复给htx" aria-label="回复给htx">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even thread-odd thread-alt depth-1" id="li-comment-31123">
		<article id="comment-31123" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/ba83fa02fc4b2ba621514941307e21be?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/ba83fa02fc4b2ba621514941307e21be?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="https://immmmm.com" rel="external nofollow ugc" class="url">林木木</a></b> </cite><a href="https://laob.me/2300/#comment-31123"><time datetime="2021-02-13T21:45:38+08:00">2021年02月13日 9:45 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>搜了一圈，到这来了！</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31123#respond" data-commentid="31123" data-postid="2300" data-belowelement="comment-31123" data-respondelement="respond" data-replyto="回复给林木木" aria-label="回复给林木木">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor odd alt depth-2" id="li-comment-31124">
		<article id="comment-31124" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-31124"><time datetime="2021-02-14T23:03:52+08:00">2021年02月14日 11:03 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>哈哈，很简单啊。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31124#respond" data-commentid="31124" data-postid="2300" data-belowelement="comment-31124" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-31178">
		<article id="comment-31178" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/f9bebda1885af841fd7b8bf30500c1d4?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/f9bebda1885af841fd7b8bf30500c1d4?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="https://www.92huayi.com" rel="external nofollow ugc" class="url">gongxuwang</a></b> </cite><a href="https://laob.me/2300/#comment-31178"><time datetime="2021-02-19T01:44:06+08:00">2021年02月19日 1:44 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>倍感珍惜谢谢博主</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31178#respond" data-commentid="31178" data-postid="2300" data-belowelement="comment-31178" data-respondelement="respond" data-replyto="回复给gongxuwang" aria-label="回复给gongxuwang">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-31735">
		<article id="comment-31735" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/1b20041be14afdc4365cfc7b665c7bd1?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/1b20041be14afdc4365cfc7b665c7bd1?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">粂原</b> </cite><a href="https://laob.me/2300/#comment-31735"><time datetime="2021-04-03T22:23:38+08:00">2021年04月3日 10:23 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>侧边或底部广告位，没看到买机场的广告怎么办？因为没有广告。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31735#respond" data-commentid="31735" data-postid="2300" data-belowelement="comment-31735" data-respondelement="respond" data-replyto="回复给粂原" aria-label="回复给粂原">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-31736">
		<article id="comment-31736" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/1b20041be14afdc4365cfc7b665c7bd1?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/1b20041be14afdc4365cfc7b665c7bd1?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">粂原</b> </cite><a href="https://laob.me/2300/#comment-31736"><time datetime="2021-04-03T23:44:17+08:00">2021年04月3日 11:44 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>嗯，成功配置好节点了。但是我想要日本的原生IP节点，虽然找到有卖的人，但他那好贵啊。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31736#respond" data-commentid="31736" data-postid="2300" data-belowelement="comment-31736" data-respondelement="respond" data-replyto="回复给粂原" aria-label="回复给粂原">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-31835">
		<article id="comment-31835" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/e49a0c37162d677341beaa148323bb5a?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/e49a0c37162d677341beaa148323bb5a?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">Cyan</b> </cite><a href="https://laob.me/2300/#comment-31835"><time datetime="2021-04-12T14:34:12+08:00">2021年04月12日 2:34 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>没看到广告位啊博主老大，求节点购买地址。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31835#respond" data-commentid="31835" data-postid="2300" data-belowelement="comment-31835" data-respondelement="respond" data-replyto="回复给Cyan" aria-label="回复给Cyan">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor even depth-2" id="li-comment-31861">
		<article id="comment-31861" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-31861"><time datetime="2021-04-21T14:53:41+08:00">2021年04月21日 2:53 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>最下面</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31861#respond" data-commentid="31861" data-postid="2300" data-belowelement="comment-31861" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment odd alt depth-3" id="li-comment-32618">
		<article id="comment-32618" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/1e4e88ac8a4d0cd47195a942ebc283fa?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/1e4e88ac8a4d0cd47195a942ebc283fa?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">袁sir</b> </cite><a href="https://laob.me/2300/#comment-32618"><time datetime="2021-08-10T15:11:56+08:00">2021年08月10日 3:11 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>真的没有广告啊</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32618#respond" data-commentid="32618" data-postid="2300" data-belowelement="comment-32618" data-respondelement="respond" data-replyto="回复给袁sir" aria-label="回复给袁sir">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-31900">
		<article id="comment-31900" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/ac190f71bc82d66f49acc3e6b9c23026?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/ac190f71bc82d66f49acc3e6b9c23026?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">zekeoo</b> </cite><a href="https://laob.me/2300/#comment-31900"><time datetime="2021-05-01T19:00:20+08:00">2021年05月1日 7:00 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>21年了有好用稳定更新的规则推荐吗？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31900#respond" data-commentid="31900" data-postid="2300" data-belowelement="comment-31900" data-respondelement="respond" data-replyto="回复给zekeoo" aria-label="回复给zekeoo">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor odd alt depth-2" id="li-comment-32097">
		<article id="comment-32097" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-32097"><time datetime="2021-06-08T21:24:37+08:00">2021年06月8日 9:24 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>用机场自带的规则~</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32097#respond" data-commentid="32097" data-postid="2300" data-belowelement="comment-32097" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-odd thread-alt depth-1" id="li-comment-31924">
		<article id="comment-31924" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/2adf059ade997c7c2204d3ae576d35b5?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/2adf059ade997c7c2204d3ae576d35b5?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">s s</b> </cite><a href="https://laob.me/2300/#comment-31924"><time datetime="2021-05-05T19:41:57+08:00">2021年05月5日 7:41 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>救命啊，连好了vpn却上不了外网</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=31924#respond" data-commentid="31924" data-postid="2300" data-belowelement="comment-31924" data-respondelement="respond" data-replyto="回复给s s" aria-label="回复给s s">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment byuser comment-author-soolby bypostauthor odd alt thread-even depth-1" id="li-comment-32098">
		<article id="comment-32098" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-32098"><time datetime="2021-06-08T21:24:49+08:00">2021年06月8日 9:24 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>规则的问题吧</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32098#respond" data-commentid="32098" data-postid="2300" data-belowelement="comment-32098" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even thread-odd thread-alt depth-1" id="li-comment-32111">
		<article id="comment-32111" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/8d27865b58506605c56ad9e7fb8eb351?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/8d27865b58506605c56ad9e7fb8eb351?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">help me</b> </cite><a href="https://laob.me/2300/#comment-32111"><time datetime="2021-06-09T15:05:18+08:00">2021年06月9日 3:05 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>问题，Shadowrocket2.112版本不能用 。那里可以下载更新？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32111#respond" data-commentid="32111" data-postid="2300" data-belowelement="comment-32111" data-respondelement="respond" data-replyto="回复给help me" aria-label="回复给help me">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment byuser comment-author-soolby bypostauthor odd alt depth-2" id="li-comment-32113">
		<article id="comment-32113" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/6433c44f9626fc666c8a268cf56a79db?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn"><a href="http://laob.me" rel="external nofollow ugc" class="url">毕扬</a></b> <span>文章作者</span></cite><a href="https://laob.me/2300/#comment-32113"><time datetime="2021-06-09T15:18:26+08:00">2021年06月9日 3:18 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>美区</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32113#respond" data-commentid="32113" data-postid="2300" data-belowelement="comment-32113" data-respondelement="respond" data-replyto="回复给毕扬" aria-label="回复给毕扬">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment even depth-3" id="li-comment-33908">
		<article id="comment-33908" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/38defc2440fe7cdc750c1f34b732def3?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/38defc2440fe7cdc750c1f34b732def3?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">毕</b> </cite><a href="https://laob.me/2300/#comment-33908"><time datetime="2021-12-06T19:11:55+08:00">2021年12月6日 7:11 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>我也姓毕，想加一家子，7525935微信</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=33908#respond" data-commentid="33908" data-postid="2300" data-belowelement="comment-33908" data-respondelement="respond" data-replyto="回复给毕" aria-label="回复给毕">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment odd alt thread-even depth-1" id="li-comment-32130">
		<article id="comment-32130" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/ec2ad892d44296b92f49a251e44750a7?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/ec2ad892d44296b92f49a251e44750a7?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">1KW2</b> </cite><a href="https://laob.me/2300/#comment-32130"><time datetime="2021-06-16T21:00:34+08:00">2021年06月16日 9:00 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>不在一个WiFi局域网下 能进行代理连接吗</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32130#respond" data-commentid="32130" data-postid="2300" data-belowelement="comment-32130" data-respondelement="respond" data-replyto="回复给1KW2" aria-label="回复给1KW2">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even thread-odd thread-alt depth-1" id="li-comment-32235">
		<article id="comment-32235" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/522285a70734b4490a46f4f3c8c78746?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/522285a70734b4490a46f4f3c8c78746?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">卡扣</b> </cite><a href="https://laob.me/2300/#comment-32235"><time datetime="2021-06-26T19:15:23+08:00">2021年06月26日 7:15 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>伪装在哪里改，免流</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32235#respond" data-commentid="32235" data-postid="2300" data-belowelement="comment-32235" data-respondelement="respond" data-replyto="回复给卡扣" aria-label="回复给卡扣">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="pingback odd alt thread-even depth-1" id="comment-32368">
		<p>Pingback引用通告： <a href="https://www.moeloc.com/22.html" rel="external nofollow ugc" class="url">ss/ssr/v2ray/trojan 代理客户端推荐、大全</a> </p>
				</li><!-- #comment-## -->
		<li class="comment even thread-odd thread-alt depth-1" id="li-comment-32425">
		<article id="comment-32425" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/c9ac5ce67f5cd7f991bb92ca04041483?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/c9ac5ce67f5cd7f991bb92ca04041483?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">AI</b> </cite><a href="https://laob.me/2300/#comment-32425"><time datetime="2021-07-22T17:29:56+08:00">2021年07月22日 5:29 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>为什么苹果商店搜不到这个应用了呢？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32425#respond" data-commentid="32425" data-postid="2300" data-belowelement="comment-32425" data-respondelement="respond" data-replyto="回复给AI" aria-label="回复给AI">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				<ol class="children">
		<li class="comment odd alt depth-2" id="li-comment-32617">
		<article id="comment-32617" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/1e4e88ac8a4d0cd47195a942ebc283fa?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/1e4e88ac8a4d0cd47195a942ebc283fa?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">袁sir</b> </cite><a href="https://laob.me/2300/#comment-32617"><time datetime="2021-08-10T15:11:20+08:00">2021年08月10日 3:11 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>中国区已经没这个app了</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32617#respond" data-commentid="32617" data-postid="2300" data-belowelement="comment-32617" data-respondelement="respond" data-replyto="回复给袁sir" aria-label="回复给袁sir">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
</ol><!-- .children -->
</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-32523">
		<article id="comment-32523" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/619bc85f4c6587482687edba63887eda?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/619bc85f4c6587482687edba63887eda?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">騰融匯通</b> </cite><a href="https://laob.me/2300/#comment-32523"><time datetime="2021-08-03T22:37:02+08:00">2021年08月3日 10:37 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>安卓手机可以用吗？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32523#respond" data-commentid="32523" data-postid="2300" data-belowelement="comment-32523" data-respondelement="respond" data-replyto="回复给騰融匯通" aria-label="回复给騰融匯通">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-32843">
		<article id="comment-32843" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/b1af7276f719359b66ad31b4a94ab68e?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/b1af7276f719359b66ad31b4a94ab68e?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">闻人落槿</b> </cite><a href="https://laob.me/2300/#comment-32843"><time datetime="2021-09-01T07:55:05+08:00">2021年09月1日 7:55 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>配置那里点击使用，总提示未完成该操作，无效的自变量。然后我又开了梯子点，出现not found。就是你给的配置地质</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=32843#respond" data-commentid="32843" data-postid="2300" data-belowelement="comment-32843" data-respondelement="respond" data-replyto="回复给闻人落槿" aria-label="回复给闻人落槿">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-34523">
		<article id="comment-34523" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/112e8bf5fb07aeb25991d08dbb384d98?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/112e8bf5fb07aeb25991d08dbb384d98?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">小火箭远程文件用不了什么原因？</b> </cite><a href="https://laob.me/2300/#comment-34523"><time datetime="2022-02-26T18:22:39+08:00">2022年02月26日 6:22 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>你好，请问下小火箭远程文件用不了怎么解决？</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=34523#respond" data-commentid="34523" data-postid="2300" data-belowelement="comment-34523" data-respondelement="respond" data-replyto="回复给小火箭远程文件用不了什么原因？" aria-label="回复给小火箭远程文件用不了什么原因？">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="pingback odd alt thread-odd thread-alt depth-1" id="comment-35051">
		<p>Pingback引用通告： <a href="https://datangcorp.com/200.html" rel="external nofollow ugc" class="url">“小火箭”（Shadowrocket）最全使用教程-龙图腾工作室</a> </p>
				</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-35268">
		<article id="comment-35268" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/977a2dbef7f11cd6249259a89d116c13?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/977a2dbef7f11cd6249259a89d116c13?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">阿呆</b> </cite><a href="https://laob.me/2300/#comment-35268"><time datetime="2022-06-23T08:59:21+08:00">2022年06月23日 8:59 上午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>有没有固定一个节点的方法呀。。。节点换来换去，油管 有些节目由国家限制，就时不时看不了。。。</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=35268#respond" data-commentid="35268" data-postid="2300" data-belowelement="comment-35268" data-respondelement="respond" data-replyto="回复给阿呆" aria-label="回复给阿呆">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		<li class="pingback odd alt thread-odd thread-alt depth-1" id="comment-35408">
		<p>Pingback引用通告： <a href="https://www.moe.ms/22.html" rel="external nofollow ugc" class="url">Shadowsocks,V2ray,Trojan,代理客户端推荐大全-MOE</a> </p>
				</li><!-- #comment-## -->
		<li class="comment even thread-even depth-1" id="li-comment-35527">
		<article id="comment-35527" class="comment">
			<header class="comment-meta comment-author vcard">
				<img alt="" src="https://secure.gravatar.com/avatar/a944f19d1a1966799f8104b8d5b0195e?s=44&amp;r=g" srcset="https://secure.gravatar.com/avatar/a944f19d1a1966799f8104b8d5b0195e?s=88&amp;r=g 2x" class="avatar avatar-44 photo" height="44" width="44" loading="lazy"><cite><b class="fn">略略略</b> </cite><a href="https://laob.me/2300/#comment-35527"><time datetime="2022-08-18T16:22:49+08:00">2022年08月18日 4:22 下午</time></a>				</header><!-- .comment-meta -->

				
				
				<section class="comment-content comment">
				<p>求资源</p>
								</section><!-- .comment-content -->

				<div class="reply">
				<a rel="nofollow" class="comment-reply-link" href="https://laob.me/2300/?replytocom=35527#respond" data-commentid="35527" data-postid="2300" data-belowelement="comment-35527" data-respondelement="respond" data-replyto="回复给略略略" aria-label="回复给略略略">回复</a> <span>↓</span>				</div><!-- .reply -->
			</article><!-- #comment-## -->
				</li><!-- #comment-## -->
		</ol><!-- .commentlist -->

		
		
	
		<div id="respond" class="comment-respond">
		<h3 id="reply-title" class="comment-reply-title">发表评论 <small><a rel="nofollow" id="cancel-comment-reply-link" href="/2300/#respond" style="display:none;">取消回复</a></small></h3><form action="https://laob.me/wp-comments-post.php" method="post" id="commentform" class="comment-form"><p class="comment-notes"><span id="email-notes">您的电子邮箱地址不会被公开。</span> 必填项已用<span class="required">*</span>标注</p><p class="comment-form-comment"><label for="comment">评论</label> <textarea id="comment" name="comment-bc95d0bb1610f10bc8b7d3f12bb3fe" cols="45" rows="8" maxlength="65525" required="required"></textarea><textarea name="comment" rows="1" cols="1" style="display:none"></textarea></p><input type="hidden" name="comment-replaced" value="true"><p class="comment-form-author"><label for="author">显示名称 <span class="required">*</span></label> <input id="author" name="author" type="text" value="" size="30" maxlength="245" required="required"></p>
<p class="comment-form-email"><label for="email">电子邮箱地址 <span class="required">*</span></label> <input id="email" name="email" type="text" value="" size="30" maxlength="100" aria-describedby="email-notes" required="required"></p>
<p class="comment-form-url"><label for="url">网站地址</label> <input id="url" name="url" type="text" value="" size="30" maxlength="200"></p>
<p class="comment-form-cookies-consent"><input id="wp-comment-cookies-consent" name="wp-comment-cookies-consent" type="checkbox" value="yes"> <label for="wp-comment-cookies-consent">在此浏览器中保存我的显示名称、邮箱地址和网站地址，以便下次评论时使用。</label></p>
<p class="form-submit"><input name="submit" type="submit" id="submit" class="submit" value="发表评论"> <input type="hidden" name="comment_post_ID" value="2300" id="comment_post_ID">
<input type="hidden" name="comment_parent" id="comment_parent" value="0">
</p><p style="display: none;"><input type="hidden" id="akismet_comment_nonce" name="akismet_comment_nonce" value="b6d85baa5a"></p><p style="display:none;"><input type="text" name="nxts" value="1665936457"><input type="text" name="nxts_signed" value="0fba5af96c10c9f1855e96fa0f39a185175ed88c"><input type="text" name="5f0208d60d0d01f083f337e1d501d5" value=""><input type="text" name="bcedf009e09cb0de4bc788" value="44c0d31355ab24179f2c8edf59056"></p><textarea name="ak_hp_textarea" cols="45" rows="8" maxlength="100" style="display: none !important;"></textarea><input type="hidden" id="ak_js" name="ak_js" value="1665937347407"></form>	</div><!-- #respond -->
	
</div><!-- #comments .comments-area -->

			
		</div><!-- #content -->
	</div>
