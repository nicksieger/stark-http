# -*- ruby -*-

require 'rubygems'
require 'hoe'

# Don't turn on warnings, output is very ugly w/ generated code
Hoe::RUBY_FLAGS.sub! /-w/, ''

Hoe.plugin :gemspec

Hoe.spec 'stark-http' do
  developer('Evan Phoenix', 'evan@phx.io')
  dependency 'stark', '< 2.0.0'
  readme_file = "README.md"
end

# vim: syntax=ruby
