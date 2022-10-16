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
		
		
