# Gemfile
source "https://rubygems.org"

# Platform helpers
def windows_only(require_as)
  RbConfig::CONFIG['host_os'] =~ /mingw|mswin/i ? require_as : false
end
def linux_only(require_as)
  RbConfig::CONFIG['host_os'] =~ /linux/ ? require_as : false
end
def darwin_only(require_as)
  RbConfig::CONFIG['host_os'] =~ /darwin/ ? require_as : false
end
 
# GEMS
gem 'awestruct', '~> 0.5.4.rc3'
gem 'slim', '~> 2.0.0'
gem 'kramdown', '~> 1.0.1'
gem 'asciidoctor', '~> 1.5.0.preview6'
gem 'uglifier', '~> 2.0.1'
gem 'htmlcompressor', '~> 0.0.6'
gem "zurb-foundation", "~> 4.3.1"
gem 'aweplug', :github => 'awestruct/aweplug'
gem 'curb', '~> 0.8.5'
gem 'oauth', '~> 0.3.6'
gem 'git', '~> 1.2.5'
gem 'oily_png', '~> 1.1.1'
gem 'nokogiri', '~> 1.5.10'
gem 'therubyracer', :platforms => :ruby, :require => linux_only('therubyracer')
#gem 'aweplug', :path => '~/projects/ruby/aweplug'
#gem 'aweplug', :path => '../aweplug'

group :development do
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', :require => false
  gem 'rb-fchange', :require => false
  gem 'rake', '~> 10.0.4'
  gem 'pry', :require => false
  #gem 'pry-nav', :require => false
  #gem 'pry-stack_explorer', :require => false
  #gem 'pry-exception_explorer', :require => false
end

