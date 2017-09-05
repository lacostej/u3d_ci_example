source 'https://rubygems.org'

gem 'fastlane'
gem 'u3d', :git => 'https://github.com/lacostej/u3d', :branch => 'sudo_passwordless'
gem 'rake'
plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
# rubocop:disable Eval
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
# rubocop:enable Eval
