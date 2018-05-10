
<!DOCTYPE html>



  


<html class="theme-next muse use-motion" lang="zh-Hans">
<head>
  <meta charset="UTF-8"/>
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"/>
<meta name="theme-color" content="#222">






  
  
  <link rel="stylesheet" media="all" href="/lib/Han/dist/han.min.css?v=3.3">




<meta http-equiv="Cache-Control" content="no-transform" />
<meta http-equiv="Cache-Control" content="no-siteapp" />
















  
  
  <link href="/lib/fancybox/source/jquery.fancybox.css?v=2.1.5" rel="stylesheet" type="text/css" />







<link href="/lib/font-awesome/css/font-awesome.min.css?v=4.6.2" rel="stylesheet" type="text/css" />

<link href="/css/main.css?v=5.1.4" rel="stylesheet" type="text/css" />


  <link rel="apple-touch-icon" sizes="180x180" href="/images/apple-touch-icon-next.png?v=5.1.4">


  <link rel="icon" type="image/png" sizes="32x32" href="/images/favicon-32x32-next.png?v=5.1.4">


  <link rel="icon" type="image/png" sizes="16x16" href="/images/favicon-16x16-next.png?v=5.1.4">


  <link rel="mask-icon" href="/images/logo.svg?v=5.1.4" color="#222">





  <meta name="keywords" content="主题优化,音乐外链,视频外链" />










<meta name="description" content="一个单纯只有文字和图片的网页未免太安静，怎样给你的博客添加一个音乐播放器？怎样在你的文章中添加一首应景的BGM，或者一段自己录制的音频，或者添加进去一段视频？这些都非常容易做到。 为主页添加背景音乐我们在侧边栏添加大话西游的片尾曲《一生所爱》，让别人打开我们的博客首页就开始播放这首歌。这里用添加网易云音乐外链播放器的方法来添加背景音乐（其他音乐播放器一样）。">
<meta name="keywords" content="主题优化,音乐外链,视频外链">
<meta property="og:type" content="article">
<meta property="og:title" content="如何在Hexo博客中添加音乐播放器和视频播放器">
<meta property="og:url" content="http://lc-leo.github.io/2018/01/09/如何在hexo博客中添加音乐播放器和视频播放器/index.html">
<meta property="og:site_name" content="LC.Leo">
<meta property="og:description" content="一个单纯只有文字和图片的网页未免太安静，怎样给你的博客添加一个音乐播放器？怎样在你的文章中添加一首应景的BGM，或者一段自己录制的音频，或者添加进去一段视频？这些都非常容易做到。 为主页添加背景音乐我们在侧边栏添加大话西游的片尾曲《一生所爱》，让别人打开我们的博客首页就开始播放这首歌。这里用添加网易云音乐外链播放器的方法来添加背景音乐（其他音乐播放器一样）。">
<meta property="og:locale" content="zh-Hans">
<meta property="og:image" content="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnao89ikzpj20z10s9aea.jpg">
<meta property="og:image" content="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnao9uiu83j21ny0zq427.jpg">
<meta property="og:image" content="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnaobnast4j20x50s1my4.jpg">
<meta property="og:image" content="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnao8zqosaj20tr0nrgqy.jpg">
<meta property="og:image" content="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnap1extrsj21470u9kbv.jpg">
<meta property="og:updated_time" content="2018-01-10T10:19:43.000Z">
<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="如何在Hexo博客中添加音乐播放器和视频播放器">
<meta name="twitter:description" content="一个单纯只有文字和图片的网页未免太安静，怎样给你的博客添加一个音乐播放器？怎样在你的文章中添加一首应景的BGM，或者一段自己录制的音频，或者添加进去一段视频？这些都非常容易做到。 为主页添加背景音乐我们在侧边栏添加大话西游的片尾曲《一生所爱》，让别人打开我们的博客首页就开始播放这首歌。这里用添加网易云音乐外链播放器的方法来添加背景音乐（其他音乐播放器一样）。">
<meta name="twitter:image" content="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnao89ikzpj20z10s9aea.jpg">



<script type="text/javascript" id="hexo.configurations">
  var NexT = window.NexT || {};
  var CONFIG = {
    root: '/',
    scheme: 'Muse',
    version: '5.1.4',
    sidebar: {"position":"left","display":"post","offset":12,"b2t":false,"scrollpercent":false,"onmobile":false},
    fancybox: true,
    tabs: true,
    motion: {"enable":true,"async":false,"transition":{"post_block":"fadeIn","post_header":"slideDownIn","post_body":"slideDownIn","coll_header":"slideLeftIn","sidebar":"slideUpIn"}},
    duoshuo: {
      userId: '0',
      author: '博主'
    },
    algolia: {
      applicationID: '',
      apiKey: '',
      indexName: '',
      hits: {"per_page":10},
      labels: {"input_placeholder":"Search for Posts","hits_empty":"We didn't find any results for the search: ${query}","hits_stats":"${hits} results found in ${time} ms"}
    }
  };
</script>



  <link rel="canonical" href="http://lc-leo.github.io/2018/01/09/如何在hexo博客中添加音乐播放器和视频播放器/"/>





  <title>如何在Hexo博客中添加音乐播放器和视频播放器 | LC.Leo</title>
  








</head>

<body itemscope itemtype="http://schema.org/WebPage" lang="zh-Hans">

  
  
    
  

  <div class="container sidebar-position-left page-post-detail">
    <div class="headband"></div>
  <a href="https://github.com/lc-leo"><img style="position: absolute; top: 0; left: 0; border: 0;" src="https://s3.amazonaws.com/github/ribbons/forkme_left_darkblue_121621.png" alt="Fork me on GitHub"></a>
    <header id="header" class="header" itemscope itemtype="http://schema.org/WPHeader">
      <div class="header-inner"><div class="site-brand-wrapper">
  <div class="site-meta ">
    

    <div class="custom-logo-site-title">
      <a href="/"  class="brand" rel="start">
        <span class="logo-line-before"><i></i></span>
        <span class="site-title">LC.Leo</span>
        <span class="logo-line-after"><i></i></span>
      </a>
    </div>
      
        <h1 class="site-subtitle" itemprop="description">He seems like a dog!</h1>
      
  </div>

  <div class="site-nav-toggle">
    <button>
      <span class="btn-bar"></span>
      <span class="btn-bar"></span>
      <span class="btn-bar"></span>
    </button>
  </div>
</div>

<nav class="site-nav">
  

  
    <ul id="menu" class="menu">
      
        
        <li class="menu-item menu-item-home">
          <a href="/" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-home"></i> <br />
            
            Home
          </a>
        </li>
      
        
        <li class="menu-item menu-item-about">
          <a href="/about/" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-user"></i> <br />
            
            About
          </a>
        </li>
      
        
        <li class="menu-item menu-item-tags">
          <a href="/tags/" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-tags"></i> <br />
            
            Tags
          </a>
        </li>
      
        
        <li class="menu-item menu-item-categories">
          <a href="/categories/" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-th"></i> <br />
            
            Categories
          </a>
        </li>
      
        
        <li class="menu-item menu-item-archives">
          <a href="/archives/" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-archive"></i> <br />
            
            Archives
          </a>
        </li>
      
        
        <li class="menu-item menu-item-picture">
          <a href="/picture/" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-camera-retro"></i> <br />
            
            Picture
          </a>
        </li>
      
        
        <li class="menu-item menu-item-message">
          <a href="/message/" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-comment"></i> <br />
            
            Message
          </a>
        </li>
      

      
    </ul>
  

  
</nav>



 </div>
    </header>

    <main id="main" class="main">
      <div class="main-inner">
        <div class="content-wrap">
          <div id="content" class="content">
            

  <div id="posts" class="posts-expand">
    

  

  
  
  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="http://lc-leo.github.io/2018/01/09/如何在hexo博客中添加音乐播放器和视频播放器/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="LC.Leo">
      <meta itemprop="description" content="">
      <meta itemprop="image" content="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fn7773l5c9j20ol0nydiv.jpg">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="LC.Leo">
    </span>

    
      <header class="post-header">

        
        
          <h2 class="post-title" itemprop="name headline">如何在Hexo博客中添加音乐播放器和视频播放器</h2>
        

        <div class="post-meta">
          <span class="post-time">
            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              
              <time title="创建于" itemprop="dateCreated datePublished" datetime="2018-01-09T00:00:00+08:00">
                2018-01-09
              </time>
            

            

            
          </span>

          
            <span class="post-category" >
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing">
                  <a href="/categories/Hexo/" itemprop="url" rel="index">
                    <span itemprop="name">Hexo</span>
                  </a>
                </span>

                
                
              
            </span>
          

          
            
              <span class="post-comments-count">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-comment-o"></i>
              </span>
              
                <a href="/2018/01/09/如何在hexo博客中添加音乐播放器和视频播放器/#SOHUCS" itemprop="discussionUrl">
                  <span id="changyan_count_unit" class="post-comments-count hc-comment-count" data-xid="2018/01/09/如何在hexo博客中添加音乐播放器和视频播放器/" itemprop="commentsCount"></span>
                </a>
              
            
          

          
          

          
            <span class="post-meta-divider">|</span>
            <span class="page-pv"><i class="fa fa-file-o"></i>
            <span class="busuanzi-value" id="busuanzi_value_page_pv" ></span>
            </span>
          

          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body han-init-context" itemprop="articleBody">

      
      

      
        <p>一个单纯只有文字和图片的网页未免太安静，怎样给你的博客添加一个音乐播放器？怎样在你的文章中添加一首应景的BGM，或者一段自己录制的音频，或者添加进去一段视频？<br>这些都非常容易做到。</p>
<h2 id="为主页添加背景音乐"><a href="#为主页添加背景音乐" class="headerlink" title="为主页添加背景音乐"></a>为主页添加背景音乐</h2><p>我们在侧边栏添加大话西游的片尾曲《一生所爱》，让别人打开我们的博客首页就开始播放这首歌。这里用添加网易云音乐外链播放器的方法来添加背景音乐（其他音乐播放器一样）。<br><a id="more"></a><br>1、首先打开<strong>网易云音乐网页端</strong>（注意客户端无法添加外链），登录你的账号，搜索《一生所爱》这首歌，点击播放。<br>2、在左侧看到<strong>“生成外链播放器”</strong>，点击获取外链（很多歌曲因为版权问题没法获取外链，可以尝试寻找无版权的版本）。<br><img src="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnao89ikzpj20z10s9aea.jpg" alt=""><br>3、这里可以更改音乐播放器的在你的主页中显示的尺寸，还可以选择是否自动播放(将外链代码中的auto=1改为auto=0可以取消自动播放）。这里选择iframe插件，复制地址。<br><img src="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnao9uiu83j21ny0zq427.jpg" alt=""><br>4、将外链插入到侧边栏文件<code>~/themes/next/layout/_macro/sidebar.swig</code><br>这里要注意外链代码插入的位置，比如我想把外链播放器放在侧边栏友情链接“Links”这一项之后，我就需要把代码放到Links相关代码后面。<br><img src="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnaobnast4j20x50s1my4.jpg" alt=""><br>5、若想插入自己录制的音频，先将音频上传到音乐网站，再获取外链即可。</p>
<h2 id="在文章中添加歌单"><a href="#在文章中添加歌单" class="headerlink" title="在文章中添加歌单"></a>在文章中添加歌单</h2><p>在文章中添加音乐就更简单了，直接将音乐外链插入到文章特定位置就可以了。</p>
<p><iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="330" height="86" src="//music.163.com/outchain/player?type=2&id=411356193&auto=0&height=66"></iframe><br>但如果想要分享很多首歌呢，怎样添加一个歌单呢？<br>首先将想要放到文章中的歌曲添加进一个歌单，然后打开“我的主页”，会看到“我创建的歌单”，进入歌单，便看到“生成外链播放器”了。<br><img src="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnao8zqosaj20tr0nrgqy.jpg" alt=""></p>
<h2 id="在文章中添加视频播放器"><a href="#在文章中添加视频播放器" class="headerlink" title="在文章中添加视频播放器"></a>在文章中添加视频播放器</h2><p>添加视频外链的方法同添加音乐外链一样。打开视频网站（非客户端），点击分享，复制HTML外链地址，插入到文章中就可以了。<br><img src="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fnap1extrsj21470u9kbv.jpg" alt=""><br>同样如果想插入自己录制的视频，比如一段视频教程，可以先上传视频到视频网站，然后再获取外链。</p>
<embed height="415" width="544" quality="high" allowfullscreen="true" type="application/x-shockwave-flash" src="//static.hdslb.com/miniloader.swf" flashvars="aid=17723385&page=1" pluginspage="//www.adobe.com/shockwave/download/download.cgi?P1_Prod_Version=ShockwaveFlash">

      
    </div>
    
    
    

    

    

    
      <div>
        <ul class="post-copyright">
  <li class="post-copyright-author">
    <strong>本文作者：</strong>
    LC.Leo
  </li>
  <li class="post-copyright-link">
    <strong>本文链接：</strong>
    <a href="http://lc-leo.github.io/2018/01/09/如何在hexo博客中添加音乐播放器和视频播放器/" title="如何在Hexo博客中添加音乐播放器和视频播放器">http://lc-leo.github.io/2018/01/09/如何在hexo博客中添加音乐播放器和视频播放器/</a>
  </li>
  <li class="post-copyright-license">
    <strong>版权声明： </strong>
    本博客所有文章除特别声明外，均采用 <a href="https://creativecommons.org/licenses/by-nc-sa/3.0/" rel="external nofollow" target="_blank">CC BY-NC-SA 3.0</a> 许可协议。转载请注明出处！
  </li>
</ul>

      </div>
    

    <footer class="post-footer">
      
        <div class="post-tags">
          
            <a href="/tags/hexo/" rel="tag"># hexo</a>
          
            <a href="/tags/音乐外链/" rel="tag"># 音乐外链</a>
          
            <a href="/tags/视频外链/" rel="tag"># 视频外链</a>
          
        </div>
      

      
      
        <div class="post-widgets">
        

        

        
          
          <div id="needsharebutton-postbottom">
            <span class="btn">
              <i class="fa fa-share-alt" aria-hidden="true"></i>
            </span>
          </div>
        
        </div>
      
      

      
        <div class="post-nav">
          <div class="post-nav-next post-nav-item">
            
              <a href="/2018/01/08/Hexo主页中文显示乱码以及手机端乱码的解决办法/" rel="next" title="Hexo主页中文显示乱码以及手机端乱码的解决办法">
                <i class="fa fa-chevron-left"></i> Hexo主页中文显示乱码以及手机端乱码的解决办法
              </a>
            
          </div>

          <span class="post-nav-divider"></span>

          <div class="post-nav-prev post-nav-item">
            
              <a href="/2018/01/14/马克飞象——让Markdown编辑变得得心应手/" rel="prev" title="马克飞象——让Markdown编辑变得更得心应手">
                马克飞象——让Markdown编辑变得更得心应手 <i class="fa fa-chevron-right"></i>
              </a>
            
          </div>
        </div>
      

      
      
    </footer>
  </div>
  
  
  
  </article>



    <div class="post-spread">
      
    </div>
  </div>


          </div>
          


          

  
    <div class="comments" id="comments">
      <div id="SOHUCS"></div>
    </div>

  



        </div>
        
          
  
  <div class="sidebar-toggle">
    <div class="sidebar-toggle-line-wrap">
      <span class="sidebar-toggle-line sidebar-toggle-line-first"></span>
      <span class="sidebar-toggle-line sidebar-toggle-line-middle"></span>
      <span class="sidebar-toggle-line sidebar-toggle-line-last"></span>
    </div>
  </div>

  <aside id="sidebar" class="sidebar">
    
    <div class="sidebar-inner">

      

      
        <ul class="sidebar-nav motion-element">
          <li class="sidebar-nav-toc sidebar-nav-active" data-target="post-toc-wrap">
            文章目录
          </li>
          <li class="sidebar-nav-overview" data-target="site-overview-wrap">
            站点概览
          </li>
        </ul>
      

      <section class="site-overview-wrap sidebar-panel">
        <div class="site-overview">
          <div class="site-author motion-element" itemprop="author" itemscope itemtype="http://schema.org/Person">
            
              <img class="site-author-image" itemprop="image"
                src="http://ww1.sinaimg.cn/large/a4bf5ec1ly1fn7773l5c9j20ol0nydiv.jpg"
                alt="LC.Leo" />
            
              <p class="site-author-name" itemprop="name">LC.Leo</p>
              <p class="site-description motion-element" itemprop="description"></p>
          </div>

          <nav class="site-state motion-element">

            
              <div class="site-state-item site-state-posts">
              
                <a href="/archives/">
              
                  <span class="site-state-item-count">13</span>
                  <span class="site-state-item-name">日志</span>
                </a>
              </div>
            

            
              
              
              <div class="site-state-item site-state-categories">
                <a href="/categories/index.html">
                  <span class="site-state-item-count">6</span>
                  <span class="site-state-item-name">分类</span>
                </a>
              </div>
            

            
              
              
              <div class="site-state-item site-state-tags">
                <a href="/tags/index.html">
                  <span class="site-state-item-count">13</span>
                  <span class="site-state-item-name">标签</span>
                </a>
              </div>
            

          </nav>

          

          
            <div class="links-of-author motion-element">
                
                  <span class="links-of-author-item">
                    <a href="mailto:l_c2016@outlook.com" target="_blank" title="E-Mail">
                      
                        <i class="fa fa-fw fa-envelope"></i>E-Mail</a>
                  </span>
                
                  <span class="links-of-author-item">
                    <a href="https://github.com/lc-leo" target="_blank" title="GitHub">
                      
                        <i class="fa fa-fw fa-github"></i>GitHub</a>
                  </span>
                
                  <span class="links-of-author-item">
                    <a href="http://blog.sina.com.cn/u/2764005057" target="_blank" title="Weibo">
                      
                        <i class="fa fa-fw fa-weibo"></i>Weibo</a>
                  </span>
                
                  <span class="links-of-author-item">
                    <a href="http://lc-leo.lofter.com/" target="_blank" title="Lofter">
                      
                        <i class="fa fa-fw fa-linode"></i>Lofter</a>
                  </span>
                
                  <span class="links-of-author-item">
                    <a href="https://www.jianshu.com/users/4a53e9d8c684/timeline" target="_blank" title="Jianshu">
                      
                        <i class="fa fa-fw fa-book"></i>Jianshu</a>
                  </span>
                
            </div>
          

          
          
	 
          
          
            <div class="links-of-blogroll motion-element links-of-blogroll-block">
              <div class="links-of-blogroll-title">
                <i class="fa  fa-fw fa-link"></i>
                Links
              </div>
              <ul class="links-of-blogroll-list">
                
                  <li class="links-of-blogroll-item">
                    <a href="https://uzer.me/z/apps" title="UZER.ME" target="_blank">UZER.ME</a>
                  </li>
                
                  <li class="links-of-blogroll-item">
                    <a href="https://sspai.com/?utm_source=infinitynewtab" title="少数π" target="_blank">少数π</a>
                  </li>
                
                  <li class="links-of-blogroll-item">
                    <a href="http://theme-next.iissnan.com/" title="Next" target="_blank">Next</a>
                  </li>
                
              </ul>
            </div>
          

  	  <div id="music163player">
      	      <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=298 height=52 src="//music.163.com/outchain/player?type=2&id=110771&auto=0&height=32">
              </iframe>
  	  </div>

          

        </div>
      </section>

      
      <!--noindex-->
        <section class="post-toc-wrap motion-element sidebar-panel sidebar-panel-active">
          <div class="post-toc">

            
              
            

            
              <div class="post-toc-content"><ol class="nav"><li class="nav-item nav-level-2"><a class="nav-link" href="#为主页添加背景音乐"><span class="nav-number">1.</span> <span class="nav-text">为主页添加背景音乐</span></a></li><li class="nav-item nav-level-2"><a class="nav-link" href="#在文章中添加歌单"><span class="nav-number">2.</span> <span class="nav-text">在文章中添加歌单</span></a></li><li class="nav-item nav-level-2"><a class="nav-link" href="#在文章中添加视频播放器"><span class="nav-number">3.</span> <span class="nav-text">在文章中添加视频播放器</span></a></li></ol></div>
            

          </div>
        </section>
      <!--/noindex-->
      

      

    </div>
  </aside>



        
      </div>
    </main>

    <footer id="footer" class="footer">
      <div class="footer-inner">
        <div class="copyright">&copy; <span itemprop="copyrightYear">2018</span>
  <span class="with-love">
    <i class="fa fa-plane"></i>
  </span>
  <span class="author" itemprop="copyrightHolder">LC.Leo</span>

  
</div>


  <div class="powered-by">Powered by <a class="theme-link" target="_blank" href="https://hexo.io">Hexo</a></div>



  <span class="post-meta-divider">|</span>



  <div class="theme-info">Theme &mdash; <a class="theme-link" target="_blank" href="https://github.com/iissnan/hexo-theme-next">NexT.Muse</a> v5.1.4</div>




        
<div class="busuanzi-count">
  <script async src="https://dn-lbstatics.qbox.me/busuanzi/2.3/busuanzi.pure.mini.js"></script>

  
    <span class="site-uv">
      <i class="fa fa-user"></i>
      <span class="busuanzi-value" id="busuanzi_value_site_uv"></span>
      
    </span>
  

  
    <span class="site-pv">
      <i class="fa fa-eye"></i>
      <span class="busuanzi-value" id="busuanzi_value_site_pv"></span>
      
    </span>
  
</div>








        
      </div>
    </footer>

    
      <div class="back-to-top">
        <i class="fa fa-arrow-up"></i>
        
      </div>
    

    

  </div>

  

<script type="text/javascript">
  if (Object.prototype.toString.call(window.Promise) !== '[object Function]') {
    window.Promise = null;
  }
</script>









  


  











  
  
    <script type="text/javascript" src="/lib/jquery/index.js?v=2.1.3"></script>
  

  
  
    <script type="text/javascript" src="/lib/fastclick/lib/fastclick.min.js?v=1.0.6"></script>
  

  
  
    <script type="text/javascript" src="/lib/jquery_lazyload/jquery.lazyload.js?v=1.9.7"></script>
  

  
  
    <script type="text/javascript" src="/lib/velocity/velocity.min.js?v=1.2.1"></script>
  

  
  
    <script type="text/javascript" src="/lib/velocity/velocity.ui.min.js?v=1.2.1"></script>
  

  
  
    <script type="text/javascript" src="/lib/fancybox/source/jquery.fancybox.pack.js?v=2.1.5"></script>
  

  
  
    <script type="text/javascript" src="/lib/canvas-nest/canvas-nest.min.js"></script>
  


  


  <script type="text/javascript" src="/js/src/utils.js?v=5.1.4"></script>

  <script type="text/javascript" src="/js/src/motion.js?v=5.1.4"></script>



  
  

  
  <script type="text/javascript" src="/js/src/scrollspy.js?v=5.1.4"></script>
<script type="text/javascript" src="/js/src/post-details.js?v=5.1.4"></script>



  


  <script type="text/javascript" src="/js/src/bootstrap.js?v=5.1.4"></script>



  


  




	





  





  




  
    <script type="text/javascript">
    (function(){
      var appid = 'cytoPLAxA';
      var conf = '6dd32cd258672e5452ec4037dc192346';
      var width = window.innerWidth || document.documentElement.clientWidth;
      if (width < 960) {
      window.document.write('<script id="changyan_mobile_js" charset="utf-8" type="text/javascript" src="https://changyan.sohu.com/upload/mobile/wap-js/changyan_mobile.js?client_id=' + appid + '&conf=' + conf + '"><\/script>'); } else { var loadJs=function(d,a){var c=document.getElementsByTagName("head")[0]||document.head||document.documentElement;var b=document.createElement("script");b.setAttribute("type","text/javascript");b.setAttribute("charset","UTF-8");b.setAttribute("src",d);if(typeof a==="function"){if(window.attachEvent){b.onreadystatechange=function(){var e=b.readyState;if(e==="loaded"||e==="complete"){b.onreadystatechange=null;a()}}}else{b.onload=a}}c.appendChild(b)};loadJs("https://changyan.sohu.com/upload/changyan.js",function(){
        window.changyan.api.config({appid:appid,conf:conf})});
      }
    })();
    </script>
    <script type="text/javascript" src="https://assets.changyan.sohu.com/upload/plugins/plugins.count.js"></script>
  









  





  

  

  

  
  
  
  <link rel="stylesheet" href="/lib/needsharebutton/needsharebutton.css">

  
  
  <script src="/lib/needsharebutton/needsharebutton.js"></script>

  <script>
    
      pbOptions = {};
      
          pbOptions.iconStyle = "box";
      
          pbOptions.boxForm = "horizontal";
      
          pbOptions.position = "bottomCenter";
      
          pbOptions.networks = "Weibo,Wechat,Douban,QQZone,Twitter,Facebook";
      
      new needShareButton('#needsharebutton-postbottom', pbOptions);
    
    
  </script>

  

  
  


  

  

</body>
</html>
