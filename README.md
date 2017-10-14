





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-d7137690e30123bade38abb082ac79f36cc7a105ff92e602405f53b725465cab.css" integrity="sha256-1xN2kOMBI7reOKuwgqx582zHoQX/kuYCQF9TtyVGXKs=" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-7a6d219bc4266e5db3eb55793bd9e9aa29d52d9e430f7493a8cfd1fc3a4f3509.css" integrity="sha256-em0hm8Qmbl2z61V5O9npqinVLZ5DD3STqM/R/DpPNQk=" media="all" rel="stylesheet" />
  
  
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/site-9628bfea02884cc06cee3aa24062d81f93e06de09ed5bac5557deb155500e539.css" integrity="sha256-lii/6gKITMBs7jqiQGLYH5PgbeCe1brFVX3rFVUA5Tk=" media="all" rel="stylesheet" />
  

  <meta name="viewport" content="width=device-width">
  
  <title>swift-style-guide/README.md at master · github/swift-style-guide · GitHub</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars3.githubusercontent.com/u/9919?s=400&amp;v=4" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="github/swift-style-guide" property="og:title" /><meta content="https://github.com/github/swift-style-guide" property="og:url" /><meta content="swift-style-guide - Style guide &amp; coding conventions for Swift projects" property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="DB2E:4D6A:210AE1D:2EA199D:59E28E8B" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

  <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="DB2E:4D6A:210AE1D:2EA199D:59E28E8B" name="octolytics-dimension-request_id" /><meta content="iad" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged Out">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="NTFjOWIwODNhODNkMDEzOWQyMTgwMTA4YmRkOGQ0M2I4MTAxYzUyODE0NzM3ODJhYWQyNTIwOWI0ZjRhZDkxMXx7InJlbW90ZV9hZGRyZXNzIjoiMTQ2LjExMS4zMC4xOTMiLCJyZXF1ZXN0X2lkIjoiREIyRTo0RDZBOjIxMEFFMUQ6MkVBMTk5RDo1OUUyOEU4QiIsInRpbWVzdGFtcCI6MTUwODAxOTg1MSwiaG9zdCI6ImdpdGh1Yi5jb20ifQ==">


  <meta name="html-safe-nonce" content="4f84b3496a9856aac569427d0480915084c45f1a">

  <meta http-equiv="x-pjax-version" content="81c76bc585b026a8fc6cc71efeb53002">
  

      <link href="https://github.com/github/swift-style-guide/commits/master.atom" rel="alternate" title="Recent Commits to swift-style-guide:master" type="application/atom+xml">

  <meta name="description" content="swift-style-guide - Style guide &amp; coding conventions for Swift projects">
  <meta name="go-import" content="github.com/github/swift-style-guide git https://github.com/github/swift-style-guide.git">

  <meta content="9919" name="octolytics-dimension-user_id" /><meta content="github" name="octolytics-dimension-user_login" /><meta content="21782593" name="octolytics-dimension-repository_id" /><meta content="github/swift-style-guide" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="21782593" name="octolytics-dimension-repository_network_root_id" /><meta content="github/swift-style-guide" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/github/swift-style-guide/blob/master/README.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  </head>

  <body class="logged-out env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="px-2 py-4 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        <header class="Header header-logged-out  position-relative f4 py-3" role="banner">
  <div class="container-lg d-flex px-3">
    <div class="d-flex flex-justify-between flex-items-center">
      <a class="header-logo-invertocat my-0" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
        <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
      </a>

    </div>

    <div class="HeaderMenu HeaderMenu--bright d-flex flex-justify-between flex-auto">
        <nav class="mt-0">
          <ul class="d-flex list-style-none">
              <li class="ml-2">
                <a href="/features" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:features" data-selected-links="/features /features/project-management /features/code-review /features/project-management /features/integrations /features">
                  Features
</a>              </li>
              <li class="ml-4">
                <a href="/business" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:business" data-selected-links="/business /business/security /business/customers /business">
                  Business
</a>              </li>

              <li class="ml-4">
                <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                  Explore
</a>              </li>

              <li class="ml-4">
                    <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:marketplace" data-selected-links=" /marketplace">
                      Marketplace
</a>              </li>
              <li class="ml-4">
                <a href="/pricing" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:pricing" data-selected-links="/pricing /pricing/developer /pricing/team /pricing/business-hosted /pricing/business-enterprise /pricing">
                  Pricing
</a>              </li>
          </ul>
        </nav>

      <div class="d-flex">
          <div class="d-lg-flex flex-items-center mr-3">
            <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/github/swift-style-guide/search" class="js-site-search-form" data-scoped-search-url="/github/swift-style-guide/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/github/swift-style-guide/blob/master/README.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

          </div>

        <span class="d-inline-block">
            <div class="HeaderNavlink px-0 py-2 m-0">
              <a class="text-bold text-white no-underline" href="/login?return_to=%2Fgithub%2Fswift-style-guide%2Fblob%2Fmaster%2FREADME.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
                <span class="text-gray">or</span>
                <a class="text-bold text-white no-underline" href="/join?source=header-repo" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
            </div>
        </span>
      </div>
    </div>
  </div>
</header>


  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      



  



    <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav ">
      <div class="repohead-details-container clearfix container ">

        <ul class="pagehead-actions">
  <li>
      <a href="/login?return_to=%2Fgithub%2Fswift-style-guide"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
  </a>
  <a class="social-count" href="/github/swift-style-guide/watchers"
     aria-label="277 users are watching this repository">
    277
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fgithub%2Fswift-style-guide"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
    Star
  </a>

    <a class="social-count js-social-count" href="/github/swift-style-guide/stargazers"
      aria-label="4336 users starred this repository">
      4,336
    </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fgithub%2Fswift-style-guide"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
      </a>

    <a href="/github/swift-style-guide/network" class="social-count"
       aria-label="470 users forked this repository">
      470
    </a>
  </li>
</ul>

        <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/github" class="url fn" rel="author">github</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/github/swift-style-guide" data-pjax="#js-repo-pjax-container">swift-style-guide</a></strong>

</h1>

      </div>
      
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/github/swift-style-guide" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /github/swift-style-guide" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>


  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/github/swift-style-guide/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /github/swift-style-guide/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">2</span>
      <meta itemprop="position" content="3">
</a>  </span>




  <a href="/github/swift-style-guide/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /github/swift-style-guide/pulse">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


    </div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    
  <a href="/github/swift-style-guide/blob/926d7ba8503fb5efcd0a890356862e1c89df1f00/README.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:14b092be5413af97015f25011372cd6c -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/github/swift-style-guide/blob/lets-in-cases/README.md"
               data-name="lets-in-cases"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                lets-in-cases
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/github/swift-style-guide/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/github/swift-style-guide/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/github/swift-style-guide"><span>swift-style-guide</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
    </div>
  </div>


  <include-fragment class="commit-tease" src="/github/swift-style-guide/contributors/master/README.md">
    <div>
      Fetching contributors&hellip;
    </div>

    <div class="commit-tease-contributors">
      <img alt="" class="loader-loading float-left" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" />
      <span class="loader-error">Cannot retrieve contributors at this time</span>
    </div>
</include-fragment>

  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/github/swift-style-guide/raw/master/README.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/github/swift-style-guide/blame/master/README.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/github/swift-style-guide/commits/master/README.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="https://desktop.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

        <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
        </button>
        <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
        </button>
  </div>

  <div class="file-info">
      311 lines (220 sloc)
      <span class="file-info-divider"></span>
    8.97 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><p>A guide to our Swift style and conventions.</p>
<p>This is an attempt to encourage patterns that accomplish the following goals (in
rough priority order):</p>
<ol>
<li>Increased rigor, and decreased likelihood of programmer error</li>
<li>Increased clarity of intent</li>
<li>Reduced verbosity</li>
<li>Fewer debates about aesthetics</li>
</ol>
<p>If you have suggestions, please see our <a href="/github/swift-style-guide/blob/master/CONTRIBUTING.md">contribution guidelines</a>,
then open a pull request. <g-emoji alias="zap" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/26a1.png" ios-version="6.0">⚡️</g-emoji></p>
<hr>
<h4><a href="#whitespace" aria-hidden="true" class="anchor" id="user-content-whitespace"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Whitespace</h4>
<ul>
<li>Tabs, not spaces.</li>
<li>End files with a newline.</li>
<li>Make liberal use of vertical whitespace to divide code into logical chunks.</li>
<li>Don’t leave trailing whitespace.
<ul>
<li>Not even leading indentation on blank lines.</li>
</ul>
</li>
</ul>
<h4><a href="#prefer-let-bindings-over-var-bindings-wherever-possible" aria-hidden="true" class="anchor" id="user-content-prefer-let-bindings-over-var-bindings-wherever-possible"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Prefer <code>let</code>-bindings over <code>var</code>-bindings wherever possible</h4>
<p>Use <code>let foo = …</code> over <code>var foo = …</code> wherever possible (and when in doubt). Only use <code>var</code> if you absolutely have to (i.e. you <em>know</em> that the value might change, e.g. when using the <code>weak</code> storage modifier).</p>
<p><em>Rationale:</em> The intent and meaning of both keywords are clear, but <em>let-by-default</em> results in safer and clearer code.</p>
<p>A <code>let</code>-binding guarantees and <em>clearly signals to the programmer</em> that its value will never change. Subsequent code can thus make stronger assumptions about its usage.</p>
<p>It becomes easier to reason about code. Had you used <code>var</code> while still making the assumption that the value never changed, you would have to manually check that.</p>
<p>Accordingly, whenever you see a <code>var</code> identifier being used, assume that it will change and ask yourself why.</p>
<h4><a href="#return-and-break-early" aria-hidden="true" class="anchor" id="user-content-return-and-break-early"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Return and break early</h4>
<p>When you have to meet certain criteria to continue execution, try to exit early. So, instead of this:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">if</span> n.<span class="pl-smi">isNumber</span> {
    <span class="pl-c"><span class="pl-c">//</span> Use n here</span>
<span class="pl-c"></span>} <span class="pl-k">else</span> {
    <span class="pl-k">return</span>
}</pre></div>
<p>use this:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">guard</span> n.<span class="pl-smi">isNumber</span> <span class="pl-k">else</span> {
    <span class="pl-k">return</span>
}
<span class="pl-c"><span class="pl-c">//</span> Use n here</span></pre></div>
<p>You can also do it with <code>if</code> statement, but using <code>guard</code> is preferred, because <code>guard</code> statement without <code>return</code>, <code>break</code> or <code>continue</code> produces a compile-time error, so exit is guaranteed.</p>
<h4><a href="#avoid-using-force-unwrapping-of-optionals" aria-hidden="true" class="anchor" id="user-content-avoid-using-force-unwrapping-of-optionals"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Avoid Using Force-Unwrapping of Optionals</h4>
<p>If you have an identifier <code>foo</code> of type <code>FooType?</code> or <code>FooType!</code>, don't force-unwrap it to get to the underlying value (<code>foo!</code>) if possible.</p>
<p>Instead, prefer this:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">if</span> <span class="pl-k">let</span> foo <span class="pl-k">=</span> foo {
    <span class="pl-c"><span class="pl-c">//</span> Use unwrapped `foo` value in here</span>
<span class="pl-c"></span>} <span class="pl-k">else</span> {
    <span class="pl-c"><span class="pl-c">//</span> If appropriate, handle the case where the optional is nil</span>
<span class="pl-c"></span>}</pre></div>
<p>Alternatively, you might want to use Swift's Optional Chaining in some of these cases, such as:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-c"><span class="pl-c">//</span> Call the function if `foo` is not nil. If `foo` is nil, ignore we ever tried to make the call</span>
<span class="pl-c"></span>foo<span class="pl-k">?</span>.<span class="pl-c1">callSomethingIfFooIsNotNil</span>()</pre></div>
<p><em>Rationale:</em> Explicit <code>if let</code>-binding of optionals results in safer code. Force unwrapping is more prone to lead to runtime crashes.</p>
<h4><a href="#avoid-using-implicitly-unwrapped-optionals" aria-hidden="true" class="anchor" id="user-content-avoid-using-implicitly-unwrapped-optionals"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Avoid Using Implicitly Unwrapped Optionals</h4>
<p>Where possible, use <code>let foo: FooType?</code> instead of <code>let foo: FooType!</code> if <code>foo</code> may be nil (Note that in general, <code>?</code> can be used instead of <code>!</code>).</p>
<p><em>Rationale:</em> Explicit optionals result in safer code. Implicitly unwrapped optionals have the potential of crashing at runtime.</p>
<h4><a href="#prefer-implicit-getters-on-read-only-properties-and-subscripts" aria-hidden="true" class="anchor" id="user-content-prefer-implicit-getters-on-read-only-properties-and-subscripts"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Prefer implicit getters on read-only properties and subscripts</h4>
<p>When possible, omit the <code>get</code> keyword on read-only computed properties and
read-only subscripts.</p>
<p>So, write these:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">var</span> myGreatProperty<span class="pl-k">:</span> <span class="pl-c1">Int</span> {
	<span class="pl-k">return</span> <span class="pl-c1">4</span>
}

<span class="pl-k">subscript</span>(<span class="pl-c1">index</span>: <span class="pl-c1">Int</span>) <span class="pl-k">-&gt;</span> T {
    <span class="pl-k">return</span> objects[index]
}</pre></div>
<p>… not these:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">var</span> myGreatProperty<span class="pl-k">:</span> <span class="pl-c1">Int</span> {
	<span class="pl-k">get</span> {
		<span class="pl-k">return</span> <span class="pl-c1">4</span>
	}
}

<span class="pl-k">subscript</span>(<span class="pl-c1">index</span>: <span class="pl-c1">Int</span>) <span class="pl-k">-&gt;</span> T {
    <span class="pl-k">get</span> {
        <span class="pl-k">return</span> objects[index]
    }
}</pre></div>
<p><em>Rationale:</em> The intent and meaning of the first version are clear, and results in less code.</p>
<h4><a href="#always-specify-access-control-explicitly-for-top-level-definitions" aria-hidden="true" class="anchor" id="user-content-always-specify-access-control-explicitly-for-top-level-definitions"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Always specify access control explicitly for top-level definitions</h4>
<p>Top-level functions, types, and variables should always have explicit access control specifiers:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">public</span> <span class="pl-k">var</span> whoopsGlobalState<span class="pl-k">:</span> <span class="pl-c1">Int</span>
<span class="pl-k">internal</span> <span class="pl-k">struct</span> <span class="pl-en">TheFez</span> {}
<span class="pl-k">private</span> <span class="pl-k">func</span> <span class="pl-en">doTheThings</span>(<span class="pl-smi"><span class="pl-en">things</span></span>: [Thing]) {}</pre></div>
<p>However, definitions within those can leave access control implicit, where appropriate:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">internal</span> <span class="pl-k">struct</span> <span class="pl-en">TheFez</span> {
	<span class="pl-k">var</span> owner<span class="pl-k">:</span> Person <span class="pl-k">=</span> <span class="pl-c1">Joshaber</span>()
}</pre></div>
<p><em>Rationale:</em> It's rarely appropriate for top-level definitions to be specifically <code>internal</code>, and being explicit ensures that careful thought goes into that decision. Within a definition, reusing the same access control specifier is just duplicative, and the default is usually reasonable.</p>
<h4><a href="#when-specifying-a-type-always-associate-the-colon-with-the-identifier" aria-hidden="true" class="anchor" id="user-content-when-specifying-a-type-always-associate-the-colon-with-the-identifier"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>When specifying a type, always associate the colon with the identifier</h4>
<p>When specifying the type of an identifier, always put the colon immediately
after the identifier, followed by a space and then the type name.</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">class</span> <span class="pl-en">SmallBatchSustainableFairtrade</span>: <span class="pl-e">Coffee </span>{ <span class="pl-k">...</span> }

<span class="pl-k">let</span> timeToCoffee<span class="pl-k">:</span> NSTimeInterval <span class="pl-k">=</span> <span class="pl-c1">2</span>

<span class="pl-k">func</span> <span class="pl-en">makeCoffee</span>(<span class="pl-smi"><span class="pl-en">type</span></span>: CoffeeType) <span class="pl-k">-&gt;</span> Coffee { <span class="pl-k">...</span> }</pre></div>
<p><em>Rationale:</em> The type specifier is saying something about the <em>identifier</em> so
it should be positioned with it.</p>
<p>Also, when specifying the type of a dictionary, always put the colon immediately
after the key type, followed by a space and then the value type.</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">let</span> capitals<span class="pl-k">:</span> [Country<span class="pl-k">:</span> City] <span class="pl-k">=</span> [sweden<span class="pl-k">:</span> stockholm]</pre></div>
<h4><a href="#only-explicitly-refer-to-self-when-required" aria-hidden="true" class="anchor" id="user-content-only-explicitly-refer-to-self-when-required"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Only explicitly refer to <code>self</code> when required</h4>
<p>When accessing properties or methods on <code>self</code>, leave the reference to <code>self</code> implicit by default:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">private</span> <span class="pl-k">class</span> <span class="pl-en">History</span> {
	<span class="pl-k">var</span> events<span class="pl-k">:</span> [Event]

	<span class="pl-k">func</span> <span class="pl-en">rewrite</span>() {
		events <span class="pl-k">=</span> []
	}
}</pre></div>
<p>Only include the explicit keyword when required by the language—for example, in a closure, or when parameter names conflict:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">extension</span> <span class="pl-en">History</span> {
	<span class="pl-k">init</span>(<span class="pl-smi"><span class="pl-en">events</span></span>: [Event]) {
		<span class="pl-c1">self</span>.<span class="pl-smi">events</span> <span class="pl-k">=</span> events
	}

	<span class="pl-k">var</span> whenVictorious<span class="pl-k">:</span> () <span class="pl-k">-&gt;</span> () {
		<span class="pl-k">return</span> {
			<span class="pl-c1">self</span>.<span class="pl-c1">rewrite</span>()
		}
	}
}</pre></div>
<p><em>Rationale:</em> This makes the capturing semantics of <code>self</code> stand out more in closures, and avoids verbosity elsewhere.</p>
<h4><a href="#prefer-structs-over-classes" aria-hidden="true" class="anchor" id="user-content-prefer-structs-over-classes"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Prefer structs over classes</h4>
<p>Unless you require functionality that can only be provided by a class (like identity or deinitializers), implement a struct instead.</p>
<p>Note that inheritance is (by itself) usually <em>not</em> a good reason to use classes, because polymorphism can be provided by protocols, and implementation reuse can be provided through composition.</p>
<p>For example, this class hierarchy:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">class</span> <span class="pl-en">Vehicle</span> {
    <span class="pl-k">let</span> numberOfWheels<span class="pl-k">:</span> <span class="pl-c1">Int</span>

    <span class="pl-k">init</span>(<span class="pl-smi"><span class="pl-en">numberOfWheels</span></span>: <span class="pl-c1">Int</span>) {
        <span class="pl-c1">self</span>.<span class="pl-smi">numberOfWheels</span> <span class="pl-k">=</span> numberOfWheels
    }

    <span class="pl-k">func</span> <span class="pl-en">maximumTotalTirePressure</span>(<span class="pl-smi"><span class="pl-en">pressurePerWheel</span></span>: <span class="pl-c1">Float</span>) <span class="pl-k">-&gt;</span> <span class="pl-c1">Float</span> {
        <span class="pl-k">return</span> pressurePerWheel <span class="pl-k">*</span> <span class="pl-c1">Float</span>(numberOfWheels)
    }
}

<span class="pl-k">class</span> <span class="pl-en">Bicycle</span>: <span class="pl-e">Vehicle </span>{
    <span class="pl-k">init</span>() {
        <span class="pl-c1">super</span>.<span class="pl-k">init</span>(<span class="pl-c1">numberOfWheels</span>: <span class="pl-c1">2</span>)
    }
}

<span class="pl-k">class</span> <span class="pl-en">Car</span>: <span class="pl-e">Vehicle </span>{
    <span class="pl-k">init</span>() {
        <span class="pl-c1">super</span>.<span class="pl-k">init</span>(<span class="pl-c1">numberOfWheels</span>: <span class="pl-c1">4</span>)
    }
}</pre></div>
<p>could be refactored into these definitions:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">protocol</span> <span class="pl-en">Vehicle</span> {
    <span class="pl-k">var</span> numberOfWheels<span class="pl-k">:</span> <span class="pl-c1">Int</span> { <span class="pl-k">get</span> }
}

<span class="pl-k">func</span> <span class="pl-en">maximumTotalTirePressure</span>(<span class="pl-smi"><span class="pl-en">vehicle</span></span>: Vehicle, <span class="pl-smi"><span class="pl-en">pressurePerWheel</span></span>: <span class="pl-c1">Float</span>) <span class="pl-k">-&gt;</span> <span class="pl-c1">Float</span> {
    <span class="pl-k">return</span> pressurePerWheel <span class="pl-k">*</span> <span class="pl-c1">Float</span>(vehicle.<span class="pl-smi">numberOfWheels</span>)
}

<span class="pl-k">struct</span> <span class="pl-en">Bicycle</span>: <span class="pl-e">Vehicle </span>{
    <span class="pl-k">let</span> numberOfWheels <span class="pl-k">=</span> <span class="pl-c1">2</span>
}

<span class="pl-k">struct</span> <span class="pl-en">Car</span>: <span class="pl-e">Vehicle </span>{
    <span class="pl-k">let</span> numberOfWheels <span class="pl-k">=</span> <span class="pl-c1">4</span>
}</pre></div>
<p><em>Rationale:</em> Value types are simpler, easier to reason about, and behave as expected with the <code>let</code> keyword.</p>
<h4><a href="#make-classes-final-by-default" aria-hidden="true" class="anchor" id="user-content-make-classes-final-by-default"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Make classes <code>final</code> by default</h4>
<p>Classes should start as <code>final</code>, and only be changed to allow subclassing if a valid need for inheritance has been identified. Even in that case, as many definitions as possible <em>within</em> the class should be <code>final</code> as well, following the same rules.</p>
<p><em>Rationale:</em> Composition is usually preferable to inheritance, and opting <em>in</em> to inheritance hopefully means that more thought will be put into the decision.</p>
<h4><a href="#omit-type-parameters-where-possible" aria-hidden="true" class="anchor" id="user-content-omit-type-parameters-where-possible"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Omit type parameters where possible</h4>
<p>Methods of parameterized types can omit type parameters on the receiving type when they’re identical to the receiver’s. For example:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">struct</span> <span class="pl-en">Composite</span>&lt;<span class="pl-c1">T</span>&gt; {
	<span class="pl-k">…</span>
	<span class="pl-k">func</span> <span class="pl-en">compose</span>(<span class="pl-smi"><span class="pl-en">other</span></span>: Composite&lt;T&gt;) <span class="pl-k">-&gt;</span> Composite&lt;T&gt; {
		<span class="pl-k">return</span> Composite<span class="pl-k">&lt;</span>T<span class="pl-k">&gt;</span>(<span class="pl-c1">self</span>, other)
	}
}</pre></div>
<p>could be rendered as:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">struct</span> <span class="pl-en">Composite</span>&lt;<span class="pl-c1">T</span>&gt; {
	<span class="pl-k">…</span>
	<span class="pl-k">func</span> <span class="pl-en">compose</span>(<span class="pl-smi"><span class="pl-en">other</span></span>: Composite) <span class="pl-k">-&gt;</span> Composite {
		<span class="pl-k">return</span> <span class="pl-c1">Composite</span>(<span class="pl-c1">self</span>, other)
	}
}</pre></div>
<p><em>Rationale:</em> Omitting redundant type parameters clarifies the intent, and makes it obvious by contrast when the returned type takes different type parameters.</p>
<h4><a href="#use-whitespace-around-operator-definitions" aria-hidden="true" class="anchor" id="user-content-use-whitespace-around-operator-definitions"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Use whitespace around operator definitions</h4>
<p>Use whitespace around operators when defining them. Instead of:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">func</span> <span class="pl-en">&lt;|</span>(<span class="pl-smi"><span class="pl-en">lhs</span></span>: <span class="pl-c1">Int</span>, <span class="pl-smi"><span class="pl-en">rhs</span></span>: <span class="pl-c1">Int</span>) <span class="pl-k">-&gt;</span> <span class="pl-c1">Int</span>
<span class="pl-k">func</span> <span class="pl-en">&lt;|&lt;</span>&lt;<span class="pl-c1">A</span>&gt;(<span class="pl-smi"><span class="pl-en">lhs</span></span>: A, <span class="pl-smi"><span class="pl-en">rhs</span></span>: A) <span class="pl-k">-&gt;</span> A</pre></div>
<p>write:</p>
<div class="highlight highlight-source-swift"><pre><span class="pl-k">func</span> <span class="pl-en">&lt;|</span> (<span class="pl-smi"><span class="pl-en">lhs</span></span>: <span class="pl-c1">Int</span>, <span class="pl-smi"><span class="pl-en">rhs</span></span>: <span class="pl-c1">Int</span>) <span class="pl-k">-&gt;</span> <span class="pl-c1">Int</span>
<span class="pl-k">func</span> <span class="pl-en">&lt;|&lt;</span> &lt;<span class="pl-c1">A</span>&gt;(<span class="pl-smi"><span class="pl-en">lhs</span></span>: A, <span class="pl-smi"><span class="pl-en">rhs</span></span>: A) <span class="pl-k">-&gt;</span> A</pre></div>
<p><em>Rationale:</em> Operators consist of punctuation characters, which can make them difficult to read when immediately followed by the punctuation for a type or value parameter list. Adding whitespace separates the two more clearly.</p>
<h4><a href="#translations" aria-hidden="true" class="anchor" id="user-content-translations"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Translations</h4>
<ul>
<li><a href="https://github.com/Artwalk/swift-style-guide/blob/master/README_CN.md">中文版</a></li>
<li><a href="https://github.com/jarinosuke/swift-style-guide/blob/master/README_JP.md">日本語版</a></li>
<li><a href="https://github.com/minsOne/swift-style-guide/blob/master/README_KR.md">한국어판</a></li>
<li><a href="https://github.com/antoniosejas/swift-style-guide/blob/spanish/README-ES.md">Versión en Español</a></li>
<li><a href="https://github.com/fernandocastor/swift-style-guide/blob/master/README-PTBR.md">Versão em Português do Brasil</a></li>
<li><a href="https://github.com/mohpor/swift-style-guide/blob/Persian/README-FA.md">فارسی</a></li>
</ul>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2017 <span title="0.10750s from unicorn-376446599-8fs2x">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha256-B2nQiwimpgbJqLq5UZ3+8Qvx3E0kKVsk+HgfjDgi7eE=" src="https://assets-cdn.github.com/assets/frameworks-0769d08b08a6a606c9a8bab9519dfef10bf1dc4d24295b24f8781f8c3822ede1.js"></script>
    
    <script async="async" crossorigin="anonymous" integrity="sha256-wl8Hs5v9Rppja0bGzYd/qF/84PdTZ7/jVJm07DyVK8o=" src="https://assets-cdn.github.com/assets/github-c25f07b39bfd469a636b46c6cd877fa85ffce0f75367bfe35499b4ec3c952bca.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

