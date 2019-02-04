source 'https://rubygems.org'

gemspec

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)

gem 'xctest_list', git: 'https://github.com/lyndsey-ferguson/xctest_list.git', branch: 'issue-4-support-xcode8'