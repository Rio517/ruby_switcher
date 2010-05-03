#Ruby Switcher

This is a dedicated repo for the ruby_switcher originally put together by the team over at http://thinkrelavance.com

Learn more: [Relevance Blog](http://blog.thinkrelevance.com/2009/7/29/ruby-switcher-working-with-multiple-ruby-versions-has-never-been-this-easy)

###Prerequisites

Ubuntu: `sudo apt-get update && sudo apt-get install build-essential zlib1g-dev libreadline5-dev libssl-dev`

OS X: [Xcode](http://developer.apple.com/technology/Xcode.html)

###Download
    cd
    curl -O -L http://github.com/Rio517/etc/raw/master/bash/ruby_switcher.sh
    echo "source ~/ruby_switcher.sh" >> .bash_profile (or .bashrc in ubuntu)
    source .bash_profile  (or .bashrc in ubuntu)

#Usage

<table>
  <tr>
    <th>Install It</th>
    <th>Use It</th>
  </tr>
  <tr>
    <td>[default on 0S X]</td>
    <td>use_leopard_ruby</td>
  </tr>
  <tr>
    <td>install_ruby_186</td>
    <td>use_ruby_186</td>
  </tr>
  <tr>
    <td>install_ree_186</td>
    <td>use_ree_186</td>
  </tr>
<tr>
    <td>install_ree_187</td>
    <td>use_ree_187</td>
  </tr>
  <tr>
    <td>install_ruby_187</td>
    <td>use_ruby_187</td>
  </tr>
  <tr>
    <td>install_ruby_191</td>
    <td>use_ruby_191</td>
  </tr>
  <tr>
    <td>install_jruby*</td>
    <td>use_jruby*</td>
  </tr>
  <tr>
    <td>install_jruby_120</td>
    <td>use_jruby_120</td>
  </tr>
</table>


*On Ubuntu you will need: `sudo apt-get update && sudo apt-get install sun-java6-jre sun-java6-jdk` before installing
