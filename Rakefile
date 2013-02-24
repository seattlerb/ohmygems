# -*- ruby -*-

require "rubygems"
require "hoe"

Hoe.plugin :seattlerb

Hoe.spec "ohmygems" do
  developer "Ryan Davis", "ryand-ruby@zenspider.com"

  license "MIT"

  self.version = "1.1.0"

  self.post_install_message = <<-"EOM"

    Add the following to your ~/.bashrc or equivalent:

      source $(gem env gemdir)/gems/ohmygems-#{self.version}/ohmygems

  EOM
end

# vim: syntax=ruby
