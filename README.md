sublime-drupal
==============

Script to setup a Sublime Text 2 editor for Drupal development (Mac & Linux)

<p>The installer include plugins and settings to configure the environment in order to speed up the Drupal Development process.</p>

<h2>Plugins Included</h2>

<ul>
  <li><a href="https://github.com/wbond/sublime_package_control">Package Control</a></li>
  <li><a href="https://github.com/kemayo/sublime-text-2-git">Git</a></li>
  <li><a href="http://github.com/facelessuser/BracketHighlighter">Bracket Highlighter</a></li>
  <li><a href="https://github.com/spadgos/sublime-jsdocs">DocBlockr</a></li>
  <li><a href="git://github.com/niklas-heer/sublime-css-colors.git">LiveCSS</a></li>
  <li><a href="http://github.com/BrianGilbert/Sublime-Text-2-Goto-Drupal-API">Goto Drupal API</a></li>
  <li><a href="https://github.com/rypit/DrupalCodingStandard">Drupal Coding Standard</a></li>
  <li><a href="http://github.com/juhasz/drupal_sublime-snippets">Drupal Sublime Snippets</a></li>
  <li><a href="https://github.com/enzolutions/drupal-sublime-config">Drupal Sublime Config</a></li>
  <li><a href="https://github.com/kemayo/sublime-text-2-goto-documentation">Goto Documentation</a></li>
  <li><a href="https://github.com/tanc/st2-drupal-autocomplete">Drupal Auto Complete</a></li>
  <li><a href="https://github.com/SublimeLinter/SublimeLinter">SublimeLinter</a></li>
  <li><a href="https://github.com/buymeasoda/soda-theme/">Sode Theme</a></li>
</ul>

<h3>Installer requirements</h3>
<p>If you are installing in mac you must to install the wget command, you can follow the guide <a href="http://osxdaily.com/2012/05/22/install-wget-mac-os-x/">http://osxdaily.com/2012/05/22/install-wget-mac-os-x/</a></p>

<h2>How to install</h2>

<ul>
  <li>Install Sublime Text 2 from <a href="http://www.sublimetext.com">http://www.sublimetext.com</a></li>
  <li>git clone https://github.com/enzolutions/sublime-drupal</li>
  <li>cd sublime-drupal</li>
  <li>chmod +x SublimeDrupal.sh</li>
  <li>./SublimeDrupal.sh</li>
</ul>

<h3>Installation Notes</h3>

<h4>Drupal Coding Standard</h4>
  <p>To use the  Drupal Coding Standard plugin you have to install before PHP Code Sniffer , you check the installation process at <a href="http://drupal.org/node/1419988">http://drupal.org/node/1419988</a></p>

<h4>Drupal Auto Compelte</h4>
  <p>To use the  Drupal Auto Complete, you need to create a SublimeProject and save the project definition at the drupal document root where index.php is located</p>

<h2>Key Binding</h2>

<ul>
  <li>CTRL + Shift + t: Delete the trailing spaces</li>
  <li>CTRL + Shift + f: Reindent selected code</li>
  <li>Super + Shift + a: Go to Drupal Api definition of selected function</li>
  <li>Super + Shift + h: Go to documentation of selected function for languages PHP/JS and others</li>
  <li>Super + b: Validate Drupal Code Standard in current file</li>
  <li>Super + Shift + e</li>

</ul>

<p>Super Key stands for Command in Mac and Windows Key in Windows</p>

<p>Orginally forked from <a href="https://github.com/phase2/sublime-drupal/">https://github.com/phase2/sublime-drupal/</a></p>
