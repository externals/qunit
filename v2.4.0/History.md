





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



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-bedfc518345498ab3204d330c1727cde7e733526a09cd7df6867f6a231565091.css" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-63a53e9762b0d5d8d4f52e5ed8855df0850a00402ac6543862a93f50691230c8.css" media="all" rel="stylesheet" />
  
  
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/site-877643c520258c4fa15ac8d1664d84efd0e3db56f5e544ccac58da0e50489904.css" media="all" rel="stylesheet" />
  

  <meta name="viewport" content="width=device-width">
  
  <title>qunit/History.md at 2.4.0 · qunitjs/qunit · GitHub</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars3.githubusercontent.com/u/23195278?v=4&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="qunitjs/qunit" property="og:title" /><meta content="https://github.com/qunitjs/qunit" property="og:url" /><meta content="qunit - An easy-to-use JavaScript Unit Testing framework." property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="ABCE:8F90:19CBECD:2D25022:59CE94C1" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

  <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="ABCE:8F90:19CBECD:2D25022:59CE94C1" name="octolytics-dimension-request_id" /><meta content="iad" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged Out">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="OWZhMTE4OWNhOTRmZjhhYjM4ZDI5ZGMyZjFjMDUyYWIyYjc5MjgyNGMyMjljMmMzNTUxNjVjODY5YTQ5ZDFhMnx7InJlbW90ZV9hZGRyZXNzIjoiODguMTMwLjg4LjE2NCIsInJlcXVlc3RfaWQiOiJBQkNFOjhGOTA6MTlDQkVDRDoyRDI1MDIyOjU5Q0U5NEMxIiwidGltZXN0YW1wIjoxNTA2NzEwNzIxLCJob3N0IjoiZ2l0aHViLmNvbSJ9">


  <meta name="html-safe-nonce" content="c387e65e23e4e4d525d671fc1545a872986c08a0">

  <meta http-equiv="x-pjax-version" content="398836b3eb6e757d73d616882787bd44">
  

      <link href="https://github.com/qunitjs/qunit/commits/2.4.0.atom" rel="alternate" title="Recent Commits to qunit:2.4.0" type="application/atom+xml">

  <meta name="description" content="qunit - An easy-to-use JavaScript Unit Testing framework.">
  <meta name="go-import" content="github.com/qunitjs/qunit git https://github.com/qunitjs/qunit.git">

  <meta content="23195278" name="octolytics-dimension-user_id" /><meta content="qunitjs" name="octolytics-dimension-user_login" /><meta content="259691" name="octolytics-dimension-repository_id" /><meta content="qunitjs/qunit" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="259691" name="octolytics-dimension-repository_network_root_id" /><meta content="qunitjs/qunit" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/qunitjs/qunit/blob/2.4.0/History.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">



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
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/qunitjs/qunit/search" class="js-site-search-form" data-scoped-search-url="/qunitjs/qunit/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/qunitjs/qunit/blob/2.4.0/History.md" class="header-search-scope no-underline">This repository</a>
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
              <a class="text-bold text-white no-underline" href="/login?return_to=%2Fqunitjs%2Fqunit%2Fblob%2F2.4.0%2FHistory.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
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
      



  



    <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
      <div class="container repohead-details-container">

        <ul class="pagehead-actions">
  <li>
      <a href="/login?return_to=%2Fqunitjs%2Fqunit"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
  </a>
  <a class="social-count" href="/qunitjs/qunit/watchers"
     aria-label="143 users are watching this repository">
    143
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fqunitjs%2Fqunit"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
    Star
  </a>

    <a class="social-count js-social-count" href="/qunitjs/qunit/stargazers"
      aria-label="3688 users starred this repository">
      3,688
    </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fqunitjs%2Fqunit"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
      </a>

    <a href="/qunitjs/qunit/network" class="social-count"
       aria-label="733 users forked this repository">
      733
    </a>
  </li>
</ul>

        <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/qunitjs" class="url fn" rel="author">qunitjs</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/qunitjs/qunit" data-pjax="#js-repo-pjax-container">qunit</a></strong>

</h1>

      </div>
      <div class="container">
        
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/qunitjs/qunit/tree/2.4.0" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /qunitjs/qunit/tree/2.4.0" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/qunitjs/qunit/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /qunitjs/qunit/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">40</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/qunitjs/qunit/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /qunitjs/qunit/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">3</span>
      <meta itemprop="position" content="3">
</a>  </span>




    <div class="reponav-dropdown js-menu-container">
      <button type="button" class="btn-link reponav-item reponav-dropdown js-menu-target " data-no-toggle aria-expanded="false" aria-haspopup="true">
        Insights
        <svg aria-hidden="true" class="octicon octicon-triangle-down v-align-middle text-gray" height="11" version="1.1" viewBox="0 0 12 16" width="8"><path fill-rule="evenodd" d="M0 5l6 6 6-6z"/></svg>
      </button>
      <div class="dropdown-menu-content js-menu-content">
        <div class="dropdown-menu dropdown-menu-sw">
          <a class="dropdown-item" href="/qunitjs/qunit/pulse" data-skip-pjax>
            <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"/></svg>
            Pulse
          </a>
          <a class="dropdown-item" href="/qunitjs/qunit/graphs" data-skip-pjax>
            <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
            Graphs
          </a>
        </div>
      </div>
    </div>
</nav>

      </div>
    </div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    
  <a href="/qunitjs/qunit/blob/c5b456cc8ba8570b6a0fef4282b345f05ee43e35/History.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:b5069510bd771cfe60b7d11272c5be9c -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Tag:</i>
      <span class="js-select-button css-truncate-target">2.4.0</span>
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
               href="/qunitjs/qunit/blob/master/History.md"
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


            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.14.0/History.md"
              data-name="v1.14.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.14.0">
                v1.14.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.13.0/History.md"
              data-name="v1.13.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.13.0">
                v1.13.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.12.0/History.md"
              data-name="v1.12.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.12.0">
                v1.12.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.11.0/History.md"
              data-name="v1.11.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.11.0">
                v1.11.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.10.0/History.md"
              data-name="v1.10.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.10.0">
                v1.10.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.9.0/History.md"
              data-name="v1.9.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.9.0">
                v1.9.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.8.0/History.md"
              data-name="v1.8.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.8.0">
                v1.8.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.7.0/History.md"
              data-name="v1.7.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.7.0">
                v1.7.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.6.0/History.md"
              data-name="v1.6.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.6.0">
                v1.6.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.5.0/History.md"
              data-name="v1.5.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.5.0">
                v1.5.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.4.0/History.md"
              data-name="v1.4.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.4.0">
                v1.4.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.3.0/History.md"
              data-name="v1.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.3.0">
                v1.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.2.0/History.md"
              data-name="v1.2.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.2.0">
                v1.2.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.1.0/History.md"
              data-name="v1.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.1.0">
                v1.1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/v1.0.0/History.md"
              data-name="v1.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.0.0">
                v1.0.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
              href="/qunitjs/qunit/tree/2.4.0/History.md"
              data-name="2.4.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.4.0">
                2.4.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.3.3/History.md"
              data-name="2.3.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.3.3">
                2.3.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.3.2/History.md"
              data-name="2.3.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.3.2">
                2.3.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.3.1/History.md"
              data-name="2.3.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.3.1">
                2.3.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.3.0/History.md"
              data-name="2.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.3.0">
                2.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.2.1/History.md"
              data-name="2.2.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.2.1">
                2.2.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.2.0/History.md"
              data-name="2.2.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.2.0">
                2.2.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.1.1/History.md"
              data-name="2.1.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.1.1">
                2.1.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.1.0/History.md"
              data-name="2.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.1.0">
                2.1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.0.1/History.md"
              data-name="2.0.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.0.1">
                2.0.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.0.0/History.md"
              data-name="2.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.0.0">
                2.0.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/2.0.0-rc1/History.md"
              data-name="2.0.0-rc1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="2.0.0-rc1">
                2.0.0-rc1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.23.1/History.md"
              data-name="1.23.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.23.1">
                1.23.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.23.0/History.md"
              data-name="1.23.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.23.0">
                1.23.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.22.0/History.md"
              data-name="1.22.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.22.0">
                1.22.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.21.0/History.md"
              data-name="1.21.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.21.0">
                1.21.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.20.0/History.md"
              data-name="1.20.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.20.0">
                1.20.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.19.0/History.md"
              data-name="1.19.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.19.0">
                1.19.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.18.0/History.md"
              data-name="1.18.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.18.0">
                1.18.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.17.1/History.md"
              data-name="1.17.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.17.1">
                1.17.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.17.0/History.md"
              data-name="1.17.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.17.0">
                1.17.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.16.0/History.md"
              data-name="1.16.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.16.0">
                1.16.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.15.0/History.md"
              data-name="1.15.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.15.0">
                1.15.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.14.0/History.md"
              data-name="1.14.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.14.0">
                1.14.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.13.0/History.md"
              data-name="1.13.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.13.0">
                1.13.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/qunitjs/qunit/tree/1.1.0/History.md"
              data-name="1.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="1.1.0">
                1.1.0
              </span>
            </a>
        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/qunitjs/qunit/find/2.4.0"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/qunitjs/qunit/tree/2.4.0"><span>qunit</span></a></span></span><span class="separator">/</span><strong class="final-path">History.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/qunitjs/qunit/commit/8f7fafd4ce65a7513f12600ffb08e8634dbe2c29" data-pjax>
          8f7fafd
        </a>
        <relative-time datetime="2017-07-08T15:13:15Z">Jul 9, 2017</relative-time>
      </span>
      <div>
        <img alt="@trentmwillis" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/3526753?v=4&amp;s=40" width="20" />
        <a href="/trentmwillis" class="user-mention" rel="contributor">trentmwillis</a>
          <a href="/qunitjs/qunit/commit/8f7fafd4ce65a7513f12600ffb08e8634dbe2c29" class="message" data-pjax="true" title="Build: Prepare 2.4.0 release, including authors and history update">Build: Prepare 2.4.0 release, including authors and history update</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>6</strong>
         contributors
      </button>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="jzaefferer" href="/qunitjs/qunit/commits/2.4.0/History.md?author=jzaefferer"><img alt="@jzaefferer" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/52585?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="leobalter" href="/qunitjs/qunit/commits/2.4.0/History.md?author=leobalter"><img alt="@leobalter" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/301201?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="trentmwillis" href="/qunitjs/qunit/commits/2.4.0/History.md?author=trentmwillis"><img alt="@trentmwillis" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/3526753?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="jdufresne" href="/qunitjs/qunit/commits/2.4.0/History.md?author=jdufresne"><img alt="@jdufresne" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/347634?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="dmitrygusev" href="/qunitjs/qunit/commits/2.4.0/History.md?author=dmitrygusev"><img alt="@dmitrygusev" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/76579?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="jsoref" href="/qunitjs/qunit/commits/2.4.0/History.md?author=jsoref"><img alt="@jsoref" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/2119212?v=4&amp;s=40" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@jzaefferer" height="24" src="https://avatars3.githubusercontent.com/u/52585?v=4&amp;s=48" width="24" />
            <a href="/jzaefferer">jzaefferer</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@leobalter" height="24" src="https://avatars3.githubusercontent.com/u/301201?v=4&amp;s=48" width="24" />
            <a href="/leobalter">leobalter</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@trentmwillis" height="24" src="https://avatars2.githubusercontent.com/u/3526753?v=4&amp;s=48" width="24" />
            <a href="/trentmwillis">trentmwillis</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jdufresne" height="24" src="https://avatars3.githubusercontent.com/u/347634?v=4&amp;s=48" width="24" />
            <a href="/jdufresne">jdufresne</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@dmitrygusev" height="24" src="https://avatars0.githubusercontent.com/u/76579?v=4&amp;s=48" width="24" />
            <a href="/dmitrygusev">dmitrygusev</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jsoref" height="24" src="https://avatars2.githubusercontent.com/u/2119212?v=4&amp;s=48" width="24" />
            <a href="/jsoref">jsoref</a>
          </li>
      </ul>
    </div>
  </div>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/qunitjs/qunit/raw/2.4.0/History.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/qunitjs/qunit/blame/2.4.0/History.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/qunitjs/qunit/commits/2.4.0/History.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>


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
      926 lines (852 sloc)
      <span class="file-info-divider"></span>
    56.3 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-240--2017-07-08" class="anchor" href="#240--2017-07-08" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.0 / 2017-07-08</h1>
<ul>
<li>Build: Disable max-len ESLint rule for tests</li>
<li>Docs: Document assert.timeout</li>
<li>Tests: Add tests for assert.timeout</li>
<li>Assert: Introduce timeout to set per-test timeout durations</li>
<li>Core: Release objects from memory in equiv</li>
<li>Assert: Fix assert.push deprecation link</li>
<li>Docs: Fix typo in docs for QUnit.module</li>
<li>Docs: Document QUnit.module.{only,skip,todo} (#1194)</li>
<li>Test: Add tests for QUnit.module.todo()</li>
<li>Core: Implement QUnit.module.todo()</li>
<li>Test: Add tests for QUnit.module.skip()</li>
<li>Core: Implement QUnit.module.skip()</li>
<li>Core: Fallback to <code>typeof obj</code> in <code>QUnit.objectType</code>.</li>
<li>Tests: Add tests using native async functions.</li>
<li>CLI: Better messaging on early exits</li>
<li>CLI: Default to non-zero exit code</li>
<li>CLI: Exit with non-zero status when no tests are run</li>
<li>Build: Register events after requiring test file in test-on-node task</li>
<li>Docs: Add note about defining multiple hooks for modules</li>
<li>Tests: Add tests for multiple module hooks</li>
<li>Core: Add support for multiple hooks</li>
<li>Test: Add tests for QUnit.module.only()</li>
<li>Core: Implement QUnit.module.only()</li>
<li>Build: Include bin file in eslint</li>
</ul>
<h1><a id="user-content-233--2017-06-02" class="anchor" href="#233--2017-06-02" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3.3 / 2017-06-02</h1>
<ul>
<li>Core: Updates for Node.js version 8 compatibility and testing</li>
<li>Docs: Update README/CONTRIBUTING with more recent/relevant information</li>
<li>Docs: Move CONTRIBUTING.md from docs to root</li>
<li>Build: Let grunt watch live-reload the test suite</li>
<li>Build: Only start one web server for grunt watch</li>
<li>Core: Support running in WorkerGlobalScope</li>
<li>Docs: Add license status (#1175)</li>
<li>Docs: delete note about QUnit.jsDump's removal</li>
<li>Docs: Document 'todo' in log details object</li>
<li>Docs: Document 'todo' in testDone details object</li>
<li>Tests: Add requireQUnit tests</li>
<li>CLI: Prefer local version of QUnit</li>
</ul>
<h1><a id="user-content-232--2017-04-17" class="anchor" href="#232--2017-04-17" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3.2 / 2017-04-17</h1>
<ul>
<li>HTML Reporter: Add specific diff for number types instead of str-diff. (#1155)</li>
<li>Core: Fix bug calling hooks with skipped tests (#1156)</li>
<li>Docs: Fix title and index link</li>
</ul>
<h1><a id="user-content-231--2017-04-10" class="anchor" href="#231--2017-04-10" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3.1 / 2017-04-10</h1>
<ul>
<li>Tests: Emit <code>suiteEnd</code> and trigger <code>moduleDone</code> for parent modules</li>
<li>Docs: Remove trailing slash from some urls</li>
<li>All: Enable ESLint indent rule (#1143)</li>
<li>Docs: Update assert.async documentation</li>
<li>Assert: Allow assertions after async</li>
<li>Docs: Copy styles from jquery-wp-content</li>
<li>Docs: Render markdown inside HTML blocks</li>
<li>Core: Ensure assertions occur while test is running</li>
<li>Assert: Throw if async callback invoked after test finishes</li>
<li>Tests: Add additional events test</li>
<li>Tests: Re-order events test</li>
<li>Core: Slim assertions after reporting them</li>
<li>Core: Fix test instance memory leak (#1138)</li>
<li>Docs: Remove baseurl as github is inserting an automatic value (#1136)</li>
<li>Docs: Migrate api docs (#1135)</li>
<li>Readme: Added Gitter badge (#1134)</li>
</ul>
<h1><a id="user-content-230--2017-03-29" class="anchor" href="#230--2017-03-29" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3.0 / 2017-03-29</h1>
<ul>
<li>Core: Test#pushFailure now calls Test#pushResult</li>
<li>HTML Reporter: Display todo tests on hidepassed</li>
<li>CLI: Add support for custom reporters</li>
<li>CLI: Properly support aborting and restarting tests</li>
<li>CLI: Add file watching option</li>
<li>Core: Revamp processing order to one test at a time</li>
<li>Core: Remove parameter from ProcessingQueue#advance</li>
<li>CLI: Add description to help command</li>
<li>CLI: Add seed option</li>
<li>Core: Account for validity of test in test counts</li>
<li>CLI: Support filtering tests</li>
<li>Core: Extract processing logic into ProcessingQueue</li>
<li>Tests: Add CLI tests</li>
<li>CLI: Introduce QUnit CLI</li>
<li>Readme: Add detailed release instructions</li>
<li>All: Enable ESLint prefer-const rule (#1109)</li>
</ul>
<h1><a id="user-content-221--2017-03-19" class="anchor" href="#221--2017-03-19" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2.1 / 2017-03-19</h1>
<ul>
<li>Test: Add basic reorder test</li>
<li>Core: Fix sessionStorage feature detection</li>
<li>Tests: Ensure onError tests are included in test/index.html (#1111)</li>
</ul>
<h1><a id="user-content-220--2017-03-11" class="anchor" href="#220--2017-03-11" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2.0 / 2017-03-11</h1>
<ul>
<li>Core: QUnit.onError now expects error or error-like object</li>
<li>HTML Reporter: Use QUnit.onError</li>
<li>HTML Reporter: Ensure window.onerror return values are correct</li>
<li>HTML Reporter: Moving window.onerror to HTML Reporter</li>
<li>Core: Extract main onError logic into exported function and add tests</li>
<li>Core: Fix start on Node when autostart is not set to true (#1105)</li>
<li>Core: Add todo to assertion event data</li>
<li>Core: Add remaining js-reporter events</li>
<li>Core: Fix double begin when calling start in Node</li>
<li>Core: Rewrite QUnit.equiv to be breadth-first</li>
<li>Core: Optimize and document the "set" and "map" callbacks</li>
<li>Core: Implement QUnit.todo</li>
<li>Core: Add assertion event</li>
<li>Assert: Use actual values for verifySteps on failed steps</li>
<li>Assert: Add assert.verifySteps</li>
<li>Assert: Add assert.step</li>
<li>Core: Fix console error in IE9 (#1093)</li>
<li>Core: Ability to run in sandboxed iframe</li>
<li>Core: Implement event emitter (#1087)</li>
</ul>
<h1><a id="user-content-211--2017-01-05" class="anchor" href="#211--2017-01-05" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.1.1 / 2017-01-05</h1>
<ul>
<li>All: Remove deprecated 1.x features</li>
<li>Assert: Deprecate assert.push</li>
<li>Build: Remove unnecessary QUnit.load call</li>
<li>Core: QUnit.start does not require calling QUnit.load</li>
<li>HTML Reporter: Add an abort button</li>
</ul>
<h1><a id="user-content-210--2016-12-05" class="anchor" href="#210--2016-12-05" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.1.0 / 2016-12-05</h1>
<ul>
<li>All: Using eslint-plugin-html to lint HTML files</li>
<li>All: Removed JSHint/JSCS config &amp; comment leftovers</li>
<li>All: Update License to JSFoundation</li>
<li>All: Fix some outstanding indentation issues in files</li>
<li>All: Use Rollup and Babel to build</li>
<li>Core: Support a predefined QUnit.config</li>
<li>Core: Fix clearing of storage on done</li>
<li>Core: Always report if test previously failed</li>
<li>Core: Introduce config.storage option</li>
<li>Core: Load the onerror module</li>
<li>Core: Fix QUnit.equiv object methods comparison</li>
<li>Core: Support multiple nested modules hooks properly</li>
<li>Core: Blacklist jsDump-1034</li>
<li>Core: Fire moduleStart only when starting module for the first time</li>
<li>Core: Fire moduleDone when actually finished with module</li>
<li>HTML Reporter: Decouple from sessionStorage reordering logic</li>
<li>HTML Reporter: Fix expanding failed tests when collapse is false.</li>
<li>HTML Reporter: Handle URL params named like Object.prototype properties</li>
<li>Test: Properly handle Promises rejected without an error</li>
<li>Tests: Fixing lint errors caught by eslint-plugin-html</li>
<li>Tests: HTML files should end with LF</li>
<li>Tests: Add tests for Storage interface</li>
<li>Tests: Add tests for logging callback/module hooks order</li>
<li>Tests: Add expects to latest Promise tests</li>
<li>Build: Update Node support versions</li>
<li>Build: Consume eslint-plugin-qunit, use "two" configuration (#1052)</li>
<li>Build: Use ESLint</li>
<li>Build: Use SPDX format in bower.json's license</li>
<li>Build: Remove dependency on es2015-rollup preset</li>
<li>Build: Build with recent Node version but test against support matrix</li>
</ul>
<h1><a id="user-content-201--2016-07-23" class="anchor" href="#201--2016-07-23" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.0.1 / 2016-07-23</h1>
<ul>
<li>Core: Add extra guard against multiple begin()s</li>
<li>Test: Use a single property for tracking all async deferred calls</li>
<li>Core: Use callback-based pause/resume for better multi-pause isolation</li>
<li>Core: Better isolate async abstractions</li>
<li>Core: Improve internal async handling by removing resumed</li>
<li>HTML Reporter: Fix apply/reset button visibilty</li>
<li>Core: Ensure runtime for skipped tests is 0</li>
<li>Dump: Add parser for Symbol</li>
</ul>
<h1><a id="user-content-200--2016-06-16" class="anchor" href="#200--2016-06-16" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.0.0 / 2016-06-16</h1>
<ul>
<li>All: Remove deprecated features</li>
<li>All: Remove QUnit.config.autorun</li>
<li>All: Code cleanup for non-supported browsers</li>
<li>All: Prevent async tests from having multiple resume timeouts</li>
<li>All: Decouple Core fixture reset from HTML reporter</li>
<li>Assert: Remove throws signature with string expected value</li>
<li>Dump: update typeOf to extract extra complex type definition</li>
<li>Core: Introduce before/after hooks for modules</li>
<li>Core: Decode "+" to " " (space) in url params</li>
<li>Core: Throw error if QUnit is already defined globally</li>
<li>HTML Reporter: Add reset/apply buttons in the module picker</li>
<li>HTML Reporter: Improve module picker accessibility</li>
<li>HTML Reporter: color/background order consistency</li>
<li>HTML Reporter: Further improve module picker styling</li>
<li>HTML Reporter: Improve toolbar styles</li>
<li>HTML Reporter: Multi-select module dropdown</li>
<li>Test: Refactor test.semaphore usage</li>
<li>Tests: Test on all Node.js releases supported by upstream</li>
</ul>
<h1><a id="user-content-200-rc1--2016-04-19" class="anchor" href="#200-rc1--2016-04-19" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.0.0-rc1 / 2016-04-19</h1>
<ul>
<li>Core: Introduce before/after hooks for modules</li>
<li>HTML Reporter: Multi-select module dropdown</li>
<li>Assert: Remove throws signature with string expected value</li>
<li>All: Remove deprecated features</li>
<li>All: Remove QUnit.config.autorun</li>
<li>All: Code cleanup for non-supported browsers</li>
<li>Test: Refactor test.semaphore usage</li>
</ul>
<h1><a id="user-content-1231--2016-04-12" class="anchor" href="#1231--2016-04-12" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.23.1 / 2016-04-12</h1>
<ul>
<li>Core: Prevents throws keyword from breaking Rhino environments</li>
<li>Core: Be consistent in function type checks</li>
</ul>
<h1><a id="user-content-1230--2016-03-25" class="anchor" href="#1230--2016-03-25" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.23.0 / 2016-03-25</h1>
<ul>
<li>Core: Confine URL parameter interactions to browser-specific code</li>
<li>Core: Reintroduce QUnit.config.module</li>
<li>Core: Implement moduleId support for nested modules</li>
<li>Core: Stop splitting URL parameter values by commas</li>
<li>Core: Introduce moduleId filtering</li>
<li>Core: Add ability to run tests in pseudo-random order</li>
<li>Dump: Fix asymmetrical function dump argument spacing.</li>
<li>HTML Reporter: Fix escaping of diffs</li>
<li>HTML Reporter: Add message explaining missing diff</li>
<li>HTML Reporter: DRY out interface initialization</li>
<li>HTML Reporter: Move module name sort into begin callback</li>
<li>HTML Reporter: Remove redundant document guards</li>
<li>HTML Reporter: Fix hidepassed element check</li>
<li>Assert: Treat Set and Map as unordered in QUnit.equiv</li>
<li>Build: Introduce AppVeyor for Windows CI</li>
<li>Build: Update .gitattributes to fix LF on json files</li>
<li>Build: Fix linefeed to LF on Grunt configuration</li>
<li>Tests: Fix QUnit.stack test to account different path systems</li>
<li>Tests: Define setup and tests near each other</li>
</ul>
<h1><a id="user-content-1220--2016-02-23" class="anchor" href="#1220--2016-02-23" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.22.0 / 2016-02-23</h1>
<ul>
<li>Assert: Implement Assert#pushResult</li>
<li>Assert: Extend Assert methods to QUnit for backwards compatibility</li>
<li>HTML Reporter: Escape setUrl output</li>
</ul>
<h1><a id="user-content-1210--2016-02-01" class="anchor" href="#1210--2016-02-01" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.21.0 / 2016-02-01</h1>
<ul>
<li>Assert: Improve size and speed of QUnit.equiv</li>
<li>Assert: Fully support Object-wrapped primitives in deepEqual</li>
<li>Assert: Register notOk as a non-negative assertion</li>
<li>CSS: Fix hidden test results under static parents</li>
<li>Core: Improve regular expression comparisons</li>
<li>Core: Support filtering by regular expression</li>
<li>Test: Prevents skiping tests after rerun reordering</li>
<li>Tests: Differentiate QUnit.equiv assertions</li>
</ul>
<h1><a id="user-content-1200--2015-10-27" class="anchor" href="#1200--2015-10-27" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.20.0 / 2015-10-27</h1>
<ul>
<li>Assert: Exposes assert.raises() to the global scope</li>
<li>Assert: Add a calls count parameter on assert.async</li>
<li>Build: Improve grunt speed using grunt-concurrent</li>
<li>Core: Implement QUnit.only</li>
<li>Core: Support Symbol types on QUnit.equiv</li>
<li>Core: QUnit.start fails if called with a non-numeric argument</li>
<li>Core: Implement Nested modules</li>
<li>Core: Equivalency for descendants of null constructors</li>
<li>HTML Reporter: Adds indicator for filtered test</li>
<li>HTML Reporter: Collapse details for successive failed tests</li>
<li>Test: Fix regression when a failing test canceled the module hooks</li>
<li>Tests: Isolate and improve tests for Object equivalency</li>
<li>Tests: Split browserstack runs on CI to avoid timeout errors</li>
</ul>
<h1><a id="user-content-1190--2015-09-01" class="anchor" href="#1190--2015-09-01" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.19.0 / 2015-09-01</h1>
<ul>
<li>Assert: Add support to ES6' Map and Set equiv objects</li>
<li>Build: Enable IRC notifications for Travis CI</li>
<li>Build: Add 'Readme' to commitplease components</li>
<li>Build: Remove unintended QUnit global export on Node</li>
<li>Build: Remove testSwarm job</li>
<li>Core: Implement QUnit.stack</li>
<li>Dump: Escape backslash when quoting strings</li>
<li>HTML Reporter: Avoid readyState issue with PhantomJS</li>
<li>HTML Reporter: HTML reporter enhancements for negative asserts</li>
<li>HTML Reporter: Show diff only when it helps</li>
<li>Tests: Avoid loosen errors on autostart test</li>
<li>Tests: HTML Reporter tests are now isolated with reordering disabled</li>
<li>Tests: Rename stack error tests</li>
<li>Test: Release module hooks to avoid memory leaks</li>
<li>Test: Don't pass Promise fulfillment value to QUnit.start</li>
<li>Test: Source Displayed Even for Passed Test</li>
</ul>
<h1><a id="user-content-1180--2015-04-03" class="anchor" href="#1180--2015-04-03" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.18.0 / 2015-04-03</h1>
<ul>
<li>Assert: throws uses push method only</li>
<li>Assert: Fix missing test on exported throws</li>
<li>Assert: Implements notOk to assert falsy values</li>
<li>Core: More graceful handling of AMD</li>
<li>Core: Simplify stack trace methods</li>
<li>Core: Expose Dump maxDepth property</li>
<li>Core: Expose QUnit version as QUnit.version property</li>
<li>Core: Handle multiple testId parameters</li>
<li>Dump: Fix .name/.property doublettes</li>
<li>HTML Reporter: New diff using Google's Diff-Patch-Match Library</li>
<li>HTML Reporter: Make it more obvious why diff is suppressed.</li>
<li>HTML Reporter: Change display text for bad tests</li>
<li>HTML Reporter: Fix checkbox and select handling in IE &lt;9</li>
<li>HTML Reporter: Fix test filter without any module</li>
<li>HTML Reporter: Retain failed tests numbers</li>
<li>Test: lowercase the valid test filter before using it</li>
</ul>
<h1><a id="user-content-1171--2015-01-20" class="anchor" href="#1171--2015-01-20" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.17.1 / 2015-01-20</h1>
<ul>
<li>HTML Reporter: Fix missing toolbar bug</li>
</ul>
<h1><a id="user-content-1170--2015-01-19" class="anchor" href="#1170--2015-01-19" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.17.0 / 2015-01-19</h1>
<ul>
<li>Build: Remove bower.json from ignored files</li>
<li>Build: Support Node.js export parity with CommonJS</li>
<li>HTML Reporter: Add the filter field</li>
<li>HTML Reporter: Don't hide skipped tests</li>
<li>HTML Reporter: Fix regression for old markup</li>
<li>HTML Reporter: Prevent XSS attacks</li>
<li>HTML Reporter: QUnit.url is now a private function in the HTML Reporter</li>
<li>HTML Reporter: url params can be set by code</li>
</ul>
<h1><a id="user-content-1160--2014-12-03" class="anchor" href="#1160--2014-12-03" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.16.0 / 2014-12-03</h1>
<ul>
<li>Assert: Add alias for throws called 'raises'</li>
<li>Async: Fail assertions after existing assert.async flows are resolved</li>
<li>Async: Implement assert.async</li>
<li>Async: Tests are now Promise-aware</li>
<li>Callbacks: Restore and warn if some logging callback gets modified</li>
<li>Callbacks: Throws an error on non-function params for logging methods</li>
<li>Core: change url() helper to output <code>?foo</code> instead of <code>?foo=true</code></li>
<li>Core: Detail modules and tests names in the logging callbacks</li>
<li>Core: Implements QUnit.skip</li>
<li>Core: Remove constructor</li>
<li>Core: Rename config.module to config.moduleFilter</li>
<li>Core: Use <code>Error#stack</code> without throwing when available</li>
<li>Dump: Configurable limit for object depth</li>
<li>HTML Reporter: Enable activating config.hidepassed from URL params</li>
<li>HTML Reporter: Move QUnit.reset back to core to run it before testDone</li>
<li>HTML Reporter: Output runtime of each assertion in results</li>
<li>Logging: Add runtime to moduleDone</li>
<li>Logging: Defer begin event till tests actually starts</li>
<li>Test: Introduce order independent testId to replace testNumber</li>
<li>Test: Rename module's setup/teardown to beforeEach/afterEach</li>
</ul>
<h1><a id="user-content-1150--2014-08-08" class="anchor" href="#1150--2014-08-08" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.15.0 / 2014-08-08</h1>
<ul>
<li>Assert: Implement Assert constructor with test context. This heavily improves debugging of async tests, since assertions can't leak into other tests anymore. Use the assert argument in your test callbacks to run assertions to get the full benefit of this.</li>
<li>Assert: Improved the default message from assert.ok. Now assert.ok() outputs the exact value it received, instead of only saying it wasn't thruthy.</li>
<li>Assert: Removal of raises, same and equals. These were deprecated a long time ago and finally removed. Use throws, deepEqual and equal instead.</li>
<li>Core: Pass total amount of tests to QUnit.begin callback as totalTests. Will be used by Karma and other reporters.</li>
<li>Dump: Move QUnit.jsDump to QUnit.dump. QUnit.jsDump still exists, but will be removed later. Use QUnit.dump.</li>
<li>Dump: Output non-enumerable properties of TypeError. Makes it easier to compare properties of error objects.</li>
<li>Reporter: Output only assertion count for green tests. Less visual clutter for passing tests.</li>
<li>Reporter: Move HTML reporter to a new JS file. The HTML reporter is still bundled, but the code has been refactored to move it to a separate file.</li>
<li>Test: Remove deprecated QUnit.current_testEnvironment</li>
<li>Throws: support for oldIE native Error types. Error objects in IE are buggy, this works around those issues.</li>
</ul>
<h1><a id="user-content-1140--2014-01-31" class="anchor" href="#1140--2014-01-31" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.14.0 / 2014-01-31</h1>
<ul>
<li>Grunt: Run tests on ios browserSet as well</li>
<li>Package: Set main property to qunit/qunit.js</li>
<li>Grunt: Inline browserSet config for TestSwarm runs</li>
<li>CSS: Removing redundancy</li>
<li>Core: Add config property for disabling default scroll-to-top</li>
<li>Grunt: Remove addons leftovers</li>
<li>Addons: Remove last remnants</li>
<li>Core: Extend QUnit.config.urlConfig to support select-one dropdowns</li>
<li>Assert: Extend throws to accept Error instances</li>
<li>Assert: Extend throws to handle errors as strings</li>
<li>CSS: Updating qunit.css for consistency</li>
<li>Core: Cache window.clearTimeout in case it gets mocked</li>
<li>Core: Run multiple tests by test number</li>
<li>jshint: add es3 option to ensure oldie support</li>
</ul>
<h1><a id="user-content-1130--2014-01-04" class="anchor" href="#1130--2014-01-04" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.13.0 / 2014-01-04</h1>
<ul>
<li>Tests: Stop using the expected argument in test() calls</li>
<li>Logging: Add runtime property to testDone, deprecate duration</li>
<li>Assert: Remove raises (deprecated 2012), replace with failed assertion</li>
<li>Grunt: Add non-browser test as grunt task. Runs existing tests in node.</li>
<li>Export: Only export to the variable that we check for.</li>
<li>Core: Properly check for existence of document</li>
<li>Core: Remove triggerEvent, which isn't used or documented anywhere.</li>
<li>Core: Silence addEvent in non-browser env</li>
<li>The Grand QUnit Split of 2013</li>
<li>Use <code>id</code> function for selection elements in two places that were not using it. Closes gh-463</li>
<li>Add bower.json. Fixes #461</li>
</ul>
<h1><a id="user-content-1120--2013-06-21" class="anchor" href="#1120--2013-06-21" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.12.0 / 2013-06-21</h1>
<ul>
<li>Add a deprecation comment to QUnit.reset. Partial fix for #354</li>
<li>Fix mis-match between moduleStart and moduleDone events</li>
<li>Removed jQuery.trim optimization. Fixes #424.</li>
<li>Use a local setTimeout reference, add separate unit test suite for that. Fixes #432 - Using a setTimeout stub can stop test suite from continuing. Closes gh-433</li>
<li>Added CONTRIBUTING.md.</li>
<li>Moved 'addons/themes/nv' to 'Krinkle/qunit-theme-nv.git'</li>
<li>Moved 'addons/themes/ninja' to 'Krinkle/qunit-theme-ninja.git'</li>
<li>Moved 'addons/themes/gabe' to 'Krinkle/qunit-theme-gabe.git'</li>
<li>Moved 'addons/canvas' to 'JamesMGreene/qunit-assert-canvas.git'. Tree: <a href="https://github.com/JamesMGreene/qunit-assert-canvas/tree/v1.0.0">https://github.com/JamesMGreene/qunit-assert-canvas/tree/v1.0.0</a></li>
<li>Moved 'addons/close-enough' to 'JamesMGreene/qunit-assert-close.git'. Tree: <a href="https://github.com/JamesMGreene/qunit-assert-close/tree/v1.0.0">https://github.com/JamesMGreene/qunit-assert-close/tree/v1.0.0</a></li>
<li>Moved 'addons/step' to 'JamesMGreene/qunit-assert-step.git'. Tree: <a href="https://github.com/JamesMGreene/qunit-assert-step/tree/v1.0.0">https://github.com/JamesMGreene/qunit-assert-step/tree/v1.0.0</a></li>
<li>Canvas plugin: Show how to test with images. Closes gh-438.</li>
<li>Clear filter and testNumber when choosing a module. Fixes #442.</li>
<li>Deprecate QUnit.current_testEnvironment in favour of config.current.testEnvironment.</li>
<li>assert.ok: Message shouldn't be undefined in 'log' event.</li>
<li>Emit moduleStart before testStart even if test isn't in a module.</li>
<li>PhantomJS plugin: Added optional timeout. Closes #415.</li>
<li>PhantomJS plugin: Include stack trace for all failed tests. Closes #416.</li>
<li>Moved 'addons/composite' to 'jquery/qunit-composite.git'. Tree: <a href="https://github.com/jquery/qunit-composite/tree/v1.0.0">https://github.com/jquery/qunit-composite/tree/v1.0.0</a> Fixes #419.</li>
<li>Moved 'addons/junitlogger' to 'jquery/qunit-reporter-junit.git'.</li>
<li>Sort the module names so we no longer rely on implicit ordering. Fixes #391. Closes gh-392</li>
<li>JUnitLogger: Add a <code>name</code> property to the test run. Closes gh-389</li>
<li>Improve circular reference logic in equiv - Fixes #397</li>
</ul>
<h1><a id="user-content-1110--2013-01-20" class="anchor" href="#1110--2013-01-20" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.11.0 / 2013-01-20</h1>
<ul>
<li>Diff: Fix exception on property "constructor". Fixes #394.</li>
<li>Composite Add-on: Test suites can be named by including an obj with name &amp; path props within array param for .testSuites()</li>
<li>Fix URL generator to take protocol and host into account to fix usage with file protocol in IE7/8</li>
<li>Fix issue with Error.prototype.toString in IE 7</li>
<li>Refactor jsDump for "node". Fixes #381.</li>
<li>Show contents of text nodes in jsDump.node. Fixes #380.</li>
<li>Escape text. Fixes #379.</li>
<li>Rewrote most of the JUnitLogger addon as it was in bad shape: unused variables, duplicate effort that QUnit handles internally (e.g. tallying number of total assertions, failed assertions, etc.), sub-optimal XmlWriter implementation, etc.</li>
<li>Phantomjs: Include source in assertion details</li>
<li>Phantomjs: Removed the polling mechanism in favor of PhantomJS 1.6+'s <code>WebPage#onCallback</code></li>
<li>Delay start() until init() happened. Fixes #358. Closes #373.</li>
<li>urlConfig: Fix checkbox event for oldIE. Fixes #369. Closes #370.</li>
<li>Issue #365: Fix module picker for oldIE. Closes #366.</li>
<li>Fixes #344 - Capture and show test duration.</li>
<li>Rename tests to assertions in summary. Fixes #336 - Summary counts assertions but mentions 'tests'.</li>
<li>Assert: Implement propEqual and notPropEqual. Fixes #317.</li>
<li>Canvas addon: Use 0.6 as alpha value to avoid inconsistencies between browsers. Fixes #342</li>
<li>Remove global variable "assert". Fixes #341.</li>
<li>Add a test for loading tests asynchronously</li>
<li>Improve start()-called-too-often fix, initialize semaphore at 1, fixes autostart=false case. Also provide stack for the offending start() call</li>
<li>There's type-free objects in Firefox, extend objectType() to allow null match. Fixes #315</li>
<li>Push a failing assertion when calling start() while already running. Resets anyway to keep other tests going. Fixes #314</li>
<li>Adds Ninja Theme</li>
<li>Extend jsdump to output Error objects as such, including the message property. Extend throws to provide 'expected' value when possible. Fixes #307</li>
<li>Use classes to collapse assertion groups. Fixes #269</li>
<li>Readme for junitlogger addon</li>
<li>Better readme for composite addon</li>
<li>Make <code>throws</code> ES3 compatible</li>
<li>Composite: Adds test whether iframe contains content. Fixes #318 - Composite: Raises "global failure" in Opera</li>
<li>Apply the same exception handling for test and teardown try/catch as for setup</li>
</ul>
<h1><a id="user-content-1100--2012-08-30" class="anchor" href="#1100--2012-08-30" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.10.0 / 2012-08-30</h1>
<ul>
<li>Simplify licensing: Only MIT, no more MIT/GPL dual licensing.</li>
<li>Scroll the window back to top after tests finished running. Fixes #304</li>
<li>Simplify phantomjs runner to use module property in testDone callback</li>
<li>Adds module and test name to the information that is returned in the callback provided to QUnit.log(Function). Fixes #296</li>
<li>Make QUnit.expect() (without arguments) a getter. Fixes #226</li>
<li>Compare the ES6 sticky (y) property for RegExp. Can't add to tests yet. Fixes #284 - deepEqual for RegExp should compare</li>
<li>onerror: force display of global errors despite URL parameters. Fixes #288 - Global failures can be filtered out by test-limiting URL parameters</li>
<li>Remove conditional codepath based on jQuery presence from reset().</li>
<li>Add module filter to UI</li>
<li>Keep a local reference to Date. Fixes #283.</li>
<li>Update copyright to jQuery Foundation.</li>
</ul>
<h1><a id="user-content-190--2012-07-11" class="anchor" href="#190--2012-07-11" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.9.0 / 2012-07-11</h1>
<ul>
<li>added jsdoc for QUnit.assert functions</li>
<li>Styling: radius to 5px and small pass/error border, remove inner shadow</li>
<li>Move checkboxes into toolbar and give them labels and descriptions (as tooltip). Fixes #274 - Improve urlFilter API and UI</li>
<li>Where we receive no exception in throws() use a relevant message.</li>
<li>Also make module filter case-insensitive. Follow-up to #252</li>
<li>Banner: Link should ignore "testNumber" and "module". Fixes #270</li>
<li>Rename assert.raises to assert.throws. Fixes #267</li>
<li>Change package.json name property to 'qunitjs' to avoid conflict with node-qunit; will publish next release to npm</li>
</ul>
<h1><a id="user-content-180--2012-06-14" class="anchor" href="#180--2012-06-14" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.8.0 / 2012-06-14</h1>
<ul>
<li>Improve window.onerror handling</li>
<li>(issue #260) config.current should be reset at the right time.</li>
<li>Filter: Implement 'module' url parameter. Fixes #252</li>
<li>raises: ignore global exceptions stemming from test. Fixes #257 - Globally-executed errors sneak past raises in IE</li>
</ul>
<h1><a id="user-content-170--2012-06-07" class="anchor" href="#170--2012-06-07" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.7.0 / 2012-06-07</h1>
<ul>
<li>Add config.requireExpects. Fixes #207 - Add option to require all tests to call expect().</li>
<li>Improve extractStacktrace() implementation. Fixes #254 - Include all relevant stack lines</li>
<li>Make filters case-insensitive. Partial fix for #252</li>
<li>is() expects lowercase types. Fixes #250 - Expected Date value is not displayed properly</li>
<li>Fix phantomjs addon header and add readme. Fixes #239</li>
<li>Add some hints to composite addon readme. Fixes #251</li>
<li>Track tests by the order in which they were run and create rerun links based on that number. Fixes #241 - Make Rerun link run only a single test.</li>
<li>Use QUnit.push for raises implementation. Fixes #243</li>
<li>CLI runner for phantomjs</li>
<li>Fix jshint validation until they deal with /** */ comments properly</li>
<li>Update validTest() : Simplify logic, clarify vars and add comments</li>
<li>Refactor assertion helpers into QUnit.assert (backwards compatible)</li>
<li>Add Rerun link to placeholders. Fixes #240</li>
</ul>
<h1><a id="user-content-160--2012-05-04" class="anchor" href="#160--2012-05-04" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.6.0 / 2012-05-04</h1>
<ul>
<li>Save stack for each test, use that for failed expect() results, points at the line where test() was called. Fixes #209</li>
<li>Prefix test-output id and ignore that in noglobals check. Fixes #212</li>
<li>Only check for an exports object to detect a CommonJS environment. Fixes #237 - Incompatibility with require.js</li>
<li>Add testswarm integration as grunt task</li>
<li>Added padding on URL config checkboxes.</li>
<li>Cleanup composite addon: Use callback registration instead of overwriting them. Set the correct src on rerun link (and dblclick). Remove the composite test itself, as that was a crazy hack not worth maintaining</li>
<li>Cleanup reset() test and usage - run testDone callback first, to allow listeners ignoring reset assertions</li>
<li>Double clicking on composite test rows opens individual test page</li>
<li>test-message for all message-bearing API reporting details</li>
</ul>
<h1><a id="user-content-150--2012-04-04" class="anchor" href="#150--2012-04-04" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.5.0 / 2012-04-04</h1>
<ul>
<li>Modify "Running..." to display test name. Fixes #220</li>
<li>Fixed clearing of sessionStorage in Firefox 3.6.</li>
<li>Fixes #217 by calling "block" with config.current.testEnvironment</li>
<li>Add stats results to data. QUnit.jUnitReport function take one argument {   xml:'&lt;?xml ...',   results:{failed:0, passed:0, total:0, time:0} }</li>
<li>Add link to MDN about stack property</li>
</ul>
<h1><a id="user-content-140--2012-03-10" class="anchor" href="#140--2012-03-10" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.4.0 / 2012-03-10</h1>
<ul>
<li>Prefix test-related session-storage items to make removal more specific. Fixes #213 - Keep hide-passed state when clearing session storage</li>
<li>Update grunt.js with separate configs for qunit.js and grunt.js, also add tests but disable for now, not passing yet. Add grunt to devDependencies</li>
<li>typo</li>
<li>Cleanup grunt.js, no need for the banner</li>
<li>Fix lint errors and some formatting issues. Use QUnit.pushFailure for noglobals and global error handler.</li>
<li>Fix a missing expect in logs test</li>
<li>Add grunt.js configuration and include some usage instructions in the readme</li>
<li>Update package.json</li>
<li>Partially revert af27eae841c3e1c01c46de72d676f1047e1ee375 - can't move reset around, so also don't wrap in try-catch, as the result of that is effectively swallowed. Can't output the result as the outputting is already done.</li>
<li>Add QUnit.pushFailure to log error conditions like exceptions. Accepts stacktrace as second argument, allowing extraction with catched exceptions (useful even in Safari). Remove old fail() function that would just log to console, not useful anymore as regular test output is much more useful by now. Move up QUnit.reset() call to just make that another failed assertion. Used to not make a test fail. Fixes #210</li>
<li>Update equals and same deprecations to use QUnit.push to provide correct source lines. Fixes #211</li>
<li>Add a test file for narwhal integration. Has to use print instead of console.log. Fails when an assertion fails, something about setInterval...</li>
<li>Apply notrycatch option to setup and teardown as well. Fixes #203. Reorder noglobals check to allow teardown to remove globals that were introduced intentionally. Fixes #204</li>
<li>Extend exports object with QUnit properties at the end of the file to export everything.</li>
<li>Output source line for ok() assertions. Fixes #202</li>
<li>Make test fail if no assertions run. Fixes #178</li>
<li>Sort object output alphabetically in order to improve diffs of objects where properties were set in a different order. Fixes #206</li>
<li>Revert "Change fixture reset behavior", changing #194 and #195 to wontfix.</li>
</ul>
<h1><a id="user-content-130--2012-02-26" class="anchor" href="#130--2012-02-26" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.3.0 / 2012-02-26</h1>
<ul>
<li>Cleanup test markup</li>
<li>Fix the jQuery branch of fixture reset. Would break when no fixture exists.</li>
<li>Added initial version of a junitlogger addon.</li>
<li>Escape document.title before inserting into markup. Extends fix for #127</li>
<li>Catch assertions running outside of test() context, make sure source is provided even for ok(). Fixes #98</li>
<li>Improve global object access, based on comments for 1a9120651d5464773256d8a1f2cf2eabe38ea5b3</li>
<li>Clear all sessionStorage entries once all tests passed. Helps getting rid of items from renamed tests. Fixes #101</li>
<li>Set fixed dimensions for #qunit-fixture. Fixes #114</li>
<li>Extend nodejs test runner to check for stacktrace output, twice</li>
<li>Extend nodejs test runner to check for stacktrace output</li>
<li>Generate more base markup, but allow the user to exclude that completely or choose their own. Fixes #127</li>
<li>Add a simple test file to check basic nodejs integration works</li>
<li>Check for global object to find setTimeout in node</li>
<li>Fix CommonJS export by assigning QUnit to module.exports.</li>
<li>Remove the testEnvironmentArg to test(). Most obscure, never used anywhere. test() is still heavily overloaded with argument shifting, this makes it a little more sane. Fixes #172</li>
<li>Serialize expected and actual values only when test fails. Speeds up output of valid tests, especially for lots of large objects. Fixes #183</li>
<li>Fix sourceFromsStacktrace to get the right line in Firefox. Shift the 'error' line away in Chrome to get a match.</li>
<li>Fix references to test/deepEqual.js</li>
<li>In autorun mode, moduleDone is called without matching moduleStart. Fix issue #184</li>
<li>Fixture test: allow anything falsy in test as getAttribute in oldIE will return empty string instead of null. We don't really care.</li>
<li>Keep label and checkbox together ( <a href="https://i.imgur.com/5Wk3A.png">https://i.imgur.com/5Wk3A.png</a> )</li>
<li>Add readme for themes</li>
<li>Fix bad global in reset()</li>
<li>Some cleanup in theme addons</li>
<li>Update headers</li>
<li>Update nv.html, add gabe theme based on <a href="https://github.com/jquery/qunit/pull/188">https://github.com/jquery/qunit/pull/188</a></li>
<li>Experimental custom theme based on <a href="https://github.com/jquery/qunit/pull/62">https://github.com/jquery/qunit/pull/62</a> by NV</li>
<li>Replace deprecated same and equals aliases with placeholders that just throw errors, providing a hint at what to use instead. Rename test file to match that.</li>
<li>Can't rely on outerHTML for Firefox &lt; 11. Use cloneNode instead.</li>
<li>Merge remote branch 'conzett/master'</li>
<li>Cleanup whitespace</li>
<li>Update sessionStorage support test to latest version from Modernizr, trying to setItem to avoid QUOTA_EXCEEDED_EXCEPTION</li>
<li>Change fixture reset behavior</li>
<li>Merge pull request #181 from simonz/development</li>
<li>Escaping test names</li>
<li>Show exception stack when test failed</li>
</ul>
<h1><a id="user-content-120--2011-11-24" class="anchor" href="#120--2011-11-24" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.2.0 / 2011-11-24</h1>
<ul>
<li>remove uses of equals(), as it's deprecated in favor of equal()</li>
<li>Code review of "Allow objects with no prototype to be tested against object literals."</li>
<li>Allow objects with no prototype to tested against object literals.</li>
<li>Fix IE8 "Member not found" error</li>
<li>Using node-qunit port, the start/stop function are not exposed so we need to prefix any call to them with 'QUnit'. Aka: start() -&gt; QUnit.start()</li>
<li>Remove the 'let teardown clean up globals test' - IE&lt;9 doesn't support (==buggy) deleting window properties, and that's not worth the trouble, as everything else passes just fine. Fixes #155</li>
<li>Fix globals in test.js, part 2</li>
<li>Fix globals in test.js. ?tell wwalser to use ?noglobals every once in a while</li>
<li>Extend readme regarding release process</li>
</ul>
<h1><a id="user-content-110--2011-10-11" class="anchor" href="#110--2011-10-11" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.1.0 / 2011-10-11</h1>
<ul>
<li>Fixes #134 - Add a window.onerror handler. Makes uncaught errors actually fail the testsuite, instead of going by unnoticed.</li>
<li>Whitespace cleanup</li>
<li>Merge remote branch 'trevorparscal/master'</li>
<li>Fixed IE compatibility issues with using toString on NodeList objects, which in some browsers results in [object Object] rather than [object NodeList]. Now using duck typing for NodeList objects based on the presence of length, length being a number, presence of item method (which will be typeof string in IE and function in others, so we just check that it's not undefined) and that item(0) returns the same value as [0], unless it's empty, in which case item(0) will return 0, while [0] would return undefined. Tested in IE6, IE8, Firefox 6, Safari 5 and Chrome 16.</li>
<li>Update readme with basic notes on releases</li>
<li>More whitespace/parens cleanup</li>
<li>Check if setTimeout is available before trying to delay running the next task. Fixes #160</li>
<li>Whitespace/formatting fix, remove unnecessary parens</li>
<li>Use alias for Object.prototype.toString</li>
<li>Merge remote branch 'trevorparscal/master'</li>
<li>Merge remote branch 'wwalser/recursionBug'</li>
<li>Default 'expected' to null in asyncTest(), same as in test() itself.</li>
<li>Whitespace cleanup</li>
<li>Merge remote branch 'mmchaney/master'</li>
<li>Merge remote branch 'Krinkle/master'</li>
<li>Using === instead of ==</li>
<li>Added more strict array type detection for dump output, and allowed NodeList objects to be output as arrays</li>
<li>Fixes a bug where after an async test, assertions could move between test cases because of internal state (config.current) being incorrectly set</li>
<li>Simplified check for assertion count and adjusted whitespace</li>
<li>Redo of fixing issue #156 (Support Object.prototype extending environment). * QUnit.diff: Throws exception without this if Object.prototype is set (Property 'length' of undefined. Since Object.prototype.foo doesn't have a property 'rows') * QUnit.url: Without this fix, if Object.prototype.foo is set, the url will be set to ?foo=...&amp;the=rest. * saveGlobals: Without this fix, whenever a member is added to Object.prototype, saveGlobals will think it was a global variable in this loop. --- This time using the call method instead of obj.hasOwnProperty(key), which may fail if the object has that as it's own property (touché!).</li>
<li>Handle expect(0) as expected, i.e. expect(0); ok(true, foo); will cause a test to fail</li>
</ul>
<h1><a id="user-content-100--2011-10-06" class="anchor" href="#100--2011-10-06" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.0.0 / 2011-10-06</h1>
<ul>
<li>Make QUnit work with TestSwarm</li>
<li>Run other addons tests as composite addon demo. Need to move that to /test folder once this setup actually works</li>
<li>Add-on: New assertion-type: step()</li>
<li>added parameter to start and stop allowing a user to increment/decrement the semaphore more than once per call</li>
<li>Update readmes with .md extension for GitHub to render them as markdown</li>
<li>Update close-enough addon to include readme and match (new) naming conventions</li>
<li>Merge remote branch 'righi/close-enough-addon'</li>
<li>Canvas addon: Update file references</li>
<li>Update canvas addon: Rename files and add README</li>
<li>Merge remote branch 'wwalser/composite'</li>
<li>Fix #142 - Backslash characters in messages should not be escaped</li>
<li>Add module name to testStart and testDone callbacks</li>
<li>Removed extra columns in object literals. Closes #153</li>
<li>Remove dead links in comments.</li>
<li>Merge remote branch 'wwalser/multipleCallbacks'</li>
<li>Fixed syntax error and CommonJS incompatibilities in package.json</li>
<li>Allow multiple callbacks to be registered.</li>
<li>Add placeholder for when Safari may end up providing useful error handling</li>
<li>changed file names to match addon naming convention</li>
<li>Whitespace</li>
<li>Created the composite addon.</li>
<li>Using array and object literals.</li>
<li>Issue #140: Make toggle system configurable.</li>
<li>Merge remote branch 'tweetdeck/master'</li>
<li>Adds the 'close enough' addon to determine if numbers are acceptably close enough in value.</li>
<li>Fix recursion support in jsDump, along with tests. Fixes #63 and #100</li>
<li>Adding a QUnit.config.altertitle flag which will allow users to opt-out of the functionality introduced in 60147ca0164e3d810b8a9bf46981c3d9cc569efc</li>
<li>Refactor window.load handler into QUnit.load, makes it possible to call it manually.</li>
<li>More whitespace cleanup</li>
<li>Merge remote branch 'erikvold/one-chk-in-title'</li>
<li>Whitespace</li>
<li>Merge remote branch 'wwalser/syncStopCalls'</li>
<li>Introducing the first QUnit addon, based on <a href="https://github.com/jquery/qunit/pull/84">https://github.com/jquery/qunit/pull/84</a> - adds QUnit.pixelEqual assertion method, along with example tests.</li>
<li>Remove config.hidepassed setting in test.js, wasn't intended to land in master.</li>
<li>Expose QUnit.config.hidepassed setting. Overrides sessionStorage and enables enabling the feature programmatically. Fixes #133</li>
<li>Fix formatting (css whitespace) for tracebacks.</li>
<li>Expose extend, id, and addEvent methods.</li>
<li>minor comment typo correction</li>
<li>Ignore Eclipse WTP .settings</li>
<li>Set 'The jQuery Project' as author in package.json</li>
<li>Fixes a bug where synchronous calls to stop would cause tests to end before start was called again</li>
<li>Point to planning testing wiki in readme</li>
<li>only add one checkmark to the document.title</li>
<li>Escape the stacktrace output before setting it as innerHTML, since it tends to contain <code>&lt;</code> and <code>&gt;</code> characters.</li>
<li>Cleanup whitespace</li>
<li>Run module.teardown before checking for pollution. Fixes #109 - noglobals should run after module teardown</li>
<li>Fix accidental global variable "not"</li>
<li>Update document.title status to use more robust unicode escape sequences, works even when served with non-utf-8-charset.</li>
<li>Modify document.title when suite is done to show success/failure in tab, allows you to see the overall result without seeing the tab content.</li>
<li>Merge pull request #107 from sexyprout/master</li>
<li>Set a generic font</li>
<li>Add/update headers</li>
<li>Drop support for deprecated #main in favor of #qunit-fixture. If this breaks your testsuite, replace id="main" with id="qunit-fixture". Fixes #103</li>
<li>Remove the same key as the one being set. Partial fix for #101</li>
<li>Don't modify expected-count when checking pollution. The failing assertion isn't expected, so shouldn't be counted. And if expect wasn't used, the count is misleading.</li>
<li>Fix order of noglobals check to produce correct introduced/delete error messages</li>
<li>Prepend module name to sessionStorage keys to avoid conflicts</li>
<li>Store filter-tests only when checked</li>
<li>Write to sessionStorage only bad tests</li>
<li>Moved QUnit.url() definition after QUnit properties are merged into the global scope. Fixes #93 - QUnit url/extend function breaking urls in jQuery ajax test component</li>
<li>Add a "Rerun" link to each test to replace the dblclick (still supported, for now).</li>
<li>Fixed the regex for parsing the name of a test when double clicking to filter.</li>
<li>Merge remote branch 'scottgonzalez/url'</li>
<li>Added checkboxes to show which flags are currently on and allow toggling them.</li>
<li>Retain all querystring parameters when filtering a test via double click.</li>
<li>Added better querystring parsing. Now storing all querystring params in QUnit.urlParams so that we can carry the params forward when filtering to a specific test. This removes the ability to specify multiple filters.</li>
<li>Make reordering optional (QUnit.config.reorder = false) and optimize "Hide passed tests" mode by also hiding "Running [testname]" entries.</li>
<li>Added missing semicolons and wrapped undefined key in quotes.</li>
<li>Optimize test hiding, add class on page load if stored in sessionStorage</li>
<li>Optimize the hiding of passed tests.</li>
<li>Position test results above test list, making it visible without ever having to scroll. Create a placeholder to avoid pushing down results later.</li>
<li>Don't check for existing qunit-testresult element, it gets killed on init anyway.</li>
<li>Added URL flag ?notrycatch (ala ?noglobals) for debugging exceptions. Won't try/catch test code, giving better debugging changes on the original exceptions. Fixes #72</li>
<li>Always show qunit-toolbar (if at all specified), persist checkbox via sessionStorage. Fixes #47</li>
<li>Use non-html testname for calls to fail(). Fixes #77</li>
<li>Overhaul of QUnit.callbacks. Consistent single argument with related properties, with additional runtime property for QUnit.done</li>
<li>Extended test/logs.html to capture more of the callbacks.</li>
<li>Fixed moduleStart/Done callbacks. Added test/logs.html to test these callbacks. To be extended.</li>
<li>Update copyright and license header. Fixes #61</li>
<li>Formatting fix.</li>
<li>Use a semaphore to synchronize stop() and start() calls. Fixes #76</li>
<li>Merge branch 'master' of <a href="https://github.com/paulirish/qunit">https://github.com/paulirish/qunit</a> into paulirish-master</li>
<li>Added two tests for previous QUnit.raises behaviour. For #69</li>
<li>add optional 2. arg to QUnit.raises #69.</li>
<li>fix references inside Complex Instances Nesting to what was originally intended.</li>
<li>Qualify calls to ok() in raises() for compatibility with CLI environments.</li>
<li>Fix done() handling, check for blocking, not block property</li>
<li>Fix moduleStart/Done and done callbacks.</li>
<li>Replacing sessionStorage test with the one from Modernizr/master (instead of current release). Here's hoping it'll work for some time.</li>
<li>Updated test for availability of sessionStorage, based on test from Modernizr. Fixes #64</li>
<li>Defer test execution when previous run passed, persisted via sessionStorage. Fixes #49</li>
<li>Refactored module handling and queuing to enable selective defer of test runs.</li>
<li>Move assertions property from config to Test</li>
<li>Move expected-tests property from config to Test</li>
<li>Refactored test() method to delegate to a Test object to encapsulate all properties and methods of a single test, allowing further modifications.</li>
<li>Adding output of sourcefile and linenumber of failed assertions (except ok()). Only limited cross-browser support for now. Fixes #60</li>
<li>Drop 'hide missing tests' feature. Fixes #48</li>
<li>Adding readme. Fixes #58</li>
<li>Merge branch 'prettydiff'</li>
<li>Improve jsDump output with formatted diffs.</li>
<li>Cleanup whitespace</li>
<li>Cleanup whitespace</li>
<li>Added additional guards around browser specific code and cleaned up jsDump code</li>
<li>Added guards around tests which are only for browsers</li>
<li>cleaned up setTimeout undefined checking and double done on test finish</li>
<li>fixing .gitignore</li>
<li>making window setTimeout query more consistent</li>
<li>Moved expect-code back to beginning of function, where it belongs. Fixes #52</li>
<li>Bread crumb in header: Link to suite without filters, add link to current page based on the filter, if present. Fixes #50</li>
<li>Make the toolbar element optional when checking for show/hide of test results. Fixes #46</li>
<li>Adding headless.html to manually test logging and verify that QUnit works without output elements. Keeping #qunit-fixture as a few tests actually use that.</li>
<li>Fix for QUnit.moduleDone, get rid of initial bogus log. Fixes #33</li>
<li>Pass raw data (result, message, actual, expected) as third argument to QUnit.log. Fixes #32</li>
<li>Dump full exception. Not pretty, but functional (see issue Pretty diff for pretty output). Fixes #31</li>
<li>Don't let QUnit.reset() cause assertions to run. Manually applied from Scott Gonzalez branch. Fixes #34</li>
<li>Added missing semicolons. Fixes #37</li>
<li>Show okay/failed instead of undefined. Fixes #38</li>
<li>Expose push as QUnit.push to build custom assertions. Fixes #39</li>
<li>Respect filter pass selection when writing new results. Fixes #43</li>
<li>Cleanup tests, removing asyncTest-undefined check and formatting</li>
<li>Reset: Fall back to innerHTML when jQuery isn't available. Fixes #44</li>
<li>Merge branch 'master' of github.com:jquery/qunit</li>
<li>reset doesn't exist here - fixes #28.</li>
<li>
<ul>
<li>less css cruft, better readability - replaced inline style for test counts with "counts" class - test counts now use a "failed"/"passed" vs "pass"/"fail", shorter/more distinct selectors - pulled all test counts styling together and up (they're always the same regardless of section pass/fail state)</li>
</ul>
</li>
<li>Adding .gitignore file</li>
<li>Removing diff test - diffing works fine, as the browser collapses whitespace in its output, but the test can't do that and isn't worth fixing.</li>
<li>Always synchronize the done-step (it'll set the timeout when necessary), fixes timing race conditions.</li>
<li>Insert location.href as an anchor around the header. Fixes issue #29</li>
<li>
<ul>
<li>kill double ;; in escapeHtml. oops</li>
</ul>
</li>
<li>Removed html escaping from QUnit.diff, as input is already escaped, only leads to double escaping. Replaced newlines with single whitespace.</li>
<li>Optimized and cleaned up CSS file</li>
<li>Making the reset-method non-global (only module, test and assertions should be global), and fixing the fixture reset by using jQuery's html() method again, doesn't work with innerHTML, yet</li>
<li>Introducing #qunit-fixture element, deprecating the (never documented) #main element. Doesn't require inline styles and is now independent of jQuery.</li>
<li>Amending previous commit: Remove jQuery-core specific resets (will be replaced within jQuery testsuite). Fixes issue #19 - QUnit.reset() removes global jQuery ajax event handlers</li>
<li>Remove jQuery-core specific resets (will be replaced within jQuery testsuite). Fixes issue #19 - QUnit.reset() removes global jQuery ajax event handlers</li>
<li>Cleaning up rubble from the previous commit.</li>
<li>Added raises assertion, reusing some of kensnyder's code.</li>
<li>Merged kensnyder's object detection code. Original message: Streamlined object detection and exposed QUnit.objectType as a function.</li>
<li>Fixed some bad formatting.</li>
<li>Move various QUnit properties below the globals-export to avoid init becoming a global method. Fixes issue #11 - Remove 'init' function from a global namespace</li>
<li>Improved output when expected != actual: Output both only then, and add a diff. Fixes issue #10 - Show diff if equal() or deepEqual() failed</li>
<li>Expand failed tests on load. Fixes issue #8 - Failed tests expanded on load</li>
<li>Set location.search for url-filtering instead of location.href. Fixes issue #7 - Modify location.search instead of location.href on test double-click</li>
<li>Add QUnit.begin() callback. Fixes issue #6 - Add 'start' callback.</li>
<li>add css style for result (".test-actual") in passed tests</li>
<li>Fixed output escaping by using leeoniya's custom escaping along with innerHTML. Also paves the way for outputting diffs.</li>
<li>Cleanup</li>
<li>Revert "Revert part of bad merge, back to using createTextNode"</li>
<li>Revert part of bad merge, back to using createTextNode</li>
<li>Fixed doubleclick-handler and filtering to rerun only a single test.</li>
<li>Add ability to css style a test's messages, expected and actual results. Merged from Leon Sorokin (leeoniya).</li>
<li>Remove space between module name and colon</li>
<li>
<ul>
<li>removed "module" wording from reports (unneeded and cluttery) - added and modified css to make module &amp; test names styleable</li>
</ul>
</li>
<li>Logging support for  Each test can extend the module testEnvironment</li>
<li>Fixing whitespace</li>
<li>Update tests to use equal() and deepEqual() rather than the deprecated equals() and same()</li>
<li>Consistent argument names for deepEqual</li>
<li>Skip DOM part of jsDump test if using a SSJS environment without a DOM</li>
<li>Improve async testing by creating the result element before running the test, updating it later. If the test fails, its clear which test is the culprit.</li>
<li>Add autostart option to config. Set via QUnit.config.autostart = false; start later via QUnit.start()</li>
<li>Expose QUnit.config, but don't make config a global</li>
<li>Expose QUnit.config as global to make external workarounds easier</li>
<li>Merge branch 'asyncsetup'</li>
<li>Allowing async setup and teardown. Fixes <a href="https://github.com/jquery/qunit/issues#issue/20">https://github.com/jquery/qunit/issues#issue/20</a></li>
<li>Always output expected and actual result (no reason not to). Fixes <a href="https://github.com/jquery/qunit/issues#issue/21">https://github.com/jquery/qunit/issues#issue/21</a></li>
<li>More changes to the detection of types in jsDump's typeOf.</li>
<li>Change the typeOf checks in QUnit to be more accurate.</li>
<li>Added test for jsDump and modified its options to properly output results when document.createTextNode is used; currently tests for DOM elements cause a stackoverflow error in IEs, works fine, with the correct output, elsewhere</li>
<li>Always use jsDump to output result objects into messages, making the output for passing assertions more useful</li>
<li>Make it so that the display is updated, at least, once a second - also prevents scripts from executing for too long and causing problems.</li>
<li>added tests and patch for qunit.equiv to avoid circular references in objects and arrays</li>
<li>No reason to continue looping, we can stop at this point. Thanks to Chris Thatcher for the suggestion.</li>
<li>Use createTextNode instead of innerHTML for showing test result since expected and actual might be something that looks like a tag.</li>
<li>'Test card' design added</li>
<li>switched green to blue for top-level pass + reduced padding</li>
<li>Bringing the QUnit API in line with the CommonJS API.</li>
<li>Explicitly set list-style-position: inside on result LIs.</li>
<li>Madness with border-radius.</li>
<li>Corrected banner styles for new class names</li>
<li>Added rounded corners and removed body rules for embedded tests</li>
<li>Resolving merge conflicts.</li>
<li>added colouring for value summary</li>
<li>adding some extra text colours</li>
<li>added styles for toolbar</li>
<li>added new styles</li>
<li>IE 6 and 7 weren't respecting the CSS rules for the banner, used a different technique instead.</li>
<li>Went a bit further and made extra-sure that the target was specified correctly.</li>
<li>Fixed problem where double-clicking an entry in IE caused an error to occur.</li>
<li>Path for <a href="https://dev.jquery.com/ticket/5426">https://dev.jquery.com/ticket/5426</a> - fix the microformat test result</li>
<li>Fixed test() to use 'expected' 2nd param</li>
<li>Remove the named function expressions, to stop Safari 2 from freaking out. Fixes #5.</li>
<li>Each test can extend the module testEnvironment</li>
<li>Extra test for current test environment</li>
<li>Make the current testEnvironment available to utility functions</li>
<li>typeOf in QUnit.jsDump now uses QUnit.is</li>
<li>hoozit in QUnit.equiv now uses QUnit.is</li>
<li>Properly set label attributes.</li>
<li>Some minor tweaks to RyanS' GETParams change.</li>
<li>left a console.log in :(</li>
<li>Took into account a fringe case when using qunit with testswarm. Trying to run all the tests with the extra url params from testswarm would make qunit look for a testsuite that did not exist</li>
<li>need to set config.currentModule to have correct names and working filters</li>
<li>Support logging of testEnvironment</li>
<li>async tests aren't possible on rhino</li>
<li>Fixed a missing QUnit.reset().</li>
<li>The QUnit. prefix was missing from the uses of the start() method.</li>
<li>Merged lifecycle object into testEnvironment</li>
<li>"replacing totally wrong diff algorithm with a working one" Patch from kassens (manually applied).</li>
<li>fixing jslint errors in test.js</li>
<li>Fixed: testDone() was always called with 0 failures in CommonJS mode</li>
<li>Fixed: moduleDone() was invoked on first call to module()</li>
<li>Added a new asyncTest method - removes the need for having to call start() at the beginning of an asynchronous test.</li>
<li>Added support for expected numbers in the test method.</li>
<li>Fixed broken dynamic loading of tests (can now dynamically load tests and done still works properly).</li>
<li>Simplified the logic for calling 'done' and pushing off new tests - was causing too many inconsistencies otherwise.</li>
<li>Simplified the markup for the QUnit test test suite.</li>
<li>Realized that it's really easy to handle the case where stop() has been called and then an exception is thrown.</li>
<li>Added in better logging support. Now handle moduleStart/moduleDone and testStart/testDone. Also make sure that done only fires once at the end.</li>
<li>Made it so that you can reset the suite to an initial state (at which point tests can be dynamically loaded and run, for example).</li>
<li>Re-worked QUnit to handle dynamic loading of additional code (the 'done' code will be re-run after additional code is loaded).</li>
<li>Removed the old SVN version stuff.</li>
<li>Moved the QUnit source into a separate directory and updated the test suite/packages files.</li>
<li>Added in CommonJS support for exporting the QUnit functionality.</li>
<li>Missing quote from package.json.</li>
<li>Fixed trailing comma in package.json.</li>
<li>Added a CommonJS/Narwhal package.json file.</li>
<li>Accidentally reverted the jsDump/equiv changes that had been made.</li>
<li>Hide the filter toolbar if it's not needed. Also exposed the jsDump and equiv objects on QUnit.</li>
<li>Retooled the QUnit CSS to be more generic.</li>
<li>Renamed the QUnit files from testrunner/testsuite to QUnit.</li>
<li>Expose QUnit.equiv and QUnit.jsDump in QUnit.</li>
<li>Moved the QUnit test directory into the QUnit directory.</li>
<li>Reworked the QUnit CSS (moved jQuery-specific stuff out, made all the other selectors more specific).</li>
<li>Removed the #main reset for non-jQuery code (QUnit.reset can be overwritten with your own reset code).</li>
<li>Moved the QUnit toolbar inline.</li>
<li>Switched to using a qunit- prefix for special elements (banner, userAgent, and tests).</li>
<li>Missed a case in QUnit where an element was assumed to exist.</li>
<li>QUnit's isSet and isObj are no longer needed - you should use same instead.</li>
<li>Make sure that QUnit's equiv entity escaping is enabled by default (otherwise the output gets kind of crazy).</li>
<li>Refactored QUnit, completely reorganized the structure of the file. Additionally made it so that QUnit can run outside of a browser (inside Rhino, for example).</li>
<li>Removed some legacy and jQuery-specific test methods.</li>
<li>Added callbacks for tests and modules. It's now possible to reproduce the full display of the testrunner without using the regular rendering.</li>
<li>QUnit no longer depends upon rendering the results (it can work simply by using the logging callbacks).</li>
<li>Made QUnit no longer require jQuery (it is now a standalone, framework independent, test runner).</li>
<li>Reverted the noglobals changed from QUnit - causing chaos in the jQuery test suite.</li>
<li>qunit: removed noglobals flag, instead always check for globals after teardown; if a test has to introduce a global "myVar", use delete window.myVar in teardown or at the end of a test</li>
<li>qunit: don't child selectors when IE should behave nicely, too</li>
<li>qunit: improvement for the test-scope: create a new object and call setup, the test, and teardown in the scope of that object - allows you to provide test fixtures to each test without messing with global data; kudos to Martin Häcker for the contribution</li>
<li>qunit: added missing semicolons</li>
<li>qunit: fixed a semicolon, that should have been a comma</li>
<li>QUnit: implemented error handling for Opera as proposed by #3628</li>
<li>qunit: fix for <a href="https://dev.jquery.com/ticket/3215">https://dev.jquery.com/ticket/3215</a> changing wording of testresults, to something more positive (x of y passed, z failed)</li>
<li>QUnit: testrunner.js: Ensures equality of types (String, Boolean, Number) declared with the 'new' prefix. See comments #3, #4 and #5 on <a href="http://philrathe.com/articles/equiv">http://philrathe.com/articles/equiv</a></li>
<li>qunit: wrap name of test in span when a module is used for better styling</li>
<li>qunit: auto-prepend default mark (#header, #banner, #userAgent, #tests) when not present</li>
<li>Landing some changes to add logging to QUnit (so that it's easier to hook in to when a test finishes).</li>
<li>Added checkbox for hiding missing tests (tests that fail with the text 'missing test - untested code is broken code')</li>
<li>qunit: eol-style:native and mime-type</li>
<li>HTML being injected for the test result wasn't valid HTML.</li>
<li>qunit: setting mimetype for testsuite.css</li>
<li>qunit: update to Ariel's noglobals patch to support async tests as well</li>
<li>Landing Ariel's change - checks for global variable leakage.</li>
<li>qunit: run module-teardown in its own synchronize block to synchronize with async tests (ugh)</li>
<li>qunit: same: equiv - completely refactored in the testrunner.</li>
<li>testrunner.js:     - Update equiv to support Date and RegExp.     - Change behavior when comparing function:         - abort when in an instance of Object (when references comparison failed)         - skip otherwise (like before)</li>
<li>qunit: code refactoring and cleanup</li>
<li>QUnit: update equiv to latest version, handling multiple arguments and NaN, see <a href="http://philrathe.com/articles/equiv">http://philrathe.com/articles/equiv</a></li>
<li>QUnit: cleanup, deprecating compare, compare2 and serialArray: usage now throws an error with a helpful message</li>
<li>QUnit: optional timeout argument for stop, while making tests undetermined, useful for debugging</li>
<li>QUnit: added toolbar with "hide passed tests" checkbox to help focus on failed tests</li>
<li>QUnit: minor output formatting</li>
<li>QUnit: adding same-assertion for a recursive comparison of primitive values, arrays  and objects, thanks to Philippe Rathé for the contribution, including tests</li>
<li>QUnit: adding same-assertion for a recursive comparison of primitive values, arrays  and objects, thanks to Philippe Rathé for the contribution, including tests</li>
<li>QUnit: adding same-assertion for a recursive comparison of primitive values, arrays  and objects, thanks to Philippe Rathé for the contribution, including tests</li>
<li>qunit: use window.load to initialize tests, allowing other code to run on document-ready before starting to run tests</li>
<li>qunit: allow either setup or teardown, instead of both or nothing</li>
<li>qunit: make everything private by default, expose only public API; removed old timeout-option (non-deterministic, disabled for a long time anyway); use local $ reference instead of global jQuery reference; minor code cleanup (var config instead of _config; queue.shift instead of slice)</li>
<li>qunit: added support for module level setup/teardown callbacks</li>
<li>qunit: modified example for equals to avoid confusion with parameter ordering</li>
<li>qunit: added id/classes to result element to enable integration with browser automation tools, see <a href="http://docs.jquery.com/QUnit#Integration_into_Browser_Automation_Tools">http://docs.jquery.com/QUnit#Integration_into_Browser_Automation_Tools</a></li>
<li>qunit: replaced $ alias with jQuery (merged from jquery/test/data/testrunner.js)</li>
<li>qunit: fixed inline documentation for equals</li>
<li>qunit testrunner - catch and log possible error during reset()</li>
<li>QUnit: Switched out Date and Rev for Id.</li>
<li>qunit: when errors are thrown in a test, the message is successfully show on all browsers.</li>
<li>qunit: added license header</li>
<li>qunit: moved jquery testrunner to top-level project, see <a href="http://docs.jquery.com/QUnit">http://docs.jquery.com/QUnit</a></li>
<li>Share project 'qunit' into '<a href="https://jqueryjs.googlecode.com/svn">https://jqueryjs.googlecode.com/svn</a>'</li>
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
      <li class="mr-3">&copy; 2017 <span title="0.14508s from unicorn-717302012-n84xm">GitHub</span>, Inc.</li>
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


    <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/compat-91f98c37fc84eac24836eec2567e9912742094369a04c4eba6e3cd1fa18902d9.js"></script>
    <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-73353845059b604494bd29bc913b29ac45035dc2b0e14f9f9a12987fae52af59.js"></script>
    
    <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-025672a52b980b3949e8952ccb1d1badad756e42ad42fca6a1a0002365a43c45.js"></script>
    
    
    
    
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

